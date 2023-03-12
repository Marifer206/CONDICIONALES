# CONDICIONALES
### RETO 5

# CODE #1
Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
```ruby
n: int
n = int(input("Ingrese un número entero:"))

if n >= 97 and n <= 122:
    print("El número " + str(n)+ " corresponde a una vocal minúscula.")
else:
    print("El número " + str(n)+ " No corresponde a una vocal minúscula.")
```
## CODE #1 CORRIDO PARA UN NUMERO QUE CORRESPONDA A UNA VOCAL MINUSCULA
[![image.png](https://i.postimg.cc/MGPyhf63/image.png)](https://postimg.cc/06SMSQJ7)
## CODE #1 CORRIDO PARA UN NUMERO QUE NO CORRESPONDA A UNA VOCAL MINUSCULA
[![image.png](https://i.postimg.cc/WzRJvMQ8/image.png)](https://postimg.cc/ZBcqPyYv)


# CODE #2
Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
```ruby
n = (input("Ingrese una cadena de longitud 1:"))
numero_ascii_de_n= ord(n)

if numero_ascii_de_n%2 == 0:
    print(" El codigo ASCII de " + str(n)+ " corresponde a un numero par.")
else:
    print(" El codigo ASCII de " + str(n)+ " corresponde a un numero impar.")
```
## CODE #2 CORRIDO PARA UN CODIGO DE ASCII QUE ES PAR
![image](https://user-images.githubusercontent.com/124616296/224579928-5a0911ea-2154-4766-a14d-8925874ec88c.png)
## CODE #2 CORRIDO PARA UN CODIGO DE ASCII QUE ES IMPAR
[![image.png](https://i.postimg.cc/GmswBGNG/image.png)](https://postimg.cc/VJ1Hprzk)


# CODE #3
Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

## CODE #3.1
El codigo es para determinar si es un digito en el conjunto de los numeros
```ruby
n = int(input("Ingrese un caracter "))
if  n>=0 and n<=9:
    print( " El caracter " + str(n) + " es un digito")
else:
    print( "el caracter " + str(n) + " no es un digito")
```
### CODE #3.1 CORRIDO PARA UN NUMERO QUE ES DIGITO     
[![image.png](https://i.postimg.cc/j53ZQkn5/image.png)](https://postimg.cc/2bvQCGwR)   
### CODE #3.1 CORRIDO PARA UN NUMERO QUE NO ES DIGITO 
[![image.png](https://i.postimg.cc/wxWS0wYD/image.png)](https://postimg.cc/3WvSwCRw)

## CODE #3.2
El codigo es para determinar si es un digitu en el codigo ASCII
```ruby
caracter = input("Ingrese un carácter de ASCII: ")

if ord(caracter) >= 48 and ord(caracter) <= 57:
    print("El carácter " + str(caracter)+ " ingresado es un dígito.")
else:
    print("El carácter " + str(caracter)+ " ingresado no es un dígito.")
```

### CODE #3.2 CORRIDO PARA UN NUMERO QUE ES DIGITO EN ASCII  
[![image.png](https://i.postimg.cc/DwKkX8KN/image.png)](https://postimg.cc/RNGDrCh1)
### CODE #3.2 CORRIDO PARA UN NUMERO QUE NO ES DIGITO EN ASCII
[![image.png](https://i.postimg.cc/8PfNv2f7/image.png)](https://postimg.cc/crWpy5mW)


# CODE #4
Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:
Positivo: "El número x es positivo"
Negativo: "El número x es negativo"
Cero (0): "El número x es el neutro para la suma"

```ruby
n : float
n = float(input("Ingrese un numero: "))
if n == 0:
    print("El numero "+str(n) + " es el neutro para la suma ")
else:
    if n > 0:
         print(" El numero "+str(n)+ " es positivo")
    else:
         print("El numero"+ str(n)+ " es negativo")
```
### CODE #4 CORRIDO PARA UN NUMERO QUE ES POSITIVO  
[![image.png](https://i.postimg.cc/qMwSzQjN/image.png)](https://postimg.cc/vc13K7Ry)
### CODE #4 CORRIDO PARA UN NUMERO QUE NEGATIVO
![image](https://user-images.githubusercontent.com/124616296/224581007-f6631b3c-9a3a-41aa-905c-c84b0b5e3480.png)
### CODE #4 CORRIDO PARA UN NUMERO QUE ES NEUTRO PARA LA SUMA
[![image.png](https://i.postimg.cc/SsLVHNPn/image.png)](https://postimg.cc/FdRjLmNv)


# CODE #5
Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
```ruby

```
# CODE #6
Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
```ruby

```
