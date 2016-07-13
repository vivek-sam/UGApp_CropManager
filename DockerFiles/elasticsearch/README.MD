[vivek@localhost elasticsearch]$ pwd
/home/vivek/git/UGApp_CropManager/DockerFiles/elasticsearch
[vivek@localhost elasticsearch]$ docker build -t ugapp/elasticsearch .

Docker Run...
docker run -d -v <data-dir>:/data -p 9200:9200 -p 9300:9300 ugapp/elasticsearch
