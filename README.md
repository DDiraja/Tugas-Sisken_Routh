# Tugas-Sisken_Routh

Program ini merupakan program Python yang digunakan untuk menghitung kestabilan sistem menggunakan kriteria Routh-Hurwitz. Program ini memiliki beberapa fungsi dan prosedur, yaitu:
1.	Fungsi K_value(Kvalue,polynomial) digunakan untuk menghitung nilai koefisien polinomial dengan mengganti nilai variabel K pada polinomial dengan nilai K yang diinputkan oleh pengguna. Fungsi ini juga menentukan kestabilan sistem berdasarkan koefisien yang dihasilkan dari penggantian nilai K. Jika semua koefisien positif, maka sistem dianggap stabil, sedangkan jika ada koefisien negatif, maka sistem dianggap tidak stabil.
2.	Prosedur input_Polynomial(polynomial) digunakan untuk menginputkan polinomial dari pengguna dengan orde tertentu. Pengguna diminta untuk menginputkan koefisien polinomial secara berurutan, dari yang tertinggi hingga konstanta.
3.	Fungsi get_Routh_Array(RouthArray) digunakan untuk menampilkan tabel Routh berdasarkan array yang dihasilkan oleh fungsi RouthHurwitz(polynomial).
4.	Fungsi get_Expr(raw_expr) digunakan untuk mengubah string ekspresi menjadi objek ekspresi SymPy.
5.	Fungsi exprArrToStrArr(expr_arr) digunakan untuk mengubah array ekspresi SymPy menjadi array string.
6.	Fungsi determinant(r1c1, r1c2, r2c1, r2c2) digunakan untuk menghitung determinan matriks 2x2 dengan elemen yang diinputkan.
7.	Fungsi ToLaTeX(str_arr) digunakan untuk mengubah array string menjadi array string yang sudah diformat dalam format LaTeX.
8.	Fungsi RouthHurwitz(polynomial) digunakan untuk menghitung array Routh berdasarkan polinomial yang diinputkan.
Pada bagian akhir program, terdapat pemanggilan prosedur dan fungsi untuk menginputkan polinomial, menampilkan tabel Routh, menginputkan nilai K dari pengguna, dan menghitung kestabilan sistem berdasarkan nilai K yang diinputkan.
