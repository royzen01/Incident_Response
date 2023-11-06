# Incident Response

## Scenario

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

* A new firewall rule to limit the rate of incoming ICMP packets
* Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
* Network monitoring software to detect abnormal traffic patterns
* An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity incident and integrate your analysis into a general security strategy:

* <b>Identify</b> security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

* <b>Protect</b> internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

* <b>Detect</b> potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

* <b>Respond</b> to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

* <b>Recover</b> affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.
  

## Incident report analysis


<table>
  <tr>
   <td><strong>Summary</strong>
   </td>
   <td colspan="3" >Recently the organization experienced a DDoS attack which compromised the internal network for two hours. The network services became unresponsive due to the flood of incoming ICMP packets. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. The attack was successful due to an unconfigured firewall which allowed the attacker to overwhelm the network.
   </td>
  </tr>
  <tr>
   <td>Identify
   </td>
   <td colspan="3" >The company’s cybersecurity team investigated the event and determined that a malicious actor had sent a flood of ICMP packet pings into the company’s network through an unconfigured firewall. The company’s network was compromised for two hours.
   </td>
  </tr>
  <tr>
   <td>Protect
   </td>
   <td colspan="3" >The cybersecurity team implemented a new firewall to limit the rate of incoming ICMP packets. They implemented source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets. Installed network monitoring software to detect abnormal traffic patterns. Configured an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.
   </td>
  </tr>
  <tr>
   <td>Detect
   </td>
   <td colspan="3" >To detect potential future attacks the security team has added an IDS/IPS system. Ensuring that a properly configured SIEM is being used and monitored is also a good idea to detect potential intrusions.
   </td>
  </tr>
  <tr>
   <td>Respond
   </td>
   <td colspan="3" >The security team should attempt to isolate the threat from the rest of the network. Attempt to restore any compromised systems. Report the incident to the proper channels and take the authorities if necessary.
   </td>
  </tr>
  <tr>
   <td>Recover
   </td>
   <td colspan="3" >Ensure business critical services are restored first. Then, confirm that the threat has been mitigated. Once the attack has stopped restore the rest of the services that might’ve gone offline (non-critical)
   </td>
  </tr>
</table>

