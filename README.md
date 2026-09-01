# Simulación Interactiva Arduino

Serie de simulaciones interactivas para estudiantes de 3.º año. Cada ejemplo tiene un control
que el usuario mueve en vivo (un slider) y muestra en tiempo real todas las etapas de la ruta
del dato: desde la magnitud física de entrada hasta la salida física final, pasando por la
lectura del sensor, la conversión analógico-digital, el cálculo o `map()`, y la orden que
Arduino manda al actuador.

## Ejemplos disponibles

### Sol, LDR y LED
Un control deslizante de intensidad solar actualiza en vivo cada etapa de la ruta del dato
(voltaje analógico → lectura ADC → decisión/`map()` → orden `analogWrite()` → salida PWM →
brillo del LED), junto con un esquema del circuito Sol – LDR – Arduino UNO – resistencia – LED.

📄 `circuito-ldr-led.html`

### Ultrasonido y servomotor
Un control deslizante de distancia actualiza en vivo cada etapa de la ruta del dato (onda
ultrasónica → eco → tiempo medido con `pulseIn()` → distancia → ángulo con `map()` → orden
`write()` al servo → giro del eje), junto con un esquema del circuito HC-SR04 – Arduino UNO –
servomotor SG-90.

📄 `circuito-ultrasonido-servo.html`

## Ver la página

Una vez publicado con GitHub Pages, la página de inicio (con acceso a ambos ejemplos) queda
disponible en:

```
https://astriandradativani.github.io/SimulacionInteractivaArduino/
```

Repositorio:

```
https://github.com/astriandradativani/SimulacionInteractivaArduino
```

## Contenido

- `index.html` — página de inicio con las tarjetas de acceso a cada ejemplo.
- `circuito-ldr-led.html` — simulación Sol, LDR y LED (autocontenida, HTML + CSS + JS, sin
  dependencias de build).
- `circuito-ultrasonido-servo.html` — simulación Ultrasonido y servomotor (autocontenida,
  HTML + CSS + JS, sin dependencias de build).

## Autoría

Esp. Ing. Astri Edith Andrada Tivani

Este contenido está bajo licencia CC BY-NC-SA 4.0 — ver archivo LICENSE
