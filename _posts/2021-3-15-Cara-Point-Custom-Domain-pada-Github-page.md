---
layout:  post
title:  Cara Point Custom Domain pada Github page
tags:  jekyll domain
permalink:  /cara-point-custom-domain-pada-github-page
toc:  true
toc-label:  "Senarai Kandungan"
---
Dikemaskini pada 15/3/2021

Assalamualaikum dan salam sejahtera kepada pembaca.
Pada post kali ni aku akan akan menerangkan cara 
yang mudah untuk point custom domain name pada github
page kita.

Sebagai contoh : daripada **rinopuji.github.io** ke **rinopuji.com**.

****

**Senarai Kandungan**
* TOC
{:toc}

****
##  Domain Name

Pertama sekali nak tukar custom domain name mestilah
dah ade domain name.Pastikan kita mempunyai permission
untuk tukar **Host Record** value pada domain tersebut.

##  Jenis Domain
**Jenis Domain** yang aku maksudkan ialah **Apex Domain** dan 
**Sub Domain**.Rilex,jangan pening kepale.

**Apex Domain** ialah _root domain_ atau _naked domain_.
Domain yang tiada nama di depan.Senang cerita 
aku panggil **Main Domain** atau dalam bahasa
melayu **Domain Utama** Sebagai contoh,

* gali.com
* kucing.com
* gagak.com

**Sub Domain** pula ialah domain yang ada nama tambahan 
di depan.

* www.gali.com
* blog.kucing.com
* team1.gagak.com

Jadi bagi situasi aku, **rinopuji.com** ialah **apex domain**,
manakala **www.rinopuji.com** pula ialah subdomain.

> **www** juga termasuk dalam **sub domain**.

Info kat atas ni sangat penting.Sekiranya kita nak point
**Main Domain** pada github page kita (dalam kes aku 
**rinopuji.com**),aku juga perlu point **www.rinopuji.com** (**Sub Domain**) 
pada page github tersebut.

Ade orang suke type direct **website.com**,dan ade 
juga yang suke type **www.website.com**.

Tujuan utama kita point **Main Domain** dan **Sub Domain**
(_www_) pada github page kita ialah untuk memastikan tiada masalah sekiranya
dua situasi di atas berlaku.

Aku akan terangkan 2 cara.Pertama,sekiranya kita
ingin menggunakan **Main Domain** dan kedua,sekiranya
kita ingin menggunakan **Sub Domain** (contoh : _blog.website.com_,
_amir.nura.com_,_kedai.kucing.com_).

## Point "Main Domain" 



