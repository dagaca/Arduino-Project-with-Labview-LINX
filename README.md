# Arduino-Project-with-Labview-LINX

## Arduino Devre Malzemeleri

1 adet Arduino UNO​, 2 adet Breadboard​, 1 adet HC-SR04 Mesafe Sensörü​, 1 adet SG90 Servo Motor​, 1 adet Foto direnç (LDR)​, 1 adet Buzzer​, 2 adet Buton​, 1 adet Led​, 5 adet Direnç.


![arduino_circuit_materials](https://github.com/dagaca/Arduino-Project-with-Labview-LINX/assets/80363244/7f6e147a-8385-4119-b8c7-ec819120a0b9)


## Arduino Devre Şeması​


![arduino_circuit_diagram](https://github.com/dagaca/Arduino-Project-with-Labview-LINX/assets/80363244/128362d4-34ea-42b5-9a47-97d477afe713)


## Projenin Amacı ve Detayları​

- Mesafe sensörü ile cismin uzaklık verilerinin ölçülerek bir metin belgesine kaydedilmesi.​

- Mesafe sensöründen gelen verilerin Front Panel’de grafik, indikatör ve string yardımları ile gösterilmesi.​

- Mesafe sensöründen gelen veriler eğer 30 cm – 2 cm aralığında değilse buzzerın bir alarm niteliği görmesi ve Front Panel’de bir Alan Uyarı ifadesinin belirmesi.​

- Servo motorun aktifliğinin fiziksel bir buton ile kontrol edilmesi. Buton Durumunun Front Panel’de bir led ile gösterilmesi. Servo motorun anlık olarak kontrol edilebileceğinin bir uyarı niteliğinde Front Panel’de gösterilmesi.

- Mesafe sensöründen gelen verilere bağlı olarak cismin konumunun belirli bir katsayı ile çarpılarak servo motora verilmesi ve servo motor pervanesinin cismin konumunu belirlemesi.​

- Servo motorun açısında bir değişiklik algılandığında Front Panel’de yer alan ledin yanması ve bir excel dosyasına 1. Konum, 2.Konum… şeklinde kaydedilmesi.​

- Servo motorun açısının Front Panel’de indikatör, grafik aracılığı ile gösterilmesi.​

- Eğer servo motoru kontrol eden buton aktif değilse bu verilerin kaydedilmesi duracaktır. Tekrar aktif edildiğinde kaydedilmeye devam edecektir.

- Foto sensör ile ortamın ışık seviyesinin ölçülerek bir metin belgesine kaydedilmesi.​

- Foto sensörden alınan verilerin indikatör ve gösterge aracılığı ile Front Panel’de gösterilmesi.​

- Front Panel’de bulunan Foto sensör sınır değerinin altına düşüldüğünde fiziksel ledin ve Front Panel’de bulunan ledin yanması. Ortam ışığının sınır değerin altına düştüğünün uyarısının Front Panel’de gösterilmesi.​

- Verilerin kaydedilmesi için yolların Front Panel’den seçilmesi ve hem metin belgesi hem de excel dosyası için veri sayılarının Front Panel’de gösterilmesi.​

- Tüm programın aktifliğinin fiziksel bir buton veya Front Panel’de yer alan buton ile kontrol edilebilmesi.


## Labview Front Panel​

![labview_front_panel](https://github.com/dagaca/Arduino-Project-with-Labview-LINX/assets/80363244/b0e4517e-e620-4ebb-b73d-1a187e81e0f6)


## Labview Block Diagram

![labview_block_diagram](https://github.com/dagaca/Arduino-Project-with-Labview-LINX/assets/80363244/be90e45d-4095-43aa-81d9-8a0a456e3142)
