# NEREIDA · Participation in Conferences

This repository collects the conference contributions (oral presentations and posters) produced within the **NEREIDA** project, which develops digital twins and seasonal forecasting tools for water quantity and quality in reservoirs and coastal areas of Catalonia, co-developed with the Catalan Water Agency (ACA).

The pilot system is the **Ter basin**, including the Sau and Susqueda reservoirs that supply drinking water to the Barcelona metropolitan area, with the Tordera basin as a comparable watershed.

## Summary

| # | Date | Conference | Location | Type | Title | Authors | Output |
|---|------|------------|----------|------|-------|---------|--------|
| 1 | 27–31 Oct 2025 | GLEON 2025 All Hands' Meeting | Virtual (host site: Lake Toba, Indonesia) | Poster | Digital twins for the prediction and management of water quality and coastal dynamics | D. Mercado-Bettín, J. Pagès, R. Marcé | [PDF](GLEON2025_poster_MercadoBettin.pdf) |
| 2 | 22–26 Jun 2026 | XXIII Congress of the Iberian Association of Limnology (AIL 2026) | Bilbao, Spain | Oral presentation | Forecasting for adaptive reservoir management | D. Mercado-Bettín, R. Marcé | [PDF](AIL2026_oralpresentation_MercadoBettin.pdf) |
| 3 | 30 Aug – 4 Sep 2026 | GLEON 2026 All Hands' Meeting | Banyoles, Spain | Poster (abstract 2.3) | Forecasting how much water a reservoir will hold, and what state it will be in, months ahead | D. Mercado-Bettín, R. Marcé | [PDF](GLEON2026_poster_Mercado-Bettin.pdf) |

## Contributions in detail

### 1. GLEON 2025 All Hands' Meeting (virtual, October 2025)

**Poster:** *Digital twins for the prediction and management of water quality and coastal dynamics*
**Authors:** Daniel Mercado-Bettín, Jordi Pagès, Rafael Marcé (CEAB-CSIC)

Introduces the NEREIDA digital-twin concept: co-development with water managers, prediction of water quantity and quality in two comparable watersheds (Ter and Tordera), and coverage of rivers, reservoirs and coastal areas. It discusses the temporal scales relevant to water management decisions, with a focus on seasonal and decadal prediction, and outlines the modelling workflow (river models in R, lake models with GLM, coastal modelling with Delft3D, and knowledge-based machine learning).

**Outputs**
- Poster: [`GLEON2025_poster_MercadoBettin.pdf`](GLEON2025_poster_MercadoBettin.pdf)
- Tool (under development at the time): [Seasonal prediction](https://nereidaca.github.io/seasonal_prediction/)

### 2. AIL 2026 – XXIII Congress of the Iberian Association of Limnology (Bilbao, June 2026)

**Oral presentation:** *Forecasting for adaptive reservoir management*
**Authors:** Daniel Mercado Bettín, Rafael Marcé (CEAB-CSIC)

Presents the integrated hydrological–limnological forecasting framework for seasonal prediction of reservoir water quantity and quality, motivated by increasing climate variability (droughts, intense rainfall, shifting seasonality) and the associated water-quality risks (eutrophication, cyanobacteria blooms, hypolimnetic oxygen depletion).

**Outputs**
- Slides: [`AIL2026_oralpresentation_MercadoBettin.pdf`](AIL2026_oralpresentation_MercadoBettin.pdf)
- Tool: [Forecasting tool](https://nereidaca.github.io/forecasting_tool/)

### 3. GLEON 2026 All Hands' Meeting (Banyoles, August–September 2026)

**Poster:** *Forecasting how much water a reservoir will hold, and what state it will be in, months ahead*
**Authors:** Daniel Mercado-Bettín, Rafael Marcé (CEAB-CSIC)

Shows the framework running on the Sau–Susqueda reservoir system, producing seasonal (1–7 month) forecasts of storage, inflows and water-quality variables from a single modelling chain forced by the 51-member ECMWF SEAS5.1 ensemble (GLM 3.1.1 for the reservoir component), so that quantity and quality forecasts remain physically consistent.

**Outputs**
- Poster: [`GLEON2026_poster_Mercado-Bettin.pdf`](GLEON2026_poster_Mercado-Bettin.pdf)
- Tools presented:
  - [Hydrological tool](https://nereidaca.github.io/hydro_tool)
  - [Saline intrusion tool](https://nereidaca.github.io/salintrusion_tool)
  - [fDOM weather app](https://danielmerbet.github.io/fdom_weather_app)
  - [Groundwater Catalunya](https://danielmerbet.github.io/gw_catalunya)

## Repository structure

```
participation_conferences/
├── README.md
├── GLEON2025_poster_MercadoBettin.pdf
├── AIL2026_oralpresentation_MercadoBettin.pdf
└── GLEON2026_poster_Mercado-Bettin.pdf
```

## Adding a new contribution

1. Name the file as `<CONFERENCE><YEAR>_<type>_<FirstAuthorSurname>.pdf`, where `<type>` is `poster` or `oralpresentation` (e.g. `EGU2027_poster_MercadoBettin.pdf`).
2. Add a row to the **Summary** table, keeping it in chronological order.
3. Add a short entry under **Contributions in detail** with the title, authors, a two- or three-line description and links to any related tools, code or data.

## Acknowledgements

This work is part of the NEREIDA project, grant RDI001/24/000044, funded by the Agència Catalana de l'Aigua (ACA) under the R+D+I call ACC/1362/2024.

## Contact

Daniel Mercado-Bettín · Centre d'Estudis Avançats de Blanes (CEAB-CSIC) · daniel.mercado@ceab.csic.es
