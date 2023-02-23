# Laboratorio-8
INTEGRANTES : Boza Paul

NRC:10069

FECHA: 17 de Enero de 2023

Objetivo General.-

El análisis y desarrollo de circuitos aplicando el período y la frecuencia de las ondas sinusoidales para descomponer sus propiedades permite calcular mejor y de forma más sencilla variables desconocidas utilizando información teórica.

Objetivo Especifico.-

Describir y descubrir las características de los periodos y frecuencias y su comportamiento en los circuitos correspondientes, para ello utilizando la información teórica proporcionada mediante el uso de sitios web y videotutoriales.El análisis y cálculo de diferentes ejemplos de circuitos aplicables a los periodos y frecuencias de las ondas senoidales previamente aprendidos en el curso, se verificará mediante un simulador virtual con un ejercicio de laboratorio.

Marco Teorico.-

La onda sinusoidal es una señal analogicaseñal analógica simple, una sola señal un tono purotono puro una única frecuencia, es periódica e infinita, no tiene principio ni tiene fin, toma el nombre según donde se dibuje la onda, puede ser senoidales que comienza en cero o coseidales que comienza a dibujar la señal en el valor máximo, igualmente puede ser proyectada desde cualquier punto y seguiría siendo sinusoidal. La porción mínima de una onda sinusoidal se denomina ciclo y el periodo es el resultado de el tiempo que tarda el ciclo en ser repetido. Las ondas sinusoidales se utilizan para representar funciones de onda sonora y las ondas de corriente alterna.

![image](https://user-images.githubusercontent.com/116833964/219712971-90c90174-95c3-4f6e-b343-ef29a0cd9c77.png)

La matemática de las ondas senoidales o sinusoidales, como también se las conoce, es la de las funciones seno y coseno.
Se trata de funciones repetitivas, lo que significa periodicidad. Ambas tienen idéntica forma, con la salvedad de que el coseno está desplazado hacia la izquierda respecto al seno en un cuarto de ciclo. Se observa en la figura 2:

![image](https://user-images.githubusercontent.com/116833964/219713206-8b39d0e2-3898-475f-b5d3-6c8202adb1d1.png)

 -Partes:

Período, amplitud, frecuencia, ciclo y fase son conceptos se aplican a las ondas periódicas o repetitivas y son importantes para caracterizarlas adecuadamente

 -Período:

Una función periódica como las mencionadas, la cual se repite a intervalos regulares, cumple siempre la siguiente propiedad:

f (t) = f (t+ T) = f (t + 2T) = f (t + 3T) = ….

Donde T es una cantidad denominada período de la onda, y es el tiempo que tarda en repetirse una fase de la misma. En unidades de Sistema Internacional, el período se mide en segundos.

  -Amplitud:
  
De acuerdo a la expresión general de la onda senoidal v (t) = vm sen (ωt+φ), vm es el valor máximo de la función, que ocurre cuando sen (ωt+φ)= 1 (recordando que el mayor valor que admite tanto la función seno como la función coseno es 1). Este valor máximo es justamente la amplitud de la onda, también conocida como amplitud pico.

En caso de tratarse de un voltaje se medirá en Voltios y si es una corriente será en Amperios. En la onda senoidal mostrada la amplitud es constante, pero en otros tipos de onda la amplitud puede variar.

  -Ciclo:
  
Es una parte de la onda contenida en un período. En la figura anterior se tomó el período midiéndolo desde dos cimas o crestas consecutivas, pero puede comenzar a medirse desde otros puntos de la onda, mientras estén limitados por un período.

Obsérvese en la siguiente figura como un ciclo abarca desde un punto hasta otro con el mismo valor (altura) y la misma pendiente (inclinación).

![image](https://user-images.githubusercontent.com/116833964/219713687-9975ced0-afbf-41d8-808d-5d5d878d679a.png)

  -Frecuencia:
  
Es la cantidad de ciclos que ocurren en 1 segundo y se encuentra vinculada al argumento de la función seno: ωt. La frecuencia se denota como f y se mide en ciclos por segundo o Hertz (Hz) en Sistema Internacional.

La frecuencia es la cantidad inversa del período, por lo tanto:

 f = 1/T

Mientras que la frecuencia f está relacionada con la frecuencia angular ω (pulsación) como:

 ω = 2πf

La frecuencia angular se expresa en radianes /segundo en el Sistema Internacional, pero los radianes son adimensionales, así la frecuencia f y la frecuencia angular ω tienen las mismas dimensiones. Obsérvese que el producto ωt da radianes como resultado, debiendo tenerse en cuenta a la hora de utilizar la calculadora para obtener el valor de sen ωt.

   -Fase:
   
Se corresponde al desplazamiento horizontal experimentado por la onda, respecto a un tiempo tomado como referencia.

En la siguiente figura la onda verde está adelantada respecto a la roja en un tiempo td. Dos ondas sinusoidales están en fase cuando su frecuencia y su fase son las mismas. Si la fase difiere, entonces están en desfase. Las ondas de la figura 2 también están desfasadas.

![image](https://user-images.githubusercontent.com/116833964/219713874-557f0edd-3a70-446a-be2d-1d03c25888cb.png)

Si la frecuencia de las ondas es diferente, estarán en fase cuando la fase ωt+φ sea la misma en ambas ondas en determinados instantes.

Procedimiento.-

7.5.1. Implemente el circuito que se presenta en la figura 7.1

![image](https://user-images.githubusercontent.com/116833964/219711035-140f5e31-5403-4473-8855-7a6ac0641204.png)

      8.5.2.. Ajuste el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 Khz.
      
![image](https://user-images.githubusercontent.com/116833964/219714943-962f15c8-d8c4-4461-af2d-91cc5c3ad321.png)

      8.5.3. Conecte el osciloscopio al resistor de carga RL. Observe la señal que aparece en el osciloscopio.
      
![image](https://user-images.githubusercontent.com/116833964/220913682-3bbd8455-78a7-4658-b70c-579f6fc7629d.png)
 
      8.5.4. Responda las siguientes preguntas:
   
NOTA: Todas las preguntas son relacionadas, por lo que debe considerar las respuestas
precedentes cada vez que conteste las preguntas. Para las lecturas de los valores debe
considerar las graficas que presenta el osciloscopio.

¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?
___________

¿En qué valor está posicionada la perilla VOLTS/DIV? _Se encuentra en 10 mi VOLTS/DIV 

¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?
__

¿En qué valor está posicionada la perilla TIME/DIV? _ En el valor de 0.1m

      8.5.5.¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?

Amplitud de voltaje: ____________(V)

Periodo: ____________(s)

     8.5.6. Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.
     
f: _____________(Hz)

ω: ____________(rad/s)

     8.5.7. Con el multímetro digital mida el voltaje de salida en RL: _______________
     
     8.5.8. Compare el voltaje medido en el punto 8.5.5. y el obtenido en el punto 8.5.7.
     
     ¿Coinciden? _______ ¿Por qué?
_______________________________________________
