# Security Considerations

This document outlines key security considerations for operating
hybrid cloud infrastructure across AWS and Azure environments.

The focus is on practical, enforceable controls rather than
theoretical security models.

---

## Identity and Access Management

- Apply least-privilege principles
- Separate administrative and application access
- Use role-based access where possible
- Regularly review access permissions

---

## Network Security

- Restrict inbound access to required endpoints only
- Use network segmentation to limit blast radius
- Avoid exposing management interfaces publicly

---

## Data Protection

- Encrypt data at rest and in transit where supported
- Protect backup data with appropriate access controls
- Ensure secure handling of credentials and secrets

---

## Operational Security

- Apply patching and update policies
- Monitor for suspicious activity
- Maintain audit logs for access and changes

---

## Scope Notes

This document intentionally avoids vendor-specific security services
to keep the guidance broadly applicable.