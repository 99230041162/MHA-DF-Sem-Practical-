# Email Authentication Lab – SPF, DKIM, DMARC

## 🎯 Aim
To analyze and understand email authentication techniques (SPF, DKIM, DMARC) and identify whether an email is spoofed or genuine.

## ⚙️ Tools Used
- Gmail (View Original Header)
- GitHub
- Google Workspace (klu.ac.in domain)

## 🧪 Procedure
1. Collected a real email header from Gmail.
2. Analyzed SPF, DKIM, and DMARC results.
3. SPF and DMARC passed successfully.
4. DKIM failed due to message forwarding.
5. Concluded that the email is **not spoofed**.

## ✅ Result
The email from `hodcse@klu.ac.in` was **authentic**, because SPF and DMARC passed successfully.
