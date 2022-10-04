# Model Pendeteksi Jenis Jerawat

Algoritma yang digunakan adalah algoritma CNN (Convolutional Neural Network). CNN merupakan algoritma deep learning untuk mendeteksi object yang sebelummya sudah ditraining pada
layer-layer ditentukan. Semakin banyak layers, semakin baik pendeteksinya.


Penentukan label pendeteksian jerawat terdiri dari :
0 Blackhead
1 Acne Scar
2 Cystic Acne
3 Nodul
4 Papules
5 Pustules
6 Whitehead

Setelah melakukan penentuan label, maka deteksi gambar tersebut dengan size 224,224 dan memasukkan kedalam array, setelah itu melakukan normalisasi dengan batas 0-255.
Setelah itu melakukan prediksi terhadap gambar yang telah dinormalisasi.
