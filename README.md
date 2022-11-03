# elastic_dev

Minimal repository for testing elastic search locally.

## Usage

Pull containers:

```
docker pull docker.elastic.co/elasticsearch/elasticsearch:8.5.0-arm64
docker pull docker.elastic.co/kibana/kibana:8.5.0-arm64
```

Clone this repo, and from this directory run:

```
docker-compose up
```

1. Check indices at: http://localhost:9200/_cat/indices

2. From another container, connect to host: http://host.docker.internal:9200

3. Access Kibana at: http://localhost:5601/
    * Query Console: http://localhost:5601/app/dev_tools#/console
    * Index Management: http://localhost:5601/app/management/data/index_management/indices