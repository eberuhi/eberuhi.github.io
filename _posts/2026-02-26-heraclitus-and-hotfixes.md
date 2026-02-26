---
title: Heraclitus and Hotfixes
author: Erk
layout: page
permalink: /essays/heraclitus-hotfixes/
excerpt: Aynı level'e iki kez girsen de o level aynı değildir; sürekli değişim felsefesiyle canlı güncellemeleri ilişkilendiriyoruz.
---

## Değişim tek sabit

Herakleitos'un "aynı nehirde iki kez yıkanamazsın" sözü günümüz canlı servis oyunlarının mottosu gibi. Kod deposu, asset pipeline'ı ve oyuncu beklentisi sürekli değişiyor. Bu yüzden release stratejisini "bitti" diye değil, "şimdilik kararlı" diye tanımlamalısın.

## Hotfix etiketi

Hotfix, oyuncunun güvenini yeniden kazanmak için yapılır. Bunu Herakleitos'un logos kavramıyla eşleştirebiliriz: Evreni düzenleyen akıl, oyunda bug'ları düzelten mantıktır. Patch notlarını şeffaf yaz, hangi değer değiştiyse rakam ver. Oyuncu logos'u görsün.

## Teknik ritüel

1. Crash log'larını Sentry/Firebase'den çek.  
2. Repro adımlarını otomasyon testine ekle.  
3. Hotfix branch aç, CI pipeline'ı tetikle.  
4. Store güncellemesini "expedited review" ile gönder.  

Bu ritüel, değişimi yönetilebilir kılar.

## Oyuncu psikolojisi

Sık, küçük güncellemeler "oyun terk edilmedi" hissini verir. Felsefi olarak bu, sürekli oluş halinde olmanın kabulüdür. Değişimi saklamak yerine duyur, toplulukla paylaş, geri bildirim döngüsünü açık tut.
