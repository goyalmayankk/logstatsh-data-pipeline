# logstatsh-data-pipeline

### docker network create --type bridge elknetwork
### docker run -dit --name elasticsearch --net elknetwork -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" elasticsearch:7.7.1

### docker run -it --rm --name logstash --network elknetwork -v /root/config/:/config logstash:7.7.1 -f /config/my5.conf
