# STA9760_bigdata2&3
Start:

docker-compose up -d


This will start ElasticSearch and Kibana.

ElasticSearch: http://localhost:9200 Kibana: http://localhost:5601


Running python:


docker-compose run pyth python parking.py --page_size=10 --num_pages=4


Shutting off:

docker-compose down
