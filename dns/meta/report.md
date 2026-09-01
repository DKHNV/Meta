# Meta DNS Maintenance Report

Generated: `2026-09-01T22:46:58Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 50 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 31 |
| Excluded | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 48 |
| Unknown | 0 |
| Suspect | 1 |
| Dead | 1 |

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
| `msgin-regional.vvv.facebook.com` | suspect | `2026-08-27T00:00:46Z` | 23 | TIMEOUT | 173.252.87.251, 66.220.149.251 | 0.0 | 23 |
| `smtpin.vvv.facebook.com` | dead | `2026-08-21T08:46:23Z` | 46 | TIMEOUT | 173.252.82.250, 173.252.87.251, 66.220.149.251 | 0.0 | 46 |

## Discovery

Discovery state updated: `2026-09-01T22:46:58Z`

## Notes

- Public active DNS file: `Meta_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
