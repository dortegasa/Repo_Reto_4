# Repo_Reto_4
En este repositorio tratare de dar una respuesta acertada a los problemas planteados en el reto 4

Pseudocodigo Primos:

```pseudocode
Algoritmo Primos_hasta_n
	Definir X Como Entero
	Definir n Como Entero
	Definir P Como Entero
	Definir Z Como Entero
	X <- 1
	P <- 1
	Z <- 0
	Leer n
	Mientras X<=n Hacer
		Mientras P<=X Hacer
			Si X MOD P=0 Entonces
				Z <- Z+1
			FinSi
			P <- P+1
		FinMientras
		P <- 1
		Si Z>2 Entonces
			Escribir X,' no es primo.'
		SiNo
			Escribir X,' es primo.'
		FinSi
		Z <- 0
		X <- X+1
	FinMientras
FinAlgoritmo

```
Diagrama de flujo:

![flujo2](https://user-images.githubusercontent.com/124607864/221447985-af8838fc-91f5-413d-8bca-a5460a19bc8a.png)


Psseudocodigo 2:
```pseudocode
Algoritmo HallarRaizCuadrada
	Escribir 'Ingresa el numero al cual se le hallara la raiz:' Sin Saltar
	Leer a
	Si numero>=0 Entonces
		raiz_cuadrada <- RC(a)
	SiNo
		raiz_cuadrada <- RC(-a)
		Escribir 'raíz i'
	FinSi
	Escribir 'Valor de raiz cuadrada: ',raiz_cuadrada
FinAlgoritmo

```

Diagrma de flujo:

![sin_titulo](https://user-images.githubusercontent.com/124607864/221449838-9d545574-8219-4c5e-a3d7-80040503f741.png)
