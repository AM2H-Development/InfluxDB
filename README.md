# InfluxDB

## install:
* git clone https://github.com/AM2H-Development/InfluxDB.git
* cd InfluxDB
* cp sample.env .env
* nano .env # adopt Project and Hostname
* docker compose up -d

## data:
all data is stored in volume "influxdb_data" and "influxdb_conf"

## use:
* localhost:8086 or Hostname:443 (behind Traefiks)
