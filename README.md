<h1 align="center">
    KTP-OCR
</h1>

<p align="center">
  <strong>Kartu Tanda Penduduk Extractor</strong><br>
  An attempt to create a production grade KTP extractor.
</p>

<div align="center">
    <img src="https://rossrightangle.files.wordpress.com/2012/05/e-ktp-contoh.jpg">
</div>

**KTP-OCR** is a open source python package that attempts to create a production grade KTP extractor. The aim of the package is to extract as much information as possible yet retain the integrity of the information.

---
<h2 style="font-weight:800;">Requirements</h2>
You will need tesseract with indonesian language support installed in your system. 

```console
$ pip install tesseract-lang
```
---

<h2 style="font-weight: 800;">🚀 How to launch</h2>

```console
$ git clone https://github.com/MRendiks/KTP-Indoensia-OCR.git
$ cd KTP-OCR
$ pip install -r requirements.txt
$ python3 ocr.py <path-image>
```
---

<h2 style="font-weight: 800;">📝 Note from Yuka</h2>

* I am actively working to create a python package out of the main `ocr.py`. For now you can play with the old script.
* I have an idea to verify the address information from the KTP via external service (Google Maps) which can be used to further standardized Indonesian address' information.
