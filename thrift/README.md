Thrift
==========================================================
finatra-thrift is a library for building Thrift services with Finatra.

Quick Start
-----------------------------------------------------------
* Depend on the `com.twitter.finatra:finatra-thrift` library.
* We recommend depending on `com.twitter.finatra:finatra-slf4j` and `ch.qos.logback:logback-classic` to choose [Logback](https://logback.qos.ch/) as your [slf4j](https://www.slf4j.org/manual.html) implementation.
* Take a look at our [examples.](../examples/)


We highly recommend taking a look at our [User Guide](https://twitter.github.io/finatra/user-guide/) for more information on getting started building services with Finatra.

Note:
-----------------------------------------------------------
Classes/objects in internal packages, e.g. `com.twitter.finatra.thrift.internal.*` are Finatra framework internal implementation details.
These are meant to be private to the framework and not intended as publicly accessible as they are details specific to the framework and
are thus more subject to breaking changes. You should not depend on their implementations remaining constant since they are not intended
for use outside of the framework itself.
