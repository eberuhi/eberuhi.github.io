---
title: Memory Palaces and Vector Databases
author: Erk
layout: page
permalink: /essays/memory-palaces-vector-dbs/
excerpt: Antik hafıza teknikleriyle modern vektör veritabanlarının benzer yolları var.
---

## Antik metod: loci tekniği

Roma hatipleri konuşmalarını hatırlamak için hayali saraylar kurar, her odada bir fikir saklarlardı. Bu teknik, bilgiyi uzaysal bağlamlara bağlayarak hatırlamayı kolaylaştırır. Puzzle oyunu tasarlarken level akışını da bir hafıza sarayı gibi kurgulayabilirsin: her mekanik farklı bir "oda"ya yerleştirilir.

## Vector DB eşleşmesi

Bilgisayar biliminde benzerlik aramak için vektör uzayına gömeriz. Bir level'in telemetri verilerini embedding'e çevirip "benzer sıkışma noktaları"nı bulmak, oyuncuların nerede takıldığını görmeni sağlar. Bu, loci tekniğinin dijital karşılığıdır: bilgi odaları = vektör kümeleri.

## Tasarım süreci

1. Her level için ana kavramları (kütle, zaman, kaydırma) etiketle.  
2. Bu etiketleri one-hot vektör yerine SentenceTransformer gibi modelle göm.  
3. Pinecone/Weaviate gibi hafif bir vector store'da tut.  
4. Yeni level üretirken önce benzerleri getir, varyasyonları incele.

## Oyuncu deneyimi

Hafıza sarayları oyuncuya "ben bunu daha önce de görmüştüm" hissi verir. Vector DB destekli seviye seçimi, zorluk eğrisini yumuşatır çünkü oyuncuya yakın deneyimler sunarsın. Böylece hem bilişsel bilim hem de modern veri altyapısı aynı hedefe hizmet eder: anıların kalıcılığı.
