# Documentación | Ejercicio de corrección de estilo usando FLEXBOX/GRID.
*Desarrollado por: Cristian Camilo Betancourt* 

### Gestión de la configuración 

  * IDE / Visual Studio Code 
  * Lenguajes / HTML-CSS
  * Gestión del proyecto / Trello 

### Extensiones utilizadas:
  * Live server
  * Html format
  * Html preview
  * Htmls Snippets
  * Html CSS Support

## Análisis de los problemas encontrados.


* ### 1. Dimensiones de la página. 

![image](https://user-images.githubusercontent.com/108433878/195932504-d780b411-c7f8-453e-9393-b912a02192bd.png)

> ## *Corrección.*
![image](https://user-images.githubusercontent.com/108433878/195933286-95ff84b7-f224-41ee-bc4b-bbd78a2aedf9.png)


  > *  Ajustes a la clase .wrap-body | al ser una clase que abarca la totalidad del documento, se integran las propiedades display: flex (para poder hacer movimientos a las etiquetas que se encuentran dentro). Flex-direction:column, para organizar los elementos en una columna de arriba para abajo y align-items: center; para que todo los elementos que se encuentran dentro de la etiqueta se centren. 

  > ![image](https://user-images.githubusercontent.com/108433878/195933677-c0d277b2-e3ae-4a30-ac48-75038b07f1fa.png)

  > * Ajustes a la clase .zerogrid | Al ser una clase que abarca diferentes secciones, se procede a aplicar width: 1000px, para aplicar un ancho predeterminado de la parte del contenido donde se almacena la información. 

  > ![image](https://user-images.githubusercontent.com/108433878/195935548-186f9e4c-e400-4910-8434-8c31839f686f.png)




* ### 2. Ajuste del menú. 

![image](https://user-images.githubusercontent.com/108433878/195937560-bd211331-3ecd-4182-9f91-9a75b6c2ea19.png)

> ## *Corrección.*
![image](https://user-images.githubusercontent.com/108433878/195937664-844c595a-1b7f-4442-a52d-ac1dab2f7850.png)

  > * Ajustes a la clase .main-header y .row | Al ser una clase no albergada dentro de las modificaciones de .wrap-body, se maneja individualmente de nuevo con diplay:flex; para poder modificar movimiento y justify-content: space-between, para generar un espacio entre el logo y el menú.  

  >  ![image](https://user-images.githubusercontent.com/108433878/195938053-a7bbe797-1d80-4440-9ecf-f9404215bbc1.png)



* ### 3. Contenedor de imágenes.

![image](https://user-images.githubusercontent.com/108433878/195936637-7691cf1a-07f4-444b-85ad-27d6e2d24b1a.png)

 > ## *Corrección.*
 ![image](https://user-images.githubusercontent.com/108433878/195937230-814d8a68-9d68-4caa-91f6-409897bc72d5.png)

  > *  Ajustes a las clases que albergan las imagenes  .row y .col-2-5 , .col-3-5 , .col-1-2  | la clase .row alberga directamente a los contonedeores de imagenes, en este caso se utilizan las dos claces para lograr cambios específicos a estas clases ya que existen varios contenedores con el mismo nombre de clase. En la clase .col-2-5 se crea una propiedad width: 60% que albergue un porcentaje total en una sección lineal por ende al otro objeto que le sigue, se destina un 40% así no se encuentre explicito, seguido por float:left que envía el contenido de la clase a la izquierda.(recordemos que al inicio se utilizó un display:flex que alberga la mayoría del documento incluyendo esta parte, por ende no es necesario usar la propiedad dos veces).

  >  ![image](https://user-images.githubusercontent.com/108433878/195939255-a3b59b77-dd3b-4096-9d43-02aef893361a.png)

  > * Clases .col-3-5 y .col-1-2 | Para la primer propiedad se agrega un width:40% y para la segunda un width:50%; al igual que la anterior clase, deja un espacio restante del 60% y 50% correspondiente, donde se posiciona el restante del contenido, es decir las otras imágenes.

  >  ![image](https://user-images.githubusercontent.com/108433878/195939829-5ed41e5f-d823-4986-a3ef-1701c8658095.png)




* ### 4. Sección de más información. 

![image](https://user-images.githubusercontent.com/108433878/195940613-051d1b87-013e-417f-b3f1-aad0929fd817.png)

 > ## *Corrección.*
 ![image](https://user-images.githubusercontent.com/108433878/195940679-dc8c5963-d89f-4a91-9d76-6808bb7a6310.png)
 
   > *  Ajustes a las clases que alberga la sección  .wrap-col .box-text | Se utiliza de nuevo el principio de especificidad para seleccionar .box-text, que alberga el texto y el botón de selección, y se le asigna un width de 480px; al seleccionar la clase que alberga dos elementos, estos se posicionan a la izquierda por los cambios de display:flex; que se generaron al comienzo. 

   > ![image](https://user-images.githubusercontent.com/108433878/195941212-004045f2-7f20-443d-b22e-e83ca073c0f6.png)


* ### 5. Footer. 
![image](https://user-images.githubusercontent.com/108433878/195946191-e2243eb1-22f3-43d1-861b-c61b19860dd2.png)

 > ## *Corrección.*
 ![image](https://user-images.githubusercontent.com/108433878/195946270-34911063-b829-4221-aeec-0a8a117e8793.png)

  > * Ajustes a la clase .wrap-footer .row | Se realiza el ajuste general al footer. Se utiliza display: flex; para modificar la ubicación de todos los contendios del footer. Justify-content: space-between; para generar espacio entre contenidos albergados. 

  > ![image](https://user-images.githubusercontent.com/108433878/195946761-6287ff9f-5615-4821-a800-0e5b202460dd.png)

  > * Ajustes a la clase .wrap-footer .wrap-col | Se utiliza un width: 270px; para ajustar las dimensiones de todos los objetos contenidos dentro del footer para que guarde una dimensión total. 

  > ![image](https://user-images.githubusercontent.com/108433878/195947124-193847f1-87f7-4028-a317-0c08509908f2.png)

  > * Ajustes a la clase .row | La clase .row solo alberga el contenedor de la derecha. Para ajustar, se utiliza de nuevo un display:flex; para poder mover los elementos libremente y luego un flex-direction:column; para para que cada elemento se ubique dejabo del primero. 

  > ![image](https://user-images.githubusercontent.com/108433878/195947439-859342ef-95f4-448b-9ab9-9ac37f9af5c8.png)


* ### 5. Blog.
![image](https://user-images.githubusercontent.com/108433878/195947733-81437f5c-b7e7-4c5b-a371-b36bcd3ff726.png)

> ## *Corrección.*
![image](https://user-images.githubusercontent.com/108433878/195947796-ce5641d2-ef23-44ca-bdeb-4ce4410d1070.png)

  > * Ajustes a la clase .flex-box .col-1-2 | Esta clase se modifica mediante su tamaño, recordemos que el ajuste documento ya tiene un display flex que actua sobre todos los elementos. Para esta clase en especificop se utiliza width: 50%; que dividira el espacio entre los dos contenidos que posee el container (imagen y texto). 

  > ![image](https://user-images.githubusercontent.com/108433878/195948148-64ec1ef4-23ff-4589-ae6e-a404263954d0.png)


* ### 5. Contacto.
![image](https://user-images.githubusercontent.com/108433878/195948234-10b0b744-33a2-4d12-925a-9ffe77ed584d.png)

> ## *Corrección.*
![image](https://user-images.githubusercontent.com/108433878/195948298-28c1b589-6531-49e9-9d40-3bfbf8177695.png)

  > * Ajustes a la clase .contact-form .t-center | se modifica la clase .t-center mediante el uso de especificidad. Agregando padding-top: 50px; se logra que el texto se separe de su margen superior para lograr una similitud.  

  > ![image](https://user-images.githubusercontent.com/108433878/195948698-55aba12f-a7f3-4ecc-81fe-ca9d811863ab.png)

  > * Ajustes a la clase .contact-form .col-1-3 | La clase .col-1-3 alberga los input de nombres y apellidos que se encuentran en la parte superior, para modificarla se genera un display: inline block; para que se posicionen los input seguidos de derecha a izquierda. Finalmente se genera un width: 33%; para que cada elemento (3) se dividan el 100% de ancho de la página y conserve las dimensiones. 

  > ![image](https://user-images.githubusercontent.com/108433878/195949026-01d88df3-05bf-49b7-b01e-e98275781af5.png)










