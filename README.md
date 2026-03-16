## Nama : Adelia Rahmatus Sa'dia
## NRP : 5025231054
## Kelas : PPB E


## WIGNET
Pada kode di aplikasi ini terdapat beberapa wignet, seperti :
## 1. MaterialApp
MaterialApp merupakan root wignet pada aplikasi ini yang digunakan untuk mengatur konfigurasi utama pada aplikasi, seperti : tema, judul, dan halaman awal.
      
      MaterialApp(
        title: 'Flutter Demo',
        theme: ThemeData(
          colorScheme: ColorScheme.fromSeed(seedColor: Colors.deepPurple),
          useMaterial3: true,
        ),
        home: const RowColumnPage(),
      );
## 2. Scaffold
Scaffold digunakan sebagai kerangka dasar pada halaman aplikasi yang menyediakan struktur layout, seperti : AppBar, Body, FloatingActionButton, dan komponen lainnya.

      Scaffold(
        appBar: AppBar(
          title: const Text(
            'My First App',
            style: TextStyle(color: Colors.black),
          ),
          backgroundColor: Colors.orange[200],
          centerTitle: true,
        ),
        body: Column(
          children: <Widget>[
            ...
          ],
        ),
      );
