# Cyber Security Internship - Task 2: Phishing Email Analysis

## Overview
This repository contains my analysis of a phishing email sample as part of the Cyber Security Internship tasks. The goal was to identify and document phishing characteristics in a suspicious email.

## Files Included
1. `phishing_analysis_report.txt` - Detailed report of phishing indicators found in the sample email
2. `interview_answers.txt` - Answers to the interview questions provided in the task

## Methodology
I followed these steps to complete the task:

1. **Obtained a phishing sample** from a public repository of known phishing emails
2. **Examined the sender's address** for spoofing attempts
3. **Analyzed email headers** using MXToolbox's free header analyzer
4. **Checked all links** by hovering and examining the underlying URLs
5. **Reviewed the email content** for language patterns and grammatical errors
6. **Verified branding elements** against the legitimate company's official communications
7. **Documented findings** in a structured report
8. **Researched and answered** all interview questions to demonstrate understanding

## Key Findings
The analyzed email contained multiple red flags:
- Domain spoofing (amaz0n-security.com instead of amazon.com)
- Mismatched URLs in hyperlinks
- Urgent/threatening language
- Poor grammar and spelling
- Requests for sensitive information
- Failed SPF checks in email headers

## Learning Outcomes
Through this task, I've developed:
- Practical skills in analyzing email headers
- Ability to spot common phishing tactics
- Understanding of email authentication mechanisms
- Awareness of social engineering techniques used in phishing

## References
- MXToolbox for header analysis
- Phishing email samples from phishing.org
- Amazon's official communication guidelines
- Cybersecurity & Infrastructure Security Agency (CISA) phishing resources

Note: The sample email analyzed was from a public repository of known phishing emails used for educational purposes only.