# Meta DNS Maintenance Report

Generated: `2026-10-16T22:58:14Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 56 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 29 |
| Excluded | 0 |
| Expired | 2 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 52 |
| Unknown | 2 |
| Suspect | 0 |
| Dead | 2 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **56**
Average stability: **92.9%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 2 |
| TLS_CERT_ERROR | 2 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `msgin-regional.vvv.facebook.com` | dead | `2026-08-27T00:00:46Z` | 185 | TIMEOUT | 173.252.82.250, 173.252.87.251 | 0.0 | 45 |
| `smtpin.vvv.facebook.com` | dead | `2026-08-21T08:46:23Z` | 208 | TIMEOUT | 173.252.87.251 | 0.0 | 45 |
| `vault.x2p.facebook.net` | unknown | `2026-10-15T07:41:37Z` | 8 | TLS_CERT_ERROR | 157.240.11.220, 57.144.221.129, 57.144.5.129 | 0.0 | 8 |
| `vaulthosted.x2p.facebook.net` | unknown | `2026-10-15T07:41:37Z` | 8 | TLS_CERT_ERROR | 157.240.11.220, 57.144.203.129, 57.144.221.129 | 0.0 | 8 |

## Discovery

Discovery state updated: `2026-10-16T22:58:14Z`

## Notes

- Public active DNS file: `Meta_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
