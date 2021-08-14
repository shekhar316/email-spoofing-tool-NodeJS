# Email Spoofing Tool

<!-- > ### Live Demo: -->
<!-- > [https://email-spoofing-tool.herokuapp.com/](https://email-spoofing-tool.herokuapp.com/) -->
<!-- >  -->
> Disclaimer: This tool is for educational purpose only. Don't misuse it.

### Email Spoofing:
Email spoofing is a form of cyber attack in which a hacker sends an email that has been manipulated to seem as if it originated from a trusted source. Email spoofing is a popular tactic used in phishing and spam campaigns because people are more likely to open an email when they think it has been sent by a known sender. The goal of email spoofing is to trick recipients into opening or responding to the message.


![Email Spoofing](/img/download.png)

### npm modules used:
* express
* body-parser
* path
* nodemailer
* fs
* http

### How it works?
Email spoofing can be easily achieved with a working Simple Mail Transfer Protocol (SMTP) server and common email platform, such as Outlook or Gmail. Once an email message is composed, the scammer can forge fields found within the message header, such as the FROM, REPLY-TO and RETURN-PATH addresses. When the recipient gets the email, it appears to come from the forged address.

This is possible to execute because SMTP does not provide a way to authenticate addresses. Although protocols and methods have been developed to combat email spoofing, adoption of those methods has been slow.

### How to identify spoofed emails:

First look for the message header, sender, from , to etc. If a spoofed email does not appear to be suspicious to users, it likely will go undetected. However, if users do sense something is wrong, they can open and inspect the email source code. Here, the recipients can find the originating IP address of the email and trace it back to the real sender.

Users can also confirm whether a message has passed a Sender Policy Framework (SPF) check. SPF is an authentication protocol included in many email platforms and email security products(in Gmail: click on three dots --> show original to identify SPF)

### Resources:
* [Techtarget- email spoofing](https://searchsecurity.techtarget.com/definition/email-spoofing)
* [How to Tell if an Email Has Been Spoofed](https://www.techlicious.com/how-to/how-to-tell-if-email-has-been-spoofed/)
* [What is Email Spoofing?](https://www.proofpoint.com/us/threat-reference/email-spoofing)
