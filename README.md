Deskripsi project :
-
Membuat kerangka API Automation dengan Gorest sebagai object testing. Project ini menggunakan framework testing JUnit dengan menggunakan library RestAssured untuk melakukan pengujian API berbasis HTTP dan menggunakan konsep POM (Page Model Object). Skenario testing mencakup GET, POST, PATCH, dan DELETE.

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
  
Negatif test > menguji input dengan user dengan gender "males" yang seharusnya adalah male/female

Models.java
![Screenshot 2024-11-25 104221](https://github.com/user-attachments/assets/7f3d57cc-c097-49f5-ad1f-5019fe19537e)

api.feature
![Screenshot 2024-11-25 104243](https://github.com/user-attachments/assets/cddd8aac-44a5-4958-bb88-99d9dd869b79)

GitHub Action Workflow
![Screenshot 2024-11-29 084125](https://github.com/user-attachments/assets/7682efa6-a1b5-464f-a5ad-54c04b035b0d)



 


