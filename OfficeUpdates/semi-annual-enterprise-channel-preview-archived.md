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
ms.openlocfilehash: 5d4d10b03d82788b4d3b561d0664b48d680dfc39
ms.sourcegitcommit: 96185aa6c5a06095c58b57ac36cb2800add8bea0
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/06/2021
ms.locfileid: "49760713"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel-preview"></a>半年企業通道 (預覽版) 封存發行記錄

這些版本資訊可提供 Office 365 專業增強版、Visio Pro for Office 365、Project Online 電腦版用戶端以及 Office 365 商務版的半年企業通道 (預覽版) 更新所含新功能和非安全性更新的相關資訊。

> [!NOTE]
> - 我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至半年企業通道 (預覽版)。 如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。 [深入了解](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - 從版本 1902 開始，Microsoft Teams 會包含在半年企業通道(預覽版) 的全新安裝中。 將 Teams 更新至版本 1908 或更新版本時，即會將 Teams 新增至半年企業通道 (預覽) 的現有安裝中。 如需詳細資訊，請參閱[使用 Office 365 專業增強版部署 Microsoft Teams](https://docs.microsoft.com/DeployOffice/teams-install)。

## <a name="version-1908-december-10"></a>版本 1908：12 月 10 日
*版本 1908 (組建 11929.20516)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

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

- 進行一項變更，可讓系統管理員啟用一個原則，以在自動探索驗證提示中較 UPN 優先使用所提供的帳戶電子郵件。 依預設，自動探索會優先於帳戶 UPN (如果有的話)。

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

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

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
- 已修正應用程式可能在關機時懸置的各種問題。 同時修正特定增益集相關失敗的問題。

### <a name="office-suite"></a>Office 套件

- 已解決第三方外掛程式中與文字方塊/圖案自動調整屬性相關的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="october-15"></a>10 月 15 日

### <a name="non-security-updates"></a>非安全性更新

### <a name="office-suite"></a>Office 套件
- 我們已暫時停用 [雲端儲存] 對話方塊以解決在 2019 年 10 月14 日針對早於 16.0.11929.20396 的組建所發佈的儲存問題。 這項功能即將重新啟用。

## <a name="version-1908-october-14"></a>版本 1908：10 月 14 日
*版本 1908 (組建 11929.20396)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="excel"></a>Excel

- <div>解決「尋找及取代」在找到第一個項目後，對話方塊中的焦點位置變更的問題。</div>

### <a name="office-suite"></a>Office 套件

- 解決使用者使用早於 16.0.11929.20396 的組建時，可能無法儲存 Word、Excel 和 PowerPoint 2019 文件的問題。  此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存新檔] 對話方塊的使用者。

- 解決在某些情況下，Office 快速鍵可能會在更新後消失的問題。  此更新可改善發佈 Office 快速鍵時的可靠性。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-october-08"></a>版本 1908：10 月 8 日
*版本 1908 (組建 11929.20388)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

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

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **使用更大的空間來縮放：** 加大 [縮放] 方塊、變更字型、記憶縮放。 [深入了解](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

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

- **內建的 Azure 樣板：** 使用數十種 Azure 樣板來設計雲端應用程式或規劃架構。 [深入了解](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

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

- **安裝 Microsoft Teams：** 我們已將 Teams 新增至 Office 365 專業增強版的現有安裝。 [深入了解](https://docs.microsoft.com/DeployOffice/teams-install)

- **隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。

- **隱私權控制：** 用於診斷資料和連線體驗的新增、更新及改良的控制項。 [深入了解](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- **Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。

- **安裝 Microsoft Teams：** 在 Office 365 專業增強版的現有安裝中，預設會安裝 Microsoft Teams。 [深入了解](https://docs.microsoft.com/DeployOffice/teams-install)


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

- 已修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-august-13"></a>版本 1902：8 月 13 日
*版本 1902 (組建 11328.20392)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

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

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


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
<br/>安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

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
 - 巨集用於驗證資料的公式若長於 255 個字元可能會產生執行階段錯誤。 此問題現已修正。
 - 發生問題，導致包含連結至其他活頁簿之樞紐分析表的檔案載入速度緩慢。 此問題已解決。
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
 - 已修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。
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

- 已修正部分 Office 更新未使用傳遞最佳化對等快取的問題。 [深入了解](https://docs.microsoft.com/windows/deployment/update/waas-delivery-optimization)
- 修正如果使用 Office 部署工具安裝 Office，並發生大小寫不相符時，可能導致移除產品或未啟用的錯誤。
- 已修正導致 Windows 10 (版本 1803 或更高版本) 裝置上出現過多登入提示的問題。
- 已修正下載連結圖片時，造成懸置的迴歸。
- 已修正在 Word、Excel、PowerPoint 貼上大型 EMF 檔案的模糊問題。
- 已修正版本歷程記錄剖析邏輯時，在少數情況下導致文件以唯讀模式開啟的錯誤 (bug)。

## <a name="version-1902-march-12"></a>版本 1902：3 月 12 日
*版本 1902 (組建 11328.20158)*

### <a name="access-feature-updates"></a>Access：功能更新

- **重新整理、重新連結或移除連結的資料表** 更新的連結資料表管理員是用於管理所有資料來源與連結資料表的位置。 [深入了解](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- **繪製成黑色、繪製成灰色：** 依照您的喜好變更 Access 的外觀。有四個佈景主題可供選擇：彩色、深灰色、黑色或白色。[深入了解](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)
- **Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。

### <a name="excel-feature-updates"></a>Excel：功能更新

- **更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。 按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。
- **使用註解共同作業：** 使用內建的回覆方塊試保持試算表中的交談正確。 [深入了解](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。 此外，它們在各種尺寸的螢幕上看起來很棒。 [深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **呼叫所有「取得與轉換」粉絲：** 如果您經常使用「取得與轉換」，您會很高興知道我們已改善資料行來源範例功能。 此外，也已改善許多連接器。 [深入了解](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。 [深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **快速查閱** 我們已加速 VLOOKUP、HLOOKUP 和 MATCH 的計算速度，讓您能更快得到答案。 [深入了解](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a>Outlook：功能更新

- **使用「大聲朗讀」聆聽您的電子郵件：** Outlook 可以大聲朗讀您的電子郵件，強調所朗讀的文字。若要開啟 [大聲朗讀]，請移至 [輕鬆存取] 設定。[深入了解](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **免用手輸入：** 您有麥克風嗎？ 按一下 [聽寫] 並看看 Outlook 如何在您說話的同時輸入您說話的內容。 [深入了解](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。 此外，它們在各種尺寸的螢幕上看起來很棒。 [深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **在經 SMIME 加密和簽署的電子郵件中，預設封鎖外部內容的下載：** 由於 SMIME 通訊協定中存在漏洞，Outlook 將封鎖在已通過 SMIME 加密或簽署的郵件上下載外部內容。 使用者無法透過 Outlook UI 的按下動作下載外部內容，藉此防止安全性漏洞。 [選項] 對話方塊中有一個新選項，可讓使用者回復為舊行為。
- **關閉會議轉寄功能：** 防止出席者將您的會議轉寄給其他人。 只需移至功能區，按一下 [回應選項] 即可。 [深入了解](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- **排程助理員中的人員建議：** 在您排定會議時查看對要新增之出席者的建議。不再來回切換排程助理員與收件者。[深入了解](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **預留房間更加輕鬆：** 使用多個會議室清單尋找會議室 - 以及切換清單，而不會失去您已選取的會議室。
- **循環範圍的新預設值：** 在 [週期設定] 對話方塊中，循環範圍之前的預設值為 [沒有結束日期]。雖然這有助於建立長時間執行的週期性系列，但在一段時間之後可能會發生損壞。我們正將 [週期設定] 對話方塊的預設值更新為 [結束於]，這樣我們的預設值就會符合行事曆操作的建議最佳做法。
- **從 Outlook 提醒對話方塊加入小組會議：** 當 Outlook 提醒使用者有即將來臨的會議時，如果即將來臨的會議是小組線上會議，則它會顯示 [線上加入] 按鈕。這個動作與從 Outlook [提醒] 對話方塊加入商務用 Skype 會議的體驗類似。
- **停止看到過去事件的提醒：** 您可以設定行事曆，以在事件結束之後自動關閉事件的提醒。 [深入了解](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **查看安全連結背後的 URL：** 安全連結可保護您防範在電子郵件中收到但隱藏原始 URL 的惡意 URL。 若要查看原始 URL，請將滑鼠游標移到 URL 上。 需要進階威脅防護授權。 [深入了解](https://products.office.com/exchange/advance-threat-protection)
- **縮放與搖桿：** 選擇要用於所有郵件的預設值，而不用在每次讀取郵件時調整 [縮放]。 [深入了解](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **郵件加密：僅加密 IRM 原則：**[選項] > [權限] 功能表上的全新僅加密選項，供 Office 365 郵件加密使用者使用。 這個選項可讓您加密郵件，並將郵件傳送給組織內外的任何人。
- **當您被列於密件副本時，顯示提醒：** 當您不小心回覆所有人，而將自己列於密件副本時，密件副本資訊提示會顯示提醒。
- **更智慧的 [收件者:] 行：** 當您按一下 [收件者:] 行來撰寫郵件時，我們會建議您可能要選擇的收件者。 此外，還可以看到收件者的相片，讓您知道要傳送的對象是正確的。 [深入了解](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- **能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。 [深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新

- **更快速地開始**：新設計的 [開始頁面] 會將您最近開啟的文件放在最前面並置中。 按幾下便能取得檔案，並從這裡直接開啟 [帳戶] 設定或 [選項]。
- **免用手輸入：** 您有麥克風嗎？ 按一下 [聽寫] 並看看 PowerPoint 如何在您說話的同時輸入您說話的內容。 [深入了解](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。 此外，它們在各種尺寸的螢幕上看起來很棒。 [深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。 [深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **色彩生動的超連結：** 超連結不再只是藍色的。 您可以套用您喜歡的任何字型色彩。 [深入了解](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **生動地觀看您的投影片：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在整個畫面橫衝直撞。 [深入了解](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
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
- **功能區圖示有了嶄新的外觀：** 別擔心，功能一切如常。 此外，它們在各種尺寸的螢幕上看起來很棒。 [深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。 [深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **利用 LinkedIn 的協助撰寫最佳簡歷或履歷表：** 利用簡歷小幫手，查看特定角色的工作經驗、建議的技能以及其他資訊。 [深入了解](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)

### <a name="project-feature-updates"></a>Project：功能更新

- **在工作面板卡片上查看詳細資訊：** 當標題本身無法陳述完整故事時，請自訂您的工作面板卡片，以顯示所有最重要的詳細資料。 [深入了解](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- **Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。

### <a name="publisher-feature-updates"></a>Publisher：功能更新

- **Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。

### <a name="visio-feature-updates"></a>Visio：功能更新

- **在下一個圖表中享受圖示時刻：** 有 26 個全新的圖示樣板供您挑選，其中包含分析、藝術、慶典、臉部、運動和其他圖示。
- **Office 擁有新的外觀：** Office應用程式現在擁有更簡單、更方便使用的現代化圖示，而功能區也更新了視覺效果，能強調顯示 Office 應用程式中的豐富共同作業功能。

### <a name="office-suite-feature-updates"></a>Office 套件：功能更新

- **Office 第三方應用程式現在已使用 office.js api 擁有插入 SVG 支援的功能：** 亦稱為 Office 增益集的第三方應用程式現在擁有插入 SVG 的功能。使用者現在可以將個人的 SVG 集合連線至 Office。開發人員現在可以使用 Office.js API 來使用這項功能。
- **安裝 Microsoft Teams：** 在 Office 365 專業增強版的現有安裝中，預設會安裝 Microsoft Teams。 [深入了解](https://docs.microsoft.com/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a>商務用 Skype：功能更新

- **改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。 [深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a>Teams：功能更新

- **改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。 [深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

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

- 修正使用 [O365 Office 集中式部署](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment)部署的增益集發生凍結且無法使用的問題。


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
  **基於安全原因已封鎖 Flash、Silverlight、Shockwave 控制在 Office 中啟動：** 基於安全原因，Windows 上新組建的 Microsoft Office for Office 365 會封鎖 Flash、Silverlight、Shockwave 控制的啟動。請看 [這裡](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)和 [這裡](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US)深入了解。

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
