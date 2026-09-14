# Nalia Fintech

### Proyecto Final — Introducción a la Inteligencia Artificial
**Alumna:** Abril Valladares  
**Año:** 2026

## Sobre el proyecto

Nalia Fintech es una aplicación web de organización financiera personal asistida por Inteligencia Artificial Generativa.

El proyecto busca facilitar la comprensión y organización de las finanzas personales mediante una experiencia simple y conversacional. La IA permite interpretar instrucciones escritas o por voz, registrar movimientos, realizar simulaciones y responder consultas utilizando los datos disponibles dentro de la aplicación.

## Objetivos

- Facilitar el registro y consulta de movimientos financieros.
- Permitir cargas mediante lenguaje natural.
- Realizar simulaciones sin modificar los datos reales.
- Mantener contexto dentro de una conversación.
- Solicitar información faltante antes de registrar un movimiento.
- Presentar información financiera de manera clara y accesible.

## Sistema de IA

El proyecto fue desarrollado mediante un Sistema de IA compuesto por:

- Instrucciones Base (System Prompt).
- Prompt Maestro.
- Prompts específicos para generación de imágenes.
- Prompts específicos para generación de audio.
- Reglas para consultas, simulaciones y registro de movimientos.

Una regla fundamental del sistema es:

**INTERPRETAR → MOSTRAR → CONFIRMAR → REGISTRAR**

La IA no debe inventar información financiera faltante ni registrar operaciones sin confirmación del usuario.

## Pruebas realizadas

El sistema fue probado en diferentes situaciones:

**Carga completa:**  
“Zara $450.000 BBVA, 3 cuotas, entra en septiembre.”

Nalia interpreta la compra, calcula las cuotas y muestra una vista previa antes de registrarla.

**Información insuficiente:**  
“Zara $450.000 BBVA en 3 cuotas.”

Nalia detecta que falta información y pregunta en qué mes comienza la primera cuota.

**Simulación:**  
“¿Qué pasa si compro un pantalón de $180.000 en 10 cuotas?”

El sistema calcula el impacto de la compra sin registrarla y mantiene el contexto de la conversación.

**Consulta:**  
“¿Cuánto gasté este mes?”

Nalia responde utilizando únicamente los movimientos registrados.

## Producción multimodal

Como parte del proyecto se desarrollaron activos visuales y sonoros mediante herramientas de Inteligencia Artificial.

### Imágenes

Se generaron diferentes propuestas para:

- Identidad visual y logo de Nalia.
- Dashboard de la aplicación.
- Personaje “Contador amigo”.

Las iteraciones permitieron comparar resultados y corregir inconsistencias visuales antes de definir la propuesta final.

### Audio

Se generaron dos piezas de audio:

1. Audio de bienvenida de Nalia.
2. Audio del “Contador amigo”.

Los audios fueron generados mediante ElevenLabs y posteriormente procesados con Adobe Enhance para mejorar su claridad.

Los archivos de audio se encuentran disponibles en este repositorio y también están integrados en el prototipo funcional.

## Herramientas utilizadas

- ChatGPT — co-creación, definición del sistema de IA, prompts y generación visual.
- Lovable — desarrollo y publicación del prototipo funcional.
- ElevenLabs — generación de voz.
- Adobe Enhance — procesamiento y mejora del audio.
- GitHub — documentación y publicación del Proyecto Final.

## Auditoría ética y responsabilidad

Durante el desarrollo se analizaron posibles riesgos asociados al uso de IA.

Entre las medidas implementadas:

- No utilizar información bancaria real.
- Trabajar únicamente con datos ficticios para la demostración.
- Evitar que la IA invente información financiera faltante.
- Solicitar confirmación antes de registrar movimientos.
- Diferenciar claramente las simulaciones de las operaciones registradas.
- Evitar presentar a Nalia como reemplazo de asesoramiento financiero profesional.
- Revisar manualmente los activos visuales y sonoros generados mediante IA.

## Limitaciones

Este proyecto es un prototipo académico.

- No existen conexiones con bancos reales.
- Todos los datos utilizados son ficticios.
- Nalia no brinda asesoramiento financiero profesional.
- El reconocimiento de voz depende del navegador y de los permisos del micrófono.
- Las notificaciones corresponden a una demostración dentro de la aplicación.

## Prototipo funcional

El prototipo público de Nalia Fintech puede probarse en:

https://nalia-lovely-start.lovable.app

### Acceso para evaluación

**Usuario:** demo@nalia.test  
**Contraseña:** NaliaDemo123!

La cuenta utiliza un perfil ficticio creado exclusivamente para la evaluación académica.

> Importante: la cuenta demo es compartida. Los movimientos registrados durante una prueba pueden permanecer visibles para el siguiente usuario.

## Documentación completa

La documentación completa del proceso incluye la definición del problema, objetivos, proceso de co-creación, Instrucciones Base, Prompt Maestro, pruebas, prompts utilizados, producción multimodal, auditoría ética, validación y limitaciones del prototipo.

## Conclusión

Nalia Fintech permitió aplicar de forma integrada los contenidos trabajados durante el curso, combinando diseño de prompts, Inteligencia Artificial Generativa, producción multimodal, evaluación de resultados, criterios éticos y desarrollo de un prototipo funcional.

El resultado es una demostración navegable que permite comprobar en la práctica el funcionamiento del sistema de IA diseñado para el proyecto.
