---

title: Foreword
layout: col-document-adv
tags: Code Review Guide
document: OWASP Code Review Guide
author:
contributors:
order: 
altfooter: true

---

**By Eoin Keary,**<br>
**Long Serving OWASP Global Board Member**

<div class='foreword'>
<img src="/assets/images/ekeary.png">
The OWASP Code Review guide was originally born from the
OWASP Testing Guide. Initially code review was covered in the
Testing Guide, as it seemed like a good idea at the time. However, the topic of security code review is too big and evolved into
its own stand-alone guide.

I started the Code Review Project in 2006. This current edition
was started in April 2013 via the OWASP Project Reboot initiative and a grant from the United States Department of Homeland Security.

The OWASP Code Review team consists of a small, but talented,
group of volunteers who should really get out more often. The
volunteers have experience and a drive for the best practices
in secure code review in a variety of organizations, from small
start-ups to some of the largest software development organizations in the world.

It is common knowledge that more secure software can be produced and developed in a more cost efective way when bugs
are detected early on in the systems development lifecycle. Organizations with a proper code review function integrated into
the software development lifecycle (SDLC) produced remarkably better code from a security standpoint. To put it simply “We
can’t hack ourselves secure”. Attackers have more time to fnd
vulnerabilities on a system than the time allocated to a defender. Hacking our way secure amounts to an uneven battlefeld,
asymmetric warfare, and a losing battle.

By necessity, this guide does not cover all programming languages. It mainly focuses on C#/.NET and Java, but includes C/
C++, PHP and other languages where possible. However, the
techniques advocated in the book can be easily adapted to almost any code environment. Fortunately (or unfortunately), the
security faws in web applications are remarkably consistent
across programming languages.
</div>

**Eoin Keary, June 2017**

---

## Appreciation to the United States Department of Homeland Security
OWASP community and Code Review Guide project leaders wish to expresses its deep appreciation to the United States Department of Homeland Security for helping make this book possible by funds provided to OWASP through a grant. OWASP continues be to the preeminent
organization for free unbiased/unfretted application security.
We have seen a disturbing rise in threats and attacks on community institutions thru application vulnerabilities, only by joining forces, and with unfettered information can we help turn back the tide of these threats. The world now runs on software and that software needs to be trustworthy. Our deepest appreciation and thanks to DHS for helping and in sharing in this goal.

## Feedback
If you have any feedback for the OWASP Code Review team, and/or fnd any mistakes or
improvements in this Code Review Guide please contact us at:
[**owasp-codereview-project@owasp.org**](mailto:owasp-codereview-project@owasp.org)