# Onaylı Depolar arası stok transferi örneği

Onay vererek depolar arası transfer yapabilmek için 3 kullanıcımız ve 2 depomuz olacak. Bizim örneğimizde kullanıcıların isimleri **1-Akın**,**2-Ceyhu**n,**3-Nazım**.

\-**Akın** kullanıcısında transfer kabul ve transfer onay yetkileri olacak\
\-**Ceyhun** kullanıcısında stok çıkış ve depo transfer yetkisi olacak. Bu kullanıcının depo adı **HANGAR**\
\-**Nazım** kullanıcısında stok çıkış ve depo transfer yetkisi olacak. Bu kullanıcının depo adı **BAKIM**

**İşlem Adımları**

**1-** **Ceyhun** kullanıcısı **Depo Transfer Fişi** ekranından **BAKIM** deposuna **KANALİZASYON PVC BORU** stoğunu transfer eder.

![Depo transfer fişi görüntüsü](<../../../.gitbook/assets/image (39).png>)

**2-Ceyhun** kullanıcısının yaptığı transfer **Onay** ekranına gelir. **Akın** kullanıcısı bu transferi onaylar. Bunun için **Akın** kullanıcısı ana menüdeki **Depo Transfer Onay (Sorumlu)** butonuna tıklar.

![](<../../../.gitbook/assets/image (40).png>)

**Depo Transfer Onay** butonuna **Akın** kullanıcısı tıkladığında transferi onaylayacağı ekran gelecektir. Bu ekranda öncelikle **Sorgula** butonuna tıklar,böylece gelen transferlerin listesi karşısına çıkacaktır.İlgili transfer fişi seçip ekranın alt kısmındaki **Onayla** butonuna tıklar.&#x20;

![](<../../../.gitbook/assets/image (41).png>)

**3-Ceyhun** kullanıcısının **HANGAR** deposundan göndermiş olduğu stok artık **Nazım** Kullanıcısının önüne kabul için gelecektir.\
Kabul işlemi için **Nazım** kullanıcısı ana menüden **Depo Transfer Kabul** butonuna tıklar.&#x20;

![](<../../../.gitbook/assets/image (42).png>)

Bu işlemden sonra **Nazım** kullanıcısının sahip olduğu depolara gelen kabul edilmemiş tüm transfer fişleri gelecektir.&#x20;

![](<../../../.gitbook/assets/image (43).png>)

Bu ekranda **Nazım** kullanıcısı **Kabul Et** butonuna tıklayarak transfer işlemini tamamlar. Böylece  **KANALİZASYON PVC BORU** stoğu **HANGAR** deposundan **BAKIM** deposuna aktarılmış olur. Belirtilen miktar kadar stok **HANGAR** deposundan çıkıp **BAKIM** deposuna eklenir.
