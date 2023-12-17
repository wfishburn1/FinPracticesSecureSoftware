# FinPracticesSecureSoftware

**Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?**

Artemis Financial is a global financial services provider; their software requirements include creating and managing personalized financial plans through a secure RESTful web API. The primary goal is to offer financial programs to clients worldwide. The client sought to address software security concerns, specifically the need for secure communication, encryption, and code refactoring compliant with software security testing protocols.


**What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?**

When addressing Artemis Financial's software security vulnerabilities, I implemented industry standard encryption algorithms, specifically SHA-256 and AES-256, and introduced a Logger instance to enhance secure coding practices. Ensuring a proactive stance on security is fundamental as it mitigates potential risks, upholds the confidentiality of sensitive financial data, and preserves the overall integrity of the system. The importance of coding securely is multifaceted, protecting against unauthorized access, data breaches, and potential harm to the organization's reputation.

**What part of the vulnerability assessment was challenging or helpful to you?**
Initially, one of the challenges included the analysis of which vulnerabilities were relevent to the program. Due to my lack of experience with the vulnerability assessment process flow, I needed to train my mind and eyes to recognize the correct vulnerabilites related to the program.

However, the assessment was extremely helpful in identifying and improving security areas once I understood the different components more clearly. It deepened my understanding of potential risks and emphasized the importance of a holistic approach to software security.

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

To enhance security layers, I implemented robust encryption algorithms, opting for SHA-256 and AES-256, and incorporated secure coding practices like introducing a Logger instance for improved error management. In the future, I would employ a combination of static code analysis tools, penetration testing, and regular security audits to assess vulnerabilities comprehensively. 

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

To ensure both functionality and security I conducted thorough testing, including functional testing and dependency checks using the OWASP dependency vulnerability report. Post-refactoring code, my testing verifed the code's functionality and identified any potential new vulnerabilities. This involved executing the refactored code and verifying checksums, as well as reassessing the OWASP report to ensure that the code changes did not compromise the system's security.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

In future assignments, I'll use robust encryption like SHA-256 and AES-256, along with secure coding practices like input sanitation, error handling and Logger implementation. These will prove fruitful when implementing a strong security strategy. Now I also know to rely on tools like OWASP for insights into potential dependency risks. Moreover, the ability to generate and self-sign my own SSL certificates, add them to my own device's/browser's trust store and use them within a program is quite handy!

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**


In presenting this assignment to future employers, I would highlight key elements that showcase my skills, knowledge, and experience. Specifically, I'd emphasize the successful implementation of robust encryption algorithms such as SHA-256 and AES-256, underlining my capability to secure sensitive data effectively. The incorporation of secure coding practices, notably the introduction of a Logger instance, illustrates my commitment to error management and system integrity.

Furthermore, I would highlight the use of industry-standard tools like the NIST OWASP dependency vulnerability report, demonstrating my proactive approach to identifying and addressing potential risks in production-level software development. The documentation of the code refactoring process, including detailed explanations and before-and-after snapshots, serves as evidence of my ability to navigate codebases, improve system security, and enhance overall software quality.
