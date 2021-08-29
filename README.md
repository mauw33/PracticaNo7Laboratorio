InformeLaboratorioNo7
==========================
# PRÁCTICA No. 7 INDUCTOR Y CAPACITOR
1. OBJETIVOS
* 1.1 OBJETIVO GENERAL

Implementar el conocimiento de superposición tanto teóricamente y prácticamente con el uso de herramientas que le permitan diseñar circuitos de una forma digital con lo cual se analizara tanto los resultados calculados como simulados 

* 1.2 OBJETIVOS ESPECIFICOS
  * Analizar circuitos mediante superposición
  * diseñar circuitos de tal manera que se facilita su resolución 
  * similar circuitos mediante una herramienta digital 
  * Comparar resultados simulados y calculados 

2. REQUISITOS PREVIOS

Se requiere el análisis analítico del circuito mostrado en la figura 4.1., aplicando el Teorema de Superposición. Obtenga los valores de VA e IX, respetando tanto la   polaridad del voltaje como el sentido de la corriente que se proporcionan y anote los resultados en la tabla 4.1. y 4.2. según corresponda.

3. INFORMACION GENERAL 

Los simuladores de circuitos electrónicos son muy útiles para explicar el comportamiento de éstos de una forma asequible a los alumnos de la rama de Eléctrica y Electrónica. El uso de la simulación por ordenador es una herramienta imprescindible hoy en día a la hora de explicar la electrónica en el aula, al ser la forma más sencilla y rápida de comprobar el funcionamiento de un circuito. Además, no necesita ningún tipo de material adicional para el montaje del mismo o medida de los resultados.

4. MATERIAL Y EQUIPO REQUERIDO

- Generador de señales
- Fuente DC.
- Osciloscopio.
- Protoboard
- Multímetro
- Cables conductores
- Resistencias, bobinas y capacitores.


5. PROCEDIMIENTO

### 7.1 Construya en el protoboard el circuito mostrado en la Figura 1.

 ![Screenshot]()

### a. Utilice el osciloscopio para observar el voltaje  variando la frecuencia entre los valores de 0, 10, 50, 100, 500, 1000 . Anote los valores pico de las ondas observadas.


### b. Utilice un multímetro para medir el voltaje  variando la frecuencia entre los valores de 0, 10, 50, 100, 500, 1000 . Anote los resultados.


### c. Utilice un multímetro para medir la corriente que atraviesa la resistencia variando la frecuencia entre los valores 0, 10, 50, 100, 500, 1000 . Anote los resultados.


### 7.2 Construya el circuito mostrado en la Figura 2

Realice las mismas mediciones de los ítems del numeral anterior y presente los resultados.

### a. Utilice el osciloscopio para observar el voltaje  variando la frecuencia entre los valores de 0, 10, 50, 100, 500, 1000 . Anote los valores pico de las ondas observadas.


### b. Utilice un multímetro para medir el voltaje  variando la frecuencia entre los valores de 0, 10, 50, 100, 500, 1000 . Anote los resultados.


### c. Utilice un multímetro para medir la corriente que atraviesa la resistencia variando la frecuencia entre los valores 0, 10, 50, 100, 500, 1000 . Anote los resultados.


### 7.3 Análisis de resultados

### Para cada uno de los circuitos anteriores, elabore una tabla con los resultados de las diferentes mediciones de voltaje realizadas con el osciloscopio y multímetro. Compare y comente los resultados obtenidos tomando en cuenta las distintas frecuencias utilizadas.


### 7.8 Preguntas

### ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?

Una bobina en corriente continua actúa diferente que un condensador, es decir deja pasar corriente (ya que las bobinas son realmente cables enrollados que soloconducen), sin embargo, no posee voltaje debido a que las bobinas en cc actúan como un corto circuito (se unen los polos positivo y negativo sin tener una carga)

El capacitor se comporta como un circuito abierto para corriente continua y la bobina como un cortocircuito. En un circuito complementado en corriente continua se puede entender un condensador como un interruptor abierto es decir no deja pasar corriente (por lo que no hay presencia de intensidad) sin embargo esta la presencia de voltaje debido a que en el condensador posee una reactancia.


### ¿Cómo se comportan la bobina y el capacitor en corriente alterna?

Bobinas en AC
 
Cuando las bobinas son sometidas a corriente con frecuencia (A.C.), cumplen su función de inductancia, es decir además de poseer corriente esta también tiene la presencia de voltaje, debido al efecto de frecuencia. Las bobinas se pueden utilizar para “Adelantar voltaje y retrasar corriente”, dependiendo de cómo se utiliza paramejorar el factor de potencia.

Condensadores en AC

En este caso, sucede todo lo contrario: el condensador deja pasar corriente, y tiene la presencia del voltaje, todo debido al efecto que tiene la corriente alterna en el elemento. Loscondensadores se utilizan para “Adelantar corriente y atrasar voltaje”, dependiendo para mejorar el factor de potencia.


### ¿Qué cree usted que ocurriría con el voltaje  y la corriente de la resistencia en los circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores distintos?

Al colocar dos capacitores o dos bobinas de diferente denominación en elcircuito, se facilita los cálculos al momento de encontrar el valor de Vo porque podemos reducir el circuito a su mínima expresión usando el concepto defasores, en los cuales a las impedancias y a las inductancias las convertimos aldominio fasorial y se representaría como una caja en el circuito a la cual podemos reducirle por el concepto de serie y paralelo.

### ¿Qué son los valores eficaces de voltaje y corriente?

Se llama valor eficaz de una corriente alterna, al valor que tendría una corriente continua que produjera la misma potencia que dicha corriente alterna, alaplicarla sobre una misma resistencia.En otras palabras, el valor RMS es el valor del voltaje o corriente en CA que produce el mismo efecto de disipación de calor que su equivalente de voltaje o corriente directa.


6. VIDEO



7. CONCLUSIONES

 - Se pudo comprobar que los valores obtenidos de los voltajes como de las corrientes fueron muy semejantes a los obtenidos mediante verificar el circuito analiticamente, con unos pequeños margenes de error.
Asi mismo tanto para las tablas obtenidas, se comprobó el uso del teorema de superposición, mediante las ecuaciones encontradas, los cálculos obtenidos nos asemejan a una silmulación real, todo este proceso de usar la ley antes mencionadas nos permiten a que los valores sean precisos y casi exactos, apoyandonos del mismo ciruito para usar las fórmulas como la dirección de los voltajes y corrientes.

8. BIBLIOGRAFIA

 Floyd Thomas L, “Principios de Circuitos Eléctricos”, 8 ed. 2007 .Pearson Educación de México, S.A. de C.V. México, pp. 281-333.
 
 Universidad de los Andes. (2015). Capacitancia e Inductancia [online]Available at: http://wwwprof.uniandes.edu.co/~ant sala/cursos/FDC/Contenidos/07_Inductancia_y_Capacitancia.pdf [Accessed 2Jul. 2017]

Sadiku, A. Fundamentos de Circuitos Eléctricos, 5ta edición. Capítulo 11, sección 11.4: "Valor eficaz o rms".
