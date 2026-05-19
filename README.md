#NEGOCIO DE VENTAS
estudiante = input("Ingrese nombre del estudiante:")
nota1 = float(input("Nota 1:"))
nota2 = float(input("Nota 2:"))
nota3 = float(input("Nota 3:"))

promedio = (nota1 + nota2 + nota3) /3
print("\nEstudiante:",estudiante)
print("\nSu promedio es:",promedio)

if promedio >= 3.0:
    print("Aprobo la materia")
else:
    print("Ha sido reprobado")
