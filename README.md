> Dokumentasi ini dibuat atas karya yang telah kami buat pada perlombaan gemastik 2023 divisi Data Mining biar keren aja gitu 😅 🐱

**Judul karya:**  
Pembangunan Model Analisis Sentimen Penerimaan AI pada Masyarakat melalui Komentar di Youtube

**Deskripsi karya:**  
Karya ini adalah sebuah analisis sentimen yang bertujuan untuk menggali pandangan dan pendapat masyarakat melalui kolom komentar Youtube terkait penerimaan AI di Indonesia. Dalam karya ini, kami menggunakan metode ensemble learning untuk melatih model kami. Data yang kami kumpulkan diterjemahkan ke bahasa Inggris menggunakan model Translator dari pustaka GoogleTrans. Lalu data dilabeli secara otomatis menggunakan model twitter-roberta-base-sentiment-latest dari pustaka Transformers. Kemudian data diekstraksi menggunakan TF-IDF dan word embbeding yang lalu kami buatkan model menggunakan beberapa algoritma seperti Naive-Bayes, SVM, KNN, dan Gradient-Boosting untuk membandingkan metode ekstraksi dan beberapa algoritma yang memperoleh model yang paling baik. Hasilnya, data yang diekstraksi menggunakan TF-IDF menunjukkan performa model yang lebih bagus ketimbang pemakaian word-embedding, serta keunggulan algoritma Gradient Boosting diantara algoritma model lainnya.

**Dosen pembimbing:**  
M. Faris Al Hakim, S.Pd., M.Cs.

**Anggota tim:**  
- Muhammad Rizqi [@Kingki19](https://github.com/Kingki19)
- Melani Siyamafiroh
- Michael Jonathan Panjaitan

**Link pekerjaan:**
- Dokumen makalah: [File PDF](https://github.com/Kingki19/We-and-techa---Gemastik-Data-mining-2023/blob/main/GEMASTIK%20XVI%20-%20Penambangan%20Data%20-%20GEMASTIK23-986616898%20-%20We%20and%20Techa%20-%20Pembangunan%20Model%20Analisis%20Sentimen%20Penerimaan%20AI%20pada%20Masyarakat%20melalui%20Komentar%20di%20Youtube.pdf)
- Notebook 1 (pelabelan manual): [Google colab](https://colab.research.google.com/drive/1_JCuKx3Ru9_cNlxSchSUWofqpYH96Ycd?usp=sharing) *{Tidak digunakan dalam makalah}*
- Notebook 2 (pelabelan otomatis): [Google colab](https://colab.research.google.com/drive/1DdJ0T4a_DaShO9ZpAScXkpGQZyMjrvpP?usp=sharing) *{Digunakan dalam makalah}*

**Video Youtube yang digunakan dalam data mining (untuk diekstrak komennya):**
> Data diekstrak pada tanggal 1 Juni 2023, komen setelah tanggal ini tidak termasuk  
1. [Titik Kritis Kecerdasan Buatan Telah Terlewati! Generative AI Mengancam Peradaban](https://www.youtube.com/watch?v=dWsIA2aOstA)
2. [AI Sama Sekali Seperti Yang Kalian Kira!](https://youtu.be/_FcHPrRY5zg)
3. [Babak Baru: AI - Kemajuan AI, Kemusnahan Manusia](https://youtu.be/yVrLflh3Ebk)
4. [Peluang dan Ancaman Kecerdasan Buatan (AI)](https://youtu.be/qAe8oGKiRbc)
5. [Eps 596: BAHAYA ChatGPT: AI ADALAH ANCAMAN BAGI MANUSIA](https://youtu.be/GA6cTuHgT7w)  

**Tools yang digunakan (selain notebook) dalam data mining ini:**
- [Youtube Comment Downloader](https://github.com/egbertbouman/youtube-comment-downloader)  
  Untuk mengekstrak comment Youtube tanpa API
- Model translator dari [googletrans](https://py-googletrans.readthedocs.io/en/latest/)  
Menerjemahkan komen ke bahasa Inggris agar bisa dilakukan pelabelan otomatis
- Model [twitter-roberta-base-sentiment-latest](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment-latest) dari [transformers](https://huggingface.co/docs/transformers/index)  
Model pre-trained yang digunakan untuk melabeli data secara otomatis



*Terakhir diedit pada tanggal: 13 Juli 2023*
