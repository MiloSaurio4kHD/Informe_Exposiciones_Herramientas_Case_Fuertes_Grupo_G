# Informe Individual — Exposiciones de Herramientas CASE (MDD)

**Universidad Técnica Estatal de Quevedo (UTEQ)**
Facultad de Ciencias de la Computación y Diseño Digital — Carrera de Ingeniería en Software

| | |
|---|---|
| **Materia** | Ingeniería en Requerimientos |
| **Docente** | Ing. Guerrero Ulloa Gleiston Cicerón, PhD. |
| **Estudiante** | Fuertes Arraes Edson Daniel — CI: 0929115087 — efuertesa2@uteq.edu.ec |
| **Curso** | Cuarto Semestre Ingeniería en Software "B" |
| **PFC** | MundiPets |
| **Periodo** | 2026 – 2027 PPA |

---

## Descripción

Informe **individual** que documenta lo observado durante las exposiciones de los distintos equipos sobre **herramientas CASE aplicadas al Desarrollo Dirigido por Modelos (MDD)**, es decir, la generación de código fuente a partir de diagramas UML.

Cada equipo presentó una herramienta distinta y demostró en vivo, sobre el proyecto **MundiPets**, el ciclo de modelar un diagrama de clases y obtener a partir de él el esqueleto del código.

## Contenido del informe

| Sección | Contenido |
|---|---|
| 1 | Introducción |
| 2 | Grupo A — Umbrello |
| 3 | Grupo B — StarUML |
| 4 | Grupo E — Modelio |
| 5 | Grupo H — BOUML |
| 6 | Grupo D — Power Designer |
| 7 | Cuadro comparativo de las herramientas |
| 8 | Conclusiones |

## Herramientas documentadas

| Grupo | Herramienta | Expositores | Lenguaje demostrado |
|---|---|---|---|
| A | Umbrello | Esther Muñoz, Frixon Morán, Ángelo Zambrano | C# (Visual Studio) |
| B | StarUML | Génesis Gutiérrez, Mayra Córdova, Anderson Naranjo | C# (Visual Studio 2022) |
| E | Modelio | Nieves Jimmy, Morales Gary | Java (IntelliJ IDEA) |
| H | BOUML | Chavarría, Mendoza, Sánchez Cornejo | C++ |
| D | Power Designer | Contreras Kevin | SQL (SQL Server) |

## Estructura del repositorio

```
.
├── README.md
├── informe_exposiciones.tex     # Documento fuente LaTeX
├── informe_exposiciones.pdf     # Documento compilado
└── figuras/
    └── logo_uteq.png            # Logo institucional (requerido por la portada)
```

## Compilación

El documento usa la clase `IEEEtran` (formato *journal*, una columna) y no requiere bibliografía externa.

```bash
pdflatex informe_exposiciones.tex
pdflatex informe_exposiciones.tex   # segunda pasada: índice y lista de tablas
```

### Requisitos

- Distribución LaTeX (TeX Live, MiKTeX o Overleaf)
- Paquetes: `IEEEtran`, `babel` (spanish), `csquotes`, `booktabs`, `tabularx`, `array`, `multirow`, `longtable`, `graphicx`, `float`, `xcolor`, `geometry`, `fancyhdr`, `parskip`, `enumitem`, `amssymb`, `titlesec`, `caption`, `hyperref`
- El archivo `figuras/logo_uteq.png` debe existir para que compile la portada

## Notas

- El informe es de carácter **individual**; recoge únicamente las observaciones del autor sobre las exposiciones de los demás equipos.
- Los procedimientos descritos corresponden a lo demostrado en vivo por cada grupo, no a pruebas realizadas por el autor.
