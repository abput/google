# Google Interview (Security Edition)

## Table of Contents

- [Code Auditing](#code-auditing)
- [Reverse Engineering](#reverse-engineering)
- [Fuzzing and Exploitation](#fuzzing-and-exploitation)
- [ETC](#etc)

---

## Code Auditing
- [X] [Design & Operational Reviews (video)](https://vimeo.com/29082852)
- [X] ISIS Labs (Source Code Auditing):
    - [part 1](https://vimeo.com/30001189)
        - Topics that will be covered are Identifying Architectural, Implementation and Operational vulnerabilities.
    - [part 2](https://vimeo.com/29702192)
        - Test the skills that you have learned last week to efficiently go over the process of auditing applications
- [X] [Offensive Computer Security - Source Code Auditing (video)](https://youtu.be/MnmX911MqMU)

## Reverse Engineering
- [X] Open Security Training - Introductory Intel x86
    - [videos](https://www.youtube.com/playlist?list=PL038BE01D3BAEFDB0)
    - [slides](http://opensecuritytraining.info/IntroX86_files/IntroX86_all_materials_with_pdf_1.zip)
- [X] Offensive Computer Security - Reverse Engineering:
    - [part 1](https://youtu.be/Pg8bmV9vcKg)
    - [part 2](https://youtu.be/Opz9xIYthD4)
- [X] ISIS Labs (Reversing 101):
    - [part 1](https://vimeo.com/6764570)
    - [part 2](https://vimeo.com/7177233)
    - [part 3](https://vimeo.com/7238091)
- [X] [Dynamic Reverse Engineering (video)](https://vimeo.com/30594548)
- [ ] Open Security Training - Introductory Intel x64
    - [slides](http://opensecuritytraining.info/IntroX86-64_files/IntroX86-64_AllMaterials_PDF_8-5-2015.zip)
- [ ] Open Security Training - Life of Binaries
    - [videos](https://www.youtube.com/playlist?list=PLUFkSN0XLZ-n_Na6jwqopTt1Ki57vMIc3)
    - [slides](http://opensecuritytraining.info/LifeOfBinaries_files/2012_LoB_all_1.zip)
- [ ] Open Security Training - Introduction to Reverse Engineering
    - [videos](https://www.youtube.com/playlist?list=PLUFkSN0XLZ-nXcDG89jS9iqKBnNHmz7Qw)
    - [slides](http://opensecuritytraining.info/IntroductionToReverseEngineering_files/reclass_2014_1.zip)
- [ ] Open Security Training - Introduction To Software Exploits
    - [videos](http://www.youtube.com/playlist?list=PL96AB65DFCE02EE3E)
    - [slides](http://opensecuritytraining.info/Exploits1_files/SoftwareExploits_public.pdf)
    - [codes](http://opensecuritytraining.info/Exploits1_files/exploitsclass.tgz)
    - [vm](http://opensecuritytraining.info/slack12.zip)
        - zip password = “Exploits1”, accounts are student/student and root/root
- [ ] Open Security Training - Malware Dynamic Analysis
    - [videos](https://www.youtube.com/playlist?list=PLUFkSN0XLZ-kqYbGpY4Gt_VATd4ytQg-Z)
    - [slides](http://opensecuritytraining.info/MalwareDynamicAnalysis_files/MalwareDynamicAnalysis_All_PPT_20140918_1.zip)
- [ ] Open Security Training - Reverse Engineering Malware
    - [videos](https://www.youtube.com/playlist?list=PLUFkSN0XLZ-kwukmQOAgCZ08C5REoZElt)
    - [slides](http://opensecuritytraining.info/ReverseEngineeringMalware_files/malware_analysis_all_materials_2014-09-08_1.zip)
- [ ] Open Security Training - Exploitation in the Windows Environment
    - [videos](https://www.youtube.com/playlist?list=PL9F9E52502327B1CA)
    - [slides](http://opensecuritytraining.info/Exploits2_files/exploits2public-8-25-2012.pptx)
    - [codes](http://opensecuritytraining.info/Exploits2_files/exploits2classmaterial.password%3Dpassword.zip)
        - password = password
- [ ] Open Security Training - Intermediate Intel x86
    - [videos](http://www.youtube.com/playlist?list=PL8F8D45D6C1FFD177)
    - [slides](http://opensecuritytraining.info/ReverseEngineeringMalware_files/malware_analysis_all_materials_2014-09-08_1.zip)
- [ ] Open Security Training - Rootkits
    - [videos](http://www.youtube.com/playlist?list=PLF58FB7BCB20ED11A)
    - [slides](http://opensecuritytraining.info/Rootkits_files/all_materials_with_ppt_1.zip)
    - [poc rootkits](http://opensecuritytraining.info/Rootkits_files/PoC_Rootkits_And_Detectors-infected_1.zip)
        - WARNING! password = “infected” because AV *will* flag on some of these files. 
    - [rootkit detectors](http://opensecuritytraining.info/Rootkits_files/%20%20DETECTION-notinfected_1.zip)
        - Password = “notinfected”, but my AV doesn’t like flister, so yours might not either.
- [ ] Open Security Training - The Adventures of a Keystroke
    - [videos](https://www.youtube.com/playlist?list=PLUFkSN0XLZ-kwukmQOAgCZ08C5REoZElt)
    - [slides](http://opensecuritytraining.info/Keylogging_files/TheAdvernturesOfAKeystroke.pptx)
    - [etc](http://opensecuritytraining.info/Keylogging_files/Materials.rar)
        - RAR file of some applications and sample keyloggers. Password is “infected”

## Fuzzing and Exploitation
- [ ] Offensive Computer Security:
    - [part 1](https://youtu.be/F4WC26_SpKA)
        - Coverage of Fuzzing techniques for SDL, VR, and other applications.
    - [part 2](https://youtu.be/kWmyGZsFc2c)
        - Wrap up of fuzzing topics
    - [part 3](https://youtu.be/1UzOTsvPYYg)
        - beginning of the exploit development
    - [part 4](https://youtu.be/jF1tQk270b0)
        - Covering the very very basics of exploitation. Concept of ret2libc is covered, examples with basic exit() shellcode, and some position-independent basic shellcode.
    - [part 5](https://youtu.be/lhAyUSM1hyA)
        - Coverage of heap and format string exploition (with demos), as well as exploit mitigations (ASLR, NX/DEP, stack cookies, EMET, etc...)
    - [part 6](https://youtu.be/JK0BsefRdJ0)
        - vulnerability examples
- [ ] ISIS Labs (Exploiting 101):
    - [Memory Corruption 1](http://vimeo.com/31348274)
    - [Memory Corruption 2](https://vimeo.com/31831062)
    - [Fuzzing](https://vimeo.com/7574602)
    - [Exploitation-1](https://vimeo.com/16298629)
    - [Exploitation-2](https://vimeo.com/16304711)

Keep learning.

You're never really done.

---

    *****************************************************************************************************
    *****************************************************************************************************

    Everything below this point is optional. These are my recommendations.
    By studying these, you'll get greater exposure to more Security concepts, and will be better prepared for
    any Security related job.

    *****************************************************************************************************
    *****************************************************************************************************

---
## ETC
- [ ] [Windows Internals (video)](https://vimeo.com/49347561)
- [ ] [Vulnerability Analysis (video)](https://vimeo.com/49284329)
