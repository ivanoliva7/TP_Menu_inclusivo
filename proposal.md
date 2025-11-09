# Propuesta TP DSW

## Grupo
### Integrantes
* 52115 - Soria, Marian Luz
* 52362 - Baistroqui, Lucas
* 53009 - Oliva, Ivan

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)

## Menú-Inclusivo
### Descripción
Menú-Inclusivo es una plataforma web diseñada para conectar a las personas con necesidades alimenticias específicas con restaurantes que ofrecen opciones adaptadas a sus dietas. Para poder realizar pedidos en línea a través de la plataforma, solo necesitás crear tu usuario. Esto nos permite personalizar tu experiencia, guardar tus preferencias y mostrarte recomendaciones acordes a tus necesidades.

### Modelo
![imagen del modelo](%3CmxGraphModel%3E%3Croot%3E%3CmxCell%20id%3D%220%22%2F%3E%3CmxCell%20id%3D%221%22%20parent%3D%220%22%2F%3E%3CmxCell%20id%3D%222%22%20value%3D%221%3A1%22%20style%3D%22text%3BstrokeColor%3Dnone%3BfillColor%3Dnone%3BspacingLeft%3D4%3BspacingRight%3D4%3Boverflow%3Dhidden%3Brotatable%3D0%3Bpoints%3D%5B%5B0%2C0.5%5D%2C%5B1%2C0.5%5D%5D%3BportConstraint%3Deastwest%3BfontSize%3D11%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3BfontFamily%3DHelvetica%3BfontColor%3Ddefault%3BlabelBackgroundColor%3Ddefault%3B%22%20vertex%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20x%3D%22220%22%20y%3D%22490%22%20width%3D%2240%22%20height%3D%2230%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3C%2Froot%3E%3C%2FmxGraphModel%3E)

## Alcance Funcional 

### Alcance Mínimo


Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario <br>2. CRUD Local <br>3. CRUD Preferencia|
|CRUD dependiente|1. CRUD Comida {depende de} CRUD Local <br>2. CRUD Precio {depende de} CRUD Comida|
|Listado<br>+<br>detalle| 1. Listado de Menu filtrado por local=> detalle muestra el conjunto de comidas de un local <br> 2. Listado de locales filtrado por preferencias => detalle muestra datos completos del local
|CUU/Epic|1. Personalizar usuario <br>2. Gestionar restaurante|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Comida|
|CRUD dependiente|1. CRUD Reseña {depende de} CRUD Usuario y CRUD Local|
|CUU/Epic|1. <br>2. |


### Alcance Adicional Voluntario


|Req|Detalle|
|:-|:-|
|Listados ||
|CUU/Epic||
|Otros||

