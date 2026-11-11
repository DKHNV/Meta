# Meta DNS Maintenance Report

Generated: `2026-11-11T22:12:10Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 56 |
| Pending | 0 |
| Suspect | 29 |
| Quarantine | 0 |
| Excluded | 0 |
| Expired | 2 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 54 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 2 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **56**
Average stability: **96.3%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `instagram.com` | alive | `2026-11-11T01:26:05Z` | 3 | TIMEOUT | 157.240.229.174, 31.13.66.174 | 92.5 | 40 |
| `msgin-regional.vvv.facebook.com` | dead | `2026-08-27T00:00:46Z` | 269 | TIMEOUT | 66.220.149.251 | 0.0 | 40 |
| `smtpin.vvv.facebook.com` | dead | `2026-08-21T08:46:23Z` | 292 | TIMEOUT | 173.252.82.250, 173.252.87.251 | 0.0 | 40 |

## Discovery

Discovery state updated: `2026-11-11T22:12:10Z`

## Notes

- Public active DNS file: `Meta_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
