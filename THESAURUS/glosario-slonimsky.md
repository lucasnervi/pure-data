---
fuente: "Nicolas Slonimsky — Thesaurus of Scales and Melodic Patterns (Amsco Publications), Introduction (pp. i-vi) + Explanation of Terms (pp. vii-viii)"
armado: 2026-08-28
---

# Diccionario de conceptos — Thesaurus of Scales and Melodic Patterns

Extraído de la Introducción y del "Explanation of Terms" original del libro (págs. i-viii). Se conserva el término en inglés tal como aparece en el libro — es el nombre que van a llevar los objetos/abstracciones en los patches de Pd — con la traducción/definición en español al lado. `[Nos. X-Y]` indica el rango de patrones numerados del Thesaurus cuando el libro lo especifica.

---

## 1. Términos estructurales generales

- **Scale (Escala)** — Progresión de tonos que cambia de dirección solo en los puntos terminales (asciende o desciende sin zigzag). Toda progresión interpolada sigue siendo, técnicamente, una "escala".
- **Pattern (Patrón melódico)** — Figura melódica en la que la dirección cambia de ascendente a descendente (o viceversa) antes de llegar al punto terminal. Toda progresión infrapolada o ultrapolada es, por definición, un "pattern".
- **Progression (Progresión)** — Término general que cubre tanto "scale" como "pattern".
- **Permutation (Permutación)** — Distribución de las notas de un patrón melódico dado en distintos órdenes de sucesión.
- **Non-Symmetric Interpolation (Interpolación no simétrica)** — Inserción libre de notas adicionales entre los tonos principales (sin restricción de equidistancia).
- **Symmetric Interpolation (Interpolación simétrica)** — Inserción de notas a intervalos iguales desde sus respectivos puntos pivote, lo que da progresiones invertibles. Ejemplo del libro: Escala No. 37 (C, D, F, F♯, G, B♭, C), donde los intervalos son los mismos subiendo desde C que bajando desde el C superior.

Todas las escalas y patrones del Thesaurus están centrados en **C** como tono inicial y final; se transponen libremente a cualquier centro tonal.

---

## 2. Los tres procesos de formación melódica (familia Interpolation)

El corazón operativo del libro: cómo se generan patrones nuevos a partir de una progresión de tonos principales.

- **Interpolation (Interpolación)** — Inserción de una o más notas *entre* los tonos principales de una progresión. `[Ejemplo: Scale No. 21]`
- **Infrapolation (Infrapolación)** — Término acuñado por Slonimsky. Inserción de una nota *por debajo* de un tono principal. `[Ejemplo: Pattern No. 231]`
- **Ultrapolation (Ultrapolación)** — Término acuñado por Slonimsky. Inserción de una nota *por encima* del tono principal siguiente. `[Ejemplo: Pattern No. 53, donde se inserta G sobre F♯]`
- **Inter-Ultrapolation** — Inserción de 2 notas entre los tonos principales: una entre ambos, otra por encima del tono principal. `[Ejemplo: Pattern No. 123]`
- **Infra-Interpolation** — Combinación de infrapolación + interpolación.
- **Infra-Ultrapolation** — Combinación de infrapolación + ultrapolación.
- **Infra-Inter-Ultrapolation** — Combinación de las tres a la vez. `[Ejemplo: Pattern No. 341]`

Infrapolación y ultrapolación producen el quiebre de dirección (zigzag) que distingue un "pattern" de una "scale" pura. Combinadas libremente dan las formas con guion.

---

## 3. Intervalos base y sus "Progressions" (división equidistante de la octava)

Slonimsky nombra los intervalos con términos latinos/griegos para evitar asociarlos a una tonalidad. El prefijo **sesqui-** agrega medio tono a un intervalo base. Cada intervalo tiene además una sección del libro ("... Progression") que lo usa como unidad de división equidistante de la octava (o de varias octavas).

| Término (libro) | Intervalo | División de la octava |
|---|---|---|
| **Semitone Progression** | Segunda menor (1 semitono) | = escala cromática |
| **Whole Tone** | Segunda mayor (1 tono) | Whole-Tone scale = octava ÷ 6 |
| **Sesquitone Progression** | Tercera menor (1½ tonos) | octava ÷ 4 = acorde de séptima disminuida |
| **Ditone Progression** | Tercera mayor (2 tonos) | octava ÷ 3 = tríada aumentada |
| **Diatessaron Progression** | Cuarta justa (2½ tonos) | 5 octavas ÷ 12 |
| **Tritone Progression** | Cuarta aumentada / quinta disminuida (3 tonos) | octava ÷ 2 |
| **Diapente Progression** | Quinta justa (3½ tonos) | 7 octavas ÷ 12 (ciclo de quintas) |
| **Quadritone Progression** | Sexta menor (4 tonos) | 2 octavas ÷ 3 (tríada aumentada "estirada") |
| **Sesquiquadritone Progression** | Sexta mayor (4½ tonos) | 3 octavas ÷ 4 |
| **Quinquetone** | Séptima menor (5 tonos) | — |
| **Sesquiquinquetone Progression** | Séptima mayor (5½ tonos) | 11 octavas ÷ 12 |
| **Septitone Progression** | Novena mayor (7 tonos) | 7 octavas ÷ 6 |

- **Sesqui** — Prefijo: agrega medio tono a un intervalo dado (Sesquitone = 1½ tonos, Sesquiquadritone = 4½ tonos).

---

## 4. Escalas de nota fija (no equidistantes)

- **Heptatonic Scales** `[Nos. 1034-1087]` — Progresiones diatónicas de 7 grados: mayor, menor, modos gregorianos, y escalas con 1 o 2 segundas aumentadas.
- **Heptatonic Arpeggios** `[Nos. 1088-1141]` — Progresiones melódicas por terceras derivadas de las escalas heptatónicas (arpegios en terceras).
- **Pentatonic Scales** `[Nos. 1142-1190]` — Escalas de 5 notas. El libro contiene 49. A diferencia de la Whole-Tone (una sola forma posible por nota), admiten múltiples formas.
- **Whole-Tone Scale** — 6 notas a la octava, división equidistante en tonos enteros; una sola forma posible sobre una nota dada. Ejemplo histórico citado: *Voiles* de Debussy.
- **Prometheus Scale** `[No. 50]` — Escala de 6 notas (C, D, E, F♯, A, B♭) usada por Scriabin en el poema sinfónico *Prometheus*.
- **Plural Scales** — Progresiones formadas por escalas disyuntas encadenadas, ej.: Do mayor, Re♭ mayor, Re mayor, Mi♭ mayor.
- **Complementary Scales** — Progresiones melódicas de 2 octavas de rango que en conjunto cubren los 12 tonos cromáticos (ej.: escala de Do mayor + pentatónica de teclas negras).

---

## 5. Politonalidad, poliritmia y politetracordos

- **Polytonal Scales** — Escalas en distintas tonalidades tocadas simultáneamente.
- **Polyrhythmic Scales** — Progresiones simultáneas en ritmos distintos.
- **Polytonal Polyrhythmic Scales** — Combina las dos anteriores: distintos ritmos en distintas tonalidades a la vez.
- **Bitonal Arpeggios** `[Nos. 1191-1213]` — Progresiones melódicas formadas alternando arpegios de 2 tonalidades distintas.
- **Quadritonal Arpeggios** `[Nos. 1251-1291]` — Progresiones formadas por 4 tríadas mutuamente exclusivas (ej.: Do mayor, Re menor, Fa♯ mayor, Sol♯ menor).
- **Mutually Exclusive Triads** — 4 tríadas (mayor, menor, disminuida o aumentada) que en conjunto cubren los 12 tonos cromáticos sin repetir ninguno.
- **Polytetrachord** — Progresión de 12 tetracordos que recorre las 12 tonalidades: *conjuncta* (el último tono de un tetracordo coincide con el primero del siguiente) o *disyuncta* (separados por un grado diatónico).
  - **Conjunct Polytetrachord**, **Disjunct Polytetrachord**
  - **Major / Minor / Phrygian / Disjunct Phrygian / Disjunct Minor / Disjunct Major / Disjunct Lydian Polytetrachord** — variantes según el modo del tetracordo. Ejemplo extremo: **Disjunct Major Polytetrachord `[No. 958]`**, con hasta 48 notas funcionalmente distintas (contando repeticiones en octavas distintas).

---

## 6. El sistema de 12 tonos y acordes de 11-12 tonos

- **Twelve-Tone Progressions** `[Nos. 1214-1318]` — Figuras melódicas de 12 tonos distintos (permutaciones de la escala cromática), en la línea del sistema de Schoenberg.
- **Crossing Intervals** `[Nos. 1243-1250]` — Dos filas de 6 tonos que se superponen, cubriendo entre ambas los 12 tonos, cada fila formando una progresión de segundas, terceras, cuartas, quintas o sextas.
- **Chord of the Minor 23rd** — Acorde de 12 notas distintas dispuestas en terceras, formando 4 tríadas mutuamente exclusivas.
- **Quartal Chord** — Acorde de 12 tonos dispuesto en cuartas justas.
- **Mother Chord** — Acorde introducido por Fritz Klein (1921, en *Die Maschine*, bajo el seudónimo *Heautontimorumenus*): 12 tonos distintos con los 11 intervalos distintos posibles.
- **Grandmother Chord** — Acorde inventado por Nicolas Slonimsky (13 de febrero de 1938): variante invertible del Mother Chord, con los intervalos ordenados alternadamente impar/par (en semitonos), donde la serie de intervalos impares forma una progresión aritmética decreciente y la de pares una creciente. Coincide con el **12-tone Spiral Pattern No. 1232a**.
- **Pyramid Chord** — Acorde introducido por Fritz Klein (1921): serie de intervalos decrecientes desde una octava hasta un semitono.
- **Major / Minor Bitonal Chord** — Acorde de 2 tríadas (mayor o menor) generalmente con tónicas a distancia de tritono (ej.: Do mayor + Fa♯ mayor).
- **Tone-Cluster** — Término de Henry Cowell: complejo de notas que llena una o más octavas, diatónica, cromática o pentatónicamente.

Nota del libro: todo acorde de 11 intervalos distintos suma 66 semitonos (progresión aritmética 1 a 11) = 5½ octavas = un tritono entre la nota más grave y la más aguda (Pyramid, Mother, Grandmother Chord, etc.)

---

## 7. Simetría, reflejo y desarrollo rítmico

- **Mirror Interval Progressions** — Escalas/patrones en los que la figura descendente es la inversión melódica exacta de la figura ascendente. `[Ejemplo: Scale No. 1 ascendente es la inversión especular de Scale No. 4 descendente]`
- **Palindromic Canons** — Cánones que se leen igual hacia adelante que hacia atrás (como la frase "Able was I ere I saw Elba"). `[Ejemplo notable: los dos cánones palindrómicos sobre el Pattern No. 72, que producen una progresión de tríadas enarmónicas alternando mayor/menor]`
- **Bitonal Palindromic Canons** — Cánones palindrómicos que al desarrollarse canónicamente forman acordes bitonales de 6 notas (2 tríadas). `[Ejemplo: Scale No. 7 → tríadas de Do mayor + Fa♯ mayor]`
- **Rhythmic Development** (p. iv, fuera del glosario oficial pero central para el uso rítmico) — Cualquier fragmento del Thesaurus puede tratarse como motivo: tocado hacia adelante y en retrógrado, con ritmos variados dentro de un compás dado, genera un número ilimitado de figuras melódicas. `[Ejemplo: Pattern No. 194]`
- **Double Notes** — Combinaciones derivadas de escalas/patrones correspondientes, tocadas en intervalos dobles.

---

## 8. Armonización

- **Octave Position** — En armonía a 4 voces: tríada con la fundamental tanto en la melodía como en el bajo.
- **Tertian Position** — Tríada con la fundamental en el bajo y la 3ª en la melodía.
- **Quintan Position** — Tríada con la fundamental en el bajo y la 5ª en la melodía.
  - Fórmula **8-3-5** (Octave-Tertian-Quintan): al subir la melodía (diatónica o cromáticamente), las posiciones rotan Octave→Tertian→Quintan→Octave; al bajar, se invierte el orden. Ejemplos citados: la escena de la celda del monje en *Boris Godunov* (Mussorgsky), y la escala de tonos enteros del bajo en el 2º acto de *Tosca* (Puccini).
- **Master Chords** — Acordes de séptima de dominante con la 5ª omitida, tabulados cromáticamente en las 12 tonalidades, indicados con números dentro de un círculo (① a ⑫) sobre las secciones Tritone/Ditone/Sesquitone Progression. Cualquier Master Chord puede transportarse un tritono arriba o abajo con buen resultado.
- **Autochordal Harmonization** — Armonizar una escala con los acordes derivados de las propias notas de esa escala. `[Ejemplo: Scale No. 12 (C, D♯, F, F♯, A, B, C) armonizada con 2 tríadas propias: Fa mayor y Si mayor]`
- **Pandiatonic** (término acuñado por Slonimsky en 1937) — Uso libre de las 7 notas de la escala diatónica, melódica y armónicamente, sin restricción funcional tonal.
  - **Pandiatonic Progressions** — Fila de las 7 notas diatónicas distintas; invertible melódicamente, retrógrada, o ambas (4 formas).
  - **Pandiatonic Counterpoint** — Contrapunto estricto con las 7 notas distintas en cada voz, sin duplicación vertical.
  - **Pandiatonic Harmony** — Contrapunto a varias voces con acordes libremente combinados de las 7 notas diatónicas. Compositores citados: Ravel, Stravinsky, Hindemith, Milhaud, Copland, Roy Harris, y el jazz orquestal (tríada mayor enriquecida con 6ª, 7ª o 9ª añadida).

---

## 9. Referencia rápida — de concepto a patch de Pd

Mapeo pensado para la skill `slonimsky-pd` (ver `.claude/skills/slonimsky-pd/SKILL.md`):

| Concepto del libro | Rol en un patch de Pd |
|---|---|
| Scale / Pattern (No. X) | tabla de notas (`table` + lista de offsets desde C) que se recorre con un secuenciador |
| Interpolation / Infrapolation / Ultrapolation | abstracciones de transformación que expanden una tabla de "tonos principales" insertando notas entre/debajo/arriba |
| Permutation | abstracción que reordena la lista de la tabla |
| Mirror Interval Progression | abstracción de inversión melódica (invertir el signo de los offsets) |
| Palindromic Canon | reproducir la tabla en retrógrado, en canon con la voz original desfasada |
| Rhythmic Development (adelante + retrógrado) | brazalete rítmico de M pasos (ver `rhythm-necklace.pd`) aplicado sobre la tabla melódica |
| Master Chords / Autochordal Harmonization | voz de acompañamiento adicional (acordes) enviada por el mismo canal MIDI que la melodía, al sintetizador |
| Progression (Tritone/Ditone/.../Diapente) | define el intervalo de paso por defecto del secuenciador cuando se genera un patrón nuevo desde cero (no transcripto del libro) |

