# 📊 Análisis de perdida de clientes de TelecomX

Este proyecto analisa a los clientes de la empresa TelecomX con el fin de encontrar los diversos factores y poder ofrecer distintas soluciones al problema de la perdida de clientes por la cual pasa la compañia

## 📂 Datos utilizados
Los datos provienen del archivo JSON disponibles en GitHub:


- **[TelecomX_LATAM](https://github.com/Yovan05/TelecomX_LATAM/blob/ea8ac77a825c0886dc77ec31ba20f2092a907787/TelecomX_Data.json)**

El archivo contiene:
- `customerID`: número de identificación único de cada cliente
- `Churn`: si el cliente dejó o no la empresa
- `gender`: género (masculino y femenino)
- `SeniorCitizen`: información sobre si un cliente tiene o no una edad igual o mayor a 65 años
- `Partner`: si el cliente tiene o no una pareja
- `Dependents`: si el cliente tiene o no dependientes
- `tenure`: meses de contrato del cliente
- `PhoneService`: suscripción al servicio telefónico
- `MultipleLines`: suscripción a más de una línea telefónica
- `InternetService`: suscripción a un proveedor de internet
- `OnlineSecurity`: suscripción adicional de seguridad en línea
- `OnlineBackup`: suscripción adicional de respaldo en línea
- `DeviceProtection`: suscripción adicional de protección del dispositivo
- `TechSupport`: suscripción adicional de soporte técnico, menor tiempo de espera
- `StreamingTV`: suscripción de televisión por cable
- `StreamingMovies`: suscripción de streaming de películas
- `Contract`: tipo de contrato
- `PaperlessBilling`: si el cliente prefiere recibir la factura en línea
- `PaymentMethod`: forma de pago
- `Charges.Monthly`: total de todos los servicios del cliente por mes
- `Charges.Total`: total gastado por el cliente

## 🛠 Tecnologías utilizadas
- **Python** como lenguaje de programacion
- **Pandas** para la manipulación de datos
- **Numpy** para la manipulacion de datos
- **Matplotlib** para la visualización gráfica
- **Seaborn** para estilizar las graficas
- **Plotly** para la visualizacion de graficas dinamicas   
- **Google collab** para la ejecución y documentación del análisis
  
## 📋 Secciones del proyecto

1. **Importación de datos**  
   Se subio el archivo a Google collab y desde ahi se cargo el archivo de la base de datos usando `pd.read_json`.

2. **Transformacion**  
   Se analizaron los datos y posteriormente se limpiaron y depuraron de tal forma que se eliminaran las inconsistencia y se tranformaron los tipos de datos paara una mejor manipulacion de los mismos.

3. **Carga y analisis**  
   Se cargaron los datos ya procesados para su posterior analisis en cada aspecto del mismo, para que con ello poder detectar distintos patrones y diferencias que pudieran llevar a entender los factores de la perdida de clientes, esto se vio representado a traves de graficos.

4. **Informe Final**  
   Se recopilaron los datos recabados y se expusieron en este apartado de forma de que quedara mas claro todos los hallazgos encontrados.

5. **Conclusiones**  
   Se procesaron los datos recabados y se sacaron conclusiones a traves de ellos para determinar las causas de la perdida de clientes.

6. **Recomendaciones**  
   En base a las conclusiones obtenidas, se propusieron diferentes estrategias para poder combatir la perdida de clientes.
