# proyecto_python
Calculadora básica hecha en Python como práctica de programación.

import os  # Missing module docstring
os.system("cls")
# Definimos las funciones de la calculadora
def sumar(a, b):  # Missing function or method docstring
    return a + b

def restar(a, b):  # Missing function or method docstring
    return a - b

def multiplicar(a, b):  # Missing function or method docstring
    return a * b

def dividir(a, b):  # Missing function or method docstring
    if b == 0:
        return "Error: No se puede dividir entre 0"
    return a / b

# Programa principal
while True:
    print("\nOpciones:")
    print("1. Sumar")
    print("2. Restar")
    print("3. Multiplicar")
    print("4. Dividir")
    print("5. Salir")

    opcion = input("Elige una opción (1/2/3/4/5): ")

    if opcion == "5":
        print("¡Byee! :3 🩷")
        break

    num1 = float(input("Ingresa el primer número: "))
    num2 = float(input("Ingresa el segundo número: "))

    if opcion == "1":
        print(f"Resultado: {sumar(num1, num2)}")
    elif opcion == "2":
        print(f"Resultado: {restar(num1, num2)}")
    elif opcion == "3":
        print(f"Resultado: {multiplicar(num1, num2)}")
    elif opcion == "4":
        print(f"Resultado: {dividir(num1, num2)}")
    else:
        print("Opción no válida. Intenta de nuevo.")
