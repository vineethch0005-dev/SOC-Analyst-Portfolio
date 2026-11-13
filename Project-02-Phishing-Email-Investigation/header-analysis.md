# Email Header Analysis

## 1. Scenario

An employee receives an unexpected email claiming to be from the company CEO.

## 2. Sample Email Header

- From: ceo@company.com
- Return-Path: bounce@external-example.invalid
- SPF: PASS
- DKIM: FAIL
- DMARC: FAIL

Note: This is fictional sample data for educational purposes.

## 3. Investigation Findings

1. The visible sender claims to be the company CEO.
2. The Return-Path uses a different domain.
3. SPF passes, but this does not establish that the authenticated domain aligns with the visible From domain.
4. DKIM fails, so the signature could not be successfully verified.
5. DMARC fails, indicating that neither SPF nor DKIM provided successful aligned authentication.

## 4. Risk Assessment

- Classification: Suspicious Email
- Severity: Medium to High – Pending Investigation
- Potential Risk: Sender spoofing or impersonation.

## 5. Recommended SOC Actions

1. Verify the CEO's email through an independent communication channel.
2. Inspect the complete email headers.
3. Check SPF and DKIM alignment.
4. Review URLs and attachments safely.
5. Search for similar emails received by other employees.
6. Escalate to the security team.

## 6. Conclusion

The email contains suspicious authentication indicators and possible sender impersonation.

It should be investigated further before confirming it as phishing.

No actual compromise has been confirmed.

Note: This is a simulated educational investigation.
