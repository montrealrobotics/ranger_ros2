# Range Base2
ROS2 driver for Ranger base with dynamic covariances added and battery status.

Need to have InDro UGV Package installed on the system first if running not provided Docker Files

To build into a production environment. Run the following commander  
```bash
DOCKER_BUILDKIT=1 docker build -f ranger_base2/Dockerfile_dev -o out_ranger_base2 .
```
Then to create the production container, run
```bash
docker build -t ranger_base2:prod -f ranger_base2/Dockerfile_prod .
```