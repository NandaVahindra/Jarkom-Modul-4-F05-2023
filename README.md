# Jarkom-Modul-4-F05-2023  
Apta Rasendriya Wijaya - 5025211139  
Made Nanda Wija Vahindra - 5025211160  

## VLSM (CPT)
### Topologi
![image](https://github.com/NandaVahindra/Jarkom-Modul-4-F05-2023/assets/114988957/c163a0ed-2f20-491e-8451-0d392b038399)
![pkt vlsm](https://github.com/NandaVahindra/Jarkom-Modul-4-F05-2023/assets/114988957/1b467970-b73a-434b-9ee3-3f01b5c3934e)

### Alokasi IP
| Subnet | Jumlah IP | Netmask |
|:-------------|:--------------|:--------------|
| A1         | 1023         | /21         |
| A2         | 2         | /30         |
| A3         | 1001         | /22         |
| A4         | 2         | /30         |
| A5         | 2         | /30         |
| A6         | 6         | /29         |
| A7         | 25         | /27         |
| A8         | 2         | /30         |
| A9         | 2         | /30         |
| A10         | 127         | /24         |
| A11        | 2         | /30         |
| A12        | 2         | /30         |
| A13        | 3         | /29         |
| A14        | 2         | /30         |
| A15        | 1001         | /22         |
| A16        | 251         | /24         |
| A17        | 2         | /30         |
| A18        | 255         | /23         |
| A19        | 2         | /30         |
| A20        | 31         | /26         |
| A21        | 512         | /22         |
| Total        | 4225         | /19         |

### Tree 
![Prak modul 4 - VLSM](https://github.com/NandaVahindra/Jarkom-Modul-4-F05-2023/assets/114988957/f312be4a-ef02-41fd-a9bb-6036f749ee21)  

### Pembagian Subnet 
![image](https://github.com/NandaVahindra/Jarkom-Modul-4-F05-2023/assets/114988957/99f64aab-80d4-4fd9-971f-9906308f64ad)

### Routing 

Aura
```
10.54.0.64/27 via 10.54.0.14
10.54.0.4/30 via 10.54.0.14
10.54.0.0/30 via 10.54.0.14
10.54.24.0/21 via 10.54.0.14
10.54.20.0/22 via 10.54.0.14
10.54.0.8/30 via 10.54.0.14
10.54.0.48/29 via 10.54.0.14
10.54.9.0/24 via 10.54.0.18
10.54.0.20/30 via 10.54.0.22
10.54.0.24/30 via 10.54.0.22
10.54.0.40/29 via 10.54.0.22
10.54.0.28/30 via 10.54.0.22
10.54.16.0/22 via 10.54.0.22
10.54.8.0/24 via 10.54.0.22
10.54.0.32/30 via 10.54.0.22
10.54.10.0/23 via 10.54.0.22
10.54.0.36/30 via 10.54.0.22
10.54.0.128/26 via 10.54.0.22
10.54.12.0/22 via 10.54.0.22
```
Frieren
```
10.54.24.0/21 via 10.54.0.6
10.54.0.0/30 via 10.54.0.6
10.54.20.0/22 via 10.54.0.6
10.54.0.8/30 via 10.54.0.6
10.54.0.48/29 via 10.54.0.6
0.0.0.0/0 via 10.54.0.13
```
Flamme
```
10.54.24.0/21 via 10.54.0.2
10.54.0.48/29 via 10.54.0.10
0.0.0.0/0 via 10.54.0.5
```
Fern
```
0.0.0.0/0 via 10.54.0.1
```
Himmel
```
0.0.0.0/0 via 10.54.0.9
```
Denken
```
0.0.0.0/0 via 10.54.0.17
```
Eisen
```
0.0.0.0/0 via 10.54.0.21
10.54.16.0/22 via 10.54.0.30
10.54.8.0/24 via 10.54.0.30
10.54.10.0/23 via 10.54.0.34
10.54.0.36/30 via 10.54.0.34
10.54.0.128/26 via 10.54.0.34
10.54.12.0/22 via 10.54.0.34
```
Lugner
```
0.0.0.0/0 via 10.54.0.29
```
Linie
```
0.0.0.0/0 via 10.54.0.33
10.54.0.128/26 via 10.54.0.38
10.54.12.0/22 via 10.54.0.38
```
Lawine
```
0.0.0.0/0 via 10.54.0.37
10.54.12.0/22 via 10.54.0.131
```
Heiter
```
0.0.0.0/0 via 10.54.0.129
```

## CIDR (GNS3)
### Topologi
![image](https://github.com/NandaVahindra/Jarkom-Modul-4-F05-2023/assets/114988957/c163a0ed-2f20-491e-8451-0d392b038399)
![image](https://github.com/NandaVahindra/Jarkom-Modul-4-F05-2023/assets/116022017/7171a6d8-6af9-435c-b9c5-09b354234b2f)

### Alokasi IP
A
| Subnet | Jumlah IP | Netmask |
|:-------------|:--------------|:--------------|
| A1         | 1023         | /21         |
| A2         | 2         | /30         |
| A3         | 1001         | /22         |
| A4         | 2         | /30         |
| A5         | 2         | /30         |
| A6         | 6         | /29         |
| A7         | 25         | /27         |
| A8         | 2         | /30         |
| A9         | 2         | /30         |
| A10         | 127         | /24         |
| A11        | 2         | /30         |
| A12        | 2         | /30         |
| A13        | 3         | /29         |
| A14        | 2         | /30         |
| A15        | 1001         | /22         |
| A16        | 251         | /24         |
| A17        | 2         | /30         |
| A18        | 255         | /23         |
| A19        | 2         | /30         |
| A20        | 31         | /26         |
| A21        | 512         | /22         |
| Total        | 4225         | /19         |

B
| Node | Alokasi | Netmask |
|:-------------|:--------------|:--------------|
| B1(A1,A2)         | 1025         | /20         |
| B2(A5,A6)         | 8         | /28         |
| B3(A21,A20)         | 544         | /21         |
| B4(A16,A15)         | 1252         | /21         |

C
| Node | Alokasi | Netmask |
|:-------------|:--------------|:--------------|
| C1(A3,B2)         | 1009         | /21         |
| C2(A19,B3)         | 546         | /20         |
| C3(A14,B4)         | 1254         | /20         |
| C4(A9,A10)         | 129         | /23         |

D
| Node | Alokasi | Netmask |
|:-------------|:--------------|:--------------|
| D1(B1,C1)         | 2034         | /19         |
| D2(A18,C2)         | 801         | /19         |
| D3(A12,C3)         | 1256         | /19         |

E
| Node | Alokasi | Netmask |
|:-------------|:--------------|:--------------|
| E1(D1,A4)         | 2036         | /18         |
| E2(A17,D2)         | 803         | /18         |
| E3(A13,D3)         | 1259         | /18         |

F
| Node | Alokasi | Netmask |
|:-------------|:--------------|:--------------|
| F1(A7,E1)         | 2061         | /17         |

G
| Node | Alokasi | Netmask |
|:-------------|:--------------|:--------------|
| G1(A8,E1)         | 2063         | /16         |
| G2(E2,E3)         | 2062         | /17         |

H
| Node | Alokasi | Netmask |
|:-------------|:--------------|:--------------|
| H1(A11,G2)         | 2064         | /16         |

I
| Node | Alokasi | Netmask |
|:-------------|:--------------|:--------------|
| I1(C4,H1)         | 2193         | /15         |

J
| Node | Alokasi | Netmask |
|:-------------|:--------------|:--------------|
| J1(G1,I1)         | 4256         | /14         |

### Tree 
![Prak modul 4 - CIDR_F05](https://github.com/NandaVahindra/Jarkom-Modul-4-F05-2023/assets/116022017/e64d0b25-5b9c-4c9f-b1b6-ca412db4c1be)

### Pembagian Subnet 
![pembagian IP CIDR](https://github.com/NandaVahindra/Jarkom-Modul-4-F05-2023/assets/116022017/7be88f26-84dc-4748-9c47-e251a21f2e1a)

![image](https://github.com/NandaVahindra/Jarkom-Modul-4-F05-2023/assets/116022017/70ca4813-e0fc-4396-89b8-96df53e7a48e)

##Konfigurasi

LaubHills
```
#LaubHills
auto eth0
iface eth0 inet static
    address 10.57.0.1
    netmask 255.255.248.0
    gateway 10.57.0.3
```
AppetitRegion
```
#AppetitRegion
auto eth0
iface eth0 inet static
    address 10.57.0.2
    netmask 255.255.248.0
    gateway 10.57.0.3
```
Fern
```
#Fern
#a1
auto eth0
iface eth0 inet static
    address 10.57.0.3
    netmask 255.255.248.0
#a2
auto eth1
iface eth1 inet static
    address 10.57.8.1
    netmask 255.255.255.252
    gateway 10.57.8.2
```
RohrRoad
```
#RohrRoad
auto eth0
iface eth0 inet static
    address 10.57.16.1
    netmask 255.255.252.0
    gateway 10.57.16.2
```
Flamme
```
#Flamme
#a2
auto eth1
iface eth1 inet static
    address 10.57.8.2
    netmask 255.255.255.252
#a3
auto eth3
iface eth3 inet static
    address 10.57.16.2
    netmask 255.255.252.0
#a5
auto eth2
iface eth2 inet static
    address 10.57.20.10
    netmask 255.255.255.252
#a4
auto eth0
iface eth0 inet static
    address 10.57.32.1
    netmask 255.255.255.252
    gateway 10.57.32.2
```
ScheweMountains
```
#ScheweMountains
auto eth0
iface eth0 inet static
    address 10.57.20.1
    netmask 255.255.255.248
    gateway 10.57.20.2
```
Himmel
```
#Himmel
#a6
auto eth0
iface eth0 inet static
    address 10.57.20.2
    netmask 255.255.255.248
#a6
auto eth2
iface eth2 inet static
    address 10.57.20.9
    netmask 255.255.255.252
    gateway 10.57.20.10
```
LakeKorridor
```
#LakeKorridor
auto eth0
iface eth0 inet static
    address 10.57.64.1
    netmask 255.255.255.224
    gateway 10.57.64.2
```
Frieren
```
#Frieren
auto eth2
iface eth2 inet static
    address 10.57.64.2
    netmask 255.255.255.224
#a4
auto eth0
iface eth0 inet static
    address 10.57.32.2
    netmask 255.255.255.252
#a8
auto eth1
iface eth1 inet static
    address 10.57.128.1
    netmask 255.255.255.252
    gateway 10.57.128.2
```
Aura
```
#Aura
#a8
auto eth1
iface eth1 inet static
    address 10.57.128.2
    netmask 255.255.255.224
#a9
auto eth3
iface eth3 inet static
    address 10.56.1.2
    netmask 255.255.255.252
#a11
auto eth2
iface eth2 inet static
    address 10.54.128.2
    netmask 255.255.255.252
```
Denken
```
#Denken
#a8
auto eth3
iface eth3 inet static
    address 10.56.1.1
    netmask 255.255.255.252
    gateway 10.56.1.2
#a10
auto eth0
iface eth0 inet static
    address 10.56.0.1
    netmask 255.255.255.0
```
Royal
```
#Royal
auto eth0
iface eth0 inet static
    address 10.56.0.2
    netmask 255.255.255.0
    gateway 10.56.0.1
```
WilleRegion
```
#WilleRegion
auto eth0
iface eth0 inet static
    address 10.56.0.3
    netmask 255.255.255.0
    gateway 10.56.0.1
```
Eisen
```
#Eisen
#a11
auto eth2
iface eth2 inet static
    address 10.54.128.1
    netmask 255.255.255.252
    gateway 10.54.128.2
#a12
auto eth3
iface eth3 inet static
    address 10.54.80.1
    netmask 255.255.255.252
#a13
auto eth0
iface eth0 inet static
    address 10.54.96.1
    netmask 255.255.255.248
#a14
auto eth4
iface eth4 inet static
    address 10.54.72.1
    netmask 255.255.255.252
#a17
auto eth1
iface eth1 inet static
    address 10.54.32.1
    netmask 255.255.255.252
```
Stark
```
#Stark
auto eth0
iface eth0 inet static
    address 10.54.80.2
    netmask 255.255.255.0
    gateway 10.54.80.1
```
Richter
```
#Richter
auto eth0
iface eth0 inet static
    address 10.54.96.2
    netmask 255.255.255.0
    gateway 10.54.96.1
```
Revolte
```
#Revolte
auto eth0
iface eth0 inet static
    address 10.54.96.3
    netmask 255.255.255.0
    gateway 10.54.96.1
```
Lugner
```
#Lugner
#a14
auto eth0
iface eth0 inet static
    address 10.54.72.2
    netmask 255.255.255.252
    gateway 10.54.72.1
#a15
auto eth1
iface eth1 inet static
    address 10.54.64.1
    netmask 255.255.252.0
#a16
auto eth2
iface eth2 inet static
    address 10.54.68.1
    netmask 255.255.255.0
```
TurkRegion
```
#TurkRegion
auto eth0
iface eth0 inet static
    address 10.54.64.2
    netmask 255.255.252.0
    gateway 10.54.64.1
```
GrobeForest
```
#GrobeForest
auto eth0
iface eth0 inet static
    address 10.54.68.2
    netmask 255.255.255.0
    gateway 10.54.68.1
```
Linie
```
#Linie
#a17
auto eth1
iface eth1 inet static
    address 10.54.32.2
    netmask 255.255.255.252
    gateway 10.54.32.1
#a18
auto eth0
iface eth0 inet static
    address 10.54.16.1
    netmask 255.255.254.0
#a19
auto eth2
iface eth2 inet static
    address 10.54.8.1
    netmask 255.255.255.252
```
Lawine
```
#Lawine
#a19
auto eth2
iface eth2 inet static
    address 10.54.8.2
    netmask 255.255.255.252
    gateway 10.54.8.1
#a20
auto eth0
iface eth0 inet static
    address 10.54.4.1
    netmask 255.255.255.192
```
GranzChannel
```
#GranzChannel
auto eth0
iface eth0 inet static
    address 10.54.16.2
    netmask 255.255.254.0
    gateway 10.54.16.1
```
BerdRegion
```
#BerdRegion
auto eth0
iface eth0 inet static
    address 10.54.4.2
    netmask 255.255.255.192
    gateway 10.54.4.1
```
Heiter
```
#Heiter
#a20
auto eth0
iface eth0 inet static
    address 10.54.4.3
    netmask 255.255.255.192
    gateway 10.54.4.1
#a21
auto eth1
iface eth1 inet static
    address 10.54.0.1
    netmask 255.255.252.0
```
Sein
```
#Sein
auto eth0
iface eth0 inet static
    address 10.54.0.2
    netmask 255.255.252.0
    gateway 10.54.0.1
```
ReigelCanyon
```
#ReigelCanyon
auto eth0
iface eth0 inet static
    address 10.54.0.3
    netmask 255.255.252.0
    gateway 10.54.0.1
```

### Routing 

Flamme
```
route add -net 10.57.0.0 netmask 255.255.248.0 gw 10.57.8.1
route add -net 10.57.20.0 netmask 255.255.255.248 gw 10.57.20.9
```
Flamme
```
route add -net 10.57.0.0 netmask 255.255.248.0 gw 10.57.32.1
route add -net 10.57.8.0 netmask 255.255.255.252 gw 10.57.32.1
route add -net 10.57.16.0 netmask 255.255.252.0 gw 10.57.32.1
route add -net 10.57.20.8 netmask 255.255.255.252 gw 10.57.32.1
route add -net 10.57.20.0 netmask 255.255.255.248 gw 10.57.32.1
```
Aura
```
route add -net 10.57.0.0 netmask 255.255.248.0 gw 10.57.128.1
route add -net 10.57.8.0 netmask 255.255.255.252 gw 10.57.128.1
route add -net 10.57.16.0 netmask 255.255.252.0 gw 10.57.128.1
route add -net 10.57.32.0 netmask 255.255.255.252 gw 10.57.128.1
route add -net 10.57.20.8 netmask 255.255.255.252 gw 10.57.128.1
route add -net 10.57.20.0 netmask 255.255.255.248 gw 10.57.128.1
route add -net 10.57.64.0 netmask 255.255.255.224 gw 10.57.128.1

route add -net 10.56.0.0 netmask 255.255.255.0 gw 10.56.1.1

route add -net 10.54.128.0 netmask 255.255.255.252 gw 10.54.128.1
route add -net 10.54.80.0 netmask 255.255.255.252 gw 10.54.128.1
route add -net 10.54.96.0 netmask 255.255.255.248 gw 10.54.128.1
route add -net 10.54.72.0 netmask 255.255.255.252 gw 10.54.128.1
route add -net 10.54.64.0 netmask 255.255.252.0 gw 10.54.128.1
route add -net 10.54.68.0 netmask 255.255.255.0 gw 10.54.128.1
route add -net 10.54.32.0 netmask 255.255.255.252 gw 10.54.128.1
route add -net 10.54.16.0 netmask 255.255.254.0 gw 10.54.128.1
route add -net 10.54.8.0 netmask 255.255.255.252 gw 10.54.128.1
route add -net 10.54.4.0 netmask 255.255.255.192 gw 10.54.128.1
route add -net 10.54.0.0 netmask 255.255.252.0 gw 10.54.128.1
```
Eisen
```
route add -net 10.54.64.0 netmask 255.255.252.0 gw 10.54.72.2
route add -net 10.54.68.0 netmask 255.255.255.0 gw 10.54.72.2
route add -net 10.54.16.0 netmask 255.255.254.0 gw 10.54.32.2
route add -net 10.54.8.0 netmask 255.255.255.252 gw 10.54.32.2
route add -net 10.54.4.0 netmask 255.255.255.192 gw 10.54.32.2
route add -net 10.54.0.0 netmask 255.255.252.0 gw 10.54.32.2
```
Linie
```
route add -net 10.54.4.0 netmask 255.255.255.192 gw 10.54.8.2
route add -net 10.54.0.0 netmask 255.255.252.0 gw 10.54.8.2
```
Lawine
```
route add -net 10.54.0.0 netmask 255.255.252.0 gw 10.54.4.3
```
