# Goldman-Sachs-Forage-Job-Simulation
This is a Job Simulation offered by Goldman Sachs which offers task which involves assessing the level of protection offered by the organization's password controls.

## Table of Contents
Memo
Requirements
Usage
Results
Author
### Subject: Recommendations for Enhancing Password Security

### Memo
Subject: Recommendations for Enhancing Password Security

Dear Sir/Ma'am,

I hope this email finds you well. I appreciate your time and attention to this matter. I am reaching out to provide a comprehensive assessment of our current password policy and to propose recommendations for strengthening our data security practices.

Upon reviewing the leaked password hashes, I have identified critical vulnerabilities in our existing policy. The primary concern is the use of the Message Digest 5 (MD5) hash function, which is highly susceptible to collisions and easy to exploit. Tools like Hashcat.com, paired with commonly available wordlists such as rockyou.txt, make cracking these passwords relatively straightforward. To enhance security, I strongly recommend transitioning to a more robust encryption mechanism, such as the Secure Hash Algorithm (SHA).

Key Weaknesses Identified:
Inadequate Minimum Password Length: The current minimum of six characters does not meet industry best practices.
Lack of Defined Complexity Requirements: Users can create passwords with any combination of words and letters, making them vulnerable to attacks.
Recommended Policy Enhancements:
Stronger Password Complexity: Require special characters, uppercase and lowercase letters, and numbers to improve password strength.
Increased Minimum Length: Set a baseline of at least eight characters for stronger security.
Password Reuse Prevention: Restrict users from reusing passwords across multiple accounts.
Prohibition of Personal Information: Ensure passwords do not contain usernames, real names, birth dates, or other easily accessible details.
User Awareness & Training: Conduct educational sessions to reinforce secure password practices and compliance with policy guidelines.
By implementing these measures, we can significantly enhance our security posture and mitigate potential threats. I appreciate your consideration of these recommendations and look forward to discussing further steps to improve our organization’s data security. Please feel free to reach out if you require any additional information or clarification.

Best regards,
Amisha Gupta
B.Tech, Information Technology Engineering

### Requirements
Hashcat
Rockyou.txt

### Usage
hashcat -m 0 -a 0 -o decrypted.txt hashes.txt rockyou.txt # to crack pass
hashcat -m 0 -a 0 -o decrypted.txt hashes.txt rockyou.txt --show # to see it again after 1st time decryption

Author
Amisha Gupta
