# Phishing-emails

Awareness of phishing tactics and email threat analysis skills

---

## 📸 Screenshots

Here are some screenshots I captured to help visualize how phishing emails operate.

### 1. 📨 Phishing Email Interface

This shows how the phishing email appeared in my inbox.

* The sender’s address looks close to legitimate but is spoofed.
* The subject and body use panic-inducing phrases like “Immediate Action Required”.

<img width="657" alt="Screenshot 2025-05-27 at 12 36 05" src="https://github.com/user-attachments/assets/14de7e49-426b-4725-bf6a-4d05ba6b1558" />

---

### 2. 🔗 Hover Link Preview

Hovering over the button/link in the email reveals a suspicious domain (`fake-paypal-verification.com`) rather than an official PayPal URL.

<img width="1429" alt="Screenshot 2025-05-27 at 12 18 56" src="https://github.com/user-attachments/assets/716b1ab1-d795-4149-a05b-1afc7a49fbb4" />

---

### 3. 🧾 Email Header Analysis

I used an email header analyzer to examine the full headers.
The results show:

* SPF: `softfail` — sender not authorized.
* DKIM: `fail` — email not signed by a valid source.
* IP address: `192.0.2.45`, which isn’t linked to PayPal.

<img width="1425" alt="Screenshot 2025-05-27 at 12 14 58" src="https://github.com/user-attachments/assets/6667b700-7153-4699-9798-f39829b94b9b" />  
<img width="1423" alt="Screenshot 2025-05-27 at 12 15 01" src="https://github.com/user-attachments/assets/d00e0a48-3f06-417a-aec8-6f67873980ea" />

> *Note: These screenshots are only for educational use and do not reflect real PayPal communications.*

---

## 🚩 Red Flags in This Email

### 1. **Sender Email Address is Spoofed**

The sender’s address was `support@paypalsecurity-alert.com`.
It tries to look official but clearly isn’t a real PayPal domain.

---

### 2. **Header Analysis Shows Discrepancies**

I analyzed the email headers using a tool like Google Admin Toolbox:

* SPF = softfail
* DKIM = fail
* Sender IP = unverified (not a PayPal server)

---

### 3. **Suspicious Links or Attachments**

There were no attachments, but the “Verify My Account Now” button leads to a phishing domain, **not** PayPal.

---

### 4. **Urgent or Threatening Language**

The email contains phrases like:

* “Your account has been suspended”
* “Immediate Action Required”
* “Your account may be permanently disabled”

This type of pressure tactic is common in phishing.

---

### 5. **Mismatched URLs**

The displayed link seems legitimate, but when I hovered over it, it pointed to `http://fake-paypal-verification.com`.

---

### 6. **Spelling or Grammar Issues**

There weren’t any glaring typos, but it used a **generic salutation** like “Dear Customer” instead of addressing me by name — another red flag.

---

### 7. **Summary of Phishing Traits**

Here's a quick summary of the phishing indicators I found:

* Spoofed sender address
* Failed SPF and DKIM checks
* Suspicious, misleading link
* Urgent and alarming tone
* Generic greeting
* Fake domain trying to impersonate a known brand

---

## ✅ What I Did (and You Should Too)

1. **Did not click any links**.
2. **Did not reply** to the sender.
3. **Reported the email** to the real PayPal ([spoof@paypal.com](mailto:spoof@paypal.com)).
4. **Deleted it immediately**.
5. **Enabled two-factor authentication (2FA)** on my accounts for extra protection.

---

## 📬 Feedback

If you have feedback or want to contribute more phishing examples, feel free to open an issue or submit a pull request.

Stay safe online.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

> **Disclaimer:** This material is for educational and awareness purposes only.
> All third-party content (e.g., screenshots of PayPal impersonation) is used under fair use to demonstrate phishing tactics.
> All trademarks and copyrights remain the property of their respective owners.
