### Project Information:
Project: Velocity Orchestrated Resource
Description: NestedOrchestration Velocity driver for Orchestrated Resource
Category: driver  
Class: Community  
  
This is the Hello-World Velocity Orchestrated Resource device driver. The driver package contains the manifest file  
and a single test case. We encourage you to use the test case's structure (main procedures  
and functional procedures) as a stub for implementing Orchestrated drivers for other devices.  
  
The driver is used with Templates of interface type Orchestration and requires the following Template   
properties:  

* passed_property (The value for this property will be passed down to the driver)  
* instanceId (Variable will be passed back from the driver)
* productId (Variable will be passed back from the driver)

This driver will also require a L2 Switch defined for the template as well as ports based on the default Network Port Template