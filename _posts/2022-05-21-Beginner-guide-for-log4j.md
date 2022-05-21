---
title: Introduction to log4j 
date: 2022-05-21 19:26:00 +0530
categories: [Software Development, Logging]
tags: [logging]     
---
## History of log4j
As with any enterprise application, logging is important to capture important events of 
the application.Semper's company had created its own logging framework and it made it publicly 
available in 1998. 
Features
API Separation
The API for Log4j is separate from the implementation making it clear for application developers which classes and methods they can use while ensuring forward compatibility. This allows the Log4j team to improve the implementation safely and in a compatible manner.

The Log4j API is a logging facade that may, of course, be used with the Log4j implementation, but may also be used in front of other logging implementations such as Logback. The Log4j API has several advantages over SLF4J:

## Features
Below are features of log4j2:
### API Separation
The API for Log4j is separate from the implementation making it clear for application developers which classes and methods they can use while ensuring forward compatibility. This allows the Log4j team to improve the implementation safely and in a compatible manner.

The Log4j API is a logging facade that may, of course, be used with the Log4j implementation, but may also be used in front of other logging implementations such as Logback. The Log4j API has several advantages over SLF4J:
1. List 1.
2. List 2
3. List 3

### Improved Performance

Log4j 2 contains next-generation Asynchronous Loggers based on the LMAX Disruptor library. In multi-threaded scenarios Asynchronous Loggers have 18 times higher throughput and orders of magnitude lower latency than Log4j 1.x and Logback. See Asynchronous Logging Performance for details. Otherwise, Log4j 2 significantly outperforms Log4j 1.x, Logback and java.util.logging, especially in multi-threaded applications. See Performance for more information.
The Log4j API supports logging Messages instead of just Strings.
### The Log4j API supports lambda expressions.
The Log4j API provides many more logging methods than SLF4J.
In addition to the “parameterized logging” format supported by SLF4J, the Log4j API also supports events using the java.text.MessageFormat syntax as well printf-style messages.

The Log4j API provides a LogManager.shutdown() method. The underlying logging implementation must implement the Terminable interface for the method to have effect.
Other constructs such as Markers, log Levels, and ThreadContext (aka MDC) are fully supported.

Improved Performance
Log4j 2 contains next-generation Asynchronous Loggers based on the LMAX Disruptor library. In multi-threaded scenarios Asynchronous Loggers have 18 times higher throughput and orders of magnitude lower latency than Log4j 1.x and Logback. See Asynchronous Logging Performance for details. Otherwise, Log4j 2 significantly outperforms Log4j 1.x, Logback and java.util.logging, especially in multi-threaded applications. See Performance for more information.
