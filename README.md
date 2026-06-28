# CS 305 Portfolio Reflection

## Artemis Financial Secure Software Project Reflection

### Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a financial services company that needed to improve the security of its web application to protect sensitive customer information and maintain secure communications. The client wanted to address vulnerabilities in its software by implementing secure coding practices, encrypting data transmissions, and ensuring that the application met modern security standards. The primary goal was to reduce security risks while maintaining the functionality and reliability of the application.

### What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

One area where I performed well was identifying and addressing software security vulnerabilities through dependency analysis and secure coding practices. I updated the OWASP Dependency-Check plugin to use the latest version and configured it to run only when necessary, which improved efficiency while still maintaining security coverage. Coding securely is important because it protects sensitive data, reduces the likelihood of attacks, and helps maintain customer trust. Strong software security also benefits a company by reducing financial losses, protecting its reputation, and ensuring compliance with industry standards.

### Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part of the vulnerability assessment was understanding how different dependencies could introduce security risks into an application. However, this process was also helpful because it demonstrated the importance of maintaining up-to-date libraries and regularly scanning projects for known vulnerabilities. Learning how to interpret dependency reports provided valuable experience that can be applied to future software projects.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased the layers of security by implementing HTTPS communication through SSL certificates, configuring a keystore, adding checksum verification functionality through a SHA controller, and updating application properties to support secure connections. In future projects, I would continue using tools such as OWASP Dependency-Check, static code analysis tools, and vulnerability scanning techniques to assess risks and determine appropriate mitigation strategies.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To ensure that the software remained functional and secure, I tested the application after each change and verified that the project built successfully using Maven. After refactoring the code, I reran dependency scans and validated that secure communication was working correctly to ensure that no new vulnerabilities had been introduced. This process helped confirm that both security and functionality requirements were satisfied.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Several resources and tools were particularly useful throughout this project, including Maven, the OWASP Dependency-Check plugin, Java keytool utilities, Spring Boot security configurations, and checksum verification techniques. These practices and tools will continue to be valuable in future assignments and professional software development tasks because they promote secure development throughout the software lifecycle.

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

For future employers, I would showcase the Artemis Financial Practices for Secure Software Report as evidence of my ability to identify vulnerabilities, implement secure coding practices, configure encrypted communications, perform dependency analysis, and validate software security after making changes. This project demonstrates both technical skills and an understanding of the importance of security within the software development process.
