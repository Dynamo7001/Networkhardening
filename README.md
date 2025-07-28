# Networkhardening
# **Scenario**

**Review the following scenario. Then complete the step-by-step instructions.**

You are a security analyst working for a social media organization. The organization recently experienced a major data breach, which compromised the safety of their customers’ personal information, such as names and addresses. Your organization wants to implement strong network hardening practices that can be performed consistently to prevent attacks and breaches in the future. 

After inspecting the organization’s network, you discover four major vulnerabilities. The four vulnerabilities are as follows:

The organization’s employees' share passwords.

The admin password for the database is set to the default.

The firewalls do not have rules in place to filter traffic coming in and out of the network.

Multifactor authentication (MFA) is not used. 

If no action is taken to address these vulnerabilities, the organization is at risk of experiencing another data breach or other attacks in the future. 

In this activity, you will write a security risk assessment to analyze the incident and explain what methods can be used to further secure the network.

# **Security risk assessment report** 

**Part 1: Select up to three hardening tools and methods to implement**
After the recent breach that just happened, I discovered that some network hardening was not put in place, which allowed this breach to be successful. I recommend these four hardening tools and methods to be implemented to prevent this type of breach and unknown breaches in the future.

**Password policies:** This is the National Institute of Standards and Technology's (NIST) latest recommendations for password policies, focusing on using methods to salt and hash passwords, rather than requiring overly complex passwords or enforcing frequent changes to passwords. This can be done by setting rules of encryption immediately after a new user password is set.

**Network access privileges:** Network access privileges involve permitting, limiting, and/or blocking access privileges to network assets for people, roles, groups, IP addresses, MAC addresses, etc. This can be implemented for every employee based on their role in the organisation.

**Multifactor authentication (MFA):** A security measure that requires a user to verify their identity in two or more ways to access a system or network. MFA options include a password, PIN number, badge, one-time password (OTP) sent to a cell phone, fingerprint, and more. This helps to mitigate the risk of brute force attacks by threat actors. This should be compulsory for every employee by using their password and any biometric method (fingerprint, iris scan, or face scan). 

**Port filtering:** This is a firewall function that blocks or allows certain port numbers to limit unwanted communication. Port filtering rules need to be put in place in the firewall rules to filter unknown and not allowed ports from having access to the organization network. 



# **Part 2: Explain your recommendations**

I recommend these four implementations because of these reasons.

1. Password policies help to prevent attackers from easily guessing user passwords, either manually or by using a script to attempt thousands of stolen passwords (commonly called a brute force attack).


2. Network access privileges help to reduce the risk of unauthorized users and outside traffic from accessing the internal network. This can be implemented once or revisited depending on the likelihood of social engineering or brute force attacks.

3. Multifactor authentication (MFA) helps protect against brute force attacks and similar security events. MFA can be implemented at any time and is mostly a technique that is set up once and then maintained.

4. Port filtering helps control network traffic and can prevent potential attackers from entering a private network.




