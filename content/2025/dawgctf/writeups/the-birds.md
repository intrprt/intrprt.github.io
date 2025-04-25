---
draft: false
type: writeup
date: 2025-04-25T14:53:13-04:00
params:
    category: "Cryptography"
tags:
- substitution-cipher
title: "The Birds"
---

In this challenge we are given an [image](https://github.com/UMBCCyberDawgs/dawgctf-sp25/blob/main/The%20Birds/burb.png). Since this is a crypto challenge, it would be safe to assume this is some kind of substitution cipher. Searching for "bird cipher" led me to a page on [dcode.fr](https://www.dcode.fr/birds-on-a-wire-cipher) providing a decoder for the "Birds on a Wire Cipher". Using this decoder to enter in the birds shown in the challenge image gives us `THEREISNOESCAPE`, meaning the flag is `DawgCTF{THEREISNOESCAPE}`.

