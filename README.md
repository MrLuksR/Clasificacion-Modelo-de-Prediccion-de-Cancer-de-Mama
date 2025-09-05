# Clasificación de Tumores y Predicción de Cáncer de Mama
Para la predicción de los resultados para el diagnóstico, se tomaron en cuenta tres
variables independientes principales: perimeter_mean - promedio del perímetro de las células,
radius_mean - promedio del radio de las células y area_mean - promedio del área de las células.
Estas variables fueron seleccionadas a partir de un mapa de calor que determinó la relación entre
las mismas y el diagnóstico final, en donde este tiene como finalidad determinar si el tumor es
maligno o benigno.

## Pruebas a partir de variables seleccionadas
Las tres variables seleccionadas estan relacionadas al tamaño del tumor (perímetro, radio, y área).
La característica principal se refiere a que: mayor tamaño, más posibilidad de que el tumor sea
maligno y la variable más significativa es el área. Los datos ingresados fueron los siguientes.

Perímetro | Radio | Área | Diagnóstico
80.90 | 10.99 | 120 | Benigno
80.90 | 10.99 | 130 | Maligno

Dentro del caso anterior se puede observar que el área del tumor cambió solo 10 centímetros y esto
fué suficiente para determinar que el mismo es maligno.

## Más ejemplos sobre topes de tumores benignos
Perímetro | Radio | Área | Diagnóstico
50.90 | 20.78 | 90.00 | Benigno
50.43 | 30.78 | 50.30 | Benigno
45.33 | 32.78 | 30.50 | Benigno
