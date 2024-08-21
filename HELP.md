# Artemis Financial Security Report

This repository contains the **Artemis Financial Practices for Secure Software Report**. This report demonstrates my ability to refactor code securely and implement secure communication mechanisms for Artemis Financial, a client specializing in financial consulting.

## Client and Software Requirements
**Client:** Artemis Financial  
Artemis Financial needed to enhance the security of their web application. They required secure communication mechanisms to protect their client data and financial information during file transfers.

## Software Security and Value to the Client
I successfully identified and addressed software security vulnerabilities in Artemis Financial's web application. By implementing SSL/TLS encryption and checksum verification, I ensured that data transmitted between clients and servers was secure and that file integrity was maintained. Secure coding practices are crucial as they protect the company’s data from potential breaches, preserving its reputation and client trust.

## Challenges and Insights from the Vulnerability Assessment
The vulnerability assessment was both challenging and insightful. The use of the OWASP dependency-check tool provided valuable insights into third-party dependencies and their vulnerabilities, helping to mitigate risks early in the development process.

## Enhancing Security Layers
To increase the security layers, I implemented HTTPS for encrypted communication and added checksum verification for data integrity. In the future, I plan to use tools like OWASP ZAP and dependency-check for continuous vulnerability assessments.

## Ensuring Code Functionality and Security
After refactoring the code, I used Spring Boot testing and static code analysis to ensure that the application was both functional and secure. Running the OWASP dependency-check again helped ensure that no new vulnerabilities were introduced during refactoring.

## Tools and Resources
Key resources included the Java `keytool` for SSL certificate generation, Spring Boot for secure application development, and the OWASP dependency-check for vulnerability analysis. These tools will be helpful for future secure coding assignments.

## Demonstrating Skills to Employers
This project showcases my ability to enhance software security by implementing SSL encryption and conducting vulnerability assessments. This artifact highlights my knowledge of secure coding practices and my ability to ensure data protection, which are valuable skills for future roles.
