# Aplikasi Quick (Real) Count Desa

Aplikasi web yang bertujuan untuk mempermudah publikasi hasil
Pemilihan Umum secara Realtime dan dapat diakses dengan mudah melalui smartphone.

Aplikasi ini telah digunakan pada Pemilihan Kepala Desa Klampok - Banjarnegara tahun 2019,
dengan kerjasama yang baik dengan tim saksi salah satu calon yang berperan sebagai `voter`
atau penginput data, Aplikasi ini telah berhasil menampilkan data secara realtime dan akurat
sesuai dengan hasil penghitungan manual oleh Panitia.

## Informasi Folder

**client/**

Berisi Git sub-module *source code* dari aplikasi web untuk client side (browser). 

**server/**

Berisi Git sub-module *source code* dari aplikasi web untuk server side (nodejs). 

**.vscode/**

Konfigurasi Editor (Visual Studio Code)


## Untuk Pengembang / Programmer

Jika kamu ingin mengembangkan aplikasi ini, saya sarankan menggunakan OS Linux. Kenapa? Karena Windows itu untuk end-user (kantoran) dan Mac untuk desain grafis.

Projek ini dibuat menggunakan NodeJS jadi saya harap kamu sudah familiar dengan JavaScript. Jika belum familiar, silahkan install projek yang sudah dibuild.

Berikut adalah informasi mengenai apa yang diperlukan untuk mengedit kode script.

**Software:**
- NodeJS - Javascript interpreter ([Download](https://nodejs.org/en/download/))
- Yarn - NodeJS Package Manager ([Download](https://yarnpkg.com/lang/en/docs/install/#windows-stable))
- Visual Studio Code - Editor ([Download](https://code.visualstudio.com/))
- GIT ([Download](https://git-scm.com/downloads))

**Clone Repo (Download Source Code)**
``` bash
# Download source
git clone git@github.com:ndunks/qcdesa.git
# Update sub-module
git submodule init
git submodule update
# masuk ke folder projek
cd qcdesa
# Install depencies
yarn
```
**Jalankan Server**
```
cd server
yarn serve
```
**Jalankan Client**
```
cd client
yarn serve
```

Buka browser pada alamat `http://localhost:8080/ `

**Build Server**
```
cd server
yarn build
```
**Build Client**
```
cd client
yarn build
```


## Screenshot

### Halaman Pengunjung / Pemantau
![Screenshot Visitor 1](https://raw.githubusercontent.com/ndunks/qcdesa-client-pwa/master/docs/img/screenshot-visitor-1.png)
![Screenshot Visitor 2](https://raw.githubusercontent.com/ndunks/qcdesa-client-pwa/master/docs/img/screenshot-visitor-2.png)
![Screenshot Visitor 3](https://raw.githubusercontent.com/ndunks/qcdesa-client-pwa/master/docs/img/screenshot-visitor-3.png)
![Screenshot Visitor 4](https://raw.githubusercontent.com/ndunks/qcdesa-client-pwa/master/docs/img/screenshot-visitor-4.png)
![Screenshot Visitor 5](https://raw.githubusercontent.com/ndunks/qcdesa-client-pwa/master/docs/img/screenshot-visitor-5.png)

### Halaman Voter
![Screenshot Voter 1](https://raw.githubusercontent.com/ndunks/qcdesa-client-pwa/master/docs/img/screenshot-voter-1.png)

### Halaman Admin
![Screenshot Admin 1](https://raw.githubusercontent.com/ndunks/qcdesa-client-pwa/master/docs/img/screenshot-admin-1.png)
![Screenshot Admin 2](https://raw.githubusercontent.com/ndunks/qcdesa-client-pwa/master/docs/img/screenshot-admin-2.png)
![Screenshot Admin 3](https://raw.githubusercontent.com/ndunks/qcdesa-client-pwa/master/docs/img/screenshot-admin-3.png)

## More Info

*Contact: arifin@klampok.id klampok.child@gmail.com*

**Aplikasi ini dapat terwujud karena dukungan dari berbagai pihak**

* [Desa Klampok - Banjarnegara](http://klampok.id)
* [LightCCTV](https://www.facebook.com/Light-cctv-klampok-347276432868896/)
* [LPK Kiraboshi](https://www.facebook.com/kiraboshilpk)
