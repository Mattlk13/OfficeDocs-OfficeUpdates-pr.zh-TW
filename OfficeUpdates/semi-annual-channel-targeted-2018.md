---
title: 2018 年半年通道 (已設定目標) 版本的版本資訊
ms.author: dacoulte
author: andymosten
manager: anankani
ms.date: 12/13/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2018 年 Office 365 專業增強版半年通道 (已設定目標) 版本的版本資訊
ms.openlocfilehash: 9d48e7bc08b3c91f3c88149afeccbc30063efa2a
ms.sourcegitcommit: dd346b30e044f8e27f3994f9266ff925e2217362
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/13/2022
ms.locfileid: "64825417"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2018"></a>2018 年半年通道 (已設定目標) 版本的版本資訊

這些版本資訊會提供 2018 年 Office 365 專業增強版的半年通道 (已設定目標) 更新所含新功能、安全性更新和非安全性更新的相關資訊。
 
> [!NOTE]
> - 下面也會提供 Visio Pro for Office 365 和 Project Online 桌面用戶端新功能、安全性更新和非安全性更新的相關資訊。
> - 此資訊也適用於 Office 365 商務版，這是隨附一些 Office 365 方案 (例如，商務進階版) 的 Office 版本。

 
> [!NOTE]
> - [安全性更新](microsoft365-apps-security-updates.md)將開始各別列出每個 Office 365 專業增強版更新通道的安全性更新資訊。

## <a name="version-1808-december-11"></a>版本 1808：12 月 11 日
*版本 1808 (組建 10730.20262)*

### <a name="excel-security-updates"></a>Excel：安全性更新 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598)：Microsoft Excel 資訊洩漏弱點 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627)：Microsoft Excel 資訊洩漏弱點 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636)：Microsoft Excel 遠端程式碼執行弱點 

### <a name="outlook-security-updates"></a>Outlook：安全性更新 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587)：Microsoft Outlook 遠端程式碼執行弱點 

### <a name="powerpoint-security-updates"></a>PowerPoint：安全性更新 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628)：Microsoft PowerPoint 遠端程式碼執行弱點 

### <a name="excel-non-security-updates"></a>Excel：非安全性更新 

- 已修正此問題：在共同撰寫工作階段中，當另一位使用者對交叉分析篩選器中的資料套用資料行篩選後，交叉分析篩選器未正確更新。
- 已修正此問題：在共同撰寫工作階段中，當其中一位使用者清除交叉分析篩選器的說明文字時，會導致共同撰寫工作階段中的另一位使用者遇到 Excel 損毀。
- 已修正此問題：建立多個繫結至相同資料行的表格交叉分析篩選器時可能發生損毀，並刪除該行資料。
- 已修正此問題：關閉自動調整欄寬的選項後，Excel 有時在重新整理儲存格中有換行文字的已篩選查詢資料表時會發生損毀。
- 已修正此問題：儲存在 Excel 2007 中的交叉分析篩選器若在較新版的 Excel 中開啟，且交叉分析篩選器中顯示的項目有變更，則可能觸發損毀。
- 引進 [取得診斷] 按鈕的支援，以簡化支援要求的調查。

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新

- 已修正使用者啟動 [管理規則及通知] 對話方塊時看到錯誤訊息的問題。
- 已修正此問題：使用者使用計量付費連線時，無法透過 DirectAccess 連線到他們的信箱。
- 已修正此問題：使用者會看到儲存在公用資料夾中的可用文件錯誤地在「受保護的檢視」中開啟。
- 已修正此問題：使用者轉寄具有內嵌附件的項目時，會看到非預期的附件。
- 已修正 OFT 檔案在作為附件傳送後，呈現效果不良的問題。
- 已修正此問題：部分增益集使用者在將會議新增至共用行事曆時遇到損毀問題。
- 已修正以下問題：使用者開啟 [交談歷程記錄] 資料夾時遇到當機問題。

### <a name="project-non-security-updates"></a>Project：非安全性更新

- 已修正在專案中支援新委內瑞拉貨幣的相關問題。
- 已修正此問題：專案若使用連線到外部監視器的介面 Surface 4，可能會停止回應。
- 已修正此問題：將專案儲存為 XML 格式時，專案可能會損毀。
- 已修正此問題：企業資源自訂欄位可能會在編輯資源的行事曆後遭到刪除。
- 已修正此問題：使用者搜尋韓文的顯示名稱時會遇到損毀問題。

## <a name="version-1808-november-13"></a>版本 1808：11 月 13 日
*版本 1808 (組建 10730.20205)*

### <a name="excel-security-updates"></a>Excel：安全性更新

-   [CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577)：Microsoft Excel 遠端程式碼執行弱點 

### <a name="outlook-security-updates"></a>Outlook：安全性更新 

-   [CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522)：Microsoft Outlook 遠端程式碼執行弱點 
-   [CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524)：Microsoft Outlook 遠端程式碼執行弱點 
-   [CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558)：Microsoft Outlook 資訊洩漏弱點 
-   [CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576)：Microsoft Outlook 遠端程式碼執行弱點 
-   [CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579)：Microsoft Outlook 資訊洩漏弱點 
-   [CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582)：Microsoft Outlook 遠端程式碼執行弱點 

### <a name="project-security-updates"></a>Project：安全性更新 

-   [CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575)：Microsoft Project 遠端程式碼執行弱點 

### <a name="word-security-updates"></a>Word：安全性更新 

-   [CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573)：Microsoft Word 遠端程式碼執行弱點 

### <a name="skype-for-business-security-updates"></a>商務用 Skype：安全性更新 

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546)：Microsoft 商務用 Skype 阻絕服務弱點 

### <a name="excel-non-security-updates"></a>Excel：非安全性更新 

- 修正了在某些組建/版本中未出現 Power Pivot 的錯誤。

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新 

- 修正此問題：使用者無法順利使用 [帳戶] 控制按鈕在自訂表單上切換帳戶。
- 修正此問題：使用者使用 ScanPST 修復 OST/PST 檔案時發生當機。
- 修正此問題：特定郵件上的 [副本:] 欄位無法顯示設定檔為線上模式的使用者。

### <a name="onenote-non-security-updates"></a>OneNote：非安全性更新 

- 修正了可能發生的穩定性問題，包括同步處理和瀏覽至刪除的部分。

### <a name="project-non-security-updates"></a>Project：非安全性更新 

- 修正此問題：如果您使用新的新式體驗 SharePoint 文件庫上的 Project 檔案，「需要取出」和「唯讀」動作沒有正確執行。


## <a name="version-1808-october-9"></a>版本 1808：10 月 9 日
*版本 1808 (組建 10730.20155)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502)：Microsoft Excel 遠端程式碼執行弱點 

### <a name="outlook-security-updates"></a>Outlook：安全性更新 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026)：Microsoft Office 深度防禦更新 

### <a name="powerpoint-security-updates"></a>PowerPoint：安全性更新 
-   [CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501)：Microsoft PowerPoint 遠端程式碼執行弱點

### <a name="word-security-updates"></a>Word：安全性更新 
-   [CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504)：Microsoft Word 遠端程式碼執行弱點 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026)：Microsoft Office 深度防禦更新 

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新 
-   [CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432)：Microsoft Graphics 元件遠端程式碼執行弱點 

### <a name="excel-non-security-updates"></a>Excel：非安全性更新 
-   修正此問題：當 2190 到 2194 範圍內的符號切換為 Cambria Math 字型，會造成 Excel 儲存格的高度增加 3 倍。
-   修正以下的 Excel 問題：當使用者將滑鼠停留在具有多個定義名稱的活頁簿中的格式選項上，Excel 可能無反應，而且即使在格式選項中停用了即時預覽，Excel 也可能在快速分析工具中無反應。
-   我們目前正在調查，當 Excel 應用程式視窗從一個桌面移動到另一個桌面時，效能降低的問題。 同時，如果您發現到這種效能降低的問題，請試試在「檔案選項」對話方塊裡的「一般」索引標籤中將「當使用多個顯示器時」設定為「相容性最佳化」。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正了使用 ActiveX 內容來儲存文件時，可能造成文件損毀的問題。

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正了插入 Word 文件物件時，會出現方程式編輯器的問題。

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正此問題：如果為列印工作設定頁首或頁尾，無法在下次列印專案時保留所做的變更。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正了儘管已透過協助功能和效能設定關閉動畫後，應用程式仍會顯示動畫的問題。 
-   修正了使用螢光筆繪圖工具時背景變為空白的問題。

## <a name="version-1808-september-11"></a>版本 1808：9 月 11 日
*版本 1808 (組建 10730.20102)*

### <a name="access-feature-updates"></a>Access：功能更新
 - **使用新圖表以視覺化方式呈現資料：** 從 11 個圖表中選擇，並將其中一個新增至您的表單和報告，更有效地以視覺化方式呈現資料並進行明智的決策。[深入了解](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)
 
 ### <a name="access-security-updates"></a>Access：安全性更新
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點

### <a name="excel-feature-updates"></a>Excel：功能更新
 - **共同作業編輯：** 在您的活頁簿中與他人同時作業。[深入了解](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **現在已預設啟用 AutoSave 雲端檔案：** AutoSave 在 2018 年 9 月的半年通道 (已設定目標) 版本中已預設為啟用。這項改變代表使用者再也無須擔心儲存在 OneDrive 或 SharePoint Online 上的文件變更會遺失。變更將會自動儲存在雲端，使用者再也不需要按下 Ctrl + S 鍵或 [儲存] 按鈕。但使用者必須了解這項動作改變，以防意外變更文件。使用者可以用畫面頂端的 AutoSave 切換開關停用 AutoSave。建議您通知使用者這項近期改變，並提供有關這項 Office 365 全新功能的使用教學。[深入了解 AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [深入了解 IT 系統管理員須知的 AutoSave 相關內容](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **改善儲存格和資料編輯列編輯：** 您現在可以使用 CTRL + A 來選取儲存格或資料編輯列中的文字。另外也改善了 Emoji 和其他複雜字元的支援。[深入了解](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **改善協助工具檢查程式︰** 協助工具檢查程式已更新對國際標準與建議的支援，以使您的活頁簿更易於存取。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **避免不想要的編輯：** 設定您的活頁簿開啟為唯讀，以避免意外變更。移至 [檔案 > 資訊 > 保護活頁簿 > 一律以唯讀開啟]

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 遠端程式碼執行弱點

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正了從原儲存格變更圖表來源資料時 Excel 可能會損毀的問題。
-   修正了即使已設定 FullCalcOnLoad 屬性，開啟時也可能不會算的問題。  
-   修正此問題：在日期儲存格格式使用日本紀元日曆時顯示錯誤年份。
-   當資料匯入 Excel 資料模型中，負值或零的輸入值會造成錯誤。此修正會將此類的值匯入為零。
-   修正 Excel 樞紐分析表中的群組 (或取消群組) 作業有時候會觸發當機的問題。
-   修正此問題：在圖表上動作可能會造成 Excel 當機。
-   修正此問題：部分使用者不小心停用 Power View 增益集。
-   修正此問題：在文件復原期間建立的暫時自動復原檔案永遠不會清除。
-   修正此問題：在嘗試與受保護 Workbook 中的文字檔建立新連線時，收到「Workbook 受到保護，且無法變更」錯誤訊息。
-   修正此問題：快速列印附加至 Outlook 電子郵件的 Excel 活頁簿可能會列印不出來。
-   修正此問題：按一下超連結可能會造成 Excel 當機。
-   修正此問題：使用 cube 函式會造成 Excel 當機。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
 - **改善協助工具檢查程式︰** 協助工具檢查程式已更新對國際標準與建議的支援，以使您的郵件更易於存取。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
 - **從設定檔選擇器管理設定檔：** 如果您習慣在 Outlook 啟動時使用設定檔選擇器，現在不用去 [控制台] 也能進行變更。建立及刪除設定檔、變更設定，全都能在 [設定檔選擇器] 一次搞定。
- **內建的協助工具：** 在圖片上新增替代文字，即可讓每個人存取相關訊息。
- **Outlook 增益集警告：** 有時 Outlook COM 增益集會發生問題，讓其餘 Outlook 功能變慢。這些問題可能是因為以下的事件延遲：在 Outlook 資料夾之間進行切換、新的電子郵件送達、開啟行事曆項目等等。當這類問題發生時，Outlook 會在通知列中顯示警告。
- **了解要參與會議的人員：** 即使您不是召集人，也可以看到其他人對於會議邀請的回應。
- **絕不錯過任何提醒：** 將提醒設定為在您正在工作的視窗上彈出。否則，Outlook 會在工作列中閃爍，以引起您的注意。[深入了解](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **將刪除的郵件標示為已讀取：** 您現在可以將任何已刪除的郵件標示為已讀取。請移至 [檔案] \> [選項] \> [郵件] \> [其他] 來選擇使用。
- **檢視三個時區：** 需要跨時區排程會議嗎？將多個時區新增至行事曆，方便檢視所有人員的空檔，並挑選出所有人都可行的時間。[深入了解](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
- **改善建立群組的使用者體驗：** 我們已精簡建立群組的使用者體驗，讓它看起來更整齊現代化。[深入了解](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 竄改弱點
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 提高權限弱點
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全性功能略過的弱點
-   [ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021)：Microsoft Office 深度防禦更新

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：如果將系統語言切換為日文，並在載入 Outlook 時嘗試輸入 VBA IDE 時，畫面會凍結。
-   修正此問題：切換到 [寄件匣] 或 [寄件備份] 資料夾造成 Outlook 當機。
-   修正此問題：會議內文或附件變更時所有出席者收到會議更新，而非傳送會議更新給選擇性的出席者。
-   修正此問題：因為使用者代理程式字串中的變更，造成使用者無法連線到 EWS 及 REST 端點。
-   修正此問題：出席者的會議位置更新是顯示舊的位置而不是新的位置。
-   修正此問題：使用者在預覽讀取窗格中的附件時，會看到錯誤。
-   修正此問題：當使用者在撰寫電子郵件時，解決電子郵件地址的顯示名稱會使 Outlook 當機。
-   修正此問題：有些使用者未收到其租用戶系統管理員已啟用的支援功能。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新 
- **現在已預設啟用 AutoSave 雲端檔案：** AutoSave 在 2018 年 9 月的半年通道 (已設定目標) 版本中已預設為啟用。這項改變代表使用者再也無須擔心儲存在 OneDrive 或 SharePoint Online 上的文件變更會遺失。變更將會自動儲存在雲端，使用者再也不需要按下 Ctrl + S 鍵或 [儲存] 按鈕。但使用者必須了解這項動作改變，以防意外變更簡報。使用者可以用畫面頂端的 AutoSave 切換開關停用 AutoSave。建議您通知使用者這項近期改變，並提供有關這項 Office 365 全新功能的使用教學。[深入了解 AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [深入了解 IT 系統管理員須知的 AutoSave 相關內容](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **轉換筆跡：** 擷取草草寫下的筆記和繪圖，並將其轉換為可供閱讀的文字和簡潔的圖形，以建立精美的簡報。 [深入了解](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
- **改善 SVG 支援：** 您可以將已套用篩選的 SVG 插入。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **使用手寫筆為投影片撰寫標題：** 使用手寫筆輸入標題，並觀看 PowerPoint 將它轉換成文字。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **避免不想要的編輯：** 設定您的活頁簿開啟為唯讀，以避免意外變更。移至 [檔案 > 資訊 > 保護活頁簿 > 一律以唯讀開啟]
- **改善協助工具檢查程式︰** 協助工具檢查程式已更新對國際標準與建議的支援，以使您的簡報更易於存取。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：表格以粗框線錯誤編譯。
-   修正當變更 Shape.Visibile 屬性時可能會造成當機的問題。
-   修正共同撰寫文件中的變更無法合併的問題。
-   修正包含 ActiveX 控制項的文件會造成共同撰寫失敗的問題。
-   修正此問題：在圖形中使用拼字校正時會造成 PowerPoint 當機。
-   修正此問題：PowerPoint 在從 SharePoint Online 開啟檔案時損毀。
-   修正此問題：開啟 [自動儲存] 時，[復原] 窗格不正確地顯示。
-   修正此問題：未顯示登入，使得使用者無法存取檔案。
-   修正此問題：多個使用者在相同簡報上共同撰寫會導致投影片母片不正確重複。
-   修正此問題：將儲存在 OneDrive 中的檔案開啟時，結束受保護的檢視時會導致 PowerPoint 當機。

### <a name="project-feature-updates"></a>Project：功能更新 
- **短期衝刺管理：** 快速新增、 更新或刪除敏捷短期衝刺。
- **工作面板篩選：** 篩選重要資源或摘要任務，以簡化您的工作面板。
- **從工作面板設定完成百分比：** 針對每個資料行選擇完成百分比，然後透過拖放更新工作完成度。
- **短期衝刺瀏覽：** 從某個短期衝刺檢視切換到另一個檢視，並快速地在短期衝刺之間移動工作。
- **管理短期衝刺的全新方法：** 採取敏捷方式來使用工作面板。隨著專案的發展，請移至 [管理短期衝刺] 來新增或移除短期衝刺。
- **使用最近的儲存位置保持組織：** 專案會保存您已儲存其他專案位置的持續清單。當您準備好要儲存專案時，只需選擇其中一個您最近的儲存位置，就能繼續進行您一天的工作。

### <a name="project-non-security-updates"></a>Project 非安全性更新
- 修正此問題：當您透過主要專案使用子專案時，系統阻止您儲存子專案。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正與 TLS 1.2 支援相關的問題。(附註：這是 4 月 10 日的資訊曾經提及的同一個修正。但在這裡，它變成 9 月彙總套件的一部分，並且再被提及一次。)
-   修正此問題：在會議中以選取 [Skype 通話] 的方式新增使用者會產生錯誤。
-   如果已將 Skype 會議室新增為位置，且會議已包含小組會議座標，請移除要求使用者將 Skype 座標新增至會議的提示。
-   修正此問題：即使 UseLocationForE911Only 設定為 true，也會填入位置。
-   修正此問題：使用名冊中的「使用會議中心呼叫」選項來邀請使用者時，商務用 Skype 會當機。
-   修正此問題：建立商務用 Skype 會議時，在終端機伺服器上運行的Outlook 會凍結。
-   將 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的預設值變更為 TRUE。

### <a name="visio-feature-updates"></a>Visio：功能更新
- **讓您的圖表和來源能保持同步：** 當您在 Visio 中編輯 [資料視覺化工具] 圖表時，可以選擇用最新的圖表內容來更新連結的 Excel 來源資料。
- **資料視覺化工具稽核範本：** 從 Excel 匯入內容，並建立金融交易、庫存管理等稽核圖表。
- **入門圖表：** 組織圖、腦力激盪和 SDL 範本有新的入門圖表可讓您快速啟動並執行。
 - **從 Visio 圖形建立 Word 文件：** 自動將圖表內容 (包括圖形和中繼資料) 新增至 Word 文件。然後自訂文件以建立程序指導方針和操作手冊。[深入了解](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="word-feature-updates"></a>Word：功能更新
- **現在已預設啟用 AutoSave 雲端檔案：** AutoSave 在 2018 年 9 月的半年通道 (已設定目標) 版本中已預設為啟用。這項改變代表使用者再也無須擔心儲存在 OneDrive 或 SharePoint Online 上的文件變更會遺失。變更將會自動儲存在雲端，使用者再也不需要按下 Ctrl + S 鍵或 [儲存] 按鈕。但使用者必須了解這項動作改變，以防意外變更簡報。使用者可以用畫面頂端的 AutoSave 切換開關停用 AutoSave。建議您通知使用者這項近期改變，並提供有關這項 Office 365 全新功能的使用教學。[深入了解 AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [深入了解 IT 系統管理員須知的 AutoSave 相關內容]
- **改善協助工具檢查程式︰** 協助工具檢查程式已更新對國際標準與建議的支援，以使您的文件更易於存取。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **改善 SVG 支援：** 您可以將已套用篩選的 SVG 插入。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-security-updates"></a>Word：安全性更新
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430)：Windows PDF 遠端程式碼執行弱點
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 資訊洩漏弱點

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正造成顯示記憶體不足訊息的問題。
-   修正了防止部分使用者開啟受 IRM 保護的文件和電子郵件 (由其他組織中的人員與他們共用) 的一些問題。
-   修正一些效能問題。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332)：Win32k 圖形遠端程式碼執行弱點
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 遠端程式碼執行弱點
-   
  **基於安全原因已封鎖 Flash、Silverlight、Shockwave 控制在 Office 中啟動：** 基於安全原因，Windows 上新組建的 Microsoft Office for Office 365 會封鎖 Flash、Silverlight、Shockwave 控制的啟動。請看[這裡](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)和[這裡](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US)深入了解。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-  已修正導致更新安裝在特定情況下需要很長時間的問題。
-  修正此問題：開啟應用程式時，使用者可能會看到以安全模式啟動的訊息，然後應用程式無法開啟。
-  修正一些效能問題。

## <a name="version-1803-august-14"></a>版本 1803：8 月 14 日
*版本 1803 (組建 9126.2275)*

### <a name="access-security-updates"></a>Access：安全性更新
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 資訊洩漏弱點 

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021)：Microsoft Office 深度防禦更新 

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 資訊洩漏弱點 

## <a name="version-1803-july-10"></a>版本 1803：7 月 10 日
*版本 1803 (組建 9126.2259)*

### <a name="access-security-updates"></a>Access：安全性更新
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 竄改弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 遠端程式碼執行弱點

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：在日期儲存格格式使用日本紀元日曆時顯示錯誤年份。
-   當資料匯入 Excel 資料模型中，負值或零的輸入值會造成錯誤。此修正會將此類的值匯入為零。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：表格以粗框線錯誤編譯。

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正此問題：如果工作以成本資源分割，成本資源未正確更新，且成本遺失。
-   修正時間表檢視的問題：在 [將現有工作新增至時間表] 對話方塊中，只會出現來自第一個摘要工作中的工作。
-   修正此問題：從 Project Online 或 Project Server 將主要專案儲存為 XML 時失敗。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正會導致更新安裝在特定情況下耗費長時間的錯誤。 
-   修正此問題：SVG 測試失敗
-   修正當使用 Configuration Manager 將更新部署至執行 Office 應用程式的用戶端時，更新未在 Office 應用程式執行時並重新啟動裝置之後套用的問題。


## <a name="version-1803-june-12"></a>版本 1803：6 月 12 日
*版本 1803 (組建 9126.2227)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 遠端程式碼執行弱點

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正 Excel 樞紐分析表中的群組 (或取消群組) 作業有時候會觸發當機的問題。

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 提高權限弱點

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正當變更 Shape.Visibile 屬性時可能會造成當機的問題。
-   修正共同撰寫文件中的變更無法合併的問題。
-   修正包含 ActiveX 控制項的文件會造成共同撰寫失敗的問題。

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正時間表檢視的問題：在 [將現有工作新增至時間表] 對話方塊中，只會出現來自第一個摘要工作中的工作。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正當使用 Configuration Manager 將更新部署至執行 Office 應用程式的用戶端時，更新未在 Office 應用程式執行時並重新啟動裝置之後套用的問題。



## <a name="version-1803-may-18"></a>版本 1803：5 月 18 日
*版本 1803 (組建 9126.2210)*

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
- 修正此問題：在圖表上動作可能會造成 Excel 當機。
- 修正此問題：部分使用者不小心停用 Power View 增益集。
- 修正此問題：在文件復原期間建立的暫時自動復原檔案永遠不會清除。
- 修正此問題：在嘗試與受保護 Workbook 中的文字檔建立新連線時，收到「Workbook 受到保護，且無法變更」錯誤訊息。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
- 修正此問題：在圖形中使用拼字校正時會造成 PowerPoint 當機。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
- 修正此問題：開啟應用程式時，使用者可能會看到以安全模式啟動的訊息，然後應用程式無法開啟。



## <a name="version-1803-may-8"></a>版本 1803：5 月 8 日
*版本 1803 (組建 9126.2191)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 資訊洩漏弱點

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：Excel 在從 SharePoint Online 開啟檔案時損毀。
-   修正此問題，列印或預覽列印時，只列印或顯示了工作表中的一部分，內容被截斷為工作表上的交叉分析篩選器。

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全性功能略過的弱點

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：切換到 [寄件匣] 或 [寄件備份] 資料夾造成 Outlook 損毀。
-   修正此問題：會議內文或附件變更時所有出席者收到會議更新，而非傳送會議更新給選擇性的出席者。
-   修正此問題：因為使用者代理程式字串中的變更，造成使用者無法連線到 EWS 及 REST 端點。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：PowerPoint 在從 SharePoint Online 開啟檔案時損毀。
-   修正此問題：開啟 [自動儲存] 時，[復原] 窗格不正確地顯示。
-   修正此問題：未顯示登入，使得使用者無法存取檔案。

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正此問題：在日期資料行上使用 [自動篩選] 下拉式清單造成專案中的所有工作隱藏。
-   修正此問題：將現有的工作新增至時間表檢視中的時間表時，對話方塊中只會出現來自第一個摘要工作的工作。

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：Word 在從 SharePoint Online 開啟檔案時損毀。
-   修正此問題：小寫羅馬數字頁碼不正確地變更為大寫。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 遠端程式碼執行弱點



## <a name="version-1803-april-10"></a>版本 1803：4 月 10 日
*版本 1803 (組建 9126.2152)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 遠端程式碼執行弱點

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：多個使用者在相同簡報上共同撰寫會導致投影片母片不正確重複。
-   修正此問題：將儲存在 OneDrive 中的檔案開啟時，結束受保護的檢視時會導致 PowerPoint 當機。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正與 TLS 1.2 支援相關的問題。

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正造成顯示記憶體不足訊息的問題。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 遠端程式碼執行弱點



## <a name="version-1803-march-20"></a>版本 1803：3 月 20 日
*版本 1803 (組建 9126.2098)*

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：快速列印附加至 Outlook 電子郵件的 Excel 活頁簿可能會列印不出來。
-   修正此問題：按一下超連結可能會造成 Excel 當機。
-   修正此問題：使用 cube 函式會造成 Excel 當機。

### <a name="onedrive-for-business-non-security-updates"></a>商務用 OneDrive：非安全性更新
-   修正此問題：商務用 OneDrive (Groove.exe) 會在 [工作管理員] 中耗用相當於一個 CPU 核心的 CPU (例如，4 核心 CPU 的 25%) 來延長一段時間。

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：出席者的會議位置更新是顯示舊的位置而不是新的位置。
-   修正此問題：使用者在預覽讀取窗格中的附件時，會看到錯誤。
-   修正此問題：當使用者在撰寫電子郵件時，解決電子郵件地址的顯示名稱會使 Outlook 當機。
-   修正此問題：有些使用者未收到其租用戶系統管理員已啟用的支援功能。

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：Word 在執行 Windows 7 的電腦上無法開啟，且該電腦上未安裝 [客戶體驗和診斷遙測](https://support.microsoft.com/help/3080149/update-for-customer-experience-and-diagnostic-telemetry)的更新。
-   修正此問題：清單中的項目符號無法列印。



## <a name="version-1803-march-13"></a>版本 1803：3 月 13 日
*版本 1803 (組建 9126.2072)*

### <a name="access-security-updates"></a>Access：安全性更新
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 遠端程式碼執行弱點

### <a name="access-non-security-updates"></a>Access：非安全性更新
-   修正此問題：開啟 Access 執行階段應用程式 (.accde 檔案) 會導致「無法辨認此資料庫格式」錯誤訊息，且應用程式不會開啟。
-   修正此問題：嘗試在文字方塊或下拉式方塊中選取文字似乎會選取所有文字，而不是表示選取範圍。

### <a name="excel-feature-updates"></a>Excel：功能更新
-   **Microsoft Translator：** 使用 Microsoft Translator 可將單字、片語或句子翻譯成另一種語言。您可以從功能區中的 [校閱] 索引標籤使用此功能。
-   **將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。
-   **取消選取儲存格：** 在工作表中進行選取，並取消選取不小心按到的儲存格而不必重新開始。
-   **快速存取您的網站和群組︰** 您可以使用 [檔案] 功能表，使用儲存在您常用的網站和群組中的文件。
-   **數位鉛筆：** 使用新的鉛筆紋理手寫或繪製出您的創意。只需傾斜即可使用支援的數位鉛筆進行陰影處理。
-   **LinkedIn 功能設定：** 移至 [檔案] \> [選項] \> [一般]，以控制 LinkedIn 功能是否要顯示在您的 Office 應用程式中。[深入了解](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **3D 模型：** 使用 3D 來增加活頁簿的視覺效果和創意影響。輕鬆插入 3D 模型，然後將其旋轉 360 度。 [深入了解](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **新的筆跡效果：** 使用金屬畫筆和筆跡效果 (如彩虹、星空、熔岩、海洋、黃金、銀等) 來展現您的想法。
-   **共用檔案 UI：** 對於商務用 OneDrive 或 SharePoint 檔案，按一下功能區右上角的 [共用] 按鈕，或移至 [檔案] \> [共用] 可啟動經簡化並改良過的 [共用] 對話方塊。對於新的或儲存在本機的檔案，該 UI 可讓使用者輕鬆地將檔案上傳至 OneDrive 以啟動共同作業。
-   **封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **有用的聲音可改善協助工具：** 開啟音訊提示可在作業時一面引導您。可在 [檔案] \> [選項] \> [輕鬆存取] 中找到此功能。無需增益集。 [深入了解](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **依帳戶的檔案位置：** 開啟或儲存檔案時，位置清單會依照與其相關聯的帳戶整理。
-   **畫筆自訂：** 針對筆跡選擇畫筆和螢光筆的個人集合。您的自訂集可在您所有的 Windows 電腦上使用。

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877)：Microsoft Excel 安全性功能略過的弱點
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878)：Microsoft Excel 記憶體損毀弱點
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全性功能略過
-   [Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正下列問題：如果您的編輯語言是日文、中文或韓文，則當您嘗試在 [首頁] 索引標籤上選取新字型時，或當編輯時，Excel 可能會凍結。
-   修正此問題：當 Excel 最小化時，開啟活頁簿時捲軸會遺失。
-   修正此問題：在 [檔案總管] 中的檔案名稱上按兩下以開啟多個活頁簿時，活頁簿參照會失敗。
-   修正此問題：以程式設計方式建立樞紐分析表，接著以程式設計方式重新整理，會造成 Excel 當機。
-   修正此問題：以程式設計方式呼叫 Workbook.Open() 可能會造成 Excel 當機。
-   修正此問題：使用者使用巨集開啟 Office 2007 或較舊的活頁簿 (.xls 或 .xla) 時，會看到不正確的「重大失敗」錯誤訊息。
-   修正此問題：使用者開啟內容功能表時，Excel 可能會當機。
-   修正此問題：當使用者嘗試在現有的活頁簿中插入物件時，Excel 會在使用者按一下 [瀏覽] 時損毀。
-   修正此問題：使用密碼保護一個範圍時，看不到要輸入密碼以解鎖範圍的對話方塊。
-   修正此問題：在檔案名稱包含方括弧時，使用者無法在受保護的檢視中關閉活頁簿。
-   修正此問題：在拖曳或拖曳填滿時，工具提示的放置位置沒有對齊。
-   修正此問題：使用 [檔案] \> [另存新檔] 來儲存活頁簿時，包含句點的檔案名稱在檔案儲存對話方塊中會出現空白或截斷。
-   修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **輕鬆地排序您的電子郵件：** 由於您的意見反應，我們已為不使用 [焦點收件匣] 的使用者，重新加入了郵件清單上方的排序功能和 [未讀取] 篩選器。
-   **將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。
-   **Office 365 群組的改善︰** 您可以在群組訊息上按兩下，開啟其個別視窗，這讓您更加容易閱讀和回覆群組對話。
-   **LinkedIn 功能設定：** 移至 [檔案] \> [選項] \> [一般]，以控制 LinkedIn 功能是否要顯示在您的 Office 應用程式中。[深入了解](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **3D 模型：** 使用 3D 來增加電子郵件的視覺效果和創意影響。輕鬆插入 3D 模型，然後將其旋轉 360 度。 [深入了解](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **個人檔案卡片：** 無論您是使用桌面應用程式、Web 應用程式或行動應用程式，都能顯示有關人員和群組的最相關詳細資料。
-   **在群組行事曆中新增約會：** 現在，您可以讓群組中的每個人都知道您何時會離開，而不需要以電子郵件傳送會議。
-   **下載雲端附件：** 當您將 OneDrive 附件儲存或拖放到電腦時，我們會為您下載檔案。
-   **有用的聲音可改善協助工具：** 開啟音訊提示可在作業時一面引導您。可在 [檔案] \> [選項] \> [輕鬆存取] 中找到此功能。無需增益集。 [深入了解](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **焦點收件匣：** 收件匣分成兩個索引標籤 – 焦點及其他。訊息會依照訊息內容和您最常互動的寄信者進行分類。 [深入了解](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)
-   **快速存取您最常使用的群組︰** 您最有可能互動的群組，會出現在 [群組] 下方清單頂端的 [資料夾] 窗格中。

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 提高權限弱點
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 記憶體損毀弱點

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：當搜尋範圍限定為 [所有信箱] 時，搜索會失敗並顯示 [找不到相符項目]。
-   修正此問題：使用 Accessible Event Watcher (AccEvent.exe) 來監視時，切換資料夾會導致 Outlook 當機。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **Microsoft Translator：** 使用 Microsoft Translator 可將單字、片語或句子翻譯成另一種語言。您可以從功能區中的 [校閱] 索引標籤使用此功能。
-   **3D 動畫：** 透過輕輕搖晃或跳躍及旋轉等動畫，讓 3D 模型栩栩如生。
-   **將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。
-   **修訂追蹤資訊漫遊：** 醒目提示共用投影片 (已經過他人修改) 的已讀取/未讀取狀態，現在會儲存在漫遊服務中 (而不是在使用者的本機電腦上)，讓這項資訊可以跨越多個裝置或平台上進行同步處理。
-   **快速存取您的網站和群組︰** 您可以使用 [檔案] 功能表，使用儲存在您常用的網站和群組中的文件。
-   **數位鉛筆：** 使用新的鉛筆紋理手寫或繪製出您的創意。只需傾斜即可使用支援的數位鉛筆進行陰影處理。
-   **LinkedIn 功能設定：** 移至 [檔案] \> [選項] \> [一般]，以控制 LinkedIn 功能是否要顯示在您的 Office 應用程式中。[深入了解](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **使用數位筆執行投影片放映：** 使用 Surface 手寫筆或其他有藍牙按鈕的手寫筆，推進您的投影片。必須有 Windows 10 Fall Creators Update。 [深入了解](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)
-   **3D 模型：** 使用 3D 來增加簡報的視覺效果和創意影響。透過「轉化」轉場在投影片之間建立電影動畫，讓 3D 模型讓您的簡報更生動。 [深入了解](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **新的筆跡效果：** 使用金屬畫筆和筆跡效果 (如彩虹、星空、熔岩、海洋、黃金、銀等) 來展現您的想法。
-   **共用檔案 UI：** 對於商務用 OneDrive 或 SharePoint 檔案，按一下功能區右上角的 [共用] 按鈕，或移至 [檔案] \> [共用] 可啟動經簡化並改良過的 [共用] 對話方塊。對於新的或儲存在本機的檔案，該 UI 可讓使用者輕鬆地將檔案上傳至 OneDrive 以啟動共同作業。
-   **封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **修訂醒目提示：** 會醒目提示已由其他使用者修改的投影片。
-   **當您離開時：** PowerPoint 會顯示自您上次查閱以來誰編輯了共用的簡報。
-   **設計工具的改進：** 設計工具現在會針對項目符號清單中的時間軸建議設計概念。
-   **有用的聲音可改善協助工具：** 開啟音訊提示可在作業時一面引導您。可在 [檔案] \> [選項] \> [輕鬆存取] 中找到此功能。無需增益集。 [深入了解](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **依帳戶的檔案位置：** 開啟或儲存檔案時，位置清單會依照與其相關聯的帳戶整理。
-   **畫筆自訂：** 針對筆跡選擇畫筆和螢光筆的個人集合。您的自訂集可在您所有的 Windows 電腦上使用。
-   **設計工具的改進：** 設計工具現在會針對新增至投影片的圖表建議設計概念。
-   **快速啟動工具：** 自動建置大綱，協助使用者開始研究他們所選擇的主題。[深入了解](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)
-   **數位尺規：** 在有觸控式螢幕的裝置上，請移至「繪圖 \> 尺規」，然後使用您的手寫筆或手指來繪製直線，或對齊一組物件。[深入了解](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)

### <a name="powerpoint-security-updates"></a>PowerPoint：安全性更新
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934)：Microsoft PowerPoint 資訊洩漏弱點

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：移除文件屬性和個人資訊會造成儲存至 SharePoint 失敗。
-   修正此問題：以 Flash Player 為基礎之 YouTube 內嵌程式碼的參考，導致開啟新視窗來播放影片。舊的內嵌程式碼現已升級為參考以 HTML5 為基礎的 YouTube 影片，以便正確地就地播放。
-   修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。

### <a name="project-feature-updates"></a>Project：功能更新
-   **工作面板檢視：** 在 [工作面板] 檢視中的卡片上排序工作。在面板上的資料行之間重新排序和移動卡片，就像在敏捷式專案中一樣。
-   **敏捷式專案：** 使用待辦項目、工作面板、衝刺及其他項目管理您的敏捷式專案。同時支援 Scrum 或 Kanban 方法。[深入了解](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)  
-   **在 Planner 中管理工作：** 將專案工作連結至 Planner，並為其建立計劃。將工作分成子工作、新增小組、指派任務，以及管理工作面板上的工作。

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正此問題：在工作階段中設定多個基準，會讓 MOD\_DATE 值都設為相同。
-   修正此問題：將實際工時從 [儲存為共用] 工作階段中移除之後，[實際工時] 仍然顯示在報表中。
-   修正此問題：在德文版中進行排程時，要使用 [週] 日期格式時會傳回錯誤。
-   修正此問題：在編輯 [排程網頁組件] 的完成日期時，工作保持為每天 8 小時，而不是隨著時間分配。
-   修正此問題：在非預期的位置繪製「進度點形狀」。
-   修正此問題：VBA 程式碼從專案中遺失。
-   修正此問題：即使有剩餘工時，工作卻顯示為完成。
-   修正此問題：使用「任務路徑」功能時，專案停止回應。
-   修正此問題：時幅沒有顯示時幅標籤。
-   修正此問題：視覺效果報表顯示不完整的資訊或完全失敗。
-   修正此問題：儲存失敗會導致檔案損毀，並造成專案在開啟時當機。
-   修正此問題：您無法在時間軸和團隊規劃檢視中拖曳工作。
-   修正此問題：「小組建立器」中沒有顯示資源可用性。
-   修正此問題：圖形指標並未正確顯示。
-   修正此問題：專案以每小時或每一天為基礎進行調整時沒有反應。
-   修正此問題：搭配使用 SharePoint 文件庫的主/子專案。
-   修正此問題：當您將工作分派新增到固定工期的排程時，可能會導致沒有名稱的資源。
-   修正此問題：變更受保護的工作時，會產生不正確的錯誤訊息。
-   修正此問題：當報表包含數個影像時，Project 可能會損毀。

### <a name="publisher-feature-updates"></a>Publisher：功能更新
-   **封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="publisher-non-security-updates"></a>Publisher：非安全性更新
-   修正此問題：執行合併列印精靈時，篩選包含 null (空白) 值的資料來源欄位失敗。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正此問題：在會議中以選取 [Skype 通話] 的方式新增使用者會產生錯誤。
-   如果已將 Skype 會議室新增為位置，且會議已包含小組會議座標，請移除要求使用者將 Skype 座標新增至會議的提示。
-   修正此問題：即使 UseLocationForE911Only 設定為 true，也會填入位置。
-   修正此問題：使用名冊中的「使用會議中心呼叫」選項來邀請使用者時，商務用 Skype 會當機。
-   修正此問題：建立商務用 Skype 會議時，在終端機伺服器上運行的Outlook 會凍結。
-   將 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的預設值變更為 TRUE。
-   修正此問題：當會議處於全螢幕模式時，[其他選項] 和 [邀請其他人] 按鈕會隱藏。
-   修正此問題：當您想要加入會議時，P2P 音訊撥號視窗或電話會議視窗會變成透明。
-   修正此問題：即將開始的 Skype 會議未顯示在 [會議] 索引標籤。
-   修正此問題：當商務用 Skype 配置為無音訊加入會議，新增音訊至會議時不會將音訊新增至現有的會議，反而是向使用者本身啟動新的 P2P 撥號。
-   修正此問題：當使用者按下 Outlook 會議邀請的 [加入 Skype 會議] 連結時，會收到錯誤訊息 [找不到此 Skype 會議]。
-   在快顯通知 UI 中為撥入的 PSTN 通話新增來電轉接按鈕。
-   當 ChatDefaultClient 和 CallDefaultClient 設定至 Teams 時，通知使用者來電與交談正在傳送至 Teams。
-   當使用者不在會議中並停用商務用 Skype 時，使用者狀態會顯示為 [離線]，且會議加入體驗會設為 [原生有限用戶端]。
-   商務用 Skype 最小化至通知區域時，停用 [開啟] 和 [結束] 以外的所有選項。
-   與 Aries 電話配對且啟用 RedirectClient 時，隱藏新來電和對話。
-   修正此問題：日期格式非美國格式 (mm/dd/yy) 時，在 PChat 中依日期搜尋訊息會失敗。
-   修正此問題：當 EnableExternalP2PFileTransfer 原則設為 false 時，使用者仍然可以在會議中附加檔案。
-   修正此問題：在 [交談歷程記錄] 中，顯示了來電者而非受話者。使用 Active Directory 修改受話者的公司電話時會發生這種情況。
-   修正此問題：對於撥出 PSTN 通話到行動號碼，交談歷程記錄的通話記錄中遺失受話方資訊。
-   修正此問題：從 Outlook 中的電子郵件起始 IM 時，電子郵件的主旨列並不包含在 IM 的主旨中。
-   修正此問題：當 [IM 交談] 視窗貼齊到一側時，交談會出現雙重堆疊。
-   修正此問題：在 VDIv2 環境中，VbSS 螢幕畫面分享要求會顯示為 RDP 要求。
-   修正此問題：來電轉接失敗時，來電者會列在失敗通知中而非列在未接受話方。
-   修正此問題：「開始使用 Teams」按鈕隱藏在用戶端升級重新導向橫幅內。
-   修正即時通訊視窗中的 DPI 縮放比例問題。
-   修正此問題：商務用 Skype 連絡人卡片中未顯示 LinkedIn 資料。
-   新增可讓使用者代表群組搜尋停止接受呼叫的功能。
-   新增功能，正在商務用 Skype 或 Teams 進行通話時，若接收或起動新的通話時，會自動保留通話。
-   修正此問題：使用者使用全螢幕共用之後無法傳送 IM。
-   修正此問題：在大廳中的使用者進入會議室遭到拒絕時，不會收到通知。
-   修正此問題：自動增益控制在通話期間無法控制的增加。
-   修正此問題：將會議室資源信箱加入會議邀請時，使用者無法選取「會議選項」中的簡報者。
-   修正此問題：如果 AllowlPVideo 設定為 False，桌面共用按鈕在端對端視訊通話期間無法使用。
-   修正此問題：將現有會議 (建立時為「停用 IM」) 的「會議選項」設定變更為「啟用 IM」之後，IM 仍保持停用。
-   修正此問題：當滑鼠停留在聊天視窗的 [插入連結] 按鈕上時，工具提示不會顯示，並且在選取按鈕時沒有協助工具名稱。

### <a name="visio-feature-updates"></a>Visio：功能更新
-   **內建資料庫模型圖表：** 使用新的資料庫模型圖表範本，將您的資料庫精確地建模為 Visio 圖表。不需要增益集。
-   **更多商用圖表的樣板：** 使用新式圖形，以文氏圖表來比較和對比資料；或繪製循環、矩陣或金字塔圖表來表達您的想法。
-   **建立網站的線框圖：** 快速地建立網站的線框圖，包括介面、瀏覽，以及如何共同作業。 [深入了解](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **建立行動應用程式的框線：** 使用範本來建立行動應用程式的框線。[深入了解](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **將資料圖形套用至 [資料視覺化工具] 圖表：** 藉由自動套用圖形資料作為資料圖形，以節省建立資料視覺化工具圖表的時間。[深入了解](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)
-   **繪圖共同作業：** 透過在商務用 OneDrive 或 SharePoint Online 上共用繪圖來與其他人合作。您可以看到誰在使用繪圖、新增註解以及查看檔案活動。 [深入了解](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)
-   **封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="word-feature-updates"></a>Word：功能更新
-   **將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。
-   **字元數：** 當您輸入時，可在狀態列上顯示字元數。您可以從 [自訂狀態列] 功能表啟用此項目。
-   **快速存取您的網站和群組︰** 您可以使用 [檔案] 功能表，使用儲存在您常用的網站和群組中的文件。
-   **Microsoft Translator：** 在 Word 中使用 Microsoft Translator 將文字、片語或整個文件翻譯成另一種語言。[深入了解](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)
-   **數位鉛筆：** 使用新的鉛筆紋理手寫或繪製出您的創意。只需傾斜即可使用支援的數位鉛筆進行陰影處理。
-   **LinkedIn 功能設定：** 移至 [檔案] \> [選項] \> [一般]，以控制 LinkedIn 功能是否要顯示在您的 Office 應用程式中。[深入了解](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **SharePoint 屬性面板：** 在文件中顯示和編輯 SharePoint 文件庫欄值。[檢視] 索引標籤上的功能區按鈕可讓您輕鬆存取面板，且 SharePoint 系統管理員可以使用文件庫設定來自動開啟 [屬性] 面板。
-   **3D 模型：** 使用 3D 來增加文件的視覺效果和創意影響。輕鬆插入 3D 模型，然後將其旋轉 360 度。 [深入了解](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **新的筆跡效果：** 使用金屬畫筆和筆跡效果 (如彩虹、星空、熔岩、海洋、黃金、銀等) 來展現您的想法。
-   **共用檔案 UI：** 對於商務用 OneDrive 或 SharePoint 檔案，按一下功能區右上角的 [共用] 按鈕，或移至 [檔案] \> [共用] 可啟動經簡化並改良過的 [共用] 對話方塊。對於新的或儲存在本機的檔案，該 UI 可讓使用者輕鬆地將檔案上傳至 OneDrive 以啟動共同作業。
-   **封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **使用學習工具進行編輯：** 在 Word 的 Web 版面配置中現已提供學習工具。在您編輯時可調整文字間距和顯示音節。在任何檢視中，都可看見每個字會隨著大聲朗讀文件而以反白顯示。 [深入了解](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)
-   **LaTeX 語法：** 使用 LaTeX 語法建立並編輯數學方程式。
-   **有用的聲音可改善協助工具：** 開啟音訊提示可在作業時一面引導您。可在 [檔案] \> [選項] \> [輕鬆存取] 中找到此功能。無需增益集。 [深入了解](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **依帳戶的檔案位置：** 開啟或儲存檔案時，位置清單會依照與其相關聯的帳戶整理。
-   **畫筆自訂：** 針對筆跡選擇畫筆和螢光筆的個人集合。您的自訂集可在您所有的 Windows 電腦上使用。
-   **以 [編輯器] 窗格增強了撰寫協助：** 使用 [編輯器] 窗格可得到進階拼字檢查、文法和書寫樣式的建議。它內建無障礙功能，並已改善對輔助技術的支援。

### <a name="word-security-updates"></a>Word：安全性更新
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 記憶體損毀弱點
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 資訊洩漏弱點
-   [Advisory 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020)：Microsoft Office 深度防禦更新

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：當使用者嘗試對商務用 OneDrive 上的現有文件執行 [另存新檔] 時，Word 會當機，並取消儲存作業或嘗試合併現有變更。
-   修正此問題：執行合併列印精靈時，篩選包含 null (空白) 值的資料來源欄位失敗。
-   修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。
-   修正此問題：要移除文件中的 IRM 保護時並沒有移除保護。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 資訊洩漏弱點
-   [Advisory 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003)：Microsoft Office 深度防禦更新

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正此問題：開啟應用程式時，使用者可能會看到以安全模式啟動的訊息，然後應用程式無法開啟。
-   當啟用 Office COM 物件，讓 Office 365 用戶端更新由 Configuration Manager 管理，[立即更新] 選項會在 [檔案] \> [帳戶] \> [更新選項] 中隱藏。
-   修正此問題：當使用者嘗試使用 [啟動 Office] 對話方塊來啟動 Office 時，Office 應用程式會當機。
-   修正在動態 DPI 環境下的 Office 增益集中縮放與調整大小的問題。
-   修正此問題：即使目前已安裝 Office 365 ProPlus，Office 設定服務提供者 (CSP) 的 CurrentStatus 節點仍會傳回空字串。
-   修正此問題：因為同一部電腦上所有的 Office 應用程式版本會共用 .box 檔案，而導致 .box 檔案格式變更；該問題會影響同一部電腦上所安裝舊版 Office 的功能。



## <a name="version-1708-february-13"></a>版本 1708：2 月 13 日
*版本 1708 (組建 8431.2215)*

### <a name="access-non-security-updates"></a>Access：非安全性更新
-   修正下列問題：當使用多個項目表單時，調整滑鼠滾輪或捲軸捲動方塊並不會變更表單中顯示的項目。

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 遠端程式碼執行弱點

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 提高權限弱點
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 記憶體損毀弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 資訊洩漏弱點



## <a name="version-1708-january-9"></a>版本 1708：1 月 9 日
*版本 1708 (組建 8431.2153)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 遠端程式碼執行弱點
-   [Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：以程式設計方式建立樞紐分析表，接著以程式設計方式重新整理，會造成 Excel 當機。

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點

### <a name="word-security-updates"></a>Word：安全性更新
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 記憶體損毀弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 遠端程式碼執行弱點
-   [Advisory 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003)：Microsoft Office 深度防禦更新

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   為 Office 365 德國方案的網域使用者新增單一登入 (SSO) 的支援，該方案的身分識別與內部部署的 Active Directory 同盟。
-   新增功能以避免未成年人獲取和啟動來自 Office 市集的 Office 增益集。


> [!NOTE]
> 如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[技術支援](https://support.microsoft.com/contactus)。
