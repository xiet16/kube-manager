# minikube 安装

1. 去官网网址，按照windows 的操作来（https://minikube.sigs.k8s.io/docs/start/）
2. .kube/config 文件在windows C:\Users\Administrator 目录底下
3. 运行官网的命令需要管理员权限运行power shell

# 其他方式
1. minikube start --image-mirror-country="cn" --registry-mirror=https://gswjjmza.mirror.aliyuncs.com --image-repository=registry.cn-hangzhou.aliyuncs.com/google_containers --force --kubernetes-version=v1.23.8
