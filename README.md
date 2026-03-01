# Probabilidad y muestreo

### 1. Distribuciones de Probabilidad

*   **Distribución Binomial:** Se exploró cómo trabajar con la probabilidad binomial, incluyendo el cálculo de su media y desviación estándar.
*   **Distribución de Poisson:** Se aprendió a identificar y aplicar la distribución de Poisson en diversos contextos, diferenciándola de la binomial.
*   **Distribución Normal:** Se cubrieron las características de la distribución normal, su estandarización, la construcción de tablas de valores normalizadas y cómo utilizarlas para calcular probabilidades y obtener valores relevantes.

### 2. Técnicas de Muestreo

*   **Población y Muestra:** Se estableció la diferencia fundamental entre estos dos conceptos estadísticos.
*   **Uso de Muestras:** Se discutieron las situaciones en las que es más apropiado utilizar una muestra en lugar de un censo.
*   **Tipos de Muestreo:** Se estudiaron las tres técnicas de muestreo más comunes:
    *   Muestreo aleatorio simple
    *   Muestreo estratificado
    *   Muestreo por conglomerados

### 3. Estimación

*   **Teorema Central del Límite:** Se interpretó y aplicó este teorema fundamental en estadística.
*   **Niveles de Confianza y Significancia:** Se comprendieron estos conceptos esenciales para la inferencia estadística.
*   **Error Inferencial:** Se analizó el concepto de error inferencial en la estimación.
*   **Intervalos de Confianza:** Se aprendió a construir e interpretar intervalos de confianza para la media poblacional.

### 4. Cálculo del Tamaño de la Muestra

*   Se abordó cómo calcular el tamaño de la muestra necesario tanto para poblaciones finitas como para poblaciones infinitas.
*   Se detalló cómo determinar el error de la muestra y el margen de error, así como la interrelación entre el error y el tamaño de la muestra.

## Descripción del Conjunto de Datos

### Encuesta Nacional por Muestreo de Hogares - 2015

La **Encuesta Nacional por Muestreo de Hogares - ENMH** en Brasil anualmente investiga, de manera permanente, características generales de la población, educación, trabajo, ingresos, vivienda y otras, con frecuencia variables, de acuerdo a las necesidades de información del país, tales como las características de migración, fecundidad, nupcialidad, salud, seguridad alimentaria, entre otros temas. La recopilación de estas estadísticas constituye, durante los 49 años de realización de la investigación, un importante instrumento para la formulación, validación y evaluación de políticas orientadas al desarrollo socioeconómico y la mejora de las condiciones de vida en Brasil.

### Fuente de los Datos

Instituto Brasileño de Geografía y Estadística (IBGE) Encuesta Nacional por Muestreo de Hogares(PNAD) en el 2015

#### <font color='red'>Nota</font>
***
> Se realizaron los siguientes tratamientos sobre los datos originales:
> 1. Se eliminaron los registros en los que **Ingreso** no era válido. (999 999 999 999);
> 2. Se eliminaron los registros en los que **Ingreso** eran missing;
> 3. Solo se consideraron los registros de **Personas de Referencia** de cada hogar (responsable del hogar).

## Ejemplos y Problemas Prácticos Destacados

### Distribución Binomial

*   **Competencia de Científico de Datos:** Calcular la probabilidad de acertar 5 de 10 preguntas de opción múltiple (3 alternativas) al adivinar, y la probabilidad de pasar (acertar 5 o más).
*   **Mega Sena:** Calcular la probabilidad de ganar la lotería (elegir 6 de 60 números).
*   **Exposición de Premios de Alura:** Determinar el número de combinaciones posibles y la probabilidad de ganar un premio eligiendo 20 de 25 números.
*   **Yincana:** Estimar cuántos equipos de 12 personas deberían tener 8 mujeres, dada una proporción del 60% de mujeres participantes.
*   **Hijos con Ojos Azules:** Calcular cuántas de 50 familias con 3 hijos se espera que tengan dos hijos con ojos azules, si la probabilidad de tener ojos azules es del 22%.

### Distribución de Poisson

*   **Delivery de Restaurante:** Calcular la probabilidad de recibir exactamente 15 pedidos en una hora, si el promedio es de 20 pedidos por hora.
*   **Panadería:** Obtener la probabilidad de que entren exactamente 25 clientes en la próxima hora, si el promedio es 20 clientes por hora.

### Distribución Normal

*   **Altura de Residentes:** Calcular probabilidades para alturas de personas (menor de 1.80m, entre 1.60m y 1.80m, y mayor de 1.90m) dada una media de 1.70m y desviación estándar de 0.1m.
*   **Puntuaciones de Prueba Estadística:** Probabilidad de que un estudiante obtenga una puntuación inferior a 85, con media de 70 y desviación estándar de 5.
*   **Facturación Diaria de un Conductor:** Probabilidad de ganar entre \$250 y \$350, o entre \$400 y \$500, con facturación normal de media \$300 y desviación estándar \$50.
*   **Vida Útil de Lámparas:** Calcular la probabilidad de que una lámpara dure entre 650 y 750 días, más de 800 días, o menos de 700 días, con vida útil normal de media 720 días y desviación estándar 30 días.
*   **Área bajo la Curva Normal:** Encontrar el área para diferentes valores de Z (Z < 1.96, Z > 2.15, Z < -0.78, Z > 0.59).

### Estimación

*   **Pesos de Bolsas de Arroz:** Construir un intervalo de confianza del 95% para la media poblacional del peso de bolsas de arroz, con una muestra de 20 bolsas (media 5050g, desviación estándar poblacional 150g).
*   **Gasto de Clientes en Comida Rápida:** Obtener el margen de error para la estimación del gasto medio de clientes, con una muestra de 50 clientes (desviación estándar poblacional \$6) y un nivel de confianza del 95%.
*   **Media Muestral y Intervalo de Confianza:** Calcular el intervalo de confianza del 90% para la media poblacional, dada una muestra de 1976 elementos (media muestral 28, desviación estándar 11).

### Cálculo del Tamaño de la Muestra

*   **Ingresos Mensuales de Jefes de Hogar:** Determinar el tamaño de la muestra necesario para estimar el ingreso medio mensual con un error máximo de \$10 y un nivel de confianza del 95%, dada la desviación estándar poblacional de \$1082.79.
*   **Contenido de Latas de Gaseosa (Población Finita):** Calcular el tamaño de la muestra para estimar la media poblacional del contenido de latas, con un lote de 10,000 latas, desviación estándar muestral de 12ml, error máximo de 5ml y nivel de confianza del 95%.
*   **Peso de Sacos de Harina:** Determinar el tamaño de la muestra para estimar el promedio poblacional del peso de sacos de harina, en un lote de 2000 sacos, con una desviación estándar muestral de 480g, error máximo de 0.3kg y nivel de confianza del 95%.

### Problemas Prácticos Integrales

*   **Evaluación de Ingresos de Jefes de Hogar en Brasil:** Un problema multifacético que involucra:
    1.  Muestreo aleatorio simple para estimar parámetros.
    2.  Cálculo de tamaños de muestra para diferentes niveles de confianza (90%, 95%, 99%) dado un margen de error fijo.
    3.  Determinación del costo de la encuesta para cada nivel de confianza.
    4.  Cálculo de un intervalo de confianza para la media de la población con el nivel de confianza más alto viable dentro de un presupuesto.
    5.  Evaluación del margen de error posible con todos los recursos disponibles para un nivel de confianza dado.
    6.  Estimación del costo para un margen de error y nivel de confianza específicos.
