# Reto-4 ejercicios de código

1. Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
a = 97
e = 101
i = 105
o = 111
u = 117
```
n : int
a = 97
e = 101
i = 105
o = 111
u = 117
n = int(input("Ingrese un numero entero: "))
if n == a:
 print("El numero ingresado corresponde al codigo ASCII de la vocal minuscula a")
elif n == e:
 print("El numero ingresado corresponde al codigo ASCII de la vocal minuscula e")
elif n == i:
 print("El numero ingresado corresponde al codigo ASCII de la vocal minuscula i")
elif n == o:
 print("El numero ingresado corresponde al codigo ASCII de la vocal minuscula o")
elif n == u:
 print("El numero ingresado corresponde al codigo ASCII de la vocal minuscula u")
else:
 print("El numero ingresado no corresponde al codigo ASCII de una vocal minuscula")
```
