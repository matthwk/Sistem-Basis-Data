# Week 2 Introduction to The Relational Model
#### Select
- _Main Points_
	- Untuk menyeleksi subset dari tuple yang berisi baris dari suatu tabel berdasarkan kondisi yang diberikan
- _Use-Case_
	- Menyeleksi semua baris dimana dept_name = "Physics" dari tabel course
	- Menyeleksi semua baris dimana dept_name = "Physics" & Credits Lebih Besar Dari 3 Credits dari tabel Course
- _Extra Notes_
#### Project
- _Main Points_
	- Untuk memproyeksi atau menamplikan atribut spesifik (kolom) dari suatu tabel
- _Use-Case_
	- Jika hanya ingin menampilkan kolom title & credits dari tabel course
	- Jika hanya ingin menampilkan kolom title dari hasil seleksi baris dimana kolom dept_name = "Physics" dari tabel course
- _Extra Notes_
#### C. Prod
- _Main Points_
	- Untuk menghasilkan tabel yang menampilkan semua kombinasi dari 2 tabel
- _Use-Case_
	- Jika ingin menampilkan semua nama course yang ditawarkan dari masing-masing department   
- _Extra Notes_
#### Union
- _Main Points_
	- Mengambukan 2 set tuple yang berbeda menjadi 1 tabel tanpa menginclude hasil duplikat dari 2 set tersebut jika ada. 2 Set yang digabungkan harus mempunyai attribut (kolom) yang sama.
- _Use-Case_
	- Jika ingin mengabungkan list course_id dari tabel course dimana dept_name = "Biology" & credits = 4 dengan list course_id dari tabel course dimana dept_name = "Comp.Sc" & credits = 4  
- _Extra Notes_
#### Set Diff.
- _Main Points_
	- Menampilkan hasil yang ada di relasi pertama namun tidak ada di relasi kedua
- _Use-Case_
	- Jika ingin menampilkan list course_id dari tabel section dimana semester = "Fall" & Year=2017 tetapi tidak ada di list dimana semester = "Spring" & year = 2018
- _Extra Notes_
#### Rename
- _Main Points_
	- Memberi nama baru kepada satu relasi atau atribut
- _Use-Case_
	- Menggunakan alias agar isi tabel lebih gampang di mengerti
- _Extra Notes_