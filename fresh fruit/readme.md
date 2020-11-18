# FruitBucket

Ini adalah program sederhana yang hanya bisa menambakan buah saja ke keranjang.

# Fungisonalitas
- User dapat memilih/menambahkan buah kedalam keranjang
- Maksimal hanya 2 saja, jika lebih tidak bisa dan akan muncul notifikasi penuh

# Cara Kerja
- Konsepnya, Model diletakan pada folder model yang berisi class `Seller.cs`, `Fruit.cs`, `Bucket.cs`, dan `BucketEventListener.cs`
- Konsep View bisa dilihat pada `MainWindow.xaml`
- Controler diletakan pada folder controller yang berisi class `BucketController.cs` agar bisa menyunting fungsionalitasnya

 jika ingin menambah kapasitas keranjangnya, bisa diedit melalui `MainWindow.xaml.cs`