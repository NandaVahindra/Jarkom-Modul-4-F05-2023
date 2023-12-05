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

