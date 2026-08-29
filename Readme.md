### Contents of security 

## Firewall contents

[ ] Firewall hardware or software — the device/system that enforces the rules.

[ ] Network interfaces — connections to the Internet/WAN, LAN, DMZ, etc.

[ ] Rule set / access-control policies — specifies which traffic is allowed or blocked.

[ ] Stateful inspection — tracks active connections and their states.

[ ] NAT (Network Address Translation) — translates private and public IP addresses when needed.

[ ] Logging and monitoring — records allowed, blocked, and suspicious traffic.

[ ] Authentication/identity controls — can restrict access based on users or devices.

[ ] VPN support — provides encrypted remote or site-to-site connections.

[ ] Intrusion detection/prevention (IDS/IPS) — identifies and potentially blocks malicious traffic.

[ ] Configuration and management interface — used by administrators to configure the firewall.

[ ] Updates/signatures — keeps threat-detection rules and software current.

## IPS Privicy layer on top of Firewall from stopping website tracking systems

                 ┌──────────────────────┐
                 │       Browser        │
                 └──────────┬───────────┘
                            │
                 ┌──────────▼───────────────┐
                 │    Privacy Enforcement   │
                 │          Layer           │
                 ├──────────────────────────┤
                 │ 1. [ ] API protection    │
                 │ 2. [ ] Fingerprint ctrl  │
                 │ 3. [ ] Data policies     │
                 │ 4. [ ] Tracker blocking  │
                 │ 5. [ ] DNS filtering     │
                 │ 6. [ ] Cookie/storage    │
                 │ 7. [ ] Permission ctrl   │
                 │ 8. [ ] Profile manager   │
                 │ 9. [ ] Audit/logging     │
                 └──────────┬───────────────┘
                            │
                 ┌──────────▼───────────┐
                 │ Windows Firewall/WFP │
                 └──────────┬───────────┘
                            │
                         Internet

## FUll LAYERS IN SIMPLE MANNER

                    ┌──────────────────────┐
                    │      Web browser     │
                    └──────────┬───────────┘
                               │
                    ┌──────────▼───────────┐
                    │ Privacy enforcement  │
                    │      extension       │
                    └──────────┬───────────┘
                               │
              ┌────────────────▼────────────────┐
              │      Windows Firewall / WFP     │
              │  IP • port • process • network  │
              └────────────────┬────────────────┘
                               │
                            Internet


