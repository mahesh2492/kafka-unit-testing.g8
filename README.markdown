A [Giter8][g8] template for Sample application of Kafka Producer and Consumer and its unit testing using Embedded Kafka.

**KAFKA-UNIT-TESTING**

A basic application to show use case of kafka producer and consumer, and to demonstrate unit testing of kafka using Embedded Kafka.
EmbeddedKafka is a library which gives us flexibility to unit test kafka. It will run zookeeper and kafka server itself before the test and stop it after test. For more info [refer](https://blog.knoldus.com/2017/07/09/unit-testing-of-kafka/)


**How to setup ?**

**1) Clone the application**

` sbt new mahesh2492/kafka-unit-testing.g8`

**2) Compile the application**

`cd kafka-unit-testing`

 `sbt clean compile `
 
 **3) Test the application**
 
 ` sbt clean test`


Template license
----------------
Written in 2018 by <Mahesh Chand> <mahesh.kndpl@gmail.com>

To the extent possible under law, the author(s) have dedicated all copyright and related
and neighboring rights to this template to the public domain worldwide.
This template is distributed without any warranty. See <http://creativecommons.org/publicdomain/zero/1.0/>.

[g8]: http://www.foundweekends.org/giter8/
