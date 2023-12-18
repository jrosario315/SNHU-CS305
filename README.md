# SNHU-CS305

### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a consulting company that develops unique financial plans for each of its clients, which include savings plans, investment plans, retirement plans, and insurance plans. This company wanted to modernize their operations and one of the ways that they wanted to do this was through improving their software's security system. 

### What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

In finding vulnerabilities in Artemis Financial's software security system, I did well in implementing an industry-standard system for the company to be able to use moving forward. This was through the algorithms used as well as the general secure coding practices implemented throughout the refactoring of the code. It is important to code securely because of the risks that insecure code leaves up. An example of this is the Artemis Financial system, which deals with sensitive consumer data like credit card numbers and personal information. Vulnerable code could leave this information up for grabs to any malicious user that is looking to exploit the weak code. Overall, a strong and properly implemented software security system allows a company to excel in their field, instead of the focus being on how they are handling consumer data. A company with few incidents relating to consumer data builds its reputation, which further gains the trust of larger and larger clients. A secure software system may not always get as much attention within a company, but it is essential to a company's success.

### What part of the vulnerability assessment was challenging or helpful to you?

Personally, the certificate generation was particularly helpful for me but the implementation of the encryption algorithm cipher came as more of a challenge to me. I hadn't worked with encryption algorithms before and so I had to go through learning how they worked before I could even begin with the implementation. I continuously ran into errors throughout the process, but overall, it was a helpful learning experience for the future as well.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

To increase the layers of security, I implemented an ecnryption algorithm to the Artemis Financial software system, as well as well as updating libraries. In the future, I will continue to use dependency checks for inspecting vulnerabilities, as they were insightful in vulnerable dependencies. I can also implement a sort of penetration testing to try and further expose potential exploits within the system.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I made certain that the code was functional and secure firstly by simply running it and makingg sure that it behaved how I expected it to behave. I then implemented the use of the HTTPS protocol to create a secure communication line and security certificates along with that. I used the dependency check reports to monitor for any new vulnerabilities that may have been introduced after the refactored code.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

The implementation of the cipher algorithms is one of the main takeaways that I had from this assignment, as it challenged me to look through different resources to understand the information that I needed. Becoming more familiar with the Maven framework and the dependency checks were also a useful tool that I will implement in future programs.

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I might show them the refactored code and the implementation of the cipher algorithms to demonstrate my knowledge in that area.
