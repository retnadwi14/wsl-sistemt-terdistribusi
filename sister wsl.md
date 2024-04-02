# Sistem Terdistribusi

install wsl

1. buka ubuntu kemudian run as administrator
2. ketik wsl install
3. ikuti langkah dibawah ini

![Screenshot (2392).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/21847703-01c1-4976-9725-54b8e21f2437.png)

sudo apt install wsl

![Screenshot (2395).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/d8a8f2f7-4660-424b-bde3-e711f60b40d0.png)

kemudian salinlah code untuk source.list pada github

![Screenshot (2397).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/253806b3-cf1a-46ff-84cc-7216f5c5fbe0.png)

maka akan terupdate source list sebelumnya jangan lupa untuk save ctrl x kemudian y dan enter

![Screenshot (2399).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/2ae79c21-7e81-44a7-a228-5ae237ab6df5.png)

sudo apt upgrade -y

![Screenshot (2402).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/28789b3d-d945-4560-bb0a-1a3271e43c7d.png)

sudo apt-get install lxc lxcctl lxc-templates net-tools

kemudian tekan y

![Screenshot (2404).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/9c5aa9fb-c60b-4104-8ba8-441f956c172c.png)

disini statusnya harus enabled semua

![Screenshot (2406).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/191092fa-224d-4b48-a18b-bffacc2f382c.png)

disini kita bisa check templates yang tersedia

![Screenshot (2408).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/8a116a13-503f-455f-b07d-d50d72244971.png)

sudo apt install nginx nginx-extras

kemudian klik y

![Screenshot (2412).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/642d334b-c0b9-4595-a8b6-32be94310463.png)

kemduian masuk ke folder nginx

![Screenshot (2416).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/c05d72c2-26e9-476d-8911-878906665d47.png)

hapus command yang berwarna biru 

![Screenshot (2417).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/6fa4441f-785a-4579-b19f-0ea94b1eecda.png)

seperti ini

jangan lupa ganti server name ke sister.local

![Screenshot (2424).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/b117d83f-56d8-489f-9a6d-ff8ff49416af.png)

kemudian ctrl x ,y, enter

![Screenshot (2426).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/15737a6c-debb-4c71-a97a-655894f45bd9.png)

kemudian dari command tulisan biru bagian bawah ada server listen 80 hapus # kemudian [example.com](http://example.com) diganti dengan sister local dan html

![Screenshot (2429).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/7ff85834-1593-4f09-8dc3-8685b63a3a87.png)

kemudian kita masuk ke folder dengan mengetik ls

![Screenshot (2430).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/577a6fb2-041e-4add-856c-a352e40cd8e6.png)

kemudian akan masuk ke sister.local

ganti title ke welcome to sister!

kemudian paraghraph 1 <h1> dengan sistem terdistribusi class!

jangan lupa untuk ctrl x , y , enter

![Screenshot (2431).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/e89abb7e-eae5-4a54-826a-7d3774c2c276.png)

agar kita bisa membuat web dan tulisan diatas masuk ke web maka kita membuat notepad

pertama klik notepad dan run as administrator

setelah kalian buka notepad tersebut maka diatas kiri muncul file 

klik kemudian open 

ke storage C pada laptop kalian

kemudian ke windows

system32

drivers

etc

pilih hosts (file)

kemudian salin isi di dalam ke notepad yang kalian buat 

kemudian letakkan pada bagian paling bawah

dan save

![Untitled](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/2726b07a-42f0-4d03-91fa-fcef2d20b900.png)

kemudian buka [localhost](http://localhost) di microsoft bing 

ketik sister.local

maka akan muncul seperti ini

![Screenshot (2437).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/975f69d7-8bbb-4519-abf9-89f8b5bdc8d6.png)

kita masuk ke var/www/html/ dan cek templates

![Screenshot (2442).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/660e0254-69cb-4415-b988-9ca73ae2e725.png)

kalau microservices2 itu bionic

![Screenshot (2449).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/8c4c6411-fba9-40f6-b642-dc7b46975d86.png)

![Screenshot (2451).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/4da381fc-4434-4ec6-a56a-c1ba1c321dbe.png)

kalau microsevices memakai focal

![Screenshot (2454).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/34af1da1-4287-4436-b1e5-7cc943c30d4b.png)

kemudian kita ping google

![Screenshot (2455).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/9820bb7b-66d7-45c2-b25e-56dfd1162282.png)

jangan lupa mengganti pada microserver2

 dhcp4: no

addresses 

gateway4 : 10.0.3.1

seperti dibawah

![Screenshot (2456).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/6c3c9fc9-2125-43af-82fc-952e1bb34b59.png)

kemudian lakukan update dan upgrade

![Screenshot (2458).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/ec058968-3163-4d28-a0d7-a22426d08949.png)

setelah masuk var/www/html sebenerny akan muncul command seperti file sister local sebelumnya namun disini saya mengalami error dan sudah membetulkan tapi tetap stuck jadi saya sampai disini pengerjaan nya.

![Screenshot (2459).png](Sistem%20Terdistribusi%201a110be387da47beb95c6486f62eb54a/a94ef904-3ac3-4499-9b9e-0a64f104baa5.png)