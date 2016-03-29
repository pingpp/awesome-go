# Awesome Go

A curated list of awesome Go frameworks, libraries and software

### Contents

- [Awesome Go](#awesome-go)
    
    - [Distributed Systems](#Distributed Systems)
    - [Configuration](#configuration)
    - [DB](#db)
       - [orm](#orm)
       - [ping++](#ping++)
    - [Logging](#Logging)
    - [mq](#mq)
    - [im](#im)
    - [cloud](#cloud)

- [Tools](#tools)
    - [Package Management](#Package Management)

- [Server Applications](#server-applications)

- [Resources](#resources)
    - [Coding Standard](code-standard)

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [protorpc](https://github.com/chai2010/protorpc) - Google Protocol Protobufs RPC for Go.
* [proto_http_rpc](https://github.com/Terry-Mao/protorpc) - golang gogoprotobuf rpc based net/http.
* [etcd](https://github.com/coreos/etcd) - Distributed reliable key-value store for the most critical data of a distributed system https://coreos.com/etcd/docs/latest/
* [raft](https://github.com/coreos/etcd/tree/master/raft) - Raft is a protocol with which a cluster of nodes can maintain a replicated state machine.
* [zookeeper](http://zookeeper.apache.org/) - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.

## Configuration

*Libraries for configuration parsing*

* [yaml](https://github.com/go-yaml/yaml) - YAML support for the Go language.
* [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul

## db



## Logging(待整理)

*Libraries for generating and working with log files.*

* [glog](https://github.com/golang/glog) - Leveled execution logs for Go.
* [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.
* [go-log](https://github.com/ian-kent/go-log) - A log4j implementation in Go.
* [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers.
* [gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Cosole, Simple Console, File or Elasticsearch.
* [log](https://github.com/apex/log) - Structured logging package for Go.
* [log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang.
* [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go
* [logex](https://github.com/chzyer/logex) - An golang log lib, supports tracking and level, wrap by standard log lib
* [logger](https://github.com/azer/logger) - Minimalistic logging library for Go.
* [logrus](https://github.com/Sirupsen/logrus) - a structured logger for Go.
* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).
* [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger.
* [logxi](https://github.com/mgutz/logxi) - A 12-factor app logger that is fast and makes you happy.
* [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser.
* [mlog](https://github.com/jbrodriguez/mlog) - A simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
* [seelog](https://github.com/cihub/seelog) -   logging functionality with flexible dispatching, filtering, and formatting.
* [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
* [tail](https://github.com/hpcloud/tail) - A Go package striving to emulate the features of the BSD tail program.
* [xlog](https://github.com/rs/xlog) - A structured logger for `net/context` aware HTTP handlers with flexible dispatching.

## mq

* [kafka](http://kafka.apache.org/) - A high-throughput distributed messaging system.
* [kafka client](https://github.com/Shopify/sarama) - Sarama is a Go library for Apache Kafka 0.8 and 0.9 https://shopify.github.io/sarama
* [Kafka Load-balancing client](https://github.com/wvanbergen/kafka)
* [NSQ](https://github.com/nsqio/nsq) - A realtime distributed messaging platform http://nsq.io/
* [nsq client](https://github.com/nsqio/go-nsq) - The official Go package for NSQ

## im

* [goim](https://github.com/Terry-Mao/goim) 
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - Golang push server cluster

## cloud

* [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google http://kubernetes.io
* [glusterfs](https://github.com/gluster/glusterfs) - Gluster Filesystem - (this is only a public mirror, see the README for contributing) https://gluster.org
* [rkt](https://github.com/coreos/rkt) - rkt is an App Container runtime for Linux
* [docker](https://github.com/docker/docker) - Docker - the open-source application container engine http://www.docker.com

# tools

## Package Management

*Libraries for package and dependency management.*

* [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.


# resources

## code-standard

* [effective_go](https://golang.org/doc/effective_go.html) - Effective Go
* [CodeReviewComments](https://github.com/golang/go/wiki/CodeReviewComments) - This page collects common comments made during reviews of Go code

