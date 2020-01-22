# Paket Server PHP 5 & MySQL

## WINDOWS :
* [folder download](https://www.dropbox.com/sh/pbp2euknc8b7smw/AADc1D_H8G1ZbP_UaL4TwpVEa?dl=0)
 
### MySQL :
* install mysql
* konfigurasi settingan mysql

### PHP 5 :
* install apache ke C/Program Files (x86) "lokasi dapat dirubah"
* folder PHP copy ke C/Program Files (x86) "lokasi dapat dirubah"
* replace httpd.conf ke apache/conf
* "jika posisi folder PHP dirubah letaknya" buka bagian bawah file httpd.conf sesuaikan tempat copy folder PHP, contoh (PHPIniDir "C:\Program Files (x86)\PHP\")
* replace file httpd-vhosts.conf pada folder extra
* bikin folder untuk vhosting (D/vhosting/rodesta) "contoh"
* buka file httpd-vhosts.conf untuk mengatur letak dan menambahkan folder vhosting
* replace file hosts pada c/windows/system32/drivers/etc
* buka file hosts untuk mengatur domain localhost folder vhosting "contoh 127.0.0.1	rodesta.id"
* untuk menjalankan vhosting, buka web browser dan jalankan local server "contoh rodesta.id"

##### Terimakasih !!!