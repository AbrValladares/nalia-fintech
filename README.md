# Nalia Fintech

### Proyecto Final — Introducción a la Inteligencia Artificial

**Alumna:** Abril Valladares  
**Año:** 2026

---

## Sobre el proyecto

Nalia Fintech es una aplicación web de organización financiera personal asistida por Inteligencia Artificial Generativa.

El proyecto busca facilitar la comprensión y organización de las finanzas personales mediante una experiencia simple, visual y conversacional. La IA permite interpretar instrucciones escritas o por voz, registrar movimientos previa confirmación del usuario, realizar simulaciones y responder consultas utilizando los datos disponibles dentro de la aplicación.

Todos los datos utilizados en el prototipo son ficticios y fueron creados exclusivamente con fines académicos y demostrativos.

---

## Objetivos

- Facilitar el registro y consulta de movimientos financieros.
- Organizar ingresos, gastos, tarjetas, cuotas y próximos pagos.
- Permitir consultas mediante lenguaje natural.
- Incorporar carga de información mediante texto y voz.
- Realizar simulaciones sin modificar automáticamente los datos registrados.
- Mostrar objetivos de ahorro e inversiones registradas.
- Incorporar recordatorios y notificaciones dentro de la aplicación.
- Mantener al usuario en control de cualquier acción que modifique información.

---

## Alcance del proyecto

El prototipo funcional incluye:

- Inicio / dashboard financiero.
- Movimientos.
- Tarjetas y cuotas.
- Calendario financiero.
- Objetivos de ahorro.
- Inversiones.
- Contador amigo.
- Perfil.
- Configuración.
- Ayuda.
- Notificaciones.
- Registro manual de movimientos.
- Carga rápida mediante IA.
- Entrada mediante voz.
- Simulaciones financieras.
- Consultas sobre información registrada.
- Audios de identidad.

Nalia no se conecta con cuentas bancarias reales y no utiliza información financiera personal real.

---

## Sistema de Inteligencia Artificial

La IA de Nalia funciona como una capa de interpretación y consulta sobre la información disponible en la aplicación.

Uno de los principios fundamentales del sistema es:

**INTERPRETAR → MOSTRAR → CONFIRMAR → REGISTRAR**

La IA nunca debe registrar automáticamente una operación interpretada.

Antes de modificar información, debe mostrar al usuario qué entendió y permitir:

- Confirmar.
- Modificar.
- Cancelar.

Cuando falta información relevante, la IA debe solicitarla en lugar de inventarla.

También debe distinguir claramente entre:

- Datos registrados.
- Cálculos.
- Simulaciones.
- Proyecciones.

---

## Instrucciones Base del sistema

El asistente de Nalia debe:

- Utilizar solamente la información disponible.
- Priorizar precisión antes que completar una respuesta con información no confirmada.
- No inventar movimientos, montos, fechas, tarjetas ni cuotas.
- Solicitar información cuando falte un dato necesario.
- Mostrar la interpretación antes de registrar una operación.
- Permitir corregir la información interpretada.
- Diferenciar datos registrados de simulaciones.
- Mantener un lenguaje claro, tranquilo y no culpabilizante.
- No proporcionar asesoramiento financiero, contable, impositivo o legal profesional.

El nombre “Contador amigo” corresponde a la identidad del asistente y no implica que el sistema sea un contador público ni que sustituya asesoramiento profesional.

---

## Prompt Maestro

El sistema de IA de Nalia debe actuar como un asistente de organización financiera personal.

Debe interpretar instrucciones en lenguaje natural utilizando únicamente la información proporcionada por el usuario o registrada en el sistema.

Cuando el usuario solicite registrar una operación, debe identificar los datos disponibles, detectar información faltante y presentar una vista previa antes de realizar cualquier modificación.

Nunca debe inventar información para completar una operación.

Ante simulaciones o escenarios hipotéticos, debe indicar claramente que se trata de una simulación y que el movimiento no fue registrado.

Debe responder con lenguaje claro, cercano y tranquilo, evitando juicios sobre las decisiones financieras del usuario.

La IA organiza, interpreta y calcula información, pero la decisión final permanece siempre bajo control del usuario.

---

## Pruebas del sistema de IA

Se realizaron pruebas funcionales para verificar el comportamiento del asistente.

### Prueba 1 — Carga rápida completa

**Entrada:**

> Zara $450.000 BBVA, 3 cuotas, entra en septiembre.

**Resultado esperado y obtenido:**

Nalia interpreta la compra, identifica el importe, tarjeta y cantidad de cuotas y calcula tres cuotas de $150.000 correspondientes a septiembre, octubre y noviembre.

Antes de registrar la operación muestra una vista previa y permite confirmar, editar o cancelar.

---

### Prueba 2 — Información incompleta

**Entrada:**

> Zara $450.000 BBVA en 3 cuotas.

**Resultado esperado y obtenido:**

Nalia detecta que falta conocer el mes de inicio de las cuotas y solicita esa información.

El sistema no inventa el dato faltante ni registra automáticamente la operación.

---

### Prueba 3 — Simulación

**Entrada:**

> ¿Qué pasa si compro un pantalón de $180.000 en 10 cuotas?

Nalia calcula un valor estimado de $18.000 por cuota e identifica claramente la respuesta como:

**SIMULACIÓN**

También informa:

> Este movimiento todavía no fue registrado.

Cuando el usuario responde:

> en octubre

el asistente mantiene el contexto de la conversación y utiliza octubre como inicio de la simulación, sin registrar la compra.

---

### Prueba 4 — Consulta

**Entrada:**

> ¿Cuánto gasté este mes?

Nalia responde utilizando únicamente los movimientos registrados en el sistema.

---

## Cronograma y planificación temporal

El desarrollo de Nalia Fintech se organizó en etapas progresivas, cada una asociada a un resultado concreto.

| Etapa | Actividad | Resultado esperado |
|---|---|---|
| 1 | Definición del problema, público y objetivos | Concepto de Nalia Fintech definido |
| 2 | Configuración del sistema de IA | Instrucciones Base y Prompt Maestro |
| 3 | Diseño de identidad y producción visual | Mínimo de 3 activos visuales |
| 4 | Producción de audio | Mínimo de 2 clips de audio |
| 5 | Desarrollo y organización del prototipo | Demostración de las funciones principales |
| 6 | Auditoría ética | Identificación de riesgos y medidas de mitigación |
| 7 | Evaluación e iteraciones | Registro de correcciones y mejoras |
| 8 | Documentación final | README con prompts, parámetros, activos y decisiones |
| 9 | Publicación | URL pública del Proyecto Final |

---

# Producción multimodal

Como parte del desarrollo se generaron activos visuales y sonoros mediante herramientas de Inteligencia Artificial Generativa.

La producción incluyó el logo de Nalia, propuestas visuales para el dashboard, dos iteraciones de la pantalla del Contador amigo y dos audios.

---

## Generación de imágenes

**Herramienta:** ChatGPT — generación de imágenes.

Los parámetros Seed, CFG Scale y Steps no fueron expuestos ni configurables manualmente en la interfaz utilizada. Por este motivo no se incorporan valores estimados o ficticios.

### Imagen 1 — Logo de Nalia Fintech

**Prompt utilizado:**

> Diseñar un logo minimalista y moderno para una aplicación de organización financiera personal llamada “Nalia Fintech”. La identidad debe transmitir tranquilidad, organización, confianza y cercanía. Incorporar de manera muy sutil una referencia visual felina mediante formas geométricas o curvas, evitando ilustraciones infantiles o un gato literal. Combinar el concepto de finanzas personales con una estética tecnológica elegante y amigable. Diseño limpio, profesional, fácilmente reconocible como icono de aplicación móvil y web, fondo simple, composición equilibrada, sin elementos financieros clichés como billetes, monedas o signos de dólar.
>
> Negative prompt: cartoon cat, childish design, dollar signs, coins, money bills, crypto symbols, complex illustration, excessive details, aggressive financial aesthetic, neon colors, cluttered composition, distorted typography, watermark.

---

### Imagen 2 — Dashboard de Nalia Fintech

**Prompt utilizado:**

> Diseñar la interfaz de un dashboard web moderno para “Nalia Fintech”, una aplicación de organización financiera personal asistida por IA. Utilizar una estética minimalista, tranquila y profesional, con abundante espacio en blanco y jerarquía visual clara. Mostrar tarjetas independientes para ingresos del mes, gastos del mes, próximos pagos y progreso de ahorro. Incorporar navegación mediante secciones para “Inicio”, “Movimientos”, “Tarjetas”, “Objetivos” y “Contador amigo”. Evitar mostrar demasiada información simultáneamente. Utilizar datos financieros completamente ficticios. La interfaz debe transmitir sensación de control y tranquilidad en lugar de urgencia. Desktop web application UI, clean fintech dashboard, accessible typography, balanced spacing, modern UX/UI.
>
> Negative prompt: cluttered dashboard, excessive charts, stock market interface, crypto trading, red warning screens, banking credentials, real personal information, excessive text, tiny typography, visual overload, dark aggressive trading interface.

A partir de este prompt se generaron dos alternativas. Luego de compararlas se seleccionó la segunda propuesta como referencia para el desarrollo del prototipo.

---

### Imagen 3 — Contador amigo: primera iteración

**Prompt utilizado:**

> Diseñar una pantalla específica del asistente conversacional “Contador amigo” para Nalia Fintech, manteniendo exactamente la misma identidad visual del dashboard previamente creado: interfaz blanca y luminosa, violetas suaves, azul, pequeños acentos pastel, tarjetas redondeadas, diseño minimalista y sensación de tranquilidad. El asistente debe estar representado por el mismo concepto de mascota felina minimalista utilizado en la interfaz de Nalia: un pequeño gato ilustrado con líneas violetas, simpático, moderno y simple. No utilizar una persona ni un contador humano.
>
> La pantalla debe incluir el título “Preguntale a tu contador amigo” y un chat donde el usuario escriba: “¿Qué pasa si compro un pantalón de $180.000 en 10 cuotas?” El asistente debe mostrar una simulación clara con: importe total $180.000, 10 cuotas y valor estimado de $18.000 por cuota. Debe indicar que necesita conocer el mes en que comenzará la primera cuota para calcular su impacto real. Mostrar claramente una etiqueta visual “SIMULACIÓN” y el mensaje “Este movimiento todavía no fue registrado”. Incorporar botones o acciones como “Modificar simulación” y “Descartar”.
>
> Mantener visible la navegación lateral de Nalia con las secciones Inicio, Movimientos, Tarjetas, Objetivos y Contador amigo, dejando seleccionada esta última. La interfaz debe transmitir acompañamiento, organización y tranquilidad. No debe parecer una plataforma de inversiones ni un home banking tradicional. No incluir recomendaciones de compra, inversiones, gráficos bursátiles, criptomonedas, credenciales bancarias ni datos personales reales. Formato horizontal de aplicación web de escritorio, UI/UX fintech moderna, limpia, accesible y coherente visualmente con el dashboard de Nalia Fintech.

La primera generación presentó una inconsistencia en la representación de la mascota. Por ese motivo se realizó una segunda iteración.

---

### Imagen 4 — Contador amigo: segunda iteración

**Prompt corregido utilizado:**

> Diseñar una pantalla específica del asistente conversacional “Contador amigo” de Nalia Fintech, manteniendo la misma identidad visual del dashboard de referencia: interfaz blanca y luminosa, violetas suaves, azul, pequeños acentos pastel, tarjetas redondeadas, diseño minimalista, moderno y sensación de tranquilidad.
>
> IMPORTANTE: mantener el mismo estilo de mascota felina que aparece en el dashboard de Nalia Fintech. El asistente debe ser un gato blanco minimalista dibujado con líneas violetas finas, de cuerpo simple, expresión tranquila y amigable, similar al gato sentado frente a la notebook que aparece en la sección “Contador amigo” del dashboard. No utilizar un gato 3D, una cabeza de gato dentro de un círculo, un emoji, una mascota infantil ni una persona humana.
>
> La mascota debe aparecer de manera sutil acompañando la conversación, manteniendo una estética elegante y coherente con una aplicación fintech para adultos.
>
> Mantener visible la navegación lateral con: Inicio, Movimientos, Tarjetas, Objetivos y Contador amigo, dejando seleccionada la sección “Contador amigo”.
>
> En el área principal mostrar el título “Preguntale a tu contador amigo”.
>
> Mostrar una conversación donde el usuario pregunta: “¿Qué pasa si compro un pantalón de $180.000 en 10 cuotas?”
>
> El asistente debe responder mostrando una tarjeta claramente identificada como “SIMULACIÓN”, con:
>
> - Importe total: $180.000
> - Cantidad de cuotas: 10
> - Valor estimado por cuota: $18.000
>
> Incluir el mensaje: “Este movimiento todavía no fue registrado.”
>
> Como falta información para realizar una proyección completa, el asistente debe preguntar: “¿En qué mes comenzará la primera cuota?”
>
> Incluir las acciones “Modificar simulación” y “Descartar”.
>
> La IA no debe recomendar realizar o evitar la compra. Solo debe presentar información objetiva y solicitar los datos faltantes.
>
> Mantener abundante espacio en blanco y evitar sobrecarga visual. La pantalla debe sentirse como una continuación directa del dashboard original de Nalia Fintech y no como otra aplicación diferente.
>
> Formato horizontal 16:9, interfaz web desktop, UI/UX fintech moderna, limpia, accesible y profesional.
>
> Evitar: personas humanas, contador humano, gato realista, gato 3D, avatar circular de gato, estética infantil, gráficos bursátiles, criptomonedas, inversiones, billetes, monedas, exceso de información, colores agresivos, recomendaciones financieras y datos personales reales.

La segunda iteración fue seleccionada por mantener mayor coherencia con la identidad visual de Nalia.

---

## Producción de audio

Se produjeron dos audios para acompañar la experiencia de uso de Nalia Fintech.

**Herramienta de generación:** ElevenLabs  
**Procesamiento posterior:** Adobe Enhance

Los audios fueron procesados posteriormente para mejorar la claridad de la voz.

La voz específica y los valores técnicos utilizados durante la generación original en ElevenLabs no fueron registrados. Para mantener una documentación transparente, no se incorporan valores estimados.

Los siguientes prompts fueron reconstruidos a partir de las indicaciones de voz utilizadas durante la producción, ya que no se conservó el texto literal ingresado originalmente en la plataforma.

### Audio 1 — Bienvenida general

**Objetivo:** acompañar el primer ingreso del usuario a Nalia y presentar la experiencia de manera cercana.

**Prompt de voz utilizado (reconstruido):**

> Generar una voz femenina joven-adulta, cálida, cercana y tranquila, en español rioplatense neutro. Mantener un ritmo pausado pero natural, con tono amable y profesional. Evitar una entonación excesivamente comercial, robótica o infantil. La voz debe transmitir confianza, organización y acompañamiento, de acuerdo con la identidad de Nalia Fintech. Leer el mensaje de bienvenida de forma clara y relajada.

---

### Audio 2 — Contador amigo

**Objetivo:** acompañar la primera interacción del usuario con el asistente conversacional.

**Prompt de voz utilizado (reconstruido):**

> Generar una voz femenina joven-adulta, cálida, cercana y tranquila, en español rioplatense neutro. Utilizar un tono conversacional y amigable, como un asistente que acompaña al usuario a comprender su información financiera. Mantener un ritmo natural, pronunciación clara y una actitud serena. Evitar sonar como una asesora financiera, una publicidad o una voz robótica. Leer el mensaje de presentación del Contador amigo transmitiendo cercanía y confianza.

Los archivos finales de ambos audios se encuentran incluidos en este repositorio.

---

## Herramientas utilizadas

- ChatGPT — co-creación, desarrollo de prompts, pruebas y generación visual.
- ElevenLabs — generación de voz.
- Adobe Enhance — mejora y procesamiento de audio.
- Lovable — desarrollo y publicación del prototipo funcional.
- GitHub — documentación y publicación de los activos del proyecto.

---

## Auditoría ética y responsabilidad

Durante el desarrollo se consideraron riesgos relacionados con el uso de IA en un contexto financiero.

| Riesgo | Medida de mitigación |
|---|---|
| La IA inventa información faltante | Solicitar el dato al usuario antes de continuar |
| Registro incorrecto de una operación | Vista previa y confirmación antes de guardar |
| Confusión entre simulación y dato real | Identificación explícita de las simulaciones |
| Recomendaciones financieras indebidas | El sistema organiza y calcula, pero no recomienda comprar o vender |
| Exposición de información sensible | Uso exclusivo de datos ficticios durante el desarrollo |
| Lenguaje culpabilizante | Uso de comunicación neutral, clara y tranquila |
| Confusión con asesoramiento profesional | Aclaración de que Nalia no sustituye asesoramiento profesional |

---

## Consideraciones sobre los activos generados

Todos los datos financieros presentes en las imágenes, pruebas y demostraciones son ficticios.

No se utilizaron datos financieros personales reales para generar los activos.

Los materiales visuales fueron generados específicamente para Nalia Fintech mediante ChatGPT.

Los audios fueron generados mediante ElevenLabs y posteriormente procesados con Adobe Enhance.

Los términos, permisos y condiciones aplicables a los contenidos generados dependen de las condiciones de uso vigentes de cada herramienta utilizada.

---

## Prototipo funcional

El prototipo fue desarrollado y publicado mediante Lovable.

**URL pública:**

https://nalia-lovely-start.lovable.app

### Acceso de demostración

**Usuario:** demo@nalia.test  
**Contraseña:** NaliaDemo123!

La cuenta contiene únicamente información ficticia preparada para la evaluación académica.

---

## Datos de demostración

El perfil ficticio utilizado en el prototipo corresponde a Sofía.

Algunos datos incluidos son:

- Salario: $1.850.000
- Alquiler: $420.000
- Supermercado: $86.500
- Gimnasio: $35.000
- Streaming: $18.500
- Dos tarjetas de demostración.
- Tres inversiones ficticias.
- Objetivo Vacaciones: $450.000 de $1.000.000.
- Fondo de emergencia: $620.000 de $1.500.000.

---

## Limitaciones del prototipo

- Todos los datos son ficticios.
- No existen conexiones con bancos reales.
- Nalia no proporciona asesoramiento financiero profesional.
- El dictado por voz depende de la compatibilidad del navegador y de los permisos del micrófono.
- Si la entrada por voz no está disponible, el usuario puede utilizar texto.
- Las notificaciones corresponden al prototipo y se muestran dentro de la aplicación.
- No se envían notificaciones del sistema operativo ni correos electrónicos.
- La cuenta demo es compartida, por lo que los cambios realizados durante una evaluación pueden permanecer visibles para el siguiente acceso.

---

## Activos incluidos en el repositorio

El repositorio público contiene:

- Documentación completa del proyecto.
- Imágenes generadas durante la producción multimodal.
- Evidencias de las pruebas funcionales.
- Audio final de bienvenida.
- Audio final del Contador amigo.
- Documento final del proyecto.

---

## Conclusión

Nalia Fintech integra Inteligencia Artificial Generativa dentro de una experiencia de organización financiera personal centrada en la claridad, el control del usuario y la transparencia.

El proyecto permitió aplicar técnicas de co-creación con IA, diseño de prompts, producción multimodal, evaluación de resultados, iteración, auditoría ética y desarrollo de un prototipo funcional.

La IA no reemplaza la decisión del usuario: interpreta, organiza y ayuda a comprender la información disponible, mientras que el usuario conserva siempre el control sobre las acciones que modifican sus datos.
