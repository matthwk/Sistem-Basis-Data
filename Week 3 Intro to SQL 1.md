# Week 3 Intro to SQL 1
#### Relation Schema & Instance
- _Main Points_
	- Relation schema terdiri dari attributes (kolom) dari sebuah tabel
	- Relation instance adalah sebuah snapshot dari suatu relation schema
- _Use-Case_
	- Menggunakan relation schema untuk kolom instructor yang berisikan (ID,name,dept_name,salary)
- _Extra Notes_
#### Database Schema
- _Main Points_
	- DB Schema struktur logis dari suatu database
	- DB instance adalah sebuah snapshot dari suatu database
- _Use-Case_
	- DB schema untuk database instructor (ID,name,dept_name,salary) 
- _Extra Notes_
#### Super Key (SK)
- _Main Points_
	- Key yang terdiri dari 1 atau lebih atribut yang dapat digunakan untuk mengindentifikasi row secara unik
- _Use-Case_
	- (ID) atau (ID,name) adalah Superkey karena keduanya bisa digunakan untuk mengindentifikasi row karena semua row memiliki value yang unik untuk atribut tersebut
- _Extra Notes_
#### Candidate Key (CK)
- _Main Points_
	- Superkey yang hanya terdiri dari 1 atribut dimana dengan 1 atribut tersebut kita tetap bisa mengidentifikasi suatu row secara unik
- _Use-Case_
	- (ID) adalah Candidate Key karena sudah cukup untuk mengidentifikasi suatu row secara unik
- _Extra Notes_
#### Primary Key (PK)
- _Main Points_
	- Dari beberap Candidate Key yang bisa digunakan 1 akan dipilih sebagai Primary Key yang tidak boleh berisikan null dan jarang berubah
- _Use-Case_
	- (ID) adalah Primary Key karena satu-satunya Candidate Key yang ada
- _Extra Notes_
#### Foreign Key (FK)
- _Main Points_
	- Foreign Key adalah Primary Key dari tabel lain yang digunakan untuk mereferensikan suatu row yang unik di tabel tersebut
	- Relasi yang menggunakan Foreign Key disebut referencing relation. Relasi teresebut di refer oleh Foreign Key
- _Use-Case_
	- dept_name di tabel instructor adalah relasi Foreign Key yang mereferensi tabel department. Yang artinya semua nama department di tabel instructor harus ada di tabel department. Ini memastikan bahwa relasi tersebut memiliki referential integrity
- _Extra Notes_