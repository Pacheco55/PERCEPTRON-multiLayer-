<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1A0A2E,50:7B2FBE,100:00C896&height=200&section=header&text=ColorMLP&fontSize=72&fontColor=F5D580&fontAlignY=38&desc=Red%20Neuronal%20Perceptrón%20Multicapa%20para%20Android&descColor=C8B8E8&descAlignY=58&animation=fadeIn" width="100%"/>

<br/>

[![Platform](https://img.shields.io/badge/Platform-Android-00C896?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Pacheco55)
[![Framework](https://img.shields.io/badge/.NET%20MAUI-8.0-7B2FBE?style=for-the-badge&logo=dotnet&logoColor=white)](https://learn.microsoft.com/en-us/dotnet/maui/)
[![Language](https://img.shields.io/badge/C%23-12.0-C9A84C?style=for-the-badge&logo=csharp&logoColor=1A0A2E)](https://learn.microsoft.com/en-us/dotnet/csharp/)
[![APK](https://img.shields.io/badge/Descarga-APK-00C896?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Pacheco55/ColorMLP/releases/latest)
[![Studio](https://img.shields.io/badge/PIXELBITS-Studio-C9A84C?style=for-the-badge&logoColor=1A0A2E)](https://github.com/Pacheco55)

<br/>

> **Detecta el color de cualquier píxel en imágenes** usando una Red Neuronal entrenada directamente en tu dispositivo Android. Sin servidores, sin internet, 100% local.

<br/>

</div>

---

## ⚡ Descarga e Instalación

<div align="center">

### Solo necesitas el APK — sin código, sin compilación

```
Releases → ColorMLP_v2.apk → Instalar en Android
```

[![Download APK](https://img.shields.io/badge/⬇%20Descargar%20APK-Releases-00C896?style=for-the-badge&logo=android)](https://github.com/Pacheco55/ColorMLP/releases/latest)

</div>

> **Requisito mínimo:** Android 5.0 (API 21) · Cualquier dispositivo moderno

**Pasos:**
1. Descarga `ColorMLP_v2.apk` desde la sección **Releases**
2. En tu Android: **Ajustes → Seguridad → Orígenes desconocidos** → Activar
3. Abre el APK descargado e instala
4. Listo — abre **ColorMLP** desde el launcher

---

## 🎨 ¿Qué hace ColorMLP?

ColorMLP entrena una **red neuronal perceptrón multicapa desde cero** en tu propio teléfono Android y la usa para clasificar el color de cualquier punto en una imagen. Todo ocurre localmente, sin conexión a internet.

<div align="center">

| Función | Descripción |
|:---:|:---|
| 🧠 **Entrenamiento local** | El MLP se entrena directamente en el dispositivo |
| 🎨 **Detección de color** | Clasifica píxeles en 9 categorías de color |
| ⚙️ **Totalmente configurable** | Ajusta cada hiperparámetro desde la interfaz |
| 📊 **Barras de confianza** | Visualiza la certeza de la red por cada clase |
| 💾 **Modelo persistente** | El modelo entrenado se guarda y reutiliza |
| 📖 **Teoría integrada** | Sección de fundamentos científicos en la app |

</div>

---

## 📱 Pantallas de la App

<div align="center">

```
┌─────────────────┐   ┌─────────────────┐   ┌─────────────────┐   ┌─────────────────┐
│   🏠  INICIO    │   │  ⚡ ENTRENAR    │   │  🎨 DETECTOR   │   │  🧠  INFO       │
│                 │   │                 │   │                 │   │                 │
│  ┌───────────┐  │   │  Neuronas: ──○  │   │ ┌─────┐ Rojo  │   │  Ecuaciones     │
│  │ 🎨 Detect │  │   │  η:        ──○  │   │ │     │ 97.3% │   │  Forward Pass   │
│  └───────────┘  │   │  Épocas: [───]  │   │ └─────┘       │   │  Backpropag.    │
│  ┌───────────┐  │   │  ECM:   [─────] │   │               │   │  Patrón IAUPT   │
│  │⚡ Entrenar│  │   │  [🟢] [🟡] [🔴]│   │  ████░░ 97%   │   │                 │
│  └───────────┘  │   │                 │   │  ██░░░░ 45%   │   │  .pml → train   │
│  ┌───────────┐  │   │  ⚡ Entrenar ▶  │   │  █░░░░░ 12%   │   │  .ppm → model   │
│  │🧠 Info    │  │   │                 │   │               │   │                 │
│  └───────────┘  │   │  ECM: 0.00412   │   │  [📂] [✏️]   │   │                 │
└─────────────────┘   └─────────────────┘   └─────────────────┘   └─────────────────┘
```

</div>

---

## 🎛️ Parámetros Configurables

<div align="center">

| Parámetro | Control | Rango | Impacto |
|:---|:---:|:---:|:---|
| **Neuronas ocultas** | Slider | 2 – 20 | Mayor capacidad vs. velocidad |
| **Factor η (lr)** | Slider + campo | 0.01 – 0.99 | Velocidad de convergencia |
| **Épocas máximas** | Campo de texto | ≥ 100 | Profundidad del entrenamiento |
| **ECM mínimo** | Campo de texto | > 0 | Criterio de parada por precisión |
| **Patrones / clase** | Slider | 5 – 80 | Calidad de generalización |
| **Función activación** | Picker | 3 opciones | Tipo de no linealidad |

</div>

### Presets incluidos

```
🟢  Rápido       →  η=0.50 | 3,000 épocas  | 4 ocultas  | 10 patrones  (~15 s)
🟡  Balanceado   →  η=0.40 | 15,000 épocas | 6 ocultas  | 20 patrones  (~2 min)
🔴  Preciso      →  η=0.25 | 40,000 épocas | 12 ocultas | 50 patrones  (~10 min)
```

---

## 🏷️ Clases de Color Detectadas

<div align="center">

![Rojo](https://img.shields.io/badge/%20-Rojo-E82020?style=flat-square)
![Verde](https://img.shields.io/badge/%20-Verde-14B450?style=flat-square)
![Azul](https://img.shields.io/badge/%20-Azul-2855D2?style=flat-square)
![Amarillo](https://img.shields.io/badge/%20-Amarillo-DCC80A?style=flat-square)
![Naranja](https://img.shields.io/badge/%20-Naranja-E67014?style=flat-square)
![Morado](https://img.shields.io/badge/%20-Morado-8C28C8?style=flat-square&logoColor=white)
![Blanco](https://img.shields.io/badge/%20-Blanco-E0E0E0?style=flat-square&logoColor=black)
![Negro](https://img.shields.io/badge/%20-Negro-303030?style=flat-square)
![Gris](https://img.shields.io/badge/%20-Gris-909090?style=flat-square)

</div>

---

## 🔬 Técnico — Cómo está programado

<details>
<summary><b>🧱 Arquitectura del proyecto</b></summary>

<br/>

El proyecto sigue el patrón **MVVM** con inyección de dependencias nativa de .NET MAUI:

```
ColorMLP/
├── Models/
│   ├── PerceptronMulticapa.cs    ← Motor MLP puro (sin dependencias externas)
│   └── MLPService.cs             ← Generador de datos + servicio singleton DI
├── ViewModels/
│   └── ViewModels.cs             ← MainVM · EntrenamientoVM · DetectorVM · BarraVM
├── Converters/
│   └── InvertBoolConverter.cs    ← IValueConverter para binding XAML
├── Views/
│   ├── MainPage                  ← Menú de navegación
│   ├── EntrenamientoPage         ← Panel de hiperparámetros
│   ├── DetectorPage              ← Clasificador con barras de confianza
│   └── InfoPage                  ← Fundamentos científicos del MLP
└── Resources/Styles/
    ├── Colors.xaml               ← Paleta: #00C896 · #7B2FBE · #C9A84C
    └── Styles.xaml               ← Estilos globales + InvertBoolConverter
```

</details>

<details>
<summary><b>🧠 Motor del Perceptrón Multicapa</b></summary>

<br/>

Implementado desde cero en C# sin ninguna librería de ML externa. Basado en el patrón de la librería [IAUPT de Zechmarquis](https://github.com/zechmarquis/IAUPT):

**Arquitectura de la red para detección de color:**
```
Entrada (3)        Oculta (N)         Salida (9)
  R/255  ─┐
  G/255  ─┼──►  N neuronas  ──►  Rojo · Verde · Azul
  B/255  ─┘     sigmoidales      Amarillo · Naranja · Morado
                                 Blanco · Negro · Gris
```

**Forward Pass — propagación hacia adelante:**
```
Capa oculta:   net_i = Σ(w¹ᵢⱼ · xⱼ) + b¹ᵢ   →   h_i = f(net_i)
Capa salida:   net_k = Σ(w²ₖᵢ · hᵢ) + b²ₖ   →   y_k = f(net_k)
Clase = argmax(y)
```

**Backpropagation — 4 pasos:**
```
1. δₖ = (dₖ − yₖ) · f'(yₖ)                     ← delta salida
2. δᵢ = f'(hᵢ) · Σ(δₖ · w²ₖᵢ)                  ← delta oculta
3. w²ₖᵢ ← w²ₖᵢ + η·δₖ·hᵢ  |  b²ₖ ← b²ₖ + η·δₖ  ← actualizar W²
4. w¹ᵢⱼ ← w¹ᵢⱼ + η·δᵢ·xⱼ  |  b¹ᵢ ← b¹ᵢ + η·δᵢ  ← actualizar W¹
```

**Funciones de activación disponibles:**
```csharp
"Sigmoide" → f(x) = 1/(1+e⁻ˣ)    f'(y) = y·(1−y)
"Tanh"     → f(x) = tanh(x)       f'(y) = 1−y²
"ReLU"     → f(x) = max(0,x)      f'(y) = 1 si y>0 else 0
```

</details>

<details>
<summary><b>📂 Patrón IAUPT — Persistencia del modelo</b></summary>

<br/>

Siguiendo el patrón de la librería IAUPT, el modelo usa dos tipos de archivo:

| Archivo | Uso | Contenido |
|:---|:---|:---|
| `.pml` | Entrenamiento | Arquitectura + η + ECM + épocas + patrones RGB |
| `.ppm` | Modelo guardado | Matrices W¹, W², vectores b¹, b² en formato G10 |

```
Entrenar:    new PerceptronMulticapa("color.pml") → .Entrenar() → genera .ppm
Inferencia:  new PerceptronMulticapa("color_model.ppm") → .Reconocer([R,G,B]) → .ClaseDetectada()
```

El modelo se guarda automáticamente en `FileSystem.AppDataDirectory` de Android y se carga al iniciar la app sin reentrenar.

</details>

<details>
<summary><b>⚙️ Stack técnico</b></summary>

<br/>

| Componente | Tecnología | Versión |
|:---|:---|:---|
| Framework | .NET MAUI | 8.0 |
| Lenguaje | C# | 12.0 |
| Target | Android | API 21+ |
| Patrón UI | MVVM | — |
| DI | Microsoft.Extensions.DI | Nativo MAUI |
| Observable | CommunityToolkit.Mvvm | 8.3.2 |
| MAUI extras | CommunityToolkit.Maui | 9.0.3 |
| Motor MLP | Implementación propia | — |
| Datos ML | Generados programáticamente | 9 clases × N patrones |
| IDE | Visual Studio Community 2022 | 17.8+ |

</details>

<details>
<summary><b>🎲 Datos de entrenamiento — One-Hot suavizado</b></summary>

<br/>

Los patrones de entrenamiento se generan programáticamente en `ColorDataGenerator` con rangos RGB por clase y codificación **one-hot suavizada** (0.9 / 0.1 en lugar de 1.0 / 0.0) para evitar saturación de la sigmoide en los extremos:

```
Rojo     →  R[0.70–1.00]  G[0.00–0.20]  B[0.00–0.20]
Verde    →  R[0.00–0.25]  G[0.55–1.00]  B[0.00–0.30]
Azul     →  R[0.00–0.20]  G[0.00–0.30]  B[0.60–1.00]
Amarillo →  R[0.75–1.00]  G[0.75–1.00]  B[0.00–0.20]
Naranja  →  R[0.80–1.00]  G[0.30–0.60]  B[0.00–0.15]
Morado   →  R[0.30–0.65]  G[0.00–0.25]  B[0.50–0.90]
Blanco   →  R[0.82–1.00]  G[0.82–1.00]  B[0.82–1.00]
Negro    →  R[0.00–0.18]  G[0.00–0.18]  B[0.00–0.18]
Gris     →  R≈G≈B  variación ±0.06 en rango [0.28–0.72]
```

</details>

---

## 📊 Rendimiento por preset

<div align="center">

| Preset | Arquitectura | ECM típico | Precisión | Tiempo Android |
|:---:|:---:|:---:|:---:|:---:|
| 🟢 Rápido | 3-4-9 | 0.015–0.025 | ~75% | < 15 s |
| 🟡 Balanceado | 3-6-9 | 0.003–0.006 | ~90% | 1–3 min |
| 🔴 Preciso | 3-12-9 | < 0.001 | > 97% | 5–15 min |

</div>

---

## 🎓 Contexto académico

<div align="center">

| | |
|:---|:---|
| **Materia** | Inteligencia Artificial y Redes Móviles |
| **Profesor** | Homer Alberto Lara Luis |
| **Institución** | Universidad Politécnica de Tecámac |
| **Grupo** | 5826 IS DUAL |
| **Referencia técnica** | [github.com/zechmarquis/IAUPT](https://github.com/zechmarquis/IAUPT) |

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C896,50:7B2FBE,100:1A0A2E&height=120&section=footer&text=PIXELBITS%20Studio&fontSize=28&fontColor=F5D580&fontAlignY=65&animation=fadeIn" width="100%"/>

[![GitHub](https://img.shields.io/badge/GitHub-Pacheco55-C9A84C?style=for-the-badge&logo=github&logoColor=1A0A2E)](https://github.com/Pacheco55)
[![Email](https://img.shields.io/badge/Email-studiospixelbits-7B2FBE?style=for-the-badge&logo=gmail&logoColor=white)](mailto:studiospixelbits@gmail.com)

**Julio César Pacheco Rojas · PIXELBITS Studio · 2026**

*Todos los derechos reservados*

</div>
