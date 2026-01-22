# Telegram-scams
Greetings! This project will look at popular types of fraud in telegram, and the code for these tools will also be posted here. P.S.: I am not responsible for the actions that you may take with these utilities, I post these files as experiments and observations.
Well, my nickname is Dr.Firewall and this is the first entry. Recently, I personally had to deal with telegram fraud, after which I decided to explore this topic and share it with you. Perhaps I'll start with the "demolition" of telegram accounts. Recently, scammers have begun to intimidate a lot of neutral people.
# Telegram Fraud Investigation Project

**Author:** Dr.Firewall  
**Status:** First entry

## Introduction

This project examines popular types of fraud occurring on Telegram. The code for the tools used in these scams will be shared here for educational purposes.

> **P.S.** I am not responsible for any actions you may take with these utilities. These files are posted solely for experimental and observational purposes.

## Personal Experience

Recently, I encountered Telegram fraud firsthand. This experience motivated me to explore and share insights on this topic. Let's begin with the issue of **Telegram account "demolition"** — a growing concern as scammers increasingly target neutral individuals.

## Common Scam Methodology

Scammers typically follow this pattern:

1. **Initial Contact**  
   They reach out via games or other online resources, targeting both children and adults.

2. **Luring to Telegram**  
   They invite the victim to Telegram with tempting offers (e.g., free money or in-game items).

3. **Gathering Information**  
   They request direct communication on Telegram to extract account registration data and the user's **account ID**.

4. **Data Harvesting**  
   Using specialized utilities, they collect personal information about the victim.

5. **Controlled Dialogue**  
   Initially polite, they maintain scripted conversations. However, if the victim deviates, the tone shifts.

6. **Demonstrating "Power"**  
   They reveal personal data (e.g., email addresses, recently visited websites) to intimidate the victim — even if the data is publicly available or falsified.

7. **Threatening Phase**  
   Scammers issue dire warnings:
   - Physical harm ("You'll end up in the hospital").
   - Legal trouble ("You'll go to jail").
   - Financial exploitation ("We'll use your cards for illegal activity").

8. **Psychological Impact**  
   The victim may experience:
   - Severe anxiety.
   - Apathy.
   - In extreme cases, suicidal thoughts.

9. **Ransom Demand**  
   Finally, they demand payment in exchange for:
   - "Protecting" the victim's data.
   - Preserving the victim's Telegram account.

## Next Steps

Tomorrow, I will:
- Share a **sample code** received from a scammer.
- Explain how the code operates.

In future entries, we will:
- Analyze other tools scammers use to harvest data.
- Discuss practical methods to protect yourself.

Stay tuned for more insights!


# How Telegram «Account Removal» Teams Work: Myths, Reality, and Technical Aspects


In the Russian‑speaking segment of Telegram, the term **«account removal team»** (or **«account takedown service»**) is frequently used. This refers to an unofficial service that allegedly can delete (or «take down») any unwanted Telegram account or channel. In this article, we will examine what lies behind this concept, how Telegram moderation actually works, and the technical and social methods used to target accounts.

## Official Paths for Content Removal

Before discussing unofficial methods, it’s important to understand the legal mechanisms.

### The «Report» Function

Every user can report a message, channel, or account using the built‑in function.


**Reasons:**  
- Spam;  
- Violence;  
- Child abuse;  
- Copyright infringement;  
- etc.

**Process:**  
The report goes to Telegram’s *Trust and Safety Team*. Decisions are made by humans based on the Platform’s *Terms of Service*. A mass influx of reports from different users may increase the priority of the case, but there is no automatic deletion based solely on the number of reports.

### Copyright Holder Requests (DMCA)

For materials infringing copyrights, there is an official takedown request procedure. This is a legal, not a technical, process.

### Judicial Authorities’ Requests

Telegram, like many platforms, may block accounts or content based on court decisions in jurisdictions where it operates officially (e.g., as a legal entity in some countries). This primarily concerns extremist and illegal content.

**Conclusion:** Officially, it is impossible to simply «take down» an account on request and for money. Valid grounds that violate the platform’s rules are required.

## What Do «Removal Teams» Actually Offer?

These services exploit vulnerabilities in moderation systems and social engineering.

### Mass Coordinated Reporting (Raid Reporting)


**Mechanism:** A group of people is organized or bots are used to mass‑report a target account for a chosen violation (most commonly «pornography», «violence», «extremism»).

**Goal:** To «flood» the moderation system, creating the illusion of a serious and widespread violation. If an abnormally large number of reports arrives in a short time, the system may temporarily restrict the account (e.g., impose a «shadow ban» or flag it for review) to minimize potential harm.

**Effectiveness:** Low/Medium. Telegram’s modern anti‑spam systems can detect report manipulation from the same devices or IP addresses. It has little effect on long‑standing and reputable accounts. It’s more a tool for harassment than guaranteed removal.

### Hacking and Subsequent Rule Violation


**Mechanism:** Methods like phishing, password brute‑forcing, or purchasing leaked data (cookies, sessions) are used to gain access to the victim’s account.

**Actions Inside the Account:** After hacking, the attacker can:
- Mass‑distribute spam or rule‑breaking content (brutality, pornography), which will almost certainly lead to an account ban by automated systems;
- Simply delete the account/channel from within.

**Effectiveness:** High, if the hack is successful. However, this is a criminal offense (e.g., Article 272 of the Russian Criminal Code and equivalents). This method is expensive and risky for the «performer».

### Social Engineering Against Telegram Support

**Mechanism:** The perpetrator, posing as a victim (e.g., the owner of a hacked account or a copyright holder), attempts to convince Telegram support of the urgent need to delete an account. Forged documentation may be used.

**Effectiveness:** Very low. Telegram’s support is known for its minimalist approach and slow response. Carrying out such an operation is difficult without high‑level skills and information about the victim.

## Technical Aspects of Telegram’s Protection


Why is «removal» so difficult? Because of Telegram’s architecture.

- **Decentralized Moderation:** There is no single «kill switch». Decisions are made by a distributed team, complicating corrupt schemes.
- **Automated Abuse Detection Systems (Anti‑Spam, Anti‑Flood):** These systems analyze behavioral patterns (reports, messages, chat joins) and easily filter out primitive attacks.
- **Priority on Data Preservation:** Telegram’s philosophy is free speech and privacy. Deleting an account without extreme grounds contradicts this philosophy.
- **Two‑Factor Authentication (2FA) and Active Sessions:** Significantly complicate hacking, even if the password or phone number is known.

## Myths and Risks

**Myth 1:** «There is a bot/person at Telegram who, for money, will delete any account.»  
This is almost always a scam. The buyer will either be given the impression that work is being done (by organizing fake reports) or the «performer» will simply take the prepayment and disappear.

**Myth 2:** «It’s enough to send N reports, and the account will be banned.»  
This is false. The system considers not the quantity but the quality and source of reports.

**Risks for the Customer:**  
- Loss of money;  
- Getting one’s own account blocked for report abuse;  
- In the case of ordering a hack — criminal liability as an accomplice.


**Risks for the Victim:**  
The most real threat is hacking. Therefore, it is critical to enable 2FA, use a strong password, and be cautious of phishing.


## Recommendations for Protecting Your Account


1. **Enable Two‑Factor Authentication (2FA)** in Telegram settings. This is the main shield.
2. **Set a password for the SMS verification code.**
3. **Regularly check** *Settings → Devices* and terminate all unfamiliar active sessions.
4. **Do not click on suspicious links** and do not enter your Telegram code on third‑party sites.
5. **Be skeptical.** If you are threatened with «removal», it is most likely a bluff. But check points 1–4.

## Conclusion


«Account removal teams» are, for the most part, either scammers selling empty promises or hackers offering to commit a crime. Telegram’s actual moderation is designed to withstand such primitive attacks.

Reliable «removal» is only possible through official channels and in the presence of real, gross violations of the platform’s rules. Everything else is the exploitation of users’ fears and lack of knowledge.

The best protection is enabled 2FA and common sense.

## What’s Next?

In a future article, I will conduct a deeper dive into practical cybersecurity:

- **Practical Defense Guide:** A step‑by‑step walkthrough on configuring the most secure settings for your Telegram account, including advanced 2FA options, passphrase management, and recognizing sophisticated phishing attempts.
- **Analysis of Data‑Gathering Tools:** I will analyze other tools and techniques commonly used by malicious actors to gather target data, such as OSINT (Open Source Intelligence) frameworks, phone number enumeration methods, and social media scraping. Understanding these tools is key to minimizing your digital footprint and protecting your privacy.

Stay tuned for a hands‑on, technical guide to fortifying your digital presence.

> **Disclaimer:** This article is for informational purposes only. The author does not encourage illegal activities and is not responsible for the use of this information.


Stay secure.  
— Dr.Firewall

