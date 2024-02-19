---
layout:  post
title:  Cara bermain Monopoly Go v1.17.0 (Predetermined)
tags:  android monopolygo
last_modified_at:  2024-2-18
---
Seperti mane yang semua sedia tahu,untuk update version v1.17.0,roll yang sebelum ni "Random" dah bertukar kepada "Predetermined".Tak kisah la berapa banyak kali pun kita reroll/reset,result yang kita akan dapat tidak berubah.Setiap multiplier mempunyai result sendiri yang tetap.

Saye akan share beberapa cara basic supaya anda dapat kembangkan sendiri mengikut gaya permainan anda.

**TABLE OF CONTENT**
* TOC
{:toc}

## Topik 1 : Cara simple max multiplier > low multiplier
Cara paling simple tanpa melibatkan apa-apa pengiraan ialah :

1. Roll dengan "Max multiplier" sebagai contoh x100.
2. Jika resultnya menguntungkan,save location/tiles terkini.
3. Jika resultnya merugikan,kita akan "reroll/reset" untuk kembali ke tempat asal.
4. Roll dengan "Low Multiplier" untuk pergi ke location/tiles lain dan repeat semula ke "1".

Kita akan ulang 4 step ni sampailah event siap.Sila rujuk video di bawah sebagai contoh :

Contoh 1 :
<div class="embed-container"><iframe width="963" height="1712" src="https://www.youtube.com/embed/a5V3VtaMn30" title="Contoh 1 untuk monopolygo v1.17.0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>

Contoh 2 : 
<div class="embed-container"><iframe width="963" height="1712" src="https://www.youtube.com/embed/PhOTKfMYJ_s" title="Contoh 2 untuk monopoly go v1.17.0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>

==============
TOPIK 1 TAMAT 
==============

## Topik 2 : Cara basic untuk tahu kemana kita akan landing
Saya akan explain the basic macam mana kita nak buat sedikit pengiraan untuk mengetahui ke mana kita landing.Anda boleh pelbagaikan atau gayakan lagi mengikut cita rasa anda.

> Bacalah secara perlahan.....Tiada apa yang perlu di kejar untuk game ni...
hari ni tak sempat,boleh sambung esok.....

Formula untuk basic predetermined terkini ni simple je sebenarnyer :

***SecondRoll (firstMultiplier) + FirstRoll (secondMultiplier) = Jumlah petak/tiles yang anda akan landing.***(Sila gunakan kembali (first Multiplier) pada roll yang ke-3.

> Relax jangan pening....teruskan membaca secara perlahan....lepas tengok contoh anda akan paham....

Untuk memudahkan anda,sila rujuk gambar di bawah.Paling penting kena ingat "kiraan" petak/tiles bermula "di depan" kedudukan terkini token anda sebelum anda roll.

![gambar1_19_2_2024](https://lh3.googleusercontent.com/pw/ABLVV85oKuJqApOPBnuGdaUOPRpTtk5MTDKnDNNSnYJCmIVkJlqK0tkjUt3vygNxb7pVzlSYUWFCTX3JqbhlLzoF2uiHETPi7e9TTruwSw5ma7oo4xSd23c=w2400){:.centered}

> Anda tak perlu nak lukis/marking macam saye buat kat atas....saye hanya nak anda paham ape yang saye maksudkan dengan kiraan petak...

Untuk stepnya :
1. Kita akan cari dulu ***result untuk SecondRoll(firstMultiplier)***.
    - Gune Multiplier yang paling tinggi,***x100*** atau kali ***x1000***(sekiranya ada HR) dan Roll 2 kali.
    - Ingat result Roll yang kedua.
    - Reroll/reset untuk kembali ke tempat asal.
    - Sila rujuk video di bawah :
<div class="embed-container"><iframe width="963" height="1712" src="https://www.youtube.com/embed/sGyO_J7Y-J0" title="Video 3 monopolygo v1.17.0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>

Dalam video result roll ke-2 untuk x100 ialah ***7***.Ingat nombor ni.

2. Next kita cari pula result untuk FirstRoll(secondMultiplier).
    - Roll x1 sekali sahaja dan ingat resultnya.
    - Rujuk video di bawah :
 
<div class="embed-container"><iframe width="963" height="1712" src="https://www.youtube.com/embed/8oDvwr4_FJ0" title="Video 4 : MonopolyGo v1.17.0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>

    - Dalam video di atas result untuk FirstRoll(secondMultiplier) ialah ***8***.
    
Kita dah dapat nilai bagi 
- secondRoll(firstMultiplier) = 8 (x100)
- firstRoll(secondMultiplier) = 7 (x1)
- 8 + 7 = ***15***.

Selepas sehaja kita roll x1,sekiranya kita tukar kembali multiplier kepada x100,kita akan beralih ***15*** petak dari kedudukan asal kita.

![gambar2_19_2_2024](https://lh3.googleusercontent.com/drive-viewer/AEYmBYQryj6-nz1o1mFoKGFUCTMWz-akf8qOUMLrc46SOYXw0E-9-JptCOqt2dceQcQqY2hHAfH7tMUaF_zc78A8sUJ-aROxaw=s1600){:.centered}

> Jangan pening sila lihat full video di bawah :
<div class="embed-container"><iframe width="963" height="1712" src="https://www.youtube.com/embed/fjUkjm59gOM" title="Video 5 : MonopolyGo v1.17.0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>

Sekarang dah nampak kan ? Tak nampak lagi ? Saye bagi lagi satu contoh video.....

 
<div class="embed-container"><iframe width="963" height="1712" src="https://www.youtube.com/embed/1tKoP2EkVwE" title="Video 6 : MonopolyGo v1.17.0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>

Seperti mana kita tahu,setiap multiple mempunyai result yang berbeza.Bila mana tengok video di atas ni,mungkin ade yang akan cakap :

> Ini jer ? Baik men hentam je....Macam lagi buang mase je....

Sabar.....ni hanya sekadar basic di mana kita hanya 1-2 langkah sahaja.Bila mana anda dah paham berkaitan basic ni,next saye akan explain macam mana anda nak "target" satu tempat yang anda nak.

==============
TOPIK 2 TAMAT
==============

*Bersambung.....*