
# Phishing Email Investigation Notes

## 1. Email Details

- Sender: it-support@example.invalid
- Reply-To: account-help@unknown.invalid
- Subject: Urgent: Your company account will be suspended!
- Attachment: Account_Verification.html
- URL: hxxps://company-login.example.invalid/verify

## 2. Suspicious Indicators

1. Urgent language creates pressure on the recipient.
2. Sender identity is not verified.
3. Reply-To address differs from the sender.
4. Email requests credential verification through a link.
5. Unexpected HTML attachment is included.

## 3. Authentication Checks

- SPF: Not available in simulated evidence.
- DKIM: Not available in simulated evidence.
- DMARC: Not available in simulated evidence.

## 4. Initial Assessment

Classification: Potential Phishing Email

Risk: High – Pending Investigation

## 5. Recommended Actions

1. Do not click the link.
2. Do not open the attachment.
3. Verify the sender through an independent official channel.
4. Preserve the original email and headers.
5. Report and escalate to the security team.
6. Search for similar emails delivered to other employees.

## 6. Conclusion

The email contains multiple phishing indicators, including urgency, a mismatched Reply-To address, a credential verification request and an unexpected HTML attachment.

The email is classified as suspected phishing pending further technical validation.

Note: This is a simulated educational investigation.

