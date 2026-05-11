# CarrenoRangel-post1-u11

Refactorizacion con SOLID (SRP, DIP), DAO/DTO, Factory y @RestControllerAdvice.

## Ejecutar
mvn spring-boot:run

## Arquitectura (texto)
- Controller -> Service (interface) -> Repository -> Entity
- Controller usa DTOs (request/response)
- ProductoFactory convierte entre DTO y Entity
- GlobalExceptionHandler centraliza errores

## Evidencias
Coloca las capturas en img/:
- img/checkpoint1-compile.png
- img/checkpoint2-post.png
- img/checkpoint3-404-400.png
