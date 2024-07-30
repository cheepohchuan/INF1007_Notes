Weekly Quiz Answer
[[L8 Quiz Answers]]

# Information Security
the practice of protecting information by mitigating information risk.

- Typically involves reducing the probability and impacts of unauthorized/inappropriate access, use, disclosure, disruption, modification, destruction, recording, or revaluation of data and information.

Key information Attributes:
- Confidentiality
- Integrity
- Availability

Information systems components:
- Hardware
- Software
- Communication

3 Layers of security:
- Physical
- Personal
- Organizational

Threats to Information security:
1. Malware
2. Vulnerabilities in software and systems
3. Unsecured wireless networks
4. Phishing and social engineering
5. Insider threats
6. Physical threats
7. Data breaches
8. Denial of service attacks

## Weakest link in information security
- Human element is the weakest link:
	- Lack of information security awareness
	- Human Error
	- Bring your own device (BYOD) practices
- Important for organizations to offer
	- Education and training programs
	- regular security awareness campaigns

# Relevant Laws and Regulations
- Cybersecurity Act: 
	- The Cybersecurity Act provides a framework for the regulation of critical information infrastructure (CII) in Singapore.
- Computer Misuse Act (CMA): 
	- The CMA criminalizes various cyber activities, including unauthorized access, hacking, and computer-related offenses.
- Telecommunications Act: 
	- The Telecommunications Act regulates the telecommunications industry in Singapore.
- Official Secrets Act (OSA): 
	- The OSA is aimed at protecting official information related to the government and public agencies.
- Copyright Act: 
	- The Copyright Act protects intellectual property rights, including software and digital content.

# Hacking Culture
Hackers: People with a high level of skills at computing
## Hacker ethics
a set of values and beliefs that guide the behaviour of hackers. 

The general tenets or principles of hacker ethics include:
 - Sharing
 - Openness
 - Decentralization
 - Free access to computers
 - World improvement (e.g., upholding democracy and privacy)

Influential in development of Internet, open-source software movement, P2P file sharing and cryptography.

Black Hat Hackers: Malicious/Criminal Hackers

# Hacker Ethics vs Code of Ethics and Law
- Example 1: In line with hacker ethics, a hacker may break into systems to use idle computer and communications resources and download system files in order to learn.
	- Violation of ACM Code of Ethics “2.8 Access computing and communication resources only when authorized or when compelled by the public good.”

- Example 2: In line with the sharing tenet, a hacker may share copyrighted materials on P2P networks so that more people can benefit from the shared intellectual properties.
	- Contradicts with ACM Code of Ethics “1.5 Respect the work required to produce new ideas, inventions, creative.”

- Activities in both examples illegal in Singapore.

Example:
- In 2013, Edward Snowden, a former contractor for the National Security Agency (NSA) in the United States, leaked classified documents to journalists, revealing the existence and scope of various global surveillance programs operated by the NSA.
	- Violation of ACM Code of Ethics “1.7 Honor confidentiality.”
	- Violation of US Law
		- Espionage Act of 1917
		- The theft of government property


Importance of following code of ethics and law:
Observe the industry codes of ethics, and DO NOT BREAK THE LAW 


# Ethical Issues and Dilemmas in Information Security

__Information Security as Credence Good__

1. Search Goods:
	- Goods with attributes that can be evaluated prior to purchase or consumption. Examples of search goods include clothing, office stationery, home furnishings.
2. Experience Goods:
	- Goods that can be accurately evaluated only after the product has been purchased and experienced. Examples include novels, music, movies and restaurants.
3. Credence Goods:
	- Goods that are difficult or impossible to evaluate even after consumption has occurred. Examples include medical diagnosis/treatment, car repairs, legal services, and information security.

### __Information Security as Credence Good__
- Consumers of credence goods may rely on price as quality indicator
- Market forces can help regulate professional practices to a certain extent

### Ethical Hacking and Penetration Testing
- Ethical hackers must first obtain proper authorization to perform their hacking activities.
- Ethical hackers may come across confidential or sensitive information during their assessments. They should handle such information with care, maintain confidentiality, and not disclose it to unauthorized individuals or misuse it for personal gain.
- Some relevant clauses in ACM Code of Ethics
	- 1.2 Avoid harm
	- 1.6 Respect privacy
	- 1.7 Honor confidentiality

# Disclosure of Vulnerabilities
- Disclosing a vulnerability can be a complex ethical dilemma.
- There are 2 general approaches
	1. __Responsible disclosure__: Involves reporting the vulnerability to the relevant parties (such as the vendor or software developer) before making it public or sharing it with unauthorized individuals.
	2. __Full disclosure__: Involves making the vulnerability information available to the public, including potential attackers.


Responsible disclosure is more consistent with the ACM Code of Ethics.
- 1.2 Avoid Harm
- 2.1 Strive to achieve high quality in both the processes and products of professional work
- 2.9 Design and implement systems that are robustly and usably secure.

Full disclosure may have legal consequences, e.g., breaching of non-disclosure agreements.


# Firesheep Case Study
Sidejacking: Hijacking of an open Web session by capturing a user's cookie.
- Unencrypted wireless networks are vulnerable to sidejacking.
- Internet security community complained about the sidejacking vulnerability for years, but ecommerce sites did not change practices.
- In October 2010, Eric Butler released Firesheep, which made it easy for average computer users to sidejack Web sessions.

Impacts:
- As a result of the Firesheep incident, many popular websites, such as Facebook and Twitter, started implementing stronger security measures, such as enabling full end-to-end encryption (HTTPS) by default, to protect users' session information.

Butler's Response:
- “The attack that Firesheep demonstrates is easy to do using tools that have been available for years. Criminals already knew this, and I reject the notion that something like Firesheep turns otherwise innocent people evil.”

## Utilitarian Analysis of Firesheep
- Benefits :
	- Firesheep increased public awareness of the importance of good security practices
	- Many websites implemented stronger security measures to protect users’ session information
- Harms:
	- Minimal. No evidence that release of Firesheep caused big increase in identity theft or malicious pranks.
- Conclusion: Release of Firesheep was good.

## Kantian Analysis of Firesheep
- Butler’s goal was to pressure websites to adopt proper security measure to protect their users.
- To achieve this end, Butler provided a tool that made it easy for people sidejack Web sessions.
- Butler sacrificed a few victims of Firesheep to pressure websites to improve their security. He treated victims of Firesheep as a means to his end.
- Conclusion: Release of Firesheep was wrong.