<div align="center">

# Marco histórico con Perplexity

**Ruta guiada de pasos para construir el marco histórico de una tesina de licenciatura, por área de conocimiento.**

![Versión](https://img.shields.io/badge/versión-2.1-14343F?style=flat-square)
![Estado](https://img.shields.io/badge/estado-en%20uso-1E6F7A?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-una%20sola%20página-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-sin%20dependencias%20de%20compilación-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-listo-222222?style=flat-square&logo=githubpages&logoColor=white)
![Perplexity](https://img.shields.io/badge/investigación-Perplexity-20808D?style=flat-square&logo=perplexity&logoColor=white)
![APA 7](https://img.shields.io/badge/citas-APA%207-9A6B1E?style=flat-square)
![Idioma](https://img.shields.io/badge/idioma-español%20(MX)-5F5C54?style=flat-square)

[**Abrir la herramienta**](./index.html) · [**Guía de uso**](./guia.html) · [Estructura por área](#estructura-por-área) · [Metadatos](#control-de-metadatos)

</div>

---

## Tabla de contenido

- [Qué es](#qué-es)
- [Para quién es](#para-quién-es)
- [La ruta de pasos](#la-ruta-de-pasos)
- [Estructura por área](#estructura-por-área)
- [Subáreas](#subáreas)
- [Cómo se usa](#cómo-se-usa)
- [Publicación en GitHub Pages](#publicación-en-github-pages)
- [Archivos del repositorio](#archivos-del-repositorio)
- [Privacidad](#privacidad)
- [Advertencia académica](#advertencia-académica)
- [Historial de versiones](#historial-de-versiones)
- [Control de metadatos](#control-de-metadatos)

---

## Qué es

Es una página web que acompaña al alumno en la redacción del **Capítulo I, marco histórico**, de su tesina. El alumno sube su anteproyecto y la herramienta:

1. Lee el tema, la pregunta, los objetivos y la delimitación.
2. Sugiere el área de la tesina (el alumno siempre puede corregirla).
3. Genera, paso por paso, los **prompts para Perplexity** con los datos del alumno ya incluidos.
4. Indica en cada paso **qué hacer**, **qué tipo de fuentes usar** y **cuándo se da por terminado**.

> [!NOTE]
> La herramienta **no redacta la tesina por sí misma**. Prepara las instrucciones para buscar fuentes reales con Perplexity y organiza el trabajo en un orden fijo.

## Para quién es

| Perfil | Uso |
|---|---|
| **Alumno** | Sigue la ruta de pasos y copia cada prompt en Perplexity. |
| **Asesor / catedrático** | Revisa el avance por pasos y usa los criterios de "Terminaste este paso cuando…" como lista de cotejo. |

## La ruta de pasos

| # | Paso | Qué produce | Prompts |
|:-:|---|---|:-:|
| 1 | **Acotar el tema** | Una pregunta de investigación delimitada (opcional) | 1 |
| 2 | **Tus datos** | Tema, pregunta, objetivos, delimitación, escala y área | — |
| 3 | **Preparar el Space** | Un Space en Perplexity con el anteproyecto y las instrucciones fijas | 1 |
| 4 | **Bloque 1** | 500–700 palabras con citas APA 7 | A + B |
| 5 | **Bloque 2** | 500–700 palabras con citas APA 7 | A + B |
| 6 | **Bloque 3** | 500–700 palabras con citas APA 7 | A + B |
| 7 | **Bloque 4** | 500–700 palabras con citas APA 7 | A + B |
| 8 | **Bloque 5** | 500–700 palabras que cierran con la pregunta de investigación | A + B |
| 9 | **Revisar coherencia** | Informe de contradicciones entre bloques 1, 2 y 3 | 1 |
| 10 | **Ensamblar el capítulo** | Introducción, cierre y lista única de referencias | 1 |

En cada bloque, el prompt **A** busca las fuentes y el prompt **B** redacta con ellas **en el mismo hilo**. Si A trae pocas fuentes, hay un prompt alternativo de **Investigación profunda** (Deep Research).

Además, la herramienta **Verificar un dato** está disponible en cualquier momento para comprobar una fecha, una reforma o una cita.

## Estructura por área

<details>
<summary><strong>Derecho</strong></summary>

1. Antecedentes remotos y recepción en México
2. Constitución y ley que hoy rige
3. Reformas y criterios de los tribunales
4. Contexto social y referente comparado
5. Situación actual y problemas heredados

</details>

<details>
<summary><strong>Administración y Contaduría</strong></summary>

1. Origen de la práctica y escuelas administrativas
2. Llegada a México y contexto económico
3. Marco normativo y evolución del sector
4. Trayectoria local o de la organización
5. Situación actual y herencia del pasado

</details>

<details>
<summary><strong>Ciencias de la Educación</strong></summary>

1. Origen del problema y corrientes pedagógicas
2. Sistema educativo mexicano y artículo 3º
3. Planes de estudio y práctica en el aula
4. Referentes internacionales y contexto social
5. Situación actual y pendientes

</details>

<details>
<summary><strong>Psicología</strong></summary>

1. Origen del constructo y escuelas psicológicas
2. Medición y criterios diagnósticos *(varía por subárea)*
3. La psicología en México e intervención
4. Ética, regulación y contexto social *(varía por subárea)*
5. Estado actual y debates abiertos

</details>

<details>
<summary><strong>Ciencias de la Salud y Enfermería</strong></summary>

1. Origen del problema y conocimiento clínico
2. El sistema de salud mexicano ante el problema
3. Normatividad y guías de práctica
4. Modelos de cuidado y evidencia internacional *(varía por subárea)*
5. Contexto epidemiológico y retos actuales

</details>

## Subáreas

Solo aplican a **Psicología** y **Salud**. Cambian uno o dos bloques según el enfoque:

| Área | Subáreas |
|---|---|
| Psicología | clínica, educativa, social, organizacional |
| Salud | enfermería, medicina, nutrición, fisioterapia |

Si no se elige subárea, se usa el bloque genérico del área.

## Cómo se usa

```text
Anteproyecto (.docx) ──► Paso 1: Acotar el tema (opcional)
                              │
                              ▼
                     Paso 2: Tus datos + escala + subárea
                              │
                              ▼
                     Paso 3: Space en Perplexity
                              │
          ┌───────────────────┴───────────────────┐
          ▼                                       │
   Bloque n · Prompt A (buscar) ──► revisar enlaces
          │                                       │
          ▼                                       │
   Bloque n · Prompt B (redactar, mismo hilo)     │
          │                                       │
          ▼                                       │
   Verificar datos dudosos ──► pegar en Word ─────┘  (×5 bloques)
                              │
                              ▼
                  Paso 9: Revisar coherencia (1-3)
                              │
                              ▼
                  Paso 10: Ensamblar el capítulo