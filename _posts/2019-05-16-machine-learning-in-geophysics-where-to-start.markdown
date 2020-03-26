---
layout: post
title:  "Machine Learning in Geophysics? Where to Start"
date:   2019-05-16 09:18:51 +0700
categories: jekyll update
---

Machine Learning (Pembelajaran Mesin) menjadi topik yang populer dalam aplikasinya di keilmuan geofisika beberapa tahun terakhir ini. Namun, banyak dari kita yang masih bingung darimana kita harus memulai untuk belajar mengenai topik ini.

Mari kita bahas bertahap mengenai Machine Learning mulai dari pengertian dasarnya. Intinya, Machine Learning merupakan cabang ilmu dari Kecerdasan Buatan / Artificial Intelligence (AI) mengenai perancangan algoritma agar komputer dapat belajar dari data (learn from data). Dua aspek penting yang mendefiniskan Machine Learning adalah data dan algoritma yang dibuat. Berdasarkan pengertian ini, pokok Machine Learning dapat dibagi menjadi 4 bagian:
1. Pembelajaran terarah (supervised learning)
2. Pembelajaran tak terarah (unsupervised learning)
3. Pembelajaran semi-terarah (semi-supervised learning)
4. Reinforcement learning

Dalam bidang Machine Learning, seringkali kita juga mendengar istilah Data Mining. Apakah kaitan antara keduanya? Data Mining sendiri lebih fokus untuk mengeksplor karakteristik baru dan melakukan analisis data atau dikenal dengan istilah exploratory data analysis (EDA) yang berprinsip pada unsupervised learning.

Selain itu, Machine Learning juga memiliki kaitan dengan Optimasasi dalam bidang matematika yang sering kita temui dalam pemrosesan dan pemodelan data geofisika. Machine Learning seringkali ditujukan sebagai formulasi untuk meminimalisasi error antara data (observasi) dan model. Perbedaan antara keduanya ialah algoritma optimisasi bertujuan untuk meminimalisir selisih dalam data, sedangkan Machine Learning lebih ditujukan untuk meminimalisir selisih dari unseen samples.

Machine Learning pun sangat erat kaitannya dengan Statistika Komputasi. Fondasi dari Machine Learning telah lama ada dalam sejarah perkembangan ilmu Statistik. Bahkan, keduanya sekarang dikukuhkan berada di bawah rumpun bidang ilmu yang sama, yakni Data Science. 

### Bagaimana konsep Machine Learning bekerja?

Tujuan utama pembelajaran adalah untuk mengeneralisasi pengalaman yang telah dilalui. Generalisasi yang dimaksud dalam Machine Learning adalah kemampuan komputer untuk berhadapan dengan data yang baru setelah diberikan "pengalaman" melalui data training. Data training dapat berupa suatu distribusi propbabiltas yang tidak diketahui dan "si pembelajar" diharuskan untuk membuat model general sehingga kelak mampu mengeluarkan prediksi untuk data yang baru. 

### Metode Pendekatan

1. Feature learning
2. Sparse dictionary learning
3. Anomaly detection
4. Decisions tree
5. Association rules

### Model
Beberapa Model berikut seringkali kita baca pada judul berbagai paper ilmiah.

- Artificial neural networks (ANNs)
Seringkali disebut juga sebagai connectionist systems, merupakan sistem komputasi yang terinspirasi dari jaringan saraf biologis yang membentuk otak hewan. ANN adalah model yang didasarkan pada kumpulan unit atau node yang terhubung yang disebut "artificial neurons". Setiap koneksi dapat mengirimkan "sinyal" dari satu artificial nueron ke yang lainnya. Artificial neuron yang menerima sinyal dapat memprosesnya dan kemudian memberi sinyal tambahan artificial neuron yang terhubung dengannya. 

Pada implementasinya, sinyal pada titik koneksi antar artificial neuron adalah bilangan real dan keluaran dari setiap artificial neuron dihitung oleh beberapa fungsi non-lineardari jumlah inputnya. Koneksi antar artificial neuron disebut dengan "edges". Artificial neuron dan edges biasanya memiliki pembobotan yang disesuaikan ketika proses pembelajaran berlangsung. Nilai pembobotan akan menambah atau mengurangi kekuatan sinyal pada suatu koneksi. Artificial neuron dapat memiliki nilai ambang batas atau "threshold" sehingga sinyal hanya akan dikirimkan jika nilainya diatas nilai threshold. Biasanya artificial neuron dikumpulkan menjadi beberapa layer. Layer yang berbeda dapat melakukan  berbagai jenis transformasi pada inputnya. Sinyal yang bergerak dari lapisan pertama (input) ke lapisan terakhir (output) bisa jadi telah melewati layer-layer tersebut berulang kali. 

- Support vector machines
- Bayesian networks
- Genetic algorithm




