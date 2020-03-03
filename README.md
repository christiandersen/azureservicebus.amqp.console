# azureservicebus.amqp.console
#Using Microsoft Azure Service Bus with the AMQP.NET Lite library#
##Small .NET Core 3.1 console program to evaluate how it is using the Microsoft Azure Service Bus with the AMQP .NET Lite library.##

I am working on a project where we need to decoupled the implementation of the service bus, to the specific service bus interface implementation. This to meet current technology and future technology requirements. We are trying to keep the technology stack low and currently have 2 implementations og Message Queue Services that our systems targets. During the analysis we found that a standard has been developed for Message Queue Service Bus Messaging. The standard is called Advanced Message Queuing Protocol (AMQP). Several implementations exists for this standard. For our .NET implementation we will use AMQP.Net Lite to reach these implementations to make sure that we are implementation independant.

We already have our project running with, Active MQ, Active MQ - Artemis, and Rabbit MQ. Now this is what it takes to make it run with Azure Service Bus.

We will use C# .NET Core 3.1 for this example.

Lets do it!

##Prerequisites:##

.Net Core 3.1 SDK installed.

Editor ( i used Visual Studio Code)
