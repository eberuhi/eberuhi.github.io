---
title: Algorithmic Stoicism
author: Erk
layout: page
permalink: /essays/algorithmic-stoicism/
excerpt: Stoacı felsefenin dayanıklılık ilkeleri, tek kişilik yazılım projelerinde nasıl algoritmik stratejilere dönüşür?
---

## Stoacı temel, deterministik karar

Stoacılık "kontrol edebildiğini güçlendir, edemediğini kabullen" der. Tek başına kod yazarken aslında aynı prensiple hareket etmek zorundayız: girdileri kontrol eder, çıktıyı kabul ederiz. Bir 2D puzzle oyununun fizik motoru, oyuncu input'u geldikten sonra deterministik kurallar uygular. Oyunun çökmemesi için daha fazla enerji harcamanın yolu, dışsal gürültüyü (API hataları, cihaz farkları) kabul edip kodun dayanabileceği tamponlar tasarlamaktır.

## Negatif görselleştirme = kaos testi

Stoacılar her sabah kötü ihtimalleri zihinde prova ederdi. Biz bunu "chaos monkey" ile yapıyoruz. Üretime çıkmadan önce oyunun kritik sahnelerinde bilinçli olarak hata üret, network gecikmesi simüle et. Bu pratik, bug raporunu duygusal bir tokat olmaktan çıkarıp ölçülebilir bir veri noktasına çevirir.

## Erdemli kod ve sürdürülebilir döngü

Stoacı erdemlerin üçlüsü (bilgelik, cesaret, ölçülülük) kod kalitesi metriklerine benzetilebilir. *Bilgelik* = önce öğren, sonra optimize et. *Cesaret* = acı veren refactorları erteleme. *Ölçülülük* = feature creep'i dengele. Bu üçlü olmadan tek kişilik bir oyun projesi finansal hedefe ulaşamaz.

## Finansal bağımsızlık için zihinsel buffer

Stoacılar dış serveti kontrol edemeyeceğini bilirdi. Mobil oyun ekonomisinde de CPI, eCPM çarpanı senin elinde değil. Sen sadece retention ve core loop üzerinde emek gösterebilirsin. Kâr eğrisi yavaşsa da planı takip etmek Stoacı disiplin gerektirir; aynı disiplin yatırımcıya güven verir.
