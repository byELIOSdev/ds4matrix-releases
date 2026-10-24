# ZEUS — PS4 / DualShock skin for GamepadViewer

Dark storm theme, gold trim, lightning flash on every button press.
100% CSS shapes — no external image assets, no broken links.

## Ver el diseño

👉 **[Demo en vivo](https://byeliosdev.github.io/ds4matrix-releases/zeus-gamepad-skin/)**
(clickeá cualquier botón del mando para probar el efecto, o tocá "Correr demo")

## Usar en OBS / GamepadViewer

1. Hosteá `zeus-ps4-skin.css` en algún lugar con link **raw** (ya lo tenés acá mismo en este repo):
   ```
   https://raw.githubusercontent.com/byELIOSdev/ds4matrix-releases/main/zeus-gamepad-skin/zeus-ps4-skin.css
   ```
2. Agregalo a tu URL de overlay clásica:
   ```
   https://TU-OVERLAY-URL?p=1&css=https://raw.githubusercontent.com/byELIOSdev/ds4matrix-releases/main/zeus-gamepad-skin/zeus-ps4-skin.css
   ```
3. En OBS → Browser Source → ancho **800** / alto **620**.

Si tu overlay usa el motor nuevo de GamepadViewer (GPV2) y los nombres de clase
no matchean 1:1 con `.custom .controller / .sticks / .arrows / .abxy / .trigger / .touchpad`,
inspeccioná el DOM del overlay (F12) y ajustá los selectores de `zeus-ps4-skin.css` acorde.
