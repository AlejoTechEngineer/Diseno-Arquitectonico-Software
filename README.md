<div align="center">

# 🏗️ Diseño Arquitectónico de Software

### Actividades · Laboratorios · Entregas — Unidades 2 · 3 · 4

[![ArchiMate](https://img.shields.io/badge/ArchiMate-3.1-1168BD?style=for-the-badge)](https://www.opengroup.org/archimate-forum)
[![Archi](https://img.shields.io/badge/Archi-5.9.0-FF6B35?style=for-the-badge)](https://www.archimatetool.com/)
[![C4 Model](https://img.shields.io/badge/C4%20Model-Simon%20Brown-0B4884?style=for-the-badge)](https://c4model.com/)
[![Draw.io](https://img.shields.io/badge/Draw.io-Diagramas-F08705?style=for-the-badge&logo=diagramsdotnet&logoColor=white)](https://www.drawio.com/)
[![Word](https://img.shields.io/badge/Word-DOCX-2B579A?style=for-the-badge&logo=microsoftword&logoColor=white)](https://www.microsoft.com/microsoft-365/word)
[![License](https://img.shields.io/badge/License-Academic-blueviolet?style=for-the-badge)](.)

*Repositorio maestro del módulo Diseño Arquitectónico de Software · Maestría en Arquitectura de Software · Politécnico Grancolombiano*

</div>

---

## ¿Qué es esto?

Repositorio consolidado con todas las actividades, laboratorios y entregas del módulo **Diseño Arquitectónico de Software**, correspondiente a la Maestría en Arquitectura de Software del Politécnico Grancolombiano.

Organiza en un único lugar las tres unidades trabajadas durante el módulo: identificación de atributos de calidad (Unidad 2), modelado de arquitectura con C4 y ArchiMate sobre el caso TradeNova (Unidad 3), y diseño de decisiones arquitectónicas con el método ADD sobre SmartRoad (Unidad 4).

---

## Arquitectura

```mermaid
flowchart TD
    DEV["👨‍💻 Alejandro De Mendoza\nDesarrollo individual"] --> FU02 & FU03 & FU04 & FFORO

    subgraph FUENTES["📁 fuentes-originales/  —  material fuente no-PDF"]
        FU02["unidad-02/\n.docx · .png"]
        FU03["unidad-03/\n.docx · .png · .archimate · .drawio"]
        FU04["unidad-04/\n.docx · .drawio · .jpeg"]
        FFORO["foro/\n.png"]
    end

    FU02 -- "PDF" --> U02["📁 unidad-02/\nentregas en PDF"]
    FU03 -- "PDF" --> U03["📁 unidad-03/\nentregas en PDF"]
    FU04 -- "PDF" --> U04["📁 unidad-04/\nentregas en PDF"]
    FFORO -- "PDF" --> FORO["📁 foro/\nentregas en PDF"]

    U02 & U03 & U04 & FORO --> REPO[("🗄️ diseno-arquitectonico-software\nGitHub · AlejoTechEngineer")]
```

---

## Estructura

```
diseno-arquitectonico-software/
│
├── README.md                                                          # Este archivo
├── .gitignore
│
├── unidad-02/                                                         # Lab No. 1 — Atributos de Calidad
│   ├── README.md
│   ├── Desarrollo_Indentificacion_Atributos_Calidad.pdf               # Entrega individual
│   └── Desarrollo_Indentificacion_Atributos_Calidad_grupo_mad_7.pdf   # Entrega grupal (MAD-7)
│
├── unidad-03/                                                         # Lab No. 2 — Modelo C4 TradeNova
│   ├── README.md                                                      # Documentación del modelo C4
│   ├── ActividadFormativa_U3.pdf
│   ├── Desarrollo_U3_DisenoArqSoft_Final_Alejandro_De_Mendoza.pdf
│   └── TradeNova_Informe_C4_Completo.pdf
│
├── unidad-04/                                                         # Lab No. 3 — ADD SmartRoad
│   ├── README.md
│   ├── ActividadSumativa_U4.pdf
│   ├── ADD_SmartRoad_U4.pdf                                           # Architecture Decision Document
│   ├── LF_U4.pdf
│   └── Unidad3_C4_TradeNova-copia-apa.pdf
│
├── foro/                                                              # Actividad de foro
│   └── Infografia de Alejandro De Mendoza.pdf
│
└── fuentes-originales/                                                # Material fuente no-PDF
    ├── unidad-02/
    │   ├── Desarrollo_Indentificacion_Atributos_Calidad.docx
    │   ├── Desarrollo_Indentificacion_Atributos_Calidad_grupo_mad_7.docx
    │   ├── 1.png
    │   └── Comprobante de entrega de la atividad desarrollada.png
    ├── unidad-03/
    │   ├── TradeNova_C4.archimate                                     # Modelo ArchiMate (fuente)
    │   ├── ActividadFormativa_U3.docx
    │   ├── Desarrollo_U3_DisenoArqSoft_Final_Alejandro_De_Mendoza.docx
    │   ├── TradeNova_Informe_C4_Completo.docx
    │   └── 01-04 · Diagramas C4 .png
    ├── unidad-04/
    │   ├── ADD_SmartRoad_U4.docx
    │   ├── ActividadSumativa_U4.docx
    │   ├── LF_U4.docx
    │   ├── Unidad3_C4_TradeNova-copia-apa.docx
    │   ├── c4-model-tradenova.drawio
    │   └── Imagen soporte entrega.jpeg
    └── foro/
        └── Infografia de Alejandro De Mendoza.png
```

---

## Resumen por unidad

| Unidad | Tema | Tipo de entrega | Estado |
|--------|------|-----------------|--------|
| **Unidad 2** | Identificación de Atributos de Calidad | Documento Word + PDF (individual y grupal MAD-7) | ✅ Entregado |
| **Unidad 3** | Modelado C4 — TradeNova (plataforma de trading) | Modelo ArchiMate · Informe · Diagramas C4 exportados | ✅ Entregado |
| **Unidad 4** | Architecture Decision Document (ADD) — SmartRoad | Documento ADD · Lineamiento formal · Draw.io | ✅ Entregado |
| **Foro** | Infografía de arquitectura de software | PDF + PNG | ✅ Entregado |

---

## Herramientas

| Herramienta | Versión | Propósito |
|-------------|---------|-----------|
| **[Archi](https://www.archimatetool.com/)** | 5.9.0 | Modelado ArchiMate y exportación de diagramas C4 |
| **ArchiMate** | 3.1 | Lenguaje de modelado de arquitectura empresarial (Open Group) |
| **C4 Model** | — | Framework de comunicación de arquitectura (Simon Brown) |
| **[Draw.io](https://www.drawio.com/)** | — | Diagramas de arquitectura vectoriales |
| **Microsoft Word** | — | Redacción de informes, documentos técnicos y entregas |

---

## Autor

**Alejandro De Mendoza**  
Ingeniero Informático · Especialista en IA · Maestría en Arquitectura de Software  
[@AlejoTechEngineer](https://github.com/AlejoTechEngineer)
