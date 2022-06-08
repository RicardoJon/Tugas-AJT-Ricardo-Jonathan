# Tugas-AJT-Ricardo-Jonathan
Mahasiswa FILKOM UB
Ricardo Jonathan

195150307111012

Arsitektur Jaringan Terkini - TKOM A

Tugas 1 Membuat Instance
![172610595-384ae730-a3dd-4444-bcf3-0cd568d47b31](https://user-images.githubusercontent.com/90437038/172729761-508ad22f-c837-49d4-aa1b-362e3a3bcf98.png)
![ww 1](https://user-images.githubusercontent.com/90437038/172726677-eb5c9a35-d706-433b-92bf-aa98487aebd6.PNG)
![ww 2](https://user-images.githubusercontent.com/90437038/172726688-7f026a0c-ad8c-48da-b3e9-fe00e3f97b2c.PNG)
Dalam tugas pertama ini, saya diajari membuat instans EC2 di konsol AWS. Jenis instans yang ditentukan: t2.medium, AMI: Server Ubuntu  22.04 LTS 64-bit, SSH diizinkan, HTTP diizinkan, HTTPS diizinkan, grup keamanan terbuka untuk port TCP  8081 dan 8080, 30 GiB, gp3. Mininet, Ryu, dan Flow Manager akan menemani Anda.

Tugas 2 Mininet Custom Topology
![ww 1](https://user-images.githubusercontent.com/90437038/172727187-f4dcffdc-3491-4255-bb2a-51389f7228a3.PNG)
![ww 2](https://user-images.githubusercontent.com/90437038/172727196-d931917c-b41f-41f9-8c1d-5b22af1bd4ec.PNG)
Dalam tugas kedua ini, saya membuat topologi khusus, membuat aliran data antara Host 1 dan Host 2, dan menguji koneksi.

Tugas 3 Ryu Load Balancer
![ww 1](https://user-images.githubusercontent.com/90437038/172727765-0bd3ecd9-83a0-4d64-a42c-68858a9f12a7.PNG)
![ww 2](https://user-images.githubusercontent.com/90437038/172727775-aa658cc1-9c20-4bc2-8cf1-45785c708939.PNG)
![ww3](https://user-images.githubusercontent.com/90437038/172727793-8c3da472-169b-4193-8f32-a3e5e69c7d1f.PNG)
![ww5](https://user-images.githubusercontent.com/90437038/172727804-ebcafa8a-2965-47ba-959b-cf61aa0399da.PNG)
Di tugas 3 ini, saya belajar membimbing load balancer, Load balancing adalah trik pembagian pikulan traffic simetri rekayasa atau server. Dengan load balancer, pikulan traffic tidak akan dibebankan menjelang sejumlah jalur koneksi. Hal ini menyelak masa tanggapan server Anda dan mencegahnya dari overloading. Dengan begini, daya server Anda akan lebih maksimal tidak peduli berapa berlebihan traffic yang Anda dapatkan.

Tugas 4 Shortest Path Routing
![ww 1](https://user-images.githubusercontent.com/90437038/172729245-ddb7d117-8cd0-4d86-a0e9-3e00c06d060c.PNG)
![ww 2](https://user-images.githubusercontent.com/90437038/172729250-70b38b28-9355-40d9-898b-8c82b53d2426.PNG)
Saya sudah mengikuti step step dari bapak, akan tetapi saya selalu error, error tersebut tertuliskan “no module named dijkstra_Ryu_controller” 
Saya juga sudah mencobanya terus menerus tapi selalu tidak ada modul bernama dijkstra ryu controller, jadi disini saya akan menggunakan contoh dari teman saya yang berhasil mengeksekusinya.

Contoh dari hasil eksekusi atau tugas teman saya:

Tampilan terminal 1:

![172608395-925a48df-5820-4b95-b07f-5e940288ec8e](https://user-images.githubusercontent.com/90437038/172729805-8eac5aa8-3d9f-4aa6-8332-9d4cd657d1fc.png)
![172608422-47cbae14-75e5-4bc2-8a1a-725e43294a88](https://user-images.githubusercontent.com/90437038/172729820-bf6cca72-8a25-4d87-8e66-58e19ac49d8b.png)
![172608967-428747b8-1ccc-4ec2-a8e1-06c731b298de](https://user-images.githubusercontent.com/90437038/172729829-8b6ec585-0da3-481c-bd82-922d1ecbf1a9.png)

Tampilan terminal 2:

![172609245-f97db450-5395-4f3f-b8e6-6aa174411a76](https://user-images.githubusercontent.com/90437038/172729880-07c2419c-1cf2-4438-b816-cf3060290bfe.png)

Pengujian koneksi (h1 ping -c 4 h4)


Tampilan terminal 1:

![172609479-e63265b4-bdcd-4043-aa9a-069ae8428aec](https://user-images.githubusercontent.com/90437038/172729934-9d3bb1e1-ca42-42b2-8a31-f39f9206fe0a.png)

Tampilan terminal 2:

![172609539-07505227-8e96-4c06-adbb-d93d66e76fb6](https://user-images.githubusercontent.com/90437038/172729978-3a05ee4d-c1cd-4cd7-ac32-c7dc82303ad2.png)

Pengujian koneksi (h5 ping -c 4 h6)


Tampilan terminal 1:

![172610150-80e0f109-a52b-40eb-8105-11a1fba16b1f](https://user-images.githubusercontent.com/90437038/172730025-a5d01c60-92b0-4efb-86b1-ef2195dca09b.png)

Tampilan terminal 2:

![172610197-4dd549c3-a42e-4afa-ae4d-65f9c057d272](https://user-images.githubusercontent.com/90437038/172730047-d036873d-de3f-406b-8fbd-0bd5c94e9a57.png)

Pada tugas 4 ini, kita diajarkan bab cara pengaplikasian SPF Routing, yang menemukan algoritma routing di mana router menilai serat terpendek ganggang setiap pasangan node yang siap di bagian dalam jaringan. Protokol Open Shortest Path First (OSPF) dibuat berlandasan algoritma Shortest Path First (SPF).
Sekali lagi ini saya tidak menyontek atau apapun, saya hanya memberi contoh hasil pengeksekusian tiap terminal dan routing jika berhasil, karena punya saya tidak dapat berjalan karena masalah “no module named dijkstra_Ryu_controller”. Mohon maaf bila banyak kekurangan.
