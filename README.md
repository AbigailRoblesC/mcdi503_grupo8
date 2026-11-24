# Proyecto Grupo 8 · MCDI503

**Exploración inteligente para la ciencia de datos (MCDI503)**
Magíster en Ciencia de Datos e Inteligencia Artificial, Universidad Andrés Bello · 2026

## Integrantes

| Integrante | Usuario GitHub |
| --- | --- |
| Abigaíl Robles Chávez | @AbigailRoblesC-github |
| Daniel Pérez Ramírez | @DanielRamirezPerez-github |
| Matias Manriquez Ortiz | @MatiasManriquezO-github |
| Roberto Sánchez Saldivia | @RobertSanchezS-github |


## Estructura del repositorio

```
MCDI503_grupo8/
├── README.md
├── notebooks/
│   └── mcdi503_f1_sumativo_grupo8                  # Informe F1_S1
└── docs/
    └── informe/
        └── F1/                                     # informe resumen de la Sumativa 1 (PDF)
```


## Convención de commits

Cada commit debe empezar con un prefijo que indique el **tipo de cambio**, seguido de dos puntos y una
descripción breve en presente. Lo que decide el prefijo es **qué archivo cambia y por qué**, no si el cambio
"corrige algo" o no.

Formato: `prefijo: verbo en presente + qué cambia`, todo en minúsculas y sin tildes
(por ejemplo `docs: agrega informe de la formativa 1`, no `Docs: Se agregó el informe`).

### Definición de cada prefijo

| Prefijo | Úsalo cuando... | No lo uses para... |
|---|---|---|
| `docs` | subes o editas documentación: README, `data/README.md`, informes en `docs/informe/`, comentarios explicativos en los cuadernos | cambios en los datos o en celdas de código que se ejecutan (aunque el archivo sea texto) |
| `data` | agregas, actualizas o reemplazas archivos de datos en `data/raw/` o `data/processed/` | cambiar cómo se limpian o filtran los datos dentro del cuaderno (eso es `feat` o `fix`) |
| `feat` | implementas algo nuevo: un cuaderno, un análisis, una prueba de hipótesis, un intervalo de confianza, una figura, una carpeta de fase | corregir algo que ya existía y estaba mal (eso es `fix`) |
| `fix` | corriges un error real en el código, en los resultados o en la estructura de archivos (rutas rotas, archivos que no debían subirse, un filtro mal aplicado) | mejorar la redacción o completar información en un informe o README (eso es `docs`) |
| `test` | agregas o ejecutas validaciones: nulos, duplicados, rangos, tipos de dato, que los faltantes sean MCAR, que los archivos se reproduzcan igual con la semilla 42 | escribir el análisis que se está validando (eso es `feat`) |


