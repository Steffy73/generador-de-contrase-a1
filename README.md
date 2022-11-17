# generador-de-contrase-a1

from random import *
print("BIENVENIDOS A TU GENERADOR DE CONTRASEÑA")

number = input("ingrese cantidad de contraseña: ")
number = int(number) 



length = input("ingrese longitud de contraseña: ")
length = int(length)

print ("AQUI ESTAN SUS CONTRASEÑAS:")


letra=choice(["A","B","C","D","E","F","G","H","I","J","K","L","M","N","Ñ","O","P","Q","R","S","T","U","W","X","Y","Z"])
letras=choice(["a","b","c","d","e","f","g","h","i","j","k","l","m","n","ñ","o","p","q","r","s","t","u","v","w","x","y","z"])
number1=choice(["1","2","3","4","5","6","7","8","9","#","$"])


#print(letra + letras + number1)

print
