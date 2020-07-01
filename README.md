<div align = "center">

# **Deteksi dan Klasifikasi Alih Fungsi Lahan Sawah Berdasarkan Citra Satelit dengan Implementasi *Deep Learning***
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)
</div>

<br>

## **Deskripsi**

<div align = "justify">

Penelitian ini dilakukan untuk mengembangkan model _deep learning_ yang mampu mendeteksi lahan sawah dari citra satelit, mengidentifikasi alih fungsi lahan sawah dan mengklasifikasikan lahan sawah yang mengalami alih fungsi ke dalam jenis tutupan lahan lainnya. Pada penelitian ini untuk memenuhi tujuan tersebut dikembangkan dua jenis model. Model pertama untuk mendeteksi lahan sawah dan model kedua untuk mengklasifikasikan lahan sawah yang mengalami alih fungsi ke dalam jenis tutupan lahan lainnya.

Model untuk mndeteksi lahan sawah dikembangkan dengan arsitektur **_U-net Neural Network_** sedangkan model untk klasifikasi tutupan lahan dikembangkan dengan arsitektur **_Convolutional Neural Network_**. Kedua model ini dikembangkan dengan bahasa pemrograman [Python](https://www.python.org/).

Model dengan arsitektur **_U-net Neural Network_** dapat mendeteksi lahan sawah dengan performa yang baik, dengan model tersebut kita dapat mengidentifikasi alih fungsi lahan sawah di suatu daerah pada peiode tertentu. Kemudian sawah yang mengalami alih fungsi dapan diklasifikasikan ke dalam jenis tutupanlahan lainnya dengan model **_Convolutional Neural Network_**. Kedua Model ini dapat diimplementasikan untuk melakukan monitoring terhadap alih fungsi lahan sawah.

</div>

## **Prasyarat**

<div align = "justify">
Terdapat beberapa hal yang perlu dipersiapkan dalam melakukan penelitian ini diantaranya:

* Environment Python
* IDE atau Code Editor untuk bahasa pemrograman Python
* Akun [Google Earth Engine](https://earthengine.google.com/)
* Tools pengolahan data geospasial, seperti  [Q-Gis](https://qgis.org/) atau [Arc-Gis](https://www.arcgis.com/)


Untuk Environment dan IDE atau Code Editor Python kita dapat menggunakan Google Colaboratory &nbsp;&nbsp;&nbsp;&nbsp;
[![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)

</div>

## **Muatan**

<div align = "justify">
Pada project ini terdapat empat (4) direktori utama yang terkait penelitian sebagai berikut:

* [SAMPLE SATELLITE IMAGERY]()
  
  Direktori ini memuat beberapa contoh citra satelit yang digunakan dalam pembangunan model pada penelitian ini seperti:

  * [LANDSAT 8]() - [ Citra satelit Landsat 8 Surface Reflectance ]
  * [SENTINEL 2]() - [ Citra satelit Copernicus Sentinel 2 ]
  * [DATASET TRAINING MODEL SEGMENTASI (UNET)]() - [ Training Dataset dalam pembangunan model deteksi sawah ]
  * [DATASET TRAINING MODEL KLASIFIKASI TUTUPAN LAHAN (CNN)]() - [ Training Dataset dalam pembangunan model klasifikasi tutupan lahan ]
  <br>
  
* [NOTEBOOK MODELLING]()
  
  Direktori ini memuat script Python yang digunakan untuk pengumpulan data dan pembangunan model dalam penelitian ini.

* [SERIALIZED MODEL]()
  
  Direktori ini memuat model deteksi sawah dan model klasifikasi tutupan lahan yang telah diserialisasi dalam format file ( h5 ).

* [DASHBOARD]()
  
  Direktori ini memuat dashboard berbasis web yang dirancang untuk mendemonstrasikan implementasi kedua model yang telah dibangun dalam monitoring alih fungsi lahan sawah.

</div>

## **Author**



## **Acknowledgments**