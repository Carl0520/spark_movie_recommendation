## Build spark enviroment reated by 
https://github.com/cluster-apps-on-docker/spark-standalone-cluster-on-docker#tech-stack
### 1. clone this project
```
git clone git@github.com:Carl0520/spark_movie_recommendation.git
```
### 2.Download small movielens dataset from below link into default 'build/workspace/data' file
https://grouplens.org/datasets/movielens/

### 3.Build from local
```
cd build
chmod +x build.sh ; ./build.sh
```
### 4. Start containers 
(must in 'build' file, stop container ctrl + C)
```
docker-compose up
```
