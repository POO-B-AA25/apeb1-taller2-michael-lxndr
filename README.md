[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/xFyxNy32)
# Taller 2 - Generación de diagramas UML

## Generación de diagramas UML _(Unified Modeling Language)_

* Leer detenidamente cada problemática propuesta.
* Usar el programa **DIA-UML** _(Open source)_, o **StarUML**, para generar la representación de su solución _(modelado)_, vía diagramas de clases.
* Para cada diagrama/solución _(modelado de su solución)_, genere/agregue 2 archivos _(fuente e imagen: \*.dia \*.mdj y \*.png \*.jpeg, etc)_. No olvide titular a cada clase, con el nombre representativo del análisis/solución.
* Para el nombrado de cada archivo use el formato: _Problema-NroProbl_NombClase_. Ejemplo 
 **Problema-1_Trabajador**
* No es necesario crear subCarpetas para agregar el modelado de cada solución, agregue todo, en el directorio raíz de este repositorio.
___

## Problema 1

* Representar en un diagrama una clase con la siguiente problemática:
	* Entidad o Sustantivo: Trabajador
	* Atributos, características: 
	 	* nombres, 
	 	* apellidos, 
	 	* sueldo
	 	* dni
	* Comportamientos, métodos: 
		* establecerNombres
		* establecerApellidos
		* establecerSueldo
		* establecerDni
		* obtenerNombres
		* obtenerApellidos
		* obtenerSueldo
		* obtenerDni

> [!Note]
> Considerar: los datos y métodos deben ser públicos
> Agregar una colección de 4 objetos, e inicialicelos.

___

## Problema 2

* Se necesita representar mediante un diagrama de clase y objetos (4), una entidad que permite administrar Instituciones Educativas de Primaria. Cada institución tiene como características: nombre, tipo de institución, número de alumnos, número de docentes, número de aulas.
Se debe relacionar la clase con los objetos. 

> [!Note]
> - Los datos deben ser privados y los métodos públicos

___

## Problema 3

Para un sistema posterior, es necesario abstraer las características de dispositivos electrónicos como los son los Equipo Celulares. Cada Equipo Celular tienen como características: sistema operativo, tamaño de pantalla, costo, dirección mac, información IMEI. Se necesita representar mediante un diagrama de clase y objetos (3). No es necesario agregar los comportamientos en los objetos. Se debe relacionar la clase con los objetos. 

> [!Note]
> - Los datos deben ser protegidos y los comportamientos públicos

___ 

## Problema 4

Se requiere administrar los escenarios deportivos de la ciudad de Loja. Se ha realizado un análisis, cada escenario tiene propiedades como: nombre, número de espectadores, dirección, número de locales comerciales, número de puertas de entrada, número de camerinos. Se quiere realizar una representación entre la clase y 4 objetos.

> [!Note]
> - Los datos deben ser privados y los comportamientos privados

___ 

## Problema 5

Diseña una clase llamada Libro para gestionar la información de libros en una biblioteca. Cada libro tiene los siguientes atributos:

* Título
* Autor
* ISBN (International Standard Book Number)
* Año de publicación
* Número de páginas

La clase debe tener métodos para establecer y obtener cada uno de estos atributos. Además, debe incluir un método para mostrar toda la información del libro en formato legible.

> [!Note]
> - Es potestad de su análisis, determinar los niveles de acceso para los datos de este objeto.

___ 

## Problema 6

Diseña una clase llamada Pedido para gestionar los pedidos realizados en una tienda online. La clase debe permitir registrar la información relevante de un pedido, como los productos solicitados, la cantidad de cada producto, el total del pedido y la dirección de envío.

La clase debe incluir métodos para añadir productos al pedido, calcular el total del pedido, actualizar la cantidad de un producto, eliminar un producto del pedido y mostrar la información completa del pedido.

Este problema permite practicar el diseño de una clase para gestionar un aspecto específico de un sistema más amplio, como es el caso de los pedidos en una tienda online. La flexibilidad en el diseño de la clase permite adaptarla a las necesidades particulares del sistema. 

> [!Note]
> - Es potestad de su análisis, determinar los niveles de acceso para los datos de los objetos involucrados.
>
## Problema 7

Diseñe una clase en UML para representar un emprendimiento en la ciudad de Loja, considerando que cada emprendimiento posee un nombre comercial, RUC, sector económico (gastronomía, tecnología, moda, etc.), propietario, y ubicación. Además, debe contar con atributos que permitan registrar su fecha de inicio de actividades y capital inicial. La clase debe incluir métodos para actualizar información del emprendimiento, calcular su antigüedad en años y determinar si es un micro, pequeño o mediano negocio en función de su capital.

> [!Note]
> - Como resultado de su análisis, determinar los niveles de acceso para los datos de los objetos involucrados (atributos, constructores y métodos).
