# Aule App

<p>
  <a href="https://github.com/meet-aule/aule-hw"><img src="https://img.shields.io/badge/Hardware-aule--hw-1f6feb.svg" alt="Hardware de Aule"></a>
  <a href="https://github.com/meet-aule/aule-fw"><img src="https://img.shields.io/badge/Firmware-aule--fw-2da44e.svg" alt="Firmware de Aule"></a>
  <a href="https://github.com/meet-aule/aule-sw"><img src="https://img.shields.io/badge/Servidor-aule--sw-d97706.svg" alt="Servidor de Aule"></a>
  <a href="https://github.com/meet-aule/aule-app"><img src="https://img.shields.io/badge/App-Aule-8250df.svg" alt="App de Aule"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/Licencia-Apache%202.0-blue.svg" alt="Apache 2.0"></a>
</p>

([English](README.md) | Español)

**Aule es el tutor de IA de código abierto.** Este repositorio es la app para los adultos que rodean al niño: el padre o la madre que configura el aparato, y quien la familia invite a seguir su aprendizaje.

El aparato es para el niño. La app es para la familia. Nunca se convierte en una segunda pantalla para el niño.

## Qué hace

- **Configurar el aparato.** Conectar Aule al Wi-Fi por Bluetooth y vincularlo a la familia.
- **Seguir el avance.** Qué practicó el niño, qué ya domina y qué le toca, en lenguaje simple.
- **Entrar a una sesión.** Escuchar, o intervenir como tutor humano, en la misma sala de LiveKit que usa el aparato.
- **Controlar la privacidad.** Consentimiento, micrófono, ajustes de sesión y borrado de los datos del niño, en un solo lugar.

## Estado

Planificada. La app partirá de la que construimos y pusimos en producción para nuestro aparato anterior, que ya configura el Wi-Fi por Bluetooth. Hecha con Flutter para Android e iOS.

## Cómo encajan las piezas

```
aule-hw   el aparato: placa, tinta electrónica, audio, carcasa
aule-fw   firmware: xiaozhi-esp32 + transporte LiveKit (WebRTC)
aule-sw   servidor central: tutor de voz, aparatos, API para familias
aule-app  la app para familias                                  (este repositorio)
```

## Licencia

Apache License 2.0. Ver [LICENSE](LICENSE).

---

Hecho en Lima, Perú, por [Aule](https://meetaule.com) · admin@meetaule.com
