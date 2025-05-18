# Reto-4 ejercicios de código

## Aquí en NoteBook: https://colab.research.google.com/drive/15-b6MjAlNv3TNnmkP2_7lKPUBz98zmeN?usp=sharing 

### 1. Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
- a = 97
- e = 101
- i = 105
- o = 111
- u = 117
  
```python
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

### 2. Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.

```python
Caracter = input("Ingrese UNA SOLA letra: ")
codigo = ord(Caracter)
if codigo % 2 == 0:
  print("El codigo ASCII de la letra es par")
  print( str(codigo))
else:
  print("El codigo ASCII de la letra es impar")
  print( str(codigo))
```

### 3. Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

```python
n = (input("Ingrese un caracter: "))
if n == '1' or n == '2' or n == '3' or n == '4' or n == '5' or n == '6' or n == '7' or n == '8' or n == '9' or n == '0':
  print("El caracter es un digito")
else:
  print("El caracter no es un digito")
```

### 4. Realice un programa que lea dos números reales y determine si el primero es múltiplo del segundo.

```python
x = float(input("Escriba el primer número: "))
y = float(input("Escriba el segundo número: "))
if x % y == 0:
  print("El primer numero si es multiplo del segundo")
else:
  print("El primer numero no es multiplo del segundo")
```

### 5. Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:
- Positivo: "El número x es positivo"
- Negativo: "El número x es negativo"
- Cero (0): "El número x es el neutro para la suma"

```python
n = float(input("Ingrese un número: "))
if n > 0:
  print("El número " + str(n) + " es positivo")
elif n == 0:
  print("El número " + str(n) +" es neutro para la suma")
elif n < 0:
  print("El número " + str(n) + " es negativo")
```

### 6. Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.

```python
cx = float(input("Cordenada x del centro del circulo: "))
cy = float(input("Cordenada y del centro del circulo: "))
r = float(input("Radio del circulo: "))
x = float(input("Cordenada x del punto: "))
y = float(input("Cordenada y del punto: "))
if (x-cx)**2 + (y-cy)**2 <= r**2:
  print("El punto " + str((x , y)) + " esta dentro del circulo")
elif (x-cx)**2 + (y-cy)**2 > r**2:
  print("El punto " + str((x , y)) + " esta fuera del circulo")
```

### 7. Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.

```python
a = float(input("Longitud 1: "))
b = float(input("Longitud 2: "))
c = float(input("Longitud 3: "))
if (a+b)>c and (a+c)>b and (b+c)>a:
  print("Se puede construir un triángulo")
else:
  print("No se puede construir un triángulo")
```

### 8. Escriba un programa que reciba el nombre en minúsculas de un país de America y retorne la ciudad capital, si el país no pertenece al continente debe arrojar país no identificado (Utilice match-case).

```python
pais = str(input("Ingrese el nombre de un país de América en minúsculas: "))

match pais:
    case "antigua y barbuda":
        print("La capital es Saint John's.")
    case "argentina":
        print("La capital es Buenos Aires.")
    case "bahamas":
        print("La capital es Nassau.")
    case "barbados":
        print("La capital es Bridgetown.")
    case "belice":
        print("La capital es Belmopán.")
    case "bolivia":
        print("La capital es Sucre")
    case "brasil":
        print("La capital es Brasilia.")
    case "canada":
        print("La capital es Ottawa.")
    case "chile":
        print("La capital es Santiago.")
    case "colombia":
        print("La capital es Bogotá.")
    case "costa rica":
        print("La capital es San José.")
    case "cuba":
        print("La capital es La Habana.")
    case "dominica":
        print("La capital es Roseau.")
    case "ecuador":
        print("La capital es Quito.")
    case "el salvador":
        print("La capital es San Salvador.")
    case "granada":
        print("La capital es Saint George's.")
    case "guatemala":
        print("La capital es Ciudad de Guatemala.")
    case "guyana":
        print("La capital es Georgetown.")
    case "haiti":
        print("La capital es Puerto Príncipe.")
    case "honduras":
        print("La capital es Tegucigalpa.")
    case "jamaica":
        print("La capital es Kingston.")
    case "mexico":
        print("La capital es Ciudad de México.")
    case "nicaragua":
        print("La capital es Managua.")
    case "panama":
        print("La capital es Ciudad de Panamá.")
    case "paraguay":
        print("La capital es Asunción.")
    case "peru":
        print("La capital es Lima.")
    case "republica dominicana":
        print("La capital es Santo Domingo.")
    case "san cristobal y nieves":
        print("La capital es Basseterre.")
    case "san vicente y las granadinas":
        print("La capital es Kingstown.")
    case "santa lucia":
        print("La capital es Castries.")
    case "surinam":
        print("La capital es Paramaribo.")
    case "trinidad y tobago":
        print("La capital es Puerto España.")
    case "uruguay":
        print("La capital es Montevideo.")
    case "estados unidos":
        print("La capital es Washington D.C.")
    case "venezuela":
        print("La capital es Caracas.")
    case _:
        print("País no identificado.")
```

## Gracias.
![image](https://github.com/user-attachments/assets/a192337a-3d45-457e-835d-0061760ad00a)
