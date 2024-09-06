# Setup Vagrant Terotomatisasi untuk Teknologi Java

Repository ini berisi konfigurasi Vagrant untuk menyiapkan lingkungan pengembangan dengan teknologi berikut:

- **JDK 11**
- **Maven 3**
- **MySQL 8**
- **Spring MVC**
- **Spring Security**
- **Spring Data JPA**
- **JSP**
- **Tomcat**
- **Memcached**
- **RabbitMQ**
- **ElasticSearch**

## Prasyarat

Sebelum menggunakan setup Vagrant ini, pastikan Anda telah menginstal hal-hal berikut pada mesin host Anda:

- [VirtualBox](https://www.virtualbox.org/)
- [Vagrant](https://www.vagrantup.com/)
- vagrant plugin install vagrant-hostmanager

## Cara Memulai

1. **Kloning Repository**

   ```bash
   git clone https://github.com/imronnm/vagrant-automated-code.git
   cd vagrant-automated-code
   ```
2. **Setup Vagrant**
   
  ```bash
  vagrant up
  ```

File Vagrantfile dan skrip provisioning (setup.sh) mengotomatisasi pemasangan dan konfigurasi komponen berikut:

    JDK 11: Java Development Kit 11
    Maven 3: Apache Maven untuk manajemen proyek
    MySQL 8: Server database
    Tomcat: Kontainer servlet
    Memcached: Sistem caching
    RabbitMQ: Broker pesan
    ElasticSearch: Mesin pencari

Teknologi yang Disertakan

    Spring MVC: Framework untuk membangun aplikasi web
    Spring Security: Framework keamanan
    Spring Data JPA: Framework akses data
    JSP: Java Server Pages untuk pembuatan tampilan

File Konfigurasi

    Vagrantfile: File konfigurasi Vagrant
    setup.sh: Skrip shell untuk provisioning lingkungan

Setelah lingkungan Vagrant berjalan, Anda dapat mengakses layanan berikut:

    MySQL: Berjalan pada localhost:3306
    Tomcat: Berjalan pada localhost:8080
    ElasticSearch: Berjalan pada localhost:9200
    RabbitMQ: Berjalan pada localhost:5672
    Memcached: Berjalan pada localhost:11211
   
   
