# Identifying-Phishing-Emails

A phishing email is a fraudulent message that appears to come from a legitimate source, often used to steal sensitive data like usernames, passwords, or credit card numbers.

1. **Examine Sender's Email Address for Spoofing**
   - Attackers often fake (or spoof) the sender’s address to make the email look like it’s from a trusted source.
   - What to look for:
     - Slight misspellings (e.g., support@paypa1.com instead of support@paypal.com)
     - Generic domains (e.g., Gmail or Yahoo for corporate communication)
     - Inconsistencies between the display name and actual email
     - Always check the actual address, not just the name

2. **Check email headers for discrepancies (using online header analyzer)**
   - Email headers show the path where the email came from; use an online header analyzer.
   - Analyze your email headers through tools like MxToolbox Email Header Analyzer.
   - Look for anomalies such as:
     - IP addresses from strange countries
     - Received fields that don’t align with the claimed sender
     - SPF, DKIM, or DMARC failures (authentication problems)

3. **Identify suspicious links or attachments**
   - Check for suspicious links or unrelated domains in URLs.
   - Avoid clicking links.
   - Look for suspicious attachments in emails (e.g., .pdf, .exe, .docm, .zip) as these may include malicious scripts.
   - Be aware of attachments from unknown or untrusted sources.

4. **Look for urgent or threatening language in the email body**
   - Many phishing emails contain threatening messages like "your account has been hacked," "immediate action required," etc.
   - These messages create fear, pressure, or a sense of urgency.

5. **Note any mismatched URLs (hover to see real link)**
   - Hover your mouse over any hyperlink (without clicking) to see the actual destination.
   - If the displayed link differs from the actual destination, it's likely malicious.
   - Example:
     - Text shows: https://www.google.com
     - Hover reveals: http://malicious-site.ru/login
   - On mobile, long-press links (without tapping) to preview them.

6. **Verify presence of spelling or grammar errors**
   - Check for grammar mistakes in emails, such as:
     - Broken sentences
     - Misspellings or awkward phrasing
     - Inconsistent tone
   - Attackers may intentionally write grammar errors to bypass spam filters and target less attentive users.
