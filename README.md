# elasticsearch

- https://hub.docker.com/_/elasticsearch
- https://hub.docker.com/_/kibana

```bash
docker run -d --name elasticsearch --net somenetwork -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" elasticsearch:7.13.2
docker run -d --name kibana --net somenetwork -p 5601:5601 kibana:7.13.2
```
