# Descripción general de la instalación

### Introducción

El primer paso para crear cualquier sitio web es tener las herramientas adecuadas. Para nosotros, eso significa configurar un entorno de desarrollo para escribir un buen código.

Muchos cursos de desarrollo en línea utilizan editores de código en el navegador o "sandboxes", que le brindan las herramientas y programas necesarios para realizar la tarea en cuestión y nada más. Utilizará algunos de estos entornos sandbox durante las primeras etapas de Codelibro, ya que son excelentes para comenzar rápidamente. Sin embargo, la mejor manera de prepararse para el éxito a largo plazo es operar en un entorno de desarrollo real.

No te mentiremos: instalar paquetes, editores e incluso sistemas operativos completos puede resultar muy frustrante. Sin embargo, tener la experiencia de configurar un entorno de desarrollo para ejecutar el código que escribirás es una habilidad invaluable del mundo real que llevarás contigo durante el resto de tu carrera.

### El plan de instalación

En las siguientes secciones, repasaremos los pasos para configurar su entorno. Estas secciones son los pasos más importantes de todo el plan de estudios. Tómese el tiempo adicional para verificar lo que está escribiendo o puede causar más dolores de cabeza en el futuro.

En las siguientes lecciones, analizaremos estos pasos de instalación juntos:

* Instalar el [sistema operativo](https://translate.google.com/translate?hl=en&sl=en&tl=es&u=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FOperating_system) de su elección
* Instalar un editor de código
* Crear una clave SSH \(una "contraseña" personal que lo identificará en GitHub, Heroku y muchos otros sitios que utilizará\);

Al final de esta sección, estará listo y funcionando con muchas de las herramientas que necesita para escribir y ejecutar código. Puede parecer una gran cantidad de pasos, ¡pero lo superaremos juntos de la manera más sencilla posible! Si algo sale mal, recuerde seguir estos pasos:

* Analice la salida del terminal en busca del error real.
* Google Google Google.
* Nunca tengas miedo de [pedir ayuda](https://app.element.io/#/room/#codelibro:matrix.org)!

### Opciones de SO

“Espera, espera, espera! Me gusta mi sistema operativo tal y como está! "

No se preocupe! No le estamos pidiendo que se deshaga de lo que se siente cómodo usando. Probablemente haya aprendido muchos consejos y trucos para su sistema operativo favorito y no quiera perder todo lo que tiene en su computadora. Sin embargo, la mayoría de los sistemas operativos se desarrollan pensando en personas sin conocimientos técnicos, por lo que ocultan o dificultan el uso de muchos de los lenguajes y marcos que necesitaremos instalar. Tener que solucionar estas dificultades hace que muchos desarrolladores nuevos se den por vencidos incluso antes de haber comenzado su viaje hacia el nirvana completo.

La modificación o el arranque dual de una computadora para trabajar con las herramientas que necesitará hará que sea mucho más fácil comenzar a programar, puede ayudar a crear un entorno libre de distracciones y quedará bien en su currículum. Respira hondo y veamos tus opciones.

#### Mac

Si usa una Mac, está en excelente forma. Las instrucciones de Codelibro asumen un sistema basado en Unix. Con solo instalar unos pocos programas, estará listo y funcionando con su educación en poco tiempo!

#### Linux

[Linux](https://translate.google.com/translate?hl=en&sl=en&tl=es&u=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FLinux) es un sistema operativo gratuito y de código abierto que funciona bien con todos los lenguajes de programación. La mayoría de las herramientas de desarrollo están escritas para funcionar de forma nativa con Linux. Es probable que sus herramientas se actualicen con más frecuencia, tengan más información disponible para solucionar problemas y simplemente funcionen mejor en Linux. Usaremos Ubuntu, una de las distribuciones más populares y fáciles de usar disponibles, o la alternativa más ligera de Xubuntu. Si no usa una Mac, le recomendamos que use Linux. Es así de simple.

#### Máquinas virtuales y arranque dual

Una máquina virtual es una emulación de una computadora que se ejecuta dentro de su sistema operativo existente. Le permite utilizar otro sistema operativo dentro de un programa en su sistema operativo actual \(por ejemplo, ejecutar Linux dentro de Windows\). Las máquinas virtuales son tan simples de instalar como cualquier otro programa y están libres de riesgos. Si no le gusta Linux, puede eliminar fácilmente la máquina virtual. Las máquinas virtuales son una excelente manera para que los nuevos desarrolladores comiencen rápidamente.

* [Mire este video](https://youtu.be/yIVXjl4SwVo) sobre máquinas virtuales para obtener una descripción general de cómo funcionan.
* Si necesita más claridad, [lea este artículo](https://translate.google.com/translate?hl=en&sl=en&tl=es&u=https%3A%2F%2Fwww.howtogeek.com%2F196060%2Fbeginner-geek-how-to-create-and-use-virtual-machines%2F) para obtener más información sobre las máquinas virtuales.

El arranque dual significa instalar dos sistemas operativos en su computadora, lo que le puede dar la opción de iniciar Linux o Windows cuando su computadora se inicia por primera vez. La ventaja del arranque dual sobre una máquina virtual es que el sistema operativo puede usar todos los recursos de su computadora, lo que resulta en una operación mucho más rápida. Existe cierto riesgo al instalar un sistema de arranque dual porque está cambiando las particiones de su disco duro, pero el riesgo es muy bajo. Estarás bien siempre que te tomes tu tiempo y leas las instrucciones.

El arranque dual puede ser tan fácil como insertar una unidad flash y hacer clic en algunos botones. Los beneficios del arranque dual no pueden subestimarse. Permitirá que Linux acceda a todas las capacidades de su hardware, tenga un entorno limpio y sin distracciones para la codificación, y aprenderá la plataforma que utilizan muchos desarrolladores y servidores senior en todo el mundo.

#### Windows 10 con el subsistema para Linux

Probablemente esté familiarizado con Windows por una razón u otra. Para muchas personas, es su sistema operativo preferido. Windows es fácil de usar y viene preinstalado en la mayoría de las computadoras. Desafortunadamente, algunos lenguajes, como Ruby, se crearon asumiendo que se usarán en sistemas basados en Unix \(Mac o Linux\) y no se ejecutarán fácilmente en Windows.

Es posible desarrollar con el Subsistema de Windows para Linux \(WSL\), pero no se recomienda. Si sigue esta ruta, terminará pasando muchas horas en Google tratando de solucionar los muchos problemas que encontrará. Para su cordura, recomendamos instalar una máquina virtual en lugar de usar WSL.

### Editores en línea

Por último, hay una variedad de entornos de pruebas de código en línea que pueden resultar muy útiles cuando no está en su sistema principal o está creando un prototipo de código antes de enviarlo.

* [Repl.it](https://repl.it/)
* [Codepen.io](https://codepen.io/)
* [JSFiddle.net](https://jsfiddle.net/)
* [CodeSandBox](https://codesandbox.io/)

Estos sitios se pueden utilizar para completar pequeños ejercicios o para esbozar un concepto que no comprende del todo. Sin embargo, no debe utilizar estos sitios como su entorno de desarrollo principal.

