[tuple.py](https://github.com/user-attachments/files/28934187/tuple.py)

# Las tuplas se utilizan para almacenar varios elementos en una sola variable.
# Una tupla es una coleccion ordenada e inmutable.
# Las tuplas se escriben entre parentesis.

print("\033c")
paises1=("Mexico","Italia","Honduras","Mexico")



for i in paises1:
    print(i)
  
for i in range(0,len(paises1)):
    print(paises1[i])
  
i=0
while i< len(paises1):
   print(paises1[i])
   i+=1
  
paises1=("Mexico","Italia","Honduras","Mexico")
varios=("Mexico",True,3,3.1416)
print(paises1)
paises1[1]="Brasil" #no se puede 

print(f"Los paises que NO clasificaron al mundial 2026 son: {paises1[1]} y {paises1[2]} ")

cuantos=paises1.count("Brasil")
print(cuantos)

posicion=paises1.index("Italia")
print(posicion)

# parte 2
paises=["México","Brasil","Canada","España"]

pais1={
        "nombre":"México",
        "capital":"CDMX",
        "poblacion":12000000,
        "idioma":"español",
        "status":True
      }

pais2={
        "nombre":"Brasil",
        "capital":"Brasilia",
        "poblacion":14000000,
        "idioma":"portugues",
        "status":True
      }

pais3={
        "nombre":"Canada",
        "capital":"Otawua",
        "poblacion":10000000,
        "idioma":["ingles","frances"],
        "status":True
      }

print(pais1)

for i in pais1:
    print(f"{i}={pais1[i]}")

#Agregar un atributo a un objeto
pais1["altitud"]=3000
for i in pais1:
    print(f"{i}={pais1[i]}")

#Modificar un valor de un item o atributo que ya existe
pais1.update({"altitud":2500}) 
for i in pais1:
    print(f"{i}={pais1[i]}")

#Quitar el ultimo atributo de un objeto 
pais1.popitem() 
for i in pais1:
    print(f"{i}={pais1[i]}") 

#Quitar un atributo en especifico de un objeto 
pais1.pop("status") 
for i in pais1:
    print(f"{i}={pais1[i]}")

