CRUD-MVC-PHP
Crud en MVC y PHP
### Objetivo: 

>Desarrolla un sistema CRUD simple en PHP 5 o 7 (sin frameworks) y MySQL para la administración de libros de una tienda.

### Detalles:

>Books debe tener la siguiente información:

1. Nombre
2. Autor
3. Número de Páginas
4. Precio (en real, contando centavos)
5. Bandera para libro activo/inactivo (que no afecta a la lista, solo un valor de referencia)
6. Fecha de inclusión/edición

### Reglas: 

>Las siguientes reglas deben seguirse al registrar/editar un libro:

1. No debería haber libros con el mismo nombre
2. El número de páginas y el precio no pueden ser cero o negativo
3. El libro debe tener el valor inicial de inactivo, y puede ser cambiado más tarde directamente a través de la lista (enlace o Ajax) o edición completa del libro
4. En el listado, el precio debe estar formateado en el estándar brasileño (R$ 1,050.10).


### Detalles sobre el programa:

1. init.php son los archivos de configuración del sistema de biblioteca
2. El directorio "view" es donde se encuentran todas las pantallas del sistema
3. El directorio "controller" es donde están las características del sistema que interactúan con la base de datos
4. El directorio "modelo" es donde se encuentran los archivos de conexión de la base de datos

En el directorio "view" hay 3 páginas principales: edit.php, catastro.php e index.php. la página principal y el menú son los ámbitos de los sistemas HTML y Menu respectivamente.

No diretório "controller" estão os arquivos PHP que executam as funcionalidades do sistema.

No diretório "model" estão os arquivos de conexão com o Banco de Dados

O arquivo script.sql é o scrip em sql que cria o banco e a tabela.
