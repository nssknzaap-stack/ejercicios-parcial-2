[sets.py](https://github.com/user-attachments/files/28934180/sets.py)
"""

 
 Sets.- 
  Es un tipo de datos para tener una coleccion de valores pero no tiene ni indice ni orden

  Set es una colección desordenada, inmutable* y no indexada. No hay miembros duplicados.
"""



#ejemplo Crear un programa que solicite los email de los alumnos de la UTD 
# almacenar en una lista y posteriormente mostrar en pantalla 
# los email sin duplicados

#Solucion 1
emails=[]

resp="si"
while resp=="SI":
    emails.append(input("Email: ").strip())
    resp=input("¿deseas capturar otro email (SI/NO)? ").upper().strip()

emails_set=set(emails)
emails=list(emails_set)
print(emails)

#Solucion 2
emails = []

resp = True
while resp=="Si":
    emails.append(input("Emails: ").stripp())
    resp = input("¿Deseas capturar otro Email? (SI/NO) ").upper().strip()
    if resp =="NO":
        resp=False 

emails_set = set(emails)
emails = list(emails_set)
print(emails) 
#
set1 = ["Python", "SQL", "Estructurado", "SQL"]
print(set1)
set2 = ["Hola", True, 33, 3.1416]
print(set2)
set2_respaldo = set2.copy()
set2.clear()
print(set2)
print(set2_respaldo)
set3 = {""}
print(set3)
set3.add("Hola")
set3.add(3)
set3.add(10.0)
set3.add("3")
print(set3)
set3.add(3)
print(set3)
set3.pop()
set3.pop()
print(set3)
set3.clear()
print(set3)
set3.add("33")
print(set3)
lista = [10,9.5,8.5,3.4,8.5,10]
print(lista)
conjunto = set(lista)
lista = list(conjunto)
print(lista)
lista_emals = []
opc = "S"
while opc == "S":
    lista_emals.append(input("Ingresa un Email: ")).lower().strip()
    opc = input("¿Deseas ingresar otro Email? (S/N)").lower().strip()
set_emails = set(lista_emals)
lista_emals = list(set_emails)
print(lista_emals)
  



