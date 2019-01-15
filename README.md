# djsite

### django运行环境镜像构建
'docker build -f djEnv.dockerfile -t djevn:v1.0 .'

### 挂载运行
'docker run -d -p 80:22222 --name mysite --mount type=bind,source=$pwd,target=/project djevn:v1.0'