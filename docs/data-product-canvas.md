
# Data Product Canvas - Berlin LOR Building Permits

## Metadata

* owner: Open Lifeworlds
* description: Data products providing Berlin building permit data on different LOR hierarchy levels
* updated: 2025-11-06

## Input Ports

### berlin-lor-geodata

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/refs/heads/main/data-product-manifest.yml

### berlin-lor-building-permits-source-aligned

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-building-permits-source-aligned/refs/heads/main/data-product-manifest.yml

## Transformation Steps

* [Data extractor](https://github.com/open-lifeworlds/open-lifeworlds-python-lib/blob/main/openlifeworlds/extract/data_extractor.py) extracts data from inout ports
* [Data blender](https://github.com/open-lifeworlds/open-lifeworlds-python-lib/blob/main/openlifeworlds/transform/data_blender.py) blends csv data into geojson files

## Output Ports

### berlin-building-permits-geojson
name: Berlin Building Permits Geojson
* owner: Open Lifeworlds
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/tree/main/data/03-gold/berlin-building-permits-geojson
* updated: 2025-11-06

**Files**

* [berlin-building-permits-2022-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2022-01-districts.geojson)
* [berlin-building-permits-2022-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2022-02-districts.geojson)
* [berlin-building-permits-2022-03-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2022-03-districts.geojson)
* [berlin-building-permits-2022-04-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2022-04-districts.geojson)
* [berlin-building-permits-2022-05-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2022-05-districts.geojson)
* [berlin-building-permits-2022-06-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2022-06-districts.geojson)
* [berlin-building-permits-2022-07-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2022-07-districts.geojson)
* [berlin-building-permits-2022-08-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2022-08-districts.geojson)
* [berlin-building-permits-2022-09-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2022-09-districts.geojson)
* [berlin-building-permits-2022-10-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2022-10-districts.geojson)
* [berlin-building-permits-2022-11-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2022-11-districts.geojson)
* [berlin-building-permits-2022-12-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2022-12-districts.geojson)
* [berlin-building-permits-2023-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2023-01-districts.geojson)
* [berlin-building-permits-2023-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2023-02-districts.geojson)
* [berlin-building-permits-2023-03-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2023-03-districts.geojson)
* [berlin-building-permits-2023-04-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2023-04-districts.geojson)
* [berlin-building-permits-2023-05-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2023-05-districts.geojson)
* [berlin-building-permits-2023-06-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2023-06-districts.geojson)
* [berlin-building-permits-2023-07-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2023-07-districts.geojson)
* [berlin-building-permits-2023-08-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2023-08-districts.geojson)
* [berlin-building-permits-2023-09-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2023-09-districts.geojson)
* [berlin-building-permits-2023-10-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2023-10-districts.geojson)
* [berlin-building-permits-2023-11-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2023-11-districts.geojson)
* [berlin-building-permits-2023-12-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2023-12-districts.geojson)
* [berlin-building-permits-2024-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2024-01-districts.geojson)
* [berlin-building-permits-2024-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2024-02-districts.geojson)
* [berlin-building-permits-2024-03-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2024-03-districts.geojson)
* [berlin-building-permits-2024-04-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2024-04-districts.geojson)
* [berlin-building-permits-2024-05-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2024-05-districts.geojson)
* [berlin-building-permits-2024-06-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2024-06-districts.geojson)
* [berlin-building-permits-2024-07-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2024-07-districts.geojson)
* [berlin-building-permits-2024-08-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2024-08-districts.geojson)
* [berlin-building-permits-2024-09-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2024-09-districts.geojson)
* [berlin-building-permits-2024-10-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2024-10-districts.geojson)
* [berlin-building-permits-2024-11-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2024-11-districts.geojson)
* [berlin-building-permits-2024-12-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2024-12-districts.geojson)
* [berlin-building-permits-2025-01-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2025-01-districts.geojson)
* [berlin-building-permits-2025-02-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2025-02-districts.geojson)
* [berlin-building-permits-2025-03-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2025-03-districts.geojson)
* [berlin-building-permits-2025-04-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-geojson/berlin-building-permits-2025-04-districts.geojson)


### berlin-building-permits-statistics
name: Berlin Building Permits Statistics
* owner: Open Lifeworlds
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/tree/main/data/03-gold/berlin-building-permits-statistics
* updated: 2025-11-06

**Files**

* [berlin-building-permits-statistics.json](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-building-permits/main/data/03-gold/berlin-building-permits-statistics/berlin-building-permits-statistics.json)


## Observability

### Quality metrics

 * name: geojson_property_completeness
 * description: The percentage of geojson features that have all necessary properties

| Name | Value |
| --- | --- |
| berlin-building-permits-2022-01-districts.geojson | 68 |
| berlin-building-permits-2022-02-districts.geojson | 77 |
| berlin-building-permits-2022-03-districts.geojson | 65 |
| berlin-building-permits-2022-04-districts.geojson | 75 |
| berlin-building-permits-2022-05-districts.geojson | 73 |
| berlin-building-permits-2022-06-districts.geojson | 78 |
| berlin-building-permits-2022-07-districts.geojson | 70 |
| berlin-building-permits-2022-08-districts.geojson | 77 |
| berlin-building-permits-2022-09-districts.geojson | 70 |
| berlin-building-permits-2022-10-districts.geojson | 67 |
| berlin-building-permits-2022-11-districts.geojson | 78 |
| berlin-building-permits-2022-12-districts.geojson | 72 |
| berlin-building-permits-2023-01-districts.geojson | 68 |
| berlin-building-permits-2023-02-districts.geojson | 58 |
| berlin-building-permits-2023-03-districts.geojson | 63 |
| berlin-building-permits-2023-04-districts.geojson | 62 |
| berlin-building-permits-2023-05-districts.geojson | 65 |
| berlin-building-permits-2023-06-districts.geojson | 58 |
| berlin-building-permits-2023-07-districts.geojson | 50 |
| berlin-building-permits-2023-08-districts.geojson | 60 |
| berlin-building-permits-2023-09-districts.geojson | 58 |
| berlin-building-permits-2023-10-districts.geojson | 57 |
| berlin-building-permits-2023-11-districts.geojson | 55 |
| berlin-building-permits-2023-12-districts.geojson | 55 |
| berlin-building-permits-2024-01-districts.geojson | 57 |
| berlin-building-permits-2024-02-districts.geojson | 63 |
| berlin-building-permits-2024-03-districts.geojson | 52 |
| berlin-building-permits-2024-04-districts.geojson | 48 |
| berlin-building-permits-2024-05-districts.geojson | 53 |
| berlin-building-permits-2024-06-districts.geojson | 67 |
| berlin-building-permits-2024-07-districts.geojson | 50 |
| berlin-building-permits-2024-08-districts.geojson | 58 |
| berlin-building-permits-2024-09-districts.geojson | 53 |
| berlin-building-permits-2024-10-districts.geojson | 45 |
| berlin-building-permits-2024-11-districts.geojson | 53 |
| berlin-building-permits-2024-12-districts.geojson | 55 |
| berlin-building-permits-2025-01-districts.geojson | 62 |
| berlin-building-permits-2025-02-districts.geojson | 50 |
| berlin-building-permits-2025-03-districts.geojson | 70 |
| berlin-building-permits-2025-04-districts.geojson | 67 |


## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

consumer-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).