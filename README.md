# docker_training
Link
Lien presentation :
    https://docs.google.com/presentation/d/1u1AtyoRZZdREEBOLTslfYxykJ5Z5n9DyKjoOrHmMbL4/edit?usp=sharing
    
    
    https://blog.jessfraz.com/post/windows-for-linux-nerds/
    
    https://docs.docker.com/engine/installation/
    
    


Day 1
TP 1
docker image build -t jthorel/lauers1 -f Dockerfile.base .
docker image history jthorel/layers1

docker container run -it jthorel/layers2
ctrl p ctrl q  pour sortir du shell sans terminer le container

docker container ps

docker container diff 353070dc627d

htop
