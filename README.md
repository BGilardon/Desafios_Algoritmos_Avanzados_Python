# Desafíos Avanzados de Algoritmos - Soluciones en Python

## Descripción General

Este repositorio contiene una serie de ejercicios resueltos en el contexto de la materia **Técnica de Diseño de Algoritmos (Algoritmos 3)**. Los problemas cubren temas avanzados de algoritmos, incluyendo:

### Tecnicas de diseño de algoritmos
- **Backtracking**
  - `Argentina`: Algoritmo para determinar la mejor combinación de 5 atacantes y 5 defensores de un equipo de fútbol, maximizando las habilidades de ataque y luego defensa. Si hay empates, se utiliza un criterio lexicográfico para desempatar.
  
- **Programación Dinámica**
  - `Murcias Skyline`: Algoritmo para determinar si el perfil de edificios en la ciudad de Murcia es creciente o decreciente. La decisión se basa en comparar la longitud de la subsecuencia creciente más larga con la subsecuencia decreciente más larga, ambas calculadas en función del ancho de los edificios.
  - `ACORN`: Algoritmo para maximizar la cantidad de bellotas que una ardilla voladora llamada Jayjay puede recolectar mientras desciende por un bosque de robles. Jayjay puede elegir entre bajar por el tronco de un árbol o volar a otro, pero pierde altura en cada vuelo, lo que limita su capacidad de recolección.
  
- **Divide and Conquer**
  - `Equivalent Strings`: Algoritmo para determinar si dos cadenas de igual longitud son equivalentes según una definición especial de equivalencia. Las cadenas pueden ser iguales o pueden dividirse recursivamente en mitades donde las subsecuencias resultantes sean equivalentes bajo ciertas condiciones.

- **Algoritmos Greedy**
  - `Wine trading in Gergovia`: Algoritmo para calcular la cantidad mínima de trabajo necesaria para satisfacer las demandas de vino de los habitantes de Gergovia. Los habitantes viven en una calle en línea recta y pueden comprar o vender vino. El trabajo se mide por la distancia en unidades entre casas durante el transporte de vino.
  - `Swap Letters`: Algoritmo para transformar dos cadenas de igual longitud, compuestas solo por los caracteres 'a' y 'b', en cadenas idénticas mediante el mínimo número de intercambios entre posiciones correspondientes en las dos cadenas. Si es imposible lograrlo, el algoritmo lo indica.

### Problemas resueltos con Grafos
- **Recorrido sobre Grafos**
  - `The New Villa`: Algoritmo para ayudar a Mr. Black a llegar a su dormitorio, partiendo del pasillo y evitando habitaciones oscuras. El objetivo es encontrar el camino más corto mientras se asegura de que todas las luces terminen apagadas excepto la del dormitorio. Los pasos incluyen moverse entre habitaciones, encender y apagar luces, y cada acción cuenta como un paso.
  
- **Arbol Generador Minimo**
  - `Anti Brute Force Lock`: Algoritmo para calcular el número mínimo de rotaciones necesarias para desbloquear un candado de cuatro dígitos que tiene múltiples combinaciones de claves. El candado comienza en 0000 y puede ser desbloqueado en cualquier orden. Ademas hay un botón especial que permite saltar a una clave desbloqueada previamente. El objetivo es encontrar la secuencia de rotaciones mínima para desbloquear todas las claves.
  
- **Camino Minimo**
  - `Lift Hopping`: Algoritmo para encontrar el tiempo mínimo necesario para viajar desde el piso 0 hasta el piso objetivo k en un rascacielos utilizando varios ascensores. Cada ascensor tiene un tiempo de viaje fijo entre pisos y no todos los pisos son accesibles por todos los ascensores. Además, cambiar de ascensor en un piso común requiere 60 segundos. El objetivo es calcular el tiempo mínimo total, considerando las posibles transferencias entre ascensores.
  - `King`: Algoritmo para verificar si es posible construir una secuencia de enteros que cumpla con una serie de restricciones sobre la suma de ciertos subsecuencias. Dadas restricciones sobre si la suma de elementos en subsecuencias específicas debe ser mayor o menor que un valor dado, se desea determinar si existe una secuencia que satisfaga todas estas restricciones.

- **Flujo**
  - `Carpeta_11`: Algoritmo para determinar si es posible distribuir un número específico de camisetas entre los voluntarios de forma que cada uno reciba una camiseta que le quede bien. Hay seis tamaños de camisetas disponibles y cada voluntario tiene dos tamaños que le quedan bien. Se deben satisfacer todos los voluntarios, pero puede haber camisetas restantes si el número de camisetas no coincide con el número de voluntarios.

Todos los ejercicios están implementados en **Python 3**.

## Estructura del Repositorio

Cada ejercicio se encuentra en su propia carpeta. Dentro de cada carpeta, encontrarás el script Python que resuelve el problema, así como un archivo PDF o TXT con la descripción del problema.

## Instrucciones de Uso

Los scripts están diseñados para recibir un **input** específico, según lo explicado en los PDFs adjuntos, y devolver el **output** correspondiente con la solución al problema.

Para ejecutar un script, asegúrate de tener **Python 3** instalado (versión entre 3.5 y 3.11, dependiendo del ejercicio). Luego, simplemente corre el script en tu terminal:

```bash
python nombre_del_script.py < input.txt > output.txt
