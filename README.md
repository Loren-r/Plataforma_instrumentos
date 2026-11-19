# Plataforma de Instrumentos de Evaluación

## Problemática
En muchos procesos de evaluación y certificación de competencias laborales, los perfiles ocupacionales y sus instrumentos se gestionan en varias planillas Excel que se mantienen por separado. Un flujo frecuente es el siguiente:

1. El área de instrumentos levanta el perfil y lo arma en una matriz Excel.
2. Prepara otra planilla para que el área de TI cargue el perfil y sus instrumentos en el sistema.
3. Genera los PDF de los instrumentos para su aplicación.
4. Entrega una copia de la matriz al área de operaciones, que aplica los instrumentos en papel y luego digita los resultados en el sistema.

Por ejemplo, si una pregunta dice "profesor de lenguaje" cuando debía decir "profesor de matemáticas", hay que corregirla en la matriz original, en la copia de operaciones, en la planilla de carga de TI y en el PDF, y además pedir a TI el cambio en el sistema.

Cuando el proceso funciona así, se genera duplicidad de información, falta de trazabilidad, errores de digitación y mucho tiempo perdido por falta de automatización.

## Solución propuesta
Una plataforma web que permita:

1. Crear y editar perfiles e instrumentos en un solo lugar, reemplazando las matrices Excel.
2. Mantener un banco de preguntas reutilizable, indicando en qué perfiles e instrumentos se usa cada pregunta.
3. Asociar a cada pregunta su brecha: el conocimiento que queda descendido si se responde mal y sus posibles consecuencias.
4. Aplicar las pruebas en línea.
5. Obtener los resultados al momento, con el detalle de los conocimientos descendidos, y descargarlos.
6. Gestionar roles con distintos permisos (por ejemplo, operaciones solo revisa y el área de instrumentos edita), sin depender de TI para cada cambio.

## Usuarios
- **Área de instrumentos:** crea y edita perfiles, preguntas e instrumentos.
- **Área de aplicación (operaciones):** aplica los instrumentos y revisa resultados.
- **Área de servicio al cliente:** consulta la información de perfiles y resultados.

## Alcance de la primera versión
- Crear, editar y consultar perfiles con sus contenidos.
- Banco de preguntas con su brecha asociada.
- Crear instrumentos para un perfil, partiendo por la prueba de conocimientos teóricos (PCT).
- Aplicar la PCT en línea y mostrar el resultado con los conocimientos descendidos.

**Fuera de esta versión:** roles y permisos, instrumentos prácticos (como la pauta de observación en terreno) y descarga de resultados. Se irán incorporando para avanzar hacia la automatización completa del proceso.