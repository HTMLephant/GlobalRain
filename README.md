# Author: Matthew Cochrane

# GlobalRain
Module Eight Submission for CS-305

# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
  Artemis Financial is a consulting company that develops individualized financial plans for their customers. They want to have some sort of file verification system implemented.

# What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
  I implemented the checksum in as few lines as possible. The end result is clean and concise code. Checksums in general are great to have for any company's software because it establishes a decentralized trust between the client and the server, giving both peace of mind.

# What part of the vulnerability assessment was challenging or helpful to you?
  The certificate generation was most challenging to me as well as the most helpful. It was the first time I had ever really interacted with Command Prompt and saw what it can do.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  The two main ways that I added layers of security were generating an SSL certificate and a checksum validation step. Maven is a tool that I plan on using in the future since it provide vulnerability assessments through other frameworks such as Spring and JUnit.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
  I went to the HTTPS link for the project and saw the information that I expected to see.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  All of the tools used in this assigment are helpful in the future. Specifically, this includes KeyTool, JUnit, Spring, and checksum verification.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  I would show them my report as it demonstrated that I know how to do all of the things that were requested by the assignment.
