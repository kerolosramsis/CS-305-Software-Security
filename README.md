# CS-305-Software-Security

This repository contains coursework and portfolio artifacts from CS 305 Software Security.

## Artemis Financial

Artemis Financial is a financial consulting company that wanted to improve the security of its software application. The company needed help identifying security vulnerabilities and making sure sensitive financial and customer information was protected. The main issue was making the application more secure by using stronger encryption, secure communication, and vulnerability testing.

I did well identifying security weaknesses and applying secure coding practices to the application. I used SHA-256 for checksum verification, configured HTTPS, generated a certificate, and used OWASP Dependency-Check to scan for known vulnerabilities. Secure coding is important because it helps protect sensitive information and reduces the risk of security breaches. Strong software security also helps a company maintain customer trust and protect its reputation.

One challenging part of the vulnerability assessment was understanding the Dependency-Check results because the report showed many vulnerabilities in the existing project dependencies. It was also helpful because it showed me how security tools can find problems that may not be obvious from only reading the code.

I increased the layers of security by adding HTTPS, using a certificate and keystore, and adding SHA-256 checksum verification. I also performed dependency scanning and manual testing. In the future, I would use tools such as OWASP Dependency-Check, code reviews, and vulnerability assessment processes to identify risks and decide which security fixes are most important.

I made sure the application remained functional by running the refactored code and checking that the application started successfully. I tested the checksum endpoint in the browser and verified that the application used HTTPS on port 8443. After refactoring, I ran Dependency-Check again to identify known vulnerabilities and make sure the changes did not introduce new dependency-related security issues.

Some of the resources and tools I used included Java keytool, SHA-256 hashing, HTTPS configuration, Maven, Eclipse, and OWASP Dependency-Check. I also used manual code review and testing to check for syntax, logic, and security problems. These tools and practices will be useful in future programming and software security projects.

For future employers, I could show the completed Practices for Secure Software Report from this project. It demonstrates my ability to identify security risks, use secure coding practices, configure HTTPS, work with certificates, use cryptographic hashing, run vulnerability scans, and test a software application after making security changes.
