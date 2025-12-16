TelecomX LATAM - Análisis de Churn

Descripción

En este notebook se realizará un análisis exploratorio de datos para entender los patrones y tendencias en el dataset de clientes de TelecomX LATAM. El objetivo es identificar factores que puedan influir en el churn de los clientes. El churn se define como la cancelación de un servicio por parte de un cliente. Esto afecta directamente a la rentabilidad de la empresa ya que la pérdida de clientes implica una disminución en los ingresos recurrentes, mayores costos de adquisición para reemplazarlos y posibles impactos negativos en la reputación de la marca.

🎯 Contexto del Negocio

La retención de clientes es un pilar fundamental para el éxito en la industria de las telecomunicaciones. Adquirir un nuevo cliente es significativamente más costoso que retener a uno existente. TelecomX puede implementar estrategias de retención dirigidas, como ofertas personalizadas o mejoras en el servicio, para reducir la pérdida de ingresos y mejorar la lealtad del cliente.

📊 Dataset

El dataset incluye columnas como:

1) customerID: Identificador unico de cada cliente
2) churn: Indica si el cliente ha dejado de contratar nuestros servicios (1) o no (0)
3) gender: Indica el genero del cliente (F) femenino o (M) masculino
4) SeniorCitizen: Indica si el cliente es mayor de 65 años (1) o no (0)
5) Partner: Indica si el cliente tiene un compañero (1) o no (0)
6) Dependents: Indica si el cliente tiene dependientes (1) o no (0)
7) tenure: Indica el tiempo que el cliente ha estado contratando nuestros servicios (en meses)
8) PhoneService: Indica si el cliente tiene un servicio de telefono (1) o no (0)
9) MultipleLines: Indica si el cliente tiene un servicio de lineas multiples (1) o no (0)
10) InternetService: Indica el tipo de servicio de internet que el cliente tiene (Fiber optic, DSL o No)
11) OnlineSecurity: Indica si el cliente tiene un servicio de seguridad en linea (1) o no (0)
12) OnlineBackup: Indica si el cliente tiene un servicio de respaldo en linea (1) o no (0)
13) DeviceProtection: Indica si el cliente tiene un servicio de protección de dispositivos (1) o no (0)
14) TechSupport: Indica si el cliente tiene un servicio de soporte tecnico (1) o no (0)
15) StreamingTV: Indica si el cliente tiene un servicio de streaming de TV (1) o no (0)
16) StreamingMovies: Indica si el cliente tiene un servicio de streaming de películas (1) o no (0)
17) Contract: Indica el tipo de contrato que el cliente tiene (Month-to-month, One year o Two year)
18) PaperlessBilling: Indica si el cliente tiene un servicio de facturacion sin papel (1) o no (0)
19) PaymentMethod: Indica el metodo de pago que el cliente tiene (Electronic check, Mailed check, Bank transfer (automatic) o Credit card (automatic))
20) MonthlyCharges: Indica el costo mensual de los servicios contratados por el cliente
21) TotalCharges: Indica el costo total de los servicios contratados por el cliente

🛠️ Tecnologías Utilizadas
Este proyecto fue desarrollado utilizando Python y las siguientes librerías principales:

Pandas: Para la manipulación y análisis de datos.
Matplotlib & Seaborn: Para la visualización de datos y el análisis exploratorio.


