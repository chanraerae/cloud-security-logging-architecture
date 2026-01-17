# Common Cloud Logging Failure Modes

Many cloud security failures stem from logging assumptions.

## 1. Partial Visibility

- Logs enabled in some accounts but not others
- Inconsistent service coverage
- New services launched without logging defaults

## 2. Silent Log Loss

- Quotas exceeded without alerting
- Misconfigured delivery targets
- Dependency failures not monitored

## 3. Investigation Friction

- Logs spread across systems without correlation
- Missing identifiers for tracing activity
- Time skew between sources

## 4. Audit Surprises

- Retention misaligned with requirements
- Logs deleted before audits
- No proof of log integrity

These failures often surface only during incidents or audits, when remediation is most costly.
