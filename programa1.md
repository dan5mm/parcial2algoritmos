def calcular_promedio(a, b, c):
    promedio = (a + b + c) / 3
    return promedio
    
numero1 = int(input("Ingrese el primer número entero: "))
numero2 = int(input("Ingrese el segundo número entero: "))
numero3 = int(input("Ingrese el tercer número entero: "))

promedio_resultante = calcular_promedio(numero1, numero2, numero3)
print("El promedio de los tres números es:", promedio_resultante)
