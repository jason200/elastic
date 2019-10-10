# Data Management 
deploy elastic &amp; kibana with docker-compose

# Install & Commands
docker-compose up -d
docker-compose down

# elastic search
No SQL DB
- excute 
  docker run -d -p 9200:9200 -p 9300:9300 -it -h elasticsearch elasticsearch
  
  git clone https://github.com/justmeandopensource/elk
  
  cd elk
  
  cd docker
  
  docker-compose up -d

# kibana
data visualizing 
- verify & screen

  http://localhost:5601

# TroubleShoot 
Case 78. vm.max_map error : increase max.map.count w/ubuntu
sudo sysctl -w vm.max_map_count=524288
