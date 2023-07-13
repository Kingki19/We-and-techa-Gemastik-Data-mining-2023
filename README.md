> Dokumentasi ini dibuat atas karya yang telah kami buat pada perlombaan gemastik 2023 divisi Data Mining

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
- Dokumen makalah: [Gdocs viewer](https://docs.google.com/document/d/1kbkb_xQ8beel8uJZu-z1mqq9H9K3Nt9O/edit)
- Notebook 1 (pelabelan manual): [Google colab](https://colab.research.google.com/drive/1_JCuKx3Ru9_cNlxSchSUWofqpYH96Ycd?usp=sharing) *{Tidak digunakan dalam makalah}*
- Notebook 2 (pelabelan otomatis): [Google colab](https://colab.research.google.com/drive/1DdJ0T4a_DaShO9ZpAScXkpGQZyMjrvpP?usp=sharing) *{Digunakan dalam makalah}*

*Terakhir diedit pada tanggal: 13 Juli 2023*
