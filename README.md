# Sensor Painter

PWA experimental que convierte movimiento y sensores del teléfono en pintura generativa.

## Incluye
- Accelerometer / DeviceMotion
- Gyroscope / rotation rate
- Orientation / inclinación
- Magnetometer cuando el navegador lo expone
- Brújula, GPS y Ambient Light Sensor cuando están disponibles
- Táctil como entrada adicional
- 6 pinceles, 6 efectos y exportación PNG
- Service Worker y modo instalable PWA
- Procesamiento local, sin enviar telemetría a servidores

## GitHub Pages
Settings → Pages → Deploy from a branch → main → /(root). Muchas APIs de sensores requieren HTTPS.

No existe una API web universal para acceder literalmente a todos los sensores físicos. La app usa las APIs que el navegador expone y fallbacks para compatibilidad, especialmente en iOS/Safari.