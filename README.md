# Tugas DAY 4 Training ARC
## 18223044 - Princessfa Azzahra Alvin

- **Router Name:** Floor14
- **Switch Name:** Room-146
- **IP Addressing:** IPv4 & IPv6 configured for all devices
- **VLANs:** VLAN 1 used for management
- **Routing:** Static 
- **Security:**
  - Console and VTY line passwords set (`cisco`)
  - Enable secret password (`class`)
  - Service password encryption enabled
- **Connectivity:** All devices successfully ping each other (IPv4 & IPv6)

#### **Router Floor14**
| Interface | IPv4 Address | Subnet Mask | IPv6 Address |
| G0/0 | 172.14.5.1 | 255.255.255.0 | 2001:DB8:CAFE:1::1/64 |
| G0/1 | 172.14.10.1 | 255.255.255.0 | 2001:DB8:CAFE:2::1/64 |

#### **Switch Room-146**
| Interface | IPv4 Address | Subnet Mask | Default Gateway |
| VLAN 1 | 172.14.10.35 | 255.255.255.0 | 172.14.10.1 |
