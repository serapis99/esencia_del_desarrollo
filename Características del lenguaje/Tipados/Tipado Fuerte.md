---
tags:
  - Definicion
---
# Tipado Fuerte

## Definición 

Cuando hablo de tipado fuerte me refiero a que las operaciones con tipos incompatibles se debe hacer una conversión de tipos para que sea compatibles de lo contrario saldrá un error.
## Ejemplo

```java

/* el editor nos indicaria que hay error de tipos 
o en caso que funcione nos dara false ya que los tipos no son iguales*/

if (1=='1'){
	System.out.println("true");
}else{
	System.out.println("false");
}

/* para hacer la comparacion se debe convertir alguno de 
los dos lados del igual para que sean del mismo tipo asi ya nos da true */

if (Integer.parseInt("1")==1){
	System.out.println("true");
}else{
	System.out.println("false");
}

```

## Lenguajes

+ [[Python]]
+ [[Dart]]
+ [[Java]]
+ [[kotlin]]
+ [[C Sharp]]
+ [[C ++]]
+ [[Golang]]
+ [[Rust]]