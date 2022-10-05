# ElasticOpenTelemetry
 
Based on  https://github.com/smith/opentelemetry-demo/blob/main/README.Elastic.md

To run demo
Set env variables
```export ELASTIC_APM_SERVER_ENDPOINT="YOUR-ELASTIC-APM-SERVER-ENDPOINT"
export ELASTIC_APM_SECRET_TOKEN="YOUR-ELASTIC-APM-SERVER-SECRET-KEY"
```

##
Replace otelcol-config-extras.yml
`opentelemetry-demo/src/otelcollector/docker-compose up --no-build`


run
```
docker-compose up --no-build
```

Once the demo is up and a change has been made to `docker-compose up --no-build`, restart otel collector container
