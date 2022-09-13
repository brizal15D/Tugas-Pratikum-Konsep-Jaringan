Muhammad Rizal

3121600007

2 D4 IT A

**CISCO -- PACKET TRACKER**

Pada data di ICMP layer 3 harus adanya SOURCE MAC address (head) dan
DESTINATION MAC address (tail).

![1](https://github.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/tree/main/Laporan%20CISCO/assets/image1.png){width="3.4588156167979003in"
height="2.708711723534558in"}

Contoh kasus ada 3 pc.
![2](https://github.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/tree/main/Laporan%20CISCO/assets/image2.png){width="6.268055555555556in"
height="6.081944444444445in"}

PC 0 / 192.168.1.1

![3](https://github.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/tree/main/Laporan%20CISCO/assets/image3.png){width="5.261150481189851in"
height="1.1459930008748906in"}

PC 1 / 192.168.1.2

![4](https://github.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/tree/main/Laporan%20CISCO/assets/image4.png){width="5.240314960629921in"
height="1.1043208661417323in"}

PC 2 / 192.168.1.3

![5](https://github.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/tree/main/Laporan%20CISCO/assets/image5.png){width="2.9900010936132984in"
height="0.4375612423447069in"}

i.  Mengecek ARP pada PC 0

![6](https://github.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/tree/main/Laporan%20CISCO/assets/image6.png){width="3.240034995625547in"
height="2.2919860017497813in"}![7](https://github.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/tree/main/Laporan%20CISCO/assets.png){width="3.240034995625547in"
height="2.229478346456693in"}

ii. Broadcasting 1 (PC 0)

![8](https://github.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/tree/main/Laporan%20CISCO/assets/image8.png){width="3.510906605424322in"
height="2.229478346456693in"}

iii. Broadcasting 2 (PC 1)

![9](https://github.com/rizal15D/Tugas-Pratikum-Konsep-Jaringan-/tree/main/Laporan%20CISCO/assets/image9.png){width="3.4900699912510937in"
height="2.4586767279090114in"}

iv. Pesan / Message


1.  PC 0 ke PC 1 (start awal)

Ketika kita nge-ping PC 1 (192.168.1.2) dengan menggunakan PC 0
(192.168.1.1) , PC 0 akan mencari PC dengan ip 192.168.1.2 dengan cara
broadcast untuk memenuhi layer 2 encapsulation. PC 2 (192.168.1.3) dan
PC 1 (192.168.1.2) akan menerima broadcast yang dimana penerima
merupakan 1 jaringan. Namun, yang membalas hanya PC 1 (192.168.1.2)
sedangkan PC 2 (192.168.1.3) tidak. Jadi layer 2 akan mendapatkan
DESTINATION MAC dan melakukan encapsulation. PING dikirim. ARP akan
disimpan ARP cache jadi PC 0 tidak akan melakukan broadcasting untuk
mencari PC 1 dan berlaku juga pada PC 1 sehingga PC 1 tidak perlu
melakukan broadcast.

2.  PC 0 ke PC 1

Ketika kita nge-ping pc 1 (192.168.1.2) dengan menggunakan PC 0
(192.168.1.1), PC 0 tidak akan broadcast lagi karena telah tersimpan di
ARP cache.

3.  PC 1 ke PC 0

Ketika kita nge-ping PC 0 (192.168.1.1) dengan menggunakan PC 1
(192.168.1.2) , PC 1 akan sudah mempunyai PC 2 dengan ip 192.168.1.1
karena telah broadcast pada kasus pertama tadi untuk memenuhi layer 2
encapsulation. Namun, yang membalas hanya PC 0 (192.168.1.1) sedangkan
PC 2 (192.168.1.3) tidak. Jadi layer 2 akan mendapatkan DESTINATION MAC
dan melakukan encapsulation. PING dikirim. ARP akan disimpan ARP cache
jadi PC 1 tidak akan melakukan broadcasting untuk mencari PC 0.
