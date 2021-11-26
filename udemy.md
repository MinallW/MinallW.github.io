# Table of Contents

1.  [Linux for network engineers, practical Linux with GNS3](#org10a825f)
	1.  [GNS3](#org5254565)
2.  [The Complete Cyber Security Course: Hackers Exposed!](#org0a7f414)
	1.  [Goals and Learning Objectives](#org8abe4d7)
		1.  [Thread Assessment and Risk Assessments](#orgef927c3)
	2.  [Why you Need Security - The value of a Hack](#org877d49d)
	3.  [Top 3 Things to stay safe online](#org1c46de3)
	4.  [Security BUgs and Vulnerabilities - The Vulnerability Landscape](#orgf57017f)
	5.  [Hackers, crackers and cyber criminals, ScriptKiddies](#orgc3e280d)
	6.  [Malware, viruses, rootkits, and RATs](#orgfc2a445)
		1.  [MacroVirus](#orgff614cc)
		2.  [Stealth Virus](#org731ff56)
		3.  [Polymorphic Virus](#org83a899b)
		4.  [Self-garbling Virus](#orgfd9579e)
		5.  [Bots & Zombies](#org1b6374d)
		6.  [Worms](#orga0705ea)
		7.  [OS Rootkit](#orgc9ca3b4)
		8.  [Firmware Rootkit](#org36c5428)
		9.  [KeyLogger](#org7b383fb)
		10. [Trojan](#orgdc41886)
		11. [Remote Access Tool (RAT)](#orgca86414)
		12. [Ransomware](#org9a13a63)
		13. [Malvertisement](#orgd2e9dc2)
		14. [Spyware](#orgd138b12)
		15. [Adware](#org45a95d8)
		16. [Scareware](#org1f310e8)
		17. [Browser Hijacking](#org770b658)
		18. [Potentially Unwanted Programs (PUPs)](#org1aa16ae)
		19. [Phishing](#org5dc177c)
		20. [XSS Cross Site Scripting (Reflected)](#orgc008be5)
		21. [Spamming and Doxing](#org0d46172)
		22. [Social Engineering, Scams and frauds](#org60ac2b0)
		23. [CPU Hijackers - Crypto Mining Malware and Cryptojackers](#orgda4ada4)



<a id="org10a825f"></a>

# Linux for network engineers, practical Linux with GNS3

Here, I will note all the important information I get on this course.


<a id="org5254565"></a>

## GNS3

> Emulation, configuration, testing and troubleshooting virtual and real networks.


<a id="org0a7f414"></a>

# The Complete Cyber Security Course: Hackers Exposed!


<a id="org8abe4d7"></a>

## Goals and Learning Objectives

-   [ ] Master the fundamental building blocks of security & privacy
-   [ ] Understand the online threat and vulnerability landscape
-   [ ] Perform threat modeling and risk assessment
-   [ ] Determine personal threats and adversaries
-   [ ] Build test environments in Virtualbox and VMware
-   [ ] Master encryption
-   [ ] Understand Windows, MacOS, Linux security & privacy features
-   [X] Be able to mitigate social engineering attacks
-   [ ] Use isolation and compartmentalization effectively

*Learn to teach someone else*

After the course is done, ask for certificate [here](https://www.stationx.net/certificate-request/)

Some important definitions, security is the protection of our Assets agains
threats imposed by our adversaries.

-   **Assets:** Anonimity, Files, Privary, Identity, Email, Location, Activity
-   **Security:** HTTP filter, Firewall, HTTPS, Encryption, VPN, Tor
-   **Threats:** Rootkits, Malware, Spying, Viruses, Surveillance, Encryption
-   **Adversaries:** Crackers, Spies, Hackers, Cyber Criminals
-   asdkjs

Some Risk Assessment Methods are:

-   <https://www.stationx.net/sabsa/>
-   <https://www.iso.org/standard/56742.html>
-   <https://www.securityforum.org/>


<a id="orgef927c3"></a>

### Thread Assessment and Risk Assessments

You cannot have 0 risk or a perfect security, no total anonimity exist. There
will always be risks on any action.

We have to accept a level of risk, what is the tolerance for it?&#x2026;

Security is a balance between mitigating the vulnerabilities of a risk.

Risk based approach to apply the right level of security to mitigate the risk,
without making a system unusable.

We need to make basic threat modeling.

RISK = (Vulnerabilities x Threats x Consequences)

1.  Assets
2.  Vulnerabilities
3.  Threats
4.  Adversaries
5.  Consequences

The process goes like this:

1.  Select
2.  Implement
3.  Assess
4.  Monitor

Being it a vulnerability, select an asset you want to protect and go for that.

The more privacy you need, the more security controls.

> Privacy isn't about hiding something. It's about being able to control how we
> present ourselves to the world. It's about maintaining a public face while at
> the same time being permitted private thoughts and actions. It's about personal
> dignity - Bruce Schneier

**CIA TRIAD**

Security attributes on an asset:

-   Confidentiality
-   Availability
-   Integrity

	GRAYLOG


<a id="org877d49d"></a>

## Why you Need Security - The value of a Hack

Bots are the most largest thread on the internet, bots will scan
external servers in attempt to check its vulnerabilities.

Pentesting is very important, because each server or implementation
will be unique. Each attacks done automatically by these bots may
have a different problem, being it on your account, computer or
internal LAN, so is important to be knowlegeable.


<a id="org1c46de3"></a>

## Top 3 Things to stay safe online

-   Antivirus
-   Visiting only known websites
-   Changing Passwords
-   Delete cookies?

There are even more important security practices:

-   Update system
-   Use unique passwords
-   Use two-factor auth
-   Use strong passwords
-   Use password manager
-   Check if HTTPS
-   Don't share info
-   Use verified software
-   BE SUSPICIOUS OF EVERYTHING

These don't do much:

-   Delete cookies
-   Change password


<a id="orgf57017f"></a>

## Security BUgs and Vulnerabilities - The Vulnerability Landscape

Complexity is the nemesis of security.

Zero day bug - no patch

Always update, since there may be patches for discovered, we should
have a list of all the vulnerabilities and patch.

Some vulnerabilities are available through databases, like
Exploit-DB and CVE.


<a id="orgc3e280d"></a>

## Hackers, crackers and cyber criminals, ScriptKiddies

Capable hackers sell tools.


<a id="orgfc2a445"></a>

## Malware, viruses, rootkits, and RATs


<a id="orgff614cc"></a>

### MacroVirus

Code written in macros, that will be executed once an spreedsheet
is executed. Well, any program that does macros falls in this category.


<a id="org731ff56"></a>

### Stealth Virus

Hides the modifications it has made while tries to change
something on the system, intercepting request to the system or
kernel, providing bague information.


<a id="org83a899b"></a>

### Polymorphic Virus

Produces multiple operational copies of itself, with no identical
parts, making it difficult to detect.


<a id="orgfd9579e"></a>

### Self-garbling Virus

Known viruses yet with code modified so, it doesn't match known
information from an antivirus.


<a id="org1b6374d"></a>

### Bots & Zombies

Hack devices under a hacker's command, your device is a zombie
once the Hacker has some sort of control to it, for sending DDoS
attacks, for example.


<a id="orga0705ea"></a>

### Worms

Viruses that spread to one machine to another.


<a id="orgc9ca3b4"></a>

### OS Rootkit

Worst software based malware, embedded into the kernel of the
operating system, so it can hide its presence totally from the OS.


<a id="org36c5428"></a>

### Firmware Rootkit

Within your hardware SSD firmware, malware could be hidden,
formatting the drive won't help on this situation. This is highly
advanced so, there are few hackers working on this, yet it is possible.


<a id="org7b383fb"></a>

### KeyLogger

Logs all keys on the machine you're using.


<a id="orgdc41886"></a>

### Trojan

Programs that appear to be one thing but are malware.


<a id="orgca86414"></a>

### Remote Access Tool (RAT)

Allow remote access to a hacker to a system.


<a id="org9a13a63"></a>

### Ransomware

Encrypts all your data and asks for payment for it to be decrypted.


<a id="orgd2e9dc2"></a>

### Malvertisement

Virus malware on ad.


<a id="orgd138b12"></a>

### Spyware

Gather information and send it back to the attacker.


<a id="org45a95d8"></a>

### Adware

Form of spyware, undesirable software that forces adverticement on you.


<a id="org1f310e8"></a>

### Scareware

Social engineering tool, tricks the user to believe there's an
unexistent thread.


<a id="org770b658"></a>

### Browser Hijacking

Hacker uses the client browser for mining or other purposes.


<a id="org1aa16ae"></a>

### Potentially Unwanted Programs (PUPs)

Programs that may be malware.


<a id="org5dc177c"></a>

### Phishing

Tricks the victim into clicking on a link, or executing malware on
some way, for example:

<http://www.rnicrosoft.com>

Depending on the font, the client won't see mispell.

-   <http://www.google.com.stationx.net>
-   <http://stationx.net/sa/google.com/support/>
-   <http://www.g00gle.com>
-   <http://www.goog1e.com>
-   Hidden URLS using HTML.

For example, sending millions of email addresses.

-   **Vishing:** Call, Voice phishing
-   **Smishing:** SMS


<a id="orgc008be5"></a>

### XSS Cross Site Scripting (Reflected)

Injecting code in the HTML code of a webpage.


<a id="org0d46172"></a>

### Spamming and Doxing

Unsolicited messages, normally mails, normally to advertize.

Sending a million emails, is cheap, and a few do fall for it, if
you have an unrequested email, you should suspicious.

Doxing is an abbreviation of document, it is a targetted
information searching, often in order to cause harass,
embarassment, etc.

Someone doxed means someone has their private information public.


<a id="org60ac2b0"></a>

### Social Engineering, Scams and frauds

'Friends', Dating sites, Ebay Scams, Fees for any service, product
or 'won' price.


<a id="orgda4ada4"></a>

### CPU Hijackers - Crypto Mining Malware and Cryptojackers

Javascript based mining tools on websites.

App store apps.
