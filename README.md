# ColeccionLibros
 Colección de libros en javascript

# Logica de las clases

# Clase Libro
Será el modelo de datos de la App
será una clase instanciable, es decir, vamos a crear objectos de esta clase
Sus propiedades son:

*Titulo
*Autor
*Isbn

# Clase UI
Para minupular los objectos del documento (DOM) y los mensajes dentro de la vista

Métodos:

mostrarLibros(), obtene el arreglo de libros haciendo uso de Datos.traerLibros() y realiza un recorrido del arreglo llamando a método agregarLibroLista(libro).

agregarLibroLista(libro), crea un elemento (tr) en la tabla

eliminarLibro(el), recibe como argumento un elemento para remover la fila de la tabla 

mostrarAlerta(mensaje, className), recibe como argumento el mensaje y la clase de estilos que se le añadirá al elemento, el mismo tiene una duración de 3 seg

# Clase Datos
Nos sirve para gestionar el almacenamiento dentro del localStorage

Métodos:

traerLibros(), el cual se encargará de consultar si localStorage contiene información de ser así retorna la misma, sino retorna un arreglo vacio

agregarLibro(libro), recibe como argumento un objeto de la clase Libro() para almacenar en el arreglo de libros

removerLibro(isbn), recibe como argumento el isbn unico de libro, recorre todos los libros existentes para remover el libro del arrglo según el isbn
