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

Negatif test > menguji penulisan string url yang seharusnya "GET_LIST_USERS" menjadi "GET_LIST_USER"
![Screenshot 2024-11-22 090621](https://github.com/user-attachments/assets/d3e56939-cb89-4da3-b19b-b6ec3c945128)
![Screenshot 2024-11-22 090701](https://github.com/user-attachments/assets/19ab0afc-bee3-47b8-a261-92b4939547d7)

  
Negatif test > menguji status code pada skenario update yang seharusnya 201 menjadi 204
![Screenshot 2024-11-22 090223](https://github.com/user-attachments/assets/78867a22-1eea-4117-9d33-727f127c28c8)
![Screenshot 2024-11-22 090252](https://github.com/user-attachments/assets/441dc4b6-e0f9-443f-9f48-dc82b8cd4830)




 


