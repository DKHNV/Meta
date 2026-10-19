# Meta DNS Maintenance Report

Generated: `2026-10-19T08:02:45Z`

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
| Unknown | 0 |
| Suspect | 2 |
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
| `msgin-regional.vvv.facebook.com` | dead | `2026-08-27T00:00:46Z` | 194 | TIMEOUT | 173.252.87.251 | 0.0 | 46 |
| `smtpin.vvv.facebook.com` | dead | `2026-08-21T08:46:23Z` | 217 | TIMEOUT | 66.220.149.251 | 0.0 | 46 |
| `vault.x2p.facebook.net` | suspect | `2026-10-15T07:41:37Z` | 17 | TLS_CERT_ERROR | 31.13.89.222, 57.144.201.129, 57.145.21.129 | 0.0 | 17 |
| `vaulthosted.x2p.facebook.net` | suspect | `2026-10-15T07:41:37Z` | 17 | TLS_CERT_ERROR | 31.13.89.222, 57.144.195.129, 57.144.201.129 | 0.0 | 17 |

## Discovery

Discovery state updated: `2026-10-19T08:02:45Z`

## Notes

- Public active DNS file: `Meta_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
