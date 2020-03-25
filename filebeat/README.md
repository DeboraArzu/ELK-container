Execute 
```
docker run \
docker.elastic.co/beats/filebeat:7.6.1 \
setup -E setup.kibana.host=localhost:5601 \
-E output.elasticsearch.hosts=["localhost:9200"]
```