# AnimacionesRoku
#Author:Silva Sandoval Cecilia
Pequeños ejemplos para entender las animaciones en roku
La clase  Animation proporciona animaciones de nodos renderizables, aplicando funciones de interpolador
a los valores en campos de nodo renderizables especificados.
Necesita un campo de interpolacion para poder hacer el efecto,puede ser uno de los siguientes:
- FloatFieldInterpolator
- Vector2DFieldInterpolator
- ColorFieldInterpolator
Puedes mover una imagen gráfica por la pantalla a diferentes velocidades y trayectorias curvas en 
diferentes momentos de la animación especificando la función adecuada en easeFunction field.
Fields de Animation: duration,easeFunction,easeInPercent,easeOutPercent,optional

FLOATFIELDINTERPOLATOR
The FloatFieldInterpolator node class specifies a keyframe animation sequence to be applied to a 
floating point field of a node (such as, an opacity, width or height value.)

VECTOR2DFIELDINTERPOLATOR
Vector2DFieldInterpolator especifica una secuencia de animación de fotogramas clave que se aplicará 
a un par de campos Vector2D de un nodo. Por lo general, esto se usa para animar las coordenadas (x, y)
del campo translation.
All field interpolators include a set of key/keyValue pairs that define a keyframe of the animation. 

COLORFIELDINTERPOLATOR
The ColorFieldInterpolator node class specifies a keyframe animation sequence to be applied 
to the color field of a node (such as the color field of a Label node).
