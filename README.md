# Latihan21
**NAMA : SARDIN** <br>

**NIM : 312010135** <br>

**KELAS : TI.20.A.1** <br>

## Langkah-langkah penggunaan git

* Download Git terlebih dahulu, dengan link berikut ini : [click here](https://git-scm.com) <br>

![GitScm](ss/gitscm.png)

* Setelah file terdownload, silahkan lakukan instalasi dengan referensi berikut ini :[ Git Installation Guide](https://https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) <br>

![installing](ss/installing.png)

* Setelah installasi selesai, buka *software* **GitBash** pada menu di Windows, dan lakukan pengecekan **versi**, dengan mengetik syntax berikut : <br>

`git --version`

![version](ss/version.jpg)

* Jika muncul tampilan **git version**, berarti Git sudah **berhasil di install** dan **bisa digunakan**. Langkah pertama kita harus **mengkonfigurasi user nama** dan **email** di **Git**, dengan mengetikkan syntax berikut : <br>

`git config --global user.name "masukan nama anda"` <br>
`git config --global user.email "masukan email anda"` <br>

![gitconfig](ss/gituser.jpg)

* Setelah diisi, silahkan lakukan pengecekan user nama dan email, dengan mengetikkan perintah berikut : <br>

`git config --global user.name` <br>
`git config --global user.email` <br>

![gitconfig1](ss/username.jpg)

* Buat akun di**GitHub**,seperti contoh dibawah ini.Dan lakukan Verifikasi akun melalui email yang sudah terdaftar <br>

* Jika akun **GitHub** sudah selesai dibuat dan di verifikasi,proses selanjutnya silahkan buat Repository seperti gambar dibawah ini: **Penjelasan** <br>

> * `Repository Name : (Silahkan isi nama repository yang diinginkan, seperti contoh saya ingin membuat repository LatihanVCS)` <br>
> * `Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)` <br>
> * `Public / Private : (PIlih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)` <br>
> * `Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda` <br>
> * `Add .gitignore : Merupakan sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.` <br>
> * `Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat Kemudian tekan tombol Create Repository untuk menyimpan` <br>

![hasil repositori yang di buat](ss/namaR.jpg)

* Jika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini :

![repositori](ss/hasilR.jpg)

* Pembuatan akun dan repository pada Github telah selesai, saat ini akan kita lakukan untuk *me-remote* repository Github pada GitBash Lokal. Bagaimana caranya? Langkah pertama kita harus menyalin link *URL git* kita di Github, dengan cara tekan tombol **Code** lalu klik *Copy*.

![code link repositori](ss/latihan.jpg)

* Setelah *Link URL* git kita *copy*, Silahkan buka File Explorer pada Windows, kemudian pilih folder dimana kita akan *mendownload* Repository dari Github ke lokal. Kemudian Klik Kanan, Pilih **Git Bash Here**.

![click git bash here](ss/GitBash.png)

* *Pop Up* Command Prompt **(CMD)** akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan *syntax* berikut :

`git clone [URL] pada contoh akan saya masukan di git clone` <br>

https://github.com/sardin311002/Latihan21.git <br>

![git clone](ss/gitclone.jpg)

* Setelah proses cloning selesai, pada saat ini kita masih pada folder awal (master), kita harus masuk kedalam folder yang telah dicloning tadi yaitu *LatihanVCS* dengan mengetikkan *syntax* berikut :

`cd Latihan21/` <br>

![cd](ss/cd.jpg)

* Saat ini kita sudah masuk kedalam folder *LatihanVCS*, Silahkan edit file README.md yang ada di File Explorer. Bisa menggunakan Text Editor *(Sublime Text, Notepad, Notepad*++, *Visual Studio Code)*. Edit sesuai dengan keinginan. Aturan file .md (Markdown) bisa dilihat di Link berikut ini : [click here](https://guides.github.com/features/mastering-markdown/) <br>


![mulai](ss/mulai.jpg)

* Setelah file README.md diedit, silahkan Simpan file tersebut dengan cara **CTRL+S** atau **File -> Save** <br>

* Langkah selanjutnya setelah file disimpan, kita kembali pada App Git Bash **(CMD)**. Ketik pada Git Bash seperti berikut ini : <br>

`git add`

![gitadd](ss/gitadd.jpg)

* Setelah selesai melakukan *git add* . langkah berikutnya kita akan melakukan *commit.* Fungsi commit adalah untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository. Ketik pada App Git Bash seperti berikut ini : <br>


`git commit "Update README.md"`

![commit](ss/commit.jpg)

* Git commit telah selesai di lakukan. Untuk saat ini akan melakuka Git Push, Git Push berfungsi untuk mengirimkan perubahan file setelah di commit ke remote repository. Silahkan ketik pada App Git Bash seperti berikut :

`git push`

![push](ss/push.jpg)

* Semua proses telah selesai, silahkan kembali ke Web Browser untuk melihat perubahan yang telah di *commit* dan *push* dari remote.



