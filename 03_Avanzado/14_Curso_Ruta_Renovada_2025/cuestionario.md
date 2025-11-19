1.
Todo sistema se basa en:

Petición, procesamiento y respuesta

2.
¿Qué es un programador?
Es quien resuelve problemas usando un lenguaje de programación
3.
¿Qué es variables variables?
Es lo que nos permite definir variables de forma dinámica
4.
¿Qué es Composer?
Es el sistema empleado para mantener un estándar profesional en nuestros proyectos web en PHP
5.
¿Qué es JSON?
Es un estándar usado para la transferencia de datos, siendo este muy legible y ligero
6.
¿Qué es la programación orientada a objetos?
Es un paradigma de programación, actualmente uno de los más populares.

7.
¿Cómo debemos abordar un proyecto?
Primero resolvemos el problema, luego organizo de manera coherente sin alterar el resultado.
8.
¿Qué es un objeto?
Es la instancia de una clase.
9.
¿Qué es la herencia?
Es unir mis propios métodos con los métodos de una clase padre.
10.
¿Qué es una interface?
Es un contrato que deben cumplir las clases al implementarlas.
11.
¿Qué tipo de dato debería usar si quiero guardar el nombre de una persona?
string
12.
¿Qué tipo de dato debería usar si quiero guardar la edad de una persona?
int
13.
¿Cuál es el operador que usamos en PHP para expresar exponenciación?
**
14.
¿Qué es la precedencia en un lenguaje de programación?
Es la forma en la que un lenguaje decide qué operación se debe ejecutar primero y qué operación se debe ejecutar después.
15.
¿Es obligatoria la etiqueta de cierre (?>) de PHP?

Es obligatoria únicamente si combinamos PHP con HTML. Si únicamente trabajamos con PHP, entonces no es obligatoria.
16.
Una buena forma de ver a los arreglos asociativos es como...
Listas que pueden contener información de cualquier cosa.
17.
¿Qué sucede si ponemos un `while(true)`?
El ciclo se repetirá de forma infinita, consumiendo recursos de mi computadora hasta que pare el programa manualmente.
18.
¿Cuál sería el resultado del siguiente código?

<?php
$contador = 0;

while($contador < 10) {
    echo $contador . "\n";
} 
Una lista del 0 al 9.
**REPASAR** 

19.
¿Cómo programarías una función para multiplicar dos números, pero que el segundo número por defecto es 1?
<?php

function multiplicar($numero1, $numero2 = 1) {
    return $numero1 * $numero2;
}
20.
¿Es posible utilizar las estructuras de control de PHP cuando trabajamos con HTML?
Verdadero. Basta con poner las etiquetas de apertura y cierre de PHP para empezar a usar dichas estructuras.
21.
¿Qué es lo primero que debería hacer cuando me enfrento a un problema que debo resolver con código?
Resolver el problema a mano o planteando un esquema para definir los casos de uso. De esta forma puedo darme una mejor visión de cómo resolver el problema, encontrar patrones y desarrollar un algoritmo para después programarlo.
22.
¿Qué es una constante mágica?
Una constante que puede cambiar su valor dependiendo del entorno en la que es invocada. Realmente para PHP no son constantes.
23.
¿Cuál sería la forma correcta de pasar parámetros por defecto a una función?
function suma($n1, $n2 = 5)...

24.
Las funciones anónimas son similares a los callbacks de JavaScript, sin embargo, en PHP también se llaman...
Closures
25.
¿Cómo definirías que en el primer parámetro de la siguiente función quieres recibir un tipo de dato entero?
function suma($n1, $n2) { return $n1 + $n2; }

function suma(int $n1, $n2) { return $n1 + $n2; }

26.
¿Cómo expresarías que la siguiente función va a devolver sí o sí un entero?
function suma($n1, $n2) { return $n1 + $n2; }

function suma($n1, $n2) : int { return $n1 + $n2; }

27.
En PHP, dado el arreglo etiquetas = ['PHP','Laravel','JavaScript'], ¿qué índice usarías para acceder a 'PHP'?
La expresión etiquetas[0] devuelve 'PHP', porque los índices en un array de PHP comienzan en 0 y no en 1.
28.
Si un colaborador clona el proyecto y ve solo .env.example, ¿cuál es el siguiente paso para usar la API key?
Copiar .env.example, renombrarlo a .env y completar las variables con sus credenciales antes de ejecutar el proyecto
29.
¿Qué acción es necesaria tras composer require openai/openai si Composer solicita habilitar la extensión en composer.json?
Agregar la habilitación solicitada en composer.json para permitir al componente OpenAI funcionar correctamente.
30.
Dado que la firma del constructor es __construct(string $title, string $subtitle, string $description, array $tags), ¿qué resultado obtienes al ejecutar new Curso('Descripción text','Subtítulo','Mi Curso',['php'])?
El objeto se crea pero sus propiedades quedan mal asignadas, generando datos inconsistentes en título y subtítulo.