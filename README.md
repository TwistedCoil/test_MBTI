# Test orientativo: perfil del director de proyectos

Un test breve que ayuda a reconocer tu estilo para dirigir proyectos y te da una orientación sobre qué habilidades reforzar.

Combina dos enfoques:

- **Dimensiones de personalidad al estilo MBTI**: de dónde sacas energía, cómo tomas la información, cómo decides y cómo te organizas.
- **Los cuatro tipos de director de proyectos de Max Wideman (2002)**: Explorador, Coordinador, Impulsor y Administrador.

Está pensado para personas de perfil técnico y ejecutivo que quieren una primera mirada a su forma de liderar, sin registros ni formularios.

> **Importante:** este test es una **orientación, no un diagnóstico**. No reemplaza el MBTI oficial ni la evaluación de un profesional.

---

## Privacidad

- **No se guardan datos.** Todo se calcula en tu navegador.
- **No se envía información** a ningún servidor ni se usan servicios externos (sin cookies, analítica, fuentes ni librerías externas).
- Al cerrar o recargar la página, las respuestas se borran.

Puedes comprobarlo revisando el código: es un solo archivo HTML con CSS y JavaScript incluidos.

---

## Qué incluye

- **30 preguntas** en dos partes (toma entre 5 y 7 minutos):
  - **Parte 1:** 20 frases con escala del 1 al 5 sobre las cuatro dimensiones de personalidad.
  - **Parte 2:** 10 preguntas de elección basadas en los rasgos del Apéndice A del artículo de Wideman.
- **Resultados con:**
  - Un tipo aproximado de cuatro letras con barras por dimensión. Si una dimensión queda entre 45 % y 55 %, se marca con **x** (equilibrada).
  - Tu distribución entre los cuatro tipos de Wideman.
  - "Lo que te sale natural" y "Lo que te conviene reforzar".
  - Formación o guía sugerida según tu estilo.
  - La fase del proyecto donde tu estilo rinde mejor.
- Un botón para **imprimir o guardar en PDF**.
- Validación de preguntas sin responder y barra de progreso.
- Diseño claro, adaptable a celular y escritorio.

---

## Cómo usarlo

### Opción 1: abrirlo en tu computador

1. Descarga `index.html`.
2. Ábrelo con cualquier navegador (Chrome, Firefox, Edge o Safari).

No necesita instalación ni conexión a internet.

### Opción 2: publicarlo con GitHub Pages

1. Sube `index.html` a la raíz del repositorio.
2. En el repositorio, ve a **Settings → Pages**.
3. En **Source**, elige **Deploy from a branch**, luego la rama `main` y la carpeta `/ (root)`.
4. Guarda. En unos minutos quedará disponible en:
   `https://<tu-usuario>.github.io/<nombre-del-repositorio>/`

---

## Estructura

```
.
├── index.html   # El test completo (HTML + CSS + JavaScript)
└── README.md
```

---

## Cómo se calcula

**Dimensiones de personalidad.** Cada dimensión tiene 5 frases. Algunas suman hacia un lado y otras hacia el contrario, para evitar respuestas automáticas. El puntaje se convierte en un porcentaje entre los dos polos:

| Dimensión | Polo 1 | Polo 2 |
|---|---|---|
| Energía | E · Extroversión | I · Introversión |
| Información | S · Sensación | N · Intuición |
| Decisiones | T · Pensamiento | F · Sentimiento |
| Organización | J · Juicio | P · Percepción |

**Tipos de Wideman.** Cada pregunta de la Parte 2 tiene cuatro opciones, una por tipo, tomadas de las características personales que el autor describe para cada estilo. Se cuenta cuántas veces elegiste cada tipo.

| Tipo | Rasgo central | Fase donde rinde mejor |
|---|---|---|
| Explorador | Imaginativo | Concepto |
| Coordinador | Receptivo | Desarrollo y planificación |
| Impulsor | Asertivo | Ejecución |
| Administrador | Organizado | Cierre |

---

## Limitaciones

- Es un instrumento **corto y no validado estadísticamente**. Sirve para reflexionar, no para tomar decisiones de selección de personal.
- Las respuestas dependen de cómo te ves a ti mismo. Para una mirada más completa, se recomienda una **evaluación 360°**.
- Si buscas un diagnóstico formal, usa el **MBTI oficial** con un profesional certificado o un test **Big Five** validado.

---

## Referencia

Wideman, R. M. (2002). *Dominant personality traits suited to running projects successfully (and what type are you?)*. AEW Services, Vancouver, BC. http://www.maxwideman.com/papers/personality/personality.pdf

*Myers-Briggs Type Indicator®* y *MBTI®* son marcas registradas de sus respectivos titulares. Este proyecto no está afiliado a ellos ni usa sus instrumentos oficiales.

---

## Autor

**René Valdés Mena** · [@TwistedCoil](https://github.com/TwistedCoil)

Desarrollado como material de apoyo para la asignatura *Fundamentos de la Empresa* (UNIR).
