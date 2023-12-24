# punto-2-trabajo-diciembre
#Centro de salud de campuslands
#Este programa le permite al usuario ingresar su nombre, edad, IMC y la categoria 
Nombre_E = input("Ingrese su nombre: ")
Edad_E = int(input("Ingrese su edad: ")) 
Peso_E = float(input("Ingrese su peso en kilogramos: "))
Altura_E = float(input("Ingrese su altura en metros: "))
Altura_E_2 = (Altura_E * Altura_E) 
IMC_E = (Peso_E / Altura_E_2) 
#Categorias
if IMC_E <= 24.9:
  print("su categoria es normal")
elif IMC_E <= 29.9: 
  print("su categoria es sobrepeso")
elif IMC_E <= 34.9:
  print("su caetgoria es obesidad grado 1")
elif IMC_E <= 39.9: 
  print("su categria es obesidad grado 2")
elif IMC_E >= 40:
  print("su categoria es obesidad grado 3")
else: 
  print("Error no entra en ninguna categoria")
#Fin
