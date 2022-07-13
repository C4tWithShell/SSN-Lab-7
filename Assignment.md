**Firewall & Intrusion Detection Systems**

Select Snort, Suricata or Zeek as your IDS/IPS of your choice. 

Create an small network of three VMs. 1 attacker, 1 Server and 1 as IDS/IPS. The remaining part of the topology is of your selection. 

Install and configure IDS/IPS on its specific vm and update its signatures/rules if required. 

1. Create a policy/rule to block all incoming ping packets.
2. Verify that newly created rule/policy can correclty detect and block incoming ping packets from attacker machine.
3. Write 5 more rules/policies of your own that can detect different attacks ( possible attacks). 
4. Show the new 5 rules and explain how the attacks would work and how the rule/policy would be able to detect it.
5. Describe how you triggered the alert for all newly created rules.
6. Attach the alert itself for each given rule/policy to the report in readable text.
7. Create one rule/policy which would be triggered if a server vm / IDS/IPS vm would browse to microsoft.com website.
8. Answer the following questions:
   1. What is a zero-day attack?
   2. Can IDS/IPS detect zero-day attack? if yes why? if no why?
   3. Given a network that has 1 million connections daily where 0.1% are attacks. If the IDS has a true positive rate of 95% what false positive alarm rate do we need to achieve to ensure the probability of an attack, given an alarm is 95%?



Happy Defending!