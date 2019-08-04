# Fundamentos De La Web

![sin nombre](http://www.cavsi.com/preguntasrespuestas/images/redes/que-es-una-red.jpg)

## Bases web

Para trabajar en algo primero debes conocer sus fundamentos, aquellos conceptos teóricos que posteriormente podremos en práctica y que nos serviran para comprender mejor el porque de las cosas.

En base a eso ¿Sabes qué es la web? bueno la web o la red es eso, una red de computadoras a larga distancia conectadas entre si intercambiando datos constantemente habiendo siempre dos papeles:

  - Cliente
  - Servidor
  - [Wiki](https://es.wikipedia.org/wiki/Cliente-servidor) para mas información

Tanto el cliente como el servidor son solo computadoras. Una computadora puede ser tanto cliente como servidor, por ejemplo cuando tu descargas un archivo estas siendo un cliente y cuando tu estas pasando un archivo a un amigo estas siendo un servidor.

Existen muchar formas que tenemos para crear una red computadoras comunicandose entre sí, la forma formal de poder hacer esta comunicación posible es usando protocolos como: [HTTP](https://es.wikipedia.org/wiki/Protocolo_seguro_de_transferencia_de_hipertexto), FTP, SMTP, POP entre otros.

## Fundamenos del Protocolo HTTP

El protocolo más famoso y usado en el día a día es el protocolo HTTP, todo gracias a la popularidad de internet, esto a permitido que practicamente todas las páginas web que accedemos usando una computadora con conexión a internet, trabajen con este protocolo.

HTTP es un abreviación de HyperText Trasfer Protocol (Protocolo de Transferencia de HiperTexto). Entonces nacé la pregunta ¿Qué es un [hipertexto](https://es.wikipedia.org/wiki/Hipertexto), es pocas palabras es un texto que tiene enlaces a otros textos, lo que permiten que todos estos texto o documentos tengan un relación entre ellos.

Para poder crear estas relaciones es necesario que conozcamos el lenguaje [HTTP](https://en.wikipedia.org/wiki/HTML), no profundizaremos mucho en el, estamos trabajando en un curso para conocer mucho mas sobre este lenguje y desarrollo web fronted, por el momento asumiremos que ya tienes conocimientos en HTML, CSS y algo de JS.

Entonces como es que se comunican el cliente y el servidor, en resumidas cuentas, cuando accedemos a un url en internet, el servidor encargado de esperar a que alguien acceda a esta url, verifica el [Método HTTP](https://diego.com.es/metodos-http) que el cliente esta usando para hacer esa petición, profundizaremos más de estos métodos mas adelante, una vez hecha y procesada la petición y el metodo, el servidor sabe que hacer, y procede a darnos una respuesta. Siempre siempre nos dara una respuesta, ya sea la respuesta que deseamos, o un [error](https://vicentferrer.com/errores-en-http/), cada error tiene un código que nos sera de mucha ayuda para resolver el problema que tengamos.


## Desarrollo Web

Bueno entonces gracias a la inclible uso que se le da hoy en día al internet, nació la necesidad de que hayan personas con el conocimiento necesario para poder manejar este protocolo, y que puedan crear sitios web completos tanto para el cliente como el servidor. Hoy en día no es necesario tener un postgrado de la universidad para poder conocer de este mundo y poder crear proyectos con estas tecnologías.

Es un conocimiento que aunque sea básico nos abrira muchas puertas en el presente y futuro.

Entonces, desde la comercialización de Internet a principios de los años 90, el desarrollo web ha estado en constante evolución. Mientras que antes las páginas web eran un compendio de campos de texto sobrios, hoy en día la costosa presentación de contenidos multimedia ocupa un lugar privilegiado, se ha convertido en un medio de entretenimiento.

En ella, los usuarios prefieren páginas web interactivas que convenzan a través de un diseño atractivo y que se puedan manejar de manera intuitiva. Los desarrolladores web cuentan, para este fin, con distintas herramientas que faciliten integrar contenidos dinámicos y crear las páginas web a medida de los clientes.

Para poder empezar a trabajar con tecnologías web nos separaremos en dos grandes grupos: Dessarrollo [Fronted](https://es.wikipedia.org/wiki/Desarrollo_web_Front-end) y Backend.

El frontend es la parte que esta enfocada a el cliente, el usuario que usara nuestra página, es una parte importante, porque como se explico arriba los usuarios hoy en día prefieren páginas dinamicas e intuitivas que les permitan moverse facilmente por ella. Para poder ser un desarrollor web necesitamos tres cosas principales: HTML, CSS y JS, esos tres lenguajes son el pilar del desarrollo web fronted.

El backend por su parte esta enfocado a el servidor, la parte que se encarga de almacenar la información de los usuarios, la seguridad de nuestro sitio web, la encargada de manejar las peticiónes de nuestro usuario. De este lado es más dificil iniciar, principalmente por la gran cantidad de tecnologías que existen hoy en día para trabajar en el. Existen muchos lenguajes de programación como PHP, Python, Java, GoLang, Elixir, por mencionar a algunos pero exiten muchos muchos más. Tenemos que tener en cuenta tambíen los frameworks web que facilitan el trabajo backend, cada lenguaje tiene mas de uno y aprenderlos todos es una tarea realmente complicada por no decir imposible. Tambien tener en cuenta de que tenemos que tener conocimientos en bases de datos, y un sin fin mas de tecnologías.

El backend tiene una gran cantidades de tecnologías por aprender, por eso aconsejamos, que cuando empiezen en este mundo, escojan un lenguaje y framework, aprendan lo mas que pueden estudien sus entrañas entiendan su filosofía, sus ventajas y desventajas, el porque de su existir, y cuando sea el momento de aprender algo nuevo o cambiar de enfoque se les sea mucho más fácil.

Es mejor empezar con una única cosa, que contodas al mismo tiempo. "El que mucho abarca poco aprieta".

Así pues nosotros hemos escojido Python y Django, son tecnologias que están en auge y que estamos seguros que teníen un gran futuro por delante. Son herramientas muchay facíles de aprender y de dominar. Entraremos más en detaller en próximos capítulos.

Entonces ya llegaros a este puento creo que ya estamos listos para pasar al próximo [capítulo](ch2.md), donde hablaremos más sobre django, que necesitas para poder empezar a utilizarlo y su respectivo método de instalación y configuración.
