---
layout:     post
title:      ZooKeeper Page Index
subtitle:   
date:       2020-05-27
author:     Justin Ling Mao
header-img: img/post-bg-ios10.jpg
catalog: 	 true
tags:
    - ZooKeeper
---


## ZooKeeper: Because Coordinating Distributed Systems is a Zoo

ZooKeeper is a high-performance coordination service for
distributed applications.  It exposes common services - such as
naming, configuration management, synchronization, and group
services - in a simple interface so you don't have to write them
from scratch.  You can use it off-the-shelf to implement
consensus, group management, leader election, and presence
protocols. And you can build on it for your own, specific needs.

The following documents describe concepts and procedures to get
you started using ZooKeeper. If you have more questions, please
ask the [mailing list](http://zookeeper.apache.org/mailing_lists.html) or browse the
archives.

+ **ZooKeeper Overview**
    Technical Overview Documents for Client Developers, Administrators, and Contributors
    + [Overview](zookeeperOver.html) - a bird's eye view of ZooKeeper, including design concepts and architecture
    + [Getting Started](zookeeperStarted.html) - a tutorial-style guide for developers to install, run, and program to ZooKeeper
    + [Release Notes](releasenotes.html) - new developer and user facing features, improvements, and incompatibilities
+ **Developers**
    Documents for Developers using the ZooKeeper Client API
    + [API Docs](api/index.html) - the technical reference to ZooKeeper Client APIs
    + [Programmer's Guide](zookeeperProgrammers.html) - a client application developer's guide to ZooKeeper
    + [ZooKeeper Use Cases](zookeeperUseCases.html) - a series of use cases using the ZooKeeper.
    + [ZooKeeper Java Example](javaExample.html) - a simple Zookeeper client application, written in Java
    + [Barrier and Queue Tutorial](zookeeperTutorial.html) - sample implementations of barriers and queues
    + [ZooKeeper Recipes](recipes.html) - higher level solutions to common problems in distributed applications
+ **Administrators & Operators**
    Documents for Administrators and Operations Engineers of ZooKeeper Deployments
    + [Administrator's Guide](zookeeperAdmin.html) - a guide for system administrators and anyone else who might deploy ZooKeeper
    + [Quota Guide](zookeeperQuotas.html) - a guide for system administrators on Quotas in ZooKeeper.
    + [JMX](zookeeperJMX.html) - how to enable JMX in ZooKeeper
    + [Hierarchical quorums](zookeeperHierarchicalQuorums.html)
    + [Observers](zookeeperObservers.html) - non-voting ensemble members that easily improve ZooKeeper's scalability
    + [Dynamic Reconfiguration](zookeeperReconfig.html) - a guide on how to use dynamic reconfiguration in ZooKeeper
    + [ZooKeeper CLI](zookeeperCLI.html) - a guide on how to use the ZooKeeper command line interface
    + [ZooKeeper Tools](zookeeperTools.html) - a guide on how to use a series of tools for ZooKeeper
    + [ZooKeeper Monitor](zookeeperMonitor.html) - a guide on how to monitor the ZooKeeper
    + [Audit Logging](zookeeperAuditLogs.html) - a guide on how to configure audit logs in ZooKeeper Server and what contents are logged.
+ **Contributors**
    Documents for Developers Contributing to the ZooKeeper Open Source Project
    + [ZooKeeper Internals](zookeeperInternals.html) - assorted topics on the inner workings of ZooKeeper
+ **Miscellaneous ZooKeeper Documentation**
    + [Wiki](https://cwiki.apache.org/confluence/display/ZOOKEEPER)
    + [FAQ](https://cwiki.apache.org/confluence/display/ZOOKEEPER/FAQ)