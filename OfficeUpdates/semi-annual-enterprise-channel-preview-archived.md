---
title: 2019 年半年通道 (已設定目標) 版本的封存版本資訊
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2019 年 Office 365 專業增強版半年通道 (已設定目標) 版本的版本資訊
ms.openlocfilehash: 72e2402dff445b9ec4b03c7241f93ee85b16bee2
ms.sourcegitcommit: 596cdb3423140df0324a952157fbc39ebedc12b9
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 05/07/2021
ms.locfileid: "52278120"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel-preview"></a>半年企業通道 (預覽版) 封存發行記錄

這些版本資訊可提供 Office 365 專業增強版、Visio Pro for Office 365、Project Online 電腦版用戶端以及 Office 365 商務版的半年企業通道 (預覽版) 更新所含新功能和非安全性更新的相關資訊。

> [!NOTE]
> - 我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至半年企業通道 (預覽版)。 如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。 [深入了解](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)


## <a name="version-2008-december-08"></a>版本2008：12 月 8 日
*版本 2008 (組建 13127.20910)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正嘗試使用 ODBC DSN 建立器時的錯誤問題


### <a name="excel"></a>Excel

- 修正從 Project 計劃匯出時無法編輯樞紐分析表和無法儲存活頁簿的問題。


- 我們已修正在某些情况下，以唯讀模式開啟文件時會出現多個訊息列。


- 我們已修正當有許多重複的欄標題值時，大綱子總計可能停止運作的問題。


- 我們已修正在多執行緒重新計算期間進行群組原則物件更新 (例如，透過遠端群組原則重新整理) 時，Excel 將停止運作的問題。


- 我們已修正當使用者對超過 255 列使用小計函數時 Excel 將停止運作的問題。


- 當內容從 Excel 複製並使用 [内嵌] 選項貼上到 PowerPoint 中時，改進了 PowerPoint 中的文字字元間距調整。


- 修正在 PowerPivot 中封鎖從 [資料表預覽] 和 [査詢編輯器] 切換的問題。


- 我們已修正使用者無法直接從 SharePoint 開啟 atomsvc (UTF8+BOM) 檔案的問題。


- 我們已修正Power Pivot 現在將成功識別定位字元分隔符號的問題。


### <a name="outlook"></a>Outlook

- 我們已修正在傳送任務狀態報告時導致 [收件人：] 欄位為空的問題。


- 我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。


- 我們已修正一些問題，導致某些使用者在從 Outlook 以外的應用程式傳送 Outlook 郵件時，遇到應用程式意外關閉的問題。


- 我們已修正會導致使用者在線上模式下在資料夾之間移動多個郵件項時效能下降的問題。


- 我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含。  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes 被排除  1 = (預設) 事件時間包含在内


- 我們已修正當回復含有「Azure 資訊保護」保護標籤的郵件時，會導致內嵌影像消失的問題。


- 我們已修正會導致在傳送受 Azure 保護的語音信箱時用戶名顯示為電話號碼，從而導致傳統型 Outlook 使用者無法開啟來自外部使用者的語音信箱。


- 我們已修正一個問題，即設定 OME 設定時在郵件項目上新增無關的附件，這會迫使 Outlook 加密郵件，即使在服務端設定了DecryptAttachmentsFontryptOnly 選項。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正當使用者將來源路徑變更為本機 OneDrive 資料夾時，連結的 Excel 圖表不正確變更為 Excel 工作表的問題。


- 我們已修正會導致「歡迎回來」的問題！ 「從先前離開的地方開始」在 PowerPoint 裏不起作用。


### <a name="visio"></a>Visio

- 修正使用者將可在自訂 Visio 樣板和內建範本中使用適用於 Office 365 的 Visio 連接器建立直線的問題。


### <a name="word"></a>Word

- 我們已修正將文件儲存成 HTML 格式時，長連結無法換行的問題。


- 我們已修正問題：如果您回復的父級註解在副檔名清單中有未知的副檔名，那麼回復將得到相同的副檔名。


- 我們已修正 Outlook 有關將郵件設定為 [不要轉寄] 的問題。


### <a name="office-suite"></a>Office 套件

- 解決已停用 ADAL 時，使用者無法匯入 SPO 清單的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-november-10"></a>版本 2008：11 月 10 日
*版本 2008 (組建 13127.20760)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel

- 我們已修正載入活頁簿之後特定功能可能會發生錯誤結果的問題。


- 我們已修正應用程式意外終止 (與 XLAM 增益集參照和命名範圍相關的問題) 的問題。


- 我們已修正使用巨集來設定某個範圍的 FormulaR1C1 屬性時，如果圖表工作表為作用中工作表，則儲存格參考會不正確的問題。


- 修正可能會導致「嘗試計算一個或多個公式時，Excel 資源不足」錯誤的問題。


- 修正當 Office 語言設定為西班牙文時，其中資料驗證清單可能無法顯示清單中所有項目的問題。


- 我們已修正在重新整理 OLAP 樞紐分析表時，可能會導致當機的問題。

### <a name="outlook"></a>Outlook

- 我們已修正一個問題，使用者現在可以停用 Outlook 的 IRM (資訊版權管理)，而不需要為其餘 Office 應用程式停用它。


- 我們已修正會導致使用者無法將 [編輯器] 權限授與代理人的問題。


- 我們已修正會導致使用者在選取搜尋結果時遇到意外終止的問題。


- 我們已修正會導致群組行事曆中的搜尋無法傳回任何結果的問題。


- 已解決導致代理人在開啟另一個信箱中的共用資料夾時出現錯誤的問題。


- 已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。


- 我們已修正在回覆或轉寄時，導致中文郵件標題出現亂碼的問題。

- 我們已修正選用連線體驗導致網頁增益集無法載入的問題。  <br />在[部落格文章](https://developer.microsoft.com/zh-TW/office/blogs/outlook-add-ins-and-optional-connected-experiences/)中查看詳細資料


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 Forms 內容增益集在插入之後不會呈現，除非使用者按一下另一張投影片讓它顯示才會呈現的問題。


### <a name="office-suite"></a>Office 套件

- 已解決針對使用 System Center Configuration Manager 或其他管理工具來使用 Microsoft 365 Endpoint 資料外洩防護進行 Office Update 的商業客戶的問題。

- 修正 Office 增益集的傳訊 API 無法正常運作的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-october-13"></a>版本 2008：10 月 13 日
*版本 2008 (組建 13127.20638)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正 PivotDateFilter API 中的錯誤，其中的 'Before' 和 'After' 篩選條件是相反的。


- 我們已修正使用者無法修改樞紐分析表篩選的問題，因為它已設定為Analysis Services數據庫中不再存在的值。


- 修正當凍結工作表頂端列之後，Excel 可能會在使用 [快速分析] 時當機的問題。


- 修正當活頁簿包含使用 IFNA () 的公式時，可能會造成錯誤活頁簿的警告之問題。


### <a name="outlook"></a>Outlook

- 解決由於按一下角落中的 [X] 而導致使用者無法關閉共用行事曆的問題。


- 解決會導致 [開啟共用行事曆改良] 設定有時候無法套用至現有共用行事曆的問題。


- 解決使用者嘗試開啟雲端附件時，會導致使用者在 safelinks 頁面上看到錯誤，而非所嘗試開啟文件的問題。


- 解決附件上傳的效能問題。


### <a name="powerpoint"></a>PowerPoint

- 此變更可解決「匯出為動畫 GIF」功能的問題，其中按一下 [匯出] 按鈕不會匯出。


- 安全性修正程式可解決在 [受保護的檢視] 中開啟 PowerPoint 檔案時會停用 IRM 保護的問題。

- 我們已修正在 PowerPoint 應用程式中 [動作設定] 對話方塊導致當機的問題。

### <a name="visio"></a>Visio

- 我們已修正會導致即時預覽在文字對齊時發生當機的問題。


### <a name="word"></a>Word

- 解決會導致使用者在開啟某些非常大型電子郵件時會遇到當機的問題。


- 我們已修正使用者開啟文件時可能會遇到當機的問題。


- 解決 Word 啟動時會導致當機的問題。


- 我們已修正 [樣式圖庫] 對話方塊的問題。


### <a name="office-suite"></a>Office 套件

- 當使用者從 Office 在噴墨印表機上列印任何文件/檔案且印表機墨水不足時，即使噴墨印表機並沒有碳粉，也會顯示「碳粉不足」或「無碳粉」訊息。變更訊息以顯示「碳粉/墨水不足」與「碳粉/墨水用完」。


- 修正使用 GIF/動畫 model3D 閒置時的高 CPU 使用量


- 此變更可解決啟動 Office 應用程式時由於無法載入 d2d1.dll 而產生的當機。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-08"></a>版本2008：9月 8 日
*版本 2008 (組建 13127.20408)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。 在 SQL 檢視中搜尋及取代文字。 在 [關聯圖] 視窗中選取多個資料表。

- **按幾下就能新增資料表：** 使用 [新增資料表] 工作窗格，當您工作時，該窗格會保持開啟狀態，以便將資料表新增至關聯和查詢。 [深入了解](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a>Excel

- **改善地圖圖表：** 我們讓地圖圖表變得更好，方法是將地圖圖表與可顯示有關對應位置豐富資訊的 Excel 地理資料類型整合。 [深入了解](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。<br />在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料

- **在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。  如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。 使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。 [深入了解](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br />在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料

- **您最愛的 Excel 函數計算速度提升了：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS 和 MINIFS 函數現在比以往更快了。 更快速地前往底線。 立即試用。

- **RealTimeData (RTD) 的改進** 在 Office 365 版本 2002 的每月通道或更新版本中，Excel RealTimeData (RTD) 函數速度快于 Excel 2010 計算試算表中的資料。 我們在其基礎記憶體和資料結構中移除了瓶頸，並使其成為安全執行緒，讓它可在多執行緒重新計算 (MTR) 的所有可用執行緒上計算。

### <a name="outlook"></a>Outlook

- **共用行事曆更新的速度更快：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。 開啟預覽以更快且更可靠地更新共用行事曆。

- **更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。 [深入了解](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。<br />在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料

- **將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。 您拖曳的郵件將會與所有群組成員共用。<br />在[部落格文章](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)中查看詳細資料

- **行事曆煥然一新：** 查看視覺更新，讓您的行事曆更容易流覽。 [深入了解](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />在[部落格文章](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)中查看詳細資料

- **加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。 將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。 [深入了解](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- **受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？ Outlook 現在會偵測這項要求並協助您取得連結。<br />在[部落格文章](https://insider.office.com/zh-TW/blog/outlook-on-public-wi-fi-networks-just-got-easier)中查看詳細資料

- **搜尋人員時取得電子郵件建議：** 當您在 [搜尋] 方塊中輸入人員的名稱時，最相關的電子郵件訊息會包括在您的搜尋建議中。 [深入了解](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a>PowerPoint

- **使用 \@ 提及取得他人注意** 在註解中使用 @ 提及功能讓同事知道您需要他們提供建議。[深入了解](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **改善地圖圖表：** 我們讓地圖圖表變得更好，方法是將地圖圖表與可顯示有關對應位置豐富資訊的 Excel 地理資料類型整合。 [深入了解](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **jiffy 中的 Gif：** 一個投影片、一個圖文框。 在 PowerPoint 中輕鬆建立迴圈 Gif。 [深入了解](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br />在[部落格文章](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)中查看詳細資料

- **更好的圖表：** 使用更完善的連接線和更平滑的筆跡轉換程式，您可以自信地用筆跡繪製您的想法。 [深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。<br />在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料

- **註解：** PowerPoint 中新增的註解體驗可讓您快速輕鬆地探索文件並新增註解。 使用註解錨定、解析、任務、已改進的提及通知等新功能使您的共同作業工作流程現代化。 [深入了解](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- **在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。 [深入了解](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />在[部落格文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看詳細資料

- **投影片連結:** 要求同事參與製作您的投影片組，讓他們直接在您需要協助的投影片上開始進行。 [深入了解](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br />在[部落格文章](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)中查看詳細資料

- **改善的 PowerPoint 中的 Steam 影片效能：** 我們改善了 Microsoft Stream 影片的播放效能，將影片載入時間減至最少，以建立出流暢的觀賞體驗。 您可以使用 Microsoft Stream 上您的公司影片來建立更完善的簡報。


### <a name="word"></a>Word

- **改善地圖圖表：** 我們讓地圖圖表變得更好，方法是將地圖圖表與可顯示有關對應位置豐富資訊的 Excel 地理資料類型整合。 [深入了解](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **對筆跡使用套索：**[繪圖] 索引標籤上的 [套索] 工具，可協助您選取使用筆跡繪製的物件。 選取個別筆劃或整個字。 [深入了解](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。<br />在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料

- **螢幕閱讀器的動作確認：** 確認動作是重要的協助工具要求。 隨著 Windows 引入新的通知 API 之後，我們現在就能通知螢幕助讀程式使用者的動作成功。 [剪下]、[複製]、[貼上]、[粗體]、[畫底線]、[復原]、[重做]、[自動校正] 和 [自動大小寫] 等功能都已公布給 Win32 Word 的朗讀程式使用者。 若要啟用此功能，請按 windows + ctrl + enter 以開啟朗讀程式。<br />在[部落格文章](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)中查看詳細資料

### <a name="office-suite"></a>Office 套件

- **敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 解決插入含有身分識別 (例如，自動編號) 欄位的連結 SQL 資料表的問題。

- 我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。

- 修正問題；您應該可以呼叫日期/時間延伸資料類型至您的程式碼，而不會在您的應用程式中遇到任何當機。

- 修正問題；您現在可以還原為最新的 Access 版本，並使用 DAO/VBA 來管理及編輯十進位資料類型。

- 此修正會解決嘗試執行之前會產生「查詢太複雜」錯誤訊息的特定查詢的問題。

- 存取已經修正了目前的問題，但將調查我們的其他介面，以確保這個問題不會持續存在。 小組會通知您未來的更新；我們感謝您的耐心等待。

- 已解决此問題 - 您現在可以使用 Office 的隨選即用應用程式外的 ODBC 驅動程式。

### <a name="excel"></a>Excel

- 自動文件分類可能已對處於唯讀模式的活頁簿發生。

- 修正若您已從帳戶登出，嘗試建立資料連線時，可能會發生的當機問題。

- 解決了嘗試將樞紐分析表插入圖表時 Excel 可能會當機的問題。

- 嘗試使用 LET() 函數儲存含有公式的檔案時發生錯誤。

- 修正使用 [複製格式] 時，某些情況下，Excel 可能會當機的問題。

- 修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。

- 修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。

- 修正在某些情況下，按一下同一個活頁簿中某個位置的超連結會導致活頁簿被隱藏的問題。

- 修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。

- 在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。

- 在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。

- 修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。

- 這解決了舊版 Office 中 SQL 資料提供者建立的連結設定內部表格内容與 Office 365 不同的問題。 這導致在舊版 Office 中使用 Office 365 開啟文件時，這些檔案的 [表格預覽/查詢編輯器] 下拉清單被停用。

- 解決當來源活頁簿關閉時，外部連結無法在填入時更新的問題。

- 修正筆跡會導致 Excel 無法回應的問題。

### <a name="onenote"></a>OneNote

- 透過在資訊列中通知使用者有關 Microsoft OneNote 中的暫時調整之資訊，將協助改善在全球高使用量期間的同步處理與服務可用性。

- 透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。

- 改善了共同撰寫狀態的偵測，以降低資源利用率。

- 透過暫時將 OneNote 2016 中新嵌入附件的最大允許大小減少為 50MB，來改善同步處理與服務的穩定性。 對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。

- 透過暫時停用 OneNote 2016 中的應用程式內視訊錄製，來改善同步處理與服務的穩定性。 本機筆記本不受這個值的影響。

- 透過暫時變更建立頁面版本歷程記錄的頻率，可改善同步處理與服務的穩定性。

- 透過暫時停用將頁面移動至資源回收桶，來改善同步處理與服務的穩定性。 若使用者想要刪除頁面，則會改為顯示詢問是否要永久刪除頁面的對話方塊。

### <a name="outlook"></a>Outlook

- 修正會導致使用者嘗試從次要帳戶建立會議邀請的問題，讓帳戶新增至他們的個人檔案，而不會看到空白的表格: 是欄位而不是其電子郵件地址。

- 修正新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。

- 解決了當代理人在某些情況下遭到拒絕而導致會議無法從經理的行事曆中移除的問題。

- 解決了導致使用 Shared Calendar Improvements 的某些使用者無法查看剛新增的共用行事曆的問題。

- 修正了當與雲端附件互動時，導致使用者偶爾當機的問題。

- 解決會導致 CLP 使用者在回覆時的寄件者地址，從受保護的內容切換到未受保護的內容時會發生當機的問題。

- 解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。

- 已解決有回應/轉寄標註的clp審查活動的問題。

- 已解決導致資料夾窗格寬度意外變更的問題。

- 解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。

- 解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。

- 解決會導致使用者在 Outlook 中更新其規則時，看到 [此電腦上的規則與 Microsoft Exchange 上的規則不相符] 訊息的問題。

- 解決會導致 Outlook 無法擷取搜尋建議的問題。

- 解決會導致共用行事曆改善功能的使用者看到行事曆失敗的問題。

- 解決會導致使用者在某些情況下遇到間歇性懸置和當機的問題。

- 解決了當您從 POP 帳戶刪除4或多個電子郵件時，已選取 [僅下載標題] 選項時，導致使用者遇到當機的問題。

- 解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。

- 解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。

- 解決使用者在第三方 MAPI 應用程式中遇到當機的問題。

- 已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。

- 已解決導致 Outlook 在某些 Windows 組建上當機的問題。

- 解決會導致 Windows 10 伺服器版本的使用者看到警告「防毒軟體狀態: 無效」的問題。 這個版本的 Windows 支援防毒偵測，但找不到任何防毒軟體。]，即使已正確安裝防毒軟體。

- 已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。

- 已解決導致 Outlook 在某些 Windows 組建上當機的問題。

- 解決會導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。

- 解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。

- 解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。

- 解決導致 [排程助理員] 頁面無法顯示的問題。

- 解決導致 [排程助理員] 頁面無法顯示的問題。

- 解決會導致使用者在擷取角色資訊時有時候會當機的問題。

- 修正了編輯收件者時，導致使用者偶爾當機的問題。

- 修正會導致使用者在使用壓縮模式時發生異常的問題。

- 解決會導致 Outlook 使用者在精簡檢視中看到瀏覽問題的問題。

- 解決的問題導致在搜尋控制項中無法顯示滑鼠右鍵功能表。

- 解決會導致使用者在回覆或撰寫新電子郵件時收到下列錯誤的問題：「這個網頁中的某些檔案不存在預期的位置， 請問您一定要下載嗎? 如果您確定網頁來自信任的來源，請按 [是]」

- 解決導致使用者在退出 Outlook 時遇到掛斷的問題。

- 解決會導致在「建議功能」中尋找功能不會傳回結果，因而讓使用者無法選擇提交新功能想法的問題。

- 解決事件通知警示中導致格式設定問題的問題。

- 已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。

- 我們已修正複製和貼上 SVG 影像的問題。

- 修正編輯收件者時，導致使用者偶爾當機的問題。

- 我們已修正複製和貼上 SVG 影像的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正使用者在同一檔案中同時有新版和舊版批註，因此觸發批註的升級而當機的問題。

- 我們已修正 PowerPoint 應用程式的當機問題。

- 我們已修正建議窗格的當機問題。

### <a name="project"></a>Project

- 修正在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件的問題。

- 修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。

- 修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。

- 修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。

- 修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。

- 修正無法正確計算摘要工作日期的問題。

- 修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。

- 修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。

- 修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。

- 修正當您貼上的工作具有多個依存性時，無法正確複製所有依存性的問題。

- 修正無法將 PDF/XPS 從 Project 儲存至 SharePoint 文件庫的問題。

- 修正當標示為 100% 完成之工作錯誤地變更為低於 100% 完成的問題。

- 修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。

- 修正如果資源中定義了多個成本費率表，其餘成本並不一定都能正確地計算的問題。

- 修正「連結至 SharePoint 工作清單的專案的完成日期沒有更新」的問題。

- 修正 [指派資源] 對話方塊中選取的工作與工作面板檢視中所選工作不同的問題。

- 修正無法開啟已進入錯誤狀態的專案的問題。

### <a name="skype"></a>Skype

- 當使用者收到將他們移至 Teams Only 的原則時，他們仍然可以使用商務版 Skype Outlook 增益集來排程會議。 在此更新之後，當客戶端讀取指示用戶為 Teams Only 的策略並進入僅限會議加入模式後，您將不再能用商務版 Skype 安排會議。 此外，如果商務版 Skype Outlook 增益集發現商務版 Skype 用戶端處於 [僅限會議加入] 模式，就無法自行啟動。

- 將跳舞表情符號膚色變更為中性色彩.

### <a name="word"></a>Word

- 解決 URL 包含查詢元件時，從自訂文件傳遞 (aspx) 開啟 Word 文件的問題。

- 此更改解決了一個問題，即在上一個協同合作的作業後，Microsoft Office 應用程式可能卡在未通知的儲存失敗狀態的問題。

- 解決會導致使用者在回覆或撰寫新電子郵件時遇到當機的問題。

- 解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。

- 我們已修正複製和貼上 SVG 影像的問題。

- 我們已修正當調整圖案大小時，使用者可能會遺失內容的問題。

- 我們已修正基本樣式並未以 [內文樣式] 更新的問題。

- 我們已修正巨集 AutoOpen 在 AutoExec 之前執行的問題。

- 我們已修正複製和貼上 SVG 影像的問題。

- 解決會導致從應用程式拖曳部分內容時遇到當機的問題。


### <a name="office-suite"></a>Office 套件

- 針對舊版非 Web 服務的 [共用] 窗格，在開啟 [共用] 窗格的情況下關閉文件時，可能會導致當機。現已修正此問題。

- 修正關閉 Office 檔案時，計時問題可能會導致當機的問題。

- 我們透過設定Bing附加預設安裝驗證設定為true默認，並將MSI返回成功視為安裝成功，而解決了 ValidateInstall 失敗率問題。

- 我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。

- 修正當嘗試硬連結符號連結時，導致更新失敗的 [點擊運作] 問題。

- 修正即使完整產品的轉換已完成，也會導致執行階段訊息顯示的問題。 此問題的修正程式是確保服務正確計算新增的產品。 我們已篩選出新增的產品 (確保它們同時存在於新的設定中)，並將它們新增到現有產品發行識別碼的結尾。

- 我們已修正使用者在特定情況下 (特別是進入或退出簡報者檢視畫面或使用多個監視器) 看到 UI 元素或內容未顯示的問題。

- 此變更會解決載入和播放動畫內容 (例如 Gif 或3D 模型) 時可能會發生的懸置。

- 此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。

- 此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。

- 此修正可解決同時防止限制存取和保護設有密碼之檔案的錯誤。

- 解決在登錄 TabProcGrowth 值為 REG_SZ 類型的情況下啟用增益集時，Windows 中的 Office 主機會當機的問題。

- 當登錄機碼 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth 設為零，且正在啟用增益集時，Office 主機會在 Windows 中當機。此變更可修正此問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-august-11"></a>版本 2002: 8月11日
*版本2002（组建12527.20988）*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正無法將以 [唯讀建議] 方式開啟的檔案切換至編輯功能的問題。

### <a name="onenote"></a>OneNote

- 移除了多餘的身分識別通話，以降低資源使用率

- 改善了共同撰寫狀態的偵測，以降低資源利用率。

- 改善了偵測錯誤的功能和同步處理經驗的品質。

### <a name="outlook"></a>Outlook

- 解決了在啟動某些租使用者的 Outlook 時，會導致嚴重效能問題的問題。

### <a name="skype"></a>Skype

- 修正在執行數天後，會無法啟動 32位元 Skype 商務版客戶螢幕共享的問題。

### <a name="office-suite"></a>Office 套件

- 修正如果 [自動儲存] 已透過組織政策關閉的話，某些文件可能不會在開啟時顯示最新的伺服器內容，除非使用者點擊 [可用的更新] 才會顯現。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-july-14"></a>版本 2002：7 月 14 日
*版本 2002 (組建 12527.20880)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 加速載入本機 OneDrive 資料夾中的檔案。

- 修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。

- 修正因為增益集是以字母順序載入，而不是以使用者指定的順序載入，而顯示 [這個活頁簿目前正由其他活頁簿所參考中，不可關閉] 錯誤訊息的問題。

- 修正按一下已開啟活頁簿中某個位置的超連結時，活頁簿可能會隱藏的問題。

- 我們已修正某些複製和貼上的圖表連結使用的是映射磁碟機位址，而不是通用位址的問題。

- 改善刪除具有合併儲存格的欄時的效能。

- 修正 [列印] 對話方塊的印表機清單中，印表機名稱可能會重複的問題。

- 我們已修正包含多個含有定義名稱的公式會導致儲存檔案時間加長的問題。


### <a name="outlook"></a>Outlook

- 我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。

- 解決會導致週期性約會或會議在接近時區定義變更時於錯誤的時間顯示的問題。

- 解決會導致使用者在 Outlook 中更新其規則時，看到 [此電腦上的規則與 Microsoft Exchange 上的規則不相符] 訊息的問題。

- 解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。

- 已解決會導致類別有時候會從電子郵件訊息中消失的問題。

- 已解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。

- 解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。

- 解決在編輯主旨之後，會導致 NDR 訊息的本文從 Unicode 變更為 ASCII 的問題。

- 解決當兩個增益集將一個按鈕新增到相同功能區群組時，會導致使用者遇到當機的問題。

- 解決了導致使用者無法將電子郵件傳送到個人通訊群組清單的問題。

- 解決當租用戶預設權限設定為「任何人」時，會導致無法將連結新增至具有正確租用戶預設權限的電子郵件的問題。

- 解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。

### <a name="word"></a>Word

- 我們已修正啟用原則 FileBlick\Word2007Files 時共同編輯中的問題。

- 我們已修正新增已重新命名之查閱欄位時，Word QuickPart 無法使用的問題。

### <a name="office-suite"></a>Office 套件

- 修正當共同撰寫大型 PowerPoint 檔案時，使用者可能會遇到過度網路和 CPU 使用量的問題。

- 我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。

- 解決在登錄 TabProcGrowth 值為 REG_SZ 類型的情況下啟用增益集時，Windows 中的 Office 主機會當機的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-june-09"></a>版本 2002: 6 月 09日
*版本2002（組建12527.20720）*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。

- 修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。

- 修正列印時表單控制項的核取方塊縮放的問題。

- 當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。

- 在已篩選清單中插入欄的時間會比預期更長。

- 修正開始公式的 @ 符號會被視為隱式交集運算子的問題。

### <a name="outlook"></a>Outlook

- 可透過原 Teams 客戶直接啟用加入 Teams 會議。

- 解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。

- 解決了導致瀏覽器模擬設置錯誤的用戶無法完成 Gmail 身分驗證提示的問題。

- 解決了導致伺服器作業系統上的 Outlook 使用者看到「防病毒處理狀態：無效」的問題。 這個版本的 Windows 支援防毒軟體檢測，但即使已適當設定防毒軟體，也無法找到防毒軟體。

### <a name="word"></a>Word

- 我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。

### <a name="office-suite"></a>Office 套件

- 我們將後台中的頻道名稱更新為2020年1月 Fork 的新通道名稱，解決了此問題。

- 我們已修正此問題，如果裝置受政策管理，將不會調用 DMS 聽眾 API。

- 已解決在單一交易中新增和移除應用程式時，未完成移除的問題。

- 當登錄機碼 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth 設為零，且正在啟用增益集時，Office 主機會在 Windows 中當機。此變更可修正此問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-may-12"></a>版本 2002：5 月 12 日
*版本 2002 (組建 12527.20612)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel

- 開啟含有許多其他活頁簿 (尤其是含有隱藏視窗) 參照的活頁簿時，速度比預期慢。

- 在某些情況下，開啟 CSV 檔案所花費的時間超過預期。

- 在某些情況下，當您切換不同縮放比例的活頁簿時，Excel 可能會當機。

- 修正 VBA 將值寫入範圍時，速度比預期慢的問題。

- 從有色彩篩選的欄複製的資料有時候無法正確貼上。

- 修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。

- 在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。

- 已解決在儲存並重新開啟檔案時，圖表軸上的 "Value Crosses At" 屬性發生意外變更的問題。

- 使用 Range.Value 和 Range.Value2 (VBA) 會導致公式以動態陣列的形式輸入。

### <a name="onenote"></a>OneNote

- 對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。

- 顯示通知，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。

- 在 OneNote 2016 中暫時降低版本歷程記錄頁面的數目和同步處理頻率，以改善同步處理與服務穩定性。

- 透過暫時停用 OneNote 2016 中的資源回收筒，來改善同步處理與服務的穩定性。當使用者嘗試刪除通常會傳送到 [資源回收筒] 的資料時，系統會詢問使用者是否希望保留或永久刪除資料。

- 透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。

- 暫時延遲下載線上筆記本中內嵌的檔案和影像，直到使用者瀏覽至 OneNote 2016 中的頁面，以改善同步處理與服務的穩定性。

- 透過暫時停用 OneNote 2016 中的應用程式內視訊錄製，來改善同步處理與服務的穩定性。 本機筆記本不受這個值的影響。

- 透過暫時將 OneNote 2016 中新嵌入附件的最大允許大小減少為 50MB，來改善同步處理與服務的穩定性。 對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。

### <a name="outlook"></a>Outlook

- 已解決導致資料夾窗格寬度意外變更的問題。

- 解決以下問題：Windows 更新之後，使用者開啟 .msg 和 .oft 檔案時遇到當機。

- 解決會導致使用者在轉寄大型 HTML 郵件時，看到郵件內文截斷的問題。

- 此更新修正在查看或撰寫郵件時，Microsoft Outlook 未顯示目前的敏感度標籤的問題。

- 解決了導致使用者無法將電子郵件傳送到個人通訊群組清單的問題。

### <a name="powerpoint"></a>PowerPoint

- 修正以下問題：當開啟的檔案複本具有增強式註解時，為使用者轉送正確的訊息。

### <a name="word"></a>Word

- 解決了 Access 和 Publisher 因所安裝的語言而無法正常啟動的問題。

- 修正受保護無法編輯之文件的比較功能問題。

- 我們已修正將兩份文件合併成一份文件時的問題。

### <a name="office-suite"></a>Office 套件

- 此修正解決了當檔案已在用戶端中進行快取時，Project 應用程式不應封鎖網路。

- 我們已解決內部作業在失敗時擲出例外狀況，而不是記錄和繼續進行的問題。 受影響的使用者將不會再無法收到更新。

- 這項變更可確保草繪大綱可在功能區中正常運作。

- 修正使用一些特定 proxy 設定時，從內部部署位置開啟檔案時發生的問題。

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。

- 此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。

- 此更新解決了 Microsoft Word 中的一個問題：如果標籤原則套用了頁首或頁尾或浮水印，那麼在套用敏感度標籤時，插入長度超過 255 個字元的文字後續將無法透過變更或刪除標籤來識別和刪除。

- 修正問題，可在 Office 遞交工作階段期間消除當機，並改善使用者體驗中的可靠性。  

- 這個錯誤會更新增強的設定服務 (ECS) url 端點。 呼叫這個較新的端點，可從 ECS 進行提取獲得更高的成功率。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-april-14"></a>版本 2002：4 月 14 日
*版本 2002 (組建 12527.20442)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **輸入會傳回多個值的公式**：現在您可以快速輸入公式來傳回多個值，並且值會自動溢出至相鄰的儲存格。 [深入了解](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- **六個功能強大的函數：** 我們新增了六個新的函數，讓您的試算表功能更強大：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。  [深入了解](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- **向左看，向右看... XLOOKUP 在這裡！：** 一列接著一列，在含有 XLOOKUP 的表格或範圍中尋找您需要的項目。  
  [深入了解](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 重複開啟內嵌在 Word 或 PowerPoint 中的活頁簿時，在某些情況下，Excel 會當機。

- 儲存為 CSV 檔案時，在某些情況下，Excel 會將所有欄合併成單一欄。

- 在受保護工作表中的範圍使用 Range.ClearContents 可能會比預期花的時間更長。

- 修正在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。

- 與功能區互動的 VBA 宏可能會意外以 ScreenUpdating 設定為 True 執行。

- 解決了當來源活頁簿關閉時，外部連結無法在填滿時 (向下填滿、跨表填滿等) 更新的問題。

- 在某些情況下，使用 VBA 的 Application.Evaluate 對使用者定義的函數無法運作。

- 解決從範本建立圖表時的效能問題。


### <a name="outlook"></a>Outlook

- 解決了在某些情況下，[群組] 標題會意外展開的問題。

- 解決了導致使用者在選取特定搜尋結果時發生當機的問題。

- 解決了使用滑鼠上的 X 按鈕時，導致使用者偶爾發生當機的問題。

- 解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。

### <a name="powerpoint"></a>PowerPoint

- 已改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並貼到迴圈中的其他投影片，可能會出現例外狀況而失敗。


### <a name="project"></a>Project

- 修正儲存使用舊版 [專案] 建立的專案時，[專案] 可能當機的問題。

- 修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。

### <a name="word"></a>Word

- 解決了使用滑鼠上的 X 按鈕時，導致使用者偶爾發生當機的問題。

- 我們已修正表格中最適文字大小的問題。

- 我們已修正插入水平線無法更短並置中的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-10"></a>版本 2002：3 月 10 日
*版本 2002 (組建 12527.20278)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **快速尋找連結資料表：** 新的搜尋方塊可讓您輕鬆尋找連結資料表。 [深入了解](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **使用 \@ 提及取得他人注意** 在註解中使用 @ 提及功能讓同事知道您需要他們提供建議。[深入了解](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **找到您要尋找的項目：** 搜尋命令、人員、檔案、相片、網頁文章等。 [深入了解](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **勾勒草圖：** 為活頁簿中的 Office 圖形提供隨意的手繪外觀。 [深入了解](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。

- **專注在待辦事項上：** 選取 [解決] 來摺疊註解，使得開啟中的項目能夠突顯。

- **建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。 [深入了解](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **轉換檔案，以提升存取性：** 將您的檔案升級為現代格式，讓所有人更容易存取。

- **資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。 [深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。

- **在活頁簿上取得統計資料：** 活頁簿統計資料提供活頁簿內容的概觀，協助您更輕鬆地探索其內容。

- **符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。 其位置：[插入] > [圖示]。 [深入了解](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a>Outlook

- **將您的 LinkedIn 人際網路連接至 Outlook：** 安全地將您的 LinkedIn 帳戶與 Microsoft 帳戶連結，以直接在人員卡片中查看 LinkedIn 個人資料中的資訊。 [深入了解](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- **集中所有加密選項：** 只要前往 [選項] > [加密]，即可選擇要用來保護電子郵件訊息的方法。[深入了解](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)

- **Outlook 中的 [插入連結] 功能表會插入含有租用戶系統管理員所定義的權限的連結：** Outlook 中使用 [插入連結] 所插入的連結，只有具有連結權限的使用者可使用。 這常會造成使用者來回傳送電子郵件，要求對方授與文件的存取權。 我們已更新這項體驗，現在插入的連結將具有由租用戶系統管理員設定的預設權限。針對 MSIT，這是「組織可以編輯」，使得以此方式收到共用連結的所有內部使用者將可以存取它。

- **具有拼字問題或錯字的搜尋：** 即使您的拼寫不相符，Outlook 也會找到您要尋找的內容。

- **網路釣魚郵件很容易找到：** 垃圾郵件和網路釣魚訊息的外觀不同，因此您可以從收件匣輕鬆找出並加以清除。

- **抵禦攻擊的進階防護：** 使用 Office 365 進階威脅防護，您會受到保護，不受電子郵件主旨、附加的郵件、簽署的郵件、網路路徑內超連結的攻擊。

- **讓我繪製：** 使用筆跡在圖片上徒手畫或新增繪圖畫布來傳達您的想法。 [深入了解](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- **在搜尋結果中查看相關郵件：** Outlook 會分析搜尋字詞，然後在搜尋結果的最上方顯示最相關的電子郵件。 您也可以在 [最佳結果] 區段中查看依日期排列順序的所有結果。 [深入了解](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- **取得位置建議：** 排程約會和會議時，請在 [位置] 中開始輸入，Outlook 會建議會議室、地址，以及其他最近使用的位置。 [深入了解](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- **在螢幕上容納更多郵件：** 選取 [檢視] > [使用更緊密的間距] 來調整郵件之間的間距。 [深入了解](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- **在不同燈光下查看郵件：** 使用太陽/月亮按鈕以在讀取窗格中於淺色和深色背景之間切換。 [深入了解](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- **符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。 其位置：[插入] > [圖示]。 [深入了解](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a>PowerPoint

- **在 PowerPoint 中快速即時共同作業：** 在 PowerPoint 中快速即時共同作業

- **新的校對工具：** 不著重您的文字。 PowerPoint 現在提供文法及書寫建議。 [深入了解](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- **即時的輔助字幕和翻譯字幕：** 簡報者的文字會自動顯示為畫面上的標題，或翻譯為所選語言的字幕。 [深入了解](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **您來計算，格式設定交給我們** 我們能將難懂的手寫數學運算式變更為標準字元。只要選擇 [筆跡轉換數學]，然後選取您的手寫筆記，即可開始使用。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。 [深入了解](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **尋找並修正遺失的投影片標題：** 投影片標題可為您的企劃加分，並讓所有功能的使用者都能存取投影片。 協助工具檢查程式會顯示缺少標題的地方，這樣您就可以快速新增標題。 [深入了解](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **勾勒草圖：** 為簡報中的 Office 圖形提供隨意的手繪外觀。 [深入了解](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。

- **將圖例另存成 SVG：** 將圖表、圖形或其他圖例另存成可縮放向量圖形，其可調整大小，且不損失影像品質。 [深入了解](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **列印講義上的投影片編號：** 投影片編號會自動包含在講義上。 由您決定將其保留或關閉。 [深入了解](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **筆跡立即重播：** 當您在投影片上進行手寫時，套用重播動畫可在投影片放映期間重播真實手繪的筆跡。 [深入了解](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- **建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。

- **全方位最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。

- **轉換檔案以增強協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。

- **更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。

- **當您可以重複使用時為什麼要重新打造？** 重複使用您所建立的投影片或其他人與您共用的投影片來以節省時間。 [深入了解](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- **在 Office 365 的 PowerPoint 中將手寫筆跡變更為圖形、文字或數學：** 從任意格式的筆跡變成 Office 圖形、文字，或以幾個筆劃變成數學運算式。 [深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **運用筆跡製作精彩的投影片：** 將筆跡轉換成標準圖形和文字，然後從 PowerPoint 設計工具吸取智慧的投影片設計概念。[深入了解](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- **符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。 其位置：[插入] > [圖示]。 [深入了解](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a>Visio

- **回到犯罪場景：** 在犯罪場景調查範本中使用新的證據、室內、室外樣板，重建犯罪場景的細節。

- **在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。 [深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **簡歷編輯器加入 LinkedIn 簡歷小幫手：** 簡歷編輯器提供特別為簡歷量身打造的文法和樣式檢查選項，讓您的寫作更準確且更專業。

- **修正合併 3D 物件所造成的文件損毀問題：** 修正合併 3D 物件所造成的文件損毀問題。

- **尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。 [深入了解](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **在生動色彩中進行共同作業：** 註解和變更都依參與者加上色彩標示，讓您可以輕鬆查看您的共同作業者。

- **共同編輯啟用巨集的文件：** 將 docm 檔案儲存在商務用 OneDrive，並與共同作業者即時編輯。

- **共同撰寫的增強功能**：在具有追蹤修訂的文件中共同撰寫來強化 Word 效能。

- **符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。 其位置：[插入] > [圖示]。 [深入了解](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。

- **勾勒草圖：** 為文件中的 Office 圖形提供隨意的手繪外觀。 [深入了解](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **精確橡皮擦：** 從兩個橡皮擦尺寸中選擇，以修正小型筆跡缺陷。 [深入了解](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。 [深入了解](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- **共同撰寫的增強功能**：增強共同撰寫時的可靠性。

- **建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。 [深入了解](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。

- **更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。 [深入了解](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致錯誤「查詢已損壞」的問題。

- 此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。

- 此更新會修正使用 ADODB 的問題。VB 程式碼中的錄製程式物件可能會不正確地報告錯誤。

- Access 範本應不再導致資料庫中的附件欄出現故障。 個體化範本後，您現在應該可以將附件欄新增至資料庫。

### <a name="excel"></a>Excel

- 解決重新命名簽名時，使用者遇到當機的問題。

- 這項變更透過利用軟體轉譯來避免特定 Intel 圖形驅動程式的問題。

- 修正對具有溢出陣列之儲存格進行資料剖析的轉換時，導致某些使用者發生當機的問題。

- 此更新可修正導致資料編輯列以預期不同的字型顯示文字的問題。

- [資料剖析] 功能對某些地區設定可能會失敗。

- 使用者在存取隱藏的命名範圍時可能會遇到錯誤。

- 使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。

- 解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。

- 從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。

- 某些當地語系化版本的 [資料剖析] 功能可能會失敗。

- 使用者在存取隱藏的命名範圍時可能會遇到錯誤。

- 使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。

- 修正某些使用者使用內嵌和連結化物件 (OLE) 時可能發生的問題。

- 我們已修正樞紐分析圖的右鍵功能表，以啟用 [顯示詳細資料] 選項。

- 解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。

- 修正當活頁簿中有外部連結時，有些使用者可能會遇到多個彈出式視窗的問題。

- 修正操作功能表中未顯示註解命令的問題。

- 解決開啟內嵌活頁簿時，功能區自訂無法載入的問題。

- 修正 CUBEVALUE 函數有時會傳回不正確結果的問題。

### <a name="outlook"></a>Outlook

- 已解決導致在搜尋意見反應體驗中懸置的問題。

- 解決在擷取雲端設定時，導致使用者在 Outlook 中遇到當機的問題。

- 解決導致搜尋方塊在高 DPI 模式中未正確對齊的問題。

- 解決導致使用者在 Outlook 處理序中看到記憶體流失的問題。

- 解決在某些情況下，導致使用者看到電子郵件傳送到與顯示的 SMTP 位址不相符之地址的問題。

- 此變更會還原在郵件標頭中檢視多行主旨的功能。

- 我們已修正會防止將檔案儲存到 WebDAV 位置的問題。

- 修正 SMIME 演算法選取的問題。

- 解決導致協力廠商應用程式無法傳送電子郵件的問題。

- 已解決導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定] 按鈕的空白訊息方塊的問題。

- 解決導致使用者在建立設定檔時遇到當機的問題。

- 解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。

- 解決導致使用黑色佈景主題的使用者看到 [寄件者] 下拉式清單在白色背景上顯示白色文字的問題。

- 已解決導致使用者在取消帳戶設定時發生當機的問題。

- 解決重新命名簽名時，使用者遇到當機的問題。

- 已解決導致在某些情況下無法使用相關選項來停用標幟項目醒目提示的問題。

- 已解決導致使用者在開啟 [規則] 對話方塊時看到「在這部電腦中建立的規則和 Microsoft Exchange 上的規則衝突」提示的問題。

- 已解決導致使用者在指定無效寄件者地址時發生當機的問題。

- 解決導致非常長時間的 Outlook 工作階段記憶體流失的問題。

- 解決在多個視窗中檢視相同項目時可能會導致當機的問題。

- 解決當使用者透過鍵盤快速鍵與信箱資料夾互動時，導致明顯延遲的問題。

- 解決導致使用者無法開啟某些週期性行事曆項目執行個體的問題。

- 解決導致使用 Exchange 2010 伺服器上信箱的使用者在將附件新增至行事曆項目時遇到問題的問題。

- 解決導致使用者在回覆數位簽章的郵件時發生問題的問題。

- 解決會導致會議中的 [位置] 欄位意外更新的問題。

- 解決導致會議的位置欄位中的逗號變成分號的問題。

- 解決導致會議位置在清除之後，又會不預期地重新加回會議的問題。

- 解決與在巴西時區中設定的會議和約會相關的問題。

- 解決當您關閉協助工具檢查程式窗格之後按 [S] 鍵時，導致使用者看到郵件意外傳送的問題。

- 這會更新 Outlook 中的附件封鎖邏輯，以同時封鎖 Python 附件。

- 解決導致網頁增益集存取數位版權管理郵件的問題。

- 解決導致使用者在建立設定檔時遇到當機的問題。

- 解決重新命名簽名時，使用者遇到當機的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正 Shape.Paste 方法的問題：當使用者使用 Shape.Paste 方法複製並貼上圖形時，它會將選取範圍變更為貼上的圖形。

- 解決在舊版 PPT 註解中使用操作功能表時可能發生當機的問題。

### <a name="project"></a>Project

- 發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。

- 修正固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成的問題。

- 修正無法正確計算摘要工作日期的問題。

- 修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。

### <a name="word"></a>Word

- 我們已修正在某些情況下，儲存現有檔案永遠會導致出現 [另存新檔] 對話方塊且檔案永遠不會儲存的問題。

- 建置組塊組合管理可能會顯示無效的通知：「您已經修改樣式、建置組塊」。

### <a name="office-suite"></a>Office 套件

- 此變更可解決轉譯某些含有資料標記的散佈圖緩慢的問題。

- 此變更可解決所報告使用 Intel 整合式 GPU 圖形配接卡的問題。

- 修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤，此修正可啟用後續更新的相關期限。

- 解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。

- 修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-february-11"></a>版本 1908：2 月 11 日
*版本 1908 (組建 11929.20606)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 此更新已修正使用 VBA 將影像新增到圖表的頁首/頁尾時發生錯誤的問題。

- 修正在預覽列印或列印時群組方塊控制項的框線無法顯示的問題。

- 使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。

- 修正圖表標題中影像檔案大小在儲存包含圖表的活頁簿時增加的問題。


- 修正以下問題：將選取範圍與交互參照的活頁簿保持同步時，導致交互參照的活頁簿中的 DBCS 字元損毀。

- 已解決使用自動調整來調整列高時，核取方塊可能收縮的問題。


### <a name="outlook"></a>Outlook

- 已解決導致使用者在指定無效寄件者地址時發生當機的問題。

- 已解決導致使用者處理衝突郵件時同步失敗的問題。

- 已解決導致使用者在啟動 Outlook 時，「正在載入設定檔」畫面時停滯的問題。

- 已解決導致使用者在變更檢視時發生當機的問題。


- 已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。 [此處](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是記錄舊版問題的個別 KB。

- 已解決以下問題：使用者將共用行事曆資料夾同步到 OST 時發生問題，這導致嘗試與這些資料夾互動時發生權限錯誤。


### <a name="powerpoint"></a>PowerPoint

- 已改善複製貼上的案例，即將 PowerPoint 投影片中的圖形複製並貼到其他投影片可能會因為異常而失敗。


- 修正導致共同作業使用者之間效能較低的問題。

- 修正以下問題：當檔案以漸進式開啟時，若其中一個投影片包含多個內嵌媒體串流可能會發生問題。

- 修正以下問題：首次啟動 PowerPoint 時，不受信任的增益集可能不會顯示安全性警告訊息列。

### <a name="project"></a>Project

- 修正以下問題：由於基準行事曆變更時未更新資源行事曆，而導致時程表和專案計劃之間的實際工作可能不同。

### <a name="word"></a>Word

- 已從遭取代的 API 移除，以修正 Word 的當機問題。

### <a name="office-suite"></a>Office 套件

- 此變更解決開啟損毀的檔案時正確呈現影像的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a>版本 1908：1 月 14 日
*版本 1908 (組建 11929.20562)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


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

- 修正 Office 更新訊息不以預期語言顯示的問題。 自此以後，Office 更新訊息會正確符合 Windows 顯示語言。

- 解決在某些情況下，如果使用者不是系統管理員且系統帳戶沒有網路連線，將無法套用更新的問題。



## <a name="version-1908-december-10"></a>版本 1908：12 月 10 日
*版本 1908 (組建 11929.20516)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 已修正包含參照遠端桌面 (例如 SQL Server 桌面) 的聯集查詢可能造成 Access 關閉並重新啟動的問題。

- 已修正彙總 (例如 Sum) 可能會將結果截斷成整數值的問題。

### <a name="excel"></a>Excel

- 解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。

- 我們已修正當 OLAP 樞紐分析表的篩選條件設定為已從 cube 移除的值時會發生的問題。

- 這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。

- 已解決 Lookup 函數可能會傳回錯誤的問題。

- 已大幅改善刪除有合併儲存格之欄的效能。

- 已解決造成執行階段錯誤啟動最小化視窗的問題。

### <a name="outlook"></a>Outlook

- 已修正 SMIME 演算法選取的問題。

- 解決會導致使用者在開啟 [規則] 對話方塊時看到「在這部電腦中建立的規則和 Microsoft Exchange 上的規則衝突」提示的問題。

- 已解決造成網頁增益集在不該存取數位版權管理郵件時進行存取的問題。

### <a name="word"></a>Word

- 我們已修正追蹤修訂有時候會進入無限迴圈的問題。

### <a name="office-suite"></a>Office 套件

- 已修正 PowerPoint 中半形片假名字元在垂直文字方塊中無法正確旋轉的問題。

- 解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。

- 為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-november-22"></a>版本 1908：11 月 22 日
*版本 1908 (組建 11929.20494)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="access"></a>Access

- 已修正執行更新查詢會不正確顯示「查詢損毀」錯誤訊息的問題。

### <a name="excel"></a>Excel

- 當檔案具備大量設定格式化的條件時，按一下 [字型色彩] 按鈕時出現的效能緩慢問題。

- 我們已修正預覽列印中的列印範圍不正確的問題。

- 從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。

- 解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。

### <a name="outlook"></a>Outlook

- 解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定]&quot;&quot; 按鈕的空白訊息方塊的問題。

- 進行一項變更，可讓系統管理員啟用一個原則，以在自動探索驗證提示中較 UPN 優先使用所提供的帳戶電子郵件。依預設，自動探索會優先於帳戶 UPN (如果有的話)。

- 解決會導致使用者看到針對新式群組的搜尋失敗的問題。

- 解決會導致使用者嘗試從「未接的交談」&quot;&quot;建立規則時遇到當機的問題。

- 解決會導致使用者看到針對新式群組的搜尋失敗的問題。

### <a name="word"></a>Word

- 我們已修正當列印到 Deskjet 印表機時，可能會導致縮放比例問題的問題。

### <a name="office-suite"></a>Office 套件

- 修正會在嘗試進行「線上展示」時防止 PowerPoint 使用者遇到錯誤的問題。

- 改善有關登錄完整性的 Office 更新程序的可靠性。

- 已更正可能會在計量網路上意外封鎖更新的問題。

- 修正 ODT 和 GPO 更新期限設定中的問題，在其中，相對期限只有在第一次設定時才會有效，此修正可啟用後續更新的相關期限。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-november-12"></a>版本 1908：11 月 12 日
*版本 1908 (組建 11929.20436)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel

- 修正以校正使用圖表範本插入圖表時，預覽中使用的色彩。
- 我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題。
- 解決使用執行中巨集變更自訂屬性時，會導致共同撰寫中斷的問題。
- 我們解決了非同步使用者定義函數造成的效能問題，導致它們同步執行。
- 我們已大幅提升依色彩篩選的效能。
- 解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題。
- 來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。

### <a name="outlook"></a>Outlook

- 來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。
- 已解決當使用者將項目從其主要行事曆複製到群組行事曆時，造成使用者遇到權限錯誤的問題。
- 已解決導致非常長時間的 Outlook 工作階段記憶體流失的問題。
- 解決會導致使用者在與特定安全連結互動時在 Outlook 中遇到失敗的問題。
- 解決會導致使用者在處理某些自動探索回應時遇到失敗的問題。
- 已解決導致某些使用者在新增次要 Exchange 帳戶時看到建立了重複特殊資料夾的問題。
- 已解決導致在搜尋意見反應體驗中懸置的問題。

### <a name="powerpoint"></a>PowerPoint

- 來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。
- 可靠性修正：修正第三方增益集可能會造成 PowerPoint 失敗的問題。

### <a name="project"></a>Project

- 修正 [全部撫平] 命令無法正確解決資源過度分配的問題。
- 修正當您有作業中有零個工作的指派時，可能無法將作業標示為完成且永遠會顯示為 99% 的問題。
- 發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。

### <a name="word"></a>Word

- 來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。
- 修正應用程式可能在關機時懸置的各種問題。 同時修正特定增益集相關失敗的問題。

### <a name="office-suite"></a>Office 套件

- 已解決第三方外掛程式中與文字方塊/圖案自動調整屬性相關的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="october-15"></a>10 月 15 日

### <a name="non-security-updates"></a>非安全性更新

### <a name="office-suite"></a>Office 套件
- 我們已暫時停用 [雲端儲存] 對話方塊以解決在 2019 年 10 月14 日針對早於 16.0.11929.20396 的組建所發佈的儲存問題。這項功能即將重新啟用。

## <a name="version-1908-october-14"></a>版本 1908：10 月 14 日
*版本 1908 (組建 11929.20396)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="excel"></a>Excel

- <div>解決「尋找及取代」在找到第一個項目後，對話方塊中的焦點位置變更的問題。</div>

### <a name="office-suite"></a>Office 套件

- 解決使用者使用早於 16.0.11929.20396 的組建時，可能無法儲存 Word、Excel 和 PowerPoint 2019 文件的問題。此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存新檔] 對話方塊的使用者。

- 解決在某些情況下，Office 快速鍵可能會在更新後消失的問題。  此更新可改善發佈 Office 快速鍵時的可靠性。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-october-08"></a>版本 1908：10 月 8 日
*版本 1908 (組建 11929.20388)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="excel"></a>Excel

- 已解決會導致將超連結貼到一些受保護工作表中的問題。

- 已修正當在增益集管理員中瀏覽時，顯示 16 個以上的增益集的問題。

- 已修正在 Excel 構想功能中，在 Win32 用戶端中按一下 [構想] 按鈕來載入增益集時會發生錯誤的問題。

### <a name="outlook"></a>Outlook

- 已解決導致部分安全連結無法顯示簡單動態顯示 URL 的問題。

- 已更新 Outlook 中的附件封鎖邏輯，以同時封鎖 python 附件。

- 已解決導致使用者在 Outlook 處理序中看到記憶體洩漏的問題。

### <a name="powerpoint"></a>PowerPoint

- 已修正在 PowerPoint 共同撰寫和離線編輯的工作階段中可能會導致資料遺失的問題。

### <a name="office-suite"></a>Office 套件

- 已修正使用者在開啟檔案時可能會遇到的當機問題。

- 已修正 Backstage 的 [資訊位置] 平板未顯示協助工具資訊的問題。

- 已改善透過恢復之前可能已中斷的下載，下載 Office 更新時的可靠性。

- 為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-september-10"></a>版本 1908：9 月 10 日
*版本 1908 (組建 11929.20300)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **使用更大的空間來縮放：** 加大 [縮放] 方塊、變更字型、記憶縮放。[深入了解](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

- **將索引標籤保留在資料庫物件上：** 能清楚看到使用中的索引標籤、輕鬆拖曳索引標籤來重新排列，只要按一下就能關閉資料庫物件。

- **順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。 在帳戶間切換就是這麼簡單。 [深入了解](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a>Excel

- **更深入地探索您的資料：** 新的 [構想] 按鈕可尋找資料的模式，並使用模式建立更有智慧且個人化的建議。[深入了解](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **快速找到該檔案：** 想要尋找最近使用過的檔案嗎？ 只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。

- **增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？ 讓協助工具檢查程式來幫助您，您不需要自行處理。 按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。

- **順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。 在帳戶間切換就是這麼簡單。 [深入了解](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **觀看工作表生動地呈現：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在工作表內橫衝直撞。 [深入了解](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- **共同作業變得更容易：** 共同撰寫的增強功能代表的是使用條件式格式設定、儲存格樣式等等時，您的變更會與共同作業者的變更順暢地合併。

- **聯結類似欄位上的表格：** 在比較合併表格的欄位時，取得及轉換 (Power Query) 現在具有近似文字比對邏輯 (也稱為模糊比對)。 [深入了解](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- **使用 Power Query 的增強功能快速撰寫程式碼：** 使用自動完成和語法色彩快速完成程式碼。 同時輕鬆探索函數、資料行和參數。

- **搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。 而當您選取時，[插入] 按鈕會告知您已經選取的數量。 [深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a>Outlook

- **在移動郵件時繼續作業：** Outlook 現在會在背景中移動郵件，因此，在資料夾之間移動大量郵件時您可以繼續作業。

- **在連續會議之間置入時間：** 將會議預設為提早 5-10 分鐘結束，讓出席者有時間休息，或在前往下一個地點。

- **他們會看到您的 meme：** 如果使用文字或靜態影像還不足以清楚表達您的想法，您可以使用動畫 GIF。[深入了解](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)

- **我們已為您更新 Outlook 使用者體驗：** 先前利用「即將推出」提供預覽的簡化體驗，專門設計來幫助您專注於最重要的事物上。 [深入了解](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **想要寬鬆或緊密的版面配置？您可自由選擇：** 若您想讓項目之間能有更多空間，可以採用「緊密間距」；或者，您也可以採用緊密的版面配置，以便查看更多項目。

- **簡化且也能自訂的功能區：** 輕鬆使用簡化、以單一列方式陳列的常用按鈕。 輕鬆在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。 [深入了解](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **更快速新增帳戶的方式：** 由於帳戶設定已改善，您現在可以更輕鬆地將使用雙因素驗證的 Outlook.com 和 Gmail 帳戶新增到 Outlook。 [深入了解](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- **挑選您的最愛動作：** 不使用 [標幟] 和 [刪除] 嗎？ 那麼 [封存] 或 [標示為已讀取] 呢？ 自訂快速動作功能表，加上您最常使用的命令。

- **不再受限於同步處理限制：** Outlook 的增強功能指出資料夾限制已不存在，因此您可以開始將您的共用信箱同步處理。

- **搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。 而當您選取時，[插入] 按鈕會告知您已經選取的數量。 [深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a>PowerPoint

- **透過測驗或問卷詢問聽眾：** 在投影片上進行測驗或問卷。Office 會收集並儲存存儲您的回應。[深入了解](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **快速找到該檔案：** 想要尋找最近使用過的檔案嗎？ 只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。

- **增加您內容的覆蓋面：** 想要讓您的簡報更易於使用嗎？ 讓協助工具檢查程式來幫助您，您不需要自行處理。 按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。

- **隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。

- **輕鬆插入內嵌影片：** 想要在您的投影片中放入 Vimeo 或 YouTube 影片嗎？只要有影片頁面連結即可。[深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **較佳變形效果：** 命名您的圖形以便加強掌控其轉化方式。 [深入了解](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。 在帳戶間切換就是這麼簡單。 [深入了解](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **線上影片有新的首頁：** 將影片儲存至 Microsoft Stream，讓組織中的任何人都看得到。 插入影片連結，享受檔案大小只有原來一小部分的多媒體簡報。 [深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。 而當您選取時，[插入] 按鈕會告知您已經選取的數量。 [深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a>Project

- **順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。 在帳戶間切換就是這麼簡單。 [深入了解](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a>Visio

- **告別錯誤的 Excel 連結：** 找不到與 Data Visualizer 圖表連結的 Excel 活頁簿嗎？重新連結，就可繼續使用了。[深入了解](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **內建的 Azure 樣板：** 使用數十種 Azure 樣板來設計雲端應用程式或規劃架構。[深入了解](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- **資料流程圖上的 Double-Take：** 資料視覺化工具流程圖美觀的新版面配置，既清新、簡潔且更易於了解。 按一下 [設計] 索引標籤來取得選項。

- **順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。 在帳戶間切換就是這麼簡單。 [深入了解](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **將進度圖表匯出到 Word：** 在 Word 文件中自動新增圖表內容，如圖案和中繼資料。 然後，自訂文件來建立程序指導方針和操作手冊。 [深入了解](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- **從 Power BI 匯出 Visio 視覺效果：** 當匯出 Power BI 報表為 PDF 或 PowerPoint 等檔案時，Power BI Visio 視覺效果會正常顯示。 [深入了解](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a>Word

- **編輯當然是使用筆跡編輯：** 使用畫筆透過單一筆劃來分割或加入文字、新增新的一行，或插入文字。[深入了解](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **為靜態文件注入動人的生命力：** 將文件轉變為在任何裝置上，均具有完美外觀的可互動、易分享的網頁。[深入了解](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **使用 \@提及功能取得他人注意：** 在註解中使用 @提及功能，讓其他人知道您需要他們提供建議。 [深入了解](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **運用行聚焦，提高理解力：** 毫不費力地逐行瀏覽文件。調整焦點，在檢視畫面中一次放入一行、三行或五行。[深入了解](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **快速找到該檔案：** 想要尋找最近使用過的檔案嗎？ 只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。

- **隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。

- **增加您內容的覆蓋面：** 想要讓您的文件更易於使用嗎？ 讓協助工具檢查程式來幫助您，您不需要自行處理。 按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。

- **[學習工具] 模式額外支援更多頁面色彩：** Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。 許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 和 Mac 的 Word 中增加了色彩選項。

- **順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。 在帳戶間切換就是這麼簡單。 [深入了解](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)


- **搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。 而當您選取時，[插入] 按鈕會告知您已經選取的數量。 [深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a>Office 套件

- **安裝 Microsoft Teams：** 我們已將 Teams 新增至 Office 365 專業增強版的現有安裝。 [深入了解](/deployoffice/teams-install)

- **隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。

- **隱私權控制：** 用於診斷資料和連線體驗的新增、更新及改良的控制項。 [深入了解](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

- **Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。

- **安裝 Microsoft Teams：** 在 Office 365 專業增強版的現有安裝中，預設會安裝 Microsoft Teams。 [深入了解](/DeployOffice/teams-install)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="excel"></a>Excel

- 修正在 Excel 中指派給圖形或表單控制項的巨集可能顯示不正確的錯誤訊息，或者可能會處理不正確目標範圍的問題。

- 修正在與其他使用者共同撰寫的工作階段中變更樞紐分析表排序的方式，然後重新整理它可能導致失敗的問題。

- 已解決當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理的問題。

- 修正 Excel 中合併衝突的問題，此問題會造成提示使用者重新開啟活頁簿以取得變更。

- 修正會導致表格旁的剪下並貼上作業在與其他人共同撰寫時失敗的問題。

### <a name="outlook"></a>Outlook

- 修正使用者將信箱從基本驗證升級為新式驗證後，造成將錯誤的帳戶與其 Outlook 設定檔相關聯的問題。

- 修正會導致部分 POP3 使用者看到所有電子郵件皆為純文字格式 (無論設定為何) 的問題。 此修正將會還原 HTML 格式郵件的檢視。

- 修正會導致使用者無法透過螢幕助讀程式存取位置建議的問題。

- 修正嘗試擷取使用者的 Outlook 雲端設定時，導致一些使用者遇到驗證錯誤的問題。

- 修正會導致經理對於代理人是否已經回覆特定會議邀請含混不清的問題。

- 修正會導致 Outlook 使用者在特定案例中停滯在「需要密碼」狀態的問題。

- 修正會導致目前的資料夾搜尋間歇性失敗的問題。

- 修正以下問題：使用者看到該會議的會議室可用時間之外的會議室建議。

- 修正導致使用者看到「找不到此檔案」錯誤的暫時服務問題。 使用雲端附件時，請確認路徑和檔案名稱正確。 [深入了解](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- 修正會導致使用者看到從 Outlook 上傳至 OneDrive 或 SharePoint 檔案其檔案名稱已變更，其中的數個字元由底線取代的問題。

- 修正非英文使用者的郵件中，主旨列會相當小的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正某些增益集會在圖表的圖形周圍擲出未預期錯誤的問題。

- 修正還原 PowerPoint 影片控制項的協助工具名稱的問題。

- 修正部分動畫無法開始的問題

### <a name="project"></a>Project

- 修正讓 Windows 7 上的使用者能夠從 Project Web App 和 SharePoint 網站開啟專案的問題。


### <a name="visio"></a>Visio

- 有多個圖形無法從 Visio 匯出至 SVG。

### <a name="word"></a>Word

- 修正在 Word 文件上與其他人共同作業時，使用者會遇到錯誤訊息的問題。

- 修正嘗試共用儲存在 SharePoint 2016 上的檔案時，導致使用者遇到「很抱歉，發生問題，無法共用」訊息的問題。


### <a name="office-suite"></a>Office 套件

- 修正在某些情況下，同步處理引擎備份的 SharePoint 檔案可能會顯示「已儲存」但實際上未儲存任何變更的問題。

- 修正大型樹狀檢視失敗的問題。

- 修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-august-13"></a>版本 1902：8 月 13 日
*版本 1902 (組建 11328.20392)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
- 修正清除篩選圖示同時對表格中已篩選和未篩選交叉分析篩選器顯示的問題。

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
- 修正使用者將信箱從基本驗證升級為新式驗證後，造成關聯的帳戶錯誤的問題

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
- 修正與其他使用者就文件共同作業時，應用程式可能會意外終止的問題。

### <a name="word-non-security-updates"></a>Word：非安全性更新
- 修正 VBA 更新欄位很緩慢的問題。
- 修正開啟部分 DOC 檔案時，出現提示說明檔案已損毀的問題。
- 修正與其他使用者就文件共同作業時，應用程式可能會意外終止的問題。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
- 修正設定 API 在某些案例下無法在 Office JavaScript 程式庫運作的問題 [深入了解](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)

## <a name="version-1902-july-09"></a>版本 1902：7 月 9 日
*版本 1902 (組建 11328.20368)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


### <a name="excel-non-security-updates"></a>Excel：非安全性更新
- 修正刪除篩選過的 Excel 資料列非常緩慢的問題。
- 修正以兩根手指捲動會導致灰色矩形繪製超出工作表範圍，並且讓 Excel 當機的問題。


### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
- 解決導致使用者有時會看見 Outlook 插入英文拼音字母，而不是讓輸入法候選視窗保持開啟以選取中文字的問題。
- 解決導致使用者看到針對排程的會議建議的會議室卻沒有可預約時間的問題。
- 解決導致使用者嘗試開啟會議系列的例外狀況卻開啟主要系列的問題。
- 解決導致使用者在 [刪除的郵件] 資料夾中看到郵件到期日期計算錯誤的問題。


### <a name="teams-non-security-updates"></a>Teams：非安全性更新

- Teams 安裝程式在安裝完成後，現在有 [原則] 可關閉自動啟動。


### <a name="visio-non-security-updates"></a>Visio：非安全性更新

- 解決適用於 Visio 的 ActiveX 解決方案無法搭配 Office 365 運作的相關問題，會以一個說明找不到 riched20.dll 的錯誤訊息表示。


### <a name="word--non-security-updates"></a>Word：非安全性更新

- 修正停用範本搜尋列的 GPO 設定
- 修正使用者在離線後又編輯僅限伺服器才有的文件而可能遺失某些變更的問題。
- 改善啟用 [文件的快速組件] 摘要資訊時的效能
- 修正從伺服器第一次下載修訂可能會失敗的問題


### <a name="office-suite--non-security-updates"></a>Office 套件：非安全性更新

- 解決安裝其他 Office 產品或語言套件後，使用共用電腦啟用的裝置可能會意外還原為使用者啟用的問題。
- 修正以 SYSTEM 身分執行 proxy 驗證時會封鎖 Office 更新的問題。
- 修正以解決使用者設定檔變更後，Office 增益集消失的問題。


## <a name="version-1902-june-11"></a>版本 1902：6 月 11 日
*版本 1902 (組建 11328.20318)*
<br/>安全性更新列於[此處](./microsoft365-apps-security-updates.md)

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
 - 已解決將包含 XML 對應的檔案儲存為 PDF 時導致當機的問題。
 - 已解決在載入包含無效工作表名稱之活頁簿時，導致外部連結遭到刪除的問題。
 - 已修正在 Excel 中使用相機工具可能會造成試算表當機的問題。
 - 已解決當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理的問題。
 - 已解決以下問題：在工作表計算期間使用依賴表格之另一個工作表上的陣列公式重新計算資料表格時，發生當機。 
 - 已解決以下問題：未先簽出檔案，無法從 SharePoint 開啟受密碼保護的活頁簿。
 - 已進行變更，確保在共用或切換自動儲存時，處理 BeforeSave 事件。

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
 - 已解決在「群組依據」中新增第二個條件後，客戶的工作似乎會消息的問題。

### <a name="word-non-security-updates"></a>Word：非安全性更新
 - 已修正以下問題：共用目前正在共同作業的文件時，會產生具 .asd 副檔名的附件。
 - 已修正註解被歸因於隨機作者的問題。
 - 已修正在簽出文件時，簽章遭到移除的問題。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
 - 此修正在「復原」動作後，VBA 的錯誤形狀填入狀態錯誤。


## <a name="version-1902-may-14"></a>版本 1902：5 月 14 日
*版本 1902 (組建 11328.20286)*

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
 -  已修正在 Excel 中使用相機工具可能會造成試算表當機的問題。
 - 已修正在帶有圖表工作表的非使用中視窗中使用滑鼠滾輪時導致當機的問題。
 - 將試算表匯入 SharePoint 時發生「未預期錯誤」訊息的問題已解決。
 - 在開啟包含使用其規則名稱和自訂檢視的條件式格式設定的活頁簿時導致 Excel 當機的問題已解決。
 - 巨集用於驗證資料的公式若長於 255 個字元可能會產生執行階段錯誤。此問題現已修正。
 - 發生問題，導致包含連結至其他活頁簿之樞紐分析表的檔案載入速度緩慢。已修正此問題。
 - 開啟 HTML 檔案時收到「檔案格式與副檔名不符」錯誤的問題已解決。
 - 已進行變更，以解決在非使用中視窗滾動滑鼠滾輪的問題。  

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
 - 解決了造成客戶無法編輯所移轉項目上某些欄位的問題。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
- 已修正在罕見的情況下，PowerPoint 停止將使用者的變更上傳到雲端的問題。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
 - 已修正 Lync (商務用 Skype) 中的問題，在其中，當任何線上會議具有 7 位以上參與者時，會議視窗可能會消失。
 - 使用用來登入其他 Office 應用程式的認證來登入商務用 Skype。
 - 隨著共用電腦啟用安裝時，正確地啟用商務用 Skype 應用程式。

### <a name="visio-non-security-updates"></a>Visio：非安全性更新
 - 已修正第三方解決方案利用停用動態 DPI 功能來擴充 Visio，造成損毀視窗階層問題的問題。

### <a name="word-non-security-updates"></a>Word：非安全性更新
 - 已修正編輯 SharePoint 新增的相關人員可能會當機的問題。
 - 已修正 Word 啟動時出現的「無法載入資源」對話方塊。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
 - 此修正程式可修正無法將檔案儲存到 Apache WebDAV 資料夾的問題。
 - 修正 Office 在客戶開啟某些雲端儲存檔案時會意外關閉的問題。
 - 修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。
 - 已修正似乎為 Windows 10 上的許多使用者清除最近使用的檔案清單的問題。
 - 已修正即使已有系統管理員觸發的更新進行中，仍導致使用者看到 Office 更新業務列的問題。
 - 已修正與間歇性的空白登入提示相關的問題。
 

## <a name="version-1902-april-9"></a>版本 1902：4 月 9 日
*版本 1902 (組建 11328.20230)*

### <a name="excel-non-security-updates"></a>Excel：非安全性更新

- 解決了當儲存格中包含的公式結尾為定義的名稱時，按下 Tab 鍵不會移至下一個儲存格的問題。
- 解決了儲存格格式設定導致檔案大小不必要地增加的問題。
- 解決了在活頁簿之間剪下並貼上樞紐分析表可能導致貼上資料，但沒有您正與其共同作業的其他人的樞紐分析表的問題。

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新

- 已修正當系統工作列停留在螢幕左側或頂部時，視窗無法顯示在正確位置的問題。
- 解決了在連絡人卡片上載入圖片時導致客戶遇到當機的問題。
- 解決了導致某些客戶在啟動 Office 應用程式時遇到當機的問題。
- 已修正當系統工作列停留在螢幕左側或頂部時，視窗無法顯示在正確位置的問題。
- 解決造成客戶無法編輯所移轉項目上某些欄位的問題。

### <a name="visio-non-security-updates"></a>Visio：非安全性更新

- 已修正第三方解決方案利用停用動態 DPI 功能來擴充 Visio，造成損毀視窗階層問題的問題。

### <a name="word-non-security-updates"></a>Word：非安全性更新

- 如果檔案以唯讀模式開啟，然後您從 [資訊] 窗格中按一下 [另存新檔]，修正問題以便顯示儲存 UI。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新

- 已修正部分 Office 更新未使用傳遞最佳化對等快取的問題。 [深入了解](/windows/deployment/update/waas-delivery-optimization)
- 修正如果使用 Office 部署工具安裝 Office，並發生大小寫不相符時，可能導致移除產品或未啟用的錯誤。
- 已修正導致 Windows 10 (版本 1803 或更高版本) 裝置上出現過多登入提示的問題。
- 已修正下載連結圖片時，造成懸置的迴歸。
- 已修正在 Word、Excel、PowerPoint 貼上大型 EMF 檔案的模糊問題。
- 已修正版本歷程記錄剖析邏輯時，在少數情況下導致文件以唯讀模式開啟的錯誤 (bug)。

## <a name="version-1902-march-12"></a>版本 1902：3 月 12 日
*版本 1902 (組建 11328.20158)*

### <a name="access-feature-updates"></a>Access：功能更新

- **重新整理、重新連結或移除連結的資料表：** 更新的連結資料表管理員是用於管理所有資料來源與連結資料表的位置。[深入了解](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- **繪製成黑色、繪製成灰色：** 依照您的喜好變更 Access 的外觀。有四個佈景主題可供選擇：彩色、深灰色、黑色或白色。[深入了解](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)
- **Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。

### <a name="excel-feature-updates"></a>Excel：功能更新

- **更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。 按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。
- **使用註解共同作業：** 使用內建的回覆方塊，在試算表中進行交談。[深入了解](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **功能區圖示有了嶄新的外觀：** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **呼叫所有取得與轉換粉絲：** 如果您經常使用取得與轉換，您會很高興知道我們已改善資料行來源範例功能。此外，也已改善許多連接器。[深入了解](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **改善了對高解析度顯示器的支援：** 現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。[深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **快速查閱** 我們已加速 VLOOKUP、HLOOKUP、MATCH 的計算速度，讓您能更快得到答案。[深入了解](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a>Outlook：功能更新

- **使用「大聲朗讀」聆聽您的電子郵件：** Outlook 可以大聲朗讀您的電子郵件，強調所朗讀的文字。若要開啟 [大聲朗讀]，請移至 [輕鬆存取] 設定。[深入了解](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **免用手輸入：** 您有麥克風嗎？ 按一下 [聽寫] 並看看 Outlook 如何在您說話的同時輸入您說話的內容。 [深入了解](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **功能區圖示有了嶄新的外觀：** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **依預設在 SMIME 加密和簽章電子郵件中封鎖下載外部內容：** 由於 SMIME 通訊協定中存在漏洞，Outlook 會封鎖從已由 SMIME 加密或簽章的郵件上下載外部內容。使用者無法利用按一下來透過 Outlook UI 下載外部內容，以防止安全漏洞。使用者可使用「選項」對話方塊中的新選項，來還原之前的行為。
- **關閉會議的轉寄：** 防止出席者將您的會議轉寄給其他人。只需移至功能區，按一下 [回應選項] 即可。[深入了解](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- **排程助理員中的人員建議：** 在您排定會議時查看對要新增之出席者的建議。不再來回切換排程助理員與收件者。[深入了解](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **預留房間更加輕鬆：** 使用多個會議室清單尋找會議室 - 以及切換清單，而不會失去您已選取的會議室。
- **循環範圍的新預設值：** 在 [週期設定] 對話方塊中，循環範圍之前的預設值為 [沒有結束日期]。雖然這有助於建立長時間執行的週期性系列，但在一段時間之後可能會發生損壞。我們正將 [週期設定] 對話方塊的預設值更新為 [結束於]，這樣我們的預設值就會符合行事曆操作的建議最佳做法。
- **從 Outlook 提醒對話方塊加入小組會議：** 當 Outlook 提醒使用者有即將來臨的會議時，如果即將來臨的會議是小組線上會議，則它會顯示 [線上加入] 按鈕。這個動作與從 Outlook [提醒] 對話方塊加入商務用 Skype 會議的體驗類似。
- **停止看到過去事件的提醒：** 您可以設定行事曆，在事件結束之後自動關閉事件的提醒。[深入了解](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **查看安全連結背後的 URL：** 安全連結可保護您防範在電子郵件中收到但隱藏原始 URL 的惡意 URL。 若要查看原始 URL，請將滑鼠游標移到 URL 上。 需要進階威脅防護授權。 [深入了解](https://products.office.com/exchange/advance-threat-protection)
- **縮放與搖桿：** 選擇要用於所有郵件的預設值，而不用在每次讀取郵件時調整 [縮放]。[深入了解](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **郵件加密：僅加密 IRM 原則：**[選項] > [權限] 功能表上的全新僅加密選項，供 Office 365 郵件加密使用者使用。 這個選項可讓您加密郵件，並將郵件傳送給組織內外的任何人。
- **當您被列於密件副本時，顯示提醒：** 當您不小心回覆所有人，而將自己列於密件副本時，密件副本資訊提示會顯示提醒。
- **更智慧的 [收件者:] 行：** 當您按一下 [收件者:] 行來撰寫郵件時，我們會建議您可能要選擇的收件者。 此外，還可以看到收件者的相片，讓您知道要傳送的對象是正確的。 [深入了解](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- **能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **改善了對高解析度顯示器的支援：** 現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。[深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新

- **更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。 按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。
- **免用手輸入：** 您有麥克風嗎？ 按一下 [聽寫] 並看看 PowerPoint 如何在您說話的同時輸入您說話的內容。 [深入了解](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **功能區圖示有了嶄新的外觀：** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **改善了對高解析度顯示器的支援：** 現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。[深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **色彩生動的超連結：** 超連結不再只是藍色的。 您可以套用您喜歡的任何字型色彩。 [深入了解](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **生動地觀看您的投影片：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在整個畫面橫衝直撞。[深入了解](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **您素描，我修飾：** 我們可將手繪文字和形狀變為更精緻的圖表。只需選取您的筆跡線條即可開始。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **發佈到 Microsoft Stream：** 透過使用 Microsoft Stream，在組織內更安全地以影片形式共用簡報。 [深入了解](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **匯出為 4K 影片：** 您現在可以在將簡報匯出為影片時選取 4K 解析度。  [深入了解](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **大型檔案現在會以更快速度開啟：** 現在開啟儲存在 OneDrive 或 SharePoint 上的檔案時，會在背景下載影像、影片及其他大型元素。

### <a name="word-feature-updates"></a>Word：功能更新

- **更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。 按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。
- **免用手輸入：** 您有麥克風嗎？ 按一下 [聽寫] 並看看 Word 如何在您說話的同時輸入您說話的內容。 [深入了解](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **生動地觀看您的文件：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在整個頁面橫衝直撞。[深入了解](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **功能區圖示有了嶄新的外觀：** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **改善了對高解析度顯示器的支援：** 現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。[深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **利用 LinkedIn 的協助撰寫最佳簡歷或履歷表：** 利用簡歷小幫手，查看特定角色的工作經驗、建議的技能以及其他資訊。 [深入了解](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)

### <a name="project-feature-updates"></a>Project：功能更新

- **在工作面板卡片上查看詳細資訊：** 當單獨標題不能訴說故事時，請自訂您的工作面板卡片，以顯示所有最重要的詳細資料。[深入了解](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- **Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。

### <a name="publisher-feature-updates"></a>Publisher：功能更新

- **Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。

### <a name="visio-feature-updates"></a>Visio：功能更新

- **在下一個圖表中享受圖示時刻：** 有 26 個全新的圖示樣板供您挑選，其中包含分析、藝術、慶典、臉部、運動和其他圖示。
- **Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。

### <a name="office-suite-feature-updates"></a>Office 套件：功能更新

- **Office 第三方應用程式現在已使用 office.js api 擁有插入 SVG 支援的功能：** 亦稱為 Office 增益集的第三方應用程式現在擁有插入 SVG 的功能。使用者現在可以將個人的 SVG 集合連線至 Office。開發人員現在可以使用 Office.js API 來使用這項功能。
- **安裝 Microsoft Teams：** 在 Office 365 專業增強版的現有安裝中，預設會安裝 Microsoft Teams。 [深入了解](/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a>商務用 Skype：功能更新

- **改善了對高解析度顯示器的支援：** 現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。[深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a>Teams：功能更新

- **改善了對高解析度顯示器的支援：** 現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。[深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

## <a name="version-1808-february-12"></a>版本 1808：2 月 12 日
*版本 1808 (組建 10730.20280)* 

### <a name="access-non-security-updates"></a>Access：非安全性更新 

- 這個更新將新日本時代的支援新增至 Access。

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新 

- 解決嘗試管理規則時，因參照不再存在資料夾的規則而導致使用者看見錯誤訊息或看見用戶端規則無法執行的問題。
- 解決因快取的委派信箱導致使用者在無法預測的時間間隔遇到頻繁的當機問題。
- 解決因為會議結束時間設定為隔天午夜而導致全天會議在某些檢視中比原訂多橫跨一天的問題。
- 修正參考日本時代建立新約會或會議時發生的當機問題。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新

- 修正使用 [O365 Office 集中式部署](/office/dev/add-ins/publish/centralized-deployment)部署的增益集發生凍結且無法使用的問題。


## <a name="version-1808-january-8"></a>版本 1808：1 月 8 日
版本 1808 (組建 10730.20264) 

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新 

- 修正導致使用者遇到行事曆同步處理錯誤的問題。

### <a name="word-non-security-updates"></a>Word：非安全性更新

- 改善開啟效能。

## <a name="version-1808-december-11"></a>版本 1808：12 月 11 日
*版本 1808 (組建 10730.20262)*

### <a name="excel-security-updates"></a>Excel：安全性更新 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8597)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8598)：Microsoft Excel 資訊洩漏弱點 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8627)：Microsoft Excel 資訊洩漏弱點 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8636)：Microsoft Excel 遠端程式碼執行弱點 

### <a name="outlook-security-updates"></a>Outlook：安全性更新 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8587)：Microsoft Outlook 遠端程式碼執行弱點 

### <a name="powerpoint-security-updates"></a>PowerPoint：安全性更新 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8628)：Microsoft PowerPoint 遠端程式碼執行弱點 

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

-   [CVE-2018-8574](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8574)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8577](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8577)：Microsoft Excel 遠端程式碼執行弱點 

### <a name="outlook-security-updates"></a>Outlook：安全性更新 

-   [CVE-2018-8522](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8522)：Microsoft Outlook 遠端程式碼執行弱點 
-   [CVE-2018-8524](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8524)：Microsoft Outlook 遠端程式碼執行弱點 
-   [CVE-2018-8558](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8558)：Microsoft Outlook 資訊洩漏弱點 
-   [CVE-2018-8576](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8576)：Microsoft Outlook 遠端程式碼執行弱點 
-   [CVE-2018-8579](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8579)：Microsoft Outlook 資訊洩漏弱點 
-   [CVE-2018-8582](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8582)：Microsoft Outlook 遠端程式碼執行弱點 

### <a name="project-security-updates"></a>Project：安全性更新 

-   [CVE-2018-8575](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8575)：Microsoft Project 遠端程式碼執行弱點 

### <a name="word-security-updates"></a>Word：安全性更新 

-   [CVE-2018-8573](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8573)：Microsoft Word 遠端程式碼執行弱點 

### <a name="skype-for-business-security-updates"></a>商務用 Skype：安全性更新 

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8546)：Microsoft 商務用 Skype 阻絕服務弱點 

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
-   [CVE-2018-8502](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8502)：Microsoft Excel 遠端程式碼執行弱點 

### <a name="outlook-security-updates"></a>Outlook：安全性更新 
-   [ADV180026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180026)：Microsoft Office 深度防禦更新 

### <a name="powerpoint-security-updates"></a>PowerPoint：安全性更新 
-   [CVE-2018-8501](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8501)：Microsoft PowerPoint 遠端程式碼執行弱點

### <a name="word-security-updates"></a>Word：安全性更新 
-   [CVE-2018-8504](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8504)：Microsoft Word 遠端程式碼執行弱點 
-   [ADV180026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180026)：Microsoft Office 深度防禦更新 

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新 
-   [CVE-2018-8432](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8432)：Microsoft Graphics 元件遠端程式碼執行弱點 

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
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點

### <a name="excel-feature-updates"></a>Excel：功能更新
 - **共同作業編輯：** 在您的活頁簿中與他人同時作業。[深入了解](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **現在已預設啟用 AutoSave 雲端檔案：** AutoSave 在 2018 年 9 月的半年通道 (已設定目標) 版本中已預設為啟用。這項改變代表使用者再也無須擔心儲存在 OneDrive 或 SharePoint Online 上的文件變更會遺失。變更將會自動儲存在雲端，使用者再也不需要按下 Ctrl + S 鍵或 [儲存] 按鈕。但使用者必須了解這項動作改變，以防意外變更文件。使用者可以用畫面頂端的 AutoSave 切換開關停用 AutoSave。建議您通知使用者這項近期改變，並提供有關這項 Office 365 全新功能的使用教學。[深入了解 AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [深入了解 IT 系統管理員須知的 AutoSave 相關內容](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **改善儲存格和資料編輯列編輯：** 您現在可以使用 CTRL + A 來選取儲存格或資料編輯列中的文字。另外也改善了 Emoji 和其他複雜字元的支援。[深入了解](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **改善協助工具檢查程式︰** 協助工具檢查程式已更新對國際標準與建議的支援，以使您的活頁簿更易於存取。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **避免不想要的編輯：** 設定您的活頁簿開啟為唯讀，以避免意外變更。移至 [檔案 > 資訊 > 保護活頁簿 > 一律以唯讀開啟]

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8331)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8429)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 遠端程式碼執行弱點

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
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 竄改弱點
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 提高權限弱點
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全性功能略過的弱點
-   [ADV180021](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180021)：Microsoft Office 深度防禦更新

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
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8430)：Windows PDF 遠端程式碼執行弱點
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 資訊洩漏弱點

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正造成顯示記憶體不足訊息的問題。
-   修正了防止部分使用者開啟受 IRM 保護的文件和電子郵件 (由其他組織中的人員與他們共用) 的一些問題。
-   修正一些效能問題。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8332)：Win32k 圖形遠端程式碼執行弱點
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 遠端程式碼執行弱點
-   
  **基於安全原因已封鎖 Flash、Silverlight、Shockwave 控制在 Office 中啟動：** 基於安全原因，Windows 上新組建的 Microsoft Office for Office 365 會封鎖 Flash、Silverlight、Shockwave 控制的啟動。請看[這裡](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)和[這裡](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US)深入了解。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-  已修正導致更新安裝在特定情況下需要很長時間的問題。
-  修正此問題：開啟應用程式時，使用者可能會看到以安全模式啟動的訊息，然後應用程式無法開啟。
-  修正一些效能問題。

## <a name="version-1803-august-14"></a>版本 1803：8 月 14 日
*版本 1803 (組建 9126.2275)*

### <a name="access-security-updates"></a>Access：安全性更新
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 資訊洩漏弱點 

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [ADV180021](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180021)：Microsoft Office 深度防禦更新 

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 資訊洩漏弱點 

## <a name="version-1803-july-10"></a>版本 1803：7 月 10 日
*版本 1803 (組建 9126.2259)*

### <a name="access-security-updates"></a>Access：安全性更新
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 竄改弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 遠端程式碼執行弱點

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
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 遠端程式碼執行弱點

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正 Excel 樞紐分析表中的群組 (或取消群組) 作業有時候會觸發當機的問題。

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 提高權限弱點

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
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 資訊洩漏弱點

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：Excel 在從 SharePoint Online 開啟檔案時損毀。
-   修正此問題，列印或預覽列印時，只列印或顯示了工作表中的一部分，內容被截斷為工作表上的交叉分析篩選器。

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全性功能略過的弱點

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
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 遠端程式碼執行弱點



## <a name="version-1803-april-10"></a>版本 1803：4 月 10 日
*版本 1803 (組建 9126.2152)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 遠端程式碼執行弱點

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：多個使用者在相同簡報上共同撰寫會導致投影片母片不正確重複。
-   修正此問題：將儲存在 OneDrive 中的檔案開啟時，結束受保護的檢視時會導致 PowerPoint 當機。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正與 TLS 1.2 支援相關的問題。

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正造成顯示記憶體不足訊息的問題。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 遠端程式碼執行弱點



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
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 遠端程式碼執行弱點

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
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11877)：Microsoft Excel 安全性功能略過的弱點
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11878)：Microsoft Excel 記憶體損毀弱點
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11884)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全性功能略過
-   [Advisory 170021](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新

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
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11939)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 提高權限弱點
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 記憶體損毀弱點

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
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11934)：Microsoft PowerPoint 資訊洩漏弱點

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
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 記憶體損毀弱點
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 資訊洩漏弱點
-   [Advisory 170020](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV170020)：Microsoft Office 深度防禦更新

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：當使用者嘗試對商務用 OneDrive 上的現有文件執行 [另存新檔] 時，Word 會當機，並取消儲存作業或嘗試合併現有變更。
-   修正此問題：執行合併列印精靈時，篩選包含 null (空白) 值的資料來源欄位失敗。
-   修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。
-   修正此問題：要移除文件中的 IRM 保護時並沒有移除保護。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11882)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 資訊洩漏弱點
-   [Advisory 180003](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180003)：Microsoft Office 深度防禦更新

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
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 遠端程式碼執行弱點

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 提高權限弱點
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 記憶體損毀弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 資訊洩漏弱點



## <a name="version-1708-january-9"></a>版本 1708：1 月 9 日
*版本 1708 (組建 8431.2153)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 遠端程式碼執行弱點
-   [Advisory 170021](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：以程式設計方式建立樞紐分析表，接著以程式設計方式重新整理，會造成 Excel 當機。

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點

### <a name="word-security-updates"></a>Word：安全性更新
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 記憶體損毀弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 遠端程式碼執行弱點
-   [Advisory 180003](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180003)：Microsoft Office 深度防禦更新

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   為 Office 365 德國方案的網域使用者新增單一登入 (SSO) 的支援，該方案的身分識別與內部部署的 Active Directory 同盟。
-   新增功能以避免未成年人獲取和啟動來自 Office 市集的 Office 增益集。


> [!NOTE]
> 如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[技術支援](https://support.microsoft.com/contactus)。
