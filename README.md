# PROYECTO1RA-OGITHUB

# Definir funciones para operaciones matemáticas
def suma(a, b):
    return a + b

def resta(a, b):
    return a - b

def multiplicacion(a, b):
    return a * b

def division(a, b):
    if b != 0:
        return a / b
    else:
        return "Error: No se puede dividir entre cero"

# Solicitar al usuario que ingrese los números y la operación deseada
num1 = float(input("Ingrese el primer número: "))
num2 = float(input("Ingrese el segundo número: "))
operacion = input("Ingrese la operación (+, -, *, /): ")

# Realizar la operación seleccionada
if operacion == '+':
    print("El resultado es:", suma(num1, num2))
elif operacion == '-':
    print("El resultado es:", resta(num1, num2))
elif operacion == '*':
    print("El resultado es:", multiplicacion(num1, num2))
elif operacion == '/':
    print("El resultado es:", division(num1, num2))
else:
    print("Operación no válida")

