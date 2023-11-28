# Book Nook

Mi aplicación consiste en una página de compra-venta de libros,
en la que un usuario podrá ser a la vez comprador y vendedor.

En la pagina de "index" hay cuatro opciones:

  1. Crear base de datos, este botón llevará a un script en el que se
  creará la base de datos con sus tablas y demás en el localhost.

  2. Insertar datos demo, este botón se encargará de rellenar la base
  de datos con algunos datos de ejemplo.

  3. Eliminar base de datos, este botón se encargará de eliminar la
  base de datos en caso de que sea necesario.

  4. Conectar a base de datos, este botón lleva a un login, en el cual
  se deberán introducir los datos de acceso del localhost:

    -Usuario: root
    -Contraseña: 
    -Nombre del servidor: localhost.

  Este login está pensado para una versión posterior en la cual, la base
  de datos estará registrada en un servidor remoto.


Una vez dentro del servidor, te encontrarás con una página de inicio de sesión
a la cual solo podrá acceder un usuario ya registrado, te recomiendo que utilices:

  Usuario: david
  contraseña: 1234

También puedes darle al botón registrarte, que abrirá un formulario de registro, a
través del cual podrás dar de alta un usuario.


Una vez la sesión esté iniciada, accederás a la página de inicio de sesión,
donde dispondrás de un div en el cual se muestran los libros disponibles a
la venta, con sus respectivos isbn, nombre y precio en euros.
También dispones de cuatro opciones como usuario:

  1. Poner a la venta, accederás a un formulario en el cual deberás introducir
  los datos del libro que deseas poner a la venta. Ejemplo:
    
    -isbn: 9788466353779
    -nombre: dune
    -género: Ciencia Ficción
    -Nº Págs: 784
    -idioma: Castellano
    -fecha de publicación: 2021-04-03
    -precio: 11.35

  2. Retirar venta, esta opción da la posibilidad de retirar un libro que haya
  sido puesto a la venta por este mismo usuario. Se introducirá el isbn de un libro
  puesto a la venta por el mismo usuario que ha iniciado sesión.

  3. Actualizar venta, se accede a un formulario que permite actualizar el precio
  de un libro que haya sido puesto a la venta por el mismo usuario que ha iniciado
  sesión.

  4. Comprar libro, lleva a un formulario en el que el usuario tendrá que introducir
  el isbn del libro que se desea comprar. Una vez comprado, el libro tendrá el campo de
  "vendido" en true y este ya no podrá comprarse más.
