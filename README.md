# 2.-Juego-con-matriz-led

# Proyecto de PHYCOM: 

El proyecto consiste en un circuito electrónico cuyo objetivo es emular una versión de Tetris minimalista. Esto se logra trás realizar las respectivas simulaciones del código arduino. El entregable se describe como un dispositivo pequeño el cual podrá ser usado como una consola portátil.

## Contenido:
  - [Materiales](#Materiales) 
  - [Circuito Esquemático](#Circuito)
  - [Implementación en Protoboard](#Implementación) 
  - [Simulaciones del proyecto](#Simulaciones) 
  - [Video](#Video) 

## Materiales
1 Resistencia 10KΩ 0.25W
5 Pulsadores N.A. o Push-Buttons N.A.
1 Transistor NPN 2SC1815
2 Módulos con Matrices de LEDs 8×8 con Circuito Integrado MAX7219 c/u.
1 Buzzer Pasivo 5V
1 Placa Arduino Nano
Software: Arduino IDE y Proteus

## Circuito

![github-small](https://github.com/PhycomEspol/2.-Juego-con-matriz-led/blob/main/imagenes/Circuito.png)

## Implementación

_Se muestra el circuito implementado_
> ![github-small](https://github.com/PhycomEspol/2.-Juego-con-matriz-led/blob/main/imagenes/implementacion1.jpeg)

_Se pueden observar cada uno de los componentes electrónicos implementados junto a sus correspondientes conexiones._
> ![github-small](https://github.com/PhycomEspol/2.-Juego-con-matriz-led/blob/main/imagenes/implementacion2.jpeg)

## ¿Por qué hacemos esto? ¿Para quién? ¿A quienes beneficia?

![github-small](https://github.com/PhycomEspol/2.-Juego-con-matriz-led/blob/main/imagenes/beneficios.png)


### Video de la simulación y explicación

[![Alt text](https://img.youtube.com/vi/j09j6VTBq4k/0.jpg)](https://www.youtube.com/watch?v=j09j6VTBq4k)


### ¿Quieres replicarlo?

Sigue lo siguientes pasos:

1.  Tener instalado proteus y Arduino IDE.
2.  Dirigirte a la sección https://github.com/PhycomEspol/2.-Juego-con-matriz-led/tree/main/codigo
3.  Descargar la librería "Arduino.Lib".
4.  Ir a "C:\Program Files (x86)\Labcenter Electronics\Proteus 8 Professional\DATA\LIBRARY" y pegar el archivo descargado.
5.  Instalar las librerias de arduino, ya sea en "herramientas" añadir libreria de LedControl o descargandola del github y pegandola en la carpeta base de arduino y sus librerias, mi caso es "C:\Users\thami\OneDrive\Documentos\Arduino\libraries".
6.  Configurar en arduino IDE, "Preferencias" activar casilla de mostrar codigo mientras se compila.
7.  Compilar el archivo "tetris.ino" en arduino IDE.
8.  Leer el mensaje que aparece y buscar la ruta que termine en "hex", en mi caso es:  "C:\\Users\\thami\\AppData\\Local\\Temp\\arduino_build_91259/tetris.ino.hex", copiarlo.
9.  Abrir el archivo "omicron.pdsprj" en preoteus y abrir las preferencias del arduino nano y pegar la ruta copiada.
11. Correr la simulación de proteus.
12. Y listo! ya podrás jugar tetris.
