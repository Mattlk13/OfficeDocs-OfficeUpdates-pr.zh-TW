---
title: 2020 年半年通道 (已設定目標) 版本的版本資訊
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2020 年 Office 365 專業增強版半年通道 (已設定目標) 版本的版本資訊
ms.openlocfilehash: 64270156e5985b3214a0e75c56f4bdb1713125fa
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978711"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2020"></a>2020 年半年通道 (已設定目標) 版本的版本資訊

這些版本資訊可提供 2020 年 Office 365 專業增強版、Visio Pro for Office 365、Project Online 電腦版用戶端以及 Office 365 商務版的半年通道 (已設定目標) 更新所含新功能和非安全性更新的相關資訊。

> [!NOTE]
>
> - 我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至半年通道 (已設定目標)。 如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。 [深入了解](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - 從版本 1902 開始，Microsoft Teams 會包含在半年通道 (已設定目標) 的全新安裝中。 將 Teams 更新至版本 1908 或更新版本時，即會將 Teams 新增至半年通道 (已設定目標) 的現有安裝中。 如需詳細資訊，請參閱[使用 Office 365 專業增強版部署 Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install)。

## <a name="version-1908-february-11"></a>版本 1908：2 月 11 日
*版本 1908 (組建 11929.20606)*

安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 此更新已修正使用 VBA 將影像新增到圖表的頁首/頁尾時發生錯誤的問題。

- 已修正在預覽列印或列印時群組方塊控制項的框線無法顯示的問題。

- 使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。

- 已修正圖表標題中影像檔案大小在儲存包含圖表的活頁簿時增加的問題。


- 已修正以下問題：將選取範圍與交互參照的活頁簿保持同步時，導致交互參照的活頁簿中的 DBCS 字元損毀。

- 已解決使用自動調整來調整列高時，核取方塊可能收縮的問題。


### <a name="outlook"></a>Outlook

- 已解決導致使用者在指定無效寄件者地址時發生當機的問題。

- 已解決導致使用者處理衝突郵件時同步失敗的問題。

- 已解決導致使用者在啟動 Outlook 時，「正在載入設定檔」畫面時停滯的問題。

- 已解決導致使用者在變更檢視時發生當機的問題。


- 已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。 [此處](https://support.microsoft.com/zh-TW/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是記錄舊版問題的個別 KB。

- 已解決以下問題：使用者將共用行事曆資料夾同步到 OST 時發生問題，這導致嘗試與這些資料夾互動時發生權限錯誤。


### <a name="powerpoint"></a>PowerPoint

- 已改善複製貼上的案例，即將 PowerPoint 投影片中的圖形複製並貼到其他投影片可能會因為異常而失敗。


- 已修正導致共同作業使用者之間效能較低的問題。

- 已修正以下問題：當檔案以漸進式開啟時，若其中一個投影片包含多個內嵌媒體串流可能會發生問題。

- 已修正以下問題：首次啟動 PowerPoint 時，不受信任的增益集可能不會顯示安全性警告訊息列。

### <a name="project"></a>Project

- 已修正以下問題：由於基準行事曆變更時未更新資源行事曆，而導致時程表和專案計劃之間的實際工作可能不同。

### <a name="word"></a>Word

- 已從遭取代的 API 移除，以修正 Word 的當機問題。

### <a name="office-suite"></a>Office 套件

- 此變更解決開啟損毀的檔案時正確呈現影像的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a>版本 1908：1 月 14 日
*版本 1908 (組建 11929.20562)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 文件標題的荷蘭文按鍵提示已變更為 Alt-G。

- 解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。

- 發生您無法從增益集開啟的 WPF (Windows Presentation Foundation) 表單的下拉式方塊選取項目的問題。

### <a name="outlook"></a>Outlook

- 解決當使用者透過鍵盤快速鍵與信箱資料夾互動時會造成明顯延遲的問題。

- 解決使用其他寄件者時導致無法顯示原則提示的問題。

- 解決了導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正將投影片從一個簡報複製到另一個簡報時可能會造成母片重複的問題。
- 如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告

### <a name="office-suite"></a>Office 套件

- 修正了 Office 更新訊息不以預期語言顯示的問題。 自此以後，Office 更新訊息會正確符合 Windows 顯示語言。

- 解決在某些情況下，如果使用者不是系統管理員且系統帳戶沒有網路連線，將無法套用更新的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> 如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。