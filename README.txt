This project deploys web servers for a HA Web Application using CloudFormation.

Files included:
network.yaml
network-parameters.yaml
services.yaml
services-parameters.yaml
High-Availability Web App.png
create.bat
update.bat
delete.bat

To create the network infrastruture stack:
./create.bat NetworkInfrastructure network.yaml network-parameters.json


To create the Server infrastruture stack:
./create.bat ServerInfrastructure services.yaml services-parameters.json

HA Web Application URL
http://serve-webap-73n6k4z0j4ac-2136512243.us-east-1.elb.amazonaws.com/