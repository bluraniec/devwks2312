![Intro](/readme/1.png)
# About the LAB
The goal of this lab is to showcase a closed-loop solution in a BGP neighbors’ example. In a stable state, BGP neighbor flaps should not occur frequently. Frequent flaps indicate a problem with Circuit, Hardware, Software or Configuration. We want to monitor these flaps and shutdown the neighbor in case of repeated alarm.  
<img align="center" width=100% src="/readme/2.png"></img>

Upon completion of this lab you, you will be able to:
- Configure Model-Driven Telemetry on Cisco IOS-XR devices 
- Consume data streams from Network Devices using Pipeline
- Store gathered data in a database such as Influx DB
- Visualize data in real-time using Grafana tool
- Create an alert in Grafana to trigger an action in the network
- Change NSO service parameters based on alert using RESTCONF protocol

# Introduction
Cisco Network Services Orchestrator (NSO) is software that enables the delivery of high-quality services faster and more easily through network automation. NSO combined with Model-Driven Telemetry (MDT) allows to create self-healing network capable of performing advanced monitoring and near real-time remedial tasks that usually require human intervention. This offers companies the opportunity to reduce the cost associated with large IT departments and to allocate human resources more strategically, reducing hours spent performing reactive work and focusing on more proactive activities.
 
This session demonstrates how NSO and Model-Driven Telemetry can be used in an environment with virtualized devices running Operating Systems, such as Cisco IOS-XR. Over the lab you will have the opportunity to create and automate a service through NSO and to connect it with open-source telemetry tools that will adjust the service in near real-time.

# Prerequisites
- Basic understanding of Python and Linux
- Basics of SQL language
- Basic understanding of NSO and YANG Data Modeling

<h4 align="center">[1/8]</h4>
<h4 align="center"> <a href="/readme/1.md"> IOS-XR Model-Driven Telemetry :arrow_right: </a> </h4>
