# how to
* create `.env` file
* start project `docker compose up -d`

***WARN*** if Sonar Qube container can't start elasticksearch server try to set larger `vm.max_map_count` with `sysctl -w vm.max_map_count=262144` command on host machine

# .env file vars
* `PG_VERSION=15.5`
* `PG_USER=db_user`
* `PG_PASSWORD=strong_password`
* `PG_PORT=5432`

* `TEAMCITY_VERSION=2023.11.1`
* `TEAMCITY_DB=teamcity_db_name`
* `TEAMCITY_UI_PORT=80`

* `SONAR_VERSION=community`
* `SONAR_DB=sonar_db_db`
* `SONAR_UI_PORT=9000`
* `SONAR_SERVICE_PORT=9092`
