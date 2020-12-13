# Jarkom_Modul4_Praktikum_C14
## Kelompok C14
* M Ridho Daffa Ardista 05111840000065
* Rifki Aulia Irawan 05111840000142

# VLSM - CPT
* Pembagian Subnet :
![Soal Shift Modul 4 (1)](https://user-images.githubusercontent.com/57948738/102009363-8eb4b500-3d69-11eb-9775-7fc0637c4ee5.png)
* Tabel Perhitungan dan Pembagian IP  
![{FB00ED9C-73C8-416C-998B-BCCEBCCA652B} png](https://user-images.githubusercontent.com/57948738/102009453-169abf00-3d6a-11eb-8909-88f14ca1e338.jpg)
* Pohon IP :
![VLSM](https://user-images.githubusercontent.com/57948738/102009330-56ad7200-3d69-11eb-8917-8d60fcc31efe.png)

* Routing di CPT
  * Surabaya
```
192.168.8.0/22 via 192.168.0.2
192.168.0.128/25 via 192.168.0.2
192.168.24.0/21 via 192.168.0.2
192.168.2.0/23 via 192.168.0.10
192.168.12.0/22 via 192.168.0.10
192.168.0.16/28 via 192.168.0.10
192.168.0.12/30 via 192.168.0.10
192.168.16.0/22 via 192.168.0.10
192.168.1.0/24 via 192.168.0.10
10.151.77.76/30 via 192.168.0.10
192.168.0.4/30 via 192.168.0.2
```
  * Pasuruan
```
0.0.0.0/0 via 192.168.0.1
192.168.0.128/25 via 192.168.0.6
192.168.24.0/21 via 192.168.0.6
```
  * Probolinggo
```
0.0.0.0/0 via 192.168.0.5
```
  * Madiun
```
0.0.0.0/0 via 192.168.2.1
```
  * Batu
```
0.0.0.0/0 via 192.168.0.9
192.168.0.16/28 via 192.168.2.3
192.168.1.0/24 via 192.168.0.14
192.168.16.0/22 via 192.168.0.14
10.151.77.76/30 via 192.168.0.14
```
  * Kediri
```
0.0.0.0/0 via 192.168.0.13
192.168.16.0/22 via 192.168.1.3
```
  * Blitar
```
0.0.0.0/0 via 192.168.1.1
```
