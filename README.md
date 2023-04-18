![Thunderbolt logo](/tblogosm.png "Thunderbolt")
# Thunderbolt-Java
A High Performance MultiProtocol Java Framework

## 1.About
  Thunderbolt-Java is a complete Enterprise grade IOT ready framework which is designed to be lightweight, multiprotocol and database friendly with high throughput performance. 
  
  Thunderbolt-Java is designed with a philosophy aimed at reducing coding effort for programmers.
  
  Thunderbolt-Java is compiled framework with very low usage of Java reflection , aop etc to mitigate performance snarls. 
  
  Thunderbolt-Java supports the following Protocols in unsecured and secured(TLS/DTLS) services
  
  1. Http/Https
  2. Mqtt/Mqtts
  3. COAP/COAPs

## 2.Main Components
### 1. Thunderbolt Framework core
    This is the parent core which is aimed at replacing lombok fashioned annotated Pojos,
    Scheduled services,NioWrappers , compiler utilities etc.
### 2. Thunderbolt Application core
    The main Application loader with Annotated configuration support
### 3. Thunderbolt Web/Websockets
    Rest and Static web services framework
### 4. Thunderbolt Data (jdbc/mongo/redis)
    Data connectors , repositories on SQL over JDBC / NoSQL over Mongo or Redis
### 5. Thunderbolt Eventbus(Stateless IOT Broker over mqtt/coap/websockets)
    Stateless enhanced queue based broker which has
    a. Protocol Bridge to bridge messages between MQTT COAP and WebSockets without 
	   the need for addtional glue code
    b. Standalone Clusterable COAP,MQTT and Websocket services
### 6. Thunderbolt maven plugin (one plugin to do build and package)
    A huge leap in plugin development in which one plugin can has the following features
    a. Compile /TestCompile
    b. Jar/TestJar/Executable/FatJar
    c. Application Assemble
### 7. Thunderbolt Plugin Framework for applications
	A high performance replacement for OSGI for One JVM multiple microservices philosophy
	aimed at zero service downtime deployments
### 8. Thunderbolt Discovery and Clustering Services 
	A peer to peer clustering service and service discovery

