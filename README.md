# kafka-azure-app-insights
Monitoring librdkafka and Confluent components in Azure Ecosystems


### Usage
1. Populate the `InstrumentationKey=` in the `applicationinsights.json` file, upi cam get this from the azure portal.
2. Kick off using `docker-compose up
   
### TODO
- Rename directory structure from jmx_export to app_insights
- Update agent in brokers
- correct JMX metrics in agent config`