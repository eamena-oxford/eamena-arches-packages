# Notes

Notes about packages.
Unfinished packages are stored into https://github.com/eamena-oxford/eamena-arches-dev:
    - [RM IIIF](https://github.com/eamena-oxford/eamena-arches-dev/tree/main/iiif)

## 220201_pkg

[220201_pkg/](https://github.com/eamena-oxford/eamena-arches-packages/tree/main/220201_pkg):
1. copied from https://github.com/reubenosborne1/eamena-package + business data

## 220323_pkg-reubenosborne

[220323_pkg-reubenosborne/](https://github.com/eamena-oxford/eamena-arches-packages/tree/main/220323_pkg-reubenosborne):
1. copied from https://github.com/reubenosborne1/eamena-package + business data
2. fixed [Heritage Place.json](https://github.com/eamena-oxford/eamena-arches-packages/tree/main/220323_pkg-reubenosborne/graphs/resource_models) to fit with an export of business data Heritage Places.jsonl from the EAMENA DB (220609), avoiding errors during `load_business_data`:
    * TileValidationErrors (`'This card requires values for the following:...'`);
    * TileCardinalityErrors (`'Unable to save a tile to a card with cardinality 1 where a tile has previously been saved...`)

