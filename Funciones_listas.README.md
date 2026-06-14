[funciones_listas.py](https://github.com/user-attachments/files/28934147/funciones_listas.py)
"""  
 List (Array)
 son colleciones o conjunto de datos/valores bajo un mismo nombre, para acceder a los valores se hace con un indice numerico 

 Nota: sus valores si son modificables

 La lista es una colección ordenada y modificable. Permite miembros duplicados.

"""


#Funciones más comunes en las listas
print("\033c")

paises = ["Mexico", "USA", "Canada"]
numeros = [1,2,3,4]

varios = ["Hola", 3.1416, 33, True]

vacia = []

#Imprimir el contenido de una lista
print(paises)
print(numeros)
print(varios)
print(vacia)

# Recorrer la lista
# 1er forma
for i in paises:
    print(i)

# 2da forma 
for i in range(0,4):
    print(paises[i])

# Ordenar elementos de una lista
paises = ["Mexico", "Canada", "EUA", "Mexico", "Brasil"]
print(paises)
paises.sort()
print(paises)

# Dar la vuelta a una lista
paises.reverse()
print(paises)

# Agregar, insertar, añadir un elemento a una lista 
# 1er forma
paises.apped("Honduras")
print(paises)

# 2da forma
paises.insert(1,"Colombia")
print(paises)
paises.insert(8,"Australia")
print(paises)

# Eliminar, borrar, suprimir, un elemento de una lista
# 1er forma
paises.pop(2)
print(paises)

# 2da forma
paises.remove("Brasil")
print(paises)

# Buscra un elemento dentro de la lista
if "Mexico" in paises:
    print("La respuesta es True")
else:
    print("La respuesta es False")

# Contar numeros de veces que aparece en un elemento dentro de una lista 
numeros = [23, 45, 8, 24, 100, 200, 0, -1,-10, 23, 24, 8, 23, 50]
print(numeros)
num = int(input("Dame un numero: "))
cuantos = numeros.count(num)
print(f"El numero de veces que aparece el {num} es: {cuantos}")

#Conocer la posicion o indice en el que se encuentra un elemento de la lista
posicion = numeros.index(23)
print(f"La posicion del numero es: {posicion}")

# Unir el contenido de una lista dentro de otra lista
numeros = [23, 45, 8, 24, 100, 200, 0, -1, -10, 23, 24, 8, 23, 50]
print(numeros) 
numeros2 = [500, 1000]
print(numeros2)
numeros.extend(numeros2)
print(numeros)  

# Crear apartir de las listas de numeros 1 y 2 un resultante y mostrar el contenido descendente 
numeros.sort()
numeros.reverse()
print(numeros)

# Buscar un elemento de la lista 
if "Brasil" in paises:
    print("La respuesta es True")
else:
    print(f"La respuesta es False")

# Contar el numero de veces que aparece un elemento dentro de una lista
numeros = [23, 45, 8, 24, 100, 200, 0, -1, -10, 23, 24, 8, 23, 50]
print(numeros)
num = int(input("Dame un numero: "))
cuantos = numeros.count(num)
print(f"El numero de veces que aparece el {num} es: {cuantos}")




