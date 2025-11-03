# Tugas_Pemmob_Elearning5
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
      ),
    );
  }
}
