---
title: 2020 年目前通道版本的版本資訊
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2020 年 Microsoft 365 Apps 每月通道版本的版本資訊
ms.openlocfilehash: 90e66226abfe32aeb4097ccdfff3ec3665437c05
ms.sourcegitcommit: e7891ceed915afd2ae74689a366cebf9b3f60614
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/12/2021
ms.locfileid: "49837504"
---
# <a name="release-notes-for-current-channel"></a>目前通道的版本資訊

這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含在 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的目前通道更新。

> [!IMPORTANT]
> 我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。 如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。

 > [!NOTE]
>
>- 我們通常會在一段時間對「目前」通道推出功能 (有時甚至推出修正程式)。  如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。 [深入了解](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- Microsoft Teams 功能可能會與最新的目前通道中發行的功能不同，因為後者的發行頻率較高。




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-january-12"></a>版本 2012：1 月 12 日
*版本 2012 (組建 13530.20376)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致在提示使用者儲存已編輯的簽名後，該動作會無法執行的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-january-05"></a>版本 2012：1 月 05 日
*版本 2012 (組建 13530.20316)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **雲端中的 Outlook 設定：** 選擇您的 Windows 版 Outlook 設定，例如自動回復、焦點收件匣和隱私權，並在任何電腦上使用這些功能。

### <a name="powerpoint"></a>PowerPoint

- **利用簡報者教練排練簡報：** 取得有助於維持對象參與的項目方面的意見反應，例如節奏、語調、填充字詞、敏感詞語等等。 [深入了解](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正使用樞紐分析表的「將值顯示為」功能表時，Excel 可能會意外關閉的問題。


- 已修正當開啟含有 Excel 4.0 巨集的 Excel 增益集檔案時，Excel 可能會在不提示的情況下停用巨集的問題。


- 已修正當某些使用者在共同撰寫時會錯誤地看到通知他們檔案新版本的訊息列之問題。


- 此變更解决了在方程式中正確顯示字型的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致某些客戶在載入行事歷時遇到停滯的問題。


### <a name="powerpoint"></a>PowerPoint

- 此變更解决對某些幾何圖形套用 [合併圖案] 作業時路徑填充的問題。


- 此變更解决了在方程式中正確顯示字型的問題。


- 我們修正了在 QAT 中新增的字型大小命令在更新時，會自動完成到最接近的已定義字型大小之問題。


### <a name="office-suite"></a>Office 套件

- 優化的二進位大小。


- Anaheim WebView 目前尚不支援 Windows 資訊保護(WIP)。 有了此修正程式，Office addin 平臺便會回到處於 WIP 啟用環境中的低層級 WebView。 根據客戶的電腦環境，這可以是 Edge Spartan WebView 或 Trident WebView。 兩個低層級 WebViews 皆支援 WIP。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-december-21"></a>版本 2011：12 月 21 日
*版本 2011 (組建 13426.20404)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正了以下問題：Excel 錯誤地顯示檔案新版本可用的訊息列，並強制使用者將變更儲存到活頁簿的副本中或捨棄變更。


- 已修正當開啟含有 Excel 4.0 巨集的 Excel 增益集檔案時，Excel 可能會在不提示的情況下停用巨集的問題。


### <a name="office-suite"></a>Office 套件

- 已修正當快取中的 URL 與 OneDrive 中的 URL 不相符時，檔案將被開啟為 NOT SyncBacked 的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-december-08"></a>版本2011：12月 08 日
*版本 2011 (組建 13426.20332)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="office-suite"></a>Office 套件

- 我們修正了 SaveRequestManagerCam 導致應用程式會關閉，而非回傳錯誤的問題。 




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-december-02"></a>版本2011：12 月 02 日
*版本 2011 (組建 13426.20308)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正導致某些會議的原始出席者在另一個出席者轉寄會議時收到取消通知的問題。


- 我們已修正導致某些使用者未設定一或多個簽章時，在 [簽名] 下拉式清單中看不到任何簽名的問題。


### <a name="project"></a>Project

- 已修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。


### <a name="office-suite"></a>Office 套件

- Office 套件已修復此問題：在某些較舊的版本上安裝較新版的 Office 時，可能會造成功能受損 (例如由於遺失登錄專案而無法使用 Power Query)。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-30"></a>版本2011：11 月 30 日
*版本 2011 (組建 13426.20294)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="powerpoint"></a>PowerPoint

- 已修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。


### <a name="word"></a>Word

- 已修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。


- 我們已修正文件樣式會以範本中的其他樣式取代的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-23"></a>版本 2011：11 月 23 日
*版本 2011 (組建 13426.20274)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a>Excel

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。 [深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

- **在來源查詢之後命名新的工作表：** 將資料載入新工作表時，會根據來源查詢的名稱來為工作表命名。

- **使用 [進階對話方塊] 來 [建立資料類型]:** [進階對話方塊] 可讓您手動選取合併您正在建立的 [資料類型] 欄位。

### <a name="onenote"></a>OneNote

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a>Outlook

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。 [深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [Office 帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

- **工作的使用者體驗更新：** 工作項目的視覺效果更新。

### <a name="powerpoint"></a>PowerPoint

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。 [深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br />在[部落格文章](https://insider.office.com/zh-TW/blog/svg-content-office-third-party-apps)中查看詳細資料

- **使用透明背景建立 GIF：** 當匯出成動畫 GIF 時，您可以使用新選項讓背景變透明。<br />在[部落格文章](https://insider.office.com/zh-TW/blog/export-animated-gifs-transparent-backgrounds)中查看詳細資料

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

- **匯出一系列的動畫 GIF：** 當匯出成動畫 GIF 時，選取一系列投影片。

- **影片庫：** 使用可在應用程式內取得的精心製作、免費的影片素材庫來提升您的文件

### <a name="project"></a>Project

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a>Publisher

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a>Visio

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a>Word

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。 [深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 已修正在傳送工作的狀態報告時，造成 [收件者] 欄位為空白的問題。


- 已修正導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。


- 我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含內容。  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。 REG_DWORD IncludeFileTimesInDataObject。 0 = 不包含 filetimes。 1 = (預設) 包含 filetimes。


- 已修正當回覆含有「Azure 資訊保護」保護標籤的郵件時，導致內嵌影像消失的問題。


### <a name="powerpoint"></a>PowerPoint

- 已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生當機的 VBA 問題。


- 已修正在複製含有新錄製音訊的投影片後，儲存檔案時發生錯誤的問題。


- 已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。


### <a name="word"></a>Word

- 已修復影響 Word 的最佳化閘道所暴露的宣告錯誤。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-november-17"></a>版本 2010：11 月 17 日
*版本 2010 (組建 13328.20408)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。


- 我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含內容。  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。  REG_DWORD IncludeFileTimesInDataObject。  0 = 不包含 filetimes。  1 = (預設) 包含 filetimes。


### <a name="powerpoint"></a>PowerPoint

- 解決在合併錯誤期間使用 IRM/受保護文件的問題。


### <a name="visio"></a>Visio

- 已修正使用者將可在自訂 Visio 樣板和內建範本中使用適用於 Office 365 的 Visio 連接器建立直線的問題。


### <a name="office-suite"></a>Office 套件

- 已修正在某些情況下，嘗試執行另存新檔失敗的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-november-10"></a>版本 2010：11 月 10 日
*版本 2010 (組建 13328.20356)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正導致使用者無法將 [編輯器] 權限授與代理人的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正在嘗試儲存已從 syncbacked 檔案轉換為僅限伺服器的檔案時，導致失敗的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-27"></a>版本 2010：10 月 27 日
*版本 2010 (組建 13328.20292)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **隨時跟上改變！[日期/時間] 延伸資料類型具有更好的精確度。：** 引進新的和改良的資料類型。 為加強與 SQL 的語法相容性，並提高包含日期和時間之記錄的詳細資料和層級，我們正在將 DateTime2 資料類型實施到 Access 中。 這個額外的日期與時間資料類型，將會包含更大的日期範圍（0001-01-01 到9999-12-31），具有更高的指定時間精準度(以納秒取代秒為單位)，讓您可以提供和執行計算。 若要啟用，請選取 [新增欄位] > [日期與時間延長]。 [深入了解](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a>Excel

- **使用 Power Query 建立資料類型：** 使用 Power Query 從任何資料來源建立豐富的資料類型。 [深入了解](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br />在[部落格文章](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)中查看詳細資料

- **將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。 不需要轉換。<br />在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料

- **使用動作手寫筆快速編輯：** 您可以使用動作手寫筆直接在儲存格中書寫，以會自動轉換成 Excel 資料的筆跡記下資料。

### <a name="outlook"></a>Outlook

- **將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。 不需要轉換。<br />在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料

- **文法檢查是您的後盾**：Outlook 會在您輸入時標記文法錯誤，這麼一來，您只需按一下就可以套用建議。 [深入了解](https://support.office.com/article/ddbadc42-4637-451d-b3f4-ecf295036fa9)<br />在[部落格文章](https://insider.office.com/zh-TW/blog/grammar-and-style-suggestions-available-in-outlook)中查看詳細資料

### <a name="powerpoint"></a>PowerPoint

- **將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。 不需要轉換。<br />在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料

### <a name="teams"></a>Teams

- **Microsoft Teams 中的範本：** 使用 Teams 中的範本，使用者可在建立新的小組時從各種可自訂的範本中選擇，協助他們快速開始使用。 IT 專業人員也可以為其組織建立新的自訂範本，讓他們能標準化小組結構、讓相關應用程式浮現，以及擴大最佳做法。

- **釘選文章：** 此功能可讓使用者將頻道中的任何訊息「釘選」到頻道資訊窗格，使得頻道中所有成員能夠看見。 擁有頻道存取權的任何成員都能查看釘選的訊息。 頻道的任何成員都能釘選任何訊息 (除非透過頻道仲裁設定關閉)。

- **提交至應用程式目錄：** 您會在此畫面左下角看到 [提交至應用程式目錄] 連結。 除了 App Studio 和 Visual Studio，它是您可以提交應用程式進行核准的另一個位置。

- **在彈出的會議體驗中，使用 Freehand by Invision 做為白板：** 您現在可以在彈出的會議體驗中，於您參與的任何會議中將 Freehand by Invision 應用程式用作白板。 從共用內容匣選取 Freehand 應用程式並安裝它，然後啟動與您的同事的白板工作階段，順暢地開始激發靈感！

### <a name="word"></a>Word

- **將您的 iPhone 相片直接插入 Office：** 來自您手機的 HEIC 圖片現在可無縫地插入 Office。 不需要轉換。<br />在[部落格文章](https://insider.office.com/zh-TW/blog/insert-apple-photos-into-office-easily)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>存取

- 我們已修正從非 Office 應用程式使用 DAO 時，會導致應用程式意外關閉的問題。


### <a name="outlook"></a>Outlook

- 我們已修正在回覆或轉寄時，會導致中文郵件標題無法閱讀的問題。


- 我們已修正在儲存為 OFT 檔案時，會導致中文字元變更為問號的問題。


- 我們已修正會導致 Outlook 為已啟用雲端設定的使用者建立第二個空白簽名的問題。


- 我們已修正會導致預設不會為使用者開啟雲端設定的問題。


- 我們已修正會導致對使用者簽章的變更無法儲存的問題。


### <a name="powerpoint"></a>PowerPoint

- 這是此問題的修正：當有增益集在接聽 PresentationBeforeClose 事件並隨著事件處理常式檢查 Presentation.Saved 內容時若關閉文件，儲存提示會以迴圈顯示。


### <a name="project"></a>Project

- 修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。


- 修正 Project 在開啟以特定方式指定資源分佈的檔案時可能會意外終止的問題。


- 修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。


- 修正如果工作表單類型檢視內的延隔時間變更，ProjectBeforeTaskChange 事件中的 NewVal 不會有正確值的問題。


### <a name="office-suite"></a>Office 套件

- 當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。 將訊息變更為顯示 [碳粉/墨水不足] 和 [沒有碳粉/墨水]。

- 已修正 Microsoft 365 端點資料外洩防護無法在磁碟上分類 Office 文件的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-21"></a>版本 2009：10 月 21 日
*版本 2009 (組建 13231.20418)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正導致使用者無法將 [編輯器] 權限授與代理人的問題。


- 我們已修正導致使用者在選取搜尋結果時遇到意外終止的問題。


- 我們已修正當回覆或轉寄郵件時，會導致中文郵件標題無法閱讀的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 [表單] 內容增益集在插入之後不會呈現，除非使用者按一下另一張投影片讓它顯示才會呈現的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-13"></a>版本 2009：10 月 13 日
*版本 2009 (組建 13231.20390)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="project"></a>Project

- 修正 Project 在開啟以特定方式指定資源分佈的檔案時可能會遇到當機的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-08"></a>版本 2009：10 月 8 日
*版本 2009 (組建 13231.20368)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解决了搜尋未緩存共用行事曆時導致搜尋不傳回結果的問題。


- 解決了導致某些使用者觀察到在離線狀態下意外啟動 Outlook 的問題。


- 解決了導致代理人在開啟另一個信箱中的共用資料夾時出現錯誤的問題。


### <a name="powerpoint"></a>PowerPoint

- 解决在受保護的檢視中開啟 PowerPoint 檔案時停用 IRM 保護的問題的安全性問題修正。


### <a name="office-suite"></a>Office 套件

- 當使用者從 Office 噴墨印表機上列印任何文件/檔案且列印機墨水不足時，即使噴墨印表機沒有碳粉，也會顯示「碳粉不足」或「無碳粉」消息。 將訊息變更為顯示「碳粉/墨水不足」和「沒有碳粉/墨水」。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-28"></a>版本 200９：9 月 28 日
*版本 2009 (組建 13231.20262)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。 [深入了解](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 E5/A5 或 Microsoft 365 E5/A5 之組織的測試人員使用。 取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。 我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。 [深入了解](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料

- **建立變數以在公式中使用：** 使用 LET 函數改善效能、可讀性及可組合性。 此函數可讓您在新的或現有的公式中建立命名變數。 [深入了解](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />在[部落格文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看詳細資料

### <a name="outlook"></a>Outlook

- **自動開展線上目錄搜尋ive Search:** Enabling auto-expanding Online Archive Search

- **Outlook 的新設定檔卡：** Outlook 的新設定檔卡，包括更完善的組織方式，並符合 Outlook Web 卡的樣式。

### <a name="teams"></a>Teams

- **在 Microsoft Teams 中共用檔案：** [深入了解](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正了在包含大量特定資料物件類型 (E2o) 的檔案上導致共同撰寫變慢的問題。


### <a name="project"></a>Project

- 已修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。


### <a name="word"></a>Word

- 我們修正了 [樣式圖庫] 對話方塊的問題。


### <a name="office-suite"></a>Office 套件

- 此變更解決 [匯出至動畫 GIF] 功能的問題，其中按一下 [匯出] 按鈕沒有匯出。


- 此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-22"></a>版本 2008: 9月 22日
*版本 2008 (組建 13127.20508)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正了當凍結工作表頂端列之後，Excel 可能會在使用 [快速分析] 時當機的問題。


- 修正了當活頁簿包含使用 IFNA () 的公式時，可能會造成錯誤活頁簿的警告之問題。


### <a name="outlook"></a>Outlook

- 解決由於按一下角落中的 [X] 而導致使用者無法關閉共用行事曆的問題。


- 解決附件上傳的效能問題。


### <a name="powerpoint"></a>PowerPoint

- 我們修正了在 PowerPoint 應用程式中導致當機的問題。


### <a name="visio"></a>Visio

- 客戶回報文字對齊會在即時預覽時發生當機。 7 月分支所發生最多的當機情況。


### <a name="word"></a>Word

- 我們修正了 [樣式圖庫] 對話方塊的問題。


### <a name="office-suite"></a>Office 套件

- 修正使用 GIF/動畫 model3D 時導致高 CPU 使用狀況空閒



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-09"></a>版本 2008：9月 9 日
*版本 2008 (組建 13127.20408)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此變更修正了當啟動縮放框 (Shift + F2) 來編輯文字時，可能會導致 Access 當機的問題。


### <a name="excel"></a>Excel

- 已修正使用 [複製格式] 時，某些情況下，Excel 可能會當機的問題。


### <a name="word"></a>Word

- 我們已修正在調整圖案大小時，使用者可能會遺失內容的問題。


- 我們已修正基本樣式未更新為「內文樣式」的問題。


### <a name="office-suite"></a>Office 套件

- 此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-31"></a>版本2008：8月31日
*版本2008（組建13127.20296）*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。 我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。 [深入了解](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

### <a name="outlook"></a>Outlook

- **電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。 您可以變更權限，讓所有收件者都能存取。 [深入了解](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br />在[部落格文章](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)中查看詳細資料



### <a name="powerpoint"></a>PowerPoint

- **儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。 我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。 [深入了解](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

### <a name="teams"></a>Teams

- **合併通話：** 合併通話可讓使用者將使用中的 unheld 1-1 撥入另一個1-1 通話或另一個群組通話。 這適用於Teams VOIP 通話和 PSTN 通話。

- **系統管理員可以針對其第一線工作者設定按班表顯示（上班、下班）：** 系統管理員可以設定其第一線工作者使用以班表為基礎的狀態顯示：上班、忙碌中（到班時可以切換）和下班。

- **在Teams中使用 Cortana 語音技能：** Teams行動裝置的應用程式的Cortana 語音功能, 可協助使用者僅使用口頭自然語言即可執行會議、通訊與共同協作任務。 使用者可以在Teams應用程式中點擊麥克風按鈕與Cortana交談, 而且當他們困在家務中或遛狗或一般外出需與某人聯繫時, 可以發出諸如“打電話給Megan”或“對我的下一個會議發送訊息”之類的請求. 使用者只要說「加入我的下一個會議」即可加入會議，或者詢問「我今天早上有什麼事」來檢查行事曆。 在會議或通話中，他們可以從會議主持者的 [溢出] 功能表中調用 Cortana，並執行典型的會議中任務，例如按照姓名或電話號碼（「將 Megan 新增至通話」）、投影片瀏覽（「顯示季度檢閱投影片瀏覽」）或檢視投影片（「移至投影片備忘稿」）。 該功能還支持其他功能, 如尋找及共享檔案、搜尋，並通常在Teams應用中導航（與約翰聊天，移至我的未讀取活動，請移至我的表述等等）。 Teams 的Cortana 對Cortana 企業服務來說說符合對 Cortana 企業服務相同的的企業級隱私、安全性和合規性承諾，並反映在 [線上服務條款（OST）](https://www.microsoft.com/licensing/product-licensing/products)中。

- **增加群組交談：** Teams新增了群組聊天中可有250個參與者的功能.

- **按 Shift 加上標籤:** 使用這項功能，系統會自動在小組中的 [Shifts app](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) 應用程式中, 為人員指派符合其行程和班表的標籤。

### <a name="word"></a>Word

- **儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。 我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。 [深入了解](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

### <a name="office-suite"></a>Office 套件

- **索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。 只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。<br />在[部落格文章](https://blog-insider.office.com/2020/02/20/improved-pane-management/)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 已解决此問題 - 您現在可以使用 Office 的隨選即用應用程式外的 ODBC 驅動程式。


### <a name="outlook"></a>Outlook

- 修正導致使用者嘗試從次要帳戶建立會議邀請的問題，讓帳戶新增至他們的個人檔案，而不會看到空白的表格: 是欄位而不是其電子郵件地址。

- 修正了新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。

- 解決了當代理人在某些情況下遭到拒絕而導致會議無法從經理的行事曆中移除的問題。

- 解决了導致使用 Shared Calendar Improvements 的某些使用者無法查看剛新增的共用行事曆的問題。

- 修正了當與雲端附件互動時，導致使用者偶爾當機的問題。

- 解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。

- 解決會導致使用者在回覆或撰寫新電子郵件時遇到當機的問題。

- 解決了當您從 POP 帳戶刪除4或多個電子郵件時，已選取 [僅下載標題] 選項時，導致使用者遇到當機的問題。

- 解決導致 [排程助理員] 頁面無法顯示的問題。

- 修正了編輯收件者時，導致使用者偶爾當機的問題。

- 修正導致使用者在使用壓縮模式時發生異常的問題。

- 解決的問題導致在搜尋控制項中無法顯示滑鼠右鍵功能表。

- 解決會導致使用者在回覆或撰寫新電子郵件時收到下列錯誤的問題：「這個網頁中的某些檔案不存在預期的位置， 請問您一定要下載嗎? 如果您確定網頁來自信任的來源，請按 [是]」


### <a name="project"></a>Project

- 已修正「連結至 SharePoint 工作清單的專案的完成日期沒有更新」的問題。

- 修正如果資源中定義了多個成本費率表，其餘成本並不一定都能正確地計算的問題。

### <a name="skype"></a>Skype

- 將跳舞表情符號膚色變更為中性色彩.

### <a name="word"></a>Word

- 此更改解決了一個問題，即在上一個協同合作的作業後，Microsoft Office 應用程式可能卡在未通知的儲存失敗狀態的問題。

- 我們已修正整體的 AutoOpen 在 AutoExec 之前執行的問題



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-august-25"></a>版本 2007：8 月 25 日
*版本 2007 (組建 13029.20460)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 嘗試使用 LET() 函數儲存含有公式的檔案時發生錯誤。


### <a name="outlook"></a>Outlook

- 解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。


- 解決會導致 Outlook 使用者在精簡檢視中看到瀏覽問題的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 PowerPoint 應用程式的當機問題。


### <a name="word"></a>Word

- 解決會導致使用者在回覆或撰寫新郵件時遇到當機的問題。


### <a name="office-suite"></a>Office 套件

- 針對舊版非網頁服務的 [共用] 窗格，在開啟 [共用] 窗格下關閉文件時，可能會導致當機。 這個問題現在已經修正。


- 我們已修正使用者在特定情況下 (特別是進入或退出簡報者檢視畫面或使用多個監視器) 看到 UI 元素或內容未顯示的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-august-11"></a>版本 2007: 8月11日
*版本 2007 (組建 13029.20344)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決會導致 Outlook 無法擷取搜尋建議的問題。


- 解決會導致使用者在擷取角色資訊時有時候會當機的問題。


### <a name="project"></a>Project

- 修正無法開啟已進入錯誤狀態的專案的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-30"></a>版本 2007：7 月 30 日
*版本 2007 (組建 13029.20308)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。 [深入了解](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- **篩選和排序而不干擾其他人：** 您現在可以排序和篩選您的 Excel 檔案，同時與其他人使用工作表檢視進行共同作業。 此新功能可防止您在共同撰寫文件時，受到其他使用者的排序和篩選的影響。 [深入了解](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

- **自動套用或建議敏感度標籤：** Office 可以根據偵測到的敏感性內容來建議或自動套用敏感度標籤。

- **在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。  如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。 使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。 [深入了解](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br />在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料

### <a name="outlook"></a>Outlook

- **在 Outlook 中使用 [快速投票] 建立投票：** 輕鬆建立投票，收集投票，並查看電子郵件中的結果 [深入瞭解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮

- **快速重新開啟上一個工作階段的項目：** 我們新增了一個選項，可快速重新開啟上一個 Outlook 工作階段的項目。 不管 Outlook 當機或您將其關閉，您現在可以在重新開啟應用程式時快速重新啟動項目。 這項功能預設為啟用。 若要將它關閉，請移至 [選項] > [一般] > [啟動選項]。

### <a name="powerpoint"></a>PowerPoint

- **[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。

### <a name="teams"></a>Teams

- **新增簡化的通知設定：** 使用者現在可以使用增強的功能，以更簡單的方式管理其通知設定。

- **Teams 現在支援 Windows 原生通知：** 使用者現在可以選取其偏好的通知傳送方式，即透過 Teams 內建橫幅或 Windows 原生橫幅。

- **頻道資訊窗格：** 選取頻道標頭中的 [頻道資訊] 圖示時，將開啟一個窗格，其中會顯示頻道資訊的摘要，包括頻道描述、最近的參與者和成員清單，以及系統訊息的新首頁。

- **關閉聊天通知的預覽：** 使用者可以變更設定，並管理其聊天通知快顯的預覽。

- **建議的回覆：** 我們新增了讓 Teams 使用者對其交談具備建議的回覆功能。 這些建議會顯示在聊天訊息的底部 (如果已啟用)。 它們能讓您快速輕鬆地回覆訊息！

### <a name="word"></a>Word

- **[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。

- **以向量保留文字：** 現在當您在 Excel、Word 和 PowerPoint 中轉換地圖、圖表和其他 SVG 向量等物件時，您可以保留物件中的文字。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此修正會解決嘗試執行之前會產生「查詢太複雜」錯誤訊息的特定查詢的問題。

### <a name="excel"></a>Excel

- 修正在分頁預覽中載入含有多個工作表的活頁簿時，可能會發生錯誤或當機的問題。


### <a name="outlook"></a>Outlook

- 解決會導致 CLP 使用者在回覆時的寄件者地址，從受保護的內容切換到未受保護的內容時會發生當機的問題。


- 解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。


- 解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。


- 解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。

- 解決導致 [排程助理員] 頁面無法顯示的問題。

- 解決事件通知警示中導致格式設定問題的問題。

### <a name="project"></a>Project

- 已修正 [指派資源] 對話方塊中選取的工作與工作面板檢視中所選工作不同的問題。

- 修正當您貼上的工作具有多個依存性時，無法正確複製所有依存性的問題。

- 修正無法將 PDF/XPS 從 Project 儲存至 SharePoint 文件庫的問題。


### <a name="office-suite"></a>Office 套件

- 修正即使完整產品的轉換已完成，也會導致執行階段訊息顯示的問題。 此問題的修正程式是確保服務正確計算新增的產品。 我們已篩選出新增的產品 (確保它們同時存在於新的設定中)，並將它們新增到現有產品發行識別碼的結尾。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-july-28"></a>版本 2006：7 月 28 日
*版本 2006 (組建 13001.20498)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正在分頁預覽中載入含有多個工作表的活頁簿時，可能會發生錯誤或當機的問題。


### <a name="outlook"></a>Outlook

- 我們已修正複製和貼上 SVG 影像的問題。


### <a name="word"></a>Word

- 我們已修正複製和貼上 SVG 影像的問題。


### <a name="office-suite"></a>Office 套件

- 關閉 Office 檔案時，計時問題可能會導致當機。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-july-14"></a>版本 2006：7 月 14 日
*版本 2006 (組建 13001.20384)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 解決插入含有身分識別 (例如，自動編號) 欄位的連結 SQL 資料表的問題。

### <a name="excel"></a>Excel

- 自動文件分類可能已對處於唯讀模式的活頁簿發生。

- 修正若您已從帳戶登出，嘗試建立資料連線時，可能會發生的當機問題。

### <a name="onenote"></a>OneNote

- 改善共同撰寫狀態的偵測，以降低資源利用率。

### <a name="outlook"></a>Outlook

- 解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。

### <a name="office-suite"></a>Office 套件

- 我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。

- 解決在登錄 TabProcGrowth 值為 REG_SZ 類型的情況下啟用增益集時，Windows 中的 Office 主機會當機的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-30"></a>版本 2006：6 月 30 日
*版本2006（組建13001.20266）*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **較長的檔案名稱：** Windows 桌面版專用 Excel 現在支援使用最多 400 個字元名稱和路徑的 OneDrive/SharePoint 檔案。

- **RealTimeData (RTD) 的改進：** 在 Office 365 版本 2002 的每月通道或更新版本中，Excel RealTimeData (RTD) 函數速度比在 Excel 2010 試算表中計算資料還快。 我們在其基礎記憶體和資料結構中移除了瓶頸，並使其成為安全執行緒，讓它可在多執行緒重新計算 (MTR) 的所有可用執行緒上計算。

### <a name="outlook"></a>Outlook

- **在 Outlook 中撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？ 現在您可以視需要將其關閉了。<br />在[部落格文章](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)中查看詳細資料

- **IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。 [深入了解](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- **新增至 Outlook 快顯通知的其他按鈕：**[快速動作] 按鈕現在會於在 Windows 10 上執行 Outlook 時顯示在 Outlook 快顯通知中

### <a name="powerpoint"></a>PowerPoint

- **改善的 PowerPoint 中的 Steam 影片效能：** 我們改善了 Microsoft Stream 影片的播放效能，將影片載入時間減至最少，以建立出流暢的觀賞體驗。 您可以在 Microsoft Stream 上使用公司影片來建立更完善的簡報。

### <a name="teams"></a>Teams

- **針對外部使用者遮罩 PSTN 參與者電話號碼：** 針對為其 Teams 會議啟用音訊會議的客戶，我們會對從組織外部加入的使用者，將 PSTN 參與者的電話號碼遮罩起來。

- **管理您的頻道通知設定的簡化方式：** 透過團隊和頻道清單或從頻道標頭，使用者只要按一下即可將所有活動開啟或關閉就能快速管理其通知設定，或深入了解自訂以快速設定其偏好的通知排列組合。

- **Walkie Talkie：** 使用按著即可發言即時語音通訊。

### <a name="word"></a>Word

- **螢幕閱讀器的動作確認：** 確認動作是重要的協助工具要求。 隨著 Windows 引入新的通知 API 之後，我們現在就能通知螢幕助讀程式使用者的動作成功。 [剪下]、[複製]、[貼上]、[粗體]、[畫底線]、[復原]、[重做]、[自動校正] 和 [自動大小寫] 等功能都已公布給 Win32 Word 的朗讀程式使用者。 若要啟用此功能，請按 windows + ctrl + enter 以開啟朗讀程式。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。


### <a name="excel"></a>Excel

- 已修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。


### <a name="outlook"></a>Outlook

- 解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。

- 解決會導致共用行事曆改善功能的使用者看到行事曆失敗的問題。


- 解決會導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。


- 解決啟用雲端設定時，會造成 Ctrl + 按一下停止運作的問題。


- 解決會導致在「建議功能」中尋找功能不會傳回結果，因而讓使用者無法選擇提交新功能想法的問題。


### <a name="project"></a>Project

- 修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。


- 已修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。


- 已修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。


### <a name="word"></a>Word

- 解決 URL 包含查詢元件時，從自訂文件傳遞 (aspx) 開啟 Word 文件的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-24"></a>版本 2005：6 月 24 日
*版本 2005 (組建 12827.20470)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 現已修正此錯誤；您應該可以呼叫日期/時間延伸資料類型至您的程式碼，而不會在您的應用程式中遇到任何當機。 請讓團隊知道您是否遇到其他問題。


- 現已修正此問題；您現在可以還原為最新的 Access 版本，並使用 DAO/VBA 來管理及編輯十進位資料類型。 如果您在使用我們的資料類型時遇到任何進一步問題，請讓 Access 團隊知道。


### <a name="excel"></a>Excel

- 已修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。





### <a name="outlook"></a>Outlook

- 解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。


- 解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。


- 解決會導致使用者在 Outlook 中更新其規則時，看到&quot;此電腦上的規則與 Microsoft Exchange 上的規則不相符&quot;訊息的問題。


- 解決會導致共用行事曆改善功能的使用者看到行事曆失敗的問題。


- 解決會導致使用者在某些情況下遇到間歇性懸置和當機的問題。


- 解決會導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。


- 解決會導致在「建議功能」中尋找功能不會傳回結果，因而讓使用者無法選擇提交新功能想法的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正建議窗格的當機問題。


### <a name="project"></a>Project

- 已修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。

### <a name="word"></a>Word

- 解決會導致從應用程式拖曳部分內容時遇到當機的問題。


### <a name="office-suite"></a>Office 套件

- 此變更會解決載入和播放動畫內容 (例如 Gif 或3D 模型) 時可能會發生的懸置。




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-09"></a>版本 2005：6 月 9 日
*版本 2005 (組建 12827.20336)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。

### <a name="powerpoint"></a>PowerPoint

- **[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。

### <a name="word"></a>Word

- **[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 解決嘗試將樞紐分析表插入圖表時 Excel 可能會當機的問題。

### <a name="powerpoint"></a>PowerPoint

- 這可修正使用者在同一檔案中同時有新版和舊版批註，因此觸發批註的升級而當機的問題。

### <a name="project"></a>Project

- 已修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。

### <a name="office-suite"></a>Office 套件

- 我們透過設定Bing附加預設安裝驗證設定為true默認，並將MSI返回成功視為安裝成功，而解決了 ValidateInstall 失敗率問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-02"></a>版本 2005：6 月 2 日
*版本2005（組建12827.20268）*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **自動使用新的資料類型**：當您輸入的資料值類似股票或地理位置時，Excel 會將該值轉換為正確的連結資料類型 - 股票或地理位置。 [深入了解](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦

### <a name="outlook"></a>Outlook

- **協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站

- **更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。 [深入了解](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦

- **行事曆煥然一新：** 查看視覺更新，讓您的行事曆更容易流覽。 [深入了解](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />在[部落格文章](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)中查看詳細資料

### <a name="powerpoint"></a>PowerPoint

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦 [深入了解](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

- **在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。 [深入了解](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />在[部落格文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看詳細資料

- **不需要簡報導覽裝置：有耳塞式耳機就夠了：** 使用您的 Surface Earbuds 控制 PowerPoint 簡報。 運作方式：配對之後，您必須在 PowerPoint 中啟用功能。 按 F5 或選取 [投影片放映] > [從開頭] 開始簡報。  在投影片放映中，以滑鼠右鍵按一下投影片，然後在 [Surface Earbuds 設定] 底下，選擇 [使用手勢來控制簡報]。  將記住此設定以用於所有未來的簡報。 現在，您可以在左耳機上向前後撥動，以在 [投影片放映] 模式中瀏覽簡報。  點兩下以播放或暫停內嵌的影片。  重要：您必須在 Windows 10 的 Surface 音訊應用程式中配對 Surface Earbuds，才能使用手勢來控制簡報。 在此取得 Windows 10 上 Surface 音訊應用程式入門的指示。 [深入了解](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a>Teams

- **對 Teams 會議中視訊版面配置所做的變更：** 在 Teams 會議期間可同時檢視的參與者人數，很快地將從 4 個增加到 9 個。

- **在即時活動中包含系統音訊：** 即時活動中的簡報者和製作人，現在可以在即時活動期間共用桌面或視窗螢幕時包含系統音訊。 這可讓您的使用者聽到您正在共用內容的任何音訊部分。

- **讓召集人可以變更撥入參與者的大廳設定：** 此設定會控制透過電話撥入的人員是否直接加入會議，或是在大廳中等候，而不論 [自動准許人員] 的設定為何。

- **在會議中舉手：** 使用者現在可以在會議中虛擬舉手！ 其他參與者會在會議舞台中您的名稱旁和名冊中您的名字旁看到您的舉手。

- **自訂會議視訊背景：** 使用視訊會議時，您現在可以選擇要使用的不同靜態背景影像。 這可讓您顯示此影像，而不是您所在位置的實際背景。

- **新增更多人員至聊天：** 我們現在可以將最多 350 個人新增至單一聊天對話。

- **您的活動摘要上設定齒輪：** 使用者現在可以從摘要左側滑軌透過設定齒輪的方式，直接存取活動摘要和通知設定。

- **從 Teams 進行中的會議內輕鬆存取會議選項：** 我們讓會議召集人在 Teams 會議一開始，便能更快速且輕鬆地變更簡報者和大廳設定，方法是在參與者窗格中直接提供易於存取的連結。 此新功能將會同時對已排定和「立即開會」會議呈現。

- **團隊與頻道分析**：除了團隊分析以外，您現在也可以檢視頻道層級指標和深入資訊。 我們也將時間週期增加到 90 天，使得您可以分析資料的時間較長。 除此以外，此版本還包含有關小組或頻道的文章、回覆和會議計數的新計量和圖表。

- **進入/結束宣告：** 我們新增了此功能，讓會議召集人能夠開啟或關閉會議的進入和結束宣告。

### <a name="word"></a>Word

- **解碼縮寫，而不需離開 Word：** 當您遇到縮寫時，Word 會試著根據其他人的使用方式來給予定義。

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel

- 已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。

- 在某些情況下，按一下同一個活頁簿中某個位置的超連結會導致活頁簿被隱藏。

### <a name="outlook"></a>Outlook

- 已解決有回應/轉寄標註的clp審查活動的問題。

- 解決會導致 Windows 10 伺服器版本的使用者看到警告「防毒軟體狀態: 無效」的問題。 此版本的 Windows 支援防毒軟體偵測，但即使已正確安裝防毒軟體，也找不到防毒軟體。

- 解決從系統管理員通知提交意見反應時，會導致使用者遇到當機的問題。

### <a name="skype"></a>Skype

- 當使用者收到將他們移至 Teams Only 的原則時，他們仍然可以使用商務版 Skype Outlook 增益集來排程會議。 在此更新之後，當客戶端讀取指示用戶為 Teams Only 的策略並進入僅限會議加入模式後，您將不再能用商務版 Skype 安排會議。 此外，如果商務版 Skype Outlook 增益集發現商務版 Skype 用戶端處於 [僅限會議加入] 模式，就無法自行啟動。

### <a name="office-suite"></a>Office 套件

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。

- 此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。

- 當您啟用增益集，而登錄金鑰 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 被設為零時，辦公主機視窗會當機。 這變更將修正此問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-21"></a>版本 2004：5 月 21 日
*版本 2004 (組建 12730.20352)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。


### <a name="outlook"></a>Outlook

- 已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。


### <a name="office-suite"></a>Office 套件

- 修正隨選即用會導致偶爾無法更新至最新組建的問題。

- 解決 Microsoft Office 中的 Visual Basic for Applications 專案，其具有的參照預期應透過搜尋 PATH 環境變數指定的位置來找到，但在執行時期中可能無法正確找到，導致 VBA 執行時期錯誤的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-12"></a>版本 2004：5 月 12 日
*版本 2004 (組建 12730.20270)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決在顯示快顯通知時，使用者遇到當機的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-04"></a>版本 2004：5 月 4 日
*版本 2004 (組建 12730.20250)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="office-suite"></a>Office 套件

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a>版本 2004：4 月 29 日
*版本 2004 (組建 12730.20236)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。 在 SQL 檢視中搜尋及取代文字。 在 [關聯圖] 視窗中選取多個資料表。

- **按幾下就能新增資料表：** 使用 [新增資料表] 工作窗格，當您工作時，該窗格會保持開啟狀態，以便將資料表新增至關聯和查詢。 [深入了解](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a>Excel

- **Facebook 連接器支援即將結束：** 於 2020 年 4 月起，Excel 就不再支援使用 Facebook 連接器的外部資料連線。

- **有問題嗎？詢問 Excel**：現在，Excel 構想可讓您提出有關資料的問題，而不需花時間編寫公式 (僅提供英文版)。 [深入了解](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **讓活頁簿更生動的新影像：** 您可以在活頁簿中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a>Outlook

- **加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。 將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。

- **讓郵件更生動的新影像：** 您可以在電子郵件中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- **週期性會議的位置建議支援：** 搜尋會議室，並排定週期性會議。

### <a name="powerpoint"></a>PowerPoint

- **在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。

- **讓投影片更生動的新影像：** 您可以在投影片中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a>Teams

- **增強 Teams 行事曆功能：** 以滑鼠右鍵按一下行事曆中的項目，以展開 RSVP 選項，開始與會議參與者交談，或在會議開始時快速加入會議。 我們也改善了活動排程表單。

- **抓到你了！：** 建立標籤並將人員指派至標籤，您就可以 @mention 群組、角色、部門等。小組擁有者可以自行嘗試。 移至某個小組，選取 [其他選項]、[管理標籤]。

### <a name="word"></a>Word

- **讓您的工具方便使用：** 在您的繪圖工具箱中，尋找智慧筆，以便在文字中加入筆跡筆勢。 [深入了解](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **讓文件更生動的新影像：** 您可以在文件中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。

- 已修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。

- 在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。

### <a name="outlook"></a>Outlook

- 已解決導致資料夾窗格寬度意外變更的問題。


- 已解決導致 Outlook 在某些 Windows 組建上當機的問題。


- 已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。


- 已解決導致 Outlook 在某些 Windows 組建上當機的問題。


- 已解決導致使用者在退出 Outlook 時遇到掛斷的問題。


### <a name="project"></a>Project

- 在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。


- 已修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。

### <a name="office-suite"></a>Office 套件

- 已解決同時防止限制存取和保護設有密碼之檔案的錯誤。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-15"></a>版本 2003：4 月 15 日
*版本 2003 (組建 12624.20466)*
* 各種錯誤和效能修正。

## <a name="version-2003-april-14"></a>版本 2003：4 月 14 日
*版本 2003 (組建 12624.20442)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。

### <a name="outlook"></a>Outlook

- 解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。

### <a name="project"></a>Project

- 在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。

### <a name="word"></a>Word

- 解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a>版本 2003：3 月 31 日
*版本 2003 (組建 12624.20382)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="onenote"></a>OneNote

- 透過在資訊列中通知使用者有關 Microsoft OneNote 中的暫時調整之資訊，將協助改善在全球高使用量期間的同步處理與服務可用性。

### <a name="project"></a>Project

- 修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-25"></a>版本 2003：3 月 25 日
*版本 2003 (組建 12624.20320)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **您最愛的 Excel 函數計算速度提升了：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS 和 MINIFS 函數現在比以往更快了。 更快速地前往底線。 立即試用。

### <a name="outlook"></a>Outlook

- **將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。 您拖曳的郵件將會與所有群組成員共用。

- **受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？ Outlook 現在會偵測這項要求並協助您取得連結。

###<a name="powerpoint"></a>PowerPoint

- **註解：** PowerPoint 中新增的註解體驗可讓您快速輕鬆地探索文件並新增註解。 使用註解錨定、解決、工作、已改進的提及通知等新功能，現代化您的共同作業工作流程。

### <a name="word"></a>Word

- **其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。

### <a name="office-suite"></a>Office 套件

- **敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 重複開啟內嵌在 Word 或 PowerPoint 中的活頁簿時，在某些情況下，Excel 會當機。

- 解決當來源活頁簿關閉時，外部連結無法在填入時更新的問題。

- 解決從範本建立圖表時的效能問題。

### <a name="onenote"></a>OneNote

- 透過暫時減少新嵌入附件的最大允許尺寸至 50MB，來改善同步處理與服務的穩定性。 對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。

- 透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。

### <a name="outlook"></a>Outlook

- 已解決導致使用者在工作管理員中看到 Outlook 處理序延遲的問題。

### <a name="powerpoint"></a>PowerPoint

- 已改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並貼到迴圈中的其他投影片，可能會出現例外狀況而失敗。


### <a name="project"></a>Project

- 修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。

- 修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。

- 修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。

- 修正無法正確計算摘要任務日期的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-10"></a>版本 2002：3 月 10 日
*版本 2002 (組建 12527.20278)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="powerpoint"></a>PowerPoint

- **投影片連結:** 要求同事參與製作您的投影片組，讓他們直接在您需要協助的投影片上開始進行。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="project"></a>Project

- 修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-01"></a>版本 2002：3 月 1 日
*版本 2002 (組建 12527.20242)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決導致協力廠商應用程式無法傳送電子郵件的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-25"></a>版本 2002：2 月 25 日
*版本 2002 (組建 12527.20194)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **活頁簿統計資料：** 我們會計算儲存格、公式、圖表、表格，這樣您就不需要計算。

- **查詢編輯器中的資料分析：** 取得欄位資料的總覽分析、識別錯誤和空白值，查看分佈長條圖等。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正 CUBEVALUE 函數有時會傳回不正確結果的問題。

### <a name="outlook"></a>Outlook

- 解決導致會議的位置欄位中的逗號變成分號的問題。

- 解決在多個視窗中檢視相同項目時可能會導致當機的問題。

- 已解決導致在某些情況下無法使用相關選項來停用標幟項目醒目提示的問題。

- 解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。


- 解決會導致使用黑色佈景主題的使用者，看到 [寄件者] 下拉式功能表在白色背景上顯示白色文字的問題。


- 此變更會還原在郵件標頭中檢視多行主旨的功能。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-february-19"></a>版本 2001：2 月 19 日
*版本 2001 (組建 12430.20288)*
* 各種錯誤和效能修正。

## <a name="version-2001-february-11"></a>版本 2001：2 月 11 日
*版本 2001 (組建 12430.20264)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


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






[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此更新會修正使用 ADODB 的問題。 VB 程式碼中的記錄器物件可能會不正確地報告錯誤。


- 此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。


### <a name="excel"></a>Excel

- 解決重新命名簽名時，使用者遇到當機的問題。


### <a name="outlook"></a>Outlook

- 解決重新命名簽名時，使用者遇到當機的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-january-22"></a>版本 1912：1 月 22 日
*版本 1912 (組建 12325.20344)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-january-14"></a>版本 1912：1 月 14 日
*版本 1912 (組建 12325.20298)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

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

- 建置組塊組合管理可能會顯示無效的通知：「您已經修改樣式、建置組塊」。

### <a name="office-suite"></a>Office 套件

- 解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> 如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。

[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|CC|Production| |16.0.13530.20376|version-2012-january-12|)
[//]: # (|Win32|CC|Production| |16.0.13530.20316|version-2012-january-05|)
[//]: # (|Win32|CC|Production| |16.0.13426.20404|version-2011-december-21|)
[//]: # (|Win32|CC|Production| |16.0.13426.20332|version-2011-december-08|)
[//]: # (|Win32|CC|Production| |16.0.13426.20308|version-2011-december-02|)
[//]: # (|Win32|CC|Production| |16.0.13426.20294|version-2011-november-30|)
[//]: # (|Win32|CC|Production| |16.0.13426.20274|version-2011-november-23|)
[//]: # (|Win32|CC|Production| |16.0.13328.20408|version-2010-november-17|)
[//]: # (|Win32|CC|Production| |16.0.13328.20356|version-2010-november-10|)
[//]: # (|Win32|CC|Production| |16.0.13328.20292|version-2010-october-27|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
