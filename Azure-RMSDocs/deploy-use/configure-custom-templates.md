---
title: "設定 Azure Rights Management Service 的自訂範本| Azure Information Protection"
description: "適用於系統管理員設定和管理使用權限範本的資訊和指示。 範本可讓使用者和其他系統管理員輕鬆地將原則套用到敏感性檔案，限制僅供已獲得授權的使用者存取。"
author: cabailey
manager: mbaldwin
ms.date: 09/25/2016
ms.topic: article
ms.prod: 
ms.service: information-protection
ms.technology: techgroup-identity
ms.assetid: 1775d8d0-9a59-42c8-914f-ce285b71ac1c
ms.reviewer: esaggese
ms.suite: ems
translationtype: Human Translation
ms.sourcegitcommit: d5b6a1fc3fa0a19f3a6b65aa7b8815eda7432cd7
ms.openlocfilehash: d8db7f0346fad1b9c46423875d1e559d41987686


---

# 設定 Azure Rights Management Service 的自訂範本

>*適用於︰Azure Information Protection、Office 365*

[啟用](activate-service.md) Azure Rights Management Service 之後，使用者就能夠自動使用兩個預設範本，讓他們可以輕鬆地將 Rights Management 原則套用至敏感性檔案，其僅限您組織中授權使用者進行存取。 這兩個範本具有下列權限原則限制：

-   受保護內容的唯讀檢視

    -   顯示名稱：**&lt;組織名稱&gt; - 僅限機密檢視**

    -   特定權限：檢視內容

-   受保護內容的讀取或修改權限

    -   顯示名稱：**&lt;組織名稱&gt; - 機密**

    -   特定權限：檢視內容、儲存檔案、編輯內容、檢視指派的權限、允許巨集、轉寄、回覆、全部回覆

此外，[RMS 共用應用程式](../rms-client/sharing-app-windows.md)可讓使用者定義自己的權限集。 而且在 Outlook 用戶端和 Outlook Web Access，使用者還可以選取 [不可轉寄](../deploy-use/configure-usage-rights.md#do-not-forward-option-for-emails) 選項。

對許多組織來說，預設範本可能就已經夠用。 但是，如果您想要建立自己的自訂權限原則範本，您也可以那麼做。 建立自訂範本的原因包括下列各項：

-   您想要一個可將權限授與組織中部分使用者而非全部使用者的範本。

-   您希望只有部分使用者能夠從應用程式中看到和選取範本 (部門範本)，而不是組織中所有使用者都能看到和選取範本。

-   您想要為範本定義自訂權限，例如「檢視」或「編輯」，但不要「複製」和「列印」。

-   您想要在範本中設定額外選項，包括到期日和是否可以在沒有網際網路連線的情況下存取內容。

若要讓使用者能夠選取包含這類設定的自訂範本，您必須先建立自訂範本、設定它，然後發佈它。 雖然您可能只需要幾個範本，您最多可在 Azure 中儲存 500 個自訂範本。 

使用下列資訊可協助您設定及使用自訂範本：

-   [如何建立、設定及發佈自訂範本](create-template.md)

-   [如何複製範本](copy-template.md)

-   [如何移除 (封存) 範本](remove-template.md)

-   [如何重新整理使用者的範本](refresh-templates.md)

-   [使用 PowerShell 來管理範本](configure-templates-with-powershell.md)





<!--HONumber=Sep16_HO4-->


