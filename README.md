#TRABAJO FINAL OPEN DATA UPA 2022
Presentado por Matthew Fehr

Componente 2: Publicación de Datos Abiertos
Este componente del código tiene cómo el objetivo de extraer datos abiertos de la web utilizando los métodos de 
scrapeo estudiado durante las clases. Estos datos entoces podrían servir de alguna manera para el desarrollo o mejoro 
de un negocio.

Primeramente vamos a importar las librerias necesarias. El código está en este caso preparado para scrapear los primero 5
páginas de la categoría celulares del portal de "comprasparaguai.com.br". 
Después de traer todo el contenido de las páginas de celulares, vamos a filtrar solamento la información que nos sea útil 
y la cuál deseamos. Para eso nos enfocamos en los contenedores de cada artículo de celular. De esos contenedores entonces
sacamos el nombre del artículo y su precio respectivo.
Esto entonces guardamos en una lista y después lo convertimos en un dataframe.
Para que nos sirve aún mejor, realizamos una limpieza básica de los datos, sacando la palabra "celular" de cada nombre y
convertiendo el string del precio en un valor numérico.

Esos datos entonces exportamos a un archivo CSV en este caso llamado "comprasparaguai_celulares.csv"

