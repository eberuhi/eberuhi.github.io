---
title: Simüle Edilmiş Sokratik Diyaloglar
author: Erk
layout: page
permalink: /essays/socratic-dialogues/
excerpt: Oyun içi yapay zekâ karakterleri oyuncuyu soru-cevapla düşünmeye zorladığında ortaya yeni bir eğitimsel loop çıkıyor.
---

## Soru soran NPC mantığı

Sokrates muhatabını sorularla sıkıştırır, cevapları kendisinin bulmasını sağlar. Aynı modeli 2D puzzle oyununun tavsiye sisteminde kullanabiliriz. NPC ipucu vermeden önce "Hangi vektörü sabitlemelisin?" gibi mikro sorular sorduğunda oyuncu düşünmeye devam eder. Bu, metakognisyonu tetikler.

## Diyalog motoru için teknik çerçeve

- **Durum makinesi:** Her sorunun tetiklendiği koşullar (ör. oyuncu 3 kez başarısız oldu).  
- **Bilgi grafı:** Sorular, oyunun kavramlarına bağlanır (momentum, süre, kaynak).  
- **Doğal dil varyasyonları:** Aynı soruyu üç farklı cümleyle sorarak monotonluğu kır.

Basit bir YAML dosyasıyla bu diyaloğu tanımlayıp oyun içinde ScriptableObject'e çevirebilirsin.

## Pedagojik kazanç

Sokratik yöntem, bilgi aktarımından çok düşünme alışkanlığı kazandırır. Mobil oyuncular bile 30 saniyelik seanslarda bu yöntemi deneyimleyebilir. Unity UI'da küçük diyalog balonları aç, oyuncunun "evet/hayır" seçimlerini logla. Bu veriler, hangi kavramın anlaşılmadığını gösterir.

## Etik sınır

Oyuncuyu sorgularken yargılayıcı dil kullanma. Amaç, "sen anlamıyorsun" demek değil, "sence bir sonraki hamlede hangi objeyi sabitlemelisin?" gibi nazik yönlendirmeler yapmak. Didaktik ton yerini merak uyandıran tona bırakmalı.
