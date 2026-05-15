# **Social Engineering Attacks**



## **Security Analyst Internship Report (Cybersecurity Domain)**



**Prepared by:** Security Analyst Intern-Mahi Surani  
**Domain:** Cybersecurity — Human-Centric Threats  
**Report Type:** Technical Internship Report  
**Date:** May 2026



## **Table of Contents**



1. [Introduction to Social Engineering](#1-introduction-to-social-engineering)
2. [Types of Social Engineering Attacks](#2-types-of-social-engineering-attacks)
3. [Real-World Case Studies](#3-real-world-case-studies)
4. [Impact on Organizations and Individuals](#4-impact-on-organizations-and-individuals)
5. [Prevention Techniques](#5-prevention-techniques)
6. [Best Practices for Individuals](#6-best-practices-for-individuals)
7. [Conclusion](#7-conclusion)
8. [References](#8-references)



## **1. Introduction to Social Engineering**



Social engineering is a category of cyberattack that exploits **human psychology** rather than technical vulnerabilities. Instead of breaking through firewalls or cracking encryption, attackers manipulate people into revealing sensitive information, granting unauthorized access, or performing actions that compromise security.

The term "social engineering" in cybersecurity broadly refers to any technique that relies on **deception, persuasion, or psychological manipulation** to gain the trust of a target. The attacker's primary weapon is not code — it is human emotion: fear, urgency, curiosity, greed, or a desire to be helpful.

According to the **Verizon Data Breach Investigations Report (DBIR) 2023**, social engineering was involved in **74% of all data breaches**, making it the leading attack vector across all industries. This highlights a critical truth: the most sophisticated technical defenses can be rendered useless by a single employee responding to a convincing fraudulent email.

Social engineering attacks can target anyone — from entry-level employees to C-suite executives. They can be conducted via email, phone calls, text messages, in-person interactions, or social media platforms. Understanding these attacks is the first step toward building an effective human-centered defense.



## **2. Types of Social Engineering Attacks**



### 2.1 Phishing



**Phishing** is the most widespread form of social engineering. It involves sending fraudulent messages — typically emails — that appear to come from a legitimate and trusted source (e.g., a bank, a government agency, or a well-known company).

The goal is to trick the recipient into:

* Clicking a malicious link
* Downloading a malware-infected attachment
* Entering credentials on a fake website

**Example:** An email appearing to be from "PayPal Support" warns the user that their account has been suspended and urges them to click a link to verify their identity. The link leads to a spoofed website that captures login credentials.



**Key characteristics:**



* Sent in bulk to thousands of targets
* Generic salutation (e.g., "Dear Customer")
* Creates a sense of urgency or fear
* Contains spoofed sender addresses or look-alike domains



### 2.2 Spear Phishing



**Spear phishing** is a highly targeted version of phishing. Unlike generic phishing campaigns, spear phishing attacks are personalized using information gathered about the specific victim — often from LinkedIn, company websites, or social media.

The attacker crafts a message that appears credible and relevant to the target, significantly increasing the chances of success.

**Example:** An attacker researches a company's finance department, finds the CFO's name and the name of a vendor they work with, then sends a spoofed email to an accountant requesting an urgent wire transfer.



**Key characteristics:**



* Personalized and context-aware
* Targets specific individuals or roles (executives, finance, IT)
* Often precedes larger attacks (e.g., Business Email Compromise)
* Harder to detect than generic phishing



### 2.3 Pretexting



**Pretexting** involves creating a fabricated scenario (a "pretext") to extract information from a target. The attacker assumes a false identity — such as a bank auditor, IT support personnel, or law enforcement officer — to gain the target's trust.

**Example:** An attacker calls a company's HR department claiming to be from a payroll software vendor conducting an audit. They ask for employee records or payroll system credentials to "complete the audit."



**Key characteristics:**



* Relies on impersonation of authority figures
* Often conducted via phone (vishing) or email
* Requires research and a believable backstory
* Targets employees with access to sensitive data or systems



### 2.4 Baiting



**Baiting** exploits human curiosity or greed by offering something enticing to lure victims into a trap. This can be digital (a fake free download) or physical (an infected USB drive left in a public place).

**Example:** A USB drive labeled "Q4 Salary Review — Confidential" is left in a company parking lot. A curious employee picks it up and plugs it into a work computer, unknowingly installing malware.



**Key characteristics:**



* Exploits curiosity, desire for free content, or financial gain
* Physical baiting involves infected storage devices
* Digital baiting involves fake software, movies, or games
* Often used to deploy ransomware or keyloggers





### 2.5 Quid Pro Quo



**Quid pro quo** (Latin for "something for something") attacks involve offering a service or benefit in exchange for information or access. The attacker typically poses as a help desk technician or IT support agent offering to solve a problem.

**Example:** An attacker calls random employees at a company claiming to be from IT support. They say there is a known issue affecting several accounts and offer to fix it — but ask the employee for their login credentials to proceed with the fix.



**Key characteristics:**



* Exchange-based: the attacker offers help or a reward
* Often conducted via phone
* Targets non-technical staff who may readily share credentials
* Lower sophistication than spear phishing but effective at scale





### 2.6 Tailgating (Physical Social Engineering)



**Tailgating** (also called "piggybacking") is a physical security attack where an unauthorized person follows an authorized employee into a restricted area by exploiting social norms such as politeness or helpfulness.

**Example:** An attacker dressed as a delivery person waits near a secure office entrance. When an employee badges in, the attacker politely asks them to hold the door — and the employee complies without verifying the person's identity.



**Key characteristics:**



* Entirely physical in nature
* Exploits social courtesy and trust
* Used to gain unauthorized access to server rooms, offices, or data centers
* Can be combined with digital attacks after gaining physical access



## **3. Real-World Case Studies**



### 3.1 The Twitter Bitcoin Scam (2020)



**What Happened:**

&#x20; 
In July 2020, attackers successfully compromised the Twitter accounts of high-profile individuals including Barack Obama, Elon Musk, Bill Gates, Joe Biden, and companies like Apple and Uber. The attackers used these verified accounts to post a Bitcoin scam, promising to double any Bitcoin sent to a specific wallet address.

**Attack Method:**  
The attackers used **spear phishing via phone** to target Twitter employees. They posed as internal IT staff and convinced employees to provide credentials to Twitter's internal admin tools. This gave them the ability to reset email addresses and bypass two-factor authentication for any account.



**Impact:**



* Approximately **$120,000 in Bitcoin** was stolen from victims
* Twitter's internal admin infrastructure was exposed
* Massive reputational and regulatory damage to Twitter
* 130 high-profile accounts were compromised
* Three individuals were arrested, including a 17-year-old mastermind



**Lesson:** Even large technology companies with sophisticated defenses are vulnerable when employees are successfully manipulated. Internal access controls and strict verification protocols are essential.



### 3.2 The RSA SecurID Breach (2011)



**What Happened:**  


RSA Security, a division of EMC and provider of the widely-used SecurID two-factor authentication tokens, suffered a major data breach that compromised the security of its authentication products — used by governments and defense contractors worldwide.

**Attack Method:**  
Attackers sent **spear phishing emails** to two small groups of RSA employees with the subject line "2011 Recruitment Plan." The email contained an Excel attachment with an embedded zero-day Adobe Flash exploit. One employee retrieved the email from their spam folder and opened it, executing the malware and giving attackers a foothold in RSA's network.



**Impact:**



* Sensitive information related to RSA's SecurID token seed values was stolen
* 40 million+ SecurID tokens were potentially compromised
* RSA spent over **$66 million** on remediation
* Defense contractors using RSA tokens (including Lockheed Martin) faced follow-on attacks
* The breach forced RSA to replace tokens for major clients



**Lesson:** A single email opened by one employee can have catastrophic, far-reaching consequences — especially when the target holds sensitive infrastructure data.



### 3.3 The Sony Pictures Hack (2014)



**What Happened:**

&#x20; 
In November 2014, Sony Pictures Entertainment suffered one of the most destructive cyberattacks in corporate history. Attackers gained access to Sony's internal network, exfiltrated massive amounts of data, and then deployed malware that wiped hard drives across the company.

**Attack Method:**  
Investigators found evidence of **spear phishing emails** sent to Sony employees, tricking them into revealing credentials. Attackers also used pretexting techniques to gather information about Sony's network architecture. Once inside, they moved laterally across systems for months before launching the destructive phase.



**Impact:**



* Over **100 terabytes** of data stolen, including unreleased films, executive emails, salary data, and employee personal information
* Entire IT infrastructure was crippled; employees resorted to pen and paper
* Estimated damages exceeded **$100 million**
* Significant reputational damage and legal liability from leaked private communications
* Attributed to the North Korean-linked group Lazarus



**Lesson:** Persistent, patient social engineering followed by lateral movement can lead to complete organizational compromise. Early detection and network segmentation are critical.



### 3.4 The Ubiquiti Inc. BEC Fraud (2015)



**What Happened:**  


Ubiquiti Networks, a US-based networking technology company, lost **$46.7 million** in a Business Email Compromise (BEC) attack — one of the largest of its kind at the time.

**Attack Method:**  
Attackers used **pretexting and email impersonation** to pose as company executives and outside legal counsel. They sent fraudulent emails to Ubiquiti's finance department directing wire transfers to attacker-controlled overseas accounts. The emails were convincing enough that finance employees executed multiple transfers before the fraud was detected.



**Impact:**



* $46.7 million transferred; approximately $8.1 million was recovered
* Regulatory scrutiny and investor fallout
* Highlighted vulnerability of wire transfer authorization processes



**Lesson:** BEC attacks cause billions in losses annually. Strong financial controls — such as dual authorization for large wire transfers and out-of-band verification — are essential defenses.





## **4. Impact on Organizations and Individuals**



### 4.1 Impact on Organizations



|Area|Impact|
|-|-|
|**Financial**|Direct fraud losses, incident response costs, regulatory fines, litigation|
|**Reputational**|Loss of customer trust, negative media coverage, brand damage|
|**Operational**|Business disruption, system downtime, productivity loss|
|**Legal \& Regulatory**|GDPR, HIPAA, and other compliance violations resulting in penalties|
|**Strategic**|Intellectual property theft, competitive disadvantage|



The **IBM Cost of a Data Breach Report 2023** found that the average cost of a data breach reached **$4.45 million** globally, with breaches involving social engineering ranking among the most expensive.



### 4.2 Impact on Individuals



* **Financial loss** from bank fraud, identity theft, or investment scams
* **Identity theft** leading to long-term credit and legal issues
* **Emotional distress** and psychological harm, particularly in romance scams
* **Career consequences** for employees who unknowingly facilitated a breach
* **Loss of personal data** including medical records, private communications, and photos



Social engineering attacks do not discriminate by age, profession, or technical knowledge. Elderly individuals, executives, and even cybersecurity professionals have fallen victim to well-crafted attacks.



## **5. Prevention Techniques**



### 5.1 Technical Measures



**Email Security:**



* Deploy **anti-phishing email gateways** (e.g., Proofpoint, Mimecast) that scan for malicious links and attachments
* Implement **DMARC, DKIM, and SPF** DNS records to prevent email spoofing
* Enable **sandboxing** to detonate suspicious attachments in an isolated environment



**Multi-Factor Authentication (MFA):**



* Enforce MFA on all critical systems and accounts
* Prefer hardware tokens (FIDO2/WebAuthn) or authenticator apps over SMS-based MFA
* MFA significantly reduces the impact of stolen credentials



**Web Filtering and DNS Security:**



* Use DNS-level filtering (e.g., Cisco Umbrella) to block known phishing and malicious domains
* Restrict access to unauthorized file-sharing and download sites



**Endpoint Protection:**



* Deploy Endpoint Detection and Response (EDR) solutions
* Automatically block execution of unauthorized removable media (USB drives)
* Maintain up-to-date patching to close zero-day vulnerabilities exploited by social engineering payloads



**Access Control:**



* Apply the **Principle of Least Privilege (PoLP)** — users should have only the minimum access required for their role
* Segment networks so that a compromised endpoint cannot freely reach sensitive systems





### 5.2 Organizational Policies



* **Acceptable Use Policy (AUP):** Define what employees can and cannot do with company systems and data
* **Verification Procedures:** Establish out-of-band verification (e.g., callback to a known number) before acting on requests for transfers, access changes, or sensitive data
* **Incident Response Plan:** Maintain and regularly test a documented plan for responding to social engineering incidents
* **Physical Security Policies:** Implement badge-based access control, mantrap entrances for sensitive areas, and a visitor escort policy to prevent tailgating
* **Wire Transfer Controls:** Require dual authorization and phone confirmation for any large or unusual financial transactions
* **Clean Desk Policy:** Prevent sensitive documents from being left visible or accessible in common areas



### 5.3 User Awareness and Training



* **Regular Security Awareness Training:** Conduct mandatory training for all employees at least annually, with refreshers for high-risk roles (finance, HR, IT)
* **Simulated Phishing Campaigns:** Use platforms like KnowBe4 or Proofpoint Security Awareness to run realistic phishing simulations and measure employee vulnerability
* **Reporting Culture:** Encourage employees to report suspicious emails or calls without fear of blame. Make reporting easy (e.g., a one-click phishing report button in email)
* **Role-Based Training:** Provide specialized training for privileged users, executives, and finance teams who are high-value targets
* **Social Engineering Awareness Drills:** Simulate pretexting calls or physical tailgating tests to evaluate and improve employee response



## **6. Best Practices for Individuals**



1. **Verify before you trust.** If someone requests sensitive information or urgent action — even if they claim to be from IT, HR, or management — verify their identity through a separate, known contact channel.
2. **Slow down when pressured.** Urgency is an attacker's tool. Legitimate organizations will not penalize you for taking a moment to verify a request.
3. **Do not click links in unsolicited emails.** Navigate directly to websites by typing the URL in your browser. Hover over links to inspect the actual destination before clicking.
4. **Use strong, unique passwords with a password manager.** Never reuse passwords across accounts. Use a reputable password manager such as Bitwarden or 1Password.
5. **Enable Multi-Factor Authentication (MFA)** on all accounts that support it, especially email, banking, and work systems.
6. **Be cautious about what you share online.** Information posted on LinkedIn, Facebook, or other platforms can be used to craft targeted spear phishing attacks against you.
7. **Do not plug in unknown USB drives or devices.** If you find a USB drive, do not insert it — report it to your security team.
8. **Lock your computer and desk.** Always lock your screen when stepping away, and secure sensitive documents.
9. **Report suspicious activity immediately.** If you suspect you've been targeted or have fallen for an attack, report it to your IT/security team immediately. Early response limits damage.
10. **Stay informed.** Subscribe to threat intelligence feeds and advisories from CISA, SANS Internet Stormcenter, or similar sources to stay current on active social engineering campaigns.





## **7. Conclusion**



Social engineering represents one of the most persistent and effective threats in the modern cybersecurity landscape. Unlike technical exploits that target software flaws, social engineering targets the most complex and unpredictable component of any system — the human being.

As demonstrated through multiple high-profile breaches, no organization — regardless of its size, resources, or technical sophistication — is immune. A single well-crafted phishing email or phone call can bypass millions of dollars worth of security infrastructure.

Defending against social engineering requires a **layered approach**: technical controls that reduce attack surface, organizational policies that establish secure workflows, and — most critically — a security-aware human workforce that can recognize and respond to manipulation attempts.

Security is not solely a technology problem. It is a **people problem**, and it demands a people-centered solution. Continuous education, a culture of healthy skepticism, and well-practiced reporting habits are as important as any firewall or endpoint solution.

The goal is not to create a culture of paranoia, but one of **informed vigilance** — where every individual understands that they are both a potential target and a critical line of defense.





## 8\. **References**



1. **Verizon Data Breach Investigations Report (DBIR) 2023**  
[https://www.verizon.com/business/resources/reports/dbir/](https://www.verizon.com/business/resources/reports/dbir/)

2. **IBM Cost of a Data Breach Report 2023**  
[https://www.ibm.com/reports/data-breach](https://www.ibm.com/reports/data-breach)

3. **CISA — Social Engineering and Phishing Attacks**  
[https://www.cisa.gov/topics/cybersecurity-best-practices/avoiding-social-engineering-and-phishing-attacks](https://www.cisa.gov/topics/cybersecurity-best-practices/avoiding-social-engineering-and-phishing-attacks)

4. **NIST Special Publication 800-63B — Digital Identity Guidelines**  
[https://pages.nist.gov/800-63-3/sp800-63b.html](https://pages.nist.gov/800-63-3/sp800-63b.html)

5. **SANS Institute — Social Engineering: The Art of Human Hacking**  
[https://www.sans.org/blog/social-engineering-the-art-of-human-hacking/](https://www.sans.org/blog/social-engineering-the-art-of-human-hacking/)

6. **Twitter Security Incident Report (2020)**  
[https://blog.twitter.com/en\_us/topics/company/2020/an-update-on-our-security-incident](https://blog.twitter.com/en_us/topics/company/2020/an-update-on-our-security-incident)

7. **RSA Security Breach — EMC Official Statement (2011)**  
[https://www.rsa.com/content/dam/en/white-paper/rsa-letter-to-customers.pdf](https://www.rsa.com/content/dam/en/white-paper/rsa-letter-to-customers.pdf)

8. **FBI Internet Crime Complaint Center (IC3) — Business Email Compromise**  
[https://www.ic3.gov/Home/BEC](https://www.ic3.gov/Home/BEC)

9. **KnowBe4 — 2023 Phishing by Industry Benchmarking Report**  
[https://www.knowbe4.com/phishing-industry-benchmarking-report](https://www.knowbe4.com/phishing-industry-benchmarking-report)

10. **MITRE ATT\&CK — Phishing Technique (T1566)**  
[https://attack.mitre.org/techniques/T1566/](https://attack.mitre.org/techniques/T1566/)





&#x20;Author



Security Analyst Intern  

GitHub: https://github.com/mahisurani06  

Project: Social Engineering Attacks Research Report  

