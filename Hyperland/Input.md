En Wayland, el teclado NO se configura a nivel de sistema como en X11.
Hyprland gestiona directamente los layouts.

## Archivo correcto
~/.config/hypr/input.conf

## Configuración recomendada (ES + US)

```conf
input {
    kb_layout = es,us
    kb_options = grp:alt_shift_toggle
}
```

## Resultado

- Layout por defecto: Español
- Segundo layout: Inglés (US)
- Atajo: `Alt + Shift` 

## Comprobación

`hyprctl devices`

Buscar:
- `l "es,us"`
- `active keymap`

Relacionado:
- [[Locale - Keyboard]]
- [[Wayland]]

