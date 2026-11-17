---
aliases: [solicitudes, índice de expedientes]
tags: [solicitudes, anm, indice, clave]
---

# Índice de Solicitudes Mineras

> **18 expedientes en seguimiento** (8 viabilizadas según Acta 001 + 10 vigentes del shapefile ANM). ⚠ La cifra "44" está prohibida ([[Hallazgo - Doble conteo de la cifra 44]]). Fuentes: [[Acta 001-2025]] + ANM shapefile corte **2026-11-09** (`WS/datos/solicitudes-mineras-popayan.geojson`). ⚠ Titulares con discrepancia → [[Hallazgo - Discrepancias Acta vs ANM]] (P-1).

## Las 8 viabilizadas (según Acta 001/2025)

| # | Expediente | Titular (web/acta) | ha | Río | Nota |
|---|---|---|---|---|---|
| 1 | LBJ-11441 | María Eucaris León (de Manzano) | 57,94 | Pisojé | [[Solicitud LBJ-11441]] ⭐ **53% traslape** |
| 2 | KJS-15091 | AngloGold Ashanti ⚠ | 2.087 | Cauca | [[Solicitud KJS-15091]] (mayor área) |
| 3 | PKA-12011 | Juan Diego Fernández Álvarez | 252,8 | Cauca | [[Solicitud PKA-12011]] (oro) |
| 4 | LDL-08441 | Francy Niyired Meneses Dorado | 76,42 | Las Piedras | [[Solicitud LDL-08441]] (concepto jurídico) |
| 5 | PJV-12071 | Alixamayi Ceballos Galvis | 50,53 | Las Piedras | [[Solicitud PJV-12071]] |
| 6 | TLS-08101 | CONEXPE ⚠ | 81,35 | Pisojé | [[Solicitud TLS-08101]] (acumulación) |
| 7 | 503648 | CONEXPE ⚠ | 14,79 | Pisojé | [[Solicitud 503648]] (acumulación) |
| 8 | 504153 | Guillermo A. Tulande y Miguel A. Guzmán | 30,82 | Cauca/Molino | [[Solicitud 504153]] (Samanga; recorte a Sotará en trámite) |

## Las 10 vigentes / en evaluación (shapefile ANM 2026-11-09)

| # | Expediente | Titular (ANM) | ha | Mineral | Nota |
|---|---|---|---|---|---|
| 9 | JIT-10451 | EL CRUCERO S.O.M. | **9.277,46** | **BAUXITA** | [[Solicitud JIT-10451]] (LA MÁS GRANDE, gran minería) |
| 10 | KJS-15061 | Mineros Tolima S.A.S. ⚠ | 2.098,23 | oro+platino | [[Solicitud KJS-15061]] (hermana de KJS-15091) |
| 11 | 513245 | Inversiones Beamounte S.A.S. | 220,62 | recebo/rocas | [[Solicitud 513245]] |
| 12 | 512505 | Construimos Obras para la Paz S.A.S. | 97,37 | gravas/recebo | [[Solicitud 512505]] |
| 13 | 513383 | Olga Victoria Fajardo Andrade | 43,16 | recebo/rocas | [[Solicitud 513383]] (la más reciente, sep-2026; también título AJD-121) |
| 14 | 511692 | Eber Gerardo Realpe Rebolledo | 45,61 | arcillas | [[Solicitud 511692]] |
| 15 | 510254 | Víctor Enrique Cerón Churrun | 28,35 | rocas volcánicas | [[Solicitud 510254]] (**concesión diferencial**) |
| 16 | TI5-09401 | Reforestadora Andina S.A. | 23,43 | recebo | [[Solicitud TI5-09401]] |
| 17 | 506073 | CONCREINSA S.A.S. | 18,50 | arenas/recebo | [[Solicitud 506073]] |
| 18 | NHR-11131 | Carlos Aldemar Santiago Bolaños | 14,79 | arenas/gravas | [[Solicitud NHR-11131]] (**legalización; NO activa**) |

**Suma de las 17 con polígono: ≈ 14.488,55 ha** (cálculo propio sobre el geojson — registrada como derivada).

## Estados en la web

`Título vigente` · `Viabilizada` · `Solicitud vigente` · `En espera` (ninguna aún) — colores y formas por estado en `lib/mapa-data.ts:27-36`.

## Fuentes

```
Dato: 17 solicitudes con polígonos y atributos (corte 2026-11-09)
Fuente: ANM — descarga municipal de solicitudes; shapefile original ~/Documentos/comite veduria/2026-11-09 SOLICITUDES MUN POPAYÁN.zip
Archivo: WS/datos/solicitudes-mineras-popayan.geojson
Estado: ✔ polígonos/atributos ANM · ◐ conciliación contra Acta 001 (P-1) · Registrado: 13-nov-2026
Se usa en: /concesiones · /mapa · /cerca · todas las notas de expediente
```
