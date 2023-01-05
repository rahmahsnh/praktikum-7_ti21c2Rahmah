# praktikum-7_ti21c2Rahmah
RELASI KELAS adalah Class tersebut saling berelasi untuk mendefinisikan bagaimana objek -objek akan berinteraksi satu dengan lainnya. Program atau Source Code :

Komputer.java ![image](https://user-images.githubusercontent.com/116366904/210826534-6b440287-4f49-4d3a-9cb8-695d8bc31beb.png)

Laptop.java ![image](https://user-images.githubusercontent.com/116366904/210826833-4fc3ab10-992f-4b94-9fa1-cb00a8cfc1d5.png)
 Source Code ini tidak bisa di Run & Compile karena ini membutuhkan kelas antara lainnya, dependensi, association, agregation, composition. Di gabungkan dalam file2 tersebut lalu di run & compile.
A. Dependensi

Dependency merupakan relasi antar kelas dimana satu kelas membutuhkan atau tergantung kepada kelas lainnya. Tapi ketergantungan tersebut tidak timbal balik.
Relasi dependency ini digambarkan dengan panah yang dari satu kelas ke kelas lainnya.
Arah panah dari diagram class menunjukkan kelas yang dibutuhkan. Programnya (dari Relasi Kelas + Source Code dibawah) :
MainProgram.java ![image](https://user-images.githubusercontent.com/116366904/210826949-6feafe51-1f32-4cd2-aec7-e64de4c02789.png)

Manusia.java ![image](https://user-images.githubusercontent.com/116366904/210827192-11d8f79c-f892-47bc-ae78-bdd348abbb9d.png)
 Hasil Compile & Run Programnya : ![image](https://user-images.githubusercontent.com/116366904/210827307-0fcefa66-60a5-4b1e-9ffe-58f1e4b8f622.png)
 Gambar Diagram Class-nya : ![image](https://user-images.githubusercontent.com/116366904/210827644-fb78bd68-a1cd-4c41-869b-b09809c32bc5.png)

B. Association

Asosiasi didefinisikan sebagai hubungan yang terstruktur, yang secara konsep memiliki arti bahwa dua komponen saling terhubung satu sama lain.
Asosiasi biasa disebut menggunakan (uses).
hubungan “use-a” yang menyatakan bahwa sebuah kelas menggunakan kelas lainnya. Programnya (dari Relasi Kelas + Source Code dibawah ini) :
MainProgram ![image](https://user-images.githubusercontent.com/116366904/210827753-1b238fd7-065b-4403-a431-b6c8d70a811e.png)

Manusia.java ![image](https://user-images.githubusercontent.com/116366904/210827824-750f215b-055a-4db1-a757-bdbbc7c10c8e.png)
 Hasil Compile & Run Programnya : ![image](https://user-images.githubusercontent.com/116366904/210827901-2f2e4e54-c2a7-41ea-9831-647d12a8dc69.png)
 Gambar Diagramn Class-nya : ![image](https://user-images.githubusercontent.com/116366904/210827977-91aeb842-0669-4385-a535-8e226b166dd2.png)

C. Agregation

Hubungan agregasi serupa dengan asosiasi, yaitu memiliki sebuah atribut dengan tipe dari class lain.
Namun hubungan diperkuat dengan adanya dependensi pada konstruktornya.
hubungan “has-a” yang menyatakan bahwa sebuah kelas memiliki hubungan dengan kelas lainnya.' Programnya (dari Relasi Kelas+ Source Code dibawah ini) :
MainProgram.java ![image](https://user-images.githubusercontent.com/116366904/210828050-97090625-fd2d-4551-9f2f-56b3ea813fc8.png)

Manusia.java ![image](https://user-images.githubusercontent.com/116366904/210828111-bfcd273d-e591-4b2b-aac0-1f08866d3304.png)
 Hasil Run & Compile Programnya : ![image](https://user-images.githubusercontent.com/116366904/210828163-d1d67222-04e3-49c7-821a-3951dcfbb4e2.png)
 Gambar Diagram Class-nya : ![image](https://user-images.githubusercontent.com/116366904/210828214-5172c0c6-f1ac-45a3-8f40-b3d82817fa17.png)

D. Composition

Composition merupakan relasi yang lebih spesifik dari relasi aggregation.
Pada relasi ini suatu kelas tidak hanya dimiliki oleh kelas lainnya, tapi juga siklus hidup kelas tersebut juga ditentukan oleh kelas yang memilikinya.
Pada relasi ini biasanya objek dari kelas yang dimiliki diciptakan di dalam kelas yang memilikinya.
Komposisi biasa disebut pasti memiliki (own) Programnya (dari Relasi Kelas + Source Code dibawah ini) :
MainProgram : ![image](https://user-images.githubusercontent.com/116366904/210828287-00c762f9-ab07-46fd-8ee6-1b35ecdde192.png)

Manusia.java : ![image](https://user-images.githubusercontent.com/116366904/210828351-8316ee8b-b3a3-4251-9bf9-e9c9f297f7b9.png)
 Hasil Run & Compile Programnya : ![image](https://user-images.githubusercontent.com/116366904/210828412-498fb970-3434-4b8d-ae1c-14401f199a6f.png)
 Gambar Diagram Class-nya : ![image](https://user-images.githubusercontent.com/116366904/210828460-fb2c2674-1ab7-4d76-962f-c6715cd19a58.png)

