# IOC Analysis – Phishing Email Investigation

## 1. Objective

Identify and document potential Indicators of Compromise (IOCs) from a simulated phishing email.

## 2. Identified IOCs

| IOC Type | Indicator | Observation |
|---|---|---|
| Sender Email | it-support@example.invalid | Unverified sender |
| Reply-To | account-help@unknown.invalid | Different from sender |
| Domain | company-login.example.invalid | Suspicious login domain |
| URL | hxxps://company-login.example.invalid/verify | Credential verification link |
| Attachment | Account_Verification.html | Unexpected HTML attachment |

## 3. IOC Analysis

1. The sender address requires verification.
2. The Reply-To address does not match the sender.
3. The URL uses a domain that is not verified as an official company domain.
4. The HTML attachment may contain a credential-harvesting page or other unsafe content.

## 4. Risk Assessment

Classification: Potential Phishing

Initial Risk: High – Pending Investigation

## 5. Recommended Actions

1. Do not click the suspicious URL.
2. Do not open the attachment.
3. Preserve the original email and headers.
4. Check whether other employees received the same email.
5. Report and escalate to the security team.
6. Block confirmed malicious indicators according to company procedures.

## 6. Conclusion

Multiple suspicious indicators were identified in the simulated email. Further technical investigation is required before confirming malicious activity.

Note: This is a fictional educational investigation. All domains use the reserved .invalid namespace.
