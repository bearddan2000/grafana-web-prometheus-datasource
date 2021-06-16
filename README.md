# grafana-web-prometheus-datasource

## Description
A demo of loading a datasource
dynamically at build time.

To see Prometheus as datasource:
- Nav to http://localhost
- Login with `admin/admin`
- configuration -> datasources
  - Select Prometheus
    - dashboards
      - import and click label

## Tech stack
- prometheus

## Docker stack
- prom/prometheus
- grafana/grafana

## To run
`sudo ./install.sh -u`
- GRAFANA DASHBOARD http://localhost
  - Login with `admin/admin`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
