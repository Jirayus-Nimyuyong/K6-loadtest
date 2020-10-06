# k6-loadtest-example
### Performance Testing with K6
  * Mockup preliminary for load Performance Testing with K6 
### Getting started:
  * RUN docker-compose up -d influxdb grafana OR ./docker-compose.sh
  * Load http://localhost:3000, and import the dashboard.json config to a new dashboard.
  * RUN docker-compose run k6 run /tests/fileScenario.js OR ./fileScenario.sh

Look through the k6 docs here:  [https://k6.io/docs](https://k6.io/docs)
