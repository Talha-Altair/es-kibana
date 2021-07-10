# Kibana Setup Local

```
wget https://artifacts.elastic.co/downloads/kibana/kibana-7.13.3-linux-x86_64.tar.gz
```

```
tar -zxvf kibana-7.13.3-linux-x86_64.tar.gz
```

## Change Host Address

```
sudo gedit config/kibana.yml
```

set elasticsearch.hosts to point at your Elasticsearch instance

```
bin/kibana
```

Open  http://localhost:5601


