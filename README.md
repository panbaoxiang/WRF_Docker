# WRF_Docker
WRF docker
### Step 0: Install docker
### Step 1: Get installation code
```
wget  https://github.com/NCAR/WRF_DOCKER/archive/refs/heads/master.zip
```
### Step 2: Build image
```
docker   build   -t   wrf_tutorial   --build-arg argname=tutorial   .
```
### Step 3: Enter the container land
```
docker   run   -it   --name   teachme   wrf_tutorial   /bin/tcsh
```

The image data is stored at:
$HOME/Library/Containers/com.docker.docker/Data
