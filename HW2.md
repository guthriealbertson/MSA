# Homework 2, Gartner Report on Compute Evolution: VMs, Containers, Serverless — Which to Use When?

First this Gartner report lists out some of the important difference, use cases, pros, and cons, of 
virtual machines vs containers. Virtual machines allow the different instances to run fully independent 
of the base machine. Virtual machines must store their own operating system and they run much more independently 
from the base machine and OS. Pros of virtual machines are the abstraction from the base machine, the ability to 
specify the operating system being used, and virtual machines work well with monolithic applications that have strict 
data persistence requirements. Containers are like virtual machines except they don’t store a new operating system for 
each instance, they use the base machines operating system. A container can still store libraries and dependencies. 
Containers allow for a much more lightweight way to run multiple instances on one machine. Containers are lightweight 
and flexible for applications where fast provisioning and scaling are important. 
	
This report also explains the concept of serverless computing, where the developers don’t have to manage infrastructure or 
system architecture. With serverless computing the application is split into functions which are hosted by a service. This 
separated the developer from the runtime environment. Some popular examples listed in the Gartner report are AWS Lambda, Azure 
functions, Google Cloud functions, and Oracle functions. The report than explains the decision-making process behind deciding which 
architecture to use (Virtual machines, Containers, or Faas). Before reading this report, I had base level knowledge and recent knowledge 
from our weekly lectures about the difference between containers and VMs. I had also heard about AWS lambda and understood its purpose in 
a very rudimentary way. Seeing a breakdown of the purpose, pros, and cons, of these different abstractions helped solidify my knowledge of 
these services and understand why they are all still in use today. 

