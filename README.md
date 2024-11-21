Deskripsi project :
-
Membuat kerangka API Automation dengan Gorest sebagai object testing. Project ini menggunakan framework testing JUnit dengan menggunakan library RestAssured untuk melakukan pengujian API berbasis HTTP dan menggunakan konsep POM (Page Model Object).

Cara run project :
-
- Buka project menggunakan Intellij Idea
- Buka terminal
- Ketik ./gradlew apiTest
- Enter

Screenshot hasil pengujian tes positif dan negatif
- 
Tes positif: uji API untuk respons yang benar dengan input yang benar.
Hasil Run menggunakan terminal (custom task)
 ![Screenshot 2024-11-21 132217](https://github.com/user-attachments/assets/cef82678-f636-489a-a8ed-9d67893c410b)
![Screenshot 2024-11-21 132240](https://github.com/user-attachments/assets/9b4952a8-25b6-4ee2-a0f4-15da71bea81b)

Report dari cucumber 
  ![Screenshot 2024-11-21 132356](https://github.com/user-attachments/assets/0c4ed733-721e-40d1-ad97-022843354909)
  ![Screenshot 2024-11-21 132410](https://github.com/user-attachments/assets/5f4aa2f3-fbbc-406c-80c4-04aee63f5e0c)
![Screenshot 2024-11-21 132427](https://github.com/user-attachments/assets/6ddf7697-02ad-41a3-810d-e4d32bfe4b73)

Tes negatif: uji API untuk respons yang salah dengan input yang salah, seperti mengirim tipe data yang salah atau kolom wajib diisi tidak ada.

Negatif test > tidak menginputkan kolom nama
![Screenshot 2024-11-21 133645](https://github.com/user-attachments/assets/1b43a99e-ba1e-4d83-9775-cf7798faea2e)
![Screenshot 2024-11-21 133603](https://github.com/user-attachments/assets/3ae533b9-0675-4fb1-a36d-627c32948b4a)
![Screenshot 2024-11-21 133617](https://github.com/user-attachments/assets/50c86116-315c-49fd-a75e-5e19b2d4d28c)
  
Negatif test > input status menjadi aktif (seharusnya pilih antara active/inactive)
 ![Screenshot 2024-11-21 133907](https://github.com/user-attachments/assets/8b763d8b-aefd-4f5b-855f-528d3cb1bf47)
![Screenshot 2024-11-21 133921](https://github.com/user-attachments/assets/e2587808-9cff-4d3d-823f-81112e1a16cc)
 ![Screenshot 2024-11-21 133930](https://github.com/user-attachments/assets/4b48fdc7-6795-4599-9f61-415bd1256c14)


 


