# Casos de Prueba - Calculadora de Texto

| ID | Escenario | Entrada (Input) | Resultado Esperado | Estado |
|---|---|---|---|---|
| **CP-01** | Texto normal | `"Hola mundo desde el test"` | Caracteres: 25, Palabras: 4 | Aprobado |
| **CP-02** | Texto vacío | `""` | Caracteres: 0, Palabras: 0 | Aprobado |
| **CP-03** | Solo espacios | `"     "` | Caracteres: 0 (o 5 según spec), Palabras: 0 | Aprobado |
| **CP-04** | Una sola palabra | `"Supercalifragilistico"` | Caracteres: 21, Palabras: 1 | Aprobado |
| **CP-05** | Texto con puntuación | `"Hola, mundo! ¿Todo bien?..."` | Caracteres: 29, Palabras: 4 | Aprobado |
