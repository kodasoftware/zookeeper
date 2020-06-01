# Zookeeper

This project provides a deployment manifest for Zookeeper into Kubernetes. The source was originally from the official
[Kubernetes tutorial](https://kubernetes.io/docs/tutorials/stateful-application/zookeeper/). Zookeeper provides a
distributed co-ordination system and ultimately for Sauce we use this to provide a highly available file-system with a
co-ordinated leader for write operations and multiple read-only followers. See the official
[Apache Zookeeper](https://zookeeper.apache.org/) website for more information about how Zookeeper works.
