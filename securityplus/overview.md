# Overview

* This section of the course focuses on the foundational knowledge
required for understanding cyber security before diving into technical aspects.
* Cyber security involves a constant struggle between security and convenience,
where trade-offs must be made.
* Balancing security and convenience is a challenge both at home and
within organizations.
* The desire for convenience often compromises security,
leading to cyber attacks and data breaches.
* Major companies spend significant amounts,
around 1.3 million dollars per data breach, due to this trade-off.
* The section will cover foundational concepts such as the CIA triad
and triple As of security.
* Two key terms are defined:
information security and information systems security.
* Information security pertains to protecting data from unauthorized access,
modification, disruption, disclosure, corruption, and destruction.
* Information systems security focuses on safeguarding the devices 
(e.g., computers, servers, networks, smartphones) that hold
and process critical data.
* Section one provides an overview of various topics,
with more in-depth coverage in subsequent sections to prepare 
students for certification exams.

## CIA Triade

![CIA Triade](./images/overview/cia-triad.png)

* The CIA triad is a foundational concept in cybersecurity, consisting of
three components: confidentiality, integrity, and availability.
    * Confidentiality ensures that information is not disclosed to unauthorized
individuals, both in the physical and digital world.
Encryption plays a key role in maintaining confidentiality.
    * Integrity focuses on preventing unauthorized modification or
alteration of information. Maintaining the accuracy and trustworthiness of
data is crucial for preserving integrity.
    * Availability ensures that information is accessible, stored,
and protected at all times. It is important for systems to be available
and functional when needed by users.
* The CIA triad works together to provide secure and usable systems.
Losing any of the components can create vulnerabilities that attackers may
exploit.
* Encryption, authentication, and hashes are examples of security measures
that contribute to achieving confidentiality, integrity, and availability.
* Understanding and applying the CIA triad is essential for building robust
security practices and protecting data and information effectively.

## AAA of Security

* The three A's of security are authentication, authorization, and accounting.
* Authentication establishes a person's identity through proof and confirmation
by the system.
    * Auth methods includei passwords, biometrics, tokens,
    actions, and location factors.
* Authorization grants users access to specific data or areas
based on their authorized privileges.
* Accounting involves tracking data, computer usage, and network resources
through log files to ensure good accounting practices and enable investigation
in case of breaches or insider threats.
* Non-repudiation ensures that users cannot deny their actions by
providing evidence, such as digital signatures, that proves their involvement.

## Security Threats

* Security threats pose risks to systems, computers, and servers.
* Four main categories of security threats are:
    1. Malware
    2. Unauthorized access
    3. System failure
    4. Social engineering
* Malware includes various malicious software types like viruses, worms,
Trojan horses, spyware, rootkits, adware, and ransomware.
* Unauthorized access occurs when unauthorized individuals gain access to
computer resources or data without the owner's consent.
* System failure refers to computer crashes or application failures,
often symbolized by the "blue screen of death" (BSOD) in older Windows systems.
* Social engineering involves manipulating users into divulging confidential
information or performing actions harmful to themselves or their company,
often through methods like phishing or physical deception.

## Mitigating Threats

* Threat mitigation involves three basic categories of controls:
    1. Physical
    2. Technical
    3. Administrative
* Physical controls are tangible measures implemented in the
real-world environment, such as alarms, surveillance cameras, locks, fences,
identification cards, and security guards.
* Technical controls encompass technologies and systems like smart cards,
access control lists, intrusion detection systems,
encryption, and network authentication.
* Administrative controls include policies, procedures, security awareness
training, contingency plans, and disaster recovery plans.
* Administrative controls can be further classified into procedural controls
(voluntary actions taken by the organization) and legal/regulatory controls
(mandatory requirements imposed by laws and regulations).
* User training is a cost-effective administrative control that plays a
crucial role in overall security, as users' actions can bypass technical controls.
* The combination of physical, technical, and administrative controls is
essential for comprehensive security.
* The terms "administrative controls" and "managerial controls" refer to the
same concept of policies and written organizational constraints.

## Hackers
* There are five types of hackers.
* 1. White hats.
      Non-malicious hackers who attempt to break into a company's systems at their request.
* 2. Black hats.
      Malicious hackers who break into computer systems and networks without authotization or permission.
* 3. Gray hats.
      Hackers without any affiliation to a company who attempt to break into a company's network but risk the law by doing so.
* 4. Blue hats.
      Hackers who attempt to hack into a network with permission of the company but are not employed by the company.
  5. Elit.
      Hackers who find and exploit vulnerabilities before anyone else does.
      1 in 10,000 are Elite

## Threat Actors.
  Script kiddies.
*    Hackers with little to no skills who only use the tool and exploits written by others.

  Hacktivists.
*    Hackers who driven by a couse like social change, political agendas, or terrorism.

  Organized Crime.
*    Hackers who are part of a crime group that is well-funded and highly sophisticated.

  Advanced Persistent Threats.
*    Highly trained and funded groups of hckers(often by nation states) with covert and open-source intellegence at their disposal.
     
## Threat Intelligence and Source.
* Timeliness
Property of an intelligence source that ensures it is up to date
* Relevancy
Proper of an intelligence source that ensures it matches the use cases intended for it
* Accuracy
Property of an intelligence source that insures it produces effective results
* Confidence Levels
Property of an intelligence source that insures it produces qualified statements about reliability
* Proprietary
Threat intelligence is very widly provided as a commercial service offering, where access to updates and research is subject subscription fee
* Closed-Source
Data that is drived from the provider's own research and analysis efforts, such as data from honeynets that they operate, plus information mined from its customer's system, suitably anonymized
* Open-Source
Data that is available to use without subscription, which may include threat feed similar to the commercial providers and may contain reputation lists and malware signature databases
##         * US-CERT
##         * UK's NCSC
##         * AT&T Security (OTX)
##         * MISP
##         * Virus Total
##         * Spamhous
##         * SANS ISC Suspicious Domains
* Open-Source intelligence (OSINT)
Methods of obtaining information about a person or organization through public records, website, and social media

##         * Threat Hunting
* Threat hunting
      A syber security technique designed to detect presence of threat that have not been discovered by a normal security monitoring
      Threat hunting is potentially less disruptive than penetration testing
* Establishing a hypothesis
      A hypothesis is drived from the threat modeling and is based on potentialevents with higher events with likelihood and higher impact
* Profiing treat actors and Activites
      Involevs the creation of scenario that shows how a prospective attacker might attempt an intrusion and what their objectives might be
* Threat hunting relies on the useg of the toos developed for regular security monitoring and incident response
      Analyze network rtaffic
      Analize the executable process list
      Analyze other infected host
      Identify how the malicious process was executed

* Threat hunting consumes a lot of recoures and time to conduct, but can yield a lot of benefits
      Improve detection capabilites
      Integrate intelligence
      Reduces attack surface
      Block attack vectors
      Identify critical assets


##         Attack frameworks

* Kill chain
      A model developed by CLockheed Martin that describes the stages by which a threat actor progreesses a network intrusion
      * Reconnaissance
           The attacker determines what method to use to complete the phases of the attack
      * Weaponization
           The attecker couples payload code that will enable access with exploit code that will use a vulnerability to execute on the target system
      *Delivery
           The attecker indentifies a vector by which to transmit the weaponized code to the target enviroment
      * Exploitation
           The weaponized code is executed on the target system by this mechanism
      * Installation
            This mechanism enables the weaponized code to run a remote access tool and achieve persistent on hte target system
      * Command and Control(C2)
            The weaponized code establishes an outbount channel to a remote server that can then be used to control the remote access tool and possible download additional tools to progress the attack
  
      * Actions on Objectives
            The attacker typically uses the access he has achieve to covertly collect information from target systems and transfer it to a remote system (data exfiltration) or achieve other goals and motives
      * kill chain analysis can be used to indetify a defensive course-of-action matrix to counter the progress of an attack at each stage     

      * MITRE ATT&CK Framework
            A knowledge base maintained by the MITRE Corporation for listing and explayning specific adversary tactics, techniques, and common knowledge or procedures (attack.mitre.org)
            The pre-ATT&CK tactics matrix aligns to the reconnaissance and weaponzation phases of the kill chain
      * Dimond Model of Intrusion Analysis
            A framework for analyzing cybersecurity incidents and intrusions by exploring the relationships between four core features: adversary, infrastructure, and victim
 

