---
author: slowe
comments: false
date: 2005-07-19 13:08:06+00:00
layout: post
slug: computer-accounts-with-ktpassexe
title: Computer Accounts With ktpass.exe
wordpress_id: 54
categories:
- Interoperability
tags:
- Kerberos
- Linux
- Microsoft
- Windows
---

As a quick follow-up to my previous posting, testing with Kerberos authentication from a Linux server with pam_krb5 was successful. Instead of using a user account in Active Directory to generate the keytab, I was able to use a computer account and just had to modify the `ktpass.exe` command line syntax slightly (see my previous post).
