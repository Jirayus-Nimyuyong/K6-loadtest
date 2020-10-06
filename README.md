# k6-loadtest-example
### Getting started:
  * docker-compose up -d influxdb grafana OR ./docker-compose.sh
  * Load http://localhost:3000, and import the dashboard.json config to a new dashboard.
  * docker-compose run k6 run /tests/fileScenario.js OR ./fileScenario.sh
