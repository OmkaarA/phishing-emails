# Phishing-emails  
Awareness of phishing tactics and email threat analysis skills.

---

## 📸 Screenshots

Below are sample screenshots that illustrate phishing email characteristics and email header analysis. These are included for educational purposes only.

### 1. 📨 Phishing Email Interface  
- A sample of the phishing email as received in the inbox.  
- Highlights spoofed sender address and urgent language.

<img width="657" alt="Screenshot 2025-05-27 at 12 36 05" src="https://github.com/user-attachments/assets/14de7e49-426b-4725-bf6a-4d05ba6b1558" />

---

### 2. 🔗 Hover Link Preview  
- Screenshot showing the link preview when hovered.  
- Reveals a mismatched and suspicious URL not pointing to the real PayPal domain.

<img width="1429" alt="Screenshot 2025-05-27 at 12 18 56" src="https://github.com/user-attachments/assets/716b1ab1-d795-4149-a05b-1afc7a49fbb4" />

---

### 3. 🧾 Email Header Analysis  
- Screenshot from an email header analyzer tool (e.g., Google Admin Toolbox).  
- Shows SPF/DKIM failures and an unverified sender IP address.

<img width="1425" alt="Screenshot 2025-05-27 at 12 14 58" src="https://github.com/user-attachments/assets/6667b700-7153-4699-9798-f39829b94b9b" />
<img width="1423" alt="Screenshot 2025-05-27 at 12 15 01" src="https://github.com/user-attachments/assets/d00e0a48-3f06-417a-aec8-6f67873980ea" />

> 📝 *Note: All screenshots are for demonstration purposes only. They do not represent real PayPal services.*

---

## 🔍 Phishing Detection Checklist

### 1. 📫 **Sender Email Address**
- Email is from `support@paypalsecurity-alert.com`, which mimics PayPal but is not an official domain.
- Spoofed domain resembling a legitimate one (`paypalsecurity-alert.com`).

### 2. 🧾 **Header Discrepancies**
- **SPF** check: `softfail` → indicates the sender is not authorized.
- **DKIM**: `fail` → the message was not signed by a verified domain.
- **IP Address**: `192.0.2.45` is not associated with PayPal servers.

### 3. 🔗 **Suspicious Links**
- Link text: “Verify My Account Now”.
- Actual destination (when hovered) redirects to a phishing site, not PayPal.

### 4. ⚠️ **Urgent or Threatening Language**
- “Your account has been suspended”.
- “Immediate Action Required”.
- “Your account may be permanently disabled”.

These phrases are commonly used to create panic and push the user into taking rash actions.

### 5. 🌐 **Mismatched URLs**
- The displayed link text differs from the actual URL (e.g., `paypal.com` vs `fake-paypal-verification.com`).
- Phishing emails often disguise harmful URLs with legitimate-looking text.

### 6. 📝 **Spelling or Grammar Errors**
- There are no apparent grammatical or spelling mistakes, but the message uses a **generic salutation** (“Dear Customer”) instead of addressing the recipient by name.
- Small details like tone and formatting help reveal illegitimacy.

### 7. 🧠 **Phishing Traits Summary**
- Spoofed sender email address
- Failed SPF and DKIM checks
- Urgent and threatening language
- Suspicious or masked hyperlinks
- Lack of personalization
- Fake domains mimicking trusted brands

---

## ✅ What To Do If You Receive Such Emails

1. **Do not click any links.**  
2. **Do not reply to the sender.**  
3. **Report the email** to the real service provider (e.g., `spoof@paypal.com`).  
4. **Delete the email immediately.**  
5. **Enable two-factor authentication (2FA)** on your accounts for extra security.

---

## 📬 Feedback

Feel free to open an issue or submit a pull request to contribute improvements or add more phishing examples.

Stay safe online! 🌐🛡️

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for full details.

---

> **Disclaimer:** This project is for educational and awareness purposes only.  
> Screenshots, email samples, and references to third-party websites or brands (e.g., PayPal) are used under fair use to demonstrate phishing techniques.  
> All trademarks and copyrights belong to their respective owners.
