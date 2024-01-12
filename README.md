# MercadoLibre-Data-Challenge

## Caso de negocio
El equipo comercial quiere realizar estrategias focalizadas para los sellers, pero en este
momento no existe una clasificación que permita identificar a aquellos que tienen un buen
perfil y son relevantes para el negocio. 
¿Cómo podrías ayudar al equipo comercial a identificar estos sellers?

## Ideas iniciales
Nos interesan los sellers que 
a) tienen un buen perfil y 
b) son relevantes para el negocio

### ¿Qué significa tener un buen perfil? 
- tener una buena 'seller_reputation'
- tener buenos ratings en los productos vendidos
### ¿Qué significa ser relevante para el negocio?
- tener un número alto de ventas concretadas
- tener una cantidad de dinero ingresado elevada

## Estrategia propuesta
Usar un modelo de aprendizaje no supervisado para clasificar sellers. Vamos a poder identificar distintos tipos de sellers de acuerdo a las variables de interés. Las variables de interés son las que determinan la reputación y el comportamiento del seller. 

También propongo clasificar a los sellers dentro de cada categoría, porque 'ser relevante para el negocio' puede estar en distintas escalas. 

## API de Mercado Libre
Usé tres fuentes de información:
- "https://api.mercadolibre.com/sites/" para obtener la lista de items en una categoría
- "https://api.mercadolibre.com/users/" para obtener los datos de reputación de los sellers
- https://api.mercadolibre.com/reviews/" para obtener el rating_average de cada producto

## Resultados
![image](https://github.com/XimenaZamora/MercadoLibre-Data-Challenge/assets/51669940/cc629ec6-bc73-42de-ab2e-deb551c34cd2)

