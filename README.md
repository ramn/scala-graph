# Graph for Scala
Graph for Scala is intended to provide basic graph functionality seamlessly 
fitting into the Scala Collection Library. Like the well known members of 
`scala.collection`, Graph for Scala is an in-memory graph library aiming at 
editing and traversing graphs, finding cycles etc. in a user-friendly way. 
Besides ready-to-go implementations of JSON-Import/-Export and Dot-Export, 
more popular graph formats, mirroring of graph databases as well as distributed 
processing are due to be supported.

Graph for Scala was originally planned to move from here to the Scala Extended 
Core Library, a new facility to be launched sometime later by the Scala Core Team. 
Until then, use this Scala Incubator site to read up on Graph for Scala.
To download the latest release `1.6.0` of the core module, SBT users will have to add

```
libraryDependencies += "com.assembla.scala-incubator" % "graph-core_2.10" % "1.6.0"
```

As a Maven user, please set 

```
group id          com.assembla.scala-incubator
artifact id       graph-core_2.10
version           1.6.0
```

For a direct download you may select the required artifacts including the executable JARs,
Scaladoc and sources [here](https://oss.sonatype.org/content/repositories/releases/com/assembla/scala-incubator/).

Any feedback is appreciated. You are also welcome as a co-contributor.

Have fun with Graph for Scala.

Peter