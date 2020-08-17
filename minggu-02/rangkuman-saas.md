# Software as a Service
## Perbedaan antara IaaS, PaaS, dan SaaS

![1](https://github.com/hudaimi/tekn-cloud-computing/blob/master/minggu-02/Image/1.png)

Terdapat 3 model layanan bisnis berbasis cloud, yaitu: SaaS (seperti MTARGET), PaaS, dan Iaas. Dalam artikel ini kami akan membahas apa saja perbedaan diantara ketiganya.

Software as a service (SaaS)
SaaS merupakan suatu lisensi perangkat lunak dan delivery model yang berbasis cloud, sehingga memungkinkan untuk tetap mengakses suatu software dimanapun dengan menggunakan device apapun melalui koneksi internet. Dalam SaaS, pengguna tidak perlu lagi melakukan install, update, atau menangani masalah pada software yang digunakan karena semua hal tersebut telah dikelola oleh vendor, pengguna hanya tinggal menggunakan service yang disediakan.
Contoh dari SaaS : Dropbox, Google Apps, MTARGET, Salesforce, Cisco WebEx.

Platform as a Service (PaaS)
Jika dalam SaaS pengguna hanya perlu menggunakan software yang disediakan oleh vendor, model cloud service pada PaaS biasanya berupa framework yang digunakan oleh pengguna (developer) untuk membangun atau membuat perangkat lunak. Sistem operasi, server dan segala kebutuhan yang diperlukan disediakan oleh vendor. Hal ini memungkinkan pengguna untuk lebih fokus pada pengembangan perangkat lunak.
Contoh PaaS : Google App Engine, Stratos Apache, OpenShift, Windows Azure, AWS Elastic Beanstalk.

Infrastructure as a service (IaaS)
IaaS dinilai sebagai model cloud service paling fleksibel karena penggunanya memiliki kendali penuh terhadap infrastruktur yang digunakan, mulai dari server cloud, jaringan, sistem operasi, hingga penyimpanan. Dalam IaaS, pengguna juga dapat membuat "pusat data virtual" di cloud dan memiliki akses ke seluruh data tanpa harus memiliki hardware tersendiri.
Contoh IaaS : DigitalOcean, Linode, Rackspace, Amazon Web Services (AWS), Cisco Metapod, Microsoft Azure, Google Compute Engine (GCE).

## Arsitektur Platform SaaS

![1](https://github.com/hudaimi/tekn-cloud-computing/blob/master/minggu-02/Image/2.png)

Dengan menggunakan model tersebut, arsitektur pada SaaS ini memungkinkan layanan untuk dapat digunakan oleh banyak pengguna dan dari berbagai jenis device seperti pada gambar diatas (App Server, Mobiles, Networks, PC, Codes, dan Database), dikarenakan aplikasi ini diinstall pada banyak mesin untuk mendukung skalabilitas.

Alasan menggunakan Arsitektur SaaS

Dari Pendapat Konsumen
Produk SaaS ini merupakan salah satu cara termudah untuk menggunakan layanan atau produk digital dimana pengguna hanya cukup mengaksesnya melalui web, membayar layanan tersebut, dan lalu menggunakannya.

Dari Pendapat Perusahaan
Produk SaaS ini membantu mereka dalam mengiklankan produk perusahaan mereka ke pasar dunia dan juga memungkinkan mereka untuk mempertahankan kontrol keseluruhan atas produk tersebut, selain itu juga membantu dalam mengurangi jangka waktu bagi produk untuk mencapai pasar, mengurangi biaya perawatan produk, memudahkan pembaruan produk, dan lain - lain.

## Kapan Menggunakan SaaS

SaaS mungkin menjadi opsi paling bermanfaat dalam beberapa situasi, Banyak sekali kegiatan dalam bisnis atau personal sangat membutuhkan Layanan Saas. Lantas Kapan kamu harus menggunakan Saas :
* Ketika sebuah Startup atau perusahaan kecil yang membuat Apps/project dengan cepat dan tidak punya waktu untuk masalah server atau perangkat lunak
* Ketika mengerjakan proyek jangka pendek yang membutuhkan kolaborasi cepat, mudah, dan terjangkau
* Aplikasi yang tidak terlalu sering dibutuhkan, seperti perangkat lunak pajak