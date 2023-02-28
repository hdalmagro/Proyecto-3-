# Proyecto-3

# 1. Objetivo
1.1 OBJETIVO GENERAL

El objetivo de la práctica de medir la temperatura utilizando el sensor LM35 y un Op-Amp es aprender a utilizar un sensor de temperatura y amplificar su señal para poder medir la temperatura con mayor precisión y exactitud.

1.2 OBJETIVOS ESPECIFICOS

• Conectar el sensor LM35 al circuito y verificar su correcto funcionamiento. 
• Configurar el amplificador operacional (Op-Amp) para amplificar la señal de salida del sensor. • Calibrar el circuito para obtener una lectura precisa de la temperatura. 
• Realizar mediciones de temperatura y verificar la precisión del circuito. 
• Analizar los resultados obtenidos y hacer las correspondientes conclusiones y recomendaciones.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 2. Marco Teorico

El sensor de temperatura LM35 es un dispositivo electrónico que se utiliza para medir la temperatura con una alta precisión. Este sensor está diseñado para producir una señal de voltaje proporcional a la temperatura en grados Celsius.

El LM35 es un dispositivo de estado sólido que utiliza la tecnología de circuitos integrados para producir una señal de voltaje precisa y lineal. Este sensor está diseñado para trabajar en un rango de temperatura de -55 °C a 150 °C, y tiene una precisión de ±0.5 °C a una temperatura ambiente de 25 °C.

El LM35 tiene una salida de voltaje lineal que varía en 10 mV por grado Celsius, lo que significa que su señal de salida aumentará en 10 mV por cada grado Celsius que aumente la temperatura. Por ejemplo, si la temperatura es de 25 °C, la salida del sensor será de 250 mV.

El sensor LM35 tiene tres pines: VCC, GND y OUT. El pin VCC se utiliza para suministrar energía al sensor, mientras que el pin GND se utiliza como tierra. La salida del sensor se encuentra en el pin OUT.

El LM35 es un sensor muy preciso y fácil de usar, ya que no requiere calibración y proporciona una salida de voltaje lineal que es fácil de interpretar. Además, el LM35 es resistente al ruido y a las interferencias electromagnéticas, lo que lo hace ideal para su uso en ambientes industriales.

En resumen, el sensor de temperatura LM35 es un dispositivo electrónico muy útil para medir la temperatura con alta precisión. Su diseño de estado sólido y su salida de voltaje lineal lo hacen fácil de usar y muy confiable en una amplia variedad de aplicaciones.

![image](https://user-images.githubusercontent.com/116819100/221759340-728fd7f5-dfce-4186-bb8b-34925318ab0c.png)

El amplificador operacional (Op-Amp) 358 es un dispositivo electrónico que se utiliza para amplificar señales eléctricas. Es un amplificador de propósito general de alta ganancia y bajo ruido, que puede ser utilizado en una variedad de aplicaciones, desde circuitos de audio hasta circuitos de medición.

El amplificador operacional 358 tiene dos entradas (positiva y negativa) y una salida. La entrada negativa se utiliza para comparar la señal de entrada con la señal de referencia, mientras que la entrada positiva se utiliza para aplicar la señal de entrada.

El amplificador operacional 358 tiene una ganancia muy alta, lo que significa que puede amplificar una señal de entrada varias veces. Además, tiene una impedancia de entrada muy alta, lo que significa que no afecta la señal de entrada en gran medida.

El 358 también tiene una impedancia de salida muy baja, lo que significa que puede entregar una gran cantidad de corriente sin afectar la señal de salida. Esto lo hace ideal para su uso en aplicaciones donde se requiere una carga pesada.

El amplificador operacional 358 también tiene una amplia banda de frecuencia, lo que significa que puede amplificar señales de alta frecuencia sin perder su forma de onda. Además, tiene una distorsión armónica muy baja, lo que significa que puede amplificar señales sin introducir ruido o distorsión.

En resumen, el amplificador operacional 358 es un dispositivo electrónico muy útil para amplificar señales eléctricas. Su alta ganancia, baja impedancia de entrada y salida, amplia banda de frecuencia y baja distorsión armónica lo hacen ideal para su uso en una amplia variedad de aplicaciones, desde circuitos de audio hasta circuitos de medición.

![image](https://user-images.githubusercontent.com/116819100/221760210-62cbd42f-3471-48be-93dc-ccdcbbe77c05.png)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 3. Explicacion del Procedimiento

Componentes a usar

    1. Fuente de Voltaje de 5V
    2. Amplificador operacional LM358
    3. Sensor de temperatura LM35
    4. Diodos leds (verde y rojo)
    5. Resistencias de 470- Ohms
    6. Preset 10KOhms
    7. Protoboard

![image](https://user-images.githubusercontent.com/116781677/221834784-40aad1d9-7d5d-40ba-8e1e-dc2ea263962b.png)

Diagrama del circuito por armar.

![image](https://user-images.githubusercontent.com/116781677/221832655-da0ffd72-91e2-4c24-b16a-eaae8dfdce40.png)

Circuito armado en fisico.

![WhatsApp Image 2023-02-28 at 06 13 13](https://user-images.githubusercontent.com/116781677/221837793-5fe6ee16-dc7f-4fa1-8f3c-9580a7899132.jpg)

CIRCUITO EN FUNCIONAMIENTO

Con temperatura ambiente

![WhatsApp Image 2023-02-28 at 06 13 14](https://user-images.githubusercontent.com/116781677/221837941-e2b087d1-167b-494a-9e65-6d7f4d672a7e.jpg)

Con la subida de temperatura

![WhatsApp Image 2023-02-28 at 06 13 14](https://user-images.githubusercontent.com/116781677/221838061-1364d954-de2d-4045-aede-30f6901305c9.jpg)

4. Video

5. Conclusiones

-El amplificador operacional LM358 se utiliza para amplificar la señal del sensor de temperatura, lo que permite que la medición sea más precisa.

-El circuito es relativamente simple y se puede construir con componentes comunes de electrónica, lo que lo hace fácil de implementar.

-La medición de temperatura puede ser útil en una variedad de aplicaciones, como monitoreo de temperatura ambiente, control de temperatura de dispositivos electrónicos, etc.

-Los LED que cambian de color proporcionan una forma visual y fácil de interpretar la medición de temperatura. Por ejemplo, un LED rojo podría indicar una temperatura alta, mientras que un LED verde podría indicar una temperatura baja.

6. Referencias

