# Practica-5-Booleanos
print(" ")
print("Angel Andrey Muñoz Centeno 3W: Booleanos")
print(" ")
print("¡Bienvenido al programa de operaciones booleanas!")

# Ingreso de valores booleanos
first_value = input("Valor 1 (True/False): ").strip().lower() == 'true'
second_value = input("Valor 2 (True/False): ").strip().lower() == 'true'

# Menú de operaciones
while True:
    print("\n1. AND (y)")
    print("2. OR (o)")
    print("3. NOT (no) del primer valor")
    print("4. NOT (no) del segundo valor")
    print("5. Comparar igualdad")
    print("6. Salir")

    choice = input("Elige una opción (1-6): ")

    if choice == '1':
        print(f"Resultado de AND: {first_value and second_value}")
    elif choice == '2':
        print(f"Resultado de OR: {first_value or second_value}")
    elif choice == '3':
        print(f"Resultado de NOT del primer valor: {not first_value}")
    elif choice == '4':
        print(f"Resultado de NOT del segundo valor: {not second_value}")
    elif choice == '5':
        print(f"¿Son iguales? {first_value == second_value}")
    elif choice == '6':
        print("¡Hasta luego!")
        break
    else:
        print("Opción no válida.")
        ![image](https://github.com/user-attachments/assets/fd68b419-5eec-4771-83e1-716b3cbfdff2)
