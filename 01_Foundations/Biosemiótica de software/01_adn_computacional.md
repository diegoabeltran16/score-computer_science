# 🧬 ADN Computacional

## 🧬 Propósito del modelo biosemiótico
Representar el software como un sistema compuesto de unidades mínimas (genes, codones, células) que pueden activarse, mutar, replicarse y evolucionar, siguiendo principios inspirados en la biología molecular.

Este enfoque permite diseñar software como si fuera un organismo: con capacidad de expresión condicional, evolución simbólica y autoorganización funcional. (Biología para entender y diseñar software)

Estas bases se emparejan siempre de forma complementaria (A-T, G-C), y su organización estructural permite:
- Codificar instrucciones (genes)
- Replicarse con fidelidad
- Activarse selectivamente (expresión génica)
- Mutar y evolucionar

---

## 💻 Analogía en ciencias de la computación

En computación, el ADN se puede comparar con el **código fuente** y su estructura modular, pero esta analogía puede profundizarse para abarcar matices esenciales que reflejan procesos biológicos avanzados.

### 1. Analogía Básica

| Biología 🧬         | Computación 💻                               | Comentario                                      |
|--------------------|----------------------------------------------|-------------------------------------------------|
| Gen                | Función o clase                              | Unidad de comportamiento o estructura de datos. |
| Secuencia genética | Código fuente                                | Instrucciones completas que definen el sistema. |
| Cromosoma          | Módulo o archivo                             | Agrupa funciones/clases relacionadas.           |
| Genoma             | Repositorio completo                         | Conjunto total de código, tests, docs y config. |
| Mutación           | Commit o cambio de código                    | Introduce variaciones que pueden mejorar o dañar. |
| Replicación        | Clonación del repositorio / branching        | Copia para experimentación y evolución.         |
| Expresión génica   | Ejecución del software                       | Solo se “expresa” el código relevante según contexto. |
| Célula             | MVP autocontenido                            | Unidad mínima funcional con lógica, datos y flujo adaptable. |
| Organo             | Servicio especializado                       | Módulo que cumple una función clara dentro del sistema. |
| Organismo          | Ecosistema de repositorios                   | Conjunto coordinado de células (MVPs) que interactúan y evolucionan juntos. |

---

## 🧬 Traducción por codones (modelo biocomputacional)

Inspirado en la genética real, se utiliza una secuencia de tripletes (codones) para construir instrucciones funcionales. Este flujo incluye:

- **Codón de inicio**: `ATG`, indica el comienzo de la traducción (activación de una función).
- **Codones funcionales**: cada triplete representa una operación específica (ej: `AAA`, `GGG`, `CTT`).
- **Codón de parada**: `TAA`, `TAG`, o `TGA`, indica el final del bloque funcional.
- **Complementariedad**: se puede generar la hebra complementaria para verificar integridad o simular reparación (ej: `ATG` ↔ `TAC`).
- **Intrones**: regiones no codificantes que se omiten en la ejecución (ej: `XXX`, `NNN`).

### Ejemplo simbólico
```
Secuencia:    ATG AAA TTT GGG CCC TAA
Traducción:   [Inicio] → [Operación1] → [Condición] → [Generación] → [Cierre] → [Parada]
```

---

## ✅ ¿Por qué este modelo es útil y potente?

1. **Estructura de codones**: Simula cómo se codifican y traducen instrucciones en biología.
2. **Inicio y fin claros**: Como los genes, cada bloque funcional tiene delimitadores reconocibles.
3. **Modularidad evolutiva**: Permite mutaciones y selección basada en “fitness” computacional (outputs).
4. **Expansión pedagógica**: Facilita la creación de pseudolenguajes genéticos para enseñar programación.
5. **Simulación de mutaciones**: Cambiar un triplete puede alterar completamente el comportamiento funcional.
6. **Diseño de sistemas autoevolutivos**: Este enfoque permite prototipar una IA que evoluciona simbólicamente, combinando lógica, mutación y expresión condicional.
7. **64 operaciones posibles**: La estructura 4³ = 64 codones da pie a un conjunto expresivo de instrucciones (similar a un instruction set de bajo nivel).

Este enfoque biosemiótico combina **estructura, simbolismo y ejecución**, permitiendo que el software se piense como un organismo capaz de nacer, mutar, expresarse y evolucionar.

---

## 🔗 Relaciones con otras capas

- [Epigenética computacional](04_Cross_Cutting/Biosemiótica de software/01_epigenetica_computacional.md): cómo se regulan las funciones sin modificar el ADN.

- [Git y reproducción celular](05_Methodology/Biosemiótica de software/01_git_y_reproduccion_celular.md): cómo se hereda, muta y reproduce el código fuente.

