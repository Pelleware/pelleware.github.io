---
title: Map Data
---

# Walkabout Map Data

Walkabout's street networks are derived from [OpenStreetMap](https://www.openstreetmap.org/copyright) data, © OpenStreetMap contributors, and are made available under the [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).

You can download the street network used in the app for each city:

| City | Download |
|---|---|
| Copenhagen + Frederiksberg | [copenhagen.json.zip](data/copenhagen.json.zip) |
| Aarhus | [aarhus.json.zip](data/aarhus.json.zip) |
| Odense | [odense.json.zip](data/odense.json.zip) |
| Manhattan | [manhattan.json.zip](data/manhattan.json.zip) |

Each file is a JSON database of the walkable street lines, the city and area boundaries, and the road widths used for tracking. It is released under the same ODbL 1.0 license; if you use it, credit "© OpenStreetMap contributors".

## Areas

The areas you can walk in each city come from these sources:

- **Copenhagen:** the city's districts (bydele) from Københavns Kommune.
- **Aarhus:** *Lokalsamfund i Aarhus*, © Aarhus Kommune, via [Open Data DK](https://www.opendata.dk/), licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Merged into larger areas and clipped to Walkabout's city outline.
- **Odense:** postal districts from Styrelsen for Dataforsyning og Infrastruktur (DAGI), as published by DAWA. Odense C is split along railways, the harbour and streets, and the areas are clipped to Walkabout's city outline.
- **Manhattan:** 2020 Neighborhood Tabulation Areas from the NYC Department of City Planning, via [NYC Open Data](https://opendata.cityofnewyork.us/). Merged into larger areas and clipped to Manhattan island.

The map background in the app is provided by Apple Maps and isn't part of this data.

Questions: [pelleware@gmail.com](mailto:pelleware@gmail.com)
