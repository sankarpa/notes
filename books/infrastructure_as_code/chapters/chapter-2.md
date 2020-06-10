# Dynamic Infrastructure Platforms

The goal is understand the capabilities, service models available and the requirements a platform must provide to effectively support infrastructure as code. 

## What is Dynamic Infrastructure?
 
A dynamic infrastructure platform is a system that provides computing resources, security, storage and networking  in a way that can be programmatically allocated and managed. 

### Examples of Dynamic Infrastructure platforms

| Types of Platform  | Products or Providers |
| ------------- | ------------- |
| Public Iaas cloud  | AWS , Azure,  Digital Ocean , Rackspace, GCP  |
| Private Iaas cloud   | Cloud stack , Open stack , VMware vSphere  |
| Community Iaas cloud | Cloud services shared between governmental departments|
| Bare metal cloud | Cobbler, Foreman, FAI|

## Requirements for a Dynamic Infrastructure Platforms

Infrastructure as a code is about treating infrastructure as a software system. To aim that the dynamic infrastructure platform should be 

* Programmable
    * An API to interact with the platform programmatically
    ![Infrastructure Platform](/resources/infrastructure_as_platform.png)
* On demand
    * Create or Destroy infra resources quickly
* Self service
    *  Tailor and Customize the resources with their requirements

## Infrastructure resources provided by the platform
  
   ![Resources Provided By Platform](/resources/resources_provided_by_platform.png)
    
   * Compute resources
   * Storage resources
        * Block storage
        * Object Storage
   * Networked File Systems
   * Network Resources
    


