---
title: Benevolent Sandboxes
author: Erk
layout: page
permalink: /essays/benevolent-sandboxes/
excerpt: SandBox denen deney alanları oyuncunun ahlaki sezgisini de kod kalitesini de besleyebilir.
---

## SandBox kavramının iki yüzü

Bilgisayar biliminde sandbox, kodu izole edip sistemi korur. Oyuncu açısından sandbox, deney alanıdır. Bu iki anlamı bir araya getirdiğinde "iyicil sandbox" ortaya çıkar: oyuncu yeni strateji denerken cihaz risk altında olmaz, veriler korunur, oyun ise öğrenme laboratuvarına dönüşür.

## Kantçı çerçeve

Kant'ın kategorik imperatifi, eylemin evrensel yasa olabilmesini şart koşar. Oyunda sandbox modunu tasarlarken oyuncunun keşfettiği exploit'lerin ana oyunu bozmasına izin vermemek gerekir; aksi halde yasa kirlenir. Sandbox'ı "testnet" gibi düşün, bulguları raporlayan oyuncuya oyun içi ödül ver.

## Mühendislik uygulanışı

- Ayrı save slotu oluştur.
- Fizik parametrelerini slider ile değiştirilebilir yap.
- Hata raporlarını otomatik toplamak için sandbox moduna özel telemetry ekle.

Bu setup, gerçek build'i kirletmeden yeni level fikirleri doğrulamana izin verir.

## Oyuncu güveni

Oyuncu sandbox'a girdiğinde açıkça "Burada ilerleme kaybı olmayacak" mesajını görsün. Şeffaflık güven oluşturur; güven, monetizasyonu uzun vadede yükseltir.
