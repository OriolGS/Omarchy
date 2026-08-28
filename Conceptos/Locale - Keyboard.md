En Linux, el idioma del sistema y el teclado SON cosas distintas.
## Locale (idioma)
Afecta a:
- idioma del sistema
- mensajes
- formato de fechas
- moneda

Archivo:
- /etc/locale.conf

Ejemplo (dev-friendly):
```conf
LANG=en_US.UTF-8
LC_MESSAGES=es_ES.UTF-8
```
## Keyboard (layout)
Afecta a:
- qué carácter produce cada tecla

En [[Wayland]]:
- se gestiona desde el compositor (Hyprland)
- NO con setxkbmap

Relacionado:
[[Input]]
