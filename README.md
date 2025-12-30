# OWASP Top 10 web app vulnerabilities 
This is a day to day basis top web application vulnerabilities explored using OWASP top 10 SKF Linux Foundation course.

# Course Summary
## Broken Access Control
In this module, we explored the risk of broken access control, which arises when restrictions on authenticated users are improperly enforced. Attackers can exploit these vulnerabilities to access unauthorized functionalities or data. We’ve seen how enforcing strict access control measures and principle of least privilege helps to mitigate such risks.

## Cryptographic Failures
This section introduced you to the concept of cryptographic failures. These are the risks associated with the misuse of cryptography, often resulting in the exposure of sensitive information. Our hands-on labs demonstrated the importance of implementing secure cryptographic practices, like using updated cryptographic algorithms and securing cryptographic keys.

## Injection
We studied various injection attacks, such as SQL, NoSQL, OS, and LDAP injection. These vulnerabilities occur when untrusted data is sent as part of a command or query. You’ve seen firsthand the impact of successful injection attacks and learned how to prevent them using input validation, parameterized queries, and other secure coding practices.

## Insecure Design
In this module, we emphasized the importance of secure design principles in software development. The insecure design risk underlines how design flaws can lead to large-scale security vulnerabilities. Through practical examples, we discovered how a ‘security by design’ approach can mitigate such risks.

## Security Misconfiguration
Here we examined the potential dangers of security misconfiguration, which is often the result of insecure default configurations, incomplete or ad hoc configurations, or unprotected cloud storage. Our lab exercises demonstrated how to detect these vulnerabilities and the necessity of a well-defined, repeatable hardening process.

## Vulnerable and Outdated Components
This part of the course focused on the risks posed by the use of vulnerable and outdated software components. We practiced identifying, updating, and removing such components to minimize the attack surface.

## Identification and Authentication Failures
We learned about the threats arising from flawed identification and authentication strategies, which can allow attackers to impersonate users or bypass authentication. We explored techniques for implementing multi-factor authentication, strong password policies, and secure session management to help combat these threats.

## Software and Data Integrity Failures
In this module, we addressed the importance of maintaining the integrity of software and data. You experienced how a lack of proper integrity controls can lead to unauthorized data modification or code execution. We also examined defenses such as checksums, digital signatures, and secure file permissions.

## Security Logging and Monitoring Failures
Here we discussed the lack of adequate logging and monitoring, which could delay or prevent the detection of security breaches. We observed the value of comprehensive and proactive monitoring practices and learned how to implement effective logging mechanisms that capture important security-related events.

## Server-Side Request Forgery (SSRF)
The course concluded with an exploration of SSRF, where malicious actors can induce the server to perform requests on their behalf. We discussed various techniques for mitigating this risk, such as validating and sanitizing all input data, employing allow-lists of approved servers, and applying the least privilege principle.

