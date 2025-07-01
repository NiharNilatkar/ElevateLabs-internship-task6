# ElevateLabs-internship-task6

# Task 6: Create a Strong Password and Evaluate Its Strength.

## Objective
Understand what makes a password strong and test it against password strength tools
---

## Tools Used
- (https://bitwarden.com/password-strength/) for checking the strength of the password

---

## Passwords Tested
I used some commonly used passwords that includes the word 'password' and analyzed it using combinations of uppercases, numbers, and symbols.
These were categorized on basis of 'very weak', 'weak', 'good', and 'strong'.

 Password                 Strength          Notes                                      

- `password123`            very weak     Commonly used, easily guessable            
- `Password@123`           weak          Added capitalization and symbol           
- `pA@ssw_202`             good          Doesn't use the complete word, added extra symbols and random number sequence            
- `p@@$$word_101`          strong        Highly complex due to added symbols obfuscating the word 'password' along with random sequence of numbers.                  

---

## Results
Screenshots were taken from Bitwarden password tester, showing:
- Strength meter levels
- Estimated time to crack

---

## What I Learned

### Tips for Creating Strong Passwords:
- Use at least **12 characters**
- Combine **uppercase, lowercase, numbers, and symbols**
- Avoid using **real words or personal info**
- Use complex words, and avoid words like **admin**,**user**,**password**(even though I've used it here)
- Never reuse the same password on different sites
This is how password complexity can strengthen security but keep in mind, they are still vulnerable.
---

## Common Password Attack Types:

Attack Type                Description 

- **Brute Force**          Tries every possible character combination
- **Dictionary Attack**    Tries common words and leaked passwords 
- **Credential Stuffing**  Tries known username-password pairs from data breaches 
- **Phishing**             Tricks users into entering passwords on fake sites 

### How Brute Force and Dictionary Password attacks are done:
**1. Brute Force:-**
- Manually trying every possible character combination to crack passwords and credentials
- Using automation tools like Jhon The Ripper, Hydra, and Hashcat to try all possible combinations in just few minutes.
- For example using the command `jhon --wordlist=/usr/share/wordlists/rockyou.txt file.txt` will crack the password that encrypts `file.txt`.
Jhon The Ripper will use wordlist to try multiple password combos.

**2. Dictionary Attack:-**
- Guessing password or trying to crack a password using list of leaked passwords or commonly used passwords
- Using lists like `wordlists` which includes `/usr/share/wordlists/rockyou.txt` which is a dictionary containing key & value pairs, for comprimising a passwords.

---

## Outcome
- Learned how to evaluate and build secure passwords  
- Understood the difference between weak and strong passwords  
- Gained awareness of password-based attacks

---

## Files Included
- Screenshots of password strength checks
- This README.md file
