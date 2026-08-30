# Contents of security 

## Firewall contents

- [ ] Firewall hardware or software — the device/system that enforces the rules.

- [ ] Network interfaces — connections to the Internet/WAN, LAN, DMZ, etc.

- [ ] Rule set / access-control policies — specifies which traffic is allowed or blocked.

- [ ] Stateful inspection — tracks active connections and their states.

- [ ] NAT (Network Address Translation) — translates private and public IP addresses when needed.

- [ ] Logging and monitoring — records allowed, blocked, and suspicious traffic.

- [ ] Authentication/identity controls — can restrict access based on users or devices.

- [ ] VPN support — provides encrypted remote or site-to-site connections.

- [ ] Intrusion detection/prevention (IDS/IPS) — identifies and potentially blocks malicious traffic.

- [ ] Configuration and management interface — used by administrators to configure the firewall.

- [ ] Updates/signatures — keeps threat-detection rules and software current.

## IPS Privicy layer on top of Firewall from stopping website tracking systems

                                                 ┌──────────────────────┐
                                                 │       Browser        │
                                                 └──────────┬───────────┘
                                                            │
                                               ┌──────────────────────────┐
                                               │    Privacy Enforcement   │
                                               │          Layer           │
                                               └────────────┬─────────────┘
                                                            │
                                                 ┌──────────▼───────────┐
                                                 │ Windows Firewall/WFP │
                                                 └──────────┬───────────┘
                                                            │
                                                         Internet

## Privicy Enforcement Layer Contents

 - [ ] API protection    
 - [ ] Fingerprint ctrl  
 - [ ] Data policies     
 - [ ] Tracker blocking  
 - [ ] DNS filtering     
 - [ ] Cookie/storage    
 - [ ] Permission ctrl   
 - [ ] Profile manager
 - [ ] Audit/logging



