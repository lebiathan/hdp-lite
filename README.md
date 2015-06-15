# hdp-lite

@Author: George Valkanas (aka lebiathan)

@Date: 15 June 2015

A light version of hadoop (name inspired by sql-lite), for parallel / distributed processing on a single machine or more. Unlike Apache Hadoop, hdp-lite does not require infrastructure setup, only the inclusion of a single jar file in the classpath, and has direct access to the underlying file system.
On the downside, it does not offer fault-tolerance, and certain things need to be manually performed (version 1.0), e.g., manually copy files when working in a distributed setting. Setting up the execution workflow also depends on the implemented application, but hdp-lite provides the necessary tools to easily set the workflow up, and process the data.
