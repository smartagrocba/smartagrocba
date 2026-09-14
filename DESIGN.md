# SmartAgro - Design System & Architecture Specification

![SmartAgro UI Screen](C:/Users/Usuario/.gemini/antigravity/brain/9f172ce1-ad02-454b-9767-2cfef087cd7a/screen_1789391040117.png)

## 📌 Visión General
**SmartAgro** es una plataforma web de aterrizaje (Landing Page) de alto rendimiento para servicios de agronomía de precisión utilizando tecnología aeronáutica (drones de pulverización, siembra y fertilización).

El diseño combina una estética **Dark Mode futurista** con micro-interacciones dinámicas, telemetría HUD en tiempo real y flujos de conversión optimizados hacia atención telefónica y WhatsApp.

---

## 🎨 Paleta de Colores & Tokens Visuales

| Token | Código Hex / HSL | Aplicación |
|---|---|---|
| **Primary Green** | `#10b981` | Botones de conversión principal, bordes activos, iconos HUD |
| **Primary Bright** | `#4edea3` | Estados hover, brillos resplandecientes |
| **Secondary Lime** | `#94de2d` | Métricas de flujo, datos de caudal y rendimiento |
| **Background Dark** | `#0a0f0d` | Fondo principal profundo anti-fatiga visual |
| **Surface Dark** | `#0f1513` | Superficie de secciones alternadas |
| **Surface Container** | `#171d1b` | Tarjetas de contenido, módulos de especificaciones |
| **Surface Border** | `#222c27` | Divisiones y bordes técnicos ultra finos |
| **On-Surface Text** | `#f1f5f3` | Texto principal de alta legibilidad |
| **WhatsApp Brand** | `#25D366` | Botón flotante animado de conversión rápida |

---

## 📐 Tipografía

* **Display / Titulares**: `Space Grotesk` (Google Fonts) — Pesos `500, 600, 700`. Aporta un aspecto técnico, preciso y contemporáneo.
* **Cuerpo de Texto**: `Manrope` (Google Fonts) — Pesos `400, 500, 600, 700`. Facilidad de lectura en cualquier resolución.
* **Telemetría & Datos**: `Font-Mono` (System Monospace) — Estructura técnica para datos satelitales RTK y mediciones anemométricas.

---

## 🚀 Componentes & Estructura de Secciones

### 1. Header Fijo con Blur Vítreo
* **Logo Vectorial**: Icono delta de precisión agronómica + logotipo "SmartAgro".
* **Navegación Suave**: Enlaces inteligentes a `#inicio`, `#servicios`, `#tecnologia`, `#habilitacion` y `#valores`.
* **CTA Principal**: Botón directo de agendamiento con enlace instantáneo a WhatsApp (`+54 9 3513884764`).

### 2. Hero Section con Video Telemétrico Autoplay
* **Matriz RTK 3D**: Cuadro de mando con latitud/longitud en vivo, altitud constante (3.5 m) y desvío milimétrico (± 1.2 cm RTK).
* **Video Autoplay Continuo**: Transmisión fluida del dron operando en lote agrícola (`264875f3cb5230d46db99a55f4dbbd2d.mp4`).
* **Distintivo Fitosanitario**: Carnet oficial de operador fitosanitario habilitado.

### 3. Capacidades Operativas (Servicios)
* **Pulverización de Precisión**: Micro-gotas sin deriva, ahorro de hasta 30% en fitosanitarios.
* **Siembra Aérea de Cobertura**: Implantación directa sobre cultivo en pie antes de cosecha.
* **Fertilización Foliar Dirigida**: Aporte nutricional en estadios críticos (R1-R5).

### 4. Ingeniería Aeronáutica & Video de Boquillas
* **Métricas Principales**: Tanque 70L, Caudal 40L/min, Tolva 80kg, Empuje 76kg, Batería 30,000mAh.
* **Video de Atomización Centrífuga**: Módulo de boquillas de gota regulable (50-500 µ) con reproducción en bucle (`f6a3d2de43aef592f6774f1b27cf58a2.mp4`).

### 5. Marco Legal & Valores Sustentables
* Carnet Fitosanitario Habilitante, Operadores Comerciales Certificados y Protocolos de Deriva Cero.
* Mapeo de beneficios: 0% compactación de suelo, -90% uso de agua y 100% cuidado del operario.

### 6. Botón Flotante con Pulso de WhatsApp
* Posicionamiento fijo inferior derecho con pulso dinámico de resplandor verde e integración directa con WhatsApp:
  `https://wa.me/5493513884764`

---

## 📱 Responsividad & Optimizaciones
* 100% Mobile First & Responsive Design (Breakpoints Tailwind `sm`, `md`, `lg`).
* Carga asíncrona de fuentes externas e iconos vectoriales SVG limpios sin imágenes pesadas que obstaculicen el rendimiento.
* Videos configurados con atributos estándar de aceleración de hardware: `autoplay loop muted playsinline`.
