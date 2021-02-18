# Security Information concepts

## Books i've used...

- Foundations of Information Security - A Straightforward Introduction

## What's Information Security?

- Information security refers to the processes and methodologies which are designed and implemented to protect print, electronic, or any other form of confidential, private and sensitive information or data from unauthorized access, use, misuse, disclosure, destruction, modification, or disruption.

[What is information security? Definition, principles, and jobs](https://www.csoonline.com/article/3513899/what-is-information-security-definition-principles-and-jobs.html)

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
