module Main where

filtrarIntervalo :: Ord a => [a] -> a -> a -> [a]
filtrarIntervalo [] _ _ = []
filtrarIntervalo (x:xs) a b
  | x >= bajo && x <= alto = x : filtrarIntervalo xs a b
  | otherwise              = filtrarIntervalo xs a b
  where
    bajo = min a b
    alto = max a b

ordenarDesc :: Ord a => [a] -> [a]
ordenarDesc [] = []
ordenarDesc (x:xs) = insertar x (ordenarDesc xs)

insertar :: Ord a => a -> [a] -> [a]
insertar x [] = [x]
insertar x (y:ys)
  | x >= y    = x : y : ys
  | otherwise = y : insertar x ys

main :: IO ()
main = do
  print (filtrarIntervalo [1,25,5,-4] 0 5)
  print (ordenarDesc [1,25,5,-4])
