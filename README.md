# LIBRARY-MANAGEMENT-SYSTEM
A project done using java with 3 tier architecture

# RMI in Java

RMI stands for Remote Method Invocation. It is a mechanism that allows an object residing in one system (JVM) to access/invoke an object running on another JVM.
RMI is used to build distributed applications; it provides remote communication between Java programs. It is provided in the package java.rmi.

## Architecture of an RMI Application
In an RMI application, we write two programs, a server program (resides on the server) and a client program (resides on the client).
Inside the server program, a remote object is created and reference of that object is made available for the client (using the registry).
The client program requests the remote objects on the server and tries to invoke its methods.

## OBJECTIVES
This project develops a complete scalable library management system that enables the management to organise, issue and maintaing records in a systematic, efficient and non-manual manner. 
