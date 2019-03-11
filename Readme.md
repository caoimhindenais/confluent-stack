# 



# docker-compose-confluent.yml
A lightly modifed compose file from Confluent's repo from 
https://github.com/confluentinc/cp-docker-images/blob/5.1.2-post/examples/cp-all-in-one/docker-compose.yml


e.g.

- No Control Center
- Run in a seperate subnet (to help prevent IP collisions) 



# docker-compose-spring-cloud-dataflow.yml

A lightly modifed compose file from spring cloud's repo

https://raw.githubusercontent.com/spring-cloud/spring-cloud-dataflow/v2.0.0.RELEASE/spring-cloud-dataflow-server/docker-compose.yml

e.g.
- wurstmeister's kafka images replaced with confluent images
- influx replaced with prometheus (springcloud/spring-cloud-dataflow-grafana-prometheus not quiet working yet ...??) 
