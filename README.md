## Exercise 2: Phishing Emails in Action (TryHackMe)

### Introduction
This exercise focuses on analyzing real phishing email samples and identifying common phishing techniques such as spoofed senders, malicious links, urgency, and malicious attachments.

---

### Task 2: Cancel Your PayPal Order
This phishing email impersonates PayPal to trick users into canceling a fake order.

Techniques identified:
- Spoofed email address
- URL shortening
- HTML impersonation of PayPal
- Urgency

Key findings:
- Sender email mismatch (service@paypal.com vs gibberish@sultanbogor.com)
- The sender email starts with: noreply

---

### Task 3: Track Your Package
This email pretends to be a shipping notification.

Techniques identified:
- Spoofed sender
- Pixel tracking
- Link manipulation

Key findings:
- Tracking pixels were used to gather victim information
- Root domain of the malicious URL (defanged): devret[.]xyz

---

### Task 4: Select Your Email Provider to View Document
This email attempts to harvest user credentials.

Techniques identified:
- Urgency
- HTML impersonation
- Credential harvesting
- Poor grammar

Key findings:
- Fake login pages impersonating OneDrive and Adobe
- Other company name used in the email: Citrix

---

### Task 5: Please Update Your Payment Details
This email impersonates Netflix billing.

Techniques identified:
- Spoofed sender
- Urgency
- Malicious attachment
- Poor grammar

Key findings:
- Sender email: z99@musacombi.online
- Users should forward suspicious Netflix emails to: phishing@netflix.com

---

### Task 6: Your Recent Purchase
This phishing email impersonates Apple Support.

Techniques identified:
- Spoofed sender
- BCC usage
- Urgency
- Malicious attachment

Key findings:
- BCC stands for: Blind Carbon Copy
- Technique used to pressure victim: Urgency

---

### Task 7: DHL Express Courier Shipping Notice
This email impersonates DHL delivery services.

Techniques identified:
- Spoofed sender
- HTML impersonation
- Malicious Excel attachment

Key findings:
- Executable file run by the attachment: regasms.exe

---

### Conclusion
This exercise enhanced my understanding of how phishing emails use social engineering, impersonation, urgency, and malicious attachments to trick victims. By carefully analyzing sender details, email content, links, and attachments, phishing attacks can be identified and prevented effectively.
