# Avatar: Map Service

## Installation

Build GeoServer:

```bash
cd geoserver/2.16.1
bash build.sh
```

Go back to root, then build and start Docker containers:

```bash
docker-compose build
docker-compose up
```

## Usage

GeoServer is available at: http://127.0.0.1:8231/geoserver/

User name and password are `admin` and `geoserver` by default.

GeoServer tutorial: https://docs.geoserver.org/stable/en/user/gettingstarted/shapefile-quickstart/index.html

The data directory of GeoServer is mapped to: `geoserver/geoserver_data/data/`

PostGIS is available on port `8232` with username `avatar` and `HcLgFb#KNCGlpg8X` by default. GeoServer could use hostname `postgis` and port `5432` to import data.

