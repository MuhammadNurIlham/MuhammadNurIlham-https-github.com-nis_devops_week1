# Culture DevOps dalam sebuah perusahaan

## DevOps Concept
DevOps adalah gabungan dari Development dan Operations. Kombinasi tersebut dirancang agar dapat meningkatkan kemampuan perusahaan untuk proses development hingga rilis produk ke public. Di bawah model DevOps ini, tim developer dan IT operations akan bekerja bersama di seluruh tahapan __*software development life cycle*__ untuk menghasilkan produk digital yang berkualitas secara efektif dan efisien.
## Flow DevOps dalam sebuah perusahaan dari awal sampai akhir
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
  -   AWS (Amazon Web Service)
  -   GCP (Google Cloud Platform)
  -   Azure (Microsoft Azure)
  -   vultr
  -   DigitalOcean
- __Containers__: adalah sebuah ruang terisolasi yang dapat berjalan di atas sistem operasi
  - Docker : Docker memungkinakn pengembangan terdistribusi dan mengotomatiskan penerapan aplikasi yang dibuat.
  - LXC or LXD
  - Podman
  - Containerd
- __Orchestrator__: adalah sebuah platform untuk memanagement service yang dapat di scale secara otomatis 
  - Docker Swarm
  - Kubernetes : Kubernetes adalah _tools open source_ yang memudahkan DevOps Engineer otomatisasi penerapan, pengolahan, pemeliharaan, dan penskalaan aplikasi container.
- __Monitoring__: adalah sebuah service yang akan melakukan pengumpulan data seperti status server, logs dan lain sebagainya agar dapat divisualisasikan
  - Grafana
  - Prometheus
- __Infrastructure as a Code__: merupakan script automation yang digunakan untuk memanagement server, konfigurasi aplikasi
  - Ansible : adalah solusi yang aman dan ringan untuk otomatisasi manajemen konfigurasi sebab tidak ada agen yang bekerja di _background_ aplikasi atau produk yang dibuat.
  - Terraform
- __Version Control System__: untuk memanagement source code aplikasi
  - Gitlab
  - Github : adalah tools yang berupa _platform version control_ untuk membantu __*DevOps Engineer*__ membuat dan menyimpan _file_ berwujud source code.
  - BitBucket
- __CI/CD Pipeline__: untuk proses automation build, test, release dan deploy. _continuous integration_ adalah salah satu praktik paling penting dari DevOps. pada tahap ini, _developer_ akan mengumpuilkan dan menyatukan kode, kemudian menjalankan pengujian program secara cepat dan otomatis.
  - Jenkins : Nah, Jenkins adalah _tools continuous integration_ andalan untuk para _DevOps Engineer_.
  - GitLab CI
  - GitHub Actions
  - BitBucket Pipeline
