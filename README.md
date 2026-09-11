# Implementación de un CRUD con Rails y RSpec

El objetivo es desarrollar una aplicación de gestión de productos para un e-commerce utilizando Ruby on Rails y RSpec. La aplicación debe permitir crear, leer, actualizar y eliminar productos. Los productos tienen atributos como nombre, precio, stock y categoría. La aplicación debe validar que los nombres de productos no sean duplicados y que los precios no sean negativos. Además, debe manejar errores de forma adecuada y mantener un registro de auditoría de las operaciones realizadas.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Ruby on Rails |
| **Nivel** | junior-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 8 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Un IDE o editor de código.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Verifica que el proyecto arranca sin errores.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Creación de la estructura básica

**Objetivo:** Configurar el entorno de desarrollo y crear la estructura básica de la aplicación.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Configurar el entorno de desarrollo para Ruby on Rails.
- Crear una nueva aplicación Rails.
- Definir el modelo de producto con los atributos necesarios.
- Crear las migraciones para la base de datos.

**Entregable:** Aplicación Rails con modelo de producto y migraciones creadas.

<details>
<summary>Pistas de conocimiento</summary>

- Considera la estructura de directorios y archivos típicos de una aplicación Rails.
- Recuerda las convenciones de nomenclatura para modelos y migraciones.

</details>

### Fase 2: Implementación de las operaciones CRUD

**Objetivo:** Implementar las operaciones de creación, lectura, actualización y eliminación de productos.

**Tiempo estimado:** 3 horas

**Instrucciones:**

- Crear los controladores necesarios para manejar las operaciones CRUD.
- Implementar las vistas para mostrar y editar productos.
- Asegurar que las validaciones de nombre y precio se apliquen correctamente.

**Entregable:** Operaciones CRUD funcionales para productos con validaciones aplicadas.

<details>
<summary>Pistas de conocimiento</summary>

- Recuerda usar los métodos adecuados en los controladores para cada operación CRUD.
- Piensa en cómo mostrar los errores de validación en las vistas.

</details>

### Fase 3: Pruebas con RSpec

**Objetivo:** Escribir pruebas unitarias y de integración para las operaciones CRUD utilizando RSpec.

**Tiempo estimado:** 3 horas

**Instrucciones:**

- Configurar RSpec en la aplicación.
- Escribir pruebas unitarias para el modelo de producto.
- Escribir pruebas de integración para los controladores.

**Entregable:** Pruebas unitarias y de integración funcionales para las operaciones CRUD.

<details>
<summary>Pistas de conocimiento</summary>

- Recuerda usar las convenciones de RSpec para escribir pruebas.
- Piensa en cómo probar las validaciones y los errores de las operaciones CRUD.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es Ruby on Rails y cuál es su propósito en el desarrollo web?
- **paraQueSirve**: ¿Para qué sirven las pruebas unitarias y de integración en el desarrollo de aplicaciones Rails?
- **comoSeUsa**: ¿Cómo se implementan las operaciones CRUD en una aplicación Rails?
- **erroresComunes**: ¿Cuáles son los errores comunes al implementar validaciones en Rails y cómo se pueden manejar?
- **queDecisionesImplica**: ¿Qué decisiones de diseño implica la implementación de un CRUD con Rails y RSpec?

## Criterios de Evaluacion

- Configuración correcta del entorno de desarrollo para Rails.
- Implementación funcional de las operaciones CRUD con validaciones aplicadas.
- Escrituras de pruebas unitarias y de integración utilizando RSpec.

## Como trabajar con un asistente de IA

- **AGENTS.md** — instrucciones nativas del repo (Cursor, Codex, Copilot, Gemini, Claude Code). Abrí el proyecto y el agente las carga solo.
- **PROMPT_MEJORA.md** — el mismo prompt, para copiar y pegar en un chat (claude.ai, ChatGPT, etc.).

---

*Reto generado automaticamente por Challenge Generator - Pragma*
