Case Study: Multifactor Authentication Delivery Issue

---

Overview

User unable to access Gmail account due to failure in MFA code delivery via SMS.

Time to Resolution ~10 minutes

---

Environment

Windows 10 

Gmail account

---

Reported Symptoms

User unable to receive MFA verification code via SMS

---

Initial Assessment

Confirmed MFA method was SMS-based authentication

---

Investigation

Attempted code resend function. Issue persisted with no SMS received.

---

Root Cause

SMS-based MFA code delivery failure (no code received on user’s device)

---

Resolution

Switched authentication method to email-based verification. Code was received successfully and used to complete login.


---

Verification

User successfully logged into Gmail account after MFA completion

---

Advisory

Use alternative MFA methods (e.g., email or authenticator app) if SMS delivery issues occur


