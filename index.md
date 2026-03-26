---
layout: default
title: Anish Feroz
---

<p class="home-role-line">Offensive Security Specialist • Penetration Tester • Security Researcher</p>

<div class="home-mid-align" markdown="1">

## About

I am a cybersecurity professional specializing in **offensive security, exploit development, and vulnerability research**.

I have conducted **300+ penetration tests** across web applications, mobile apps, networks, cloud infrastructure, IoT systems, and APIs.

---

## Areas of Research

- Exploit Development
- Mobile & iOS Security
- Vulnerability Research
- Red Team Techniques
- Active Directory Attacks
- Malware Analysis

---

## Selected Skills

- Web Application Penetration Testing
- Mobile Application Security
- Red Team Operations
- Reverse Engineering
- Exploit Development
- Cloud Security Assessments
- Secure Code Review

---

## Latest Research

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})**  
  {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

</div>
