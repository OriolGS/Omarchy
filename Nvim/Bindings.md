## Buscar palabra en la que estoy:
- *

## Ir de palabra seleccionada a la siguiente:
- Ctrl + n

## Cambiar palabra:
- c + i + w
  - C = cambiar línea
- Si se usa luego n para ir a la siguiente, y aprietas "." lo repite

## Buscar y reemplazar
1. Buscar y reemplazar todo = :%s/<palabra>/<nueva_palabra>/g
  - g implica global (cambiar en todos sitios)
2. Buscar y reemplazar pero preguntando cada vez = :%s/<palabra>/<nueva_palabra>/gc
  - c quiere decir preguntar una a una
  - se escoge si se hace en cada una con N y Y 

## Ver registros:
- :reg

## Copiar texto en registro de ordenador (copiar en otra app)
- "+y

## Eliminar letra en normal mode:
- x

## Escribir al inicio de la línea:
- I

## Escribir al final de la línea:
- A

## Añadir línea y empezar a escribir:
- o = línea abajo
- O = línea arriba

## Ir al inicio de la línea:
- _ = Inicio escrito
- 0 (zero) = caracter 0

## Ir al final de la línea:
- $

## Moverse a extremos del archivo:
- :<num> = ir a línea en específico
- G = ir al final
- gg = ir al inicio

## GOTO:
- Siguiente caracter en específico = f + <caracter> --> f = forward
- Anterior caracter en específico = F + <caracter> 

### Recurso para borrar, copiar...
- Eliminar hasta siguiente caracter en específico pero sin ese = dt + <caracter> 
- Eliminar hasta anterior caracter en específico pero sin ese = dT + <caracter> 

## Moverse en párrafos:
- { = anterior
- } = siguiente

## Centrar pantalla verticalmente para tener cursor en medio:
- zz
