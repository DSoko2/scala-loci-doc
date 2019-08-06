---
layout: default
title: Introduction
nav_order: 1
permalink: /
has_toc: true
---
# ScalaLoci

This site serves as an introduction into [ScalaLoci](https://scala-loci.github.io/) and the concepts behind it. The target audience are developers, who want to use ScalaLoci as well as those that want to get a brief overview.

ScalaLoci is a multitier distributed programming language based on Scala. It allows users to write distributed applications as if they were one single application. ScalaLoci automatically splits the code across the different compile targets (currently JVM applications as well as JavaScript web-applications are supported) and takes care of the networking logic.
 
Multitier programming in ScalaLoci enables reasoning about distributed data flows, while the underlying placement type system keeps the distribution of code clear to the developer. In contrast to many other multitier languages, ScalaLoci supports user-defined, complex topologies between the nodes in the system. Thereby, it abstracts over the details of network communication and takes the pain of moving data and function calls between processes from the developer. Moreover, proper separation of functionalities in the distributed system is enabled through modularization of the multitier code without enforcing these borders at the communication points as common in today's programs. ScalaLoci aims for easier and more joyful development of distributed systems by making it as simple as writing non-distributed programs.


To get started using ScalaLoci, have a look at the [Getting Started](howtos/getting_started) section or look at one of the example applications on [Github](https://github.com/scala-loci/examples-simple).

This documentation is available as website at [https://scala-loci.github.io/doc/](https://scala-loci.github.io/doc/).