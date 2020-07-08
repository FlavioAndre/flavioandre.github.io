---

title:  JDK 15 - The new features in Java Open JDK 15

description:  Let's see what's new in java open jdk version 15, feature text blocks, garbage collectors, hidden classes.

og-image:  java.jpg
---

The new features in Java [Open JDK 15](https://openjdk.java.net/projects/jdk/15/) next version of Java SE on June 11:

<!--more-->

![Java]({{ site.url }}/img/java.jpg)

- A preview of [sealed classes](https://openjdk.java.net/jeps/360). Along with interfaces, sealed classes restrict which other classes or interfaces may extend or implement them.  - A second incubator of a [foreign-memory access API](https://openjdk.java.net/jeps/383).
 - Cryptographic signatures based on the [Edwards-Curve Digital Signature Algorithm (EdDSA)](https://openjdk.java.net/jeps/339).
 - [Reimplementing the legacy DatagramSocket API](https://openjdk.java.net/jeps/373) by replacing the underlying implementations of the `java.net.datagram.Socket` and `java.net.MulticastSocket`.
 - A second preview of [pattern matching for  `instanceof`](https://openjdk.java.net/jeps/375), following a previous preview in [JDK 14](https://www.infoworld.com/article/3436795/jdk-14-the-new-features-in-java-14.html).
- [Disabling biased locking](https://openjdk.java.net/jeps/374) by default and deprecating all related command-line options.
 - Hidden classes.
 - The [ZGC: A Scalable Low-Latency Garbage Collector](https://openjdk.java.net/jeps/377) ([ZGC](https://openjdk.java.net/jeps/377)) would graduate from an experimental feature to a product under this proposal. Integrated into JDK 11, which arrived in September 2018, ZGC is a scalable, low-latency garbage collector.
 - Text blocks.
 - The Shenandoah low-pause-time garbage collectorwould become a production feature and move out of the experimental stage.
 - Removal of Nashorn.
 - [Deprecation of the RMI Activation mechanism](https://openjdk.java.net/jeps/385), for future removal.
  
