﻿# Adversary-Hunting-ToolKit
Difficult to carry a VM or install tools eerytime you need to work on a Forensics Case or a New Environment. Collrcting all Containerized Versions of Defensive Tools for easy installation and reducing time to install, Build & Deploy.  


## Analytical Tools : 
* Shogun : https://hub.docker.com/r/shogun/shogun
* Tensorflow , Pytorch , Keras, Rstudio, Jupyter Notebook, Python (x64),Apache Spark : https://docs.anaconda.com/anaconda/user-guide/tasks/docker/
* Elastic Container : https://github.com/peasead/elastic-container
* Apache Zepplin : conda install -c danielfrg apache-zeppelin

## Visualization Tools : 
* Neo4j - https://hub.docker.com/_/neo4j
* Graphana : docker run -d -p 3000:3000 grafana/grafana-enterprise
* Kibana : docker run --name kib-01 --net elastic -p 5601:5601 docker.elastic.co/kibana/kibana:8.7.0
* Apache Superset : https://hub.docker.com/r/apache/superset
* Metabase : docker run -d -p 3000:3000 --name metabase metabase/metabase

## SOC Tools: 
* MISP/Cortex/TheHive/Shuffle - https://github.com/TheHive-Project/Docker-Templates/tree/main/docker/thehive4-cortex3-misp-shuffle
* Maltego Docker Compose : https://dolores.paterva.com/customers/docker/download_compose/13/
* Splunk : https://splunk.github.io/docker-splunk/EXAMPLES.html
* MITRE Navigator : docker run -it -p 80:80 --name attacknav davidjbianco/attacknav:dev
* MITRE TRAM : https://raw.githubusercontent.com/center-for-threat-informed-defense/tram/787143e4f41f40e4aeb72d811a9d4297c03364d9/docker/docker-compose.yml

## Utilities & Extras : 
* Cyberchef : https://hub.docker.com/r/mpepping/cyberchef
* ViperMonkey : https://hub.docker.com/r/cincan/vipermonkey
* YETI : https://github.com/yeti-platform/yeti/tree/master/extras/docker
* Caldera : https://hub.docker.com/r/mitre/caldera
* nmap : https://hub.docker.com/r/instrumentisto/nmap
* Intelmq: https://github.com/certat/intelmq-docker


Will Keep on Adding more tools and frameworks as i keep coming across them. 
