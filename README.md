# 镜像是由一层层组成的，不同层的修改不互通？
# 每一个容器都需要有一个Dockerfile，多个容器组合成一个应用需要有docker_compose.yml
# 不同容器的文件系统互不相通，所以工作目录名称相同，但其实不会相互冲突
# 清除docker缓存命令：docker system prune -a
# docker compose启动命令：docker compose up -d
# 如果需要重新build镜像，删掉image后执行上一条
