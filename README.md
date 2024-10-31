<h1 align="center"> NLP With HuggingFace Transformers </h1>
<p align="center"> Berisi tentang pipeline dari HuggingFace Transformers untuk keperluan NLP (Natural Language Processing)</p>

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">

</div>

<h2 align="center"> Analisis Pipeline Transformers pada HuggingFace </h2> 

- <strong>Zero Shot Classification</strong> termasuk ke bagian "Klasifikasikan ke seluruh kalimat" dimana dia mencari label yang paling cocok dengan prompt atau input yang dikasih dan memberikan score tertinggi kepada label tersebut. zero shot classification merupakan salah satu pipeline yang menggunakan model yang telah di "pretrained" atau dilatih untuk mengklasifikasikan suatu kalimat ke label yang belum pernah dilihat oleh model. Pada prompt yang saya berikan mungkin kata "semiconductor" ditemukan sangat berhubungan dengan label "electronic" sehingga pada label "electronic" model memberikan score tertinggi kepada label "electronic"

- <strong>Text Generation</strong> seperti namanya memiliki peran untuk menghasilkan/melanjutkan teks dari input prompt yang telah diberikan, secara default menggunakan model gpt2. Text generation ini termasuk kategori membuat konten teks dalam NLP.

- <strong>Fill Mask</strong> berfungsi untuk mengisi kata yang kosong di tengah kalimat, menggunakan model distilroberta-base memberikan score terhadap label kata yang dianggap cocok seperti pada contoh output yang diberikan adalah "cheese" dan "basil". Termasuk kategori membuat konten teks dalam NLP.

- <strong>NER(Named Entity Recognition)</strong> mengklasifikasikan suatu kata dalam teks yang diberikan ke salah satu label ini PER: Nama orang, LOC: Lokasi atau tempat, ORG: Organisasi, MISC: Entitas lain seperti acara, merek, atau produk. Pada contoh dapat mendeteksi konteks orang dalam kalimat dan lokasi yaitu "Roland" dan "Indonesia". NER ini termasuk dalam kategori klasifikasi setiap kata.

- <strong>Question Answering</strong> menerima prompt input yang berupa konteks yaitu data yang diperlukan untuk menjawab pertanyaan yang juga merupakan salah satu prompt input. Seperti pada contoh kita memberikan konteks tentang makanan dari spanyol dan kita tanya apa itu paella, dan dijawab oleh model dengan "a classic Spanish dish of rice". Termasuk ke dalam kategori ekstrak jawaban dari teks.

- <strong>Sentiment Analysis</strong> seperti namanya menganalisis sentimen atau perasaan pada teks input prompt. Dari input prompt yang diberi diberikan sentimen negatif mungkin karena kata "need" dan "replace". Termasuk ke dalam kategori klasifikasikan seluruh kalimat.

- <strong>Summarization</strong> seperti namanya merupakan bagian NLP yang digunakan untuk meringkas teks input sambil mempertahankan informasi penting dan makna keseluruhan dari teks awal yang lebih panjang. Termasuk dalam kategori membuat kalimat baru dari teks masukan.

- <strong>Translation</strong> atau translasi dalam Bahasa Indonesia merupakan bagian NLP yang digunakan untuk menerjemahkan teks dari satu bahasa ke bahasa yang berbeda. Pada contoh akan menerjemahkan dari Bahasa Indonesia ke Bahasa Inggris. Termasuk dalam kategori membuat kalimat baru dari teks masukan.
Dst...
