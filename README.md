# Elasticsearch + FileBeat + Kibana

Use the latest version of efk, and do not need to compile, directly pull the official image to run.



## Usage

1. start up elasticsearch and kibana

   ```bash
   docker-compose up -d
   ```

   

2. start up the filebeat

   ```bash
   cd filebeat
   bash filebeat_docker.sh
   ```

   

3. view

Open the browser and enter `http://<your-address>:5601`.



