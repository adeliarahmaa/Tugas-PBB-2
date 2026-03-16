## Nama : Adelia Rahmatus Sa'dia
## NRP : 5025231054
## Kelas : PPB E


## WIGNET
Pada kode di aplikasi ini terdapat beberapa wignet, seperti :
## 1 MaterialApp
MaterialApp merupakan root wignet pada aplikasi ini yang digunakan untuk mengatur konfigurasi utama pada aplikasi, seperti : tema, judul, dan halaman awal.
      
      MaterialApp(
  title: 'Flutter Demo',
  theme: ThemeData(
    colorScheme: ColorScheme.fromSeed(seedColor: Colors.deepPurple),
    useMaterial3: true,
  ),
  home: const RowColumnPage(),
);
