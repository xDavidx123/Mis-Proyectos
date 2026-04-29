# Mis-Proyectos
Aquí pondré los programas en los que trabajo
Funciones de lista en haskell
main = do
  let numeros = [1, 2, 3, 4, 5, 6]
  putStrLn ("El primer elementode la lista es: " ++ show(head numeros))
  putStrLn ("La lista sin el primer elemento es: "++ show(tail numeros))
  putStrLn ("El ultimo elemento de la lista es: "++ show(last numeros))
  putStrLn ("La lista sin el ultimo elemento es: "++ show(init numeros))
  putStrLn ("La cantidad de lista se: "++ show(length numeros))
  putStrLn ("¿La lista esta vacia?: "++ show(null numeros))
  putStrLn ("Lista al revez: "++ show(reverse numeros))
  putStrLn ("Valor maximo en la lista: "++ show(maximum numeros))
  putStrLn ("El valor que pido es mayor que 4:"++ show(filter(>4)numeros))
  putStrLn ("El valor que pido es par:"++ show(filter(even)numeros))
  putStrLn ("El valor que pido es impar:"++ show(filter(odd)numeros))
  putStrLn ("Quiero este valor: "++ show(numeros!!5))
  putStrLn(show numeros)
