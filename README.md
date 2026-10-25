# CS-305 Software Security

## Project Overview

In this course, I worked with Artemis Financial, a financial consulting company that develops individualized financial plans for its clients. The company wanted to improve the security of its software application to protect sensitive financial information. My responsibility was to identify potential vulnerabilities and implement security improvements to ensure the application could communicate securely and protect client data.

## What did you do well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall well-being?

I successfully used OWASP Dependency-Check to identify potential vulnerabilities in the application's dependencies and reviewed the results to better understand possible security risks. I also learned how to evaluate vulnerabilities and identify false positives rather than assuming every reported issue was an actual threat. Secure coding is important because it helps prevent unauthorized access, protects sensitive information, and reduces the risk of security breaches. For a financial company like Artemis Financial, strong software security also helps maintain customer trust and protects the company's reputation.

## Which part of the vulnerability assessment was challenging or helpful to you?

One of the most challenging parts of the vulnerability assessment was learning how to configure and run OWASP Dependency-Check in Eclipse using Maven. I also had to understand the vulnerability reports and determine how to address the findings. Working with the suppression file helped me understand how false positives can be documented and managed. This experience was helpful because it showed me that identifying vulnerabilities is only one part of software security. Developers also need to understand the results and determine appropriate actions.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased security by implementing HTTPS communication using SSL/TLS and generating a self-signed certificate with a Java keystore. This allowed the application to use an encrypted connection rather than transmitting information over an unsecured HTTP connection. I also used dependency scanning to identify potential risks associated with third-party libraries. In the future, I would continue using tools such as OWASP Dependency-Check, vulnerability databases, and secure coding guidelines to evaluate risks and determine which security improvements are necessary.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

After making changes to the application, I ran the project in Eclipse and verified that the HTTPS endpoint was functioning. I also reviewed the application output and used the browser to confirm that the secure connection was available. Because the certificate was self-signed, the browser displayed a security warning, which I documented in my report. I used dependency scanning and reviewed the results to help identify potential vulnerabilities. This process taught me the importance of testing an application after making security changes to ensure it still functions correctly and to check for newly introduced risks.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Throughout this project, I used Eclipse, Java, Maven, OWASP Dependency-Check, and Java keytool. I also gained experience working with SSL/TLS certificates, dependency reports, and vulnerability suppression files. Breaking the project into smaller steps, reviewing error messages, and testing changes as I worked helped me troubleshoot problems more effectively. These are practices I plan to continue using in future programming assignments and professional software development projects.

## What might you show future employers from this assignment?

I would show future employers my Artemis Financial Practices for Secure Software Report because it demonstrates my experience identifying security concerns, implementing HTTPS communication, and testing a Java application. The report includes documentation and screenshots showing the security improvements I made. This project demonstrates my ability to apply secure coding practices, use vulnerability assessment tools, and document my work in a professional manner.
