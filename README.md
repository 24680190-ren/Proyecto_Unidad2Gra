# Proyecto_Unidad2Gra
# Documentación: Animación de tortuga basada en Walk Cycle (Frame x Frame)
## 1. Descripción

La animación de la tortuga se realizó utilizando el método mostrado en el video de referencia, el cual consiste en construir un walk cycle mediante la definición de poses clave colocadas en el timeline.

A diferencia de otros métodos, esta técnica no utiliza armature, sino que se basa en la manipulación directa del objeto en distintos frames.

## 2. Objetivo

Aplicar el método de animación frame por frame para generar un ciclo de caminata en una tortuga, utilizando 6 poses clave distribuidas en intervalos de tiempo definidos.

## Abrir Blender

Para iniciar con la animación, se abre el software Blender y se selecciona el modo de trabajo 2D. Posteriormente, se coloca la imagen de referencia que se utilizará como guía. Esto se realiza presionando Shift + A, seleccionando la opción de importar imagen y ubicándola en la escena, de manera que sirva como base sobre la cual se trabajará la animación.

<img width="300" height="200" alt="1" src="https://github.com/user-attachments/assets/ccd07523-5663-4c9a-9d3c-5685584d0c6f" />

## Definición de poses clave (Key Poses)

Primero se identifican las poses principales del movimiento (como en el walk cycle del video).

Para la tortuga se utilizaron:

1. Contacto inicial
2. Paso hacia adelante
3. Posición media (passing)
4. Paso contrario
5. Elevación (up)
6. Regreso a contacto

Estas poses representan todo el ciclo de caminata.

<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/dfd411e4-5ccf-4ba3-b6b5-fadb0df06de1" />

## Uso y configuración del Timeline en la animación

__¿Qué es el Timeline?__

El timeline en Blender es una herramienta que permite organizar la animación a lo largo del tiempo mediante frames (fotogramas). Cada frame representa un instante específico donde se puede definir una posición, rotación o cambio en el objeto.

En otras palabras, el timeline funciona como una línea de tiempo donde se construye el movimiento paso a paso.

__¿Para qué sirve en esta animación?__

En esta animación, el timeline se utiliza para:

Colocar cada una de las poses clave de la tortuga
Controlar el ritmo del movimiento
Definir cuándo ocurre cada cambio en la animación
Permitir que el movimiento siga una secuencia ordenada basada en el walk cycle

Gracias al timeline, se puede transformar una serie de imágenes estáticas en una animación continua.

__¿Cómo ayuda en el proceso?__

El uso del timeline facilita:

Organización: cada pose tiene un lugar exacto en el tiempo
Control: se puede ajustar la velocidad separando o acercando frames
Precisión: permite editar cada parte del movimiento sin afectar las demás
Repetición: ayuda a crear ciclos de animación (loop)

Esto es especialmente importante en animaciones frame por frame, donde cada detalle depende del control manual.

__¿Cómo se utiliza en esta animación?__
+ Se define la duración total del proyecto en el timeline
+ Se establecen los frames según los segundos deseados (en este caso, 18 fps)
+ Se colocan las 6 poses clave en frames específicos, separados por 72 frames (3 segundos)
+ En cada uno de esos frames:
+ Se ajusta la posición y rotación de la tortuga
+ Se insertan keyframes para guardar la pose
+ El timeline reproduce todas las poses en orden, generando la animación completa

## Creación de una pose de la tortuga mediante dibujo por líneas
 Modo dibujo en Blender

Para comenzar a dibujar una pose de la tortuga, primero es necesario cambiar al modo de dibujo (Draw Mode).

Esto se realiza seleccionando el objeto de tipo dibujo (Grease Pencil) o entrando al espacio de trabajo 2D, donde se permite trazar directamente sobre la pantalla.
Construcción de la pose con líneas

Para dibujar una pose de la tortuga, se sigue un proceso simple basado en formas básicas:

1. Estructura general
   
+ Se inicia dibujando una línea curva o forma ovalada que represente el caparazón
+ Esta será la base del cuerpo.

2. Cabeza
   
+ Se dibuja un círculo pequeño al frente del caparazón.
+ Se conecta con una línea corta (cuello).

3. Patas
   
+ Se agregan líneas simples que representen las patas.
+ La posición dependerá de la pose (adelante, atrás o levantadas).
+ No es necesario mucho detalle, solo indicar dirección y movimiento.

A continuación, se presentarán capturas de cada una de las poses realizadas, con el fin de visualizar el proceso de construcción del movimiento paso a paso.

**Pose 1:**

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/6bfc4ec1-27ad-41b0-aff1-fb27ff54d466" />

**Pose 2:**

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/507087fe-d3c6-4807-93ee-882c9614f8e8" />

**Pose 3:**

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/1bdcc318-8726-4fe7-84a3-1ea3b157e453" />


**Pose 4:**

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/38316c9b-0468-4720-9d3d-16a7178307a4" />

En esta parte se observa la misma imagen dos veces, ya que el movimiento del brinco se percibía un poco antinatural. Al agregar una segunda imagen intermedia, se logra un brinco más fluido y natural en la animación.

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/0622b041-2841-4769-a673-b794d07da8b3" />


**Pose 5:**

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/a8a08d54-da6f-45f6-b3b8-cb112a5109be" />

Se repite lo mismo quue en la anterior pose.

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/410cdf38-4cd8-4e19-9e6f-c52283166fd0" />

**Pose 6:**

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/df2e5776-7c7b-4819-8a4a-e0f1a4dd3182" />

Como final damos play. 

## Video de la animación 

https://github.com/user-attachments/assets/7ba52831-b4a8-4725-924e-4025f59a6d09






