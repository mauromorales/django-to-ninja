# Primeros pasos

### ¿Qué es Django?
Django es un framework de código abierto hecho en python con un controlador MTV, esto quiere decir que Django es un conjunto de código ya echo a nuestra completa disposición.

### ¿Para qué sirve?
Django sirve para poder crear servidores estables y seguros de manera rápida y eficaz siendo la razón de por qué muchas personas lo elijen a él, cabe decir que django no es el único que puede hacer esto también hay otros frameworks que pueden hacerlo pero hoy veremos a Django.

### Historia
Django surgió por una necesidad: la intensa creación de aplicaciones web las cuales no eran fáciles de crear y el proceso tomaba mucho tiempo, al mismo tiempo el mundo online se volvía más perfeccionista, en el otoño del 2003 dos desarrolladores abandonaron php y comenzaron a usar python (ambos son lenguajes de programación), con la intensa creación de aplicaciones web poco a poco desarrollaron un framework genérico que les permitía crear aplicaciones más rápidamente, ellos ajustaron este framwork por **2 años**, en 2005 decidieron hacer este framework de código libre.

### ¿Qué necesito?
Para poder usar django necesitas los siguientes elementos:
* Pc o laptop
* Python instalado
* Acceso a Internet 
* Editor de texto
* Navegador web
* **Voluntad de aprender**. 

### Bases de Django
primero debemos abordar lo que normalmente usaras en Django para que funcione de forma correcta.

#### Urls:
Las url es la forma en la diferentes clientes se comunicaran con nosotros, por ejemplo github posee la url "https://github.com" esta url permite que nos comuniquemos con los servidores y pagina de github, nosotros debemos crear nuestras propias url.

#### Vistas:
Las vistas son las encargadas de recibir la petición del cliente y dependiendo de los datos que se le den envié los datos necesarios, los datos que la vista necesita se pasan atravez de la url, estas son muy importantes ya que sin ellas no sabríamos que datos debemos enviar al cliente es por ello que también cuentan con lógica que nosotros debemos darle.

#### Modelos:
Un modelo es la fuente única y definitiva de información sobre los datos. Contiene los campos y comportamientos esenciales de los datos que está almacenando. En general, cada modelo se asigna a una sola tabla de base de datos, a partir de estos modelos podemos crear objetos donde podremos usar los los datos ya sean nuestros o del usuario.

#### Templates o Plantillas
Los templates o Plantillas son archivos html donde podremos crear paginas web que renderizara nuestro servidor, estas plantillas están completamente ligadas al servidor por lo que podemos tener mas control sobre ellas, el sistema de plantillas de django es simple ya que nos permite crear plantillas de forma rápida y fácil.

#### Admin
El admin es una herramienta indispensable que nos da django, con ella tenemos control de todo lo que pasa tanto en la pagina web como en la base de datos, podemos crear y eliminar datos fácilmente sin mencionar que este adimin esta protegido por contraseña y nombre, la manera de crearlo es desde la consola de django.

### Orm:
Django puede conectarse a la base de datos que nosotros estemos manejando de una forma fácil y rápida, una de las maneras en las que django se conecta con la base de datos es mediante *Querysets*, Un *QuerySet* es, en esencia, una lista de objetos de un modelo determinado. Un *QuerySet* te permite leer los datos de la base de datos, filtrarlos y ordenarlos.
