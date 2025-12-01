# Caso-Practico-SQL
Consulta en base de datos de restaurant para su analisis 

## En el siguiente repositorio daremos solución al caso practico de SQL contestando las siguientes preguntas:

### Encontrar el número de artículos en el menú.
Respuesta: 32 articulos
### ¿Cuál es el artículo menos caro y el más caro en el menú?
Respuesta: Mas barato: Edamame ; Mas caro: Shrimp Scampi
### ¿Cuántos platos americanos hay en el menú?
Respuesta: 6 platos
### ¿Cuál es el precio promedio de los platos?
Respuesta: Precio promedio de 13.2859375000
### ¿Cuántos pedidos únicos se realizaron en total?
Respuesta: 5370 pedidos
### ¿Cuáles son los 5 pedidos que tuvieron el mayor número de artículos?
Respuesta: Chicken Parmesan
Chips & Salsa
Edamame
Eggplant Parmesan
Fettuccine Alfredo
### ¿Cuándo se realizó el primer pedido y el último pedido?
Respuesta: Primer pedido: 2023-01-01 ; Ultimo pedido: 2023-03-31
### ¿Cuántos pedidos se hicieron entre el '2023-01-01' y el '2023-01-05'?
Respuesta: 308 pedidos
### Reaccion de los clientes al menu
Respuesta: Con la ayuda del numero de veces pedido podemos ver que:
Hamburguer con 622 pedidos 
Edamame con 620 pedidos
Korean Bowl Beff con 588 pedidos 
Chesseburguer con 583 pedidos 
French Fries con 571 pedidos
Eso nos da a entender que esos platillos son los que los clientes reaccionan a favor de ellos.
## Para el ultimo inciso se utilizo un letf join para poder utilizar ambas tablas

### Identificar 5 puntos clave que puedan ser de utilidad para los dueños del restaurante en el lanzamiento de su nuevo menú.

### 1. Lo primero que consideraría es conservar los platillos que mas se venden en un top 5 que serían: 
Hamburguer con 622 pedidos 
Edamame con 620 pedidos
Korean Bowl Beff con 588 pedidos 
Chesseburguer con 583 pedidos 
French Fries con 571 pedidos
### 2. Ahora seria eliminar el top 5 de los menos vendidos ya que solo generarían gastos en insumos:
Chicken tacos con 123 pedidos.
Potstickers con 205 pedidos.
Chesse lasagna con 207 pedidos.
Steak tacos con 214 pedidos.
Chesse quesadillas con 233 pedidos.
### 3. Podemos agregar mas platillos a un top 3 de categorías de comida más vendida para este caso serían:
Asian con 3470 artículos vendidos.
Italian con 2948 artículos vendidos.
Mexican con 2945 artículos vendidos.
### 4. Ver que día es el que se vende menos y así poder aplicar alguna promoción:
Los miércoles es cuando se venden menos artículos con 1531 de artículos vendidos
### 5. Retomando parte del punto anterior podemos ver que artículos se llevan juntos y aplicar una promoción que con dichos productos juntos más X cantidad (en pesos) se pueden llevar otro producto:
Los 5 artículos que mas llevan juntos son los siguientes:
Hamburguer y edamame 90 veces juntos.
Chesseburguer y edamame 88 veces juntos.
Hamburguer y chesseburguer 85 veces juntos.
Korean beef bowl y edamame 79 veces juntos.
French fries y Korean beef bowl 78 veces juntos.

### Conclusion: 

Gracias al analisis de estos puntos que se consideraron de los mas importantes, se le puede orientar a los dueños sobre su nuevo menu con base en sus ventas, asi asegurar ventas satisfactorias, menos perdidas en platillos poco aceptados, poder ofrecer ofertas/combos y ampliar platillos sobre las categorias de comida preferida de los clientes. 





