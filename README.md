# xuperchain-on-k8s
Deploy a three-node xuperchain network on kubernetes

# Overview
Docker image: lonerii/xuperchain-nc

Config file directory: tpnode1, tpnode2, tpnode3

Save config file on your kubernetes nfs storage before create pv, pvc

Do not make any change in conf/plugins.conf

# Change the xchain.yaml config

When you deploy the k8s service , you should change bootnodes ip in config yaml
