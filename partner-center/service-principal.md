---
title: Azure AD hizmet sorumlusu
ms.topic: how-to
ms.date: 06/03/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: Azure AD kiracınıza hizmet sorumlusu ekleme hakkında bilgi edinin. Bunun yapılması, Iş Ortağı Merkezi 'ne bir Azure AD uygulaması (hizmet sorumlusu) ekleme anlamına gelir.
author: dhirajgandhi
ms.author: dhgandhi
ms.localizationpriority: High
ms.custom: SEOMAY.20
ms.openlocfilehash: 6ef5373fd9a606cd25345cbe80a55f28fc1f753f
ms.sourcegitcommit: ec33c2352a9dd3e5a941f0f42ff1e8d256bb2399
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 03/24/2021
ms.locfileid: "105028477"
---
# <a name="add-an-azure-ad-application-service-principal-in-partner-center"></a><span data-ttu-id="7e24b-104">Iş Ortağı Merkezi 'ne bir Azure AD uygulaması (hizmet sorumlusu) ekleme</span><span class="sxs-lookup"><span data-stu-id="7e24b-104">Add an Azure AD application (service principal) in Partner Center</span></span>

<span data-ttu-id="7e24b-105">**Uygun roller**</span><span class="sxs-lookup"><span data-stu-id="7e24b-105">**Appropriate roles**</span></span>

- <span data-ttu-id="7e24b-106">Genel yönetici</span><span class="sxs-lookup"><span data-stu-id="7e24b-106">Global admin</span></span>

<span data-ttu-id="7e24b-107">Iş Ortağı Merkezi 'ndeki ticari Market programında artık Iş Ortağı Merkezi hesabınıza bir kullanıcı olarak bir Azure AD uygulaması (hizmet sorumlusu) ekleyebileceksiniz.</span><span class="sxs-lookup"><span data-stu-id="7e24b-107">In the Commercial Marketplace program in Partner Center, you are now able to add an Azure AD application (service principal) as a user in your Partner Center account.</span></span> <span data-ttu-id="7e24b-108">(Bunu daha önce Bulut İş Ortağı Portalı veya CPP, hesabınızda de yapabileceksiniz.</span><span class="sxs-lookup"><span data-stu-id="7e24b-108">(You were able to do so previously in your Cloud Partner Portal, or CPP, account.</span></span> <span data-ttu-id="7e24b-109">Artık Iş Ortağı Merkezi 'ne geçirdiniz, CPP hesabı salt okunurdur.)</span><span class="sxs-lookup"><span data-stu-id="7e24b-109">Now that you have migrated to Partner Center, the CPP account is read-only.)</span></span>
 
>[!Note] 
><span data-ttu-id="7e24b-110">Hizmet sorumlusu, Azure AD uygulaması ile eşanlamlıdır.</span><span class="sxs-lookup"><span data-stu-id="7e24b-110">Service principal is synonymous with Azure AD application.</span></span>

## <a name="add-an-azure-ad-application-service-principal"></a><span data-ttu-id="7e24b-111">Azure AD uygulaması ekleme (hizmet sorumlusu)</span><span class="sxs-lookup"><span data-stu-id="7e24b-111">Add an Azure AD application (service principal)</span></span>

1. <span data-ttu-id="7e24b-112">Iş Ortağı Merkezi panosundan **Ayarlar** ' ı seçin ve ardından **Geliştirici ayarları**' nı seçin.</span><span class="sxs-lookup"><span data-stu-id="7e24b-112">From the Partner Center dashboard, select **Settings** and then select **Developer settings**.</span></span>

2. <span data-ttu-id="7e24b-113">**Kullanıcıları** seçin ve ardından **Azure AD uygulamaları Ekle**' yi seçin.</span><span class="sxs-lookup"><span data-stu-id="7e24b-113">Select **Users** and then select **Add Azure AD Applications**.</span></span>

3. <span data-ttu-id="7e24b-114">Mevcut bir Azure AD uygulaması seçin veya yeni bir tane oluşturun.</span><span class="sxs-lookup"><span data-stu-id="7e24b-114">Select an existing Azure AD application or create a new one.</span></span>

4. <span data-ttu-id="7e24b-115">Yeni bir Azure AD uygulaması oluşturursanız, aşağıdaki bilgileri ekleyin:</span><span class="sxs-lookup"><span data-stu-id="7e24b-115">If you create a new Azure AD Application, include the following information:</span></span>  

   - <span data-ttu-id="7e24b-116">**Yanıt URL 'si**: KULLANıCıLARıN Azure AD uygulamanızı kullanmak için oturum açabilecekleri URL.</span><span class="sxs-lookup"><span data-stu-id="7e24b-116">**Reply URL**: The URL where users can sign in to use your Azure AD application.</span></span>

   - <span data-ttu-id="7e24b-117">**Uygulama kimliği URI 'si**: Azure AD 'ye yönelik çoklu oturum açma isteği gönderdiğinde sunulan Azure AD uygulaması için mantıksal tanımlayıcı.</span><span class="sxs-lookup"><span data-stu-id="7e24b-117">**App ID URI**: A logical identifier for the Azure AD application that is presented when it sends a single sign-on request to Azure AD.</span></span>

   - <span data-ttu-id="7e24b-118">**Güvenlik rolleri**: roller **Yöneticisi** (cpp ' deki ' Owner ' rolüyle aynı) ve **Geliştirici** (cpp ' de ' katkıda bulunan ' rolüyle aynı), iş ortağı merkezi 'nde ticari Market programına uygulanır ve bu Azure AD uygulamasıyla ilişkilendirilebilir.</span><span class="sxs-lookup"><span data-stu-id="7e24b-118">**Security roles**: The roles **Manager** (the same as  ‘Owner’ role in CPP) and **Developer** (the same as ‘Contributor’ role in CPP) apply to the Commercial Marketplace program in Partner Center, and they can be associated with this Azure AD Application.</span></span>  

## <a name="next-steps"></a><span data-ttu-id="7e24b-119">Sonraki adımlar</span><span class="sxs-lookup"><span data-stu-id="7e24b-119">Next steps</span></span>

- [<span data-ttu-id="7e24b-120">Iş Ortağı Merkezi 'nde ticari Market 'e genel bakış</span><span class="sxs-lookup"><span data-stu-id="7e24b-120">Overview of the commercial marketplace in Partner Center</span></span>](csp-commercial-marketplace-overview.md)