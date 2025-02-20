# Goldman-Sachs-Forage-Job-Simulation
This is a Job Simulation offered by Goldman Sachs which offers task which involves assessing the level of protection offered by the organization's password controls.

##Table of Contents
Memo
Requirements
Usage
Results
Author
###Subject: Recommendations for Enhancing Password Security

###Memo
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

###Requirements
Hashcat
Rockyou.txt
###Usage
hashcat -m 0 -a 0 -o decrypted.txt hashes.txt rockyou.txt # to crack pass
hashcat -m 0 -a 0 -o decrypted.txt hashes.txt rockyou.txt --show # to see it again after 1st time decryption

##Results
Security Algorithms used(listed below): 

experthead:e10adc3949ba59abbe56e057f20f883e – MD5
interestec:25f9e794323b453885f5181f1b624d0b – MD5
ortspoon:d8578edf8458ce06fbc5bb76a58c5ca4 –MD5
reallychel:5f4dcc3b5aa765d61d8327deb882cf99 –MD5
simmson56:96e79218965eb72c92a549dd5a330112 – MD5
bookma:25d55ad283aa400af464c76d713c07ad – MD5 
popularkiya7:e99a18c428cb38d5f260853678922e03 – MD5
eatingcake1994:fcea920f7412b5da7be0cf42b8c93759 – MD5 
heroanhart:7c6a180b36896a0a8c02787eeafb0e4c – MD5
edi_tesla89:6c569aabbf7775ef8fc570e228c16b98 – MD5
liveltekah:3f230640b78d7e71ac5514e57935eb69 – MD5
blikimore:917eb5e9d6d6bca820922a0c6f7cc28b – MD5
johnwick007:f6a0cb102c62879d397b12b62c092c06 – MD5
flamesbria2001:9b3b269ad0a208090309f091b3aba9db – MD5
oranolio:16ced47d3fc931483e24933665cded6d - MD5
spuffyffet:1f5c5683982d7c3814d4d9e6d749b21e - MD5
moodie:8d763385e0476ae208f21bc63956f748 - MD5
nabox:defebde7b6ab6f24d5824682a16c3ae4 - MD5
bandalls:bdda5f03128bcbdfa78d8934529048cf - MD5

###Cracked Passwords(listed below):

experthead:e10adc3949ba59abbe56e057f20f883e - 123456
interestec:25f9e794323b453885f5181f1b624d0b - 123456789
ortspoon:d8578edf8458ce06fbc5bb76a58c5ca4 - qwerty
reallychel:5f4dcc3b5aa765d61d8327deb882cf99 - password
simmson56:96e79218965eb72c92a549dd5a330112 - 111111
bookma:25d55ad283aa400af464c76d713c07ad - 12345678
popularkiya7:e99a18c428cb38d5f260853678922e03 - abc123
eatingcake1994:fcea920f7412b5da7be0cf42b8c93759 - 1234567
heroanhart:7c6a180b36896a0a8c02787eeafb0e4c - password1
edi_tesla89:6c569aabbf7775ef8fc570e228c16b98 - password!
liveltekah:3f230640b78d7e71ac5514e57935eb69 - qazxsw
blikimore:917eb5e9d6d6bca820922a0c6f7cc28b - Pa$$word1
johnwick007:f6a0cb102c62879d397b12b62c092c06 - bluered
Author
Amisha Gupta
