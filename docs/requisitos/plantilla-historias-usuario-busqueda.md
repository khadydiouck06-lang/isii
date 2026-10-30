# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Fecha | [30/10/2026] |
| Versión | [1.0] |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Como [rol], quiero [capacidad amplia], para [beneficio].

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

[Justificación de los resultados útiles que separa la división.]

## US-01

**Título:** buscar mediante una palabra o frase

Como usuario, quiero poder buscar recetas mediante palabras clave o frases en un campo de búsqueda dedicado, para encontrar recetas que contengan esa palabra o frase .

**Fuentes:** UR-08; UC-21; FR-085; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dada una búsqueda por palabra clave  , cuando se ejecute la bsuqueda  , entonces apareceran las palabras que contengan la palabara e en titulo o descripcion .
- **CA-02.** Dada una busqueda por frase, cuando se ejecute la busqueda , entonces se mosraran las recetas q contengan la frase en el mismo orden
- **CA-03.**Dada una busqueda por frase, cuando se ejecute la busqueda y no existen q contengan la frase en el mismo orden, entonces el sistema indicara que no hay resultados de busqueda 
## US-02

**Título:** buscar por ingredientes incluidos

Como usuario, quiero  buscar recetas por ingredientes seleccionados, mostrando solo las que los contengan, para encontrar recetas que contengan esos ingredientes.

**Fuentes:** UR-08; UC-21; FR-086; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado que una persona selecciona un ingrediente que desea encontrar , cuando ejecute la búsqueda , entonces deben aparecer solo recetas que contengan ese ingrediente .
  
- **CA-02.** Dado que una persona selecciona varios ingredientes que desea encontrar , cuando ejecute la búsqueda , entonces deben aparecer solo recetas que contengan todos esos ingredientes .
- 
- **CA-03.** Dado que una persona selecciona los ingredientes que desea encontrar , cuando ejecute la búsqueda y  si no existen recetas que contengan todos esos ingredientes , entonces el sistema indicara que no hay resultados de busqueda .

## US-03

**Título:** Excluir ingredientes

Como usuario, quiero excluir ingredientes de la búsqueda, para ver recetas que no contengan eso ingredientes.

**Fuentes:** UR-08; UC-21; FR-087; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado que una persona selecciona un ingredientes que desea excluir, cuando ejecute la búsqueda, entonces solo pueden aparecer recetas que no contengan el  ingrediente seleccionado.
- **CA-02.** Dado que una persona selecciona varios  ingredientes que desea excluir, cuando ejecute la búsqueda, entonces  entonces solo pueden aparecer recetas que no contengan ninguno de los ingredientes seleccionados.
- **CA-03.** Dado que una persona selecciona los ingredientes que desea excluir, cuando ejecute la búsqueda y no existen recetas que no contengan ninguno de los ingredientes seleccionados , entonces el sistema indicara que no hay resultados de busqueda  .

## Revisión INVEST

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio | Pregunta de revisión | Aplicado | Cumple | Justificación |
| --- | --- | --- | --- | --- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Negociable | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Valiosa | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Estimable | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Pequeña | ¿Se centra cada historia en una única capacidad de alcance manejable? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Comprobable | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |

## Dudas pendientes

[Cuestiones pendientes de aclaración. Si no quedan cuestiones, indicar «Ninguna».]
