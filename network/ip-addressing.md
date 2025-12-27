# IP Addressing Scheme

## Network Overview
Private IP addressing using RFC1918 standards.

### Management Network (VLAN 99)
| Device | IP Address |
|------|------------|
| MikroTik Router | 192.168.99.1 |
| Core Switch 1 | 192.168.99.2 |
| Core Switch 2 | 192.168.99.3 |
| Omada Controller | 192.168.99.10 |

---

### Server Network (VLAN 10)
| Server | IP Address |
|------|------------|
| Dell R220 – Server 1 | 192.168.10.10 |
| Dell R220 – Server 2 | 192.168.10.11 |

---

### Staff Network (VLAN 20)
- DHCP Range: `192.168.20.100 – 192.168.20.200`
- Gateway: `192.168.20.1`

---

### CCTV Network (VLAN 30)
- Static IPs
- Range: `192.168.30.10 – 192.168.30.100`

---

### Guest / Wi-Fi (VLAN 40)
- DHCP Enabled
- Internet-only access
- No internal routing
