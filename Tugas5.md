Nama : Prawira Setia Ramdhani Kelas : INF – A2
NPM : 41155050210062


TUGAS 5
A.	K-Nearest Neighbours (KNN). Lakukan praktik dari https://youtu.be/4zARMcgc7hA?si=x6RoHQXFF4NY76X8 , buat screenshot dengan nama kalian pada coding, kumpulkan dalam bentuk pdf, dari kegiatan ini: <br>
1.	Persiapan Sample Dataset
![image](https://github.com/user-attachments/assets/b940e6d4-86e2-4012-8366-1546c932ac4c) <br>

2.	Visualisasi Dataset <br>
 ![image](https://github.com/user-attachments/assets/8b3e6df5-e4b5-4d71-8dd7-7fcd574ee7a1) <br>

3.	Pengantar classification dengan K-Nearest Neighbours | KNN Algoritma K-Nearest Neighbor (KNN) adalah algoritma machine learning yang bersifat non-parametric dan lazy learning. Metode yang bersifat non-parametric memiliki makna bahwa metode tersebut tidak membuat asumsi apa pun tentang distribusi data yang mendasarinya. Dengan kata lain, tidak ada jumlah parameter atau estimasi parameter yang tetap dalam model, terlepas data tersebut berukuran kecil ataupun besar.
Algoritma non-parametric seperti KNN menggunakan sejumlah parameter yang fleksibel, dan jumlah parameter seringkali bertambah seiring data yang semakin banyak. Algoritma non-parametric secara komputasi lebih lambat, tetapi membuat lebih sedikit asumsi tentang data. Algoritma KNN juga bersifat lazy learning, yang artinya tidak menggunakan titik data training untuk membuat model. Singkatnya pada algoritma KNN tidak ada fase training, kalaupun ada juga sangat minim.

4.	Preprocessing dataset dengan Label Binarizer
  ![image](https://github.com/user-attachments/assets/93a44e85-5e30-4942-99ee-f34bf3f873cd) <br>
  ![image](https://github.com/user-attachments/assets/2840d1b6-4c6c-4287-b2fc-1502f2080ecc) <br>
  ![image](https://github.com/user-attachments/assets/48aab831-854a-4508-abec-e766fd3614e3) <br>

5.	Training KNN Classification Model
   ![image](https://github.com/user-attachments/assets/a0039917-a794-403c-8e85-1db17da0980b) <br>

6.	Prediksi dengan KNN Classification Model
   ![image](https://github.com/user-attachments/assets/799227b3-de54-4c4b-a52b-d917b6744256) <br>
   ![image](https://github.com/user-attachments/assets/6dc76c80-1239-4e58-b434-ab24d1dafe7b) <br>

7.	Visualisasi Nearest Neighbours
   ![image](https://github.com/user-attachments/assets/a394356e-fff8-4877-b01b-b4c3e5f654bc) <br>

8.	Kalkulasi jarak dengan Eulidean Distance
   ![image](https://github.com/user-attachments/assets/ed2b2282-3b87-4d52-bb47-d82159355794) <br>
   ![image](https://github.com/user-attachments/assets/ab616c75-aebf-40d9-991f-ffc0b07ef25a) <br>

9.	Evaluasi KNN Classification Model | Persiapan testing set
    ![image](https://github.com/user-attachments/assets/40448edd-7885-41df-9f1a-2c81ff82a5d0) <br>

10.	Evaluasi model dengan accuracy score
    ![image](https://github.com/user-attachments/assets/7e34c6cd-1809-4ca3-8caf-c23e62e0defe) <br>

11.	Evaluasi model dengan precision score
    ![image](https://github.com/user-attachments/assets/cfed6bff-4520-4f00-9fb1-6632fa285f35) <br>

12.	Evaluasi model dengan recall score
    ![image](https://github.com/user-attachments/assets/ac3963ee-dc38-42d2-af93-61140fe7b89b) <br>

13.	Evaluaasi model dengan F1 score
    ![image](https://github.com/user-attachments/assets/87e6d6b3-8d2e-4c23-b74f-04e81919a489) <br>

14.	Evaluasi model dengan classification report
    ![image](https://github.com/user-attachments/assets/19ffa601-a75f-4a67-ba6b-5fd765a9fc8a) <br>

15.	Evaluasi model dengan Mathews Correlation Coefficient
    ![image](https://github.com/user-attachments/assets/a2d82500-7a23-4a2a-8d26-c65353fffabb)

   
B.	Support Vector Machine (SVM). Lakukan praktik dari https://youtu.be/z69XYXpvVrE?si=KR_hDSlwjGIMcT0w , buat screenshot dengan nama kalian pada coding, kumpulkan dalam bentuk pdf, dari kegiatan ini:
1.	Pengenalan Decision Boundary & Hyperplane
    ![image](https://github.com/user-attachments/assets/a7722780-3c60-4b3e-b5de-1f7e01217434) <br>

Decision boundary adalah garis yang membagi jalan atau margin menjadi 2 bagian yang sama besar. Hyperplane adalah bidang yang memisahkan kedua kelas, sedangkan margin adalah lebar 'jalan' yang membagi kedua kelas.
2.	Pengenalan Support Vector & Maximum Margin
    ![image](https://github.com/user-attachments/assets/08e178d7-90b3-4888-81b9-afe27ffc1d26) <br>
 
Maximum margin adalah model linier yang memisahkan kelas dalam satu set data dengan jarak yang paling jauh dari cangkang cembung kelas. Pemisahan ini juga harus tegak lurus terhadap garis terpendek yang menghubungkan kelas tersebut.
3.	Pengenalan kondisi Linearly Inseparable dan Kernel Tricks
    ![image](https://github.com/user-attachments/assets/5759128a-6edf-4fbe-9fcc-54adef8985da) <br>

Dua set titik data dalam ruang dua dimensi dikatakan dapat dipisahkan secara linear jika keduanya dapat dipisahkan sepenuhnya oleh satu garis lurus . Secara umum, dua kelompok titik data dapat dipisahkan dalam ruang n-dimensi jika keduanya dapat dipisahkan oleh bidang hiper n-1 dimensi. Trik kernel adalah teknik hebat yang memungkinkan SVM memecahkan masalah klasifikasi non-linier dengan memetakan data input secara implisit ke ruang fitur berdimensi lebih tinggi . Dengan demikian, kita dapat menemukan hiperbidang yang memisahkan kelas data yang berbeda.
4.	Pengenalan MNIST Handwritten Digits Dataset
    ![image](https://github.com/user-attachments/assets/39764b67-7913-4062-8356-b31558da0e4c) <br>
    ![image](https://github.com/user-attachments/assets/e8c5e966-bd83-40d1-9b36-7d0a85d925c1) <br>
    ![image](https://github.com/user-attachments/assets/a8f63e6d-d72e-4ba4-ae02-b2fc03d07689) <br>
    ![image](https://github.com/user-attachments/assets/bb9df714-7309-4ca0-b7b5-6eeb56e0e203) <br>

5.	Klasifikasi dengan Support Vector Classifier | SVC
    ![image](https://github.com/user-attachments/assets/c2be1da0-f3a8-4752-b292-3d1aad60be9d) <br>
    ![image](https://github.com/user-attachments/assets/6f35c758-6562-46bc-8f05-50d3e9cae186) <br>

6.	Hyperparameter Tuning dengan Grid Search
    ![image](https://github.com/user-attachments/assets/b556d2cd-5384-4532-a12e-4ffa820f6714) <br>
    ![image](https://github.com/user-attachments/assets/c1dd7788-55ca-41d5-b916-6de337512a24) <br>

7.	Evaluasi Model <br>
    ![image](https://github.com/user-attachments/assets/a3d69563-7743-4b35-bf97-e96dda5aa7ed) <br>

