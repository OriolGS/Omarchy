Omarchy NO configura Hyprland directamente en `hyprland.conf`.

Este archivo actúa como **orquestador**, cargando:
- defaults del sistema
- tema activo
- overrides personales

## Archivo principal
~/.config/hypr/hyprland.conf

## Regla de oro
❌ NO editar archivos en:
- ~/.local/share/omarchy/default/hypr/
- ~/.config/omarchy/current/theme/

✅ SIEMPRE usar overrides personales en:
- ~/.config/hypr/input.conf
- ~/.config/hypr/bindings.conf
- ~/.config/hypr/looknfeel.conf
- ~/.config/hypr/autostart.conf

## Flujo de carga
1. Defaults de Omarchy
2. Tema activo
3. Configuración personal (override)

Esto garantiza:
- actualizaciones seguras
- configuración estable
- control total sin romper el sistema

Relacionado:
- [[Input]]
- [[Bindings]]
