# Docker build
```
git clone https://github.com/shineyoungw/dockerTest
cd dockerTest/UbuntuDocker
docker build --rm -t shineyoungw/ut:v2 .
docker images
```

# Docker run 
```
docker run -it --name ut -v ~/df:/df --rm shineyoungw/ut:v2
```
