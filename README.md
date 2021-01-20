# spark_movie_recommendation

## Build spark enviroment
### 1. Install Docker and Docker Compose 
### 2. Clone docker project from 
https://github.com/cluster-apps-on-docker/spark-standalone-cluster-on-docker#tech-stack
### 3. Edit docker-compose.yml file and assign the volume path
#### line 18, 26, 36, 48 ( Ex. shared-workspace -> workspace )
### 4. Download small movielens dataset from below link into default 'workspace/data' file
https://grouplens.org/datasets/movielens/
### 5. Build

```
chmod +x build.sh ; ./build.sh
docker-compose up
(stop container ctrl + C)
```


