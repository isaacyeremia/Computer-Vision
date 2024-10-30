pada klasifikasi gambar untuk mengindentifikasi jenis kelamin, sistem menggunakan algoritma pembelajaran mesin untuk membedakan gambar wajah laki-laki dan perempuan

Dataset CelebA dari kaggle dan ukuran dataset : 52.000 gambar label male dan female
preprocessing data yang dilakukan yaitu hapus data duplikat, balancing data, dan augmentasi
traning model menggunakan Hyperparameter yaitu Adam optimizer, loss function: Sparse categorical Crossentropy
traning model menggunakan Epoch : 5, Learning Rate : 0,00001
