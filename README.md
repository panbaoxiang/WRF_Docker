# WRF_Docker
WRF docker

### Step 1: wget https://github.com/NCAR/WRF_DOCKER/archive/refs/heads/master.zip
### Step 2: build image
```
docker   build   -t   wrf_tutorial   --build-arg argname=tutorial   .
```
### Step 3: Enter the container land
```
docker   run   -it   --name   teachme   wrf_tutorial   /bin/tcsh
```

The image data is stored at:
$HOME/Library/Containers/com.docker.docker/Data
