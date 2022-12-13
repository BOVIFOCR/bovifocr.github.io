---
title: Home
layout: home
nav_order: -999
---

![](/assets/images/logos.png)

# BOVIFOCR
Ocular Biometrics, Face Liveness and OCR in official documents

This project has the main objective of improving Computer Vision algorithms for large-scale human face ocular biometric authentication and verification, face liveness detection and key information extraction in documents (in particular w.r.t. the Portuguese language). It is a partnership between [Universidade Federal do Paraná (UFPR)](https://www.ufpr.br/portalufpr/) and [Unico](https://unico.io/).

## Team
- David Menotti Gomes (associate professor at UFPR, project supervisor)
- Bernardo Janko Goncalves Biesseck (PhD student)
- Bruno Henrique Kamarowski de Carvalho (undergrad CS student)
- Lucas Matheus Leite Wojcik (undergrad CS student)
- Pedro Beber de Queiroz Vidal (undergrad CS student)
- Raul Gomes Pimentel de Almeida (master's student)

## Research Topics
This project involves three lines of research: Face Anti-Spoofing, Ocular Biometrics and Key Information Extraction. They are briefly summarized below.

In biometrics, spoofing is a malicious act of impersonation or obfuscation of identity. In Face Recognition (FR) systems, an attacker may for example wear a paper mask made from a picture of someone else. **Face Anti-Spoofing**[^1] (FAS, or liveness detection) is the problem of detecting spoofing attempts in FR systems. As FR becomes more important in daily life, with relevant applications such as banking and citizen identification migrating to mobile devices, it is fundamental that FAS models become adequately robust and performant in order to avoid exploits.

There are two branches in FAS: in **passive liveness detection**, the user only has to take a picture or a video of their still face. In **active liveness detection**, the user has to perform challenges such as moving their face according to instructions in an app. While active liveness allows for lower error rates, passive liveness remains important for applications where user interaction is not possible (such as in-the-wild face recognition).

**Ocular Biometrics**[^2] consists of detecting a person's identity from the ocular region. It has recently gotten growing attention due to the COVID-19 pandemic, which created the need for regular use of face masks that cover nose and mouth (affecting face recognition models' performances).

**Key Information Extraction**[^3] is the task of extracting structured information from unstructured representations such as scanned documents. This plays a vital role in office automation, document authentication and other tasks that are important in day-to-day life.

----
[^1]: [Deep Learning for Face Anti-Spoofing: A Survey (arXiv abstract)](https://arxiv.org/abs/2106.14948v3)
[^2]: [Ocular Recognition Databases and Competitions: A Survey (arXiv abstract)](https://arxiv.org/abs/1911.09646v3)
[^3]: [Key Information Extraction (Papers With Code)](https://paperswithcode.com/task/key-information-extraction/)
