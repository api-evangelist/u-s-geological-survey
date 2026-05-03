# U.S. Geological Survey (u-s-geological-survey)

The U.S. Geological Survey (USGS) is a scientific agency of the U.S. government that conducts research and provides data on the natural resources and hazards of the United States. The USGS is known for its work in mapping and monitoring earthquakes, volcanoes, and landslides to help mitigate risks and protect communities. USGS also studies water resources including streamflow, groundwater, and water quality through a nationwide network of monitoring stations. Their public APIs provide programmatic access to real-time earthquake data, water monitoring observations, seismic design parameters, and geospatial data products.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Federal Government, Geological, Earth Science, Natural Resources, Earthquake, Water, Hydrology

## Timestamps

- **Created:** 2024-11-14
- **Modified:** 2026-05-03

## APIs

### Earthquake Notifications, Feeds, and Web Services

The USGS Earthquake Hazards Program provides real-time notifications and historical earthquake data through the FDSN Event Web Service. Search the ANSS ComCat earthquake catalog by geography, time, magnitude, and depth. Responses available in GeoJSON, CSV, KML, and QuakeML formats.

**Human URL:** [https://earthquake.usgs.gov/earthquakes/feed/](https://earthquake.usgs.gov/earthquakes/feed/)

#### Tags:

 - Earthquakes, Seismic, Geoscience

#### Properties

- [Documentation](https://earthquake.usgs.gov/fdsnws/event/1/)
- [GettingStarted](https://earthquake.usgs.gov/earthquakes/feed/)
- [OpenAPI](openapi/usgs-earthquake-api-openapi.yaml)
- [Earthquake Properties Schema](json-schema/usgs-earthquake-api-earthquake-properties-schema.json)
- [JSON-LD](json-ld/usgs-earthquake-api-context.jsonld)
- [Earthquake Properties Example](examples/usgs-earthquake-api-earthquake-properties-example.json)

### USGS Water Data APIs

The USGS Water Data OGC APIs provide standardized access to USGS water monitoring data including continuous streamflow, daily values, groundwater levels, discrete water quality measurements, and monitoring location metadata. Implements OGC API Features standard with spatial and temporal filtering support.

**Human URL:** [https://api.waterdata.usgs.gov/](https://api.waterdata.usgs.gov/)

#### Tags:

 - Water, Hydrology, Streamflow, Groundwater

#### Properties

- [Documentation](https://api.waterdata.usgs.gov/docs/)
- [Authentication](https://api.waterdata.usgs.gov/signup/)
- [OpenAPI](openapi/usgs-water-data-api-openapi.yaml)
- [Monitoring Location Schema](json-schema/usgs-water-data-api-monitoring-location-properties-schema.json)
- [Time Series Properties Schema](json-schema/usgs-water-data-api-time-series-properties-schema.json)
- [JSON-LD](json-ld/usgs-water-data-api-context.jsonld)
- [Monitoring Location Example](examples/usgs-water-data-api-monitoring-location-properties-example.json)

### Asset Identifier Service (AIS)

The USGS Asset Identifier Service (AIS) allows USGS personnel to reserve, register, publish, and manage USGS persistent identifiers to make research more FAIR.

**Human URL:** [https://www.usgs.gov/tools/asset-identifier-service-ais](https://www.usgs.gov/tools/asset-identifier-service-ais)

#### Properties

- [Documentation](https://www.usgs.gov/tools/asset-identifier-service-ais)

### Seismic Design Web Service

Web services for calculating parameter values from various seismic design reference documents for engineering and construction purposes.

**Human URL:** [https://earthquake.usgs.gov/ws/designmaps/](https://earthquake.usgs.gov/ws/designmaps/)

#### Properties

- [Documentation](https://earthquake.usgs.gov/ws/designmaps/)

### ScienceBase

ScienceBase is a USGS Trusted Digital Repository providing permission-controlled and public access to scientific data products through a REST API.

**Human URL:** [https://www.usgs.gov/tools/sciencebase](https://www.usgs.gov/tools/sciencebase)

#### Properties

- [Documentation](https://www.usgs.gov/tools/sciencebase)
- [ScienceBase API Documentation](https://www.usgs.gov/sciencebase-instructions-and-documentation/api-and-web-services)

### StreamStats Web Services

HTTP-accessible hydrological analysis services for drainage area delineation, peak flow estimation, and basin characteristic computation.

**Human URL:** [https://www.usgs.gov/tools/streamstats-web-services](https://www.usgs.gov/tools/streamstats-web-services)

#### Properties

- [Documentation](https://www.usgs.gov/tools/streamstats-web-services)

### USGS Water Services (Legacy)

The original USGS NWIS water services API providing streamflow, groundwater, and water quality data via REST protocol.

**Human URL:** [https://www.usgs.gov/tools/usgs-water-services](https://www.usgs.gov/tools/usgs-water-services)

#### Properties

- [Documentation](https://nwis.waterservices.usgs.gov/)

## Common Properties

- [Website](https://www.usgs.gov/)
- [GitHubOrganization](https://github.com/usgs)
- [Documentation](https://www.usgs.gov/products/web-tools/apis)
- [SpectralRules](rules/usgs-spectral-rules.yml)
- [Vocabulary](vocabulary/u-s-geological-survey-vocabulary.yaml)
- [Geoscience Data Access Capability](capabilities/geoscience-data-access.yaml)

## Features

| Name | Description |
|------|-------------|
| Earthquake Catalog Query | Search the USGS ANSS ComCat earthquake catalog by geography, time, magnitude, depth, and event type with 20,000 event limit per query. |
| Real-Time Earthquake Data | Access near real-time earthquake data updated within minutes of events occurring anywhere in the world. |
| Water Monitoring Locations | Query USGS stream gages, groundwater wells, and other water quality monitoring stations by state, watershed, or geographic area. |
| Water Data Time Series | Retrieve continuous and daily water data including streamflow, stage, temperature, and water quality parameters. |
| OGC API Compliance | USGS Water Data APIs implement OGC API Features standard supporting CQL2 filtering, spatial queries, and standardized output formats. |
| GeoJSON Output | All spatial data returned in GeoJSON format compatible with mapping libraries and geospatial analysis tools. |

## Use Cases

| Name | Description |
|------|-------------|
| Earthquake Hazard Monitoring | Emergency managers and scientists monitor real-time earthquake activity for hazard assessment and emergency response planning. |
| Flood Forecasting | Hydrologists use USGS streamflow data for flood prediction, water supply forecasting, and reservoir management. |
| Groundwater Management | Water managers track groundwater level trends for sustainable aquifer management and drought assessment. |
| Environmental Research | Researchers use USGS geological and water data for environmental impact assessments and climate change studies. |
| Engineering Design | Civil engineers use USGS water data and seismic design services for infrastructure planning and construction. |

## Integrations

| Name | Description |
|------|-------------|
| USGS GitHub Organization | Open-source tools including libcomcat, rcomcat, and other clients for accessing USGS earthquake and water data. |
| USGS Water Data for the Nation | The flagship USGS water data portal providing maps and tools built on the NWIS water services API. |
| National Water Information System (NWIS) | Legacy USGS water data system providing the underlying data for Water Data APIs with millions of site records. |
| FDSN Standards | USGS earthquake API implements FDSN web service specifications for international seismograph network data exchange. |

## Artifacts

### OpenAPI

- [usgs-earthquake-api-openapi.yaml](openapi/usgs-earthquake-api-openapi.yaml)
- [usgs-water-data-api-openapi.yaml](openapi/usgs-water-data-api-openapi.yaml)

### JSON Schema

- [usgs-earthquake-api-earthquake-feature-collection-schema.json](json-schema/usgs-earthquake-api-earthquake-feature-collection-schema.json)
- [usgs-earthquake-api-earthquake-properties-schema.json](json-schema/usgs-earthquake-api-earthquake-properties-schema.json)
- [usgs-earthquake-api-earthquake-geometry-schema.json](json-schema/usgs-earthquake-api-earthquake-geometry-schema.json)
- [usgs-water-data-api-monitoring-location-properties-schema.json](json-schema/usgs-water-data-api-monitoring-location-properties-schema.json)
- [usgs-water-data-api-time-series-properties-schema.json](json-schema/usgs-water-data-api-time-series-properties-schema.json)

### JSON Structure

- [usgs-earthquake-api-earthquake-properties-structure.json](json-structure/usgs-earthquake-api-earthquake-properties-structure.json)
- [usgs-water-data-api-monitoring-location-properties-structure.json](json-structure/usgs-water-data-api-monitoring-location-properties-structure.json)
- [usgs-water-data-api-time-series-properties-structure.json](json-structure/usgs-water-data-api-time-series-properties-structure.json)

### JSON-LD

- [usgs-earthquake-api-context.jsonld](json-ld/usgs-earthquake-api-context.jsonld)
- [usgs-water-data-api-context.jsonld](json-ld/usgs-water-data-api-context.jsonld)

### Examples

- [usgs-earthquake-api-earthquake-properties-example.json](examples/usgs-earthquake-api-earthquake-properties-example.json)
- [usgs-water-data-api-monitoring-location-properties-example.json](examples/usgs-water-data-api-monitoring-location-properties-example.json)
- [usgs-water-data-api-time-series-properties-example.json](examples/usgs-water-data-api-time-series-properties-example.json)

## Capabilities

### Shared Per-API Definitions

- [USGS Earthquake API](capabilities/shared/usgs-earthquake-api.yaml) — 3 operations for earthquake event querying and catalog discovery
- [USGS Water Data API](capabilities/shared/usgs-water-data-api.yaml) — 3 operations for water monitoring location and time series access

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Geoscience Data Access](capabilities/geoscience-data-access.yaml) | USGS Earthquake API, USGS Water Data API | 7 | Geoscientist, Emergency Manager, Hydrologist |

## Vocabulary

- [U.S. Geological Survey Vocabulary](vocabulary/u-s-geological-survey-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 4 actions, 1 workflow, and 4 personas across earthquake monitoring and water resources domains

## Rules

- [USGS Spectral Rules](rules/usgs-spectral-rules.yml) — 32 rules across 13 categories enforcing USGS API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
