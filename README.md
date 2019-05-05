# Burger Queen

# Contexto 
Burquer Queen es una cadena de comida rápida que ofrece un servicio las 24 horas del día. Actualmente ha recibido una respuesta favorable por parte de sus clientes debido a la calidad de sus productos y servicio por lo que busca expandirse. Para ello requiere de un sistema eficiente con el que pueda tomar el pedido de sus  clientes de una manera rápida.

Burguer Queen tinee dos menús: uno para el desayuno, que es bien sencillo:

> **Desayuno**

> |Item|Precio|
> |:---|:---:|
> |Café Americano|$20|
> |Café con Leche| $28 |
> |Sandwich de Jamón y Queso| $35 |
> |Jugo Natural| $15 |


Y un menú para el resto del dia:

> **Diario**

> |Hamburguesas|Precio|Acompañamientos|+$15|Bebidas|Precio|
> |:---|:---:|:---|:---:|:---|:---:|
> |Sencilla|$40|Papas a la Francesa||Refresco|$15|
> |Doble| $55 |Onion Rings||Agua|$10|

> Los clientes pueden escoger entre hamburguesas de res, de pollo, o vegetariana. Y por $15 MXN pueden agregarle queso o huevo.

> Los clientes son suelen ser indecisos, por por lo que es muy común que cambien el pedido varias veces antes de finalizarlo.

# Metodología 
La metodología que se utilizó para desarrollar la aplicación fue Design Sprint ya que permite prototipar y validar ideas con usuarios finales de manera rápida. Este método consiste de cinco pasos: 

![Metodología](https://github.com/Cristalgarcia/UX_BurgerQueen/blob/master/assets/Metodolog%C3%ADa_design%20sprint.PNG)


## Requerimientos del cliente
- Los empleados tomaran los pedidos utilizando una tablet, por lo que la interfaz deberá tener un diseño adaptado a dos tamaños de tablets 9.7 y 7 pulgadas.
- Necesitamos hacer una web app, así será accesible y funcionará bien en tablets iOS y Android.
- La interfaz debe mostrar los dos menús (desayuno y resto del día), cada uno con todos sus productos.
- El usuario debe poder ir eligiendo qué productos agregar.
- El estado actual del pedido siempre deberá de ser  visible mientras tomamos un pedido.
- El empleado deberá poder editar los pedidos. 

## Objetivo 
Diseñar una interfaz de una comanda en la que un empleado de una cadena de comida rápida pueda tomar la orden de los clientes de manera eficaz. 


## Entendimiento 
Las comandas son programas sencillos y efectivos para el registro de pedidos establecimientos de comida y bebidas que ofrecen una rapidez y precisión en la gestión de pedidos y que repercute de manera positiva en el servicio al cliente al evitar lo olvidos o los errores en tomar un pedido y mejorar la productividad del negocio. 

## Investigación del campo

Se realizaron dos visitas a establecimientos de comida rápida para comprender el uso de comandas digitales como parte de su servicio.

### Primera visita: McDonald´s

Para comprender cómo funciona el servicio de comida rápida se acudió a la sucursal de McDonald´s ubicada en calle Génova 56, Juárez, en la Ciudad de México para solicitar una visita guiada a las instalaciones y comprender el proceso de elaboración de sus productos, limpieza y organización. 

Durante la visita la gerente de la sucursal mostró las instalaciones, el proceso de limpieza de la tienda, los estándares de calidad que debe de cumplir la cadena de alimentos, los productos utilizados y el proceso de producción de la cocina. Por último, indicó cómo es el proceso en la caja y el sistema que utilizan para tomar pedidos. La comanda presenta las siguientes características:

![Pains y gains de McDonalds](https://github.com/Cristalgarcia/UX_BurgerQueen/blob/master/assets/Pains_gains_MCD.jpg)

La cajera indicó que la comanda ideal sería:
- Tener la posibilidad de visualizar los productos por categoría.
- Más organización. 
- La navegación fuera intuitiva.
- Código por color.
- Actualización de productos.


### Segunda visita: Pan D´Monium

La sucursal Pan D´Monium ubicada en Orizaba, Roma Norte, CDMX, ofrece alimentos veganos. Como parte de sus proceso ha utilizado sistemas de comanda en tablet la cual presenta los siguientes gains y pains: 

![Pains y gains Pan d´monium](https://github.com/Cristalgarcia/UX_BurgerQueen/blob/master/assets/Pains_gains_PD.jpg)


Se realizó una entrevista a la persona que toma las órdenes y utiliza la aplicación ([guía de entrevista](https://docs.google.com/document/d/1d9dWYZm5liHBv9hYJGxbOVlD6ejI3oSpHrCwE2RhouA/edit?usp=sharing)).
Al preguntarle cómo sería su aplicación ideal ella comentó que las características que debería tener son: 
- Opción de imprimir ticket o no.
- Separar cuentas por método de pago.
- Visualización por mesa y por cliente.
- Considerar que el proceso de factura  sea sencillo.
- Íconos en los botones 
- Separar cuentas por comensal.

## Benchmarking
En colaboración con otras compañeras interesadas en elaborar su interfaz para el proyecto de Burguer Queen se elaboraron dos benchmarks para la investigación. 

1. El primero tuvo como objetivo conocer los sistemas de comandas que utilizan otros establecimientos de comida rápida (Hot dog Rodriguez, Pastes Kiko´s, Pan D´Monium, Loyverse, Domino´s Pizza, McDonald´s y Casino Yak). Para conocer la información completa consultar la siguiente [liga](https://github.com/Cristalgarcia/UX_BurgerQueen/blob/master/assets/Benchmark_BQ.jpg). 

2. El segundo analiza seis sistemas operativos (Izettle pro, NCR Aloha Quick Service, Business Plus Accounting, Adelo, Software Silverpos y Master Chef) para conocer sus características como el orden de los productos, mesa o cliente, visualización de la orden y diseño. Para conocer la información completa consultar la siguiente [liga](https://docs.google.com/spreadsheets/d/1zudCBhf3ApfQi0Ym1H0A-1gIIHcijtAL3z-1MhDGrtE/edit?usp=sharing). 

## Definir
A través de la exploración de campo se realizó un [mapa de empatía](https://github.com/Cristalgarcia/UX_BurgerQueen/blob/master/assets/Mapa%20de%20empat%C3%ADa_BQ.jpg) para definir el perfil de nuestro usuario

#### Perfil de usuario
Edad: 20-30 años 
Escolaridad: Bachillerato
Sexo: Indistinto 
Puesto: Cajera 
Trabaja en una cadena de comida rápida en vacaciones para solventar sus gastos. 
En la sucursal labora seis días a la semana con un día de descanso entre semana. 
Se caracteriza por ofrecer buena atención al cliente al ser atenta y empática con las personas. Es responsable, comprometida y busca mejorar en su trabajo. 

Con respecto a las interfaces que ha utilizado refiere: 

PAINS
- En las cadenas de comida rápida donde ha trabajado no hay una capacitación para utilizar los sistemas de comanda. 
- Las interfaces que ha utilizado son difíciles de navegar.
- Diseño poco atractivo.
- No hay un orden de los productos. 

GAINS 
- Contribuyen a agilizar la toma de órdenes.
- De forma inmediata llega el pedido a la cocina. 
- Los botones son grandes para poder seleccionar los productos. 
- Visualizar los productos que se están seleccionando.


## Divergir  

Con el equipo de trabajo se utilizó material didáctico para mapear diversos escenarios y posibles soluciones para el diseño de la interfaz. Para ello los botones podían moverse en diferentes direcciones para corroborar el flujo de navegación. 

![Material](https://github.com/Cristalgarcia/UX_BurgerQueen/blob/master/assets/Material%20didactico_BQ.PNG)


## Converger
Se realizó un boceto del [flujo de la información](https://github.com/Cristalgarcia/UX_BurgerQueen/blob/master/assets/Flujo%20de%20contenido_BQ.jpg) de la solución elegida. 

Con base en las propuestas se realizó el boceto para crear el prototipo de la fase siguiente. 
![Boceto](https://github.com/Cristalgarcia/UX_BurgerQueen/blob/master/assets/Bocetos_BQ.PNG)


## Prototipar 
Para diseñar el prototipo se utilizó la herramienta Figma. 

#### Criterios de diseño
- Los colores de fondo están basados en contrarrestar la fatiga visual, ya que los usuarios pasan largas horas utilizando la interfaz. La paleta de colores son: 


- Los botones son grandes para poder seleccionar los productos o acciones de forma rápida y precisa.
- Los productos  cuentan con iconos para distinguir de manera visual los alimentos, además de contar con una descripción para las personas de nuevo ingreso que están utilizando por primera vez la interfaz. 
- Los productos están categorizados por colores para identificarlos de manera sencilla. 

![Imagen prototipo](https://github.com/Cristalgarcia/UX_BurgerQueen/blob/master/assets/Imagen%20prototipo_BQ.PNG)


Para visualizar el prototipo de la aplicación consultar el siguiente [link](https://www.figma.com/proto/0CElJMixkqznK5BHrt4JWHmi/Untitled?node-id=25%3A0&scaling=scale-down). 


## Validar
La aplicación fue testeada por tres personas para realizar las modificaciones pertinentes y definir el prototipo actual. Los cambios realizados fueron:

- Los botones para seleccionar la cantidad se encontraban de forma individual por cada producto, sin embargo representaba saturación visual y clics adicionales por lo que se optó por un teclado en la parte superior. 
- Los botones se hicieron más grandes para reducir la saturación de la información. 
- La información era mostrada hasta dar clic en el botón OK. Se optó en que todo momento ésta fuera visualizada. 
 
 ![Bocetos](https://github.com/Cristalgarcia/UX_BurgerQueen/blob/master/assets/Bocetos_BQ.PNG)

### Requerimientos

- Entender cómo se realizan los pedidos en un restaurante similar a BQ y cuáles son las necesidades del personal de cocina y del personal de atención al público (meser@s y cajer@s).
  - Ideal si dentro de la investigación toman fotos de las formas en que se toman pedidos actualmente.
- Diseñar la versión para tablets de esta aplicación, teniendo en cuenta el modo de uso de esta tablet (por ej. El uso de la     pantalla táctil) y los distintos tipos de usuarios.
  - El diseño se debe adaptar a dos tamaños de tablets 9.7 y 7 pulgadas.
  - Crear un ícono para poder agregar la pantalla al home de la tablet. Puedes usar [appicon](https://appicon.co/#app-icon) y     agregar las especificaciones para   el equipo de desarrollo.
- El estado actual del pedido siempre visible mientras tomamos un pedido.
- Necesitamos hacer una web app, así será accesible y funcionará bien en tablets iOS y Android.
- Testear e iterar los diseños con personal de restaurantes similares a BQ.
- Entregar las especificaciones de diseño al equipo de desarrollo en Figma, Zeplin ó XD.
- Hacer seguimiento y QA a la implementación realizada por el equipo de desarrollo.
- Realizar pruebas de usabilidad de la aplicación web al final de cada entrega del equipo de desarrollo.


