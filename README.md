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
    DEV["👨‍💻 Alejandro De Mendoza\nDesarrollo individual"] --> U02["📁 unidad-02/"]
    DEV --> U03["📁 unidad-03/"]
    DEV --> U04["📁 unidad-04/"]
    DEV --> FORO["📁 foro/"]

    U02 --> A1["Desarrollo_Indentificacion_Atributos_Calidad.docx"]
    U02 --> A2["Desarrollo_Indentificacion_Atributos_Calidad_grupo_mad_7.docx"]

    U03 --> B1["TradeNova_C4.archimate"]
    U03 --> B2["Desarrollo_U3_DisenoArqSoft_Final_Alejandro_De_Mendoza.docx"]
    U03 --> B3["01 - 04 · Diagramas C4 .png"]

    U04 --> C1["ADD_SmartRoad_U4.docx"]
    U04 --> C2["LF_U4.docx"]
    U04 --> C3["c4-model-tradenova.drawio"]

    FORO --> D1["Infografia de Alejandro De Mendoza.pdf"]

    A1 & A2 & B1 & B2 & B3 & C1 & C2 & C3 & D1 --> REPO[("🗄️ diseno-arquitectonico-software\nGitHub · AlejoTechEngineer")]
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
│   ├── Desarrollo_Indentificacion_Atributos_Calidad.docx              # Entrega individual
│   ├── Desarrollo_Indentificacion_Atributos_Calidad.pdf
│   ├── Desarrollo_Indentificacion_Atributos_Calidad_grupo_mad_7.docx  # Entrega grupal (MAD-7)
│   ├── Desarrollo_Indentificacion_Atributos_Calidad_grupo_mad_7.pdf
│   ├── 1.png
│   └── Comprobante de entrega de la atividad desarrollada.png
│
├── unidad-03/                                                         # Lab No. 2 — Modelo C4 TradeNova
│   ├── README.md                                                      # Documentación del modelo C4
│   ├── TradeNova_C4.archimate                                         # Modelo ArchiMate (fuente)
│   ├── 01 - Diagrama de Contexto.png
│   ├── 02 - Diagrama de Contenedores.png
│   ├── 03 - Diagrama de Componentes.png
│   ├── 04 - Diagrama de Código.png
│   ├── Desarrollo_U3_DisenoArqSoft_Final_Alejandro_De_Mendoza.docx
│   ├── Desarrollo_U3_DisenoArqSoft_Final_Alejandro_De_Mendoza.pdf
│   ├── ActividadFormativa_U3.docx
│   ├── ActividadFormativa_U3.pdf
│   ├── TradeNova_Informe_C4_Completo.docx
│   └── TradeNova_Informe_C4_Completo.pdf
│
├── unidad-04/                                                         # Lab No. 3 — ADD SmartRoad
│   ├── ADD_SmartRoad_U4.docx                                          # Architecture Decision Document
│   ├── LF_U4.docx
│   ├── LF_U4.pdf
│   ├── ActividadSumativa_U4.docx
│   ├── ActividadSumativa_U4.pdf
│   ├── c4-model-tradenova.drawio
│   ├── Unidad3_C4_TradeNova-copia-apa.docx
│   └── Imagen soporte entrega.jpeg
│
└── foro/                                                              # Actividad de foro
    ├── Infografia de Alejandro De Mendoza.pdf
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
