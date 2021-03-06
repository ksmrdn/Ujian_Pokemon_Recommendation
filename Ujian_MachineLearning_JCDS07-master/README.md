# Soal Ujian Data Science - Machine Learning

![Lintang_Purwadhika](https://static.wixstatic.com/media/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png/v1/fill/w_246,h_39,al_c,usm_0.66_1.00_0.01/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png)

#

<img src='https://img.pokemondb.net/sprites/sun-moon/icon/pikachu.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/bulbasaur.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/charmander.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/squirtle.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/caterpie.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/pidgey.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/rattata.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/clefairy.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/poliwhirl.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/jigglypuff.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/growlithe.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/nidoran-m.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/nidoran-f.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/psyduck.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/machop.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/bellsprout.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/haunter.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/krabby.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/magikarp.png' alt='lintang' style='height:13px; width:18px'/>


## **Pokemon Recommendation**

Disediakan sebuah dataset Pokemon: [unduh di sini](https://www.kaggle.com/abcsds/pokemon), beserta Pokemon API: [akses di sini](https://pokeapi.co/). Buatlah sebuah __*content-based filtering recommender system*__ dengan menggunakan __Flask__, yang dapat memfasilitasi user untuk menyebutkan Pokemon favoritnya & menyajikan rekomendasi __6 Pokemon__ berdasarkan feature: __Type 1__, __Generation__ & __Legendary__ Pokemon. Aplikasi yang dibuat harus memenuhi syarat minimal berikut:

1. Server aplikasi akan berjalan di __localhost:5000__ dan ketika user melakukan GET request via browser akan tampil sebuah halaman __HTML__ sederhana yang memuat __1 buah text input__ dan __1 buah button__. Desain tampilan HTML tidak harus sama seperti contoh soal, utamakan fitur!

    ![poke_1](./soal2a.png)

2. User dapat memasukkan nama Pokemon favoritnya ke dalam text input yang sudah disediakan. Saat user menekan tombol __"Cari Pokemon"__, jika data ditemukan, maka user akan di-redirect ke __localhost:5000/hasil__ yang berisi halaman __HTML__, yang menampilkan data seputar Pokemon favorit user, disertai dengan data __6 Pokemon__ yang direkomendasikan berdasarkan __type__, __generasi__ & __legend__. Data yang ditampilkan untuk tiap Pokemon minimal: _nama_, _gambar_, _tipe_, _generasi_ & _legendary_. Gambar Pokemon tidak terdapat pada dataset, tapi dapat diambil dari [Pokemon API](https://pokeapi.co/). Halaman ini juga dilengkapi __1 buah button__ untuk kembali ke halaman awal. Desain tampilan HTML tidak harus sama seperti contoh soal, utamakan fitur!

    - Contoh jika user memfavoritkan __Pikachu__ <img src='https://img.pokemondb.net/sprites/sun-moon/icon/pikachu.png' alt='lintang' style='height:13px; width:18px'/>:
    
        ![poke_2](./soal2b.png)

        ![poke_3](./soal2c.png)

    - Contoh jika user memfavoritkan __Pidgeotto__ <img src='https://img.pokemondb.net/sprites/sun-moon/icon/pidgey.png' alt='lintang' style='height:13px; width:18px'/>:

        ![poke_4](./soal2d.png)

        ![poke_5](./soal2e.png)

4. Namun jika Pokemon favorit user tidak ditemukan, maka user akan di-redirect ke halaman __HTML__ yang memberikan informasi bahwa data tidak ditemukan. Halaman ini juga dilengkapi __1 buah button__ untuk kembali ke halaman awal. Desain tampilan HTML tidak harus sama seperti contoh soal, utamakan fitur!

    ![poke_6](./soal2f.png)

⚠ [Pokemon API](https://pokeapi.co/) memiliki batasan __100 API request per IP address per menit__. Jika Anda mengalami kendala dikarenakan telah mencapai limit, maka tunggulah sejenak beberapa menit, lalu coba call API kembali.

<img src='https://img.pokemondb.net/sprites/sun-moon/icon/raichu.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/venusaur.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/charizard.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/blastoise.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/butterfree.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/pidgeot.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/raticate.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/clefable.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/poliwrath.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/wigglytuff.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/arcanine.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/nidoking.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/nidoqueen.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/golduck.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/machamp.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/victreebel.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/gengar.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/kingler.png' alt='lintang' style='height:13px; width:18px'/> <img src='https://img.pokemondb.net/sprites/sun-moon/icon/gyarados.png' alt='lintang' style='height:13px; width:18px'/>

#