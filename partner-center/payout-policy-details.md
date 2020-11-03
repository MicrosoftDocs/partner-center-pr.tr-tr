---
title: Ödeme ilkesi ayrıntıları-Microsoft ticari Market
description: Zamanlamalar ve engel dahil olmak üzere ticari Market ödeme ilkelerine ilişkin ayrıntılar hakkında bilgi edinin.
ms.service: marketplace
ms.subservice: partnercenter-marketplace-publisher
ms.topic: conceptual
author: mingshen-ms
ms.author: mingshen
ms.date: 09/28/2020
ms.openlocfilehash: eec5f85f38280757bc1e5d5c36a4dd1ac5ce8d22
ms.sourcegitcommit: 3c45a181ef86b3a4866e97fb50efeae8714ab3f7
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 10/19/2020
ms.locfileid: "92532006"
---
# <a name="payout-policy-details"></a>Ödeme ilkesi ayrıntıları

Bu makalede, Microsoft 'un ödeme süreci, ödeme zamanlaması, ödeme ve dağıtım ilkesinin durumunun nerede bulunacağı açıklanır.

## <a name="payment-schedules"></a>Ödeme zamanlamaları

Aşağıdaki bölümlerde, ödeme sürecimiz açıklanır.

### <a name="enterprise-agreement-transactions-after-may-1-2020"></a>1 Mayıs 2020 ' den sonra işlemleri Kurumsal Anlaşma

#### <a name="update-to-our-commercial-marketplace-publisher-payout-model"></a>Ticari Market Yayımcımız ödeme modelinize güncelleştirin

1 Mayıs 2020 ' den itibaren, Azure Marketi 'nde satın alınan ürünlerle veya Microsoft Kurumsal Anlaşma olan müşterilere göre AppSource 'a ilişkin ödemeler ilkemizi güncelleştiriyoruz. Bir müşteri Azure Marketi 'nden veya AppSource 'tan bir ürün satın aldığında 1 Mayıs 2020 ' den sonraki işlemler için mevcut Microsoft Kurumsal Anlaşma, ' den sonra ödemeler vermeye başlayacağız. Bir müşterinin kredi kartı kullandığı işlemler değiştirilmez ve ödemesinden önce 30 günlük tutma süresine sahip olmaya devam edecektir. Bu tablo, ödeme zamanlaması hakkındaki ayrıntıları gösterir.

> [!NOTE]
> Müşteri ödeme yapamazsa, ancak size bir ödeme vermiş olduğumuz eylemler için aşağıdaki [Müşteri ödemesiz işleme](#process-for-customer-non-payment) bölümüne bakın.

| Olay  | Tarih (UTC) | İş ortağı görünürlüğü: Iş Ortağı Merkezi ödeme raporu  |  İş ortağı görünürlüğü: Iş ortağı merkezi analizi\* |
| --- | --- | --- | --- |
| İşlem veya kullanım ayı | 8/1/2020 – 8/31/2020 | Yok | **Kullanım raporu** : yeni tüketim gösteriliyor (her dört saatte bir yenilenir)<br>**Sipariş raporu** : yok |
| Dönem sonu (ay) | 8/31/2020 | Yok | **Kullanım raporu** : aylık son tüketim gösteriliyor<br>**Sipariş raporu** : yok |
| Sıra oluşturuldu | 9/3/2020 – 9/7/2020 | Yok | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
| Ödeme kazanmakta hesaplama | 9/4/2020 – 9/10/2020 | Ödeme panosundaki Işlem geçmişinde **işlenmemiş** olarak işaretlendi | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
| Aylık ödeme | 10/5/2020 | Ödeme panosundaki işlem geçmişinde **yakında çıkacak** şekilde işaretlendi | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
| Ödeme tarihi\** | 10/15/2020 | Işlem geçmişinde ve ödeme panosunun ödemeler bölümünde **gönderildi** olarak işaretlendi | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
| Müşteri faturası toplandı | 12/1/2020 | Işlem geçmişinde ve ödeme panosunun ödemeler bölümünde **gönderildi** olarak işaretlendi | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi  |
|  |  |  |  |

\* Kullanım ve sipariş raporlarına Iş Ortağı Merkezi 'ndeki çözümle bölümünde erişilebilir. \* *. Ödeme tarihi, Pasifik Standart Saati (PST) olarak belirlenir.

### <a name="customers-who-pay-using-credit-card-or-invoice"></a>Kredi kartı veya fatura kullanarak ödeme yapan müşteriler

Kredi kartı veya aylık fatura içeren tüm satın almalarda, fonların temizlendiğinden ve geri ödeme veya şüpheli sahtekarlık olmadığından emin olmak için 30 günlük bir bekleme süresi bulunur.

| Olay  | Tarih (UTC) | İş ortağı görünürlüğü: Iş Ortağı Merkezi ödeme raporu  |  İş ortağı görünürlüğü: Iş ortağı merkezi analizi\*  |
| --- | --- | --- | --- |
| İşlem veya kullanım ayı | 8/1/2019 - 8/31/2019 | Yok | **Kullanım raporu** : yeni tüketim gösteriliyor (her dört saatte bir yenilenir)<br>**Sipariş raporu** : yok |
| Dönem sonu (ay) | 8/31/2019 | Yok | **Kullanım raporu** : aylık son tüketim gösteriliyor<br>**Sipariş raporu** : yok |
| Sıra oluşturuldu | 9/3/2019 – 9/7/2019 | Yok | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
| Müşteri faturası toplandı | 9/7/2019 – 9/10/2019 | Yok | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
| Ödeme 'yi hesapla | 9/8/2019 -9/12/2019 | Ödeme panosundaki Işlem geçmişinde **işlenmemiş** olarak işaretlendi | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
| Aylık ödeme | 11/5/2019\* | Ödeme panosundaki Işlem geçmişinde **yakında çıkacak** şekilde işaretlendi | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
| Ödeme tarihi\** | 11/15/2019 | Işlem geçmişinde ve ödeme panosundaki ödemeler bölümünde **gönderildi** olarak işaretlendi | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
|  |  |  |  |

\* Kullanım ve sipariş raporlarına Iş Ortağı Merkezi 'ndeki çözümle bölümünde erişilebilir.</br>\** Ödeme tarihi Pasifik standart saatine (PST) göre yapılır.

### <a name="enterprise-agreement-transactions-prior-to-may-1-2020"></a>1 Mayıs 2020 ' den önceki işlemleri Kurumsal Anlaşma

Bu tarihten önce oluşan tüm satın alımlar, Microsoft 'un müşterilerden ödeme topladıktan ve Market ücretini işleyene sonra aşağıdaki zamanlama başına işlenir ve ücretlenir.

| Olay  | Tarih (UTC)  | İş ortağı görünürlüğü: Iş Ortağı Merkezi ödeme raporu  |  İş ortağı görünürlüğü: Iş ortağı merkezi analizi\*  |
| --- | --- | --- | --- |
| İşlem veya kullanım ayı | 8/1/2019 – 8/31/2019 | Yok | **Kullanım raporu** : yeni tüketim gösteriliyor (her dört saatte bir yenilenir)<br>**Sipariş raporu** : yok |
| Dönem sonu (ay) | 8/31/2019 | Yok | **Kullanım raporu** : aylık son tüketim gösteriliyor<br>**Sipariş raporu** : yok |
| Sıra oluşturuldu | 9/3/2019 – 9/7/2019 | Yok | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
| Müşteri faturası toplandı | 12/1/2019 | Yok | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
| Ödeme 'yi hesapla | 12/5/2019 – 12/7/2019 | Ödeme panosundaki Işlem geçmişinde **işlenmemiş** olarak işaretlendi | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
| Aylık ödeme | 1/5/2019 | Ödeme panosundaki işlem geçmişinde **yakında çıkacak** şekilde işaretlendi | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
| Ödeme tarihi\** | 1/15/2019 | Işlem geçmişinde ve ödeme panosundaki ödemeler bölümünde **gönderildi** olarak işaretlendi | **Kullanım raporu** : OrderID/Orderlineıtemıd ile gösterilen tüketim<br>**Sipariş raporu** : MÜŞTERI siparişlerinin etkin olarak gösterilmesi |
|  |  |  |  |

\* Kullanım ve sipariş raporlarına Iş Ortağı Merkezi 'ndeki çözümle bölümünde erişilebilir.</br>\** Ödeme tarihi Pasifik standart saatine (PST) göre yapılır.

## <a name="process-for-customer-non-payment"></a>Müşteri ödemesiz işlem

Nadir durumlarda Microsoft, ticari Market satın alımları için müşterilerden ödeme toplayamamaktadır. Bir müşteri Microsoft 'un faturalandırma zamanlamalarına göre ödeme yapamazsa koleksiyonlar işlemine başlayacağız. Bu işlem yaklaşık dört ay sürer ve Microsoft 'tan kalıcı iletişim içerir. Ödeme bu işlemin sonuna kadar alınmıyorsa, Microsoft fonları toplanabilir olmayan bir tablo olarak yazar.

Bu işlem için, Microsoft, bu işlemin sonunda, son olarak toplanabilir bir tablo olan yayımcılar 'a (siz) zaten ücret ödemüş olabilir. Bu nedenle, bu miktarları mutabık kılma sürecimiz vardır. (Zaten alınmış) ödemenin uzlaştırılabileceğini belirten bir uyarı olduğundan emin olmak için, bir müşteri koleksiyonlar sürecinde olduğunda ve satın alımlarınızın kapalı olma olasılığı varsa size bildirilir.

Microsoft, aşağıdaki yöntemlerden birini kullanarak zaten ücretli olan tüm ödemeler için ödeme yapacaktır: (1) Microsoft, ödenmemiş miktarları gelecekteki ödemeler üzerinden çıkartabilir; Örneğin, ödemelerden $1.000, toplanmamış tablo olarak kabul edilir ve bu durum devre dışı bırakılırsa, gelecekteki ödemelerden bazıları $1.000 kurtarılana veya (2) Microsoft, toplanan herhangi bir miktar için bir para iadesi veya fatura yayımcıları isteyebileceği için,

Örnek zamanlama aşağıda verilmiştir:

| Olay | Yaklaşık Tarih | İş ortağı görünürlüğü |
| --- | --- | --- |
| Örnek ödeme tarihi | 10/15/2020 | Ödeme panosundaki Işlem geçmişi ve ödemeler bölümünde **gönderildi** olarak işaretlendi |
| <font color="red">Müşteri Microsoft 'a ödeme yapmasa da</font> | 12/2/2020 – 12/5/2020 | Değişiklik yok, yukarıdaki ile aynı |
| Müşteri ilk geç ödeme e-postasını alır | 12/6/2020 | Yok |
| Müşteri, artan aciliyet e-postalarını alır | 12/7/2020 – 1/31/2021 | Yok |
| Yayımcı, yazma işlemi için büyük olasılıkla | 1/7/2021 | Müşteriye henüz ödeme gönderilmemiş olan e-posta bildirimi gönderilir. İşlem KIMLIĞI ve dolar miktarı dahil edilir. |
| Müşteri sonlandırma bildirimini alır | 2/1/2021 | Yok |
| Toplama işleminin bitişi/fonları yazılır | 2/15/2021 | Fonların yazıldığı yayımcıya gönderilen e-posta bildirimi. İşlem KIMLIĞI ve dolar miktarı dahil edilir. |
| Ödeme kesinti | 01.03.2021 | Yayımcı, Iş Ortağı Merkezi ödeme bildiriminde negatif işlem görür |
| Ödeme stopaj uygulanan | 3/15/2021 | Gelecekteki ödemeler, Iş Ortağı Merkezi ödeme bildiriminde gösterilir. Bu, bakiye artık negatif olmadığından, ödeme ödemeyi almaz.  |
|||

## <a name="number-of-days-for-payments-to-reach-a-payout-account"></a>Ödemelerin bir ödeme hesabına ulaşması için geçen gün sayısı

Genellikle söz konusu ayın 15. gününde belirli bir ay boyunca herhangi bir ödeme gönderiyoruz, ancak ödemenin hesabınıza ulaşması daha fazla zaman alır. Gün sayısı, aşağıda açıklandığı gibi, hesabınız için kullandığımız ödeme yöntemine bağlıdır.

> [!NOTE]
> Aşağıda gösterilen günler yaklaşık değerlerdir; Tüm ödemeler hesabınıza ulaşmak için daha uzun veya daha kısa bir süre alabilir.

| Ödeme yöntemi     | Ödeme hesabına ulaşma gün sayısı     |
|--------------------|--------------------------------------------|
| PayPal             | 1 iş günü                             |
| ACH/SEPA           | 2-3 iş günü                          |
| Tel aktarım      | 7-10 iş günü                         |
|

## <a name="next-steps"></a>Sonraki adımlar

- [Vergi ayrıntıları](tax-details-marketplace.md)
