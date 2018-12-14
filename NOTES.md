# Zookeeper build notes

## Docker with dynamic reconfig

* Will require zookeeper 3.5 minimum: https://zookeeper.apache.org/doc/r3.5.3-beta/zookeeperReconfig.html
* Need to research state management and ECS - can it be all stateless with zookepper?
* Another old article https://container-solutions.com/dynamic-zookeeper-cluster-with-docker/
* Mounting volumes to preserve configurations between docker container restarts

