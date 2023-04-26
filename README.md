# Incident Response Basics

## Incident Response Lifecycle
![IR](https://user-images.githubusercontent.com/111991325/234446445-4cc85e7a-985b-4811-a963-2e4db4cd611b.png)

### 1. Preparation
- To prepare for incidents, compile a list of IT assets such as networks, servers and endpoints, identifying their importance and which ones are critical or hold sensitive data. 
- Set up monitoring so you have a baseline of normal activity. 
- Determine which types of security events should be investigated, and create detailed response steps for common types of incidents.


### 2. Detection and Analysis
- Detection involves collecting data from IT systems, security tools, publicly available information and people inside and outside the organization, and identifying precursors (signs that an incident may happen in the future) and indicators (data showing that an attack has happened or is happening now).
- Analysis involves identifying a baseline or normal activity for the affected systems, correlating related events and seeing if and how they deviate from normal behavior.


### 3. Containment, Eradication, and Recovery
- The goal of containment is to stop the attack before it overwhelms resources or causes damage. 
- Your containment strategy will depend on the level of damage the incident can cause, the need to keep critical services available to employees and customers, and the duration of the solution—a temporary solution for a few hours, days or weeks, or a permanent solution. 
- It is important to identify the attacking host and validate its IP address. This allows you to block communication from the attacker and also identify the threat actor to understand their mode of operation, search for and block other communication channels they may be using.

- In the eradication and recovery stage, after the incident has been successfully contained, you should act to remove all elements of the incident from the environment. This might include identifying all affected hosts, removing malware, and closing or resetting passwords for breached user accounts.

- Finally, once the threat is eradicated, restore systems and recover normal operations as quickly as possible, taking steps to ensure the same assets are not attacked again.

### 4. Post-Incident Activity
- A central part of the NIST incident response methodology is learning from previous incidents to improve the process.

You should ask, investigate and document the answers to the following questions:

- What happened, and at what times?
- How well did the incident response team deal with the incident? Were processes followed, and were they sufficient?
- What information was needed sooner?
- Were any wrong actions taken that caused damage or inhibited recovery?
- What could staff do differently next time if the same incident occurred?
- Could staff have shared information better with other organizations or other departments?
- Have we learned ways to prevent similar incidents in the future?
- Have we discovered new precursors or indicators of similar incidents to watch for in the future?
- What additional tools or resources are needed to help prevent or mitigate similar incidents?
Use your findings to improve the process, adjust your incident response policy, plan, and procedures, and feed the new data into the preparation stage of your incident response process.



## Incident Response Framework 

1. Containment: Immediately isolate the affected system(s) from the network to prevent further damage or loss of data.
2. Analysis: Gather as much information as possible about the incident, including the type of attack, the affected systems, and the potential impact on the organization.
3. Eradication: Remove the malware or other malicious code from the affected systems and restore them to their previous state.
4. Recovery: Restore data and systems that were affected by the incident.
5. Lessons learned: Conduct a post-mortem analysis of the incident to identify areas for improvement and develop a plan for preventing similar incidents in the future.


## Best Practice for Building Your Incident Response Plan
- Create a simple, well-defined process.
- Create a communication strategy.
- Use an incident response plan temaplte - prevent reinventing the wheel and provides quick reaction time.
- Test your incident response plan - conduct realistic drills, exercises, and test detection tools/controls.
- Use a centralized approach - minimize the amount of logging in to multiple tools aqnd correlating information between them. 
