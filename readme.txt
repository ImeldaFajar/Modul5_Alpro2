Penjelasan Unguided 1

Fungsi Fibonacci Fungsi ini menerima parameter n yang merupakan indeks suku Fibonacci
yang ingin dihitung. Jika n kurang dari atau sama dengan 1, fungsi mengembalikan n itu 
sendiri (0 atau 1). Jika tidak, fungsi memanggil dirinya sendiri untuk menghitung dua suku 
sebelumnya dan menjumlahkannya.

Penjelasan Unguided 2

Fungsi cetakbintang Fungsi ini menerima satu parameter n yang merupakan bilangan bulat.
Jika n kurang dari atau sama dengan 0, fungsi akan berhenti (return).
Fungsi memanggil dirinya sendiri dengan n - 1, sehingga menciptakan efek rekursif. 
Setelah panggilan rekursif, loop for digunakan untuk mencetak bintang sebanyak n kali, 
diikuti dengan fmt.Println() untuk pindah ke baris berikutnya.

Penjelasan Unguided 3

Fungsi findFactors Fungsi ini menerima dua parameter: N (bilangan bulat positif) dan
divisor (bilangan yang digunakan untuk mencari faktor). Jika divisor lebih besar dari N,
fungsi akan berhenti (base case). Jika N dapat dibagi oleh divisor tanpa sisa 
(N%divisor == 0), maka divisor dicetak sebagai faktor. 
Fungsi kemudian memanggil dirinya sendiri dengan divisor yang ditingkatkan satu untuk 
mencari faktor berikutnya.

Penjelasan Unguided 4

Fungsi printSeries Parameter N adalah bilangan bulat positif yang dimasukkan oleh pengguna.
Parameter current adalah bilangan yang sedang diproses. Jika current sama dengan 1, 
fungsi mencetak 1 dan mengembalikan kontrol. Jika tidak, fungsi mencetak current, 
memanggil dirinya sendiri dengan current-1, dan kemudian mencetak current lagi setelah 
pemanggilan rekursif.

Penjelasan Unguided 5

Fungsi printOddNumbers Fungsi ini menerima dua parameter: N (batas atas) dan current 
(bilangan saat ini yang sedang diperiksa). Jika current lebih besar dari N, fungsi akan berhenti (base case). 
Jika current adalah bilangan ganjil (diperiksa dengan current%2 != 0), maka bilangan tersebut dicetak. 
Fungsi kemudian memanggil dirinya sendiri dengan current+1 untuk memeriksa bilangan berikutnya.

Penjelasan Unguided 6

Fungsi pangkat Memeriksa nilai y. Jika y sama dengan 0, maka hasilnya adalah 1 (karena setiap bilangan pangkat 0 adalah 1). 
Jika y sama dengan 1, maka hasilnya adalah x. Jika y lebih besar dari 1, fungsi memanggil dirinya sendiri dengan y dikurangi 1, 
dan mengalikan hasilnya dengan x.