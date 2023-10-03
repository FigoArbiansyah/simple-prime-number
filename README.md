# Simple Prime Number
Aplikasi pengecekan sebuah angka, apakah angka tersebut adalah bilangan prima atau bukan

### Flowchart
[Start]
 |
 V
Input angka (num)
 |
 V
Jika num < 2, maka
 |  |
 |  V
 |  Tampilkan "Bukan bilangan prima"
 |  |
 |  V
 |  [End]
 |
 V
Inisialisasi variabel i = 2
 |
 V
Selama i <= num/2, lakukan
 |  |
 |  V
 |  Jika num % i = 0, maka
 |  |  |
 |  |  V
 |  |  Tampilkan "Bukan bilangan prima"
 |  |  |
 |  |  V
 |  |  [End]
 |  |
 |  V
 |  Tingkatkan i dengan 1
 |  |
 |  V
 |
 V
Tampilkan "Bilangan prima"
 |
 V
[End]
