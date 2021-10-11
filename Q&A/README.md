# Skill

#### Git
- git 基本命令
- github fork repo
- github PR 相关操作
- github issue 相关操作
- 搭建 git

#### Docker
- 安装 Docker
- Docker 基本命令
- 使用 Dockerfile 构建一个 docker 镜像
- 使用具有 multi-stage 特性的 Dockerfile 构建一个 docker 镜像
- 通过 veth-paris 和网络名称空间完成两个容器之间的网络通信

#### Kubernetes

- Kubernetes 基本概念
- Kubectl 基本命令
- 使用 RKE 部署一个 Kubernetes 集群(1个主节点和2个节点)
- 在 Kubernetes 中运行 WordPress 应用程序，并使用 ingress 公开服务
- 在 Kubernetes 集群中添加一个动态 NFS 供应器，使用 NFS 存储运行一个应用程序

#### Rancher
- Rancher 基本功能使用
- Rancher 单节点部署
- Rancher HA部署
- Rancher 离线部署
- 托管集群
- 导入集群

#### Linux
- linux 基本命令使用

#### Pytest
- python 基本语法
- 搭建 pytest 环境
- 本地运行测试 case
- 编写 case

#### Tools
- Jmeter 使用
- Postman 使用
- Charles 使用
- Jenkins 使用

# Plan
#### 1月
skill | 学习内容 | 任务 | 完成时间
-- | -- | -- | --
Git | 1. git 基本命令 </br> 2. github fork repo </br> 3. github PR 相关操作 </br> 4. github issue 相关操作 | 1. 完成 git 提交周报 </br>2. 完成 issue 创建/comment/关闭等操作 | 第1周
Docker | 1. 安装 Docker </br> 2. Docker 基本命令 | 1. Docker 镜像基本操作 </br> 2. 运行/停止/重启/删除 Docker 容器 </br> 3. 查看容器日志 </br> 4. Docker 容器执行命令 | 第1周
Kubernetes | 1. Kubernetes 基本概念 </br> 2. Kubectl 基本命令 </br> 3. RKE 部署 Kubernetes 集群| 1. 使用 RKE 部署一个 Kubernetes 集群(1个主节点和2个节点) </br> 2. 部署 pod </br> 3. 部署 service | 第4周
Rancher | 1. Rancher 基本功能使用 </br> 2. 托管集群 </br> 3. 导入集群 </br> 4. Rancher 单节点部署| 1. 搭建一个单节点Rancher环境 </br> 2. 托管一个集群 </br> 3. 导入一个集群 </br> 4. project/ns相关操作 </br> 5. 工作负载/service/ingress/pod相关操作 | 第4周

#### 3月
skill | 学习内容 | 任务 | 完成时间
-- | -- | -- | --
Git | 1. 搭建 git | 1. Linux 环境搭建 git 环境并创建 project | 第2月
Docker | 1. Docker 镜像 | 1. 使用 Dockerfile 构建一个 docker 镜像 </br> 2. 使用具有 multi-stage 特性的 Dockerfile 构建一个 docker 镜像 | 第3月
Kubernetes | 1. Kubernetes 应用 | 1. 在 Kubernetes 中运行 WordPress 应用程序，并使用 ingress 公开服务 </br> 2. 在 Kubernetes 集群中添加一个动态 NFS 供应器，使用 NFS 存储运行一个应用程序 | 第3月
Rancher | 1. Rancher HA 部署 </br> 2. Rancher 离线部署 </br> 3. Rancher 功能使用| 1. 搭建一个 Rancher HA 环境 </br> 2. 搭建一个 Rancher 离线环境 </br> 3. 部署监控/日志/全局监控 </br> 4. 创建1个project和1个namespace，并配置资源配额（project 2cpu 1G memory）（ns 1cpu 500M memory），然后在该ns下启动一个应用，限制 limit cpu 1 memory 500M | 第2月
Pytest | 1. 搭建 pytest 环境 </br> 2. 运行测试 case | 1. 本地运行测试 case | 第3月

#### 5月
skill | 学习内容 | 任务 | 完成时间
-- | -- | -- | --
Docker | 1. Docker 容器 | 1. 通过 veth-paris 和网络名称空间完成两个容器之间的网络通信 | 第5月
Rancher | 1. Rancher 功能使用 | 1. 搭建 Harbor/审计日志/macvlan/GPU/F5 环境 | 第4月
Pytest | 1. 编写 Test case </br> 2. Jenkins 使用 | 1. 编写 Test Case </br> 2. Jenkins 创建/运行 Pipeline | 第5月
