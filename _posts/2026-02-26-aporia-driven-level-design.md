---
title: Aporia-Driven Level Design
author: Erk
layout: page
permalink: /essays/aporia-driven-level-design/
excerpt: Aporia yani "yol bulamama" hali, puzzle tasarımında bilinçli kullanılabilir mi?
---

## Felsefi çıkmazdan oyun mekaniğine

Sokratik diyalogda aporia, cevap verilemeyen soru anıdır. Oyuncu da bazen çözüm yolunu göremez. Bunu başarısızlık olarak değil, metodolojik araç olarak tasarlayabilirsin. Level 7'de oyuncuya bilinçli belirsizlik sun, Level 8'de bu belirsizliği çözme araçları ver. Böylece zihinsel ödül iki katına çıkar.

## Bilişsel yük yönetimi

Aporia yaratırken bilişsel yükü kontrol et. Miller'ın 7±2 kuralına göre, oyuncuya aynı anda en fazla birkaç değişken göster. Belirsizlik bilgi kalabalığından değil, bilgi eksikliğinden gelsin. Bu, puzzle'ı adil kılar.

## Teknik uygulama

- Tutorial'da *negative space* kullan: Oyuncunun ihtiyaç duyduğu bilgiyi gizle, ipucu sistemiyle ortaya çıkar.  
- Level verilerini JSON'da `requires_reveal` flag'iyle işaretle.  
- Telemetry'de "aporia süresi"ni (çözüm öncesi idle zaman) ölç.

## Duygusal sonuç

Oyuncu aporiadan çıkınca minik bir aydınlanma yaşıyor. Bu anı glow efektleri, müzik geçişi ve haptic feedback ile güçlendir. Aporia'yı cezaya değil, katharsise dönüştür.
