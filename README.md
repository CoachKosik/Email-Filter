# Email Filter - Filter malicious emails

### Overview
In this activity, you will analyze a suspicious email and identify signs of a phishing attack. Then, you will determine whether the email should be allowed or quarantined. 

Phishing is one of the most common and dangerous forms of social engineering that you’ll encounter in the field. Identifying phishing attempts will help you prevent threats and find ways to improve security procedures.

### Scenario
You’re a security analyst at an investment firm called Imaginary Bank. An executive at the firm recently received a spear phishing email that appears to come from the board of Imaginary Bank. **Spear phishing** is a malicious email attack targeting a specific user or group of users, appearing to originate from a trusted source. In this case, the executive is being asked to install new collaboration software, ExecuTalk.

The executive suspects this email might be a phishing attempt because ExecuTalk was never mentioned during the last board meeting. They've forwarded the message to your team to verify if it’s legitimate. Your supervisor has tasked you with investigating the message and determining whether it should be quarantined.

### Step 1: Analyse the suspicious email
Start your investigation by analyzing the suspicious message. Try to identify clues that this is a phishing attack against this executive at Imaginary Bank:

# 
**From:** imaginarybank@gmail.org

**Sent:** Saturday, December 21, 2019  15:05:05

**To:** cfo@imaginarybank.com

**Subject:**  RE: You are been added to an ecsecutiv's groups

Conglaturations! You have been added to a collaboration group ‘Execs.’

Downlode ExecuTalk to your computer.

**Mac® | Windows® | Android™** 

You're team needs you! This invitation will expire in 48 hours so act quickly.

Sincerely,

**ExecuTalk©**

All rights reserved. 
# 

### Step 2: Examine the sender's information
Next, examine the major parts of this message in closer detail starting with the email header. You can often find clues in the message header that indicate you are dealing with a phishing attack.

Examine the email header of this suspicious message:

# 
**From:** imaginarybank@gmail.org

**Sent:** Saturday, December 21, 2019  15:05:05

**To:** cfo@imaginarybank.com

**Subject:**  RE: You are been added to an ecsecutiv's groups
# 
Question 1
Which two clues in the message header indicate to you that this is a phishing attempt?
  * Two clues in the message header that indicate that this is a phishing attempt are that there is a misspelling in the subject line and the sender is using a different domain. Phishing emails commonly contain glaring spelling and grammatical errors. Another typical sign of phishing is when messages come from external domains, like a personal Gmail account.

### Step 3: Review the message body for clues
Next, review the body of the message received by the executive at Imaginary Bank. Try to identify three ways this threat actor tried to disguise their message as a legitimate email.
#
Conglaturations! You have been added to a collaboration group ‘Execs.’

Downlode ExecuTalk to your computer.

**Mac® | Windows® | Android™**

You're team needs you! This invitation will expire in 48 hours so act quickly.

Sincerely,

**ExecuTalk©**

All rights reserved.
#
Question 2
What details make this message appear legitimate?
  * The brand labeling, the download options for major operating systems, and the title of the group, are all details that make this message appear legitimate.

### Step 4: Investigate the download options
Phishing emails often contain links that redirect to malicious sites or trigger malware downloads.

In this case, the message contains three download options. Each of them opens this login form:

![Malicious email image](https://github.com/user-attachments/assets/5168cc4b-446d-46a3-bc7a-fffb70a77443)<br>

Question 3
The download options open a webpage that contains a login form where someone can enter a username and password. Carefully review the webpage. What is the main clue that indicates this form is malicious?
  * The URL is the main clue that indicates this form is malicious. Threat actors make this difficult to spot by design. When accessing SaaS services, like Microsoft applications, the URL typically includes the organization’s domain.

Question 4
After completing your investigation, should this email be quarantined?
  * Yes!
