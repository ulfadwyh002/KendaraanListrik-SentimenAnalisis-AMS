# Analisis Sentimen Publik terhadap Tren Kendaraan Listrik sebagai Alternatif Transportasi Ramah Lingkungan

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-4B8BBE?style=flat)
![YouTube](https://img.shields.io/badge/Data%20Source-YouTube-FF0000?style=flat&logo=youtube&logoColor=white)
![Collaborative](https://img.shields.io/badge/Collaborative%20Project-3776AB?style=flat)


## 📌 Latar Belakang

Kendaraan listrik kini mulai banyak dibicarakan sebagai solusi transportasi yang ramah lingkungan. Pemerintah juga sudah mendorong penggunaannya lewat subsidi dan insentif. Namun, belum semua masyarakat menerima hal ini dengan mudah. Ada yang mendukung karena dianggap lebih bersih dan modern, tapi ada juga yang masih ragu soal harga, daya tahan, dan infrastrukturnya. Oleh karena itu, analisis sentimen di media sosial menjadi penting untuk mengetahui bagaimana tanggapan publik secara lebih luas terhadap isu ini.

## ❓ Rumusan Masalah

1. Bagaimana sentimen publik terhadap kendaraan listrik sebagai solusi transportasi ramah lingkungan?
2. Bagaimana tanggapan publik terhadap aspek produk kendaraan listrik, seperti harga, performa, daya tahan, dan infrastruktur pendukungnya?
3. Sejauh mana merek kendaraan listrik memengaruhi opini dan sentimen publik?

## 🧭 Metodologi

Analisis dilakukan menggunakan pendekatan **sentiment analysis** dan **topic modeling**, dengan data komentar publik yang kemudian dikelompokkan menjadi beberapa cluster topik untuk sentimen **positif** dan **negatif** secara terpisah.

---

## 🟢 Topic Modeling — Sentimen Positif

| Cluster | Fokus Topik | Insight |
|---|---|---|
| **1. Transportasi & Energi** | Polusi, bahan bakar, subsidi BBM, transisi energi | Masyarakat menyuarakan isu polusi dan mendukung transisi ke kendaraan listrik, disertai keresahan terhadap bahan bakar konvensional dan subsidi BBM. |
| **2. Energi & Lingkungan (Baterai & Nikel)** | Nikel, baja, baterai, tambang, PLTU (termasuk isu Raja Ampat) | Publik mulai kritis terhadap dampak ekologis dari energi "bersih", terutama eksploitasi tambang nikel untuk baterai. |
| **3. Teknologi Baterai** | Harga, daur ulang, ketahanan baterai | Fokus masyarakat pada sisi teknis baterai — relevan dengan keinginan adopsi teknologi ramah lingkungan. |
| **4. Kendaraan Listrik Konsumen** | Mobil & motor listrik, pengalaman pengguna | Berfokus pada user experience — jarak tempuh hingga fasilitas pengisian. |
| **5. Random / Humor / Kritik Sosial** | Opini bebas, anekdot, kritik ringan | Ruang ekspresi publik yang lebih bebas dan tidak selalu berbasis data, namun berpotensi membentuk opini publik. |

## 🔴 Topic Modeling — Sentimen Negatif

| Cluster | Fokus Topik | Insight |
|---|---|---|
| **1. Harga Baterai & Biaya** | Baterai mahal, biaya energi listrik | Persepsi publik bahwa baterai kendaraan listrik terlalu mahal muncul berulang di berbagai komentar. |
| **2. Kerusakan & Umur Pakai Baterai** | Penggantian baterai, risiko kerusakan | Kekhawatiran publik terhadap umur pakai dan biaya penggantian baterai memperkuat narasi "mahal + rentan". |
| **3. Polusi, Nikel & Lingkungan** | Polusi, emisi, batubara, nikel | Sentimen bahwa kendaraan listrik tetap menyumbang polusi tidak langsung, terutama dari produksi nikel. |
| **4. Pajak & Insentif Pemerintah** | Diskon, pajak, kebijakan fiskal | Wacana dukungan fiskal pemerintah dinilai perlu ditingkatkan agar adopsi makin masif. |
| **5. Energi Alternatif & Teknologi** | Panel surya, cuaca ekstrem, transisi energi | Kelompok pembahasan yang lebih visioner tentang masa depan energi hijau. |
| **6. Kendaraan Listrik Rakyat & Humor** | Sepeda listrik, motor, nada satire | Konten ringan yang menggambarkan keraguan atau sindiran terhadap teknologi listrik. |
| **7. Bahan Bakar Fosil & Subsidi** | Minyak, bahan bakar, infrastruktur subsidi | Ketergantungan pada bahan bakar fosil masih menjadi tantangan transisi energi di Indonesia. |

## 🔑 Key Findings

- **Sentimen negatif mendominasi** opini publik terhadap kendaraan listrik sebagai alternatif transportasi ramah lingkungan (**42.8% negatif**, **40.5% netral**, dan hanya **16.6% positif**), meski jaraknya dengan sentimen netral cukup tipis.
- Sentimen positif cukup signifikan pada aspek **pengurangan polusi udara**, namun tetap kalah dominan karena publik meragukan klaim "ramah lingkungan" akibat dampak proses produksi (terutama tambang nikel untuk baterai).
- **Isu baterai** menjadi topik paling sering dibahas, publik menyoroti baterai sebagai komponen paling bermasalah dari segi biaya, daya tahan, dan dampak lingkungan.
- **Isu infrastruktur (SPKLU)** juga banyak dibahas, publik ragu terhadap kesiapan dan pemerataan Stasiun Pengisian Kendaraan Listrik Umum di berbagai daerah Indonesia.
- **Persepsi merek** bervariasi:
  - Sentimen **positif** dominan: **BYD**
  - Sentimen **negatif** dominan: **Tesla** dan **Wuling**
  - Sentimen **netral** dominan: **Hyundai** dan **Toyota**
  - Kurang mendapat sorotan publik: **Honda, BMW, Nissan**
- Masih banyak keraguan publik terhadap kendaraan listrik yang mencakup biaya operasional, isu lingkungan dan keselamatan, hingga kesiapan infrastruktur dan regulasi yang menunjukkan perlunya **edukasi, transparansi, dan percepatan pembangunan ekosistem kendaraan listrik** secara menyeluruh.
- Mayoritas masyarakat menilai ada **kontradiksi** antara branding kendaraan listrik sebagai solusi ramah lingkungan dengan realita produksi baterai di Indonesia yang masih bergantung pada nikel, bahan yang dikenal merusak lingkungan pada proses ekstraksinya.

## 🛠️ Tools & Teknik

- Sentiment Analysis
- Topic Modeling (Clustering)
- Data Visualization

## ✍️ Kesimpulan

Meskipun kendaraan listrik didorong sebagai solusi transportasi ramah lingkungan, persepsi publik di media sosial masih didominasi oleh sentimen negatif — terutama terkait biaya dan dampak lingkungan dari baterai serta kesiapan infrastruktur. Temuan ini menjadi masukan penting bagi pemangku kebijakan dan industri untuk memperkuat edukasi publik, transparansi rantai pasok baterai, dan percepatan pemerataan infrastruktur pengisian daya.

**Kata Kunci**
1. Kelemahan dan kelebihan kendaraan listrik
2. Kendaraan listrik ramah lingkungan
3. Subsidi pemerintah untuk kendaraan listrik: layak atau tidak?
