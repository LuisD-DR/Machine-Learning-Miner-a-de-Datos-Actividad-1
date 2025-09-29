# Machine-Learning-Miner-a-de-Datos-Actividad-1
Actividad 1 de Machine Learning Corte 2 | Minería de Datos

Descripción General
Este dataset sintético contiene información de 500 estudiantes universitarios y su probabilidad de deserción académica.
Se construyó con fines educativos para simulación de datos, análisis exploratorio y pruebas de modelos de Machine Learning.
El dataset incluye variables demográficas, académicas, financieras y una variable de salida binaria: Deserta (0 = No, 1 = Sí).

Variables
Demográficas
Edad: Tipo entero. Valores típicos entre 16 y 29 años, con algunos valores atípicos (10, 45, 60).
Genero: Variable categórica con valores {Masculino, Femenino}.
Origen: Variable categórica con valores {Urbano, Rural, Extranjero}.

Académicas
Promedio_Secundaria: Tipo float. Rango de 0.0 a 5.0. Representa el promedio de notas de la secundaria (escala 0–5). Tiene aproximadamente un 5% de valores nulos.
Puntaje_Admision: Tipo float. Rango de 0 a 100. Nota del examen de admisión a la universidad. Tiene aproximadamente un 5% de valores nulos.
Nota_Primer_Semestre: Tipo float. Rango de 0.0 a 5.0. Promedio de notas del primer semestre. Tiene aproximadamente un 5% de valores nulos.

Financieras
Nivel_Socioeconomico: Variable categórica con valores {Bajo, Medio, Alto}.
Beca: Variable binaria con valores {0 = No, 1 = Sí}. Tiene aproximadamente un 5% de valores nulos.
Credito: Variable binaria con valores {0 = No, 1 = Sí}. Indica si el estudiante tiene crédito educativo.
Ayuda_Financiera: Variable binaria con valores {0 = No, 1 = Sí}. Indica si el estudiante recibe algún tipo de ayuda financiera adicional.

Variable de salida
Deserta: Variable binaria con valores {0 = No, 1 = Sí}. Es la variable objetivo que indica si el estudiante desertó o no.
Esta variable fue calculada con una función logística basada en el promedio de secundaria, la nota del primer semestre, el nivel socioeconómico y si el estudiante tenía o no beca.

Valores Nulos y Outliers
Valores Nulos
Se introdujeron valores faltantes de forma intencional para simular escenarios reales de bases de datos:
Afectaron las variables Promedio_Secundaria, Puntaje_Admision, Nota_Primer_Semestre y Beca.
Aproximadamente el 5% de los registros en cada una de estas columnas se reemplazaron con valores nulos (NaN).
Esto representa situaciones como notas no registradas, falta de datos en sistemas académicos o información financiera incompleta.

Outliers
Se agregaron valores atípicos en la variable Edad para hacer más realista el dataset:
A un 2% de los registros se les asignaron valores poco comunes: 10, 45 o 60 años.
Esto representa casos extremos como estudiantes muy jóvenes (niños prodigio) o adultos mayores que deciden ingresar a la universidad.
