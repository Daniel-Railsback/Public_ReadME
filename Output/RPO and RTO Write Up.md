What is RPO

RPO stands for Recovery Point Objective. 
This is a buzz word way of asking how much data is OK to lose during a failover caused by an outage.   The shorter the RPO the less data can be lost.  


## Here are two examples: 


##### DR for AVD
RPO for AVD may be high as many document files MAY not be critical for to continue working.  This type of work MAY not build on previous work meaning it is easy for users to continue working if they have a safe place to be productive. 



##### DR for MMO
An MMO's RPO goal will be zero. This doesn't mean there can’t be any downtime; it means players should not lose progress or items due to an outage. For instance, if the server goes down right after a player rolls on the rare item table for a reward from slaying a boss, when the server comes back online, they should still see that item in their inventory.


##### What is RTO

RTO or Recovery Time Objective is how fast the service will take to roll over to DR.  
RTO is a term used when building out DR plans to ensure the objedtives are clear. 



## Here are two examples: 


##### DR for AVD
RTO for AVD may be a short time due to the amount of users and critical work flow. When these users are not working, the business is losing money. A possibility here might be an RTO of 1 hour.  This means that within an our of an outage being declared services must be restored.  


##### DR for MMO
An MMO's RTO can be a bit more flexible.  Servers taking an online video game results in users being annoyed but not in danger. An MMO


