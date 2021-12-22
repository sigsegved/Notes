### Staff level expectation 
* Be able to understand the problem and clarify requirements to define a minimum viable product and setup the scope and goals.
* Be able to articulate trade offs in every design component clearly and justify the reasoning behind the option you picked. Especially in the following areas
    * data store - sql vs nosql, why and what kind is the best. 
    * cache - where to use cache and why
    * eventual vs strong consistency of data and what is the right choice for the system under design 
    * docker, kubernetes vs ec2 - how to best host the service. 
    * load balancer and sharding approach, what to shard on and why. 
* Spend time talking about the capacity and scale of the system. RPS, BPS, fleet size etc. Address scalability part of the system, vertical and horizontal scaling.
* Be able to talk about various points of failures and how to mitigate such failures.
* Talk about monitoring the system and how to measure performance and other operational indicators. 
### Questions
* Design a system that can serialize an object into XML and then deserialize it to reconstruct the object back. #oracle
* Design an API Rate limiter #oracle  (solution : refer educative.io)
    * Interviewer didnt like that i used a stateless system. Make sure to specifiy how you can persist the rate data for recovery if needed. 
* Design tiny url system #oracle (solution : refer educative.io) 
* Design airbnb experience system. Given a host can host one or more experience (ex: painting class or cooking class) on a regular interval, create a system which will allow customers to search and book available experiences up to 2 years in advance. #airbnb
* Design a wallet system for airbnb where customers can keep cash and use that to pay for airbnb bookings. How would you handle asynchronous future payment. #airbnb 
* Design an online battleship game service. #google
* Design distributed hash table that a crawler will use to keep track of links that needs to be visited. #google
* Design an identity service (resource level role access) for enforcing varies policies inside an organization. Service should allow adminstrator to add/edit/delete policies. #stripe 
* Given access to a single VM (3 Ghz, 16 GB RAM, 5 Gbps internet, 1TB SSD) and 1000 bots (devices like mobile phone, alexa etc), design a mechanism to replicate wikipedia in the VM. System should also make sure the replicated content stays up to date when the page gets an update. #lyft 
* #microsoft's design question were specific to the team. Intune's policy engine processes millions of devices and evaluates compliance. What are some strategies you can use to make sure you prioritize the right devices for compliance evaluation? 

### Leadership Expectation
* Demonstrate scope spanning multiple teams, being able to work with multiple stake holders. This is the key part, lot of recruiters will try to down level. Be upfront and talk to them about levels and what level you want to interview for. Convince yourself where you want to be and work towards that. Ask counter questions to the HM and recruiter about the scope of their staff role. For example Google L6 role (Staff) scope is equivalent to Amazon's L6 role. Mostly confined to a single team, seldom going cross team yet they will try to hire an Amazon L6 as L5. So stand your ground and push for the level you want before you setup the interviews. 
* Demonstrate that you can manage expectation with the leadership
* Demonstrate strong mentorship and setting up processes to bring up the best practices to the team as well as help them grow
* Have strong examples of working with hostile/not-so-great people and how you handled it
* How do you provide and take feedback, both constructive and critial feedback. 


--------


