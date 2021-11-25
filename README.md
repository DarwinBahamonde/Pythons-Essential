@author: darvids
"""
print("Darwin Bahamonde")
print(" ")
print("PARTE 1")
print("El tipo de dato 875 es ")
print(type(875)) #int#
print("El tipo de dato 4.89 es ")
print(type(4.89)) #float#
print("El tipo de dato 85.5 es ")
print(type(85.5)) #float#
print("El tipo de dato Now is better tha never. es ")
print(type("Now is better tha never.")) #str#
print("El tipo de dato 1.32 es ")
print(type(1.32)) #float#
print("El tipo de dato 5 + 8j es ")
print(type(5 + 8j))#complex#
print("El tipo de dato 8.2 es ")
print(type(8.2)) #float#
print("El tipo de dato Readability counts. corresponde a un string? es ")
print(type("Readability counts. corresponde a un string?")) #str#
print(" ")
print("PARTE 2")
print("Programa que identifica el tipo de dato de un valor ingresado por el usuario, se realizarán cinco")

numero = 0

while numero <= 4:
    numero = numero + 1
    print("Ingreso un valor cualquiera:")
    variable=input()
    print(type(variable))
 
print("")    
print("no hay mas interacciones")    
