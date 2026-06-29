# CS 305 Portfolio Reflection – Artemis Financial Software Security

## Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a financial services company that required improvements to the security of its web application. The company wanted to protect sensitive financial information by implementing secure communications, identifying software vulnerabilities, and ensuring the application followed secure coding practices. The project focused on assessing security risks and strengthening the application against potential attacks.

## What did you do well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall well-being?

I successfully used automated vulnerability scanning to identify outdated dependencies and security risks within the application. After reviewing the results, I evaluated which findings required action and implemented improvements to strengthen the application's security. Secure coding is important because it protects sensitive information, reduces the risk of cyberattacks, and improves customer trust. Strong software security also helps organizations avoid financial losses, legal issues, and damage to their reputation.

## Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part was understanding the vulnerability scan results and determining which findings represented actual security risks versus false positives. At the same time, the assessment was valuable because it demonstrated how automated tools can quickly identify weaknesses that may not be obvious during manual code reviews.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I improved the application's security by implementing HTTPS communication, generating a secure certificate, updating vulnerable dependencies, and following secure coding practices. In future projects, I would continue using automated security scanners, dependency analysis tools, static code analysis, and manual code reviews to identify vulnerabilities and determine the most appropriate mitigation strategies.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

After making security improvements, I rebuilt the project, verified that it compiled successfully, and tested the application to confirm that it still functioned correctly. I also reran the vulnerability scan to verify that the identified issues had been resolved and that no additional vulnerabilities had been introduced during the refactoring process.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Throughout this project I used Eclipse, Maven, OWASP Dependency-Check, Java Keytool, and Spring Boot. I also relied on secure coding principles, dependency management, and code reviews. These tools and practices will continue to be valuable for developing secure software and identifying vulnerabilities in future projects.

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would include my completed security assessment report and vulnerability remediation work to demonstrate my understanding of software security principles. This project highlights my ability to identify vulnerabilities, interpret security scan results, implement secure coding practices, and verify that applications remain both functional and secure after making changes.
