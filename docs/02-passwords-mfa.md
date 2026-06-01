# Module 02 — Password & MFA Policy

**Training Program:** AKG IT Security Awareness (IT-SEC-AWARE-01)  
**Estimated Read Time:** ~5 minutes

---

## Password Requirements

All AKG corporate accounts must comply with the following password policy:

| Requirement | Value |
|-------------|-------|
| Minimum length | 14 characters |
| Complexity | Uppercase + lowercase + digit + special character |
| Expiry | Every 90 days |
| History | Cannot reuse last 12 passwords |
| Restrictions | Cannot contain your name, username, or "AKG" |
| Sharing | **Prohibited** — no exceptions |

> **Policy:** Sharing credentials is a policy violation regardless of intent. If a colleague needs access, submit an access request via the IT portal — do not share your password.

---

## Password Strength Examples

| Type | Example | Status |
|------|---------|--------|
| Weak | `AKG2024!` | ❌ Dictionary word + year — cracked in seconds |
| Strong | `Tr!#9vKm@wqLz4` | ✅ Random, 14+ chars, no pattern |

---

## Password Manager (Required)

You are expected to use one of the following corporate-approved tools:

- **KeePass** — corporate-licensed, preferred for offline use
- **Bitwarden** — approved for cloud-synced use

Password managers eliminate the need to memorize complex passwords and prevent reuse across systems. Contact IT for setup assistance.

---

## Multi-Factor Authentication (MFA)

MFA is **mandatory** on all AKG systems: VPN, Microsoft 365, Azure AD, and all internal applications.

### Enrollment

- Enroll in **Microsoft Authenticator** within your first working day
- Use app-based TOTP (time-based one-time passwords)
- SMS-based OTP is no longer accepted on critical systems

### MFA Rules

- **Never approve** an MFA prompt you did not initiate
- Always verify the number code on screen matches the Authenticator prompt before approving
- Unexpected prompts = assume credential compromise — deny, change password, report

> **Attack Vector — MFA Fatigue:** Attackers send repeated push notifications hoping you click "Approve" to stop the noise. If you receive more than one unexpected prompt, deny all and report to IT Security immediately.

---

## Privileged Accounts

If your role requires admin or elevated-privilege access, additional requirements apply:

- Separate credentials for privileged accounts (not your day-to-day login)
- Privileged Access Workstation (PAW) for sensitive tasks
- Quarterly access reviews — unused privileges will be revoked

---

## Key Contacts

| Need | Action |
|------|--------|
| MFA enrollment help | IT Helpdesk — Ext. 2200 |
| Suspicious MFA activity | it-security@akg.com immediately |
| Password manager setup | IT Helpdesk ticket |

---

*Previous: [Module 01 — Phishing](01-phishing.md) | Next: [Module 03 — Acceptable Use Policy](03-acceptable-use.md)*
