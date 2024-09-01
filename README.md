# Conversión A/D y D/A
## 1. Señales Digitales vs. Señales Analógicas
Las señales digitales y analógicas se utilizan para representar información de formas diferentes. Las señales analógicas pueden variar de manera continua, mientras que las señales digitales están limitadas a valores discretos. Esta distinción afecta la precisión, flexibilidad, velocidad y costo de los sistemas de control.

>🔑 *Señal Digital:* Una señal digital es aquella que solo puede adoptar dos valores específicos, generalmente representados por 0 y 1, y su forma de onda es cuadrada.Son esenciales hoy en día, particularmente en sistemas de comunicación y procesamiento de información, gracias a su habilidad para ser almacenadas, transmitidas y manejadas con alta eficiencia y precisión.

>🔑 *Señal Analógica:* Una señal analógica es una señal continua que puede asumir cualquier valor dentro de un rango específico a lo largo del tiempo.Este tipo de señales transmite información en formas como voltaje, corriente o frecuencia, y lo hace de manera gradual, sin cambios bruscos

## 2.Transformada Z de adelantos y atrasos
permite transformar una serie temporal de valores discretos en una función que puede ser manipulada y analizada más fácilmente en el dominio de la frecuencia. La transformada Z facilita la resolución de ecuaciones diferenciales lineales y el análisis de sistemas en el dominio de la frecuencia, proporcionando una visión integral del comportamiento y la estabilidad de sistemas digitales y señales discretas.

# ecuaciones en diferencias
Las ecuaciones en diferencias pueden ser homogeneas,
lineales, invariantes en el tiempo
* 𝑦 𝑘 + 2 + 0,8𝑦 𝑘 + 1 + 0,07𝑦 𝑘 𝑢 𝑘 = 0
* 𝑦 𝑘 + 4 + 𝑠𝑒𝑛 0,4𝑘 𝑦 𝑘 + 1 + 0,3𝑦 𝑘 = 0
* 𝑦 𝑘 + 1 = −0,1 (𝑦( 𝑘))^2

### transformada z
Es la contraparte discreta de la transformada de LaPlace
Transformada Z

# Conclusiones
En esta clase, se ha discutido la importancia de los controladores digitales en los sistemas de control modernos, así como los procesos de conversión entre señales analógicas y digitales. Entender estas conversiones es esencial para diseñar y analizar sistemas de control digital que interactúen eficazmente con el entorno físico.
