# Tutorial 8 - Game Polishing & Balancing
## Ramadhan Andika Putra (2206081976) - GameDev A <br>

### Latihan: Creating Particles
> Untuk latihan ini, saya membuat dua jenis particle di Godot menggunakan node GPUParticles2D. Pertama, saya membuat particle environment berupa hujan dengan menambahkan node GPUParticles2D di root level dan mengatur properties seperti Amount, Lifetime, Scale, Emission Shape, dan Gravity agar titik-titik particle terlihat seperti butiran hujan yang jatuh dan menyebar secara natural. Saya juga mengaktifkan fitur Trail agar partikel memiliki ekor sehingga tampilannya lebih halus dan hidup. Selanjutnya, saya menyesuaikan Visibility Rect supaya particle tetap terlihat meskipun kamera bergerak.
> 
> Untuk membuat particle trail saat player berjalan, saya menambahkan node GPUParticles2D di dalam scene player dan mengatur Texture menggunakan asset yang sesuai, serta mengatur Amount dan Lifetime supaya particle muncul sedikit dan tidak bertahan lama. Saya juga mengubah Emission Shape dan posisi node agar particle muncul di sekitar kaki player. Agar particle trail hanya aktif saat player berjalan dan menyentuh lantai, saya mengontrol atribut Emitting lewat script Player dengan mengecek input gerak dan kondisi pemain di lantai. Dengan begitu, efek trail ini berjalan dinamis mengikuti player dalam game.
<br>

### Latihan: Game Balancing
> Untuk latihan ini, saya mencoba menerapkan game balancing di Godot dengan mengatur Spawn Rate musuh pada scene Spawner.tscn yang saya tempatkan di level. Awalnya, spawn rate terlalu cepat sehingga pemain kesulitan melewati rintangan karena musuh muncul terlalu banyak tanpa jeda. Dengan mengubah Spawn Rate menjadi lebih lama, saya membuat permainan menjadi lebih seimbang, sehingga pemain tetap tertantang tapi tidak terlalu sulit sampai akhirnya saya menemukan nilai Spawn Rate yang pas agar gameplay terasa flow dan menyenangkan.
