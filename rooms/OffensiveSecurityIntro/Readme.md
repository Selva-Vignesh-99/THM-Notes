# Offensive Security Intro

- **Room Link:** https://tryhackme.com/room/offensivesecurityintro
- **Difficulty:** Easy
- **Category:** Fundamentals
- **CEH v13 Domain:** Introduction to Ethical Hacking
- **Completed:** 2026-06-01

## Summary
Brief intro to what offensive security is — thinking like an attacker
to find vulnerabilities before malicious hackers do.

## Approach & Notes

### Task 1 - THINK LIKE AN ATTACKER
Offensive Security is about thinking like an attacker to find the weaknessess before the real hackers do

### Task 2 - STARTING THE LAB
    Get the Bank Account number

    Account Number - 8881

### Task 3- FINDING THE HIDDEN PAGES
    One common mistake websites make is leaving hidden pages accessible. We will use the terminal to run a command that can look for these:
    Inside the terminal, copy and paster the dirb command below and wait for it to finish. Any lines from the output that starts with + are pages that have been found.

    dirb http://fakebank.thm

    output:
    http://fakebank.thm/images
    http://fakebank.thm/bank-transfer

### Task 4- ATTACK AN ADMIN PAGE

    Paste the link in the browser address bar and hit enter, and deposit an amount to the account number 8881

    link
    http://fakebank.thm/bank-transfer

## Key Takeaways
- dirb command fetches all the hidden url
- 

## References
- https://tryhackme.com/room/offensivesecurityintro