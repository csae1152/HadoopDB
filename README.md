# HadoopDB
MapReduce and DBMS - Working together for Analytical Workload

Abstract
========

Many enterprises are shifting away from deploying their analytical databases on high-propietary machines, and moving towards cheaper, lower-end, commodity hardware, typically arranged in a shared-nothing MPP architecture.

There tend to be two schools of thought regarding what technology to use for big data analysis. Proponents of parallel databases argue that the strong emphasis on performance and efficiency of parallel databases make them well suited to perform such analysis.

Introduction
============

The analytical database market currently consists of $4 billion of the $15 billion database software market.

HadoopDB tries to melt together both worlds: The relational approach and the Map Reduce approach.

We are aware of that classical Hadoop is a batch oriented technology.

Parallel databases have been proven to scale really well into the tens of nodes (near linear scalability is not common). However, there are very few known parallel database deployments consisting of more than hundred nodes.

MapReduce
==========

MapReduce was introduced by Dean et. in 2004.

MapReduce processes data distributed (and replicated) across many nodes in a shared-nothing cluster via three basic operations. First, a set of Map tasks are processed in parallel by each node in the cluster without communicating with other nodes. Next, data is repartioned across all nodes of the cluster.


