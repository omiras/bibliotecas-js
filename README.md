# Bibliotecas JavaScript

Una de las habilidades más importantes como programadores es saber utilizar otros componentes que nosotros mismos no hemos creado

Usa esta bilbioteca que permite [renderizar gráficos estadísticos](https://plotly.com/javascript/) de forma sencilla.

En este ejemplo, vemos un gráfico que muestra el precio medio de una viviendo según sus meotros cuadrados de superficie.

## Ejercicios

### Apartado 1: Identificar variables 
Pon un comentario en cada una de las variables presentes dentro del tag \<script> del fichero index-ploty.html. Indentifica qué tipo de dato contiene CADA UNA de las variables, y si puedes, el tipo de información que parece contener.

Ejemplo:


```
// Array de numbers. Contiene cada uno de los valores de la coordenada X
var xArray = [50, 60, 70, 80, 90, 100, 110, 120, 130, 140, 150];
```

### Apartado 2: Modificaciones
Nos han pedido una serie de modificaciones sobre el gráfico existente. Consulta la documentación de la biblioteca para realizar los siguientes cambios.

[Ejemplo del aspecto aproximado que se espera conseguir](https://oscarm.tinytake.com/msc/Njg4NDQwNF8xOTU1NzYwOQ)

1. Queremos añadir una nueva relación metros cuadrados-precio. Nos dicen que si una casa tiene 160 metros cuadrados, la casa debería valer 16 mil euros. Modifica las variables adecuadamente para conseguir plasmar este nuevo dato en la gráfica
2. Les gustaría que el texto de las leyendas aparecieran en español (cambialo manualmente). 
3. Queremos cambiar los marcadores. Fíjate que ahora son de color azul, pequeñitos y en forma de círculo. Cambialos a:
   1. Color verde
   2. Forma de diamante
   3. Y que sean un poco más grandes que los actuales
4. Siéntete libre de experimentar con la bilbioteca y cambiar o añadir cualquier otro dato, configuración o parámetro.

### Apartado 3: BONUS

Crea un formulario que permita añadir nuevas coordenadas X,Y al gráfico actual. Debes crear el formulario en HTML primero.

1. El formulario debe contener dos campos, valor de la X y valor de la Y
2. Aplica las validaciones que creas convenientes
3. Recuerda que hay que asociar un evento de tipo 'submit' al formulario
4. Deberás actualizar las variables xArray y yArray con el valor de los campos del formulario
5. Es necesario volver ejecutar la instrucción `    Plotly.newPlot("myPlot", data, layout);` para actualizar el gráfico.

### Apartado 4

Crea un nuevo gráfico de tipo [pastel](https://oscarm.tinytake.com/msc/Njg4NDQwNF8xOTU1NzYwOQ) en el fichero "ejercicio-2-pie.html". Nos han pedido crear un gráfico con los 5 principales lenguajes de programación del lado back end.

1. PHP :44%
2. JavaScript: 33%
3. Python: 20%
4. Otros: 3%

Deberas implementar toda la estructura necesaria para crear el gráfico en el fichero  "ejercicio-2-pie.html". Recuerda que es esencial cargar la biblioteca Ploty para poder usarla; y generar la estructura HTML y JS. Busca en la documentación de Ploty cómo crear gráficos de tipo pastel.
