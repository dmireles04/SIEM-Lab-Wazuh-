<h1>SIEM Dashboard and Capabilities</h1>

<h2>Description</h2>
I created this home lab with open-sourced software to showcase my experience with SIEM configuration and analysis.
<br />


<h2>Utilities and Environments Used</h2>

<br />
<b>Akamai - formerly Linode</b>
- <img src="https://imgur.com/bk8SsMb.png" height="40%" width="40%" alt="Akamai"/>
<br />
<b>Linux - Ubuntu</b>
- <img src="https://imgur.com/GFONWKH.png" height="40%" width="40%" alt="Linux -Ubuntu"/>
<br />
<b>Wazuh</b>
- <img src="https://imgur.com/lP5Yd0N.png" height="40%" width="40%" alt="Wazuh"/>
<br />
<b>Windows 10</b> (21H2)
<br />
<br />
<br />
<h2>Program walk-through:</h2>

<p align="Left">
<b>Wazuh Dashboard - Main:<b> <br/>
<br /> 
- This dashboard allows the user to see the list of "agents" that have been added for monitoring
<br />
- The agent shown here, and all subsequent screen shots are from my own test device and actual event items that I have documented while setting this up in my test environment
<img src="https://imgur.com/rWG2ysv.png" height="120%" width="120%" alt="SIEM Dashboard and Capabilities"/>
<br />
<br />
<br />
<b>Wazuh Dashboard - <b>
<b>Agent Specific Dashboard:<b>  <br/>
<br />
- This "agent-specific" dashboard offers a high-level view and summary of that agent's MITRE, Compliance*, FIM, SCA, and # of events
<br />
- The compliance section shown in this image , highlights PCI DSS related items, however, other compliance options include: GDPR, NIST 800-53, HIPPA, GPG13, TSC
<img src="https://imgur.com/pexgaFG.png" height="100%" width="100%" alt="SIEM Dashboard and Capabilities"/>
<br />
<br />
<br />
<b>Wazuh Dashboard -<b>
<b>Sample PCI DSS Compliance Alert and Rule Explanation:<b> <br/>
<br />
- Here I demonstrate the ability to sort by compliance requirements, and then highlight the additional details and explanation regarding that specific rule/requirement
<br />
<img src="https://imgur.com/5X8RpIZ.png" height="100%" width="100%" alt="SIEM Dashboard and Capabilities"/>
<br />
<br />
<br /> 
<b>Wazuh Dashboard -<b>
<b>Sample PCI DSS Rule-Related Event Log<b>  <br/>
<br />
 - This is an example of an event log that highlights the relevant Rule/Requirement Code ID # 
<br />
<img src="https://imgur.com/Bhs4pVa.png" height="100%" width="100%" alt="SIEM Dashboard and Capabilities"/>
<br />
<br />
<br />
<b>Wazuh Dashboard -<b>
<b>Sample SCA Findings and Rationale:<b>  <br/>
<br />
  - While viewing the Security Configuration Assessment logs, I expanded the log to see the ID#'s <b>Rationale, Remediation, Description, Check, and Compliance info</b> 
<img src="https://imgur.com/3OybMsa.png" height="100%" width="100%" alt="SIEM Dashboard and Capabilities"/>
<br />
<br />
<br />
<b>Wazuh Dashboard -<b>
<b>MITRE Attack Description and Mitigation Steps:<b>  <br/>
<br />
- While viewing the MITRE ATTACK logs, I expanded the log to see the ID# details, (which advise how the known attack has been utilized and by which known adversarial actors) Mitigation Steps, (which give a brief description of how to address these threats, and each mitigation "name" can be clicked for additional detail), as well as the common Software targets that have fallen victim to this specific known attack as reference.
<img src="https://imgur.com/V0pub14.png" height="100%" width="100%" alt="SIEM Dashboard and Capabilities"/>
<br />
<br />
<br />
<b>Wazuh Dashboard -<b>
<b>Integrity Monitoring:<b>  <br/>
<br />
-While viewing the Events logs under the Integrity Monitoring section, I highlighted where the exact file path, the relevant Rule Description, and Rule ID related to the events listed can be referenced for further investigation
<img src="https://imgur.com/AEUAQCW.png" height="100%" width="100%" alt="SIEM Dashboard and Capabilities"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
