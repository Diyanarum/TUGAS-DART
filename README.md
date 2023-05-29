# ULANGAN TENGAH SEMESTER
### NAMA  : DIYAN ARUM MAHESWARI
### KELAS : TI. 20. A. 1
### NIM   : 312010133
_____________________________________________________________________________________________________________________



### **Buatlah seperti tampilan dibawah ini**

![menambahkan_gambar](img/soal.png)

### **Berikut Source Code Yang Digunakan**

```
import 'dart:io';
/*
NAMA  : DIYAN ARUM MAHESWARI
NIM   : 312010133
Kelas : TI.20.A1
*/

// Fungsi angka pilihan user
void result(var nama, int angka) {
  var oddeven = (angka % 2 == 0) ? 'Genap' : 'Ganjil';

  print("-----Hasil-----");
  for (int i = 1; i <= angka; i++) {
    //GENAP
    if (oddeven == "Genap" && i % 2 == 0) {
      print(nama);
      print(i);
    }
    //GANJIL
    if (oddeven == "Ganjil") {
      print(nama);
      print(i);
    }
  }
}

void main() {
  // Input nama
  stdout.write("Masukkan nama: ");
  var nama = stdin.readLineSync();
  // Input angka
  stdout.write("Masukkan angka: ");
  int? angka = int.parse(stdin.readLineSync()!);

  // Panggil fungsi
  result(nama,angka);
}
```


### **Jawaban Atau Hasil**

![menambahkan_gambar](img/hasil.png)



  ###   === THANKS FOR YOUR ATTENTION!!! ===
  ### == DIYAN ARUM MAHESWARI - 312010133 ==