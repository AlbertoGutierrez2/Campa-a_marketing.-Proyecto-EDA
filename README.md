# Campaña_marketing.-Proyecto-EDA
Proyecto EDA con Python para una campaña de marketing directo de una institución bancaria portuguesa

## Tabla de Contenidos
### 1. Introducción
### 2. Elaboración del proyecto (pasos seguidos)
### 3. Informe

### 1. Introducción

El objetivo del proyecto es analizar los datos propuestos relacionados con campañas de marketing directo de una institución bancaria portuguesa que reflejan información sobre las características demográficas y comportamiento de compra de los clientes del banco para determinar tendencias, posibles patrones, establecer posibles relaciones entre las características del cliente (edad, ocupación, nivel educativo, nivel de ingresos...) y la contratación del producto objecto de la campaña de marketing (depósito a plazo bancario).

### 2. Elaboración del proyecto (pasos seguidos)

Para la elaboración del proyecto se han seguido los siguientes pasos:

  #### 2.1 Transformación y limpieza de los datos.
  #### 2.2 Análisis descriptivo de los datos.
  #### 2.3 Visualización de los datos.
  #### 2.4 Informe explicativo del análisis.

En cuannto a la transformación de los datos se han unido ambos dataframes en uno solo, se han eliminado las variables que a mi juicio no aportaban valor y se ha llevado a cabo la gestión de nulos imputando estos con valores representativos, aunque en la mayoría de los casos se ha optado por imputar un valor neutro (0) para no falsear los datos en la medida de lo posible.

A lo largo del proyecto se ha recurrido a visualización de los datos con distintos tipos de gráficos para analizarlos y, finalmente, en el último apartado llamado "Relaciones cruzadas, análisis y conclusiones" se muestran los gráficos sobre los que se sustenta el análisis del proyecto.

### 3. Informe

Del análisis de los gráficos expuestos en el último apartado "Relaciones cruzadas, análisis y conclusiones" se establecen las siguientes conclusiones:

3.1. La mayoría de los clientes tienen una edad comprendida entre 20 y 60 años, situándose la medía en torno a los 40 años de edad. En cuanto a la relación entre el nivel educativo y la edad se puede inferir del gráfico 1 que entre los 20 y 25 años la mayoría de los clientes tienen un nivel educativo de basic.9y o high.school, es decir educación básica o secundaria, mientras que entre los 30 y 45 años la tendencia suele ser clientes con formación universitaria (university.degree).

3.2. En el segundo gráfico podemos analizar la duración de la última interacción con el cliente en relación con su edad y las conversiones realizadas (y), es decir los clientes que han suscrito finalmente un producto o servicio. En este caso podemos observar que en las interacciones con una duración entre 600 y 1800 segundos es donde se produce el mayor número de conversiones en clientes de edades comprendidas entre 20 y 60 años. Sin embargo, a partir de los 60 años se acorta un poco la duración, encontrándose el mayor número de conversiones en aquellas interacciones con una duración entre 100 y 900 segundos.

3.3. En el tercer gráfico podemos analizar el número de contactos realizados (campaign) según el nivel educativo, encontrando que los mayores contactos se realizan a clientes con formación universitaria, educación secundaria, educación básica y formación profesional en este orden. De la misma forma, el cuarto gráfico muestra una proporción muy similar en cuanto al nivel de ingresos y formación.

3.4. El 5º, 6º y 7º gráfico establecen la relación entre ocupación y número de contactos realizados (campaign), ingresos y duración de la interacción, siendo en este order: administrativos, obreros y técnicos las profesiones donde se realizan más contactos, las que tienen mayor nivel de ingresos y donde la duración de la interacción es mayor.

3.5. El gráfico 8º muestra que el mayor número de interacciones se llevaron acabo entre el año 2015 y 2020.

3.6. Analizando el gráfico 9 y 10 se puede concluir que el mayor número de contactos y de conversiones se realizaron a través del teléfono, sin embargo la tasa de conversión (porcentaje de usuarios que realizan una compra tras la interacción) es similar a los contactos realizados con teléfono móvil. Por último, el número de visitas de clientes a la web cuando el contacto se realiza mediante teléfono es mayor que cuando la interacción se lleva a cabo a través de teléfono móvil.

3.7. En relación con el estado civil del cliente, el mayor número de contactos, y por consiguiente, el mayor número de visitas a la web se realiza por parte de personas casadas, seguidas de solteras y divorciadas en tercer lugar (gráficos 11 y 12).

3.8. El gráfico 13 relaciona el número de contactos realizados (campaign) con la duración de los mismos y la conversión (y). Como podemos observar en los clientes en los que se lleva a cabo entre 0 y 10 interacciones con una duración entre 600 y 1.800 segundos (es decir, entre 10 y 30 minutos aprox.) es la franja donde se da el mayor número de conversiones.
Asimismo, el gráfico 14 nos confirma que el mayor número de conversiones se da entre 0 y 10 interacciones con el cliente, siendo mayor en los casos en los que se había contactado al cliente al menos 1 vez antes de esta campaña. Aquellos casos en los que se había contacto previamente hasta 5 veces es la franja donde el número de conversiones es mayor.

3.9. El gráfico 15 y 16 nos confirman que el mayor número de contactos realizados (campaign) y, por consiguiente, el mayor número de visitas mensuales a la web se da en usuarios con edades comprendidas entre 20 y 60 años, situándose el número de contactos realizados durante esta campaña entre los usuarios de esta franja de edad, entre un mínimo de 1 y un máximo de 20 contactos, en la mayoría de los casos.

3.10. El gráfico 17 nos indica la relación entre la profesión, la duración del contacto realizado en segundos y la conversión (y). Este gráfico, que estaría relacionado con el segundo gráfico y con el gráfico 13, nos confirma que en las interacciones con una duración entre 600 y 1800 segundos, es decir entre 10 y 30 minutos, es donde se da el mayor número de conversiones con independencia de la profesión del cliente.

3.11. Por último, el gráfico 18 nos indica la relación entre el estado civil, edad y si el cliente tiene o no contratado un préstamo hipotecario. Como se puede observar, los clientes casad@s de todas las edades, y los clientes divorcid@s con edades comprendidas entre 60 y 90 años, es el perfil de clientes que tienen contratado un préstamo hipotecario.





















