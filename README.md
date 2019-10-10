# Data Management 
deploy elastic &amp; kibana with docker-compose

# elastic search
No SQL DB

# kibana
data visualizing 

# Install & Commands
docker-compose up -d
docker-compose down

# TroubleShoot 
Case 1. vm.max_map error : increase max.map.count
sudo sysctl -w vm.max_map_count=524288
