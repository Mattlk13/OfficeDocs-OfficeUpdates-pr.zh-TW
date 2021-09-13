---
title: 每月企業通道版本的封存版本資訊
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 Office 365 專業增強版每月企業通道版本的版本資訊
ms.openlocfilehash: 171f5436b47f6d35bac641005849c165bf5b6e88
ms.sourcegitcommit: cf2e99223e6d8678d60c01ee8c8959d6f9c8f8a9
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/12/2021
ms.locfileid: "59273416"
---
# <a name="archived-release-notes-for-monthly-enterprise-channel"></a>每月企業通道的封存版本資訊
這些版本資訊可提供 Office 365 專業增強版、Visio Pro for Office 365、Project Online 電腦版用戶端以及 Office 365 商務版的每月企業通道更新所含新功能和非安全性更新的相關資訊。

 > [!NOTE]
>- 我們通常會在一段時間每個月推出功能 (有時甚至推出修正程式)。  如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。 [深入了解](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- 現有 Office 365 專業增強版安裝上的 Microsoft Teams - 從 7 月初開始，對 Office 365 專業增強版 (和 Office 365 商務版) 的更新將包含 Microsoft Teams。  新增 Teams 的日期取決於您使用的更新通道。 如需詳細資訊，請參閱[隨著 Office 365 專業增強版部署 Microsoft Teams](/deployoffice/teams-install)。



## <a name="version-2010-december-08"></a>版本 2010: 12 月 8 日
*版本 2010 (組建 13328.20478)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 / Microsoft 365 和 Power BI Pro 服務方案的組織測試人員使用。 取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。 我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。 [深入了解](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料

### <a name="outlook"></a>Outlook

- **工作的使用者體驗更新：** 工作項目的視覺效果更新

- **電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。 您可以變更權限，讓所有收件者都能存取。

### <a name="powerpoint"></a>PowerPoint

- **匯出範圍中的動畫 GIF：** 當匯出成動畫 GIF 時， 選取投影片的範圍

- **使用透明背景建立 GIF：** 當匯出成動畫 GIF 時，您可以使用新選項讓背景變透明。<br />在[部落格文章](https://insider.office.com/en-us/blog/export-animated-gifs-transparent-backgrounds)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正從非 Office 應用程式使用 DAO 時，會導致應用程式意外關閉的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致 Outlook 為啟用雲端設定的使用者建立第二個空白簽名的問題。


- 我們已修正會導致預設不會為使用者開啟雲端設定的問題。


- 我們已修正會導致對使用者簽章的變更無法儲存的問題。


- 我們已修正當回覆或轉寄郵件時，會導致中文郵件標題無法閱讀的問題。


- 我們已修正在儲存為 OFT 檔案時，會導致中文字元變更為問號的問題。


- 我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含。  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。  REG_DWORD IncludeFileTimesInDataObject。  0 = 不包含 filetimes。  1 = (預設) 包含 filetimes。


- 我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。


- 我們已修正會導致某些會議的原始出席者在另一個出席者轉寄會議時收到取消通知的問題。


- 我們已修正會導致使用者無法將 [編輯器] 權限授與代理人的問題。


### <a name="powerpoint"></a>PowerPoint

- 這是此問題的修正：當有增益集在接聽 PresentationBeforeClose 事件並隨著事件處理常式檢查 Presentation.Saved 內容時若關閉文件，儲存提示會以迴圈顯示。


- 解決在合併錯誤期間使用 IRM/受保護文件的問題。


- 修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。


### <a name="project"></a>Project

- 修正 Project 在開啟以特定方式指定資源分佈的檔案時可能會意外終止的問題。


- 修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。


- 修正如果工作表單類型檢視內的延隔時間變更，ProjectBeforeTaskChange 事件中的 NewVal 不會有正確值的問題。


### <a name="visio"></a>Visio

- 修正使用者將可在自訂 Visio 樣板和內建範本中使用適用於 Office 365 的 Visio 連接器建立直線的問題。


### <a name="word"></a>Word

- 修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。


### <a name="office-suite"></a>Office 套件

- 修正 Microsoft 365 端點資料外洩防護無法在磁碟上分類 Office 文件的問題。


- 當使用者從 Office 在噴墨印表機上列印任何文件/檔案且印表機墨水不足時，即使噴墨印表機並沒有碳粉，也會顯示「碳粉不足」或「無碳粉」訊息。變更訊息以顯示「碳粉/墨水不足」與「碳粉/墨水用完」。


- 修正將註解中的文字複製/貼上到 Excel 時出錯的問題。


- 修正在某些情況下，嘗試執行另存新檔失敗的問題。


- 我們已修正在嘗試儲存已從 syncbacked 檔案轉換為僅限伺服器的檔案時，導致失敗的問題。



[//]: # (請勿移除 BUGDETAILS 內容尾)

## <a name="version-2009-december-08"></a>版本 2009：12 月 8 日
*版本 2009 (組建 13231.20620)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

## <a name="version-2009-november-10"></a>版本 2009：11 月 10 日
*版本 2009 (組建 13231.20514)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。

### <a name="powerpoint"></a>PowerPoint

- **[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。

### <a name="word"></a>Word

- **[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正在回覆或轉寄時，會導致中文郵件標題無法閱讀的問題。


- 已解決導致代理人在開啟另一個信箱中的共用資料夾時出現錯誤的問題。


- 已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。


- 解決了導致某些使用者觀察到在離線狀態下意外啟動 Outlook 的問題。


- 已解決搜尋未快取共用行事曆時導致搜尋未傳回結果的問題。


- 我們已修正會導致使用者在選取搜尋結果時遇到意外終止的問題。


- 我們已修正會導致使用者無法將 [編輯器] 權限授與代理人的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正了在包含大量特定資料物件類型 (E2o) 的檔案上導致共同撰寫變慢的問題。


- 已解決在受保護的檢視中開啟 PowerPoint 檔案時停用 IRM 保護的問題。


- 我們已修正 Forms 內容增益集在插入之後不會呈現，除非使用者按一下另一張投影片讓它顯示才會呈現的問題。


### <a name="project"></a>Project

- 修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。


- 修正 Project 在開啟以特定方式指定資源分佈的檔案時可能會意外終止的問題。


- 修正當您將專案從 PWA 儲存到本機 mpp 檔案時，會針對實際上使用者未變更的資料觸發 ProjectBeforeTaskChangeEvent 的問題。


### <a name="word"></a>Word

- 我們已修正 [樣式圖庫] 對話方塊的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正 [壓縮圖片] 對話方塊無法保留某些使用者設定的問題。


- 修正 Microsoft 365 端點資料外洩防護無法在磁碟上分類 Office 文件的問題。


- 當使用者從 Office 在噴墨印表機上列印任何文件/檔案且印表機墨水不足時，即使噴墨印表機並沒有碳粉，也會顯示「碳粉不足」或「無碳粉」訊息。變更訊息以顯示「碳粉/墨水不足」與「碳粉/墨水用完」。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-november-10"></a>版本 2008：11 月 10 日
*版本 2008 (組建 13127.20760)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正使用巨集來設定某個範圍的 FormulaR1C1 屬性時，如果圖表工作表為作用中工作表，則儲存格參考會不正確的問題。


- 修正可能會導致「嘗試計算一個或多個公式時，Excel 資源不足」錯誤的問題。


- 修正當 Office 語言設定為西班牙文時，其中資料驗證清單可能無法顯示清單中所有項目的問題。


- 我們已修正在重新整理 OLAP 樞紐分析表時，可能會導致當機的問題。


- 我們已修正載入活頁簿之後特定功能可能會發生錯誤結果的問題。


- 我們已修正應用程式意外終止 (與 XLAM 增益集參照和命名範圍相關的問題) 的問題。

### <a name="outlook"></a>Outlook

- 我們已修正在回覆或轉寄時，導致中文郵件標題出現亂碼的問題。


- 已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。


- 已解決導致代理人在開啟另一個信箱中的共用資料夾時出現錯誤的問題。


- 我們已修正會導致群組行事曆中的搜尋無法傳回任何結果的問題。


- 我們已修正會導致使用者在選取搜尋結果時遇到意外終止的問題。


- 我們已修正一個問題，使用者現在可以停用 Outlook 的 IRM (資訊版權管理)，而不需要為其餘 Office 應用程式停用它。


- 我們已修正會導致使用者無法將 [編輯器] 權限授與代理人的問題。


- 我們已修正選用連線體驗導致網頁增益集無法載入的問題。<br />在[部落格文章](https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/)中查看詳細資料


### <a name="powerpoint"></a>PowerPoint

- 這是此問題的修正：當有增益集在接聽 PresentationBeforeClose 事件並隨著事件處理常式檢查 Presentation.Saved 內容時若關閉文件，儲存提示會以迴圈顯示。


- 我們已修正 Forms 內容增益集在插入之後不會呈現，除非使用者按一下另一張投影片讓它顯示才會呈現的問題。


### <a name="office-suite"></a>Office 套件

- 已解決針對使用 System Center Configuration Manager 或其他管理工具來使用 Microsoft 365 Endpoint 資料外洩防護進行 Office Update 的商業客戶的問題。

- 修正 Office 增益集的傳訊 API 無法正常運作的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-october-13"></a>版本 2008：10 月 13 日
*版本 2008 (組建 13127.20638)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **有問題嗎？詢問 Excel**：現在，Excel 構想可讓您提出有關資料的問題，而不需花時間編寫公式 (僅提供英文版)。 [深入了解](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。  我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。 [深入了解](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

- **建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。 [深入了解](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- **將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。 [深入了解](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。 [深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a>Outlook

- **在 Outlook 中使用 [快速投票] 建立投票：** 輕鬆建立投票，收集投票，並查看電子郵件中的結果 [深入瞭解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **Outlook 的新個人檔案卡片：** Outlook 的新個人檔案卡片，包括更完善的檢視，並符合 Outlook Web 的卡片樣式。 [深入了解](https://support.office.com/article/e80f931f-5fc4-4a59-ba6e-c1e35a85b501)

### <a name="powerpoint"></a>PowerPoint

- **儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。  我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。 [深入了解](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

### <a name="word"></a>Word

- **儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。  我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。 [深入了解](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 已解决此問題 - 您現在可以使用 Office 的隨選即用應用程式外的 ODBC 驅動程式。


- 此變更可修正當啟動縮放控制方塊 (Shift + F2) 以編輯文字時，可能會導致 Access 當機的問題。


- 此問題現在已解決，您不應該會再遇到當機。


### <a name="excel"></a>Excel

- 修正當活頁簿包含使用 IFNA () 的公式時，會導致活頁簿損毀警告的問題。


- 修正在凍結工作表頂端列之後，使用「快速分析」時 Excel 可能會當機的問題。


- 我們已修正使用者無法修改樞紐分析表篩選的問題，因為它已設定為Analysis Services數據庫中不再存在的值。


- 修正使用「複製格式」時，在某些情況中 Excel 可能會當機的問題。


- 修正 PivotDateFilter API 中的錯誤，其中的 'Before' 和 'After' 篩選條件是相反的。


### <a name="outlook"></a>Outlook

- 解決會導致使用者在回覆或撰寫新電子郵件時收到下列錯誤的問題：「這個網頁中的某些檔案不存在預期的位置， 請問您一定要下載嗎? 如果您確定網頁來自信任的來源，請按 [是]」


- 解決會導致在搜尋控制項中滑鼠右鍵功能表無法顯示的問題。


- 修正在使用精簡檢視時會導致使用者看到異常的問題。


- 這可修正編輯收件者時，會導致使用者偶爾遇到當機的問題。


- 解決會導致排程助理員頁面無法顯示的問題。


- 解決附件上傳的效能問題。


- 解決了當您從 POP 帳戶刪除4或多個電子郵件時，已選取 [僅下載標題] 選項時，導致使用者遇到當機的問題。


- 解決使用者嘗試開啟雲端附件時，會導致使用者在 safelinks 頁面上看到錯誤，而非所嘗試開啟文件的問題。


- 修正與雲端附件互動時，會導致使用者偶爾遇到當機的問題。


- 解決會導致使用者無法按一下角落中的 "X" 來關閉共用行事曆的問題。


- 修正新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。


- 解決了當代理人在某些情況下遭到拒絕而導致會議無法從經理的行事曆中移除的問題。


- 解決了導致使用 Shared Calendar Improvements 的某些使用者無法查看剛新增的共用行事曆的問題。


- 解決會導致 [開啟共用行事曆改良] 設定有時候無法套用至現有共用行事曆的問題。


- 修正會導致使用者嘗試從次要帳戶建立會議邀請的問題，讓帳戶新增至他們的個人檔案，而不會看到空白的表格: 是欄位而不是其電子郵件地址。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正在 PowerPoint 應用程式中導致當機的問題。


- 安全性修正程式，可解決在受保護檢視中開啟 PowerPoint 檔案時會停用 IRM 保護的問題。


- 此變更可解決「匯出為動畫 GIF」功能的問題，其中按一下 [匯出] 按鈕不會匯出。


### <a name="project"></a>Project

- 修正「連結至 SharePoint 工作清單的專案的完成日期沒有更新」的問題。


- 修正如果資源中定義了多個成本費率表，其餘成本並不一定都能正確地計算的問題。

### <a name="skype"></a>Skype

- 將跳舞表情符號膚色變更為中性色彩.


### <a name="visio"></a>Visio

- 客戶回報文字對齊會在即時預覽時發生當機。 7 月分支所發生最多的當機情況。


### <a name="word"></a>Word

- 我們已修正巨集 AutoOpen 在 AutoExec 之前執行的問題


- 我們已修正 [樣式圖庫] 對話方塊的問題。


- 解決 Word 啟動時會導致當機的問題。


- 我們已修正基本樣式未更新為「內文樣式」的問題。


- 我們已修正使用者開啟文件時可能會遇到當機的問題。


- 我們已修正在調整圖案大小時，使用者可能會遺失內容的問題。


- 解決會導致使用者在開啟某些非常大型電子郵件時會遇到當機的問題。


- 解決會導致使用者在回覆或撰寫新電子郵件時遇到當機的問題。


- 此變更可解決於前一個共同撰寫之後，Microsoft Office 應用程式可能卡在無訊息的儲存失敗狀態的問題。


### <a name="office-suite"></a>Office 套件

- 此變更可解決啟動 Office 應用程式時由於無法載入 d2d1.dll 而產生的當機。


- 修正使用 GIF/動畫 model3D 閒置時的高 CPU 使用量


- 當使用者從 Office 在噴墨印表機上列印任何文件/檔案且印表機墨水不足時，即使噴墨印表機並沒有碳粉，也會顯示「碳粉不足」或「無碳粉」訊息。變更訊息以顯示「碳粉/墨水不足」與「碳粉/墨水用完」。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-october-13"></a>版本 2007：10 月 13 日
*版本 2007 (組建 13029.20708)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正 PivotDateFilter API 中的錯誤，其中的 'Before' 和 'After' 篩選條件是相反的。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-september-08"></a>版本 2007：9 月 8 日
*版本 2007 (組建 13029.20534)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。 [深入了解](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- **快速重新開啟上一個工作階段的項目：** 我們新增了一個選項，可快速重新開啟上一個 Outlook 工作階段的項目。 不管 Outlook 當機或您將其關閉，您現在可以在重新開啟應用程式時快速重新啟動項目。 這項功能預設為啟用。 若要將它關閉，請移至 [選項] > [一般] > [啟動選項]。

### <a name="word"></a>Word

- **以向量保留文字：** 現在當您在 Excel、Word 和 PowerPoint 中轉換地圖、圖表和其他 SVG 向量等物件時，您可以保留物件中的文字。

### <a name="office-suite"></a>Office 套件

- **索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。 只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。<br />在[部落格文章](https://blog-insider.office.com/2020/02/20/improved-pane-management/)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此修正會解決嘗試執行之前會產生「查詢太複雜」錯誤訊息的特定查詢的問題。


### <a name="excel"></a>Excel

- 修正在分頁預覽中載入含有多個工作表的活頁簿時，可能會發生錯誤或當機的問題。


- 嘗試使用 LET() 函數儲存含有公式的檔案時發生錯誤。


### <a name="outlook"></a>Outlook

- 解決事件通知警示中導致格式設定問題的問題。


- 解決會導致 Outlook 使用者在精簡檢視中發現瀏覽問題的問題。


- 解決會導致使用者在擷取角色資訊時有時候會當機的問題。


- 解決導致 [排程助理員] 頁面無法顯示的問題。


- 解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。


- 解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。


- 解決會導致 Outlook 無法擷取搜尋建議的問題。


- 解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。


- 解決會導致 CLP 使用者在回覆時的寄件者地址，從受保護的內容切換到未受保護的內容時會發生當機的問題。

- 解決會導致使用者在回覆或撰寫新郵件時遇到當機的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 PowerPoint 應用程式的當機問題。


### <a name="project"></a>Project

- 修正無法將 PDF/XPS 從 Project 儲存至 SharePoint 文件庫的問題。


- 修正當您貼上的工作具有多個依存性時，無法正確複製所有依存性的問題。


- 修正 [指派資源] 對話方塊中選取的工作與工作面板檢視中所選工作不同的問題。


- 修正無法開啟已進入錯誤狀態的專案的問題。



### <a name="office-suite"></a>Office 套件

- 我們已修正使用者在特定情況下 (特別是進入或退出簡報者檢視畫面或使用多個監視器) 看到 UI 元素或內容未顯示的問題。


- 修正即使完整產品的轉換已完成，也會導致執行階段訊息顯示的問題。 此問題的修正程式是確保服務正確計算新增的產品。 我們已篩選出新增的產品 (確保它們同時存在於新的設定中)，並將它們新增到現有產品發行識別碼的結尾。


- 針對舊版非 Web 服務的 [共用] 窗格，在開啟 [共用] 窗格的情況下關閉文件時，可能會導致當機。現已修正此問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-september-08"></a>版本 2006：9 月 8 日
*版本 2006 (組建 13001.20648)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

## <a name="version-2006-august-11"></a>版本 2006: 8月11日
*版本2006（组建13001.20520）*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。

- **篩選和排序而不干擾其他人：** 您現在可以排序和篩選您的 Excel 檔案，同時與其他人使用工作表檢視進行共同作業。 此新功能可防止您在共同撰寫文件時，受到其他使用者的排序和篩選的影響。 [深入了解](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

### <a name="outlook"></a>Outlook

- **協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站。

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。

- **在 Outlook 中撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？ 現在您可以視需要將其關閉了。<br />在[部落格文章](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)中查看詳細資料

- **將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮。

### <a name="powerpoint"></a>PowerPoint

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。

- **改善的 PowerPoint 中的 Steam 影片效能：** 我們改善了 Microsoft Stream 影片的播放效能，將影片載入時間減至最少，以建立出流暢的觀賞體驗。 您可以使用 Microsoft Stream 上您的公司影片來建立更完善的簡報。

### <a name="word"></a>Word

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。

- **用其他方式表達：** 當您想要以不同方式表達時，「重寫」功能可以幫助您。 重寫提供其他不同方式來表達您的詞彙。<br />在[部落格文章](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/)中查看詳細資料

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。

- 解決插入含有身分識別 (例如，自動編號) 欄位的連結 SQL 資料表的問題。


### <a name="excel"></a>Excel

- 修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。

- 修正在載入含有多張分頁預覽的活頁簿時，可能會發生錯誤或當機問題。

- 修正當您從帳戶登出時，嘗試建立資料連線時，可能會發生的當機問題。

- 自動文件分類可能已對處於唯讀模式的活頁簿發生。

### <a name="onenote"></a>OneNote

- 改善共同撰寫狀態的偵測，以降低資源利用率。

### <a name="outlook"></a>Outlook

- 我們已修正複製和貼上 SVG 影像的問題。

- 解決導致在[建議功能]中尋找功能沒有結果並未留給使用者選項以提交新功能點子的問題。

- 解決啟用雲端設定時，按下 Ctrl + 按一下會造成運作停止的問題。

- 解決選取安全性對話方塊上的 [儲存] 選項時，會導致使用者無法將來自其租用戶外部的 OneDrive 附件儲存至其本機電腦的問題。

- 解決導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。

- 解決導致 [共用行事曆] 改善的使用者查看行事曆失敗的問題。

- 解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。

### <a name="project"></a>Project

- 修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。

- 修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。

- 修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。

### <a name="word"></a>Word

- 我們已修正複製和貼上 SVG 影像的問題。

### <a name="office-suite"></a>Office 套件

- 我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。

- 關閉 Office 檔案時，計時問題可能會導致當機

- 解決在登錄 TabProcGrowth 值為 REG_SZ 類型的情況下啟用增益集時，Windows 中的 Office 主機會當機的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-august-11"></a>版本 2005: 8月11日
*版本2005（组建12827.20656）*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

## <a name="version-2005-july-14"></a>版本 2005：7 月 14 日
*版本 2005 (組建 12827.20538)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。 [深入了解](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 修正問題；您應該可以呼叫日期/時間延伸資料類型至您的程式碼，而不會在您的應用程式中遇到任何當機。

- 修正問題；您現在可以還原為最新的 Access 版本，並使用 DAO/VBA 來管理及編輯十進位資料類型。

### <a name="excel"></a>Excel

- 修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。

- 在某些情況下，按一下同一個活頁簿中某個位置的超連結會導致活頁簿被隱藏。

- 修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。

- 解決嘗試將樞紐分析表插入圖表時 Excel 可能會當機的問題。

### <a name="outlook"></a>Outlook

- 已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。

- 解決導致在[建議功能]中尋找功能沒有結果並未留給使用者選項以提交新功能點子的問題。

- 解決導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。

- 解決問題：導致 Windows 10 伺服器版本的使用者看到警告 [防毒軟體狀態: 未安裝。 這個版本的 Windows 支援防毒偵測，但找不到任何防毒軟體。]，即使已正確安裝防毒軟體。

- 解決會導致使用者在某些情況下遇到間歇性懸置和當機的問題。

- 解決導致 [共用行事曆] 改善的使用者查看行事曆失敗的問題。

- 解決會導致使用者在 Outlook 中更新其規則時，看到「此電腦上的規則與 Microsoft Exchange 上的規則不相符」訊息的問題。

- 解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。

- 解決 Outlook 無法為已支付 M365 Business Plus 方案服務的使用者啟用「資料外洩防護」原則提示的問題。

- 解決有回覆/轉寄標籤的 clp 審查事件的問題。


### <a name="powerpoint"></a>PowerPoint

- 這可修正使用者在同一檔案中同時有新版和舊版批註，因此觸發批註的升級而當機的問題。

- 我們已修正建議窗格的當機問題。


### <a name="project"></a>Project

- 修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。

- 修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。

### <a name="skype"></a>Skype

- 當使用者收到將他們移至 Teams Only 的原則時，他們仍然可以使用商務版 Skype Outlook 增益集來排程會議。 在此更新之後，當客戶端讀取指示用戶為 Teams Only 的策略並進入僅限會議加入模式後，您將不再能用商務版 Skype 安排會議。 此外，如果商務版 Skype Outlook 增益集發現商務版 Skype 用戶端處於 [僅限會議加入] 模式，就無法自行啟動。

### <a name="word"></a>Word

- 解決會導致從應用程式拖曳部分內容時遇到當機的問題。

### <a name="office-suite"></a>Office 套件

- 此變更會解決載入和播放動畫內容 (例如 Gif 或3D 模型) 時可能會發生的懸置。

- 我們透過設定Bing附加預設安裝驗證設定為true默認，並將MSI返回成功視為安裝成功，而解決了 ValidateInstall 失敗率問題。

- 此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。

- 當登錄機碼 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth 設為零，且正在啟用增益集時，Office 主機會在 Windows 中當機。此變更可修正此問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-july-14"></a>版本 2004：7 月 14 日
*版本 2004 (組建 12730.20602)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

## <a name="version-2004-june-09"></a>版本 2004: 6 月 09 日
*版本2004（組建12730.20430）*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **按幾下就能新增資料表：** 使用 [新增資料表] 工作窗格，當您工作時，該窗格會保持開啟狀態，以便將資料表新增至關聯和查詢。 [深入了解](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a>Excel

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。<br />在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料

- **Facebook 連接器支援即將結束：** 於 2020 年 4 月起，Excel 就不再支援使用 Facebook 連接器的外部資料連線。

- **讓活頁簿更生動的新影像：** 您可以在活頁簿中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />在[部落格文章](https://blog-insider.office.com/2020/04/06/premium-creative-content/)中查看詳細資料

### <a name="outlook"></a>Outlook

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。<br />在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料

- **將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。 您拖曳的郵件將會與所有群組成員共用。<br />在[部落格文章](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)中查看詳細資料

- **行事曆煥然一新：** 查看視覺更新，讓您的行事曆更容易流覽。 [深入了解](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />在[部落格文章](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)中查看詳細資料

- **讓郵件更生動的新影像：** 您可以在電子郵件中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />在[部落格文章](https://blog-insider.office.com/2020/04/06/premium-creative-content/)中查看詳細資料

### <a name="powerpoint"></a>PowerPoint

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。<br />在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料

- **在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。 [深入了解](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />在[部落格文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看詳細資料

- **讓投影片更生動的新影像：** 您可以在投影片中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />在[部落格文章](https://blog-insider.office.com/2020/04/06/premium-creative-content/)中查看詳細資料

### <a name="word"></a>Word

- **對筆跡使用套索：**[繪圖] 索引標籤上的 [套索] 工具，可協助您選取使用筆跡繪製的物件。 選取個別筆劃或整個字。 [深入了解](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。<br />在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料

- **讓文件更生動的新影像：** 您可以在文件中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />在[部落格文章](https://blog-insider.office.com/2020/04/06/premium-creative-content/)中查看詳細資料

### <a name="office-suite"></a>Office 套件

- **敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。

- 在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。

- 在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。

- 修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。

### <a name="outlook"></a>Outlook

- 已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。

- 已解決導致使用者在退出 Outlook 時遇到掛斷的問題。

- 解決在顯示快顯通知時，使用者遇到當機的問題。

- 已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。

- 已解決導致 Outlook 在某些 Windows 組建上當機的問題。

- 已解決導致資料夾窗格寬度意外變更的問題。

### <a name="project"></a>Project

- 在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。

- 修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。

### <a name="office-suite"></a>Office 套件

- 修正當嘗試硬連結符號連結時，導致更新失敗的 [點擊運作] 問題。

- 當登錄機碼 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth 設為零，且正在啟用增益集時，Office 主機會在 Windows 中當機。此變更可修正此問題。

- 此修正可解決同時防止限制存取和保護設有密碼之檔案的錯誤。

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。

- 此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-june-09"></a>版本 2003: 6 月 09日
*版本2003（組建12624.20708）*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="office-suite"></a>Office 套件

- 此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-may-12"></a>版本 2003：5 月 12 日
*版本 2003 (組建 12624.20588)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。 在 SQL 檢視中搜尋及取代文字。 在 [關聯圖] 視窗中選取多個資料表。

### <a name="excel"></a>Excel

- **輸入會傳回多個值的公式**：現在您可以快速輸入公式來傳回多個值，並且值會自動溢出至相鄰的儲存格。 [深入了解](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br />在[部落格文章](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)中查看詳細資料

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。

- **六個功能強大的函數：** 我們新增了六個新的函數，讓您的試算表功能更強大：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。 [深入了解](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- **向左看，向右看... XLOOKUP 在這裡！：** 一列接著一列，在含有 XLOOKUP 的表格或範圍中尋找您需要的項目。 [深入了解](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br />在[部落格文章](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)中查看詳細資料

- **即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。

### <a name="outlook"></a>Outlook

- **搜尋人員時取得電子郵件建議：** 當您在 [搜尋] 方塊中輸入人員的名稱時，最相關的電子郵件訊息會包括在您的搜尋建議中。 [深入了解](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- **群組命名原則：** 群組命名原則可讓 IT 系統管理員將組織中使用者所建立群組的名稱標準化及管理。 系統管理員可以要求在建立群組時，將特定首碼和尾碼新增至群組的名稱，而且可以封鎖使用特定字詞。 這有助於將群組名稱中使用不當字詞的情況最小化，以及 IT 管理其目錄中群組的表示方式。 命名原則也可協助部署小組網站的組織根據部門來分類。

- **加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。 將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。

- **受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？ Outlook 現在會偵測這項要求並協助您取得連結。

### <a name="powerpoint"></a>PowerPoint

- **在 PowerPoint 中快速即時共同作業：** 在 PowerPoint 中快速即時共同作業

- **線上影片有新的首頁：** 將影片儲存至 Microsoft Stream，讓組織中的任何人都看得到。 插入影片連結，享受檔案大小只有原來一小部分的多媒體簡報。 [深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。

- **jiffy 中的 Gif：** 一個投影片、一個圖文框。 在 PowerPoint 中輕鬆建立迴圈 Gif。 [深入了解](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br />在[部落格文章](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)中查看詳細資料

- **更好的圖表：** 使用更完善的連接線和更平滑的筆跡轉換程式，您可以自信地用筆跡繪製您的想法。 [深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。<br />在[部落格文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看詳細資料

### <a name="word"></a>Word

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。

- **其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。

### <a name="office-suite"></a>Office 套件

- **以漸進方式開啟大型檔案：** 即使大型 PowerPoint 簡報的某些部分 (例如大型視訊或影像) 還沒有下載完成，還是能夠下載、開啟並與之互動。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel

- 在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。

- 解決當來源活頁簿關閉時，外部連結無法在填入時更新的問題。


### <a name="onenote"></a>OneNote

- 透過暫時變更建立頁面版本歷程記錄的頻率，可改善同步處理與服務的穩定性。


- 透過暫時停用將頁面移動至資源回收桶，來改善同步處理與服務的穩定性。 若使用者想要刪除頁面，則會改為顯示詢問是否要永久刪除頁面的對話方塊。


- 透過暫時將 OneNote 2016 中新嵌入附件的最大允許大小減少為 50MB，來改善同步處理與服務的穩定性。 對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。


- 透過暫時停用 OneNote 2016 中的應用程式內視訊錄製，來改善同步處理與服務的穩定性。 本機筆記本不受這個值的影響。


- 透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。


- 透過在資訊列中通知使用者有關 Microsoft OneNote 中的暫時調整之資訊，可協助改善在高全球使用狀況時的同步處理與服務可用性。


### <a name="outlook"></a>Outlook

- 已解決導致使用者在工作管理員中看到 Outlook 處理序延遲的問題。


- 解決使用滑鼠上的按鈕時，導致使用者偶爾發生當機的問題。


- 解決使用者在第三方 MAPI 應用程式中遇到當機的問題。


- 已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。


- 已解決導致 Outlook 在某些 Windows 組建上當機的問題。


- 已解決導致資料夾窗格寬度意外變更的問題。


### <a name="project"></a>Project

- 修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。


- 修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。


- 修正無法正確計算摘要工作日期的問題。


- 修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。


- 修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。


- 修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。


- 修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。


- 在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。


### <a name="word"></a>Word

- 解決使用滑鼠上的「X」按鈕時，導致使用者偶爾遇到當機的問題。

### <a name="office-suite"></a>Office 套件

- 此修正可解決同時防止限制存取和保護設有密碼之檔案的錯誤。

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> 如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。