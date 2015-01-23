# Chapter 1: Introduction

Logging sucks when you have to scale your application. **Logstash** helps logging evolve to be more centralized. Some tools for this already exist, like `rsyslog` and `syslog-ng`. These help move logs to a central location but it’s still hard to sift through the data to retrieve what you are looking for. The next wave of logging applications no long saves logs in a flat file, but instead in more elegent ways. Good bye `grep`.

**Introducing Logstash**

* Provides framework for log collection, centralization, parsing, storage and search
* Free (Apache 2.0)
* Easy to set up, performant, scalable and easy to extend
* Wide variety of inputs and outputs with a large collection of filters at the server level to transform the log events and extract the information needed

**Logstash Design and Architecture**

* Written in JRuby and runs in JVM.
* Message based architecture
* Single agent with several functions that are part of a larger ecosystem:
  * Shipper - sends events to Logstash. Called Lumberjack
  * Broker and indexer - receives and indexes and events
  * Search and storage - pretty straightforward
  * Web UI - Kibana, different library

```scala
def fakeFunction(): Unit = {
    val s = "this is some fake code"
}
```

