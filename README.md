# Química AR — Modelos Moleculares en Realidad Aumentada

> Proyecto de investigación en química para la visualización de ácidos carboxílicos mediante modelos 3D interactivos con Realidad Aumentada.

**Laboratorio MACEDONIA × LabTec UMCE**

---

## 🔬 Descripción

Este repositorio contiene los archivos necesarios para explorar **14 modelos 3D de ácidos carboxílicos** en Realidad Aumentada directamente desde el navegador del teléfono, sin necesidad de instalar ninguna aplicación.

La iniciativa es parte de un proyecto de investigación en química y educación química del [Laboratorio MACEDONIA](https://sites.google.com/umce.cl/lab-macedonia/) —química orgánica y formación inicial docente— desarrollado en colaboración con el [Laboratorio de Tecnología (LabTec)](https://sites.google.com/umce.cl/labtec) de la [Universidad Metropolitana de Ciencias de la Educación (UMCE)](https://www.umce.cl/).

## 🧪 Moléculas disponibles

| # | Molécula | Fórmula | pKa |
|---|----------|---------|-----|
| 00 | Ácido Acético | C₂H₄O₂ | 4,76 |
| 01 | Ácido Butanoico | C₄H₈O₂ | 4,82 |
| 02 | Ácido Cloroacético | C₂H₃ClO₂ | 2,86 |
| 03 | Ácido (Dimetilamino)oxoacético | C₄H₇NO₃ | ~2,0 |
| 04 | Ácido 2,2-Dimetilpropanoico | C₅H₁₀O₂ | 5,03 |
| 05 | Ácido Fórmico | CH₂O₂ | 3,75 |
| 06 | Ácido Glicólico | C₂H₄O₃ | 3,83 |
| 07 | Ácido Glioxílico | C₂H₂O₃ | 3,18 |
| 08 | Ácido Láctico | C₃H₆O₃ | 3,86 |
| 09 | Ácido Oxálico | C₂H₂O₄ | 1,25 / 4,27 |
| 10 | Ácido Propanoico | C₃H₆O₂ | 4,87 |
| 11 | Ácido Sulfanilacético | C₂H₄O₂S | 3,68 |
| 12 | Ácido Trifluoroacético | C₂HF₃O₂ | 0,5 |
| 13 | Ácido 2-Fosfonoacético | C₂H₅O₅P | 1,34 / 4,82 |

## 📱 Cómo usar

1. Accede al sitio desde tu teléfono: **https://lab-macedonia.github.io/quimica-ar/**
2. Selecciona la molécula que quieres explorar.
3. Rota el modelo con un dedo · Zoom con dos dedos.
4. Pulsa el botón **AR** para proyectarla en tu espacio real (apunta al suelo).

> Compatible con cualquier navegador moderno en Android e iOS. La función AR requiere Chrome (Android) o Safari (iOS 12+).

## 📁 Estructura del repositorio

```
quimica-ar/
├── index.html              ← Página principal con el índice de moléculas
├── Acetico.html
├── Butanoico.html
├── Cloroacetico.html
├── Dimetilaminooxoacetico.html
├── Dimetilpropanoico.html
├── Formico.html
├── Glicolico.html
├── Glioxilico.html
├── Lactico.html
├── Oxalico.html
├── Propanoico.html
├── Sulfanylacetic.html
├── Trifluoroacetico.html
├── 2-phosphonoacetic.html
├── Acetico.glb             ← Modelos 3D (formato glTF Binary)
├── Butanoico.glb
└── ...
```

## 🛠️ Tecnologías

- [Google Model Viewer](https://modelviewer.dev/) — renderizado 3D y AR en el navegador
- HTML5 + CSS3 + JavaScript vanilla
- Modelos en formato `.glb` (glTF Binary)
- Alojado en [GitHub Pages](https://pages.github.com/)

## 🏛️ Instituciones

| | |
|---|---|
| **Laboratorio MACEDONIA** | Química orgánica y educación química · Formación inicial docente (FID) · [Visitar sitio](https://sites.google.com/umce.cl/lab-macedonia/) |
| **LabTec** | Laboratorio de Tecnología · Innovación en educación científica · [Visitar sitio](https://sites.google.com/umce.cl/labtec) |
| **UMCE** | Universidad Metropolitana de Ciencias de la Educación · [www.umce.cl](https://www.umce.cl/) |

---

© 2025 Laboratorio MACEDONIA · LabTec · UMCE · Todos los derechos reservados
