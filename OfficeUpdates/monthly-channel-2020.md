---
title: 2020 年每月通道版本的版本資訊
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2020 年 Office 365 專業增強版每月通道版本的版本資訊
ms.openlocfilehash: 35d4a8383dcfcb81a872901337cb5f36ed6166e6
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978601"
---
# <a name="release-notes-for-monthly-channel-releases-in-2020"></a>2020 年每月通道版本的版本資訊

這些版本資訊可提供 2020 年 Office 365 專業增強版、Visio Pro for Office 365、Project Online 電腦版用戶端以及 Office 365 商務版的每月通道更新所含新功能和非安全性更新的相關資訊。

 > [!NOTE]
>
>- 我們通常會在一段時間每個月推出功能 (有時甚至推出修正程式)。  如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。 [深入了解](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- 現有 Office 365 專業增強版安裝上的 Microsoft Teams - 從 7 月初開始，對 Office 365 專業增強版 (和 Office 365 商務版) 的更新將包含 Microsoft Teams。  新增 Teams 的日期取決於您使用的更新通道。 如需詳細資訊，請參閱[隨著 Office 365 專業增強版部署 Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install)。

## <a name="version-2001-february-11"></a>版本 2001：2 月 11 日
*版本 2001 (組建 12430.20264)*

安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- Access 範本應不再導致資料庫中的附件欄出現故障。 個體化範本後，您現在應該可以將附件欄新增至資料庫。

### <a name="excel"></a>Excel

- 已修正未顯示操作功能表中的註解命令的問題。

- 已修正以下問題：將文字轉換成具有溢出陣列之儲存格的欄時，某些使用者發生當機。


### <a name="outlook"></a>Outlook

- 解決導致使用者在指定無效寄件者地址時發生當機的問題。


- 解決導致使用者在取消帳戶設定時發生當機的問題。


### <a name="project"></a>Project

- 已修正以下問題：固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成。


### <a name="office-suite"></a>Office 套件

- 此變更解決使用 Intel Integrated GPU 的圖形配接卡報告問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-january-30"></a>版本 2001：1 月 30 日
*版本 2001 (組建 12430.20184)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。

- **向左看，向右看... XLOOKUP 在這裡！：** 一列接著一列，在含有 XLOOKUP 的表格或範圍中尋找您需要的項目。 [深入了解](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a>Outlook

- **進階群組電子郵件設定：** 此功能可協助使用者自訂要在收件匣中接收/追蹤哪些電子郵件或活動。

- **群組命名原則：** 群組命名原則可讓 IT 系統管理員將組織中使用者所建立群組的名稱標準化及管理。 系統管理員可以要求在建立群組時，將特定首碼和尾碼新增至群組的名稱，而且可以封鎖使用特定字詞。 這有助於將群組名稱中使用不當字詞的情況最小化，以及 IT 管理其目錄中群組的表示方式。 命名原則也可協助部署小組網站的組織根據部門來分類。

### <a name="word"></a>Word

- **更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。 [深入了解](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- **對筆跡使用套索：**[繪圖] 索引標籤上的 [套索] 工具，可協助您選取使用筆跡繪製的物件。 選取個別筆劃或整個字。 [深入了解](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。 [深入了解](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- <div><span style="display:inline !important;">此更新會修正使用 ADODB 的問題。VB 程式碼中的錄製程式物件可能會不正確地報告錯誤。&nbsp;</span><br></div>


- <div style="box-sizing:border-box;"><span style="box-sizing:border-box;"><span style="background-color:rgba(255, 255, 255, 1);box-sizing:border-box;display:inline;">此更新修正可能會導致 Microsoft Access 無法識別連結 SQL Server 資料表中的身分識別資料行的問題，這可能會導致將資料列報告為刪除不正確</span></span></div>


### <a name="excel"></a>Excel

- <div>解決重新命名簽名時，使用者遇到當機的問題。</div>


### <a name="outlook"></a>Outlook

- <div>解決重新命名簽名時，使用者遇到當機的問題。</div>


### <a name="outlookexe"></a>outlook.exe

- <div>解決重新命名簽名時，使用者遇到當機的問題。</div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-january-22"></a>版本 1912：1 月 22 日
*版本 1912 (組建 12325.20344)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- <div>此更新修正可能會導致 Microsoft Access 無法識別連結 SQL Server 資料表中的身分識別資料行的問題，這可能會導致將資料列報告為刪除不正確</div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-january-14"></a>版本 1912：1 月 14 日
*版本 1912 (組建 12325.20298)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

## <a name="version-1912-january-08"></a>版本 1912：1 月 8 日
*版本 1912 (組建 12325.20288)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新

### <a name="outlook"></a>Outlook

- **傳送可存取的郵件給最需要它的人員：** Outlook 會顯示郵件提示，協助確保將您的內容傳送給偏好可存取內容的使用者時可供其存取

### <a name="powerpoint"></a>PowerPoint

- **最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。

- **jiffy 中的 Gif：** 一個投影片、一個圖文框。 在 PowerPoint 中輕鬆建立迴圈 Gif。 [深入了解](https://support.office.com/zh-TW/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。

### <a name="outlook"></a>Outlook

- 解決了導致會議位置在清除之後，又會不預期地重新加回會議的問題。

- 解決當使用者透過鍵盤快速鍵與信箱資料夾互動時會造成明顯延遲的問題。

- 解決在某些情況下，導致使用者看到電子郵件傳送到與顯示的 SMTP 位址不相符之地址的問題。

- 解決在擷取雲端設定時，導致使用者在 Outlook 中遇到當機的問題。

### <a name="word"></a>Word

- 建置組塊組合管理可能會顯示無效的通知：&quot;您已經修改樣式、建置組塊&quot;。

### <a name="office-suite"></a>Office 套件

- 解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> 如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。
