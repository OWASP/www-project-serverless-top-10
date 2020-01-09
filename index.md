---

layout: col-sidebar
title: OWASP Serverless Top 10
tags: serverless security top10 acknowledgments translations join roadmap news 
level: 2
type: documentation

---


# Main

<table>
<tbody>
<tr class="odd">
<p>The <a href="/www-pdf-archive/OWASP-Top-10-Serverless-Interpretation-en.pdf">OWASP Top 10: Serverless Interpretation</a> is now available.</p>
<h2 id="introduction">Introduction</h2>
<p>When adopting serverless technology, we eliminate the need to develop a server to manage our application. By doing so, we also pass some of the security threats to the infrastructure provider such as <a href="https://aws.amazon.com/serverless/">AWS</a>, <a href="https://azure.microsoft.com/en-us/services/functions/">Azure</a> and <a href="https://cloud.google.com/functions/">Google Cloud</a>. In addition to the many advantages of serverless application development, such as cost and scalability, some security aspects are also handed to our service provider. Serverless services run code without provisioning or managing servers and the code is executed only when needed.</p>
<p>However, even if these applications are running without a managed server, they still execute code. If this code is written in an insecure manner, it can still be vulnerable to application-level attacks.</p>
<p>The first report will examine the differences in attack vectors, security weaknesses, and the business impact of application attacks on in the serverless world, and, most importantly, the report will suggest ways to to prevent them. As we will be able to see in the report, attack and defense techniques are different from what we used to in the traditional application world.</p>
<p>After that, an open-call will be established to collect data in the wild and establishing the official Serverless Top 10 Report.</p>
<h2 id="purpose">Purpose</h2>
<p>OWASP Serverless Top 10 aims at educating practitioners and organizations about the consequences of the most common serverless application security vulnerabilities, as well as providing basic techniques to identify and protect against them.</p>
<h2 id="licensing">Licensing</h2>
<p>The OWASP Serverless Top 10 is free to use. It is licensed under the <a href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 license</a> (CC BY-SA 4.0).</p>

{info.md}


{leaders.md}

