## 📋 Submission Information

**Name:** [Emre Akın]  
**Email:** [reach.emreakin@gmail.com]  
**LinkedIn:** [linkedin.com/in/emreakin-]   
**Submission Date:** [2025-11-09]

---

## ✅ Deliverables Checklist

Please confirm you've included all required items:

- [✔️] **Report** (PDF, max 5 pages)
  - [✔️] Section 1: Incident Analysis
  - [✔️] Section 2: Architecture Review
  - [✔️] Section 3: Response & Remediation
  
- [✔️] **Video Presentation** (10-15 minutes)
  - [✔️] Link provided in 
  - [✔️] Video is accessible (tested in incognito)
  - [✔️] Duration is within guidelines

- [ ] **File Structure**
```
  submissions/firstname-lastname/
  ├── https://docs.google.com/document/d/1vj-4CYhMBXoDTcG9Zm6rm0AWLz-uyjBZdB7_HBQ1TlA/edit?usp=sharing
  ├── https://www.youtube.com/watch?v=_Kl92HUTJvI&t=187s
  └── notes.md (optional)
```

---

## 📊 Self-Assessment

**Time spent on this lab:** Approximately  hours

**Tools used:**
- Log analysis: 5 hours
- Diagrams: 2 hours
- Video recording: 3 hours

**Confidence level:**
- [✔️] Very confident in my analysis
- [ ] Confident but some uncertainties
- [ ] Attempted my best with available knowledge

---

## 🎯 Brief Summary (2-3 sentences)

_Briefly describe your approach and key findings:_

[Early log inspection suggests a brute force attack, while i specifically observed an enumeration attack from IP 203.0.113.45. Additionally, a phishing attempt was found in email logs, and the WAF logs confirmed a SQL injection attempt.]

---

## 🔍 Key Findings Highlight

**Main attack vectors identified:**
1. Brute-Force Attack
2. Enumeration Attack
3. Phishing Attack and SQL Injection

**Most critical vulnerability:**
IDOR ( Insecure Direct Object Reference ) 

**Top recommendation:**
To detech IDOR, endpoint-based testing tools (Burp Suite, OWASP ZAP) can be used, And I would design something that would prevent too many requests from coming over the same IP Address.

---

## 💭 Challenges & Learnings

**What was most challenging?**
[Investigating too many logs with an entry level knowledge was tough]

**What did you learn?**
[I learned reading logs and analyzing them and providing some solutions.]

**What would you do differently?**
[Nothing, i spent too much time working on those logs and i think i've come a long way.]

---

## 📝 Additional Notes _(optional)_

Any context, assumptions, or additional information you'd like evaluators to know:

[This project helped me a lot in learning how to read logs, thank you.]

---

## ⚖️ Declaration

I declare that:
- [✅️] This work is entirely my own
- [✅️] I have not copied from other submissions or answer keys
- [✅️] I have not modified the provided log files
- [✅️] All sources and tools are properly attributed
- [✅️] I understand plagiarism results in disqualification

**Signature:** [Emre Akın]  
**Date:** [2025-11-09]

---

## 🚀 Ready for Review

By submitting this PR, I confirm that my work is complete and ready for evaluation.

---

_Thank you for your submission! Our team will review it within 1 week._
