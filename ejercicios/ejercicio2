num = int(input("Introduce un número: "))

divisores = []

for i in range(1, num + 1):
    if num % i == 0:
        divisores.append(i)

print("Los divisores de", num, "son:", divisores)
numero = int(input("Ingresa un número entero positivo: "))

if numero > 1:
    es_primo = True
    for i in range(2, int(numero/2)+1):
        if numero % i == 0:
            es_primo = False
        break
    if es_primo: 
        print("El número", numero, "es primo.")
    else:
        print("El número", numero, "no es primo.")
else:
  print("El número ingresado no es válido.")