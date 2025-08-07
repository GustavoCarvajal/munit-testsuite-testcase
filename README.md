 Pruebas MUnit para MuleSoft
Este repositorio incluye un conjunto de pruebas MUnit diseñadas para validar la funcionalidad de los flujos desarrollados en la aplicación MuleSoft. Las pruebas están orientadas a garantizar la calidad, confiabilidad y comportamiento esperado de cada componente del proyecto.

🔍 Objetivos de las pruebas MUnit
Validar los flujos de integración bajo distintas condiciones de entrada.

Simular respuestas externas mediante mocks de conectores y subflujos.

Detectar errores tempranos durante el desarrollo y cambios futuros.

Asegurar que las transformaciones de datos (DataWeave) funcionen correctamente.

Verificar el manejo adecuado de errores y excepciones.

⚙️ Estructura del módulo de pruebas
Cada flujo principal tiene al menos una prueba asociada.

Se incluyen pruebas positivas (casos exitosos) y negativas (errores esperados).

Uso de mock, when, assert-that, y verify-call para evaluar el comportamiento.

Los tests están organizados en el archivo `src/test/munit
