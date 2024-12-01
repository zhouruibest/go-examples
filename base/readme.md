# 搭建开发环境

1. 克隆 https://github.com/zhouruibest/go-examples 
2. 从中拷贝目录 gonivinck，然后改成自己的目录名
3. docker-compose up -d
4. 创建工程目录，如mall
mkdir -p mall && cd mall && go mod init mall && \
mkdir common && mkdir service && cd service && \
mkdir -p user/api && \
mkdir -p user/rpc && \
mkdir -p user/model && \
mkdir -p product/api && \
mkdir -p product/rpc && \
mkdir -p product/model && \
mkdir -p order/api && \
mkdir -p order/rpc && \
mkdir -p order/model && \
mkdir -p pay/api && \
mkdir -p pay/rpc && \
mkdir -p pay/model