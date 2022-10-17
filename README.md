# SNHU-CS305-T1165-Software-Security
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a financial planning company that seeks to modernize its digital spaces with current software security practices in order to protect its clients personal and financial data. Their main requirement was to add a file verification step to their web application to ensure secure communications. This would be achieved through a data verification step using a checksum.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
Secure code is important because it serves as the foundation for the security of the entire application. By not following secure coding practices an application will lack basic software security and allow malicious users to take unintended actions against your users or company. Following good software security practices gives a company like Artemis Financial and their clients the peace of mind that their information will be kept private and safe.  

What part of the vulnerability assessment was challenging or helpful to you?
Part 6, Functional Testing, was the most challenging portion of the assessment for me.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased layers of security for this appliation by adding a checksum and converting the website from HTTP to HTTPS. The Vulnerability Assessment Process Flow Diagram is a very useful guide for reviewing sofware. I will continue to use it to guide me in assessing vulnerabilities. In addtion to the diagram the OWASP Cheat Sheet Series was a useful tool that included strategies for many software security vulnerabilities. I will continue to reference this website for mitigation techniques.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
One way to ensure the code remained functional and secure was to continually check to see if the code was executing without errors. Also, running depenedency check reports. After refactoring the code I would execute the program and run another dependency check report to see if any vulnerabilities were introduced. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The OWASP Cheat Sheet Series and the Vulnerability Assessment Process Flow Diagram are two tools/resources that were helpful in this assignment, and I will continue to use them in future tasks.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
The main element I would highlight from this assignment is the use of the checksum and how cryptography is used in web applications to protect data. The second thing I would highlight is how HTTPS is used as a standard in web applications to protect users.
