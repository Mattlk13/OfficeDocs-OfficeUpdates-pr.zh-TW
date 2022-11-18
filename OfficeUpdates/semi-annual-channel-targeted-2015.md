---
title: 2015 年Semi-Annual通道 (目標) 版本的版本資訊
ms.author: dacoulte
author: andymosten
manager: anankani
ms.date: 12/8/2015
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2015 年 Office 365 專業增強版 Semi-Annual 通道 (目標) 版本的版本資訊
ms.openlocfilehash: 952507e5b2f1c7c537b633a2c525d06cd24e7a28
ms.sourcegitcommit: dd346b30e044f8e27f3994f9266ff925e2217362
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/13/2022
ms.locfileid: "64825457"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2015"></a>2015 年Semi-Annual通道 (目標) 版本的版本資訊

這些版本資訊提供新功能、安全性更新和非安全性更新的相關資訊，這些更新包含在 2015 年 Semi-Annual 通道 (Office 365 專業增強版的目標) 更新中。
 
> [!NOTE]
> - 下面也會提供 Visio Pro for Office 365 和 Project Online 桌面用戶端新功能、安全性更新和非安全性更新的相關資訊。
> - 此資訊也適用於 Office 365 商務版，這是隨附一些 Office 365 方案 (例如，商務進階版) 的 Office 版本。
> - Semi-Annual通道 (目標) 在 2017 年 9 月之前命名為延後通道的第一個版本。


## <a name="version-1509-december-8"></a>版本 1509：12 月 8 日
*版本 1509 (組建 6001.1043)*

### <a name="onenote-non-security-updates"></a>OneNote：非安全性更新
-   修正此問題：XPS 或使用 Windows 桌面用戶端所建立的列印成品，在非 Windows 桌面用戶端呈現為紅色的 X，因為這些用戶端不支援原生 XPS 轉譯。

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：已建立橫跨多個段落的書籤，但收到電子郵件時，使用 [移至] 時僅會選取書籤的第一個段落。

### <a name="skype-for-business-security-updates"></a>商務用 Skype：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-128](/security-updates/SecurityBulletins/2015/ms15-128)：解決遠端程式碼執行問題的 Microsoft 圖形元件安全性更新 (3104503)

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正此問題：應用程式共用的工作階段失敗，尤其是在流量爆發的期間。
-   修正此問題：在安裝 Office 2016 後，若第一個使用的應用程式為商務用 Skype 時會導致當機。

### <a name="word-security-updates"></a>Word：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-131](/security-updates/SecurityBulletins/2015/ms15-131)：解決遠端程式碼執行問題的 Microsoft Office 安全性更新 (3116111)

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：在使用某些字型時，不分行連字號會顯示為正方形。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   將背景下載更新的預設傳輸，從快取/位元變更為 HTTP。
-   修正此問題：在自動升級期間，因授權相關的動作失敗，讓使用者沒有 Office 安裝。
-   修正此問題：若 Windows 7 OEM 電腦的稽核模式中已執行 Office 預先安裝套件，在此電腦上升級至 Office 2016 時，會造成啟用期間發生錯誤 0x80070005。



## <a name="version-1509-november-10"></a>版本 1509：11 月 10 日
*版本 1509 (組建 6001.1038)*

### <a name="access-security-updates"></a>Access：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116)：解決遠端程式碼執行問題的 Microsoft Office 安全性更新 (3104540)

### <a name="excel-security-updates"></a>Excel：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116)：解決遠端程式碼執行問題的 Microsoft Office 安全性更新 (3104540)

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：錄製查詢建立的巨集會導致編譯錯誤。
-   修正此問題：在 [查詢編輯器] 中刪除資料行之後，重新整理查詢後在資料表結尾處會顯示空白的資料行。
-   修正此問題：在查詢資料表的 [快速分析] 中選擇 [Sparklines] 索引標籤時，會發生未預期的錯誤。
-   修正此問題：在查詢資料表中執行剪下貼上的作業之後，無法使用 [活頁簿查詢] 窗格重新整理查詢。
-   修正此問題：當您重新整理查詢時，焦點會移到其相關聯查詢資料表的工作表。
-   從錯誤訊息中移除有關支援 OData 版本的 Power Query 參考。
-   修正此問題：當產品尚未啟動時，Power Query 顯示為可用的功能但沒有作用。
-   更新 [檔案 \> 帳戶 \> 關於 Excel] 中 Dotlesscss 的 URL。

### <a name="onenote-security-updates"></a>OneNote：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116)：解決遠端程式碼執行問題的 Microsoft Office 安全性更新 (3104540)

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：將文字貼到 Outlook 時，如果貼上的文字數量大於視窗的高度，就不會顯示全文。

### <a name="powerpoint-security-updates"></a>PowerPoint：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116)：解決遠端程式碼執行問題的 Microsoft Office 安全性更新 (3104540)

### <a name="project-security-updates"></a>Project：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116)：解決遠端程式碼執行問題的 Microsoft Office 安全性更新 (3104540)

### <a name="publisher-security-updates"></a>Publisher：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116)：解決遠端程式碼執行問題的 Microsoft Office 安全性更新 (3104540)

### <a name="skype-for-business-security-updates"></a>商務用 Skype：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116)：解決遠端程式碼執行問題的 Microsoft Office 安全性更新 (3104540)
-   Microsoft 資訊安全佈告欄 [MS15-123](/security-updates/SecurityBulletins/2015/ms15-123)：解決資訊洩漏問題的商務用 Skype 和 Microsoft Lync 安全性更新 (3105872)

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正此問題：有兩個輸入麥克風的裝置音訊有雜音。
-   修正此問題：膝上型電腦從睡眠模式恢復後、且 Skype 用戶端尚未簽入前，使用者無法成功地加入會議。
-   加入對內容相關訊息的支援，以協助提供功能感知給使用者。
-   更新 [加入會議音訊] 對話方塊中的文字，以引導使用者到 UI 中的正確位置去變更設定。
-   修正通知的問題，即使用者同時遇到網路傳送和接收問題時看到的通知。

### <a name="visio-security-updates"></a>Visio：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116)：解決遠端程式碼執行問題的 Microsoft Office 安全性更新 (3104540)

### <a name="word-security-updates"></a>Word：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116)：解決遠端程式碼執行問題的 Microsoft Office 安全性更新 (3104540)

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：當文件中有註腳設定為「每一頁重新編號」，並在背景中列印文件時，顯示在 Word 中和列印成品上的註腳編號不同。
-   修正此問題：即時共同撰寫不適用於儲存在 OneDrive 的檔案，包括使用者即時編輯時未顯示讓其他人得知，以及沒有顯示出席資訊。
-   修正此問題：在從 SharePoint 或 OneDrive 開啟的文件上進行即時共同撰寫時，Word 會當機。
-   修正格式問題：將資料表放入 Outlook 中的 HTML 電子郵件，並重新調整視窗大小時，格式問題導致資料表無法正確呈現。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-116](/security-updates/SecurityBulletins/2015/ms15-116)：解決遠端程式碼執行問題的 Microsoft Office 安全性更新 (3104540)

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正此問題：當使用者嘗試從 SharePoint Online 開啟檔案時，會重複提示使用者登入。
-   修正此問題：在手動升級期間，系統不會替所有使用者移除已釘選在工作列上的捷徑。
-   在隨選即用手動升級程序加入新的能力，可偵測 Outlook 是否連線到 Exchange Server 2007 或是否已安裝 Business Contact Manager，以警告使用者可能的升級問題。
-   將解除安裝或升級期間的結束程序對話方塊變得更明顯，因為這些對話方塊可能被藏在開啟的應用程式或其他 UI 背後使用者看不到。
-   修正此問題：當使用者使用的電腦被識別為已加入網域和雲端網域時，不會將使用者自動登入 Office 應用程式。



## <a name="version-1509-october-21"></a>版本 1509：10 月 21 日
*版本 1509 (組建 6001.1034)*

### <a name="onenote-non-security-updates"></a>OneNote：非安全性更新
-   修正此問題：在色彩選擇器中，選取了兩次框線相同的色彩時會導致 OneNote 當機。

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：在編輯電子郵件簽章時，螢幕助讀程式只會讀取多個段落電子郵件簽章的第一段。
-   修正此問題：在撰寫或回覆電子郵件時，滑鼠指標不在正確的位置。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正此問題：在記憶體不足的情況下，嘗試檢視共用的桌面或應用程式會導致中斷連線，以及重複的嘗試自動重新加入與檢視共用的桌面或應用程式。
-   修正此問題：當參與者人數增加時，共用桌面體驗會變得更糟。
-   修正此問題：在設定多因素驗證之後，一天之內會收到重複的提示，要求進行電話驗證。

### <a name="visio-non-security-updates"></a>Visio：非安全性更新
-   修正此問題：關閉並重新開啟 Visio 之後，要顯示為圖示的已插入 Word 物件會變得空白。

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：文件在 SharePoint Server 2013 中無法使用共同撰寫，且文件會遭到鎖定。
-   修正此問題：在 docx 文件中，即便資料表中的內容有包括 [隱藏] 選項的樣式，資料表仍然可見。
-   修正此問題：在執行自動更正後，無法儲存具有相關超連結的文件。
-   修正此問題：使用鏡像縮排在文件中編輯段落時，行會四處跳動。
-   修正此問題：停用子像素定位時，在編輯期間行顯示會發生不一致。
-   修正此問題：按一下具有多個註解的快顯視窗，而其中第一個註解標記為完成時，將會造成當機。
-   修正分行不正確的問題。
-   修正此問題：執行在文件中使用 TransformDocument 函式，且在頁首或頁尾帶有文字方塊的巨集，將會造成當機。
-   修正 .docm 文件的問題：當文件開啟時，移除所有 ActiveX 控制項會造成錯誤。
-   修正此問題：按進頁首時不會觸發 ContentControlOnExit 事件。
-   修正此問題：追蹤修訂顯示具有相同名稱的檢閱者的刪除記錄。
-   修正即時共同撰寫文件設定移除個人資訊的問題：每次儲存文件時，將變更顯示為追蹤修訂。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正此問題：升級至 2016 後第一次開啟 Office 應用程式，會導致應用程式處於精簡的功能模式，且需要重新啟動應用程式才能取得完整功能。
-   修正此問題：使用共用電腦啟用執行 Office，而且該啟用是處於執行遠端桌面服務的電腦上時，會在開啟應用程式時導致錯誤，告訴使用者需要使用 Office 的大量授權版本。
-   修正此問題：安裝過程會在 90% 完成時卡住。
-   修正此問題：不該當地語系化的產品名稱具有當地語系。
-   修正此問題：「操作說明搜尋」的工具提示和按鍵提示不相符，並與其他各種當地語系化版本中的功能區按鍵提示發生衝突。
-   修正此問題：從 Office 2013 升級至 Office 2016 之後，Windows 將 Outlook 顯示為新的應用程式。
-   修正此問題：從 Office 2013 版本 15.0.4615.1002 (2014 年 5 月) 升級至 Office 2016 會產生 0x80041015 錯誤。



## <a name="version-1509-october-5"></a>版本 1509：10 月 5 日
*版本 1509 (組建 4229.1029)*

### <a name="onenote-non-security-updates"></a>OneNote：非安全性更新
-   修正 Office 365 商務版的問題：嘗試搭配使用 SharePoint 與 OneNote 會導致錯誤訊息，告訴使用者他們必須升級至不同版本的 Office 版本。
-   修正 Surface Pro 3 的問題：錄影預覽不會顯示錄下的內容。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   變更當共享者鎖定 RDP 中的畫面時，檢視者看到的東西。檢視者會看到一則通知，而非 RDP 暫停影像。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正隨選即用的問題：如果 Office 2016 自動更新因為錯誤或使用者取消而沒有完成，則不會還原 Office 2013 隨選即用的服務。
-   修正隨選即用的問題：Office 2016 自動更新期間發生錯誤而導致更新失敗，且無法使用或解除安裝 Office 2013 應用程式。
-   修正隨選即用的問題：在先前嘗試更新的期間重新開機後重新嘗試自動更新至 Office 2016，會導致更新失敗和無法關機。
-   修正隨選即用的問題：安裝期間如果電腦重新開機，資料流工作無法順利復原。
-   修正隨選即用的問題：在手動更新至 Office 2016 期間重新開機會使工作處於「執行中」狀態。
-   修正隨選即用的問題：在安裝程序進行期間啟動新安裝的應用程式，會導致「網際網路連線遺失」對話方塊的出現。
-   修正隨選即用的問題：在安裝期間顯示的應用程式磚沒有作用，當使用者按一下應用程式磚時不會啟動該應用程式。
-   修正隨選即用的問題：自動更新 sr-latn-cr 安裝至 Office 2016 並不會將用戶端語言轉換為 sr-latn-rs。
-   修正隨選即用的問題：在準備更新時若電腦上已安裝多個 Office SKU，自動更新會失敗。
-   修正隨選即用的問題：啟動手動更新時如果自動更新正在執行，會出現錯誤對話方塊。
-   更新產品 UI 中「增益集」的參考，其詞彙的大小寫不正確。



## <a name="version-1509-september-22"></a>版本 1509：9 月 22 日
*版本 1509 (組建 4229.1024)*

這是此通道的最初發行版本。這是第一個提供 Office 2016 應用程式的發行版本。

### <a name="excel-security-updates"></a>Excel：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-099](/security-updates/SecurityBulletins/2015/ms15-099)：Microsoft Office 的弱點可能會允許遠端程式碼執行 (3089664)
-   Microsoft 資訊安全佈告欄 [MS15-110](/security-updates/SecurityBulletins/2015/ms15-110)：解決遠端程式碼執行問題的 Microsoft Office 安全性更新 (3096440)

### <a name="visio-security-updates"></a>Visio：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-081](/security-updates/SecurityBulletins/2015/ms15-081)：Microsoft Office 的弱點可能會允許遠端程式碼執行 (3080790)

### <a name="word-security-updates"></a>Word：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-081](/security-updates/SecurityBulletins/2015/ms15-081)：Microsoft Office 的弱點可能會允許遠端程式碼執行 (3080790)

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   Microsoft 資訊安全佈告欄 [MS15-081](/security-updates/SecurityBulletins/2015/ms15-081)：Microsoft Office 的弱點可能會允許遠端程式碼執行 (3080790)
-   Microsoft 資訊安全佈告欄 [MS15-099](/security-updates/SecurityBulletins/2015/ms15-099)：Microsoft Office 的弱點可能會允許遠端程式碼執行 (3089664)