
# XSS ( Cross Site Scripting )

Cross-Site Scripting (XSS) adalah kerentanan keamanan yang memungkinkan attacker
menyisipkan kode berbahaya ( malicius ) yang berbentuk Javascript.
untuk nama sendiri kenapa disingkar menjadi XSS bukan CSS karena singkatan CSS sudah ada
yang dimana CSS pertamakali di usulkan pada oktober tahun 1994 oleh Hakon Wium Lie.


## 📒 Sejarah

Sejarah xss tak lepas dari awal berdirinya web ( WWW ) tahun 1996, saat e-commerce mulai marak di dunia internet yang masih muda itu
ketika situs web keren di bingkai menggunakan HTML, bahasa javascript muncul mengubah lanscap dunia web, dimana web yang flat
berubah menjadi web yang mempunyai efek-efek menarik. namun munculnya javascript di sambut bahagia oleh kalangan peretas yang
segera menemukan dunia baru untuk di jelajahi.
 
Serangan XSS pertama kali di publikasi oleh aleph1 ( Apleph One) pada 17 Oktober 1997 yang mempublikasikan serangan XSS di internet explorer
( https://seclists.org/bugtraq/1997/Oct/85 )




## 🏷️ Jenis XSS Attack

- Presistent XSS ( Stored XSS )

Presistent XSS adalah jenis serangan xss yang bersifat permanen dan dapat berakibat pada seluruh pengguna

- Non-Presistent XSS

Non-Presistent XSS adalah Jenis serangan yang bersifat non permanen, serangan ini akan hilang ketika dilakukan refresh atau semacamnya


## 🪲 Deteksi Bug XSS

dengan memberikan script 

```Javascript
<script>alert('This Vuln')</script> 
```
![image.png](https://miro.medium.com/max/720/1*qSouyC55mdl0KDUTJRoXPQ.jpeg)

jika muncul popup berarti vuln


## 🔗 Bug Bounty XSS 

**GOOGLE**
- ["XSS vulnerabilities in Google Cloud, Google Play could lead to account hijacks"](https://portswigger.net/daily-swig/xss-vulnerabilities-in-google-cloud-google-play-could-lead-to-account-hijacks) - *JesscaHaworth*
- ["XSS on Google{5.000$}-Google Vulnerability Reward Program (VRP)"](https://sites.google.com/site/bugbountybughunter/home/stored-xss-in-google-image-search) - *cem yld*
- ["Another Vulnerability"](https://github.com/xdavidhu/awesome-google-vrp-writeups)

**EBAY**
- ["Persistent (Stored) DOM XSS on ebay.com domain"](http://www.korznikov.com/2016/02/persistent-stored-dom-xss-on-ebaycom.html) - *nopernik*

**NASA**
- ["XSS NASA Sub Domain"](https://adelittle.medium.com/xss-nasa-sub-domain-308266dfd670) - *adelittle*

**PAYPAL**
- ["Finding DOM Polyglot XSS in PayPal the Easy Way"](https://portswigger.net/research/finding-dom-polyglot-xss-in-paypal-the-easy-way) - *Gareth Heyes*

**Facebook**
- ["Facebook DOM Based XSS using postMessage"](https://ysamm.com/?p=493) - *Samm0uda*
- ["Another Vulnerability"](https://github.com/jaiswalakshansh/Facebook-BugBounty-Writeups)


## Kesimpulan
XSS adalah serangan yang berpotensi untuk menjadi salah satu serangan yang paling berbahaya untuk sebuah situs website. 

Hal ini tentu bisa menjadi konsekuensi yang mungkin tidak akan bisa pemilik website manapun menerimanya
