# Week 1 Introduction to Database (DB)

#### 📍 Definition and Purpose of Database (DB)
- _Poin-poin Utama_
	- Mengurangi data redundancy and inconsistency
	- Mempermudah akses data untuk program baru
	- Mengurang isolasi data dengan banyak jenis file & format yang berbeda
	- Menjaga integritas dan constraint data
- _Contoh/Use-Case_
	- Menggunakan database system yang dapat diakses dari berbagai aplikasi
- _Catatan Tambahan_
	- Saat database system belum diadopsi secara luas sebuah program memiliki menyimpan data dengan file system dari masing-masing aplikasi yang menyebabkan isolasi data dan kerumitan untuk membaca data dari satu aplikasi ke yang lain nya
#### 📍 View of Data
- _Poin-poin Utama_
	- Data Models
		Merupakan framework dari sebuah database yang menentukan struktur orginisasi dan flow of data dalam sebuah database system
	- Data Abstraction
		Digunakan untuk mengurangi kompleksitas dari sebuah data structures untuk merepresentasikan data dari database melalui beberapa level dari data abstraction
		- Physical Level
			Mendeskripsi bagaimana suatu record di simpan
		- Logical Level
			Mendeskripsi data apa yang di simpan disuatu database dan relationship antar data
		- View Level
			Level teratas dimana kita dapat memanipulasi dan menyembunyikan suatu data tergantung kebutuhan akses dari suatu user
- _Contoh/Use-Case_
	- Menampilkan view yang berbeda untuk level user-user yang berbeda dimana Admin dapat membaca,mengedit, dan mengakses semua data sedangkan level user dibawah admin hanya diberikan akses sesuai kebutuhan
- _Catatan Tambahan_
#### 📍 DB Languages
- _Poin-poin Utama_
	- DML Data Manimpulation Language adalah bahasa yang digunakan untuk mengupdate data
		- Procedural DML
			Mengharuskan user untuk menspecify data apa saja yang diperlukan & bagaimana cara menggambil data tersebut
		- Declarative DML
			- Mengharuskan user untuk menspecify data apa saja yang diperlukan tanpa cara menggambil data tersebut
			- Juga dinamakan sebagai non-procedural DMLs
		- Porsi DML yang mengatur information retrival juga dipanggil sebagai query language
- _Contoh/Use-Case_
	- SQL sebagai query language non procedural. Dapat menerima tables sebagai input dan menggembalikan hasil dalam bentuk single table
- _Catatan Tambahan_
	- Limitasi SQL
		- Tidak bisa menggunakan dynamic input dari user
		- Tidak bisa mendikte hasil akhir yang di display ke end user
		- Tidak bias menghandle pekerjaan networking
	- Solusi
		- Pengguna Dynamic SQL / Query Parameter digunakan agar dapat mengenerate query sesuai user input
#### 📍 DB Design
- _Poin-poin Utama_
	- Logical Design
		Design Skema Database
		- Entity
		- Relationship
		- Attribute
	- Physical Design
		Layout Fisik Dari Sebuah Database
		- Tables and Indexes
		- Storage
		- Security
- _Contoh/Use-Case_
	- Menentukan Logical Design dengan membuat Skema Database terlebih dahulu sebelum membuat layout fisik dari sebuah database
- _Catatan Tambahan_
- 