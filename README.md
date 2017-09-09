# Pholcus with Docker

### 通过Dockerfile构建
```
git clone https://git.ustclug.org/Crawlerlearning/Pholcus/
cd Pholcus
docker build -t pholcus .
docker run -d -P -v `pwd`/pholcus_pkg:/root/pholcus_pkg pholcus
```
### 直接从Docker Hub运行
```
docker run -d -P -v `pwd`/pholcus_pkg:/root/pholcus_pkg silentyang/pholcus
```
