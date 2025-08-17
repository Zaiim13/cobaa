# Analisis Bahasa Slang Internet: Studi Kasus Ketikan Netizen Indonesia

Di dunia digital, bahasa slang mendominasi percakapan netizen Indonesia, menggantikan bahasa formal yang jarang dipakai. Fenomena ini menarik untuk diteliti karena slang tidak hanya sekadar singkatan, tapi juga mencerminkan kreativitas dan adaptasi bahasa di ruang virtual. Namun, bagi yang belum terbiasa, pola-pola abstrak seperti "bgsd" (bangsat) atau "wkwk" (tawa) bisa membingungkan, memicu pertanyaan: mengapa slang lebih populer daripada bahasa baku?

Studi ini bertujuan mengungkap:  
1. Pola umum pembentukan slang
2. Kata-kata yang paling sering diubah menjadi slang
3. Kata-kata yang paling jarang dimodifikasi  

Hasil analisis ini tidak hanya menarik bagi peneliti bahasa, tapi juga bermanfaat untuk memahami dinamika sosial di internet. Dari sini bisa dilihat apakah slang muncul karena efisiensi, tren, atau sekadar gaya bermain-main dengan kata. Dengan memetakan pola-pola ini, kita mendapat gambaran lebih jelas tentang evolusi bahasa di era digital.

## Raw dataset Link : https://huggingface.co/datasets/theonlydo/indonesia-slang

## Insight & Findings

Terdapat banyak pola bahasa slang yang ada pada data, tapi akan diambil 5 pola yang lumayan sering digunakan netizen indonesia, antara lain :
- penambahan huruf pada kata
- penghapusan huruf vokal
- penghapusan satu huruf
- penggunaan angka
- penggunaan pola abstrak

semua pola bahasa slang diperuntukkan untuk mempermudah penulis menyampaikan pesan, entah dengan mempersingkat dengan menghapus huruf2 pada kata, atau menggunakan angka untuk mengisyaratkan huruf maupun pengulangan, atau penambahan huruf untuk mengekspresikan emosi dalam bentuk tulisan, atau bahkan dengan pola-pola abstak yang harus dikonfirmasi dulu maksudnya. 

Lalu untuk kata yang paling sering diubah adalah kata **amin**, yang mempunyai hingga lebih dari 10 variasi. sedangkan, untuk kata yang paling jarang dimodifikasi ialah **subhanallah**, dengan hanya 3 variasi kata. banyak asumsi yang dapat disimpulkan dari temuan-temuan diatas, namun favorit saya ialah kata **amin** sangat mungkin diucapkan dalam banyak ekspresi, entah itu marah, senang, bahagia, kecewa, khawatir, berharap, ikhlas, dan lain-lain. oleh karena itu, sangat banyak variasi dari kata amin yang ditemukan.

## AI Support explanation

AI yang digunakan ialah IBM Granite 3.2-8b instruct lewat google colab, digunakan untuk analisis pola, klasifikasi, dan summarization. lebih lengkapnya silakan kunjungi : https://colab.research.google.com/drive/1-LocFsdI6j4D810TaZ40xfQQ4ezBIqka?usp=sharing