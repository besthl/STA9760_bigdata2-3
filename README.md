# STA9760_bigdata Part 2

Start:

docker-compose up -d


This will start ElasticSearch and Kibana.

ElasticSearch: http://localhost:9200 Kibana: http://localhost:5601


Running python:


docker-compose run pyth python parking.py --page_size=1000 --num_pages=4


export curl output:

curl -X GET {localhost:9200/parking-violation-index} > output.txt


Shutting off:

docker-compose down

Visualisation
![Plot1](screenshots/img1.png)
![Plot4](screenshots/img4.png)
![Plot5](screenshots/img5.png)
