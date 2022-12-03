---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RE4uOIy?ver=8098&q=90&m=8&h=431&w=767&b=%23FFFFFFFF&l=f&x=438&y=1&s=716&d=403&aim=true
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS (experimental)
css: unocss
---

# Calidad del Aire

Presentado por alumnos del ITGAM

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
     <carbon:arrow-right class="inline"/>
  </span>
</div>



<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# Introduccion


- El presente proyecto se basa en una investigación referente a la contaminación del aire por la emisión de gases como el ozono y la combustión de combustibles fósiles. 
Para completar el proceso de la investigación, recabamos información en portales gubernamentales para conocer algunas afectaciones al ambiente con este problema y también la importancia de saber dónde existen las mayores emisiones de gases en las alcaldías de la CDMX. El tema de investigación cuenta con el suficiente acceso de información primaria tanto en internet, revistas, libros, etc. 
Con le ejecución de nuestra investigación no se causará ningún daño al ambiente, individuo o comunidad, más bien tiene la finalidad de conocer la calidad del aire y que sea descifrada por un sistema de visión por computadora para así llegar a una conclusión. 

<br>
<br>



<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# CONTAMINACION Y CALIDAD DEL AIRE EN LA CDMX
planteamiento del problema
|     |     |
| --- | --- |
- La contaminación es uno de los grandes problemas de la humanidad, ya que afecta de manera directa a todos nosotros. Ya que según la ONU (Organización de las Naciones Unidas) Las emisiones de gases de efecto invernadero deben reducirse entre un 40% y un 70% entre 2010 y 2050 para cumplir el Acuerdo de París y evitar los peores efectos del cambio climático. Contaminación del aire. Esta polución causa entre seis y siete millones de muertes prematuras al año. 
Los principales culpables de que la calidad del aire sea tan deplorable hoy en día somos nosotros y nuestro exceso del uso de vehículos o productos los cuales la ser usados provocan la emisión de gases como el ozono que es principalmente emitido por vehículos.

<!-- https://sli.dev/guide/animations.html#click-animations -->
---


# Objetivos
### Generales
- Medir los niveles de la calidad del aire que respiramos en las distintas zonas de la ciudad de México mediante un programa y un sensor de medición 
<br>

### Especificos
- Realizar un estudio del impacto del dióxido de carbono (CO2) y el ozono y las consecuencias en la calidad del aire.
- Desarrollar una inteligencia artificial (IA) que compare imágenes del ambiente del día a día durante una semana.
- Desarrollar un programa para obtener datos de los niveles de contaminación que se encuentran en el aire.
- Verificar que los resultados que arroja la inteligencia artificial (IA) y el sensor sean similares. 



---

# justificacion

- En la Ciudad de México, el Índice AIRE Y SALUD se reporta cada hora los 365 días del año, para cada una de las 29 estaciones automáticas de monitoreo de la calidad del aire.
Por lo que es importante tener en cuenta la calidad del aire antes de realizar:
- Ejercicio
-	Actividades que requieran algún esfuerzo vigoroso
- Antes del recreo en la escuela
- Para salir a jugar o caminar a la calle
- Si vas de compras o al parque




---
layout: image-right
image: https://www.padova24ore.it/wp-content/uploads/2020/03/6955-sanificazione-con-ozono.jpg
---

# ¿Que es el ozono?
marco teorico

El ozono es un gas que está presente naturalmente en nuestra atmósfera. Cada molécula de ozono contiene tres átomos de oxígeno y su fórmula química es O3. Las moléculas de oxígeno (O2) contenidas en el aire que respiramos constan de dos átomos de oxígeno solamente. 

Las moléculas de oxígeno reaccionan para formar moléculas de ozono y, al mismo tiempo, las moléculas de ozono reaccionan para formar moléculas de oxígeno. Si el número de moléculas de ozono que se crean es el mismo que el número de moléculas de ozono que se descomponen, la reacción está en equilibrio dinámico



---
class: px-20
---

# ¿QUE ES EL DIOXIDO DE CARBONO?
- El dióxido de carbono (también conocido como anhídrido carbónico) ‘habita’ la atmósfera en una proporción media de 380 partes por millón. Esa presencia es una de las estaciones del ‘ciclo planetario del carbono’. (Rafael Sardá, CSIC) 
Tal ciclo circula entre los cuatro espacios planetarios que incluyen los llamados reservorios activos: la atmósfera, la biosfera, la hidrosfera (fundamentalmente los océanos) y la litosfera (la capa superficial sólida de la Tierra), que juntos construyen la ‘casa’ del CO2. Pero una de las singularidades de este gas es que lo pequeño se vuelve grande. Su proporción en la atmósfera es la menor de estos cuatro reservorios, y sin embargo desempeña el papel más trascendente frente al resto.

<div grid="~ cols-2 gap-2" m="-t-2">

<img border="rounded" src="https://www.siberzone.es/blog-sistemas-ventilacion/wp-content/uploads/2020/09/co2-886x591.jpg">



</div>

---
---
# ARDUINO
- Arduino es una plataforma de desarrollo basada en una placa electrónica de hardware libre que incorpora un microcontrolador reprogramable y una serie de pines hembra. Estos permiten establecer conexiones entre el microcontrolador y los diferentes sensores y actuadores de una manera muy sencilla (principalmente con cables Dupont). 
Una placa electrónica es una PCB (“Printed Circuit Board”, “Placa de Circuito Impreso” en español). Las PCBs superficies planas fabricadas en un material no conductor, la cual costa de distintas capas de material conductor. Una PCB es la forma más compacta y estable de construir un circuito electrónico. 



<div grid="~ cols-2 gap-2" m="-t-2">

<img border="rounded" src="https://www.robomart.com/image/catalog/RM0058/02.jpg">



</div>
---
---

# PYTHON
- Python es un lenguaje de programación potente y fácil de aprender. Tiene estructuras de datos de alto nivel eficientes y un simple pero efectivo sistema de programación orientado a objetos. La elegante sintaxis de Python y su tipado dinámico, junto a su naturaleza interpretada lo convierten en un lenguaje ideal para scripting y desarrollo rápido de aplicaciones en muchas áreas, para la mayoría de plataformas.

<div grid="~ cols-2 gap-2" m="-t-2">

<img border="rounded" src="https://www.datocms-assets.com/14946/1590686329-python-analytics-cover.png?auto=format&corner-radius=16&fit=crop&h=312&mask=corners&q=45&w=568">



</div>

---
---

# Sensor Cjmcu-811 Ccs811 Dióxido Carbono
- El Sensor Dióxido Carbono CJMCU-811 monitorea la calidad del aire con un microcontrolador de 8 bits que está integrado para ejecutar el algoritmo de conversión analógico-digital de 12 bits para lecturas de sensores y conversiones digitalizadas con una interfaz esclava I2C que permite la conexión al sistema de control maestro. El CCS811 se basa en tecnología de microplacas que es eficaz para sensores de gas con tiempos de ciclo rápidos y una reducción significativa en el consumo de energía.
El Sensor Dióxido Carbono Cjmcu-811 está diseñado para monitorear la calidad del aire dentro de dispositivos personales como dispositivos móviles y relojes inteligentes, con bajo consumo de energía que se puede usar con batería

<div grid="~ cols-2 gap-2" m="-t-2">

<img border="rounded" src="https://d33wubrfki0l68.cloudfront.net/2c512f2f72913835a0e7b3b182c03dfa002b7967/9e2f8/uploads/2020/06/02/wire-ccs811only.jpg">



</div>

---
---
# Avances 
- utilizamos la placa PCB de arduino llamada Arduino UNO. conectamos el sensor de la forma correcta hacia la placa arduino, y en este caso conectamos una panytalla lcd para que nos muestre los datos obtenidos por el sensor hacia la acumulacion de CO2.
para ello debemos de importar la libreria que trabaja con el sensor desde el ide de arduino, como se muestra:
```ts {all|2|1-6|9|all}

#include "Adafruit_CCS811.h"
Adafruit_CCS811 ccs;
void setup() {
  Serial.begin(9600);
  Serial.println("CCS811 test");
  if(!ccs.begin()){
    Serial.println("Failed to start sensor! Please check your wiring.");
    while(1);
  }
  while(!ccs.available());
}

 
```

---
---
# continuacion del codigo
- el codigo basicamente es solo la medicion de las concentraciones de CO2 en el ambiente. 
como podemos ver el codigo manda a imprimir los resultados del sensor.
en caso de que el sensor este mal conectado mandara un mensaje para revisar el alambrado del sensor.
```ts {all|2|1-6|9|all}
void loop() {
  if(ccs.available()){
    if(!ccs.readData()){
      Serial.print("CO2: ");
      Serial.print(ccs.geteCO2());
      Serial.print("ppm, TVOC: ");
      Serial.println(ccs.getTVOC());
   }
    else{
      Serial.println("ERROR!");
      while(1);
    }
  }
  delay(500);
}
```



---
---
# Avances
- Despues de realizar deversas pruevas con el sesor, hicimos un programa que nos ayudara a medir los niveles de contaminacion de manera visual donde ocupamos una inteligencia artificial codificada desde el entorno de python con una de sus famosas librerias llamada OpenCV. para poder detectar los colores del ambiente con la camara de la pc o del movil.

<div grid="~ cols-2 gap-2" m="-t-2">

<img border="rounded" src="https://opencv.org/wp-content/uploads/2021/02/1_HfZmZayUqnYioPC9qTfd4A.png">



</div>


a continuacion compartiremos el codigo del programa realizado en python con OpenCV.

---
preload: false
---

# Codigo


```ts {all|2|1-6|9|all}
import cv2
import numpy as np
cap = cv2.VideoCapture(0)
redBajo1 = np.array([0, 10, 20], np.uint8)
redAlto1 = np.array([179, 30, 89], np.uint8)
redBajo2=np.array([0, 20, 20], np.uint8)
redAlto2=np.array([179, 30, 89], np.uint8)
while True:
  ret,frame = cap.read()
  if ret==True:
    frameHSV = cv2.cvtColor(frame, cv2.COLOR_BGR2HSV)
    maskRed1 = cv2.inRange(frameHSV, redBajo1, redAlto1)
    maskRed2 = cv2.inRange(frameHSV, redBajo2, redAlto2)
    maskRed = cv2.add(maskRed1, maskRed2)
    maskRedvis = cv2.bitwise_and(frame, frame, mask= maskRed)        
    cv2.imshow('frame', frame)
    cv2.imshow('maskRed', maskRed)
    cv2.imshow('maskRedvis', maskRedvis)
    if cv2.waitKey(1) & 0xFF == ord('s'):
      break
cap.release()
cv2.destroyAllWindows()

}
```

---



# Learn More
