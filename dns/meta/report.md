# Meta DNS Maintenance Report

Generated: `2026-10-16T13:28:49Z`

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
| `msgin-regional.vvv.facebook.com` | dead | `2026-08-27T00:00:46Z` | 183 | TIMEOUT | 173.252.87.251, 66.220.149.251 | 0.0 | 44 |
| `smtpin.vvv.facebook.com` | dead | `2026-08-21T08:46:23Z` | 206 | TIMEOUT | 173.252.87.251, 66.220.149.251 | 0.0 | 44 |
| `vault.x2p.facebook.net` | unknown | `2026-10-15T07:41:37Z` | 6 | TLS_CERT_ERROR | 57.144.217.129 | 0.0 | 6 |
| `vaulthosted.x2p.facebook.net` | unknown | `2026-10-15T07:41:37Z` | 6 | TLS_CERT_ERROR | 57.144.217.129 | 0.0 | 6 |

## Discovery

Discovery state updated: `2026-10-16T13:28:49Z`

## Notes

- Public active DNS file: `Meta_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
