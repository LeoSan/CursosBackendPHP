1.
¿Qué son los controladores?
Clases que contienen la lógica de la respuesta a solicitudes HTTP
2.
¿Para qué sirve un layout?
Para contener el HTML, CSS y JavaScript común a todo el sitio
3.
¿Por qué necesito un framework?
Principalmente para no reinventar la rueda y enfocarnos en la necesidad real.
4.
¿Qué es un helper?
Es un ayudante con tareas específicas y repetitivas.
5.
¿Cuál es la función principal de la carpeta views?
Organizar nuestras vistas.
6.
¿Qué comando usarias para borrar las tablas, volverla a crear y rellenarlas de datos?
php artisan migrate:fresh --seed
7.
¿Qué es Tailwind CSS?
Un Framework CSS para crear rápidamente diseños propios.
8.
¿Cuando usamos el método foreign?
Cuando queremos crear una relación de tablas
9.
¿Qué es un API?
Código preparado en el servidor para que otros sistemas se puedan conectar.
10.
¿Qué método usamos para verificar que contamos con un registro en una tabla?
$this->assertDatabaseHas()
11.
¿Cómo funciona el Server Side Rendering?
Mi servidor procesa toda la página por cada solicitud y manda las plantillas HTML al navegador ya procesadas.
12.
¿Cuál de las siguientes es una buena práctica para evitar código espagueti?
Usa las etiquetas de PHP diseñadas para imprimir en HTML.
13.
¿Podemos usar la función `mail()` de PHP?
Verdadero, pero requiere de una configuración muy avanzada en nuestra computadora para poder usarla, por eso es mejor usar alternativas como PHP Mailer.
14.
¿Qué tipo de rendering utiliza PHP?
Server Side Rendering (SSR)
15.
¿Es posible ver los datos enviados por medio de una solicitud POST?
Verdadero. Usando la consola de desarrolladores podemos inspeccionar cada solicitud que es enviada al servidor y ver qué datos se están mandando.
16.
¿Cuál es la extensión de mis vistas?
.blade.php
17.
¿Qué son los traits?
Son una alternativa a la herencia en PHP. Permite definir métodos que pueden ser compartidos o reutilizados por varias clases.

18.
Si quiero ligar datos que un usuario escribe a una consulta SQL con el driver de PDO, ¿cuál método sería el más seguro para hacerlo?
bind_param. 
**REPASAR**

19.
¿Cuál de las siguientes afirmaciones lograría explicar que es un Framework?
Un Framework de backend te da buenas prácticas y arquitectura base para construir un producto.

20.
¿Las cookies se pueden usar para almacenar información tanto en los navegadores como en apps móviles?
FALSE

21.
¿Cómo instamos a bootstrap en nuestro proyecto?
npm install bootstrap --save-dev
22.
¿Con qué atributo HTML seleccionamos una opción en select?

selected
23.
¿Por qué usamos datos falsos en pruebas?
Los datos falsos permiten: aislar las pruebas de la API de la base de datos de producción y de datos reales; proteger la confidencialidad de datos sensibles; simular diferentes escenarios o para probar casos límite y excepcionales que pueden ser difíciles de lograr con datos reales.

24.
Si defines $nombres = ['Ana','Luis','María','Pedro'], ¿cómo mostrarías en PHP solo el tercer y el último elemento?
Usar echo $nombres[3] para el tercer elemento y echo $nombres[count($nombres)-1] para el último.
**REPASAR**


25.
Según la clase, ¿qué sitios populares demostraron que PHP domina la web?
Facebook, Twitter y LinkedIn fueron mostrados como sitios principales que usan PHP
**REPASAR**

26.
¿Cuál es la cadena DSN correcta para conectar con host 127.0.0.1, base de datos web_php y charset utf8 usando PDO?
mysql:host=127.0.0.1;dbname=web_php;charset=utf8
27.
Si al listar preguntas en el home notas lentitud, ¿cómo optimizarías las consultas en Laravel y LiveWire?
Usar eager loading con with(‘author’,‘category’,‘likes’) en render de LiveWire y reducir queries innecesarias.

28.
Si usas @can('update',$question) en Blade y tu Policy exige ownership y sin contenido, ¿qué botones ves en preguntas con comentarios?
Se ocultan ambos botones para preguntas ajenas y para propias con comentarios, sin opción de eliminar.
**REPASAR**

29.
¿Cómo adaptarías el método toggle para que use el ID del usuario autenticado en lugar del usuario hardcodeado ID 20?
Reemplazar el ID 20 por auth()->id() en las llamadas a darCorazon y quitarCorazon.

30.
Si al crear un proyecto con laravel new seleccionas LiveWire y respondes no a Volt, ¿qué configuración se aplica?
Se configura autenticación de Laravel con LiveWire, sin incluir Volt en el scaffold y omitiendo PHP U