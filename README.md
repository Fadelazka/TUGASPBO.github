Kode ini sebenernya sederhana tapi cukup bikin saya mikir pas pertama lihat. Jadi, kita punya data dari klinik yang berisi rekam medis pasien dengan detak jantung (BPM). Data itu disimpan dalam bentuk dictionary dengan list di dalamnya—lumayan rapi sih menurut saya. Nah, tugasnya adalah memproses setiap data BPM untuk menentukan statusnya: Rendah, Normal, atau Tinggi.

Pertama, saya bikin fungsi analisa_kondisi yang isinya percabangan biasa. Kalau BPM di bawah 60, berarti Rendah; antara 60 sampai 100 itu Normal; di atas 100 baru Tinggi. Saya sempat ragu, apa batasan ini udah sesuai standar medis? Tapi buat keperluan latihan kayaknya aman.

Bagian loop-nya pakai enumerate biar sekalian dapet nomor urut (mulai dari 1). Tadinya saya coba pake for i in range(len(...)), tapi kata teman lebih gampang pake enumerate, dan bener aja, kodenya jadi lebih pendek dan gampang dibaca. Di setiap iterasi, saya ambil nilai bpm, masukin ke fungsi, terus cetak hasilnya.

Yang paling bikin saya seneng adalah pertama kali kodenya jalan tanpa error. Pas output muncul "Data ke-1: 70 BPM -> Normal", rasanya puas banget, kayak ada lampu yang nyala di otak. Tapi jujur, pas ngetik pertama kali, saya lupa indentasi di fungsi, jadi error mulu. Alhamdulillah, setelah dicek pelan-pelan, ketemu juga salahnya. Ke depannya saya pengen lebih teliti lagi soal indentasi dan penamaan variabel biar nggak ribet sendiri.

