Panduan Aplikasi:
1. file __init__.py
    pada file ini tidak diisikan apapun, file ini hanya berfungsi sebagai modul python
2. folder books yang berisi file book.py yang 
    file tersebut berfungsi sebagai modul yang berisi kelas book dan memiliki beberapa atribut
3. folder data yang berisi file books.json
    file tersebut berfungsi sebagai database
4. Folder test yang berisi file test_book.py
    file tersebut berfungsi sebagai testing dari modul dan database yang sudah dibuat
5. file main.py
    ini merupakan file inti dari aplikasi ini, dimana file ini menjalankan program atau aplikasi berdasarkan file book.py, books.json dan test_book.py
    ketika file ini dijalankan maka akan keluar beberapa menu, yaitu:
        1. Program untuk menambahkan data buku
            Ketika ingin menambahkan data buku maka yang perlu dimasukan adalah nama buku, pengarang buku, dan tahun terbit buku
        2. Program untuk mencari buku
            Ketika ingin mencari buku maka yang harus dimasukan adalah nama judul buku dan harus akurat, karena uppercase dan lowercase sangat sensitif
        3. Program untuk menampilkan daftar buku
            menu ini akan menampilkan daftar buku yang ada di dalam database
        4. Keluar dari menu atau program
            Ketika memilih menu ini jika belum memilih menu apapun maka yang terjadi adalah keluar dari aplikasi