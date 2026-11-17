# Capricorn App

<p>
  <a href="https://github.com/aule-org/capricorn-hw"><img src="https://img.shields.io/badge/Hardware-capricorn--hw-1f6feb.svg" alt="Hardware de Capricorn"></a>
  <a href="https://github.com/aule-org/capricorn-sw"><img src="https://img.shields.io/badge/Software-capricorn--sw-2da44e.svg" alt="Software de Capricorn"></a>
  <a href="https://github.com/aule-org/capricorn-app"><img src="https://img.shields.io/badge/App-Capricorn-8250df.svg" alt="App de Capricorn"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/Licencia-Apache%202.0-blue.svg" alt="Apache 2.0"></a>
</p>

([English](README.md) | Español)

**Capricorn es el tutor de IA de código abierto.** Este repositorio es la app para los adultos que rodean al niño: el padre o la madre que configura el aparato, y quien la familia invite a seguir su aprendizaje.

El aparato es para el niño. La app es para la familia. Nunca se convierte en una segunda pantalla para el niño.

## Qué hace

- **Configurar el aparato.** Conectar Capricorn al Wi-Fi por Bluetooth y vincularlo a la familia.
- **Seguir el avance.** Qué practicó el niño, qué ya domina y qué le toca, en lenguaje simple.
- **Entrar a una sesión.** Escuchar, o intervenir como tutor humano, en la misma sala de LiveKit que usa el aparato.
- **Controlar la privacidad.** Consentimiento, micrófono, ajustes de sesión y borrado de los datos del niño, en un solo lugar.

## Estado

Planificada. La app partirá de la que construimos y pusimos en producción para nuestro aparato anterior, que ya configura el Wi-Fi por Bluetooth. Hecha con Flutter para Android e iOS.

## Cómo encajan las piezas

```
capricorn-hw   el aparato: placa, tinta electrónica, audio, carcasa
capricorn-sw   firmware: xiaozhi-esp32 + transporte LiveKit (WebRTC)
capricorn-app  la app para familias                                  (este repositorio)
```

## Licencia

Apache License 2.0. Ver [LICENSE](LICENSE).

---

Hecho en Lima, Perú, por [Aule](https://meetaule.com) · admin@meetaule.com
