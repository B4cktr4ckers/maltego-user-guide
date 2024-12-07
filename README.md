# 📖💻 Maltego : Beginner's Guide 💻📖
Want to know how maltego works to help you with your next assignment? <br>
You don't know the software? <br>
Did you get lost on github? <br>
This guide is made for you <br>

## Table of Contents
1. [Introduction](#introduction)
2. [Why Maltego](#why-maltego)
3. [Why Use Maltego for Malware Analysis?](#why-use-maltego-for-malware-analysis)
4. [Setting Up Maltego](#setting-up-maltego)
5. [Key Features of Maltego for Malware Analysis](#key-features-of-maltego-for-malware-analysis)
6. [Practical Example: Analyzing a Malicious Domain](#practical-example-analyzing-a-malicious-domain)
7. [Tips and Best Practices](#tips-and-best-practices)
8. [Additional Resources](#additional-resources)

---
<img src="recources/first_screen.png" width="800">

## Introduction
Maltego is a powerful open-source intelligence (OSINT) and data visualization tool (It's a bit like a mental map that we do at school, but for OSINT). <br>
It helps cybersecurity professionals connect the dots by visualizing relationships between data points, such as IPs, domains, files, and even malware samples. <br>
Like mental maps 🧠, this system allows you to have a quick visual of all the data available. <br>
This guide provides a step-by-step approach to how using Maltego and why it's a good software for malware analysis. <br>

---

## Why Maltego ❓
To complete what was said above, and to summarize and give concrete examples. <br>
Maltego is the equivalent of the cork board with all the evidence from the old detective series <br>
(The famous cork board with red threads connecting all the evidence together) <br>
It is a visual way of collecting clues about a specific situation.
<br>
Some usage of Maltego is :
- Tracking Criminals: View connections between email addresses, phones, and online profiles to identify suspects or organized groups.
- Fraud analysis: Examine financial transfers, fake accounts or fictitious organizations.
- Cyberattack tracking: Identify where an attack is coming from by connecting digital clues (like IP addresses and servers).
- Investigative Research: Collect and organize information for investigative reporting (e.g. Pandora Papers).
- Finding information about individuals: Find email addresses, social media profiles, phone numbers, or associations with organizations. <br>

Some famous exemples :
- During investigations into malicious infrastructure linked to attacks like Emotet, Maltego has been used to map associated domains, servers and IP addresses, allowing the location of command and control (C&C) servers.
- Maltego has been included in investigations by Interpol and other agencies to detect terrorist organizations' financing networks or their online communications.
- Journalists investigating the misuse of Pegasus spyware (by governments to target journalists, activists, and politicians) used Maltego to visualize and understand the connections between targeted phone numbers and the organizations involved.
<br>
Maltego is also used by police force worldwide : <br>
- Interpol 🌍 <br>
- Cyber Police 🇺🇦 <br>
- Federal Bureau of Investigations 🇺🇸 <br>

## Why Use Maltego for Malware Analysis ❓
Maltego’s graph-based interface makes it ideal for:
- **Investigating malware infrastructure** (domains, IP addresses, email addresses).
- **Mapping relationships** between malware indicators (IOCs).
- **Connecting OSINT data** to malware samples for deeper analysis. <br>

<img src="recources/Affaire_Commenary.png" width="800">
Exemple of a map for a murder case 🗡️.

---

## Setting Up Maltego

### Step 1: Install Maltego
1. Download Maltego from [Maltego's official website](https://www.maltego.com/).
2. Install the appropriate version for your OS (Windows, macOS, or Linux).
   
> [!TIP]
> For Linux users, I encourage you to search directly on the internet for "how to install maltego" accompanied by your distribution

### Step 2: Create an Account
1. Launch Maltego and sign up for a free license (community edition, the only one you can use at least u wana pay 8k).
2. Log in to the Maltego client (just follow the instructions).
3. You are ready to go !

> [!TIP]
> If one day maltego refuses to log you and assign you a license <br>
> delete your account files (MaltegoID.activation and MaltegoID.keypair) <br>
> on ~/.maltego/ <br>
   
---

## Practical Example: Joseph Murder Case :
Working on it :)


> [!WARNING]
> Of course, don't use these techniques for bad intentioned purposes. <br>

---

## Tips and Best Practices
1. **Start Small**: Begin with a single entity (e.g., a domain or IP) to avoid cluttered graphs.
2. **Use Filters**: Focus on significant connections by hiding unrelated entities.
3. **Validate Findings**: Cross-reference data with other tools (e.g., Threat Intelligence Platforms).
4. **Stay Up-to-Date**: Regularly update transforms and integrate new data sources.

---

## Additional Resources
- **Official Maltego Documentation**: [Maltego Docs](https://docs.maltego.com/)
- **Maltego Transform Hub**: Explore transforms for various use cases. (is like add-on store of vscode)
- **VirusTotal API**: [VirusTotal](https://www.virustotal.com/)
- **Shodan API**: [Shodan](https://www.shodan.io/)
- **AbuseIPDB**: [AbuseIPDB](https://www.abuseipdb.com/)
- **OSINT: Maltego Beginner Get Started Tutorial**: [Maltego4Begginers](https://www.youtube.com/watch?v=kmOIhvsklv8)
- **Maltego - The Automated OSINT Tool for Ethical Hackers**: [Auto4begginers](https://www.youtube.com/watch?v=a2ZvpwF3u-M)
- **Maltego - Maltego FAQ** : [Maltego-FAQ](https://www.maltego.com/maltego-faq/)

> [!TIP]
> As you learn at Epitech. Google is your friend, this guide is not yet very complete and will probably never be the best <br>
> So don't hesitate to ask your Google friend, he will also be happy to help you <br>

---

Happy investigating! ^^ <br>
Alex <br>
