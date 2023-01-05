# praktikum-7_ti21c2Rahmah
RELASI KELAS adalah Class tersebut saling berelasi untuk mendefinisikan bagaimana objek -objek akan berinteraksi satu dengan lainnya. Program atau Source Code :

Komputer.java image
Laptop.java image Source Code ini tidak bisa di Run & Compile karena ini membutuhkan kelas antara lainnya, dependensi, association, agregation, composition. Di gabungkan dalam file2 tersebut lalu di run & compile.
A. Dependensi

Dependency merupakan relasi antar kelas dimana satu kelas membutuhkan atau tergantung kepada kelas lainnya. Tapi ketergantungan tersebut tidak timbal balik.
Relasi dependency ini digambarkan dengan panah yang dari satu kelas ke kelas lainnya.
Arah panah dari diagram class menunjukkan kelas yang dibutuhkan. Programnya (dari Relasi Kelas + Source Code dibawah) :
MainProgram.java image
Manusia.java image Hasil Compile & Run Programnya : image Gambar Diagram Class-nya : image
B. Association

Asosiasi didefinisikan sebagai hubungan yang terstruktur, yang secara konsep memiliki arti bahwa dua komponen saling terhubung satu sama lain.
Asosiasi biasa disebut menggunakan (uses).
hubungan “use-a” yang menyatakan bahwa sebuah kelas menggunakan kelas lainnya. Programnya (dari Relasi Kelas + Source Code dibawah ini) :
MainProgram
image
Manusia.java
image Hasil Compile & Run Programnya : image Gambar Diagramn Class-nya : image
C. Agregation

Hubungan agregasi serupa dengan asosiasi, yaitu memiliki sebuah atribut dengan tipe dari class lain.
Namun hubungan diperkuat dengan adanya dependensi pada konstruktornya.
hubungan “has-a” yang menyatakan bahwa sebuah kelas memiliki hubungan dengan kelas lainnya.' Programnya (dari Relasi Kelas+ Source Code dibawah ini) :
MainProgram.java image
Manusia.java image Hasil Run & Compile Programnya : image Gambar Diagram Class-nya : image
D. Composition

Composition merupakan relasi yang lebih spesifik dari relasi aggregation.
Pada relasi ini suatu kelas tidak hanya dimiliki oleh kelas lainnya, tapi juga siklus hidup kelas tersebut juga ditentukan oleh kelas yang memilikinya.
Pada relasi ini biasanya objek dari kelas yang dimiliki diciptakan di dalam kelas yang memilikinya.
Komposisi biasa disebut pasti memiliki (own) Programnya (dari Relasi Kelas + Source Code dibawah ini) :
MainProgram : image
Manusia.java : image Hasil Run & Compile Programnya : image Gambar Diagram Class-nya : image
