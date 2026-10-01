# Optimizaci-n-de-Marketing-Digital
Determinar si la nueva Página B mejora la conversión respecto  a la Página A en un e-commerce de moda.

# Proyecto N-2: Optimización de Marketing Digital (A/B Testing)

## Contexto
E-commerce de moda. El equipo de Diseño rediseñó la página de inicio 
(Página B). Marketing dudaba de que mejorara la conversión respecto a 
la anterior (Página A). Se corrió un A/B Test con ~40,000 usuarios.

## Metodología
- Métrica: tasa de conversión (proporción).
- Auditoría: variables balanceadas entre grupos (F-3).
- Test: Chi-Cuadrado de independencia (2×2).
- Dataset: [Marketing A/B Test - Synthetic](https://www.kaggle.com/datasets/krishnaharish1/marketing-ab-test-synthetic-uplift)

## Resultados
| Grupo | Conversión |
|---|---|
| Control (A) | 11.36% |
| Treatment (B) | 18.79% |

- Diferencia absoluta: +7.44 pp
- Diferencia relativa: +65.49%
- p-value: ≈ 0 (<< α = 0.05)

## Conclusión
La Página B SÍ mejora las conversiones, con un 95% de confianza. 
Se recomienda mantener la Página B.

## Estructura del repo
- `Optimización de Marketing Digital.ipynb` — Análisis completo (F-1 a F-7)
- `README.md` — Este archivo
- `images/` — Visualizaciones del EDA

## Cómo reproducir
Abrir el notebook en [Google Colab](link).
