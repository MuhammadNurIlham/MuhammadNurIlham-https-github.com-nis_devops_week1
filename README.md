# Culture DevOps dalam sebuah perusahaan

## DevOps Concept
DevOps adalah gabungan dari Development dan Operations. Kombinasi tersebut dirancang agar dapat meningkatkan kemampuan perusahaan untuk proses development hingga rilis produk ke public. Di bawah model DevOps ini, tim developer dan IT operations akan bekerja bersama di seluruh tahapan __*software development life cycle*__ untuk menghasilkan produk digital yang berkualitas secara efektif dan efisien.
## Flow DevOps dalam sebuah perusahaan dari awal sampai akhir
![Flow DevOps](https://raw.githubusercontent.com/andreybleme/andreybleme.github.io/master/assets/img/devops-principles.png)

DevOps divisualisasikan sebagai proses loop tak terbatas yang terdiri dari :
- __Plan__ : Dalam proses ini melibatkan perencanaan untuk seluruh alur kerja yang dibutuhkan sebelum tim pengembang mulai menulis kode. Dalam tahap ini, manajer produk dan manajer proyek akan memainkan peran penting.
- __Code__ : Setelah rencana dibuat, tim developer dapat mulai menulis kode yang dibutuhkan untuk mengembangkan produk.
- __Build__ : Code yang dibuat untuk mengotomasi aplikasi untuk melakukan proses Build sebelum dapat digunakan, tergantung bahasa pemrograman yang akan di build. Setelah tim developer selesai menulis kode yang dibutuhkan, mereka akan memasukkan kode tersebut ke dalam shared code repository.
- __Test__ : selanjutnya adalah melakukan pengujian. jika ada masalah yang ditemukan pada tahap ini, maka masalah tersebut akan dikirim kembali ke tim developer untuk diselesaikan.
- __Release__ : Fase Release menjadi tonggak penting dalam DevOps. pada tahap ini setiap perubahan kode telah melewati serangkaian pengujian dan tim IT operations telah memastikan bahwa masalah yang merusak dan regresi sudah teratasi dengan baik.
- __Deploy__ : Tahap selanjutnya adalah __*deployment*__. setelah production environment dibuat dan dikonfigurasi maka versi terakhir dari pengembangan yang telah dilakukan akan diterapkan.
- __Operate__ : pengoperasian aplikasi atau produk yang sudah dibuat
- __Monitor__ : pada tahap terakhir ini, tim IT operations akan terus bekerja keras untuk memantau infrastruktur, sistem, dan aplikasi. hal ini dilakukan untuk memastikan bahwa produk atau aplikasi yang dikembangkan dapat berjalan dengan lancar.
## Tools dan Fungsi yang digunakan DevOps
- __Cloud Environment__: merupakan platform yang dapat digunakan untuk menjalankan aplikasi
  -   GCP (Google Cloud Platform) 
![Google Cloud Platform](https://www.cloud-ace.sg/hs-fs/hubfs/logo_lockup_cloud_platform_icon_horizontal.png?width=600&height=155&name=logo_lockup_cloud_platform_icon_horizontal.png)
- __Containers__: adalah sebuah ruang terisolasi yang dapat berjalan di atas sistem operasi
![Docker](https://glints.com/id/lowongan/wp-content/uploads/2021/08/docker_facebook_share-300x256.png)
  - Docker : Docker memungkinkan pengembangan terdistribusi dan mengotomatiskan penerapan aplikasi yang dibuat.
- __Orchestrator__: adalah sebuah platform untuk memanagement service yang dapat di scale secara otomatis 
  - Kubernetes : Kubernetes adalah _tools open source_ yang memudahkan DevOps Engineer otomatisasi penerapan, pengolahan, pemeliharaan, dan penskalaan aplikasi container.
![Kubernetes](https://linuxhint.com/wp-content/uploads/2017/09/kubernetes-300x162.jpg)
- __Monitoring__: adalah sebuah service yang akan melakukan pengumpulan data seperti status server, logs dan lain sebagainya agar dapat divisualisasikan
  - Grafana
  - Prometheus
 ![Grafana & Prometheus](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/001/214/134/datas/gallery.jpg)
- __Infrastructure as a Code__: merupakan script automation yang digunakan untuk memanagement server, konfigurasi aplikasi
  - Ansible : adalah solusi yang aman dan ringan untuk otomatisasi manajemen konfigurasi sebab tidak ada agen yang bekerja di _background_ aplikasi atau produk yang dibuat.
![Ansible](https://upload.wikimedia.org/wikipedia/commons/0/05/Ansible_Logo.png)
- __Version Control System__: untuk memanagement source code aplikasi
  - Github : adalah tools yang berupa _platform version control_ untuk membantu __*DevOps Engineer*__ membuat dan menyimpan _file_ berwujud source code.

![GitHub](https://logos-world.net/wp-content/uploads/2020/11/GitHub-Logo-700x394.png)

![CI/CD WorkFlow](https://opsani.com/wp-content/uploads/2020/09/CI_CD-768x432.png)
- __CI/CD Pipeline__: untuk proses automation build, test, release dan deploy. _continuous integration_ adalah salah satu praktik paling penting dari DevOps. pada tahap ini, _developer_ akan mengumpuilkan dan menyatukan kode, kemudian menjalankan pengujian program secara cepat dan otomatis.
  - __Jenkins__ : Nah, Jenkins adalah _tools continuous integration_ andalan untuk para _DevOps Engineer_. Jenkins sendiri memiliki kelebihan sebagai berikut : Mudah untuk menangkap bug sejak dini, proses pengujian otomatis, integrasi berkelanjutan.
![Jenkins](https://webapp.io/content/images/2021/03/logo-title-opengraph.png)
## System Operasi yang digunakan pada perusahaan SWK Group
System Operasi yang digunakan adalah __*Linux*__ dengan distribusi __*Ubuntu*__ yang cocok untuk server
![Linux](https://thumb.viva.co.id/media/frontend/thumbs3/2017/05/19/591e9c72b5e1b-logo-linux_665_374.jpg)
![Ubuntu](https://1.bp.blogspot.com/-TEQdcux369Q/X56zkS39UcI/AAAAAAAADUc/DZPYLZTfAVoL5gqxNWeJLPYACtvzDa4qQCLcBGAsYHQ/w400-h300/Logo%2BUbuntu.png)

## Cloud Computing
__Cloud Computing__ adalah pengiriman berbagai layanan melalui internet, seperti data storage, servers, databases, networking dan software. pada perusahaan ini jenis __Cloud Computing__ yang digunakan adalah __*Public Cloud__* dengan menggunakan __*Google Cloud Platform*__.

## NetWork
Pada Perusahaan ini menggunakan __LAN (Local Area Network)__ karena jaringannya masih belum meluas hanya mencakup wilayah kecil dengan tipe jaringan __*CLient-Server*__ karena memiliki akses yang tinggi dan keamanan dan backup data lebih baik ini yang dicari oleh perusahaan ini dan dengan jenis __Topology__ yang digunakan adalah __*Star*__ 
IP address yang digunakan perusahaan ini adalah __IP Address Public__ dengan jenis __*IP Address Dinamis*__ dengan menggunakan __OSI Concept__ 
__OCI Concept__ sendiri adalah __*Open System Interconncetion*__, yaitu model referensi yang diciptakan dari sebuah kerangka yang bersifat konseptual
