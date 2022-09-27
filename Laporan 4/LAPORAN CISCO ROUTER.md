**ANALISA ROUTING PAKET - TRACKING**

1.  **Topologi Jaringan**

![](vertopal_17d7a2db96a64143891804ff23cadcc6/media/image1.png){width="4.198502843394576in"
height="2.6566207349081363in"}

Komponen diatas adalah 2 router, 2 pc, 2 copper straight, dan 1 copper
cross over

2.  **Konfigurasi IP untuk PC**

![Graphical user interface, application, email Description automatically
generated](vertopal_17d7a2db96a64143891804ff23cadcc6/media/image2.png){width="6.268055555555556in"
height="6.0993055555555555in"}

**Konfigurasi IP PC 1 diatas adalah**

-   Static

-   IPv4 Address : 192.168.1.2

-   Subnet mask : 255. 255. 255.0

-   Default gateway : 192.168.1.1

![Graphical user interface, application, email Description automatically
generated](vertopal_17d7a2db96a64143891804ff23cadcc6/media/image3.png){width="6.268055555555556in"
height="6.064583333333333in"}

**Konfigurasi IP PC 2 diatas adalah**

-   Static

-   IPv4 Address : 192.168.1.2

-   Subnet mask : 255. 255. 255.0

-   Default gateway : 192.168.1.1

3.  **Konfigurasi Router**

![Graphical user interface, text, application Description automatically
generated](vertopal_17d7a2db96a64143891804ff23cadcc6/media/image4.png){width="6.268055555555556in"
height="6.107638888888889in"}

**Pengaturan pada router0 GigabitEthernet0/0/0 diatas adalah**

-   Port status : ON

-   Bandwith : Auto

-   Duplex : Auto

-   Mac Address : 0060.70A4.1C01 (Auto)

-   IPv4 Address : 192.168.1.1

![](vertopal_17d7a2db96a64143891804ff23cadcc6/media/image5.png){width="6.268055555555556in"
height="6.090277777777778in"}

**Pengaturan pada router0 GigabitEthernet0/0/1 diatas adalah**

-   Port status : ON

-   Bandwith : Auto

-   Duplex : Auto

-   Mac Address : 0060.70A4.1C02 (Auto)

-   IPv4 Address : 192.168.2.1

Atur juga pada router1

**Untuk router1 GigabitEthernet0/0/0 adalah**

-   Port status : ON

-   Bandwith : Auto

-   Duplex : Auto

-   Mac Address : 00D0.BCE6.C001 (Auto)

-   IPv4 Address : 192.168.3.2

**Untuk router1 GigabitEthernet0/0/1 adalah**

-   Port status : ON

-   Bandwith : Auto

-   Duplex : Auto

-   Mac Address : 00D0.BCE6.C002 (Auto)

-   IPv4 Address : 192.168.2.2

4.  **Tes ping PC1 ke PC2**

![Graphical user interface, text Description automatically
generated](vertopal_17d7a2db96a64143891804ff23cadcc6/media/image6.png){width="6.268055555555556in"
height="6.08125in"}

Diketahui bahwa terdapat 2 kali gagal/lost dan 2 kali received. Hal ini
dapat terjadi karena broadcast dilakukan disaat pertama dan melewati
router.

![Graphical user interface, text, application Description automatically
generated](vertopal_17d7a2db96a64143891804ff23cadcc6/media/image7.png){width="6.268055555555556in"
height="6.072222222222222in"}

Pada PC2 telah berhasil menyimpan hasil broadcast yang telah dilakukan
PC1 sehingga akan didapat hasil seperti dibawah ini.

![A screenshot of a computer Description automatically
generated](vertopal_17d7a2db96a64143891804ff23cadcc6/media/image8.png){width="6.268055555555556in"
height="6.08125in"}

Ping dari PC2 ke PC1 tidak akan kehilangan paket/data karena ARP telah
disimpan sebelumnya.
