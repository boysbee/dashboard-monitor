# Examle Grafana Dashboard
## Build docker-compose

```sh
docker-compose build
```

## Run
```sh
docker-compose up
```

## Login to Grafana

Open browser and input the url `http://localhost`. You will see login page, fill user `admin` and password `admin`.

## Set Datasource
Add datasource first.

__Add Datasource__
- Fill Name.
- Check `default`.
- Fill datasource url `http://localhost:8000`.
- Add

## Add new Dashboard
- Dashboard -> New
- Add Graph.
- Add `Metrics` -> `stats.couter.servers.*`.
- Or add more new `Query`. 
