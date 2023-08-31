---
marp: true
theme: bbzbl
paginate: true
header: Modul 117 - Aufbau von Netzwerken - Adressierung
footer: BBZBL / Gianluca Aebi / Informatik- und Netzinfrastruktur für ein kleines Unternehmen realisieren
---

<!-- _class: big center -->
### Modul 117
## Informatik- und Netzinfrastruktur für ein kleines Unternehmen realisieren

---

<!-- _class: big center -->
### Aufbau von Netzwerken
# Adressierung
## Modul 117

---
# MAC (Media Access Control) - Hardware Adresse

[![MAC Adresse](../images/Aufbau-MAC-Adresse.jpeg)](https://www.com-magazin.de/bilderstrecke/mac-adressen-id-eines-netzwerkadapters-322081.html)

- 48-Bit lange unterteilt in 6 Oktette (jeweils 8 Bit)

---
# IPv4 - Logische Adresse
[![IP Adresse](../images/ipv4.png)](https://bluecatnetworks.com/glossary/what-is-ipv4/)

---
# IPv4 - Subnetting
[![IP Adresse](../images/what-is-a-subnet-how-subnetting-works-2.png)](https://gcore.com/de/learning/what-is-a-subnet-how-subnetting-works/)

---
[![IP Adresse](../images/subnetting-mask.jpg)](https://ipcisco.com/lesson/subnetting-examples/)

---
# IPv4 - Classen
[![IP Adresse](../images/what-is-a-subnet-how-subnetting-works-3.png)](https://gcore.com/de/learning/what-is-a-subnet-how-subnetting-works/)

---
# Private IP

| historische Namen | CIDR-Notation | Netzadressbereich | Anzahl Adressen |
| -------- | ------------ | ---------------------- |----------------|
| Klasse A   | 10.0.0.0/8   | 10.0.0.0 bis 10.255.255.255 | 16'777'216 |
| Klasse B  | 172.16.0.0/12   | 172.16.0.0 bis 172.31.255.255 | 1'048'576 |
| Klasse C  | 192.168.0.0/16   | 192.168.0.0 bis 192.168.255.255 | 65'536 |

---
# Subnetzmasken
[![Public IP](../images/Subnetzmaske.png)](https://www.scaleuptech.com/blog/was-ist-und-wie-funktioniert-subnetting/)

---
Number of hosts = 2^(number of host bits)-2

---
[![IP Adresse](../images/noplacelike.webp)](https://medium.com/@hackersleague/theres-no-place-like-127-0-0-1-explained-1e6af9368e32)

---
# Public IP
[![Public IP](../images/Public-vs-local-IP-addresses.png)](https://www.avg.com/en/signal/public-vs-private-ip-address)

---
# NAT
[![NAT](../images/NAT_Concept.png)](https://en.wikipedia.org/wiki/Network_address_translation)

---
# Static vs. Dynamic
[![Static vs. Dynamic](../images/staticvsdynamicip.png)](https://avocado89.medium.com/networking-static-ip-vs-dynamic-ip-56785ee9b1e4)

---
# IPv6 - Logische Adresse
[![IPv6](../images/IPv6-Adresse.png)](https://www.heise.de/select/ct/2019/12/1559577580718293#&gid=1&pid=3)