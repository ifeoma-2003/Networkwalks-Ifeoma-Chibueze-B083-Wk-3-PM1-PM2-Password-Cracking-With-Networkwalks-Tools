## Networkwalks Week 3- Password Cracking With Networkwalks Tools

## Overview

This repository documents my Week 3 practical exercises, focusing on password security, cryptographic hashing, 
password hash analysis, and password recovery techniques within a controlled laboratory environment.
The practical sessions provided an opportunity to move beyond theoretical concepts and examine how password related 
security mechanisms operate in practice. Working with multiple tools and approaches helped to understand the relationship
between plaintext passwords, crytographic hashes, password verification and recovery attempts.
The exercise covered:
```
Hash generation and analysis using a Hash Calculator.
Password-hash testing using a Hash Password Cracker.
Password auditing with John the Ripper.
Graphical interaction with John the Ripper through Johnny GUI.
```

## Objectives

The objective was not merely to execute commands,but to understand the underlying security concepts, observe tool 
behaviour, document the workflow, and relate practical findings to defensive password security practices.
The practical activities were designed to stregthened the understanding of the following:
```
Hash representation and identification.
Crytographic password hashing.
Password-hash recovery techniques.
Password complexity and attack resistance.
Wordlist based password attacks.
Command line security tools.
The importance of strong password for storage practices.
```

## Practical Modules

## Hash Calculator

The Hash Calculator exercise introduced the process of converting plaintext input into cryptographic hash values.
This provided a practical foundation for understanding that hashing is a one way transformation used extensively in 
authentication systems and other security applications.
The exercise also demonstrated how the same input consistently produces the same hash when processed using the same 
hashing algorithm.

## Hash Password Cracker

The Hash Password Cracker exercise focused on the relationship between a stored password hash and the original password.
Rather than treating the hash as an encrypted version of the password,the exercise reinforced the distinction between 
hashing and encryption and demonstrated how candidate passwords can be tested against a known hash.
This provided practical context for understanding why weak passwords remain vulnerable even when passwords are not stored
directly as plaintext.

## John the Ripper

John the Ripper was used to explore password auditing and password recovery techniques in a controlled environment.
The exercise involved examining how a password hash can be subjected to systematic password candidates and how factors
such as password composition and available wordlists can influence recovery attempts.
Working with John the Ripper also strengthened my familarity with command line cybersecurity tooling and security 
oriented workflows.

## Johnny GUI

The Johnny graphical interface provided a visual way of interacting with John the Ripper.
Using the GUI helped reinforce the same password auditing concepts explored from the command line while making the work
flow easier to observe through a graphical interface.
Comparing both approaches demonstrated the value of understanding the underlying command line tool even when a graphical
interface is available.

## Evidence

![](

![](

![](

![](

![](

![](

![](

![](

![](

## Ethical Consideration

All activities documented in this repository were conducted for educational and authorized cybersecurity training purposes
within a controlled laboratory environment.
Password auditing and recovery techniques should only be applied to systems, files, accounts, and credentials for which
explicit authorization has been provided.

## Tools
```
Hash Calculator.: (https://networkwalks.com/hash-calculator/)
Hash Password Cracker: (https://networkwalks.com/password-cracker/)
John the Ripper.
Johnny GUI.
```

## Author 

Ifeoma Chibueze | Networkwalks Cybersecurity Intern | B083 | Week 3

