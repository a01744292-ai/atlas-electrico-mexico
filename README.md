# Atlas Eléctrico de México · Eco Solare

Aplicación web estática desarrollada para TE1020. Explica el sistema eléctrico mexicano desde los recursos energéticos hasta el consumidor con datos oficiales y trazabilidad documental.

## Módulos

1. **Recursos energéticos** — clasificador interactivo, diagramas de conversión, matriz y comparador.
2. **Generación** — mapa de centrales, filtros, gráficas e indicadores.
3. **Transmisión** — sistemas eléctricos, indicadores y simulador trifásico de corriente/pérdidas.
4. **Distribución** — divisiones CFE, continuidad, pérdidas y simulador de transformador ideal.
5. **¿Sabías que?** — 20 hallazgos verificables, reforma energética 2013, comparación histórica y control final de calidad.

## Control de calidad

- 20 hallazgos: 5 recursos, 5 generación, 5 transmisión y 5 distribución.
- 3 mapas interactivos.
- 2 simuladores físicos con casos de prueba reproducibles.
- Separación explícita entre CFE y SEN, MW y GWh, bruto y neto, limpio y renovable.
- Matriz CFE 2022 comprobada con su Informe Anual: 139,831 GWh desglosados en 90,252 GWh fósiles, 38,729 GWh renovables y 10,850 GWh nucleares.
- Indicadores históricos 2022 de Transmisión (SAIDI, MVAr) y Distribución (pérdidas con alcance diferenciado, SAIDI, SAIFI, obras y cobertura).
- Datos inconsistentes se conservan y señalan; no se corrigen silenciosamente.
- La sección final documenta las iteraciones de revisión y ejecuta 18 controles automáticos de estructura, consistencia y cálculos.

## Publicación

Sitio preparado para GitHub Pages desde la rama `main`.

## Fuentes principales

CFE Informes Anuales 2022–2024 (Informe 2022 pp. 10–11, 17, 37, 141 y 293); SENER/PRODESEN; Diario Oficial de la Federación (reforma constitucional 2013, LIE 2014, LTE 2015, LSE 2025); Programa Sectorial de Energía 2025–2030.