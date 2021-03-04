# Security Information concepts

## Books i've used...

- Foundations of Information Security - A Straightforward Introduction

## What's Information Security?

- Information security refers to the processes and methodologies which are designed and implemented to protect print, electronic, or any other form of confidential, private and sensitive information or data from unauthorized access, use, misuse, disclosure, destruction, modification, or disruption.

[What is information security? Definition, principles, and jobs](https://www.csoonline.com/article/3513899/what-is-information-security-definition-principles-and-jobs.html)

## five Pillars of Information Assurance Framework.

### Confidentiality

- This is the assurance that information is not disclosed to unauthorized individuals, groups, processes, or devices. Highly confidential data must be encrypted so third parties cannot easily decrypt it. Only those who are authorized to view the information are allowed access.

### Integrity

- The accuracy and completeness of vital information must be safeguarded. Data should not be altered or destroyed during transmission and storage. This involves making sure that an information system is not tampered with by unauthorized entities. Policies should be in place so that users know to properly utilize their system.

### Availability

- This means that authorized users have timely and easy access to information services. IT resources and infrastructure should remain robust and fully-functional at all times even during adverse conditions, such as database conundrums or fall-overs. It involves protecting against malicious codes, hackers, and other threats that could block access to the information system.

### Authenticity

- This security measure is designed to establish the validity of a transmission, message, or originator, or a means of verifying an individual's authorization to receive specific information. Authentication prevents impersonation and requires users to confirm their identities before being allowed access to systems and resources. This includes user names, passwords, emails, biometrics, and others

### Non-Repudiation

- This attribute assures the sender of data is provided with proof of delivery and the recipient is provided with proof of the sender's identity, so neither party can deny sending, receiving, or accessing the data. Security principles should be used to prove identities and to validade the communication process.


## Identification and Authentication

- Identification makes a claim about what someone or something is, and authentication establishes whether this claim is true.


<img height="100" src="https://user-images.githubusercontent.com/62820717/107723813-faab8f00-6cc0-11eb-984e-78dffee109b7.png"/>
Example: Payment cards that require a personal identification number (PIN). When you swipe the magnetic strip on the card, you're asserting that you're the       person indicated on the card. At this point, you've given your identification, but nothing more. When you're prompted to enter the PIN associated with the         care, you're completing the authentication portion of the transaction, proving you're the legitimate cardholder.

- We can use several methods for identification and authentication. from requiring simple usernames and passwords to implementing purpose-built hardware tokens that serve to establish your identity in multiple ways.

## Identify Verification

- Identify verification a step beyond identification, but it's still a step short of authentication.

Example: When you send an email the identity you provide is taken to be true; the system rarely takes any additional steps to authentication you. → it's a port to spams

## Authentication

- In information security, authentication is the set of methods used to establish whether a claim of identify is true.
- Authentication does not decide what the party being authenticated is permitted to do, this is a separate task, known as ***authorization***.

## Factors

- Factors are used to authenticate any people or something.
- They are "Something you know", "Something you have", "Something you do" and "Where you are"
- The more factors you use, the more positive your results will be.

### Something you know

- Include passwords or PINs.

### Something you are is

- Based on the relatively unique physical attributes of an individual. often referred to as biometrics.
- Biometrics can include simple attributes such as height, weight, hair color, or eye color. These aren't usually distinctive enough to make very secure identifiers.
- They are stronger than passwords.

### Something you have

- Based on a physical possession, although it can into some logical concepts.
- Common examples are Automatic Teller Machine (ATM) cards, state or federally issued identity cards, or software-based security tokens

### Something you do

- Sometimes considered a variation of something you are, is a factor based on the actions or behaviors of an individual.

### Where you are

- Geographically based authentication factor.
- Requires a person to be present in a specific location.

## Multifactor Authentication

- Use one or more of the factores above.
- When you're using only two factors, this practice is also sometimes called two-factor authentication.
- Examples: ATM cards, writing checks.
- Depending on the factors selected, you can assemble stronger or weaker multifactor authentication schemes particular to each situation.

## Mutual Authentication 
- It is a mechanism in which both parties in a transaction authenticate each other.
- Mutual authenticate often relies on digital certificates.

Example: The client authenticates to the server and the server authenticates to the client.

- In cases where you don't perform mutual authentications, you leave yourself open to impersonation attacks, often referred to as "man-in-the-middle attacks".
- In the man-in-the-middle-attack, the attacker inserts himself between the client and server.
- This is typically possible because the attacker needs to subvert or falsify authentication only from the client to the server. 
- If you implement a Mutual authentication,  this becomes a considerably more difficult attack because the attacker would have to falsify two different Authentications

## Common identification and authentication methods

### Passwords
- Passwords only a single factor of authentication, but they can represent a relatively high level of security when constructed and implemented properly.
- 1234567 -> easly cracked.
- $$@!0n!21 -> harder to crack.
- To constructing strong passwords, you also need to practice good password hygiene.

  #### Tips
    - Don't write your password down and post it under your keyboard or on your monitor.
    - Use password managers.
    - Don't use the same password on many sites.

### Biometrics
- You can use them to verify the identity claim someone has put forth, or you can reverse the process and use biometrics as a method of identification.
- You can also save a copoy of a fingerprint in the system, then you can use the minutiae later to match the characteristic to the user.
- This process is commonly used by law enforcement agencies to idenfity the owner figerprints left on various objects.

  #### Characteristics of Biometric Factors
    - Universality, uniqueness, permanence, collectability, performance, acceptability, and circumvention.
