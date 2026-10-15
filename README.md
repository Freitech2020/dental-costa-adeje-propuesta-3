# Dental Costa Adeje — Propuesta 3: Coastal Human Trust & Instant CRO

**Rediseño Web Dental Costa Adeje 2026 • Modalidad 3**

Repositorio oficial de la Propuesta 3 para el rediseño de **Costa Adeje Dental Center** (dentalcostaadeje.com).

---

## 🌊 Concepto Estratégico & Posicionamiento

La propuesta **"Coastal Human Trust & Instant CRO"** está diseñada para eliminar por completo la ansiedad y el miedo al dentista (*odontofobia cero*), conectando con pacientes locales y turistas europeos en Tenerife Sur a través de una experiencia cálida, empática, transparente y de altísima conversión.

### Pilares Fundamentales:
1. **Estética Bioclimática Cálida**: Paleta inspirada en la luz de Costa Adeje y el Océano Atlántico: Marfil Cálido (`#FAF9F6`), Arena Suave (`#F4EFEA`), Azul Atlántico (`#023E8A`) y Terracota Solar (`#E76F51`).
2. **Escudo Anti-Odontofobia (4 Bloques)**:
   - Sedación consciente monitorizada para cirugías sin dolor ni ansiedad.
   - Anestesia computerizada indolora sin pinchazos bruscos.
   - Tiempos sin prisas y trato médico cercano.
   - Presupuestos cerrados 100% transparentes con financiación al 0%.
3. **Furgoneta de Transporte Gratuito**: Servicio exclusivo de recogida y retorno en hotel o domicilio para pacientes en Costa Adeje, Playa de las Américas y Los Cristianos.
4. **Embudo CRO Instantáneo en 3 Clics**: Reemplazo de formularios densos por un flujo interactivo ágil conectado directamente con WhatsApp (`+34 683 10 10 30`).
5. **Autoridad Médica E-E-A-T Colegiada**: Presentación detallada del cuadro médico (Dra. Maryuri de Castro, Dr. Facundo Mateo Ríos, Dra. Ana Isabel Martín Fuster) con sus respectivos números oficiales de colegiación COEST.
6. **Experiencia Multilingüe (ES, EN, DE, IT)**: Selector dinámico interactivo de 4 idiomas.

---

## 📁 Estructura del Entregable

```
propuesta-3-coastal-trust/
├── index.html                 # Prototipo interactivo navegable (HTML5/CSS/JS)
├── elementor-template.json    # Plantilla lista para Elementor Pro (Flexbox Containers v0.4)
├── README.md                  # Especificaciones y documentación
├── .gitignore                 # Exclusiones de control de versiones
└── assets/                    # Activos WebP (<90 KB) y spritesheet SVG
    ├── logo_costa_adeje_dental.webp
    ├── hero_coastal_warm.webp
    ├── transporte_vip_shuttle.webp
    ├── doctora_maryuri_castro.webp
    ├── doctor_facundo_mateo.webp
    ├── clinica_doctora_consulta.webp
    ├── marca_straumann.webp
    ├── marca_invisalign.webp
    ├── marca_nobel_biocare.webp
    ├── marca_spark.webp
    ├── marca_ticare.webp
    └── spritesheet_dental_icons.svg
```

---

## 🎨 Design Tokens & Accesibilidad WCAG 2.1 AA

- **Fondo Base**: `#FAF9F6` (Sunlight Ivory)
- **Superficies**: `#FFFFFF` / `#F4EFEA`
- **Color Principal / Acento**: `#023E8A` (Atlantic Blue)
- **Texto Principal**: `#0A2540` (Trust Navy — Ratio 14.30:1 en `#FAF9F6`, 15.70:1 en `#FFFFFF`, nivel AAA)
- **Texto Cuerpo**: `#334155` (Slate Body — Ratio 9.15:1 en `#FAF9F6`, nivel AAA)
- **Acento Cálido**: `#E76F51` (Terracotta)
- **Bordes & Radios**: `border-radius: 20px` en tarjetas y `9999px` en píldoras y botones.
- **Tipografía**: Montserrat (Google Fonts) — H1 único en Hero, cuerpo desktop >= 18px (line-height 1.6em), móvil >= 16px (line-height 1.5em).

---

## 🚀 Despliegue en WordPress / Elementor Pro

1. Abrir el panel de administración de WordPress en el entorno Staging o Producción.
2. Ir a **Plantillas > Plantillas Guardadas > Importar Plantillas**.
3. Seleccionar y subir el archivo `elementor-template.json`.
4. Crear una nueva página en Elementor y cargar la plantilla importada.
5. Los estilos están desacoplados mediante selectores `html body[class*="elementor-page"]` inmunes a cambios de tema.

---

## 📦 Control de Versiones & Git

- **Rama principal**: `main`
- **Identidad**: `Freitech` (`freitech@users.noreply.github.com`)
- **Remoto configurado**: `https://github.com/Freitech2020/dental-costa-adeje-propuesta-3.git`
