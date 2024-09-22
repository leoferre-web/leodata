# leodata
Repositorio para data scientist

## ABSTRACT


### Breve Descripción Temática:
El análisis se centra en comprender cómo diversos factores afectan el estado de entrega de los pedidos de Amazon. Esto incluye la influencia de la ciudad de destino, el tipo de prenda comprada y el canal de ventas utilizado. El estudio busca identificar patrones y factores críticos que puedan ser utilizados para mejorar la logística y las estrategias de ventas, proporcionando información valiosa para la optimización operativa y la mejora de la experiencia del cliente.

### Alcance:

El análisis abarcará:
- Datos de Ventas: Información sobre transacciones específicas, incluyendo detalles del estado de entrega, ciudades, tipos de prendas, y canales de ventas.
- Región Geográfica: Datos de diferentes ciudades y posibles variaciones regionales.
- Temporalidad: Análisis en diferentes períodos si los datos están disponibles.

### Usuario Final:
Los usuarios finales de este análisis podrían ser:
- Amazon: Para optimizar procesos logísticos, mejorar la satisfacción del cliente y tomar decisiones basadas en datos.
- Consumidores de Amazon: A través de una experiencia de compra mejorada y un mejor servicio de entrega.
- Equipos de Marketing y Ventas: Para ajustar estrategias de marketing y canales de ventas según los patrones identificados.

### Resumen:
#### Este proyecto se centra en el análisis exhaustivo de los datos de ventas de Amazon, examinando diversas características como:
- Estado de entrega de las ventas
- Ciudades de destino
- Tipos de prendas
- Canal de ventas

 ###  Hipótesis de interés:
#### Basándonos en un análisis preliminar del dataset, planteamos las siguientes hipótesis:
- El estado de entrega está relacionado con la ciudad de destino y el canal de ventas.
- Las ciudades pueden influir en el tipo de prendas compradas y en el estado de entrega.
- El canal de ventas tiene un impacto significativo en el estado de entrega y en el tipo de prendas adquiridas.
  
  ### Objetivos:
- Probar las hipótesis planteadas mediante análisis estadísticos y visualizaciones.
-Identificar patrones y tendencias en los datos relacionados con el estado de entrega, ciudades, tipos de prendas, y canales de ventas.
-Desarrollar un modelo predictivo para estimar el estado de entrega basado en las características de las ventas.

### Impacto:
#### Los resultados de este estudio permitirán:
-Entender mejor los factores que influyen en el estado de entrega de los pedidos en Amazon.
-Desarrollar estrategias para mejorar la logística y la satisfacción del cliente.
-Informar decisiones estratégicas sobre el enfoque de ventas y marketing en diferentes ciudades y canales.

### Conclusiones:
Utilizando XGboost y Random Forest, veo que los modelos obtienen un 0.99 de acierto. Esto sugiere que son buenos métodos, sin embargo, pueden ser valores sobreajsutados. Es decir, el modelo ha mostrado un desempeño excepcional con un 99% de precisión en los datos de entrenamiento. Sin embargo, este alto nivel de acierto me sugiere un posible sobreajuste, donde el modelo ha aprendido no solo los patrones generales, sino también el ruido presente en los datos. Para lo cual, se podría seguir realizando otras técnicas sobre el modelo
