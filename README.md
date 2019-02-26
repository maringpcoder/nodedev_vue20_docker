# nodedev_vue20_docker

## 基于docker构建vue开发环境

## 开始
```
docker-compose build
docker-compose up -d
docker-compose ps

```
**配置**:本地项目映射到docker容器地址

```
PROJECT_LOCAL_PATH=/Users/marin/workspace/front
```

## 进入容器

```
docker exec -i
#使用脚手架初始化项目
vue init webpack vueproject
cd vueproject
#安装依赖
npm install

```

**注意**：
vue20project是已经初始化了的项目，可以通过如上命令自己创建
