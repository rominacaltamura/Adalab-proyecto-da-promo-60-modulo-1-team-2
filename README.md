
¡Hola! 

Bienvenido/a al repositorio de JUEGOS CLÁSICOS del grupo 2, Promo 60. 

Aquí encontrarás el código generado para poder disfrutar de tres juegos clásicos:
- El ahorcado
- Piedra, papel, tijera
- Preguntas y respuestas

## ¿Qué hay en las carpetas?
En el repositorio encontrarás varias carpetas.

Por una parte, se encuentran las versiones finales del código de cada juego, en la carpeta "proyecto_juegos_definitivos". 

Por otra parte, se encuentran las carpetas de trabajo correspondientes al desarrollo de cada juego.
¡No las toques! Son carpetas internas de desarrollo de producto.
El equipo las usará si así es necesario para revisar versiones anteriores del código.

## ¿Cómo son los archivos de cada juego?

Como ya sabes, los juegos se encuentran en la carpeta en la carpeta "proyecto_juegos_definitivos".
Dentro, encontrarás tres archivos: uno correspondiente a cada juego. Su nombre así lo indica. 

## Información y consideraciones sobre el código de los juegos:

### Cada juego consta de:

- Una introducción y saludo al usario/a (sale por consola para el usuario/a).
- Instrucciones del juego (sale por consola para el usuario/a).
- Contadores de puntos (sale por consola para el usuario/a).
- El código del juego en sí: 
    - Se han añadido emojis y figuras visuales para mejorar la experiencia del usuario/a. 👇🏽
``` python

    elif vidas_restantes == 0: 
        print(r"""
  ____
 |/  O
 |  /|\\
 |   |
 |  / \\  
_|_
        """)    

```
 

### Ten encuenta que:
- Los juegos se juegan contra el ordenador.
- Debes importar las librerías que se indican en el código para el correcto funcionamiento de los juegos. 
```python
import random
```
- Los emojis se encuentran asignados mediante códigos. No los borres si quieres usarlos. 

```python
calavera = '\U0001F480'
confeti = '\U0001F389'
shhh = '\U0001F92B'     
guiño = '\U0001F609'
pulgar_down ="\U0001F44E"
lengua_guiño = '\U0001F61C'
biceps = '\U0001F4AA'
```
- En el ahorcado se imprime la respuesta como control de funcionamiento del juego. Borra ese print antes de pasárselo al usuario/a.

```python
print(f'PALABRA SECRETA (borrar print luego): {palabra_secreta}')
```

¡Disfruta de los juegos!




