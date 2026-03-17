## Nama : Adelia Rahmatus Sa'dia
## NRP : 5025231054
## Kelas : PPB E


------

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

## 3. AppBar
Appbar digunakan untuk membuat header pada bagian atas aplikasi biasanya berisi judul halaman.

      AppBar(
        title: const Text(
          'My First App',
          style: TextStyle(color: Colors.black),
        ),
        backgroundColor: Colors.orange[200],
        centerTitle: true,
      )

## 4. Column
Colum digunakan untuk menyusun wignet secara vertikal (dari atas ke bawah).

      Column(
        crossAxisAlignment: CrossAxisAlignment.center,
        mainAxisAlignment: MainAxisAlignment.center,
        children: <Widget>[
          ...
        ],
      )

## 5. Row
Row digunakan untuk menyusun wignet secara horizontal (dari kiri ke kanan)

      Row(
        mainAxisAlignment: MainAxisAlignment.spaceEvenly,
        crossAxisAlignment: CrossAxisAlignment.start,
        children: <Widget>[
          Column(children: [Icon(Icons.food_bank), Text("Food")]),
          Column(children: [Icon(Icons.landscape), Text("Scenery")]),
          Column(children: [Icon(Icons.people), Text("People")]),
        ],
      )

## 6. Container
Container digunakan untuk mengatur layout dan tampilan suatu komponen, seperti : ukuran, warna, margin dan padding.

      Container(
        width: MediaQuery.of(context).size.width,
        margin: EdgeInsets.fromLTRB(20.0, 5.0, 20.0, 10.0),
        padding: EdgeInsets.all(20.0),
        color: Colors.lightBlue[100],
      )

## 7. Padding
Padding digunakan untuk memberikan jarak antara isi wignet dengan batas wignet tersebut.

      padding: EdgeInsets.all(20.0) - kode ini digunakan di dalam container.

## 8. Center
Center digunakan untuk menempatkan wignet tepat di tengah area yang tersedia.

      Center(
        child: Image.network(
          'https://picsum.photos/200',
          fit: BoxFit.cover,
          width: 500,
        ),
      )

## 9. Image
Image.network digunakan untuk menampilkan gambar dengan menggunakan URL.

      Center(
        child: Image.network(
          'https://picsum.photos/200',
          fit: BoxFit.cover,
          width: 500,
        ),
      )

## 10. Icon
icon digunakan untuk menampilkan ikon dari library Material icons yang tersedia.

      Icon(Icons.food_bank)
      Icon(Icons.landscape)
      Icon(Icons.people)

## 11. Button
Button ini salah satu dari icon yang berupa tombol yang dapat ditakan pengguna.

      IconButton(
        onPressed: _incrementCounter,
        icon: Icon(Icons.add, color: Colors.black, size: 16),
      )

## 12. Text
Text digunakan untuk menampilkan teks pada layar.

      Text(
        'What image is that',
        style: TextStyle(fontSize: 16),
      )

