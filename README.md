# Latihan Praktikum 12 DPBO 2023 C1

## Janji
Saya Azzahra Siti Hadjar 2100901 mengerjakan Latihan Praktikum 12 dalam mata kuliah Desain Pemrograman Beriorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Alasan memilih MVVM
Saya memilih MVVM karena lebih mudah digunakan daripada MVP. Dalam MVVM, perubahan pada model secara otomatis diteruskan ke view melalui viewmodel. Ini memungkinkan tampilan untuk berjalan dengan mandiri tanpa bergantung pada model yang spesifik. Selain itu, MVVM memisahkan tampilan dari model, sehingga memudahkan pengujian dan membuat tampilan menjadi lebih independen. ViewModel berfungsi sebagai penghubung antara tampilan dan logika bisnis.

Sebagai contoh, dalam file Display, tampilan dapat berjalan dengan baik bahkan jika tidak ada model yang dibuat. Tampilan ini mereferensi ke viewModel, yang dalam contoh ini adalah file Game. Dengan menggunakan MVVM, Display dapat menampilkan tampilan dari Game dengan mudah dan terpisah dari kompleksitas logika bisnis di baliknya.

## Perbedaan dengan TMD
Pada TMD saya menggunakan struktur MVVM juga, untuk penempatan file pada setiap package (Model/View/ViewModel) nya hampir sama antara program TMD (Keep Standing) saya dengan program LP12 (Synchronization) seperti menyimpan file game dan handler pada Viewmodel, file display dan menu pada View, serta file gameObject dan player pada Model
