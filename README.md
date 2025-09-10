# Proyecto-1-Data-Analytics
# 📊 Análisis de datos y dashboard de reservas hoteleras (2015-2017)

## 🗒️ Descripción del proyecto

Este proyecto resume el desempeño de las reservas de un hotel entre 2015 y 2017. El objetivo es ofrecer una visión ejecutiva y operativa del volumen de reservas, mix de canales y segmentos, comportamiento de las reservas en el tiempo, y métricas clave como el ADR, la estancia media y el lead time.

Consiste en una visualización que transforma los datos iniciales en bruto en indicadores operativos que permitan una rápida lectura del rendimiento del negocio, en este caso dividido entre dos hoteles diferentes, el “City Hotel” y el “Resort Hotel”.

### Problema que resuelve

El dashboard responde a la necesidad de visibilidad inmediata sobre:

- Demanda (reservas por mes y año, y país de origen del cliente)
- Tarifa media diaria (ADR)
- Tasa de cancelaciones sobre reservas realizadas
- Anticipación de las reservas
- Mix comercial (por canales de distribución y segmentos de mercado)

### Enfoque y técnicas utilizadas

Se ha realizado un análisis descriptivo en el que se ha trabajado con las columnas originales del dataset para calcular KPIs principales de negocio como los ingresos totales, la tarifa media diaria ponderada o la tasa de cancelaciones, y se ha llevado a cabo una limpieza de los datos para evitar obtener conclusiones érroneas por valores duplicados.

Apunte: los datos registran las reservas desde enero de 2015 hasta agosto de 2017, por lo que las comparativas año con año se realizan filtrando por periodo: desde enero de 2017 hasta agosto 2017 frente a enero 2016 hasta agosto 2016.

## 🗂️ Estructura del proyecto

— dashboard: hoja con los gráficos y slicers

— tablas dinámicas: hoja con las tablas que alimentan el dashboard

— raw data: dataset utilizado 

— README.pdf: descripción del proyecto

## 🖥️ Instalación y Requisitos

Para visualizar los datos e interactuar con las tablas y gráficas únicamente es necesario disponer de Excel (2016 o superior).

## 📈 Resultados y Conclusiones

### KPIs principales

Los datos de **reservas** entre enero y agosto 2017 vs el año anterior muestran que crece ligeramente el volumen (+2,2% YoY), aunque se observa también un incremento considerable en la **tasa de cancelaciones**, llegando a ser 41,8% de las reservas en 2017 (+72,2% YoY). A pesar de que este aumento en las cancelaciones, el ADR y los ingresos aumentaron en 2017. 

Adicionalmente, la **antelación media de reserva** son 89 días, lo que supone una ventana de compra amplia compatible con tácticas como aplicación de tarifas early-bird para asegurar demanda con tiempo y reducir la tasa de cancelación.

En base a estos KPIs, la prioridad operativa debe ser reducir cancelaciones sin disminuir el ADR y nivel de ingresos conseguidos.

### Estacionalidad

Se observa en las gráficas de reservas e ingresos una estacionalidad con picos de reservas en verano y valles a principios del año. 

### Tipo de hotel: City vs Resort

El City Hotel tiene un mayor número de reservas de media y un mayor ADR, pero también una tasa de cancelaciones más alta que el Resort Hotel. Por tanto, el foco está en reducir las cancelaciones sin erosionar el ADR en el City Hotel, mientras se eleva el ADR en el Resort Hotel, alargando las estancias, entre otros factores.

### Mix comercial

El segmento de mercado que domina es el Online TA, seguido de Offline TA/TO, Groups y Direct.

En cuanto a los canales de distribución, prevalece TA/TO, seguido de Direct y Corporate con menor peso, lo que indica una alta dependencia de intermediación y por tanto una oportunidad para crecer en el canal directo.

### Geografía

Los top 5 países por ADR, que a su vez cuentan con más de 50 reservas, son España, Rusia, Rumanía, Suiza y Estados Unidos. Teniendo esta información sobre los países en los que se concentra el mayor volumen de reservas y que tienen un ADR más alto, se pueden valorar estrategias de geo-pricing, especialmente en temporada alta.

### ➡️ Próximos pasos

De continuar con el análisis, los próximos pasos deben centrarse en aplicar los insights obtenidos de los datos en la estrategia de cara a la próxima temporada.

### 🖋️ Autores

Cristina Díaz Castillo
