# Informe — Exposición-demostración MDD (UML → Código)

Documento que evidencia el ciclo completo de **Desarrollo Dirigido por Modelos (MDD)** aplicado al PFC **MundiPets**, usando la herramienta CASE **Visual Paradigm** para generar código C# a partir de un diagrama de clases UML.

## ¿De qué trata?

El documento demuestra, de principio a fin, cómo se pasa de un modelo UML a código fuente funcional sobre un subsistema real de MundiPets: la **gestión del perfil de mascota y validación de información médica**.

## Contenido

- **Marco teórico:** explica los fundamentos de MDE, MDA (niveles CIM, PIM, PSM), MDD, las transformaciones modelo-a-modelo y modelo-a-texto, los perfiles UML y la ingeniería de ida y vuelta (round-trip).

- **Justificación de la herramienta:** argumenta por qué se eligió Visual Paradigm frente a alternativas como Enterprise Architect, considerando cobertura de lenguajes, plantillas editables y licencia.

- **Descripción del subsistema:** delimita el módulo modelado, sus actores, requisitos funcionales y alcance.

- **Modelo UML de origen:** presenta el diagrama de clases (8 clases del dominio y 2 enumeraciones con el estereotipo «Entity») y el perfil UML con estereotipos y valores etiquetados.

- **Configuración y generación:** documenta cómo se configuró el Instant Generator, las plantillas Apache Velocity utilizadas, y el proceso de generación del código C#.

- **Verificación:** comprueba la correspondencia entre el modelo y el código generado, con una tabla de trazabilidad y las limitaciones detectadas del generador.

- **Cierre del ciclo (roundtrip):** evidencia que un cambio en el modelo (agregar el atributo `peso` a la clase Mascota) se refleja en el código al regenerar.

- **Reparto del trabajo y conclusiones.**

- **Anexos:** estructura del repositorio, tabla de mapeo completa modelo→código, los códigos completos de las 10 clases generadas e instrucciones de reproducibilidad.

## Sistema de aplicación

**MundiPets** — plataforma orientada a centralizar perfiles de mascotas y apoyar procesos de adopción y cruza responsable, correspondiente al Proyecto Fin de Curso del equipo.

## Herramientas utilizadas

- **Visual Paradigm 17.3** — modelado UML y generación de código (Instant Generator)
- **C#** — lenguaje objetivo del código generado
- **Visual Studio 2022** — compilación y ejecución
- **LaTeX** — elaboración del documento

## Equipo

- Fuertes Arraes Edson Daniel — Líder e integrador (modelado UML y generación de código)
- Cedeño Avila Winston Damian — Marco teórico, descripción del subsistema y conclusiones
- Cedeño Coronado Wilson Lizandro — Justificación de la herramienta MDD
