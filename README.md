目录
=================

* [1、集群原理](https://github.com/linabellbiu/CloudNative/blob/main/k8s/%E5%8E%9F%E7%90%86.md#1集群原理)
   * [1、master-node 架构](https://github.com/linabellbiu/CloudNative/blob/main/k8s/%E5%8E%9F%E7%90%86.md#1master-node-架构)
   * [2、工作原理](https://github.com/linabellbiu/CloudNative/blob/main/k8s/%E5%8E%9F%E7%90%86.md#2工作原理)
   * [3、原理分解](https://github.com/linabellbiu/CloudNative/blob/main/k8s/%E5%8E%9F%E7%90%86.md#3原理分解)
      * [1、主节点（master）](https://github.com/linabellbiu/CloudNative/blob/main/k8s/%E5%8E%9F%E7%90%86.md#1主节点master)
      * [2、工作节点（node）](https://github.com/linabellbiu/CloudNative/blob/main/k8s/%E5%8E%9F%E7%90%86.md#2工作节点node)
   * [其他：](https://github.com/linabellbiu/CloudNative/blob/main/k8s/%E5%8E%9F%E7%90%86.md#其他)
   * [2、组件交互原理](https://github.com/linabellbiu/CloudNative/blob/main/k8s/%E5%8E%9F%E7%90%86.md#2组件交互原理)

* [Kubernetes安装](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#kubernetes安装)
   * [1、集群原理](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#1集群原理)
      * [1、master-node 架构](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#1master-node-架构)
      * [2、工作原理](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#2工作原理)
      * [3、原理分解](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#3原理分解)
         * [1、主节点（master）](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#1主节点master)
         * [2、工作节点（node）](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#2工作节点node)
   * [其他：](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#其他)
   * [2、组件交互原理](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#2组件交互原理)
   * [3、安装](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#3安装)
      * [1、理解](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#1理解)
      * [2、执行](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#2执行)
         * [1、准备机器](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#1准备机器)
         * [2、安装前置环境（都执行）](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#2安装前置环境都执行)
            * [1、基础环境](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#1基础环境)
            * [2、docker环境](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#2docker环境)
         * [3、安装k8s核心（都执行）](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#3安装k8s核心都执行)
         * [4、初始化master节点（master执行）](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#4初始化master节点master执行)
         * [5、初始化worker节点（worker执行）](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#5初始化worker节点worker执行)
         * [6、验证集群](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#6验证集群)
         * [7、设置ipvs模式](https://github.com/linabellbiu/CloudNative/blob/main/k8s/安装.md#7设置ipvs模式)



<!-- Created by https://github.com/ekalinin/github-markdown-toc -->
