**Muhammad Rizal**

**2 D4 IT A**

**3121600007**

**Praktikum - Static Routing**

**1. Topologi Jaringan**

![Gambar 1](https://raw.githubusercontent.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/main/Laporan%208/assets/001.png)

Kita buat topologi jaringan seperti gambar di atas.

**2. Setting IP PC**

|**PC**|**IP**|**Default Gateway**|
| :-: | :-: | :-: |
|0|192.168.4.2|192.168.4.1|
|1|192.168.5.2|192.168.5.0|
**3. Setting Interface Router**

**Router 2**

|**Interface**|**IP**|
| :-: | :-: |
|0|192.168.2.1|
|1|192.168.3.1|
|2|192.168.4.1|
**Router 1**

|**Interface**|**IP**|
| :-: | :-: |
|0|192.168.1.1|
|1|192.168.3.2|
|2|192.168.5.1|
**Router 0**

|**Interface**|**IP**|
| :-: | :-: |
|0|192.168.2.2|
|1|192.168.1.2|
**4. Setting Static Routing**

|**Destination**|**Netmask**|**Interface**|
| :-: | :-: | :-: |
|192.168.5.0|255.255.255.0|192.168.3.2|
|192.168.4.0|255.255.255.0|192.168.3.1|
|192.168.4.0|255.255.255.0|192.168.2.1|
|192.168.5.0|255.255.255.0|192.168.1.1|

![Gambar 2](https://raw.githubusercontent.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/main/Laporan%208/assets/002.png) 
![Gambar 3](https://raw.githubusercontent.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/main/Laporan%208/assets/003.png)

