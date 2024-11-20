# <h1 align='center'> **Henry DataPT11 - Proyecto Individual 02** </h1>
# <h1 align="center">**Telecomunicaciones**</h1>

### Tabla de contenido
1. [Descripción](#descripción)
2. [Requisitos](#requisitos)
3. [Estructura del Proyecto](#estructura-del-proyecto)
4. [Datos y Fuentes](#datos-y-fuentes)
5. [Metodología](#metodología)
6. [Insights](#insights)
7. [Conclusiones](#conclusiones)
8. [Recomendaciones](#recomendaciones)
9. [KPI's propuestos](#kpis-propuestos)
10. [Autor](#autor)

### Descripción
Este proyecto tiene como objetivo realizar un análisis completo del comportamiento del sector telecomunicaciones a nivel nacional y provincial en Argentina, con el fin de orientar a la empresa a identificar tendencias y oportunidades de crecimiento en la oferta de accesos a internet a la población. Mediante el análisis de los datos disponibles, se generaran insights de los que se extraerán conclusiones y recomendaciones a seguir para capitalizar las oportunidades encontradas.

### Requisitos
- Python 3.7 o superior
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Estructura del Proyecto
- `EDA.ipynb`: Análisis exploratorio de los datos.
- `HenryPI02.pbix` : Dashboard para el cliente.
- `README.md`: Resumen del proyecto.

### Datos y Fuentes
- Fuente: Los datos fueron obtenidos de la página del Ente Nacional de Comunicaciones (ENACOM) de Argentina. La ENACOM es el organismo regulador de las telecomunicaciones en Argentina, responsable de la regulación y control de los servicios de comunicación en el país.
- Datos: [Datasets](https://indicadores.enacom.gob.ar/datos-abiertos)

### Metodología
Se realizó revision de los datasets, busqueda de valores nulos, erróneos, faltantes, duplicados. Corrección de errores e imputación de valores. Graficos de lineas para observar el comportamiento de las variables a través del tiempo y mapas de calor para observar la correlacion entre los diferentes atributos.

### Insights
- El número de accesos a telefonía fija y conexión a internet mediante ADSL disminuye con el tiempo.
- El numero de accesos a internet mediante cablemodem (misma infraestructura de television por cable) tiende a aumentar a través del tiempo.
- La fibra óptica muestra crecimiento exponencial en todas las provincias a partir del rango de años entre 2019-2022.

### Conclusiones
- La telefonía fija, y por ende, el ADSL, son tecnologías que están siendo descartadas por los consumidores argentinos.
- La demanda de internet mediante cablemodem es creciente, independientemente del comportamiento de su compañera de infraestructura: la televisión por cable.
- Los proveedores de fibra óptica fueron los mas beneficiados de las consecuencias de la pandemia.

### Recomendaciones
- No invertir en ADSL ni en telefonía fija, ya que son tecnologías que están quedando obsoletas y el público es consciente de ello.
- Invertir en otras tecnologías de acceso a internet, en especial cablemodem y fibra óptica.

### KPI's propuestos
1. Aumentar en 1% la proporcion de la cobertura de acceso a internet mediante cablemovil a internet con respecto al total de accesos a television por cable, para el proximo trimestre, por provincia.
2. Aumentar en 5% el numero total de accesos a internet mediante fibra óptica a internet, para el proximo trimestre, por provincia.
3. Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia.

### Autor
Samuel Antonio Rangel - Contacto: [LinkedIn](https://www.linkedin.com/in/samuel-antonio-rangel-sar021/)