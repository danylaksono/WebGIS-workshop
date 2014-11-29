.. _leaflet:

***************************
Peta Online dengan Leaflet
***************************

.. raw:: html

   <hr></br>

Tentang Leaflet
================

**LeafletJS** merupakan library atau kumpulan fungsi berbasis Javascript yang
digunakan untuk menampilkan peta interaktif pada halaman web. Leaflet menyediakan Map API (Application Programming Interface) yang memudahkan web developer untuk menampilkan peta berbasis *Tile* pada halaman web. Pengguna peta juga dapat berinteraksi dengan menggunakan perangkat tertentu yang telah disediakan oleh leaflet.

Dibandingkan Map API lainnya seperti OpenLayer, GMAP API, ArcGIS JS API atau Mapbox API, Leaflet memiliki keunggulan dalam kecepatan akses dan ukuran berkas yang kecil. Meskipun memiliki ukuran berkas yang lebih kecil, Leaflet memiliki fungsi web mapping yang cukup lengkap. Fungsionalitas Leaflet ini dapat ditingkatkan dengan menggunakan Plugin yang tersedia secara cuma-cuma.

Memanggil Leaflet
=====================

Sebagaimana pada bagian Bootstrap, Anda dapat menggunakan LeafletJS dengan dua cara:

1. Mengunduh file yang berisi library LeafletJS dari http://leafletjs.com/download.html
2. Menggunakan CDN (Content Delivery Network) yang menyimpan kode Leaflet

.. highlight:: html

Kode Leaflet yang tersimpan pada CDN dapat anda akses dengan cara berikut::

        <link rel="stylesheet" href="http://cdn.leafletjs.com/leaflet-0.7.3/leaflet.css" />
        <script src="http://cdn.leafletjs.com/leaflet-0.7.3/leaflet.js"></script>


Berlatih dengan Leaflet
=======================

1. Buatlah sebuah file baru pada repository lokal anda sebagaimana pada latihan sebelumnya. Beri nama file ini sebagai ``latihan-leaflet.html``.

2. Isikan kode berikut pada file yang telah anda buat:

.. literalinclude:: ./_static/webpage/latihan-leaflet.html
   :linenos:

3. Lakukan ``git push`` sebagaimana sebelumnya

4. Buka web page anda dan arahkan ke file yang baru anda buat, misalnya ``http:://username.github.io/latihan-leaflet.html``


Komponen Leaflet
=======================

Komponen Leaflet terdiri dari beberapa elemen sebagai berikut:

* Tipe Raster (TileLayer dan ImageOverlay)
* Tipe Vektor (Path, Polygon, dan tipe lain yang spesifik seperti Circle)
* Tipe Grup (LayerGroup, FeatureGroup and GeoJSON

Leaflet dapat mendukung berbagai format data untuk ditampilkan pada peta online, seperti GeoJSON, KML, CSV, GPX dan WKT. Data spasial yang disimpan pada Leaflet dapat disajikan dalam bentuk layanan WMS atau static JSON. Tidak ada dukungan untuk penyajian data spasial melalui WFS maupun GML.


What's Next?
=============

Anda telah mempelajari mengenai Github, Bootstrap, dan Leaflet. Ketiga komponen ini dapat digunakan sebagai batu loncatan untuk membuat sebuah web map. Tentunya masih banyak fungsi geospasial yang dapat disajikan melalui internet dengan berbagai perangkat lain. Semakin banyak anda berlatih, maka semakin banyak yang dapat anda temukan. Selamat berlatih!



.. _ref-leaflet:

Rujukan
========

* http://leafletjs.com/examples.html
* https://leanpub.com/leaflet-tips-and-tricks/read  **(RECOMMENDED)**
* https://github.com/buche/leaflet-openweathermap
* http://map.comlu.com/openweathermap/


.. raw:: latex
   
   \pagebreak[4]
