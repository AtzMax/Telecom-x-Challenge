# Telecom-x-Challenge
Este repositorio contiene el desarrollo del desafío del programa de formación en **Data Science de Alura LATAM (Oracle Next Education)**.
Este proyecto tiene como objetivo analizar la evasión de clientes (Churn) en una empresa de telecomunicaciones llamada TelecomX LATAM.

El análisis busca identificar patrones y factores que influyen en la cancelación del servicio, utilizando técnicas de limpieza de datos, análisis exploratorio y visualización.

El objetivo final es generar insights que permitan a la empresa mejorar sus estrategias de retención de clientes.

##  Objetivos
- Analizar la distribución de clientes que cancelan el servicio.
- Identificar variables categóricas relacionadas con el churn.
- Analizar variables numéricas que influyen en la evasión.
- Generar visualizaciones que faciliten la interpretación de los datos.
- Proporcionar insights para la toma de decisiones estratégicas.

## Análisis Exploratorio de Datos (EDA)

Se analizó la proporción de clientes que:
* permanecen en el servicio
  
*cancelan su suscripción

Este análisis permitió observar que la mayoría de los clientes permanece, pero existe un grupo significativo que cancela.

##  Herramientas Utilizadas

- **Python**
- **Pandas** (Procesamiento y limpieza de datos)
- **Matplotlib** (Visualización de datos)

### CONCLUSIÓN
El análisis conjunto de las variables categóricas y numéricas sugiere que los factores más asociados con la cancelación de clientes son:

* Tipo de contrato, especialmente los contratos mensuales.

* Tiempo de permanencia en el servicio (tenure), donde los clientes más nuevos tienen mayor probabilidad de cancelar.

* Nivel de cargos mensuales, que podría influir en la decisión de abandonar el servicio.

En contraste, variables como género muestran poca influencia en la evasión de clientes.

Estos resultados proporcionan información valiosa para diseñar estrategias de retención, como incentivar contratos de mayor duración o implementar acciones de fidelización durante los primeros meses de servicio.

### RECOMENDACIONES

* Incentivar el uso de pagos automáticos por transferencia o tarjeta, que muestran menores tasas de churn.
* Fidelización de clientes nuevos: Implementar programas de bienvenida, beneficios iniciales y ofertas de permanencia para clientes con menos de 12 meses.
* Contratos más atractivos a largo plazo: Promover planes anuales o bianuales con descuentos o beneficios exclusivos.
Revisión de cargos mensuales
* Analizar si los planes de mayor costo generan una percepción de sobreprecio que incentive la fuga.
Optimización de métodos de pago
