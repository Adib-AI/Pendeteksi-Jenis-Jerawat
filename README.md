# Model Pendeteksi Jenis Jerawat

Algoritma yang digunakan adalah algoritma CNN (Convolutional Neural Network). CNN merupakan algoritma deep learning untuk mendeteksi object yang sebelummya sudah ditraining pada
layer-layer ditentukan. Semakin banyak layers, semakin baik pendeteksinya.


Penentukan label pendeteksian jerawat terdiri dari : <br>
0 -> Blackhead <br>
1 -> Acne Scar <br>
2 -> Cystic Acne <br>
3 -> Nodul <br>
4 -> Papules <br>
5 -> Pustules <br>
6 -> Whitehead <br>

Setelah melakukan penentuan label, maka deteksi gambar tersebut dengan size 224,224 dan memasukkan kedalam array, setelah itu melakukan normalisasi dengan batas 0-255.
Setelah itu melakukan prediksi terhadap gambar yang telah dinormalisasi.
