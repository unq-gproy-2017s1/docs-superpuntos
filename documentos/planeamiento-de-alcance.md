# Planeamiento de alcance

## Breve Descripción


El proyecto constara de un sistema de fidelización de clientes para un supermercado, el cual permite canjear ciertos productos a cambios de puntos obtenidos por compra.   
La gestion consta de dar a los clientes puntos por cada compra los cuales podrán ser canjeados por premios.
Los puntos a obtener estarán en función de los productos comprados, cantidades e importes. Un punto se obtiene por un total de 4 pesos comprados, ademas puede pasar que en intervalos de tiempo un producto duplique triplique la cantidad de puntos que corresponden por su valor, entre otras posibilidades.


## Justificación

Una gran cantidad de cadenas de supermercados ha experimentado un mayor crecimiento de ventas y clientes gestionando de manera automatica el consumo total de productos, promociones y canjes por parte de los usuarios. Los años de experiencia y graficas creadas a partir de estas estiman que el consumo de los seres humano puede ser persuadido o influenciado a consumir ciertos productos por la "necesidad" misma.

Nuestro porfolio de clientes con perfiles similares nos indica que sistemas de este estilo ayudan a la retención en masa de clientes así como a aumentar la cantidad de productos promedio por cliente.

Nuestra empresa garantiza a los clientes cierto nivel de confiabilidad y soporte a largo plazo del producto finalizado.

## Producto

El producto consistirá en:

### Gestión de puntos:

El sistema que se propone permitira a los encargados de marketing diseñar, desarrollar y componer las promociones y ofertas en base a distintos criterios como por ejemplo:
  * Multiplicar la cantidad de puntos correspondientes a un producto
  * Combos de productos por un determinado periodo de tiempo
  * Descuentos sobre productos a cambio de puntos

### Integración con el sistema de facturación existente
El proyecto estara preparado para iteractuar con el sistema de facturacion y transacciones en uso, la integracion planteada sera transparente al usuario final de la aplicacion, ya sea en la linea de cajas o en los centros de atencion al cliente.

### Integración con el sistema de stock existente
El proyecto se integrara al sistema actual de stock que cada supermecado posee. Esto ayudara a preveer posibles fallos en el canje de cupones o puntos por productos de los cuales no hay stock. Ademas podra ser usado para recrear una posible grafica sobre los productos canjeados.

### Subsistema para la carga de promociones y ofertas
El proyecto permitira al supervisor del supermercado actualizar de manera diaria las ofertas y promociones. Aprovechando dias festivos, semanas especiales, entre otras actividas culturales, asi maximizar la venta de los productos.

### Arquitectura escalable a múltiples sucursales (en caso de ser necesario)
La experiencia obtenida de los multiples proyectos en los que trabajo nuestra compañia nos indica que un producto efectivo suele requerir ser integrado en diversas sucursales. Por este motivo vemos una gran ventaja brindandole al proyecto la capacidad de interactuar y administrar los datos y/o graficas sobre las ventas y canjes desde una o mas sucursales.

## Lista de objetivos del proyecto

* Proteger la información personal de los clientes
    Como es de esperar en estos tiempos, un software sin seguridad es un potencial objetivo de explotacion por parte los hackers. Pudiendo de manera facil alterar, robar, dañar o secuestrar datos vitales de las sucursales.

* Brindar soporte estadístico sobre el impacto de las ventas
    Como mensionamos anteriormente, el buen manejo de la informacion puede proveer estadisticas sobre el consumo de los clientes, indicando que puntos de ventas son viables para explotar.

* Interfaz intuitiva para el cliente
    Brindarle al usuario final una interfaz intuitiva y facil de usar ayuda en gran medida a la adaptabilidad del mismo al proyecto y asi mantener una forma estandar de uso.

* Garantizar la consistencia de los datos
    En muchas ocaciones, los datos suelen ser dañádos, alterados o simplemente mal actualizados. Es por esto que permitiremos al cliente visualizar los cambios que fueron obteniendo a traves del tiempo y verificar su validez.

## Restricciones y supuestos

* Estabilidad en la red del negocio
    Ya que el proyecto consta de un sistema de manejo delicado de informacion, es requerido que la compañia a usarlo brinde un buen servicio de red entre los operarios.

* Conexión entre sucursales
    Si bien el sistema proporcionara la capacidad de ser utilizado de forma simultanea en diferentes sucursales, es requerido que se provea alguna forma de conexion entre ellas.

* Sistema de facturación existente
    Nuestro proyecto dependera del sistema de facturacion existente para contabilizar y operar los puntos de manera correcta.

* El sistema necesita Windows para su ejecución
    Aprovechando que, actualmente mas del 50% de los usuarios de sistemas operativos siguen eligiendo windows. El sistema sera implementado solo para esta plataforma, dependiendo asi del mismo para utilizarlo.

## Entregables

1. Manual de usuario

2. Capacitación

3. Soporte

4. Puesta en producción

## Criterio de finalización

* Aumento en la retención de clientes

* Plazo de entrega del sistema cumplido
