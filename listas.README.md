[listas.py](https://github.com/user-attachments/files/28934173/listas.py)[Uploading listas.pyprint("\033c")

#Ejemplo 1 Crear una lista de numeros e imprimir el contenido
numeros=[10,34,25,45]

print(numeros)

lista="["
for i in numeros:
    lista+=f"{i}, "
    print(f"{lista}]")

lista="["
for i in range(0, len(numeros)):
    lista+=f"{numeros[i]}, "
    print(f"{lista}]")


# ahora sustitullendo for por while
lista = "["
i = 0
while i < len(numeros):
    lista += f"{numeros[i]}, "
    print(f"{lista}]")
    i += 1
    

#Ejemplo 2 Crear una lista de palabras y posteriormente buscar la coincidencia de una palabra 
#1er forma
palabras=["UTD","SEGUNDO","TI","MTI"]
palabra=input("dame una palabra a buscar").strip()

if palabra in palabras: 
    print("encontre la palbra en la lista")
else:
    print("NO se encontro la palabra en la lista")

# 2da forma
true = "Si"
while true == "Si":
    dato = input("Ingrese un valor a la lista: ").strip().upper()
    lista.append(dato)
    true = input("¿Deseas añadir mas elementos a la lista? (Si/No)").lower().strip()

print(lista)

# Ejemplo 4: Crear una lista multidimensional que permita almacenar el nombre y telefono
# de una agenda
agenda=[ 
    ["Carlos", "6181234567"],
    ["Alberto", "6182344567"],
    ["Martin", "6181231223"],
    ]
print(agenda)

for i in agenda:
    print(i)

for c in range(0,2):
    for r in range(0.3):
        print(agenda[r],[c])

lista = ""
for r in range(0,3):
    for c in range(0,2):
        lista += f"{agenda[r][c]}, "
    lista += "\n"
print("["+lista+"]")

…]()
