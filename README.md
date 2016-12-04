#Security Documentation and Threat Modelling Tool for Java
##Secuirty Now
In my understanding thoughts also have evolution. By influencing each other with any form of communication thoughts have also changed. These changes are viable or non-viable in a certain space and time. Security is a subjective definition (it is much more a feeling) that has transformed and evovled in the last few decades.
I beleive that this is the time when Security entered the next level. Indistry is not ignoring the fact that there are cyber-threats any more and lately stopped whining and focused on the security in a professional point of view. The days of security peddlers and showmen are nearly over and a new era with more professional and pragramatic approach will rise.
This project would like to aid this transformation in a form code building on the foundation of OWASP which is one the most important initiatives that helped this evolution.
##Sources and Inspiraion
This is an initial document which collects inspirational information and definitions focused on the area of threat modelling. Most of the quotes are originated from OWASP pages.
#Quotes and Memos
##'evil user stories'
The process is essentially the same at different levels of abstraction, although the information gets more and more granular throughout the lifecycle. Ideally, a high-level threat model should be defined in the concept or planning phase, and then refined throughout the lifecycle. As more details are added to the system, new attack vectors are created and exposed. The ongoing threat modeling process should examine, diagnose, and address these threats.

##Outline of a generic methodology for Threat Modeling:

###Assessment Scope
The first step is always to understand what's on the line. Identifying tangible assets, like databases of information or sensitive files is usually easy. Understanding the capabilities provided by the application and valuing them is more difficult. Less concrete things, such as reputation and goodwill are the most difficult to measure, but are often the most critical.
###Identify Threat Agents and possible Attacks
A key part of the threat model is a characterization of the different groups of people who might be able to attack your application. These groups should include insiders and outsiders, performing both inadvertent mistakes and malicious attacks.
###Understand existing Countermeasures
The model must include the existing countermeasures
###Identify exploitable Vulnerabilities
Once you have an understanding of the security in the application, you can then analyze for new vulnerabilities. The search is for vulnerabilities that connect the possible attacks you've identified to the negative consequences you've identified.
###Prioritized identified risks
Prioritization is everything in threat modeling, as there are always lots of risks that simply don't rate any attention. For each threat, you estimate a number of likelihood and impact factors to determine an overall risk or severity level.
###Identify Countermeasures to reduce threat
The last step is to identify countermeasures to reduce the risk to acceptable levels.

Levels \ Steps of Evaluation#N	| Scopes |	Models |	Agents |	Vulnerabilities |	History |	Impact |	Response
------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
Re(quirements)							|||||||
De(sign)|||||||
Im(plementation)|||||||
Ve(rification)|||||||
Va(lidation)|||||||
Op(eration)|||||||
Re(peat)|||||||

##Final Thoughts
Beware threat modeling processes that are inefficient about pruning the search space of possible threats to eliminate threats that are very unlikely or have minimal impact.There is no "right" way to evaluate the search space of possible threats. But there are "wrong" ways. Attempting to evaluate all the possible combinations of threat agent, attack, vulnerability, and impact is a waste of time and effort.The process of exploring the search space is iterative and constantly refined based on what you have done so far.  So, for example, starting with all possible vulnerabilities is usually pointless, as most of them are not attackable by the threat agents, protected by a safeguard, or do not lead to a conseequence.

##Inspiration
https://github.com/csikosbalint/seasponge \\
https://github.com/csikosbalint/threatmodel-sdk/
