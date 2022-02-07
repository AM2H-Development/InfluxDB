# InfluxDB

git clone https://github.com/AM2H-Development/InfluxDB.git

touch .env (fill with your personal data, see .env in git)

cd InfluxDB

docker-compose --env-file ../.env up -d

to connect with Grafana use https://influx.HOST as Server-URL
