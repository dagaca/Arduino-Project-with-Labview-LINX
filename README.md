# LabVIEW LINX ile Arduino Projesi

## Genel Bakış

Bu repo, çeşitli bileşenleri kullanarak kapsamlı bir sistem oluşturmak amacıyla LabVIEW LINX kullanılarak geliştirilmiş bir Arduino projesini içerir. Proje, HC-SR04 ultrasonik sensör ile mesafe ölçme, verileri LabVIEW Front Panel üzerinde anlık gösterme, bir servo motoru kontrol etme, servo motor konumlarını bir Excel dosyasına kaydetme ve LDR (Foto Direnç) ile ortam ışığını izleme odaklıdır.


## Arduino Devre Malzemeleri

1 adet Arduino UNO​, 2 adet Breadboard​, 1 adet HC-SR04 Mesafe Sensörü​, 1 adet SG90 Servo Motor​, 1 adet Foto direnç (LDR)​, 1 adet Buzzer​, 2 adet Buton​, 1 adet Led​, 5 adet Direnç.


![arduino_circuit_materials](https://github.com/dagaca/Arduino-Project-with-Labview-LINX/assets/80363244/7f6e147a-8385-4119-b8c7-ec819120a0b9)


## Arduino Devre Şeması​


![arduino_circuit_diagram](https://github.com/dagaca/Arduino-Project-with-Labview-LINX/assets/80363244/128362d4-34ea-42b5-9a47-97d477afe713)


## Proje Detayları
### HC-SR04 ile Mesafe Ölçme

- Mesafe ölç ve verileri bir metin dosyasına kaydet.
- Mesafe verilerini grafik ve göstergeler kullanarak Front Panel üzerinde göster.
- Mesafe 2 cm ile 30 cm arasında değilse, bir buzzer alarmını etkinleştir.
- Servo motorun etkinliğini fiziksel bir düğme ile kontrol et.

### Servo Motor Kontrolü
- Front Panel üzerinde bir LED ile servo motor durumunu göster.
- Mesafe sensörü verilerine dayanarak servo motor pozisyonunu ayarla.
- Servo motor pozisyonlarını bir Excel dosyasına kaydet.
- Servo motor açısını Front Panel üzerinde görselleştir.

### Foto Direnç ile Işık Ölçümü
- Ortam ışığını ölç ve verileri bir metin dosyasına kaydet.
- Işık verilerini göstergeler kullanarak Front Panel üzerinde göster.
- Işık seviyesi belirli bir eşik altındaysa LED'leri etkinleştir.

### Genel Özellikler
- Veri depolama yollarını Front Panel üzerinden seç.
- Genel program etkinliğini fiziksel veya Front Panel üzerindeki bir düğme ile kontrol et.


## Labview Front Panel​

![labview_front_panel](https://github.com/dagaca/Arduino-Project-with-Labview-LINX/assets/80363244/b0e4517e-e620-4ebb-b73d-1a187e81e0f6)


## Labview Block Diagram

![labview_block_diagram](https://github.com/dagaca/Arduino-Project-with-Labview-LINX/assets/80363244/be90e45d-4095-43aa-81d9-8a0a456e3142)


## Nasıl Başlamalı?​
1. Bu repo'yu bilgisayarınıza klonlayın.
   ```bash
   git clone https://github.com/dagaca/Python-Programming.git
   
2. LabVIEW'de Arduino_Project_with_Labview_LINX.lvproj dosyasını açın.

3. Proje dosyalarını keşfedin ve uygulamayı başlatmak için Arduino_ReadWrite.vi dosyasını çalıştırın.
