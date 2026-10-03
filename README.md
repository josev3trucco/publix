# Impacto económico de la incautación de Puerto Gaitán

Tablero interactivo que estima el valor económico interrumpido por la incautación de 1.198 kg de cocaína en Puerto Gaitán (Meta), con la contabilidad oficial de la cadena de valor de 2022 del Ministerio de Justicia y UNODC.

**Ver el tablero:** https://josev3trucco.github.io/dashboard-puerto-gaitan/

## Qué muestra

- El valor del inventario incautado: entre $6.120 y $7.907 millones de pesos.
- De qué está hecho ese valor: insumos, transformación, cultivo y logística.
- Quién recibe el valor: insumos importados, remuneración y excedente de toda la cadena.
- La escalera de precios, del mercado interno al mayorista de destino.
- El capital que pierde la estructura según su margen propio, con una calculadora para probar supuestos.

## Hallazgos principales

- La cifra oficial de $7.906,8 millones equivale a 1.198 kg × $6,6 millones por kg. Es un precio de referencia, no una tasación ni una renta criminal.
- Ese precio coincide con los precios oficiales de 2021 y 2022 ajustados por inflación (diferencia menor a 2%).
- El excedente de la cadena (73% del valor) está repartido entre muchos actores; no es la renta de la estructura incautada.
- El valor en mercados de destino es ingreso bruto de otros actores, no pérdida colombiana.

## Cómo leerlo

El selector de escenario cambia todas las cifras: conservador (precio de salida 2022), central (precio reportado 2026) y alto (referencia andina, solo como escenario). Cada cifra del modelo tiene una clasificación: OBSERVED, OFFICIAL_ESTIMATE, MODELLED, ASSUMPTION, SCENARIO o UNRESOLVED.

## Archivos

- `index.html`: el tablero completo (gráficos, tablas y diagramas Mermaid), con los datos incluidos en JSON.

## Fuentes

- [Boletín técnico FFI 2020-2022, Minjusticia y UNODC](https://www.minjusticia.gov.co/programas-co/ODC/Publicaciones/Publicaciones/Bolet%C3%ADn%20t%C3%A9cnico%20FFI.pdf)
- [Boletín de precios de drogas ilícitas 2021, Minjusticia](https://www.minjusticia.gov.co/programas-co/ODC/Documents/Publicaciones/Criminalidad/Delitos-Relacionados-Drogas/Boletin%20Precios%202021.pdf)
- [El Tiempo, 2 de octubre de 2026](https://www.eltiempo.com/colombia/otras-ciudades/incautan-en-el-meta-1-2-toneladas-de-clorhidrato-de-cocaina-a-disidentes-de-ivan-mordisco-que-tendrian-como-destino-los-estados-unidos-3590891)
- [Ejército, decomiso de 606 kg en Puerto Gaitán](https://cgfm.mil.co/es/node/42671)
- IPC del DANE, vía [Noticias Caracol](https://www.noticiascaracol.com/economia/ipc-de-2025-en-colombia-quedo-en-5-1-segun-el-dane-en-cuanto-podran-subir-arriendos-y-mas-rg10) y [Noticias RCN](https://www.noticiasrcn.com/economia/colombia-registra-inflacion-anual-de-6-24-en-agosto-de-2026-segun-el-dane-1058573)

## Limitaciones

- Son salidas de modelo con promedios nacionales de 2022, no observaciones del cargamento.
- No hay precio regional publicado para el Meta, ni valor de los medios logísticos incautados.
- El método con que se calculó la cifra oficial no está publicado; se dedujo por aritmética.
- El margen propio de la estructura (10% a 40%) es un supuesto.
- Los precios ilícitos se ajustaron con el IPC del consumidor, que no es su índice natural.
- El estudio es económico y de política pública. No contiene información operativa sobre producción, rutas ni ocultamiento.

## Autor

José Trucco, [@jose_tcco](https://x.com/jose_tcco). 
Fecha de referencia: 3 de octubre de 2026.
