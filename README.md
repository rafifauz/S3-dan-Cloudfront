# S3-dan-Cloudfront
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#S3">S3</a>
      <ul>
        <li><a href="#Tahap-tahap">Tahap-tahap</a></li>
      </ul>
    </li>
    <li><a href="#Cloudfront">Cloudfront CDN</a></li>
  </ol>
</details>


<!-- S3 -->
## S3
Sebelum melakukan setup pada cloudfront, pertama kita harus menyiapkan erlebih dahulu ebuah bucket di Amazon S3. Karena cloudfront sendiri menggunakan S3 ucket untuk penggunaannya.

Tahap-tahapnya:
* Buat Bucket pada AWS S3
	<img src="Image/a.png" width="100" height="100">
* Upload file index.html dan ubah permisionnya menjadi public
	![](Image/b.png)

<!-- Cloudfront -->
## Cloudfront
* cd 

