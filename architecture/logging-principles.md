# Cloud Logging Design Principles

Cloud logging is a security control, not an operational afterthought.

## 1. Completeness

Logging should cover:
- identity and access events
- control plane activity
- data access where applicable
- security-relevant configuration changes

Gaps in any of these areas create blind spots that cannot be retroactively fixed.

## 2. Integrity

Logs must be protected from:
- unauthorized modification
- accidental deletion
- delayed delivery

Controls should exist to detect log tampering or loss.

## 3. Timeliness

Security logs must be available quickly enough to support response.

Delayed logs reduce containment options and increase uncertainty during incidents.

## 4. Consistency

Log formats and fields should be consistent across services and accounts.

Inconsistent schemas slow investigations and increase error rates.

## 5. Retention

Retention periods should reflect:
- investigation needs
- regulatory requirements
- incident discovery timelines

Short retention creates artificial incident response limits.
