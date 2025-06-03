# 🔐 Password Strength Evaluation Report

---

## 🧠 Purpose of Passwords
Passwords are the **first line of defense** against unauthorized access to personal accounts, systems, and data. A strong password prevents brute-force attacks, guessing, and unauthorized logins.

---

## 🔍 Password Strength Categorization

Passwords are categorized based on **length**, **character diversity**, and **unpredictability**. Based on the Document attached in this repository, we can have a clear idea on which type of passwords are classified as strong, which are classified as weak and how much time it will take for a hacker to crack them. Here's a general classification that can give you an idea on the types of passwords based on strength and complexity:

| Strength      | Criteria                                               |
|---------------|--------------------------------------------------------|
| Weak          | Short, dictionary words, numbers only (e.g., `123456`) |
| Moderate      | Some mix of letters and numbers (e.g., `Appl3@123`)    |
| Strong        | Long, complex with symbols (e.g., `H3ll0_W0rld@2025`)  |
| Very Strong   | 14+ characters, random, diverse (e.g., `!T1mE2R0ck#`)  |

Strength is evaluated using tools like:
- [passwordmeter.com](https://www.passwordmeter.com)
- [howsecureismypassword.net](https://howsecureismypassword.net)

---

## 🔧 Enforcing Strong Passwords

To enforce password security in a system:

- Require **minimum length** (e.g., 12 characters).
- Enforce use of **uppercase, lowercase, numbers, and symbols**.
- Disallow **common or breached passwords**.
- Require **periodic changes** or checks against breach databases.
- Use **multi-factor authentication (MFA)** for added security.

---

## 🧨 Common Password Cracking Methods

Hackers use the following techniques to crack passwords:

1. **Brute Force**  
   - Tries every possible combination of characters.
   - Time-consuming but effective against weak passwords.

2. **Dictionary Attack**  
   - Uses a predefined list of common passwords and dictionary words.
   - Fast and effective on weak or common passwords.

3. **Credential Stuffing**  
   - Uses breached username-password pairs on other services.
   - Exploits reused passwords.

4. **Rainbow Table Attack**  
   - Uses precomputed hash tables to reverse weak hashes.
   - Preventable using salting.

---

## 🧾 How Hackers Generate Wordlists

Hackers create wordlists using tools and data:

- **Tools**: 
  - `Crunch`, `Cewl`, `John the Ripper`, `Hashcat`, `Hydra`.
- **Sources**:
  - Leaked password dumps (e.g., `rockyou.txt`, `HaveIBeenPwned`).
  - Social engineering, scraping social media or public info.
- **Customization**:
  - Based on target's hobbies, birthdates, names, etc, family names, pets, inside sources of information, etc...

---

## 📌 Summary

Password strength is critical to preventing unauthorized access. Weak passwords are susceptible to automated attacks. By understanding how attackers exploit password weaknesses and how strength is measured, users and organizations can implement better password policies and tools.

**Best Practices:**
- Use a password manager.
- Avoid reuse.
- Embrace randomness and length.
- Educate users on secure password hygiene.

---

> 🛡️ *A strong password today is your defense tomorrow.*
