# Tugas_Pemmob_Elearning5

Dibawah ini merupakan hasil tugas e-elearning ke 5 di mata kuliah Pemograman Mobile 2. Mohon maaf tidak dapat menyertakan hasil screenshotan nya di karenakan ada error yang sulit di betulkan yaitu ndk nya antara error dan belum sepenuhnya terpasang. Sudah saya coba ulik namun masih tetap tidak dapat menampilkan hasil outputnya di device yang telah di sambungkan padahal code yang di gunakan serta file lainnya sudah benar tidak ada error sama sekali. Semoga ibu dapat memakluminya dan memberikan nilai disamping saya maish belajar dan usaha untuk mengikuti tiap materinya. Berikut code main.dart nya:

import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      theme: ThemeData(
        useMaterial3: false,
        fontFamily: 'MomoTrust',
        primarySwatch: Colors.deepOrange,
        scaffoldBackgroundColor: const Color.fromARGB(255, 64, 217, 255),
      ),
      home: Scaffold(
        appBar: AppBar(title: const Text("muti's mine")),
        body: Center(
          child: Column(
            mainAxisAlignment: MainAxisAlignment.center,
            children: [
              const Text(
                'HellowPeeps!',
                style: TextStyle(
                  fontFamily: 'MomoTrust',
                  fontSize: 40,
                  color: Colors.orange,
                ),
              ),
              const SizedBox(height: 20),
              const Text(
                'ini apa ya??',
                style: TextStyle(fontSize: 20, color: Colors.white),
              ),
              ElevatedButton(
                onPressed: () {},
                child: const Text('Click Me'),
              ),
            ],
          ),
        ),

Terima kasih.
      ),
    );
  }
}
