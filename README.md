# NETConfTDD

TDD (Test Driven Development)

Vamos a convertir números arábigos a romanos.

## Creémos el proyecto

En linux:

1. `mkdir NETConfTDD`
2. `cd NETConfTDD`
3. `dotnet new sln --name=NETConfTDD`
4. `dotnet new classlib --name=NETConfTDD`
5. `dotnet new mstest --name='NETConfTDD.Tests'`
6. `dotnet add "NETConfTDD.Tests/NETConfTDD.Tests.csproj" reference "NETConfTDD/NETConfTDD.csproj"`
7. `dotnet sln NETConfTDD.sln add 'NETConfTDD.Tests/NETConfTDD.Tests.csproj' 'NETConfTDD/NETConfTDD.csproj'`

![alt text](http://iwt2.org/wp-content/uploads/2015/06/tdd-logo-300x235.png)

## Ciclo TDD

1. ¡Pensar!
2. Escribir una prueba que compile, pero no pase (Rojo).
3. ¡Pensar si la prueba que escribimos tiene sentido!
4. Escribir LA MÍNIMA CANTIDAD DE CÓDIGO necesaria para que la prueba pase (Verde).
5. Refactorizar, es decir, limpiar el código escrito SIN AÑADIR NUEVA FUNCIONALIDAD (Azul).
6. Volver a empezar el ciclo.

## Partes de los tests

Vamos a utilizar el patrón AAA para seccionar los casos de pruebas:

1. **Arrange (Preparación):** Donde creamos los objetos necesarios para ejecutar el caso de pruebas.
2. **Act (Ejecución):** Donde se ejecuta el SUT (Software under Test), es decir el método que vamos a probar.
3. **Assert (Acertar):** Donde verificamos el resultado esperado del caso de pruebas.


### Primer paso
Pensar en la mínima funcionalidad posible para resolver los números romanos.
### Segundo paso
Podrán encontrar la primera prueba en RomanNumeralsTests.cs.
### Tercer paso
Ya pensé que resolver el 1 es el caso más sencillo que da inicio al problema.
### Cuarto paso

**Por favor escriban dentro del método ArabicToRoman el MÍNIMO CÓDIGO NECESARIO para pasar la primera prueba.**

### Quinto paso
Refactorizamos, si podemos.

### Por hacer:
Generen las pruebas y sus correspondientes implementaciones para los siguientes casos:

* ` public void WhenInputIs2ThenShouldReturnII()`

* `public void WhenInputIs3ThenShouldReturnIII()`

[Step 1 solution](https://github.com/luisfelipediaz/NETConfTDD/tree/Step1)
