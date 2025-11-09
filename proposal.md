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
![imagen del modelo](https://github.com/user-attachments/assets/6d37590d-1302-44d7-a34c-e5a6e036d589)

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

