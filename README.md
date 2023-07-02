# Web-Application-Penetration-Testing---SmartBridge

# Project Name

Web Application Penetration Testing

## Overview

The objective of this project is to conduct an in-depth web application penetration testing, also known as ethical hacking, to identify vulnerabilities and 
weaknesses in web applications. By simulating real-world attacks, the project aims to assess the security measures implemented in web applications and provide
valuable insights into potential risks and mitigation strategies. The testing is performed within a virtualized environment using VirtualBox, Kali Linux, and 
Metasploitable 2. Two websites have been selected for this project: a practice website (Metasploitable 2) and a target website (batterybhai.com).

## Purpose

The purpose of web application penetration testing is to proactively identify and address security vulnerabilities before malicious actors can exploit them. By 
conducting these tests, organizations can enhance the security of their web applications, protect sensitive information, and ensure the availability and reliability
of their services. The project's ultimate goal is to provide actionable recommendations to improve the security posture of the tested web applications.


### Proposed solution

The proposed solution in this project is to conduct web application penetration testing using a virtualized environment consisting of VirtualBox, Kali Linux, and
Metasploitable 2. The project proceeds through various stages, including information gathering, vulnerability scanning, port exploitation, session-based attacks,
and identification of OWASP Top 10 vulnerabilities.

To begin, the project utilizes Nmap, a popular network scanning tool, to perform information gathering and identify open ports on the target websites. This step 
helps to identify potential entry points that could be exploited by attackers. Following this, the project employs Nikto, a web server vulnerability scanner, to
conduct a comprehensive vulnerability assessment of the target websites. Nikto identifies common vulnerabilities, misconfigurations, and outdated software versions
that could be exploited.

With the vulnerabilities identified, the project proceeds to exploit open ports on the practice website, Metasploitable 2. This step involves using various tools,
including Metasploit, a powerful penetration testing framework, to exploit known vulnerabilities and gain unauthorized access. By performing these controlled
exploits on the practice website, the project gains hands-on experience and a deeper understanding of the potential risks and consequences of such vulnerabilities.

Moving forward, the project focuses on the target website, batterybhai.com, to simulate real-world attacks. Specifically, session-based attacks such as session 
hijacking and session Denial-of-Service (DoS) attacks are conducted. Session hijacking aims to exploit vulnerabilities in session management mechanisms, allowing
unauthorized users to impersonate legitimate users and gain unauthorized access. On the other hand, session DoS attacks aim to disrupt the availability of the web
application by overwhelming its session management infrastructure.

Lastly, the project leverages ZAP Proxy, an open-source web application security scanner, to identify the OWASP (Open Web Application Security Project) Top 10
vulnerabilities on a website from the Metasploitable environment. The OWASP Top 10 is a widely recognized list of the most critical web application security risks,
and the project's findings provide insights into the presence and severity of these vulnerabilities.

Through this proposed solution, the project aims to provide a comprehensive understanding of web application penetration testing techniques and their practical 
application.By simulating attacks and identifying vulnerabilities, the project highlights the importance of proactive security measures and serves as a foundation
for strengthening the security posture of web applications.

