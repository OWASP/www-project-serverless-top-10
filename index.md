---

layout: col-sidebar
title: OWASP Serverless Top 10
tags: serverless security top10 acknowledgments translations join roadmap news 
level: 2
type: documentation

---


# Main

The [OWASP Top 10: Serverless Interpretation](https://github.com/OWASP/Serverless-Top-10-Project/raw/master/OWASP-Top-10-Serverless-Interpretation-en.pdf) is now available.

## Introduction
When adopting serverless technology, we eliminate the need to develop a server to manage our application. By doing so, we also pass some of the security threats to the infrastructure provider such as [AWS](https://aws.amazon.com/serverless), [Azure](https://azure.microsoft.com/en-us/services/functions/) and [GCP](https://cloud.google.com/functions/). In addition to the many advantages of serverless application development, such as cost and scalability, some security aspects are also handed to our service provider. Serverless services run code without provisioning or managing servers and the code is executed only when needed.

However, even if these applications are running without a managed server, they still execute code. If this code is written in an insecure manner, it can still be vulnerable to application-level attacks.

The interpretation report examines the differences in attack vectors, security weaknesses, and the business impact of application attacks on in the serverless world, and, most importantly, the report will suggest ways to prevent them. As we will be able to see in the report, attack and defense techniques are different from what we used to in the traditional application world.

After that, an open-call will be established to collect data in the wild and establishing the official Serverless Top 10 Report.

## Purpose
OWASP Serverless Top 10 aims at educating practitioners and organizations about the consequences of the most common serverless application security vulnerabilities, as well as providing basic techniques to identify and protect against them.

## License
The OWASP Serverless Top 10 is free to use. It is licensed under the [Creative Commons Attribution-ShareAlike 4.0 license (CC BY-SA 4.0)](http://creativecommons.org/licenses/by-sa/4.0/).
