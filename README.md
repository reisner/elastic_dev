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
