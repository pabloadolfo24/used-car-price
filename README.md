# used-car-price

PREDICCIÓN DE PRECIO DE AUTOMÓVILES USADOS

Identificación del problema
Actualmente, el mercado de automóviles es un negocio próspero y de elevado crecimiento debido al volumen de transacciones cada vez mayor. En este sentido, como en toda venta de productos de segunda mano, es necesario realizar una tasación del vehículo antes de poder realizar una comprar o venta. Sin embargo, ésta no es directa y es basada tradicionalmente en la evaluación de activos que se ve afectado en gran medida por subjetividad y carece de adecuada precisión. Por tanto, se genera un problema para los individuos ajenos a este mercado a la hora de saber cuánto vale un automóvil, ya sea para saber a qué precio venderlo o comprarlo. Dada esta problemática, en este proyecto se analizó un sistema computacional automático de tasación de vehículos de segunda mano que tiene como objetivo entregar el valor de mercado actual del auto, haciendo uso de conjunto de datos reales (19237 datos para el conjunto de datos de entrenamiento y 8245 para el conjunto de datos de prueba).

Objetivo
- Desarrollar un sistema de predicción de precios de automóviles usados basado en las características de éstos (modelo, año de fabricación, kilometraje, tipo de combustible, tipo de caja de cambios, etc.), que permita al usuario realizar tasaciones de autos para fines comerciales.

Dataset
El dataset es descargable del siguiente link: https://neuraldojo.org/media/carprice/archive.zip

Columnas
Target variable:
- Price: Precio.
Integer variables:
- ID: Identificación.
- Prod. year: Año de fabricación.
- Airbags: Bolsas de aire.
Continuous variables:
- Cylinders: Cilindros.
Categorical variables:
- Levy: Exacción.
- Manufacturer: Fabricante.
- Model: Modelo.
- Category: Categoría de automóvil.
- Leather interior: Interior de cuero.
- Fuel type: Tipo de combustible.
- Engine volume: Volumen del motor.
- Mileage: Kilometraje.
- Gear box type: Tipo de caja de cambios.
- Drive wheels: Ruedas motrices.
- Doors: Número de puertas.
- Wheel: Rueda.
- Color: Color.
