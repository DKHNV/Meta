# Meta DNS Maintenance Report

Generated: `2026-08-27T00:00:46Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 50 |
| Pending | 0 |
| Suspect | 31 |
| Quarantine | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 48 |
| Unknown | 1 |
| Suspect | 1 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **50**
Average stability: **96.0%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 2 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `msgin-regional.vvv.facebook.com` | unknown | `2026-08-27T00:00:46Z` | 1 | TIMEOUT | 173.252.82.250, 66.220.149.251 | 0.0 | 1 |
| `smtpin.vvv.facebook.com` | suspect | `2026-08-21T08:46:23Z` | 24 | TIMEOUT | 173.252.82.250, 66.220.149.251 | 0.0 | 24 |

## Discovery

Discovery state updated: `2026-08-27T00:00:46Z`

## Notes

- Public active DNS file: `Meta_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
