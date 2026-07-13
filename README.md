<div align="center">
  <h1>⚙️ Zaraz Maker</h1>
  <p><strong>El Motor "Point & Click" Definitivo para Juegos de Gran Estrategia</strong></p>
</div>

<br>

> ⚠️ **Nota Importante:** Este repositorio sirve como **Landing Page / Showcase** (Portafolio) del ecosistema Zaraz. El código fuente de `Zaraz Engine` (el motor de simulación subyacente) se mantiene bajo licencia propietaria y de código cerrado. 

---

## 🌍 ¿Qué es Zaraz Maker?

**Zaraz Maker** es un entorno de desarrollo visual (IDE) de última generación diseñado para democratizar la creación de videojuegos del género *Grand Strategy* (Gran Estrategia) y simulación económica. 

Inspirado en el flujo de trabajo accesible de motores como RPG Maker o Godot, pero especializado matemáticamente en la geopolítica masiva, Zaraz Maker permite a los diseñadores y creadores indie construir simuladores hiper-detallados **sin escribir una sola línea de código**. A través de una interfaz *Point & Click*, el motor compila los datos visuales directamente hacia un backend de procesamiento masivo escrito en Rust.

### ✨ Características Principales de Zaraz Maker

* 🖱️ **Interfaz Visual Híbrida (Tauri):** La interfaz de edición (el IDE) está construida sobre tecnologías Web (HTML/CSS/JS) acopladas a un core de escritorio nativo mediante Tauri. Esto brinda un renderizado de UI "Premium" (Data Visualization interactiva) a 60 FPS sin saturar la GPU.
* 🗺️ **Pintor Cartográfico Vectorial:** Carga archivos crudos GeoJSON y pinta polígonos con un pincel para agrupar dinámicamente bloques territoriales, definiendo Provincias, Regiones y Países enteros de manera visual y directa.
* 📜 **Visual Scripting Integrado:** Diseña árboles tecnológicos, misiones y eventos narrativos arrastrando y conectando nodos. Las lógicas visuales se transpilan automáticamente y se ejecutan en tiempo real a través de nuestro motor de scripting `Rhai`.
* 📊 **Inspector de Simulación (Telemetría en Vivo):** Corre tu mundo de estrategia en segundo plano y espía cómo reacciona el PIB, la militancia ciudadana y la estabilidad global a través de gráficas WebSocket en tiempo real conectadas al editor.
* 🚀 **One-Click Deploy (Exportador):** Haz clic en "Publicar" y Zaraz Maker unirá tus bases de datos visuales con un binario pre-compilado del motor, entregándote un `.exe` (o binario Linux) nativo y optimizado, listo para distribuir en plataformas como Steam.

---

## 🧠 Potenciado por Zaraz Engine (Core Propietario)

Por debajo de los botones visuales, todos los juegos creados con Zaraz Maker son impulsados por **Zaraz Engine** (`zaraz-core`). Se trata de un motor de backend ultra-optimizado, desarrollado 100% en **Rust**, construido para resolver los cuellos de botella clásicos de los juegos de estrategia masivos.

A diferencia de los motores gráficos genéricos, Zaraz Engine está especializado en la matemática detrás del mundo:

* **Sistemas Multi-Hilo Asíncronos:** Desarrollado sobre la runtime `tokio`, capaz de procesar millones de transacciones simultáneas sin bloquear el hilo de dibujado gráfico.
* **Modelo Demográfico Avanzado (POPs):** Simulación estricta de estratos poblacionales con necesidades dinámicas, riqueza variable y cálculo de asimilación e ideología cultural.
* **Simulador Económico (Ledger System):** Motor de doble partida contable para seguimiento del flujo comercial, inventarios mundiales de materias primas e ingresos fiscales nacionales.
* **Inteligencia Geopolítica Modular (Utility AI):** Agentes evaluadores basados en curvas de utilidad para la toma de decisiones diplomáticas o militares.

---

<div align="center">
  <p><i>Arquitectura construida con ❤️ en Rust, Tauri y TypeScript.</i></p>
  <p><b>Estado del Proyecto:</b> En Desarrollo Activo.</p>
</div>
