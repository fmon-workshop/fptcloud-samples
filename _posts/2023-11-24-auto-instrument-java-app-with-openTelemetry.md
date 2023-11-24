# Intro

OpenTelemetry stands at the forefront of modern observability practices, revolutionizing how developers gain insights into their applications' performance and behavior. As a powerful distributed tracing framework, it empowers engineers to effortlessly instrument their applications, providing comprehensive visibility into the intricacies of microservices architectures.

# Instrumenting a sample Java app for traces

In this section, you will learn to instrument a Java application with OpenTelemetry to get traces.

## Prerequisite

- A FPT Smart Cloud account
- Java 8 or newer (full JDK, not a JRE)
- OpenTelemetry Jar agent, latest version.

## Install the OpenTelemetry Jar agent


To instrument your Java application, the OpenTelemetry Java Jar agent will be utilized. The JAR agent can be attached to any Java 8+ application. It can detect a number of popular libraries and frameworks and instrument them right out of the box. You don't need to add any code for that.

To download the Java Jar agent, run the below command in your terminal:

```sh
wget https://github.com/open-telemetry/opentelemetry-java-instrumentation/releases/latest/download/opentelemetry-javaagent.jar
```

## Set up the Java application

