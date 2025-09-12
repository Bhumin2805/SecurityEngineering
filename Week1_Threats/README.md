# Week 1

### Grading 

Task #|Points|Description|
-----|:---:|----------|
[Virtual Machine Setup](#virtual-machine-setup-virtual-machine-with-docker) | - | Virtual Machine & Docker
[Task 1](#task-1-what-measures-have-you-taken-to-protect-yourself-from-cyber-crimes) | 1 | Measures Against Cyber Crimes
[Task 2](#task-2-company-security-policy) | 1 | Company Security Policy
[Task 3](#task-3-threat-modelling) | 2 | Threat Modelling
[Task 4](#task-4-personal-security-audit) | 1 | Personal Security Audit

---

> Please note the part, 'virtual machine & docker' will have most focus on the first exercise session.

### Virtual Machine Setup: Virtual Machine with Docker

You should setup the courses virtual machine and get it ready with docker working. This weeks exercise session will focus on this. 

- Download the course virtual machine from https://ouspg.org/archlinux/.

- Set it up in [VirtualBox](https://www.virtualbox.org/), install if it is not yet installed. You should set it up with no more than 4 cores, less than or around half of system RAM, around 30 GBs of space should be good and for future use make sure it can use USB. (Defaults: 4 cores, 4gb ram, 30gb storage)

- Credentials for the machine are 'arch/arch'

- Update keyring in console with ```sudo pacman -S archlinux-keyring```

- Update system with ```sudo pacman -Syu```

- Test Docker with ```docker run hello-world```

# Tasks

### Task 1: What measures have you taken to protect yourself from cyber crimes?

Answer : 

Yes, I have been a victim of cyber crime. I could have have prevented them. I was receiving some phishing emails from some unknown or unverified email address. while surfing on net on my network, I was once infected with adware via a malicious software downloaded as a virus. This could have been prevented with stricter network segmentation and more controlled user permissions on that specific device.

Actions I have taken to fortify defenses:
* I use a popular password manager to create long, complex, and unique passwords for every account and websites. This prevents a risk of hacking. Also I dont save this as a note in smart phone or any other online platform. 
* All my applications and softwares are on automated software updation mode. So, They cant be hacked easily. 
* I always use VPN security to avoid open or unknown networks. Also I dont use public  or open wifi networks. 
* I have taken backup for all my data and files on offline mode.
* I avoid to click on any random links and download it
  
Area of Improvement:
* Better software updation ontime and regular interval checking of systems update . 
* Should Invest in more advanced, dedicated firewall hardware or software solutions for deeper safety.
---

### Task 2: Company Security Policy
Answer:- 

- Password policy

* A password should be strong and Unique.
* Password must be at least 14 characters long.
* It shoulde be complex and It should be contain Uppercase letters, Lowercase letters, Numbers, Symbols.
* Do not use your birthday or name etc. So that nobody can guess your password.
* Never share your password with anyone.
* If you forget your password, please contact the IT Help Desk to reset it.
* Do not reuse password. Always create a new password and not the repeated one.
* After entering your password, you'll need to approve the login with something you have, in which you will receive a code and you need to approve that from any device, like your phone.
* Make sure to use VPN (Virtual Private Network). It is secure network that lets you connect to our office network from home or anywhere.

- Social media security policy

* Think Twice Before You Post anything on social media platform.
* Do not share any confidential information like financial issues, Future plans, upcoming projects, etc. about our company.
* If you are sharing any information about the company than it is better to ask your manager before post on social media.
* Whenever you post about the company, make sure your post should be respectful and your words should be chosen wisely.
* Make sure your account is private and if it is public than you have to be careful because your account can be hacked easily.
* If anything posted on your account is not done by you than inform your manager and IT team immediately and also don't forget to delete it.
* Be careful with any direct messages or links you received on social media. If you don't know, don't click it. 



### Task 3: Threat Modelling


- Identify your assets. WHAT do you want to protect?
  Answer:- I want to protect all my devices like mobile, laptop, Tablet etc. Moreover all the data and information I have in these devices.
         - All the accounts like gmail and other app account and their password and text messages. All of these are important and needs to be protect.

  
- Who are your potential adversaries. WHO do you want to protect from? 
  Answer:- I want to protect from my employers, my relatives, friends, hackers and my business compititors.

  
- Assess the threats and likelyhoods of them for each of your assets. How LIKELY is it that you will need to protect it?
  Answer:- mobile is the most important devices for us nowadays and all of my data is in my mobile, so it can be harmful if it will be hacked, because there are photos and videos which can be misused.
         - Laptop is also imporant device to protect as it contains my all documents and information.
         - Gmail account contains all the important mail and it needs to be protect.
         - Password is Also important because without password we can not open any of our account. So it is important to protect the password, so hacker will also can't login our account easily.

- Evaluate impact if an asset is compromised. How bad are the CONSEQUENCES if you fail?
  Answer:- My photos and videos can be misused with the usage of AI.
         - Hacker can blackmail me for some benefits. I can loose my reputation, I might be face financial issues.

- Cost. How much trouble and time are you willing to spend to prevent the consequences? 
  Answer:- To prevent the consequences I will use passowrd manager to protect my password and also I can use authentification for login.
         - For software and apps I will use the regular software update.
         - I will use VPN to protect my network from any unknown and open network.
  
- Mitigate or mitigation plan; determine what you can do now and what to do if compromised.
  Answer:- For now I will use the password manager to protect the password, Use software update for software and for network I use VPN
         - If compromised then I will logout from all my account and change the password immediately. For all the software and other data I will restore all of them.


### Task 3A: [Threat Dragon](https://owasp.org/www-project-threat-dragon/) (1p)

Threat Dragon is an OSS tool used to create threat model diagrams(see image below). The tool very specifically does **not** try to do too much on its own, rather gives control to the user and encourages their own thinking, as they should thoroughly analyse the system they are working on. 

In this task we are using the second version, it's documentation is [here](https://owasp.org/www-project-threat-dragon/docs-2/install-options/). You may use your preferred method for installation, they are very similar, but we recommend **the desktop application,** as it stores the models on the local file system. First go through a bit of the documentation to get acquainted with the tool. Then you will be analysing a ready made flawed model, and you should find pain points and fix the model. The model is *"Student_website_Threat_Model.json"* in the threat dragon repository, there you will also find an example of how the report looks like without threats. Below you will find minimum requirements and a system description. 

<details>
<summary>Minimun requirements for the point:</summary>
<br>

Each **missing** or **incomplete** main point deducts 0.2 from this part.

- Created at least 10 threats 
    - Use [STRIDE](https://learn.microsoft.com/en-us/previous-versions/commerce-server/ee823878(v=cs.20)) with approriate categories
- Mitigated at least 5 threats 
    - Must include how mitigated and how that works 
- Filled in the spots with '???'
- Exported report as PDF and uploaded to github
    - Named yourself as the reviewer
- Gave feedback on this task on your github page 

</details>

<details>
<summary>System description:</summary>
<br>

The model is of a static student portfolio website with the following attributes: 

- HTML5 and CSS 
- Containerized with docker, Nginx
- Cloud hosted, student rents server
- Local development, connect via SSH 

</details>

### Task 3B: Personal Threat Model (1p)

A threat model is a tool used widely in security, it can be used for example to identify sensitive or vulnerable data or systems. Its goal is to identify potential vulnerabilities and a likely impact of a security breach, helping companies take proper measures to mitigate and / or prevent these. A threat model can also help companies assess and prioritize its security efforts by identifying which assets are the most critical and which threats are the most probable. Overall, a threat model is a vital part of a comprehensive cyber security strategy helping organizations manage risks and breaches, and how to allocate defense budget.

In this task we are focusing solely on the cyber side of threat models as you will be creating a personal threat model to identify and assess potential threats to your assets, for example sensitive information and online accounts.

The goal of creating a personal threat model is to help you understand potential ways to analyze your own cyber behavior and how to prioritize your efforts regarding your own personal security and privacy. It is also important for cyber security students to understand the types of threats they may face and what the potential impact can be. Threat modelling is also an important skill for security professionals and doing personal threat modelling can be translatable to real world businesses.

You can find more information on [OWASP Threat modelling,](https://owasp.org/www-community/Threat_Modeling) in [The Threat Modelling Manifesto](https://www.threatmodelingmanifesto.org/) and [Privacyguides' threat modelling](https://www.privacyguides.org/en/basics/threat-modeling/)


We also recommend creating a visual representation(s) of your threat model(for example threat dragon), diagrams and flowcharts are good for this. Discussing with your classmates can also help with any additional measures you can take to reduce your risks.

You can follow this flowchart from a previous students answer and expand on it
![Example Personal Threat Model](PersonalThreatModelExampleFlowchart.png)

---

### Task 4: Personal Security Audit

### Task 4A: Network scan 

Let's start with a network scan, [NMAP](https://nmap.org/); a network mapper which is 
> "A free and open source utility for network exploration and security auditing" -[NMAP Book](https://nmap.org/book/preface.html) 

NMAP is available as both a CLI and [GUI (Zenmap)](https://nmap.org/zenmap/) application, most of the time you will use nmap from the command line. There are some benefits to Zenmap, such as the topology map, and we are going to showcase that here in this task. 

NMAP is available on all the commmon platforms and you can get it from their [website](https://nmap.org/download), however if you are using Linux, you can most likely get it from your package manager. 

> For course VM ```yay zenmap``` and choose the 'aur/zenmap' option 

Go ahead and proceed with the installation, for Linux you might have to install Zenmap package as it usually is not bundled with NMAP. If you are using Windows we recommend leaving everything as default.

>**Note**
>Before scanning your network, make sure to let everyone on the network know about it, and more importantly give them the ability to disconnect their devices. 

To scan your network you are going to need your ip address in CIDR notation, which will most likely look something like this: ```192.168.1.0/24```. Below you will find instruction for Linux, Windows and Mac.

<details>
<summary>Linux</summary>

The command ```ip a``` will show your ip address already in CIDR notation, you just have to find the address of the correct device, usually the second from the top as the first will be localhost. 

![ip a on Linux](https://github.com/ouspg/SecurityEngineering/blob/main/Week1_Threats/Images/Linux_ip_a.png)

Now make sure to swap the host part; part after the last '.' and before the '/' to a 0. Add the CIDR and this will be the address you will scan.

</details>

<details>
<summary>Windows</summary>

The command ipconfig will show you your ip address and the subnet mask, with these we will figure out the address you will scan.

![ipconfig on windows](https://github.com/ouspg/SecurityEngineering/blob/main/Week1_Threats/Images/Windows_ipconfig.PNG)

These are the numbers we care about.

The most common subnet mask in home networks is ```255.255.255.0``` this will result in '/24' at the end of the ip address. If your subnet mask is something else, please refer to this [cheat sheet](https://www.freecodecamp.org/news/subnet-cheat-sheet-24-subnet-mask-30-26-27-29-and-other-ip-address-cidr-network-references/) to find out your CIDR notated address.

Now make sure to swap the host part of your ip address; part after the last '.' to a 0. Add the CIDR and this will the address you will scan. 

</details>

Now that we have the address we want to scan, open up Zenmap. The UI is mostly self-explanatory, put the ip address in CIDR notation to the target and choose intense scan for the profile, then just press scan. This should scan the devices in your network. While the scan is running, you can see the output the same way as in NMAP, wait for it to finish and comb through the output. Take note of open ports, scripts and operating systems the scan found.

Make your way over to the topology tab. Enable easy controls with the control button on the left. Here you should now see all the devices found, icon definitions can be seen after clicking the 'Legend' button on the right, and more info on the devices can be found by right clicking.

Save the scan with ```CTRL + S``` and take a screenshot of this topology screen with devices clearly visible, you can redact device information from the screenshot if you want to. 

>The topology map can show traceroutes when scanning outside your network, this is where the tool shines as a simple visual aid. 

**What to return:**
1. Did you find devices you did not know were in your network?
2. Were there open ports which should have been closed?
3. Did nmap find any vulnerabilities with the scripts?
4. Screenshot of the topology of your network. You can redact device information if you want.

### Task 4B: Account Security

This part of task 4 is to check yourself with haveibeenpwned. This should let you know if your account details have been leaked and what types of information was included.

[Haveibeenpwned](https://haveibeenpwned.com/) Is a website and very simple to use, you input your email address and it will search for leaks on platforms where you have accounts. The website shows you platforms it detected had been leaked and those leaks included your email address, however it is not a definitive list and there may be more leaks or dumps with your email included. Take a screenshot for the return. 

**What to return:**
1. Has your account details leaked?
2. Screenshot of haveibeenpwned search, you can redact information if you want.
3. Did you change passwords and/or email + password combos, that were leaked, if not, do it.

### Feedback
Be sure to give feedback on these tasks. Do you feel these to be the kind of skills you might need or want?
