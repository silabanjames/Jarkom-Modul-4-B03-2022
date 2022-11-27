# Jarkom-Modul-4-B03-2022

## Anggota Kelompok:

| Nama                           | NRP        |
| ------------------------------ | ---------- |
| Maheswara Danendra Satriananda | 5025201060 |
| James Silaban                  | 5025201169 |
| Anak Agung Yatestha Parwata    | 5025201234 |

### Metode VLSM

![pembagian-subnet](https://user-images.githubusercontent.com/70903245/204132406-6114e4ca-94aa-4f12-90ab-593ccd2957f5.jpg)

![diagram-vlsm](https://user-images.githubusercontent.com/70903245/204132345-921ecae6-719c-4824-8869-582abe60849a.jpg)

| Subnet | Node           | IP             | Subnet Mask     | Length |
| ------ | -------------- | -------------- | --------------- | ------ |
| A1     | The Minister   | 192.174.0.1    | 255.255.252.0   | /22    |
| A1     | Guideau        | 192.174.0.2    | 255.255.252.0   |        |
| A2     | The Dauntless  | 192.174.8.1    | 255.255.255.0   | /24    |
| A2     | Phanora        | 192.174.8.2    | 255.255.255.0   |        |
| A2     | Johan          | 192.174.8.3    | 255.255.255.0   |        |
| A3     | The Order      | 192.174.11.193 | 255.255.255.252 | /30    |
| A3     | The Minister   | 192.174.11.194 | 255.255.255.252 |        |
| A4     | The Order      | 192.174.11.129 | 255.255.255.192 | /26    |
| A4     | Ashaf          | 192.174.11.130 | 255.255.255.192 |        |
| A5     | The Resonance  | 192.174.11.197 | 255.255.255.252 | /30    |
| A5     | The Order      | 192.174.11.198 | 255.255.255.252 |        |
| A6     | The Resonance  | 192.174.11.201 | 255.255.255.252 | /30    |
| A6     | The Instrument | 192.174.11.202 | 255.255.255.252 |        |
| A7     | The Resonance  | 192.174.11.205 | 255.255.255.252 | /30    |
| A7     | The Magical    | 192.174.11.206 | 255.255.255.252 |        |
| A8     | The Resonance  | 192.174.11.209 | 255.255.255.252 | /30    |
| A8     | The Beast      | 192.174.11.210 | 255.255.255.252 |        |
| A9     | The Magical    | 192.174.6.1    | 255.255.254.0   | /23    |
| A9     | Corvekt        | 192.174.6.2    | 255.255.254.0   |        |
| A9     | Haines         | 192.174.6.3    | 255.255.254.0   |        |
| A10    | The Instrument | 192.174.10.1   | 255.255.255.128 | /25    |
| A10    | Matt Cugat     | 192.174.10.2   | 255.255.255.128 |        |
| A11    | The Instrument | 192.174.11.213 | 255.255.255.252 | /30    |
| A11    | The Firefist   | 192.174.11.214 | 255.255.255.252 |        |
| A12    | The Instrument | 192.174.11.217 | 255.255.255.252 | /30    |
| A12    | The Profound   | 192.174.11.218 | 255.255.255.252 |        |
| A13    | The Profound   | 192.174.11.1   | 255.255.255.128 | /25    |
| A13    | Heiga          | 192.174.11.2   | 255.255.255.128 |        |
| A14    | The Profound   | 192.174.10.129 | 255.255.255.128 | /25    |
| A14    | The Spendrow   | 192.174.10.130 | 255.255.255.128 |        |
| A15    | The Firefist   | 192.174.9.1    | 255.255.255.0   | /24    |
| A15    | Keith          | 192.174.9.2    | 255.255.255.0   |        |
| A15    | The Queen      | 192.174.9.3    | 255.255.255.0   |        |
| A16    | The Firefist   | 192.174.4.1    | 255.255.254.0   | /23    |
| A16    | Oakleave       | 192.174.4.2    | 255.255.254.0   |        |
| A17    | The Queen      | 192.174.11.221 | 255.255.255.252 | /30    |
| A17    | The Witch      | 192.174.11.222 | 255.255.255.252 |        |
| A18    | The Minister   | 192.174.11.225 | 255.255.255.252 | /30    |
| A18    | The Dauntless  | 192.174.11.226 | 255.255.255.252 |        |

### Metode CIDR

Pertama, kita perlu membuat subnet dalam topologi. Pembuatan subnet dilakukan akan mempermudah pembagian IP yang akan dilakukan

![image](https://user-images.githubusercontent.com/78299006/204123824-6044cb6a-c629-4773-9089-06aaba5e9343.png)

Kemudian, lakukan penggabunggan kepada subnet yang paling bawah, atau paling jauh dari awan. Untuk memudahkan memilah subnet mana yang terletak di bawah, kita dapat mengubah subnet ke dalam bentuk tree.

![image](https://user-images.githubusercontent.com/78299006/204123925-0167a4cd-d424-4a49-8930-0222a4c970f8.png)

Gabungkan subnet paling bawah, seperti berikut

![image](https://user-images.githubusercontent.com/78299006/204123948-8f0a6e83-de90-4922-b6b6-341122c8d1e2.png)

![image](https://user-images.githubusercontent.com/78299006/204124517-ecb2a9a8-1ba1-40c6-bfb2-bfe275206f11.png)

![image](https://user-images.githubusercontent.com/78299006/204124531-341c9761-e880-4c01-adcf-529d52aa86dd.png)

![image](https://user-images.githubusercontent.com/78299006/204124676-48697040-e81a-4507-83c5-750c7633dac3.png)

![image](https://user-images.githubusercontent.com/78299006/204124704-1c2d61e0-2baf-488c-9f95-149bab3334e4.png)

![image](https://user-images.githubusercontent.com/78299006/204124728-f93928fa-00d1-491d-83ff-4f3832847121.png)

![image](https://user-images.githubusercontent.com/78299006/204124737-68d73e63-d9a2-44d2-b34e-ec62050bcbf9.png)

![image](https://user-images.githubusercontent.com/78299006/204124748-226d2e7b-ee71-43f0-bf2e-ba356affc47f.png)

Setelah didapat subnet besar yang mencakup keseluruhan topologi, maka kita akan mendapat netmask /16. Digunakan NID 129.174.0.0 dengan netmask 255.255.0.0. Lakukanlah pembagian IP berdasarkan penggabungan subnet yang telah dibuat

![image](https://user-images.githubusercontent.com/78299006/204124933-1d1dd8d6-08e2-4954-ac61-40a37e3de89c.png)

Berdasarkan tree tersebut, maka didapatkanlah pembgaian IP sebagai berikut:

![image](https://user-images.githubusercontent.com/78299006/204125359-13e5472c-ed31-4c22-93c8-60238f59b65a.png)

![image](https://user-images.githubusercontent.com/78299006/204125368-4c6d3567-32d8-4c73-9a6d-8228a6c1be08.png)

![image](https://user-images.githubusercontent.com/78299006/204125382-80c7ef6c-90b1-466c-b0c0-794ecc313e4a.png)

Kemudian, aturlah pembagian ip di bagian `Edit Network Configuration` pada GNS ke setiap router dan client berdasarkan pembagian ip yang telah didapatkan. Pembagian ip pada setiap node dapat dilihat sebagai berikut:

1. The Resonance (Router)

```
  auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 192.174.64.1
	netmask 255.255.255.252


auto eth2
iface eth2 inet static
	address 192.174.130.1
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 192.174.132.1
	netmask 255.255.255.252

auto eth4
iface eth4 inet static
	address 192.174.0.1
	netmask 255.255.255.252
```

2. The Order (Host)

```
auto eth0
iface eth0 inet static
	address 192.174.64.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 192.174.96.1
	netmask 255.255.255.192

auto eth2
iface eth2 inet static
	address 192.174.112.1
	netmask 255.255.255.252
```

3. Ashaf (Host)

```
auto eth0
iface eth0 inet static
	address 192.174.96.2
	netmask 255.255.255.192
	gateway 192.174.96.1
```

4. The Minister(Router)

```
auto eth0
iface eth0 inet static
	address 192.174.112.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 192.174.120.1
	netmask 255.255.252.0

auto eth2
iface eth2 inet static
	address 192.174.126.1
	netmask 255.255.255.252
```

5. Guideau (Host)

```
auto eth0
iface eth0 inet static
	address 192.174.120.2
	netmask 255.255.252.0
	gateway 192.174.120.1
```

6. The Dauntless (Router)

```
auto eth0
iface eth0 inet static
	address 192.174.126.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 192.174.124.1
	netmask 255.255.255.0
```

7. Phanora (Host)

```
auto eth0
iface eth0 inet static
	address 192.174.124.2
	netmask 255.255.255.0
	gateway 192.174.124.1
```

8. Johan (Host)

```
auto eth0
iface eth0 inet static
	address 192.174.124.152
	netmask 255.255.255.0
	gateway 192.174.124.1
#	addressnya 192.174.124.152 karena range 2-151 dimiliki Phanora
```

9. The Beast (Server)

```
auto eth0
iface eth0 inet static
	address 192.174.132.2
	netmask 255.255.255.252
	gateway 192.174.132.1
```

10. The Magical (Router)

```
auto eth0
iface eth0 inet static
	address 192.174.130.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 192.174.128.1
	netmask 255.255.254.0
```

11. Converkt (Host)

```
auto eth0
iface eth0 inet static
	address 192.174.128.2
	netmask 255.255.254.0
	gateway 192.174.128.1
```

12. Hainess (Host)

```
auto eth0
iface eth0 inet static
	address 192.174.128.202
	netmask 255.255.254.0
	gateway 192.168.0.1
#	2-201 dimiliki oleh Converkt
```

13. The Instrument (Router)

```
auto eth0
iface eth0 inet static
	address 192.174.0.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 192.174.48.1
	netmask 255.255.255.128

auto eth2
iface eth2 inet static
	address 192.174.56.1
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 192.174.32.1
	netmask 255.255.255.252
```

14. Matt Cugat (Host)

```
auto eth0
iface eth0 inet static
	address 192.174.48.2
	netmask 255.255.255.128
	gateway 192.174.48.1
```

15. The Firefist (Router)

```
auto eth0
iface eth0 inet static
	address 192.174.56.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 192.174.63.1
	netmask 255.255.255.0

auto eth2
iface eth2 inet static
	address 192.174.60.1
	netmask 255.255.254.0
```

16. Keith (Host)

```
auto eth0
iface eth0 inet static
	address 192.174.63.2
	netmask 255.255.255.0
	gateway 192.174.63.1
```

17. The Queen (Router)

```
auto eth0
iface eth0 inet static
	address 192.174.63.212
	netmask 255.255.255.0
# address 2-211 dimiliki oleh Keith

auto eth1
iface eth1 inet static
	address 192.174.62.1
	netmask 255.255.255.252
```

18. The Witch (Server)

```
auto eth0
iface eth0 inet static
	address 192.174.62.2
	netmask 255.255.255.252
	gateway 192.174.62.1
```

19. Oakleave (Host)

```
auto eth0
iface eth0 inet static
	address 192.174.60.2
	netmask 255.255.254.0
	gateway 192.174.60.1
```

20. The Prefound (Router)

```
auto eth0
iface eth0 inet static
	address 192.174.32.2
	netmask 255.255.255.252

auto eth1
iface eth1 inet static
	address 192.174.33.1
	netmask 255.255.255.128

auto eth2
iface eth2 inet static
	address 192.174.33.129
	netmask 255.255.255.128
```

21. Spendrow (Host)

```
auto eth0
iface eth0 inet static
	address 192.174.33.2
	netmask 255.255.255.128
	gateway 192.174.33.1
```

22. Helga (Host)

```
auto eth0
iface eth0 inet static
	address 192.174.33.130
	netmask 255.255.255.128
	gateway 192.174.33.129
```

Setelah ip dibagi kepada setiap node, maka sekarang akan dilakukan routing pada setiap router. Routing pada GNS3 dapat dilakukan dengan menggunakan command

```
route add -net <NID subnet> netmask <netmask> gw <IP gateway>
```

Pada praktikum kali ini, routing dilakukan dengan membuat script dalam console setiap router. Setelah script dibuat, kemudian script tersebut dijalankan. Adapun isi script setiap router sebagai berikut:

1. The Resonance

```
route add -net 192.174.120.0 netmask 255.255.252.0 gw 192.174.64.2
#192.174.120.0 -> NID Guideau

route add -net 192.174.124.0 netmask 255.255.252.0 gw 192.174.64.2
#192.174.124.0 -> NID Johan dan Keith

route add -net 192.174.96.0 netmask 255.255.255.192 gw 192.174.64.2
#192.174.96.0 -> NID Asshaf

route add -net 192.174.128.0 netmask 255.255.254.0 gw 192.174.130.2
#192.174.128.0 -> NID Convekt dan Haines

route add -net 192.174.48.0 netmask 255.255.255.128 gw 192.174.0.2
#192.174.48.0 -> NID MattCugat

route add -net 192.174.63.0 netmask 255.255.255.0 gw 192.174.0.2
#192.174.63.0 -> NID Keith

route add -net 192.174.62.0 netmask 255.255.255.252 gw 192.174.0.2
#192.174.62.0 -> NID TheWitch

route add -net 192.174.60.0 netmask 255.255.254.0 gw 192.174.0.2
#192.174.60.0 -> Oakleave

route add -net 192.174.33.128 netmask 255.255.255.128 gw 192.174.0.2
#192.174.33.128 -> NID Helga

route add -net 192.174.33.0 netmask 255.255.255.128 gw 192.174.0.2
#192.174.33.0 -> NID Spendrow
```

2. The Order

```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.174.64.1

route add -net 192.174.120.0 netmask 255.255.252.0 gw 192.174.112.2
#192.174.120.0 -> NID Guideau

route add -net 192.174.124.0 netmask 255.255.252.0 gw 192.174.112.2
#192.174.124.0 -> NID Johan dan Phanora
```

3. The Minister

```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.174.112.1
#192.174.112.1 -> IP GW TheOrder

route add -net 192.174.124.0 netmask 255.255.255.0 gw 192.174.126.2
#192.174.124.0 -> NID Johan dan Phanora
```

4. The Dauntless

```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.174.126.1
#192.174.126.1 -> IP GW TheMinister
```

5. The Magical

```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.174.130.1
```

6. The Instrument

```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.174.0.1

route add -net 192.174.63.0 netmask 255.255.255.0 gw 192.174.56.2
#192.174.63.0 -> NID Keith

route add -net 192.174.62.0 netmask 255.255.255.252 gw 192.174.56.2
#192.174.62.0 -> NID TheWitch

route add -net 192.174.60.0 netmask 255.255.254.0 gw 192.174.56.2
#192.174.60.0 -> NID Oakleave

###

route add -net 192.174.33.128 netmask 255.255.255.128 gw 192.174.32.2
#192.174.33.128 -> NID Helga

route add -net 192.174.33.0 netmask 255.255.255.128 gw 192.174.32.2
#192.174.33.0 -> NID Spendrow
```

7. The Prefound

```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.174.32.1
```

8. The Firefist

```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.174.56.1

route add -net 192.174.62.0 netmask 255.255.255.252 gw 192.174.63.212
#192.174.62.0 -> NID TheWitch
```

9. The Queen

```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.174.63.1
```

#### Testing

Setelah script dibuat dan dijalankan, kita dapat melakukan testing dengan cara melakukan ping.

_Guideau(Host) ke The Resonance(Router)_

![image](https://user-images.githubusercontent.com/78299006/204126950-36797205-6f30-4d5c-b661-8394db6f585c.png)

_Guideau(Host) ke Spendrow(Host)_

![image](https://user-images.githubusercontent.com/78299006/204127074-121ecd25-b195-413f-933d-a1459cc7259f.png)

_The Helga(Host) ke The Dauntless(Router)_

![image](https://user-images.githubusercontent.com/78299006/204127219-aa59a706-b0c8-4280-b86d-b1561b458af4.png)
