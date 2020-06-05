#Chapter 1 - Challenges and Principles
                                     
Infrastructure as code is an approach to infrastructure automation based on practices from software development. It emphasizes consistent, repeatable routines for provisioning and changing systems and their configuration. Changes are made to definitions and then rolled out to systems through unattended processes that include thorough validation.
                    
##Goals of Infrastructure as Code
* Supports and enables change, rather than being an obstacle  or a constraint.
* Changes to system are routine without stress or drama to IT staff
* Enables IT staff to spend their time in valuable things that engage their abilities, not on routine, repetitive tasks.
* Users are able to define,  provision  and manage the resources they need without needing IT staff 
* Teams are able to easily  and quickly recover from the failures rather than assuming failures can be completely prevented.
* Improvements are made continuously , rather than done through expensive and risky big bang projects. 
* Solutions to problems proven through implementing , testing and measuring them , rather than by discussing them in meetings and documents. 

Infrastructure as a code  has come into its own with the cloud , because it's difficult to manage servers in the cloud well without it. Infrastructure as a code is not just for cloud but can be applied to the physical infrastructure. 

```Dynamic Infrastructure - The ability to create and destroy servers programmatically.```

##Challenges with Dynamic Infrastructure
* Server sprawl 
* Configuration Drift
* Snowflake servers
* Fragile Infrastructure
* Automation Fear Spiral
* Erosion

![Automation Fear](/resources/automation-fear-spiral.png)

##Principles of Infrastructure as code
* Systems to be easily reproducible 
* Systems are Disposable 
* Treat your servers like cattles, not pets
* Systems are consistent
* Process are repeatable
* Design is always changing

## Practices
* Use Definition Files
* Self documented systems and process
* Version all the things for 
* Traceability
* Rollback
* Visibility
* Correlation 
* Actionability
* Continuously test systems and process
* Small changes rather than batches
* Keep services available continuously
* Continuous Improvement to make the infra anti fragile
