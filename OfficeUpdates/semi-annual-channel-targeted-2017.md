---
title: 在 2017年分號每年次通道 (Targeted) 版本的版本資訊
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/12/2017
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: 提供 IT 專業人員與版本資訊分號每年次通道 (Targeted) 版本的 Office 365 ProPlus 中 2017
ms.openlocfilehash: 6014107ae2471707d226602cc71efaa24f1de310
ms.sourcegitcommit: 5dabd0a6045b54940da7821e2349ec78b6b99d00
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/04/2018
ms.locfileid: "19555982"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2017"></a>在 2017年分號每年次通道 (Targeted) 版本的版本資訊

這些版本資訊提供的新功能、 安全性更新及 2017年中包括分號每年次通道 (Targeted) 更新至 Office 365 ProPlus 中的非安全性更新的相關資訊。
 
> [!NOTE]
> - 下列也提供資訊的新功能、 安全性更新及非安全性更新 Visio Pro for Office 365 及 Project Online 桌面用戶端。
> - 此資訊也適用於 Office 365 商務是隨附 Office 365 計劃，例如企業進階版的 Office 版本。
> - 分號每年次通道 (Targeted) 命名為第一次發行之前年 9 月 2017年延期通路。

## <a name="version-1708-december-12"></a>版本 1708年： 年 12 月 12 日
*版本 1708 （組建 8431.2131）*

 ### <a name="excel-security-updates"></a>Excel： 安全性更新
-   [CVE-2017年-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935)： Microsoft Excel 遠端程式碼執行弱點

### <a name="excel-non-security-updates"></a>Excel： 的非安全性更新
-   修正問題其中使用者不正確地看見 「 災難性失敗 」 錯誤訊息開啟 Office 2007 或更舊的活頁簿 （.xls 或.xla） 時的巨集。
-   修正問題其中從命令列開啟活頁簿可能會導致 rtf 格式儲存格中的遺失。

### <a name="outlook-security-updates"></a>Outlook： 安全性更新
-   [CVE-2017年-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939)： Microsoft Office 資訊洩漏弱點

### <a name="powerpoint-security-updates"></a>PowerPoint： 安全性更新
-   [CVE-2017年-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934)： Microsoft PowerPoint 資訊洩漏弱點

### <a name="project-non-security-updates"></a>專案： 的非安全性更新
-   修正問題發生問題之專案層級的自訂欄位的資料可以取得遺失的儲存位置。
-   修正問題其中失敗儲存可以損毀檔案並導致當機在開啟的專案。
-   修正問題其中開啟專案計劃可能導致損毀。

### <a name="word-security-updates"></a>Word： 安全性更新
-   [Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)： 深度更新中的 Microsoft Office 防禦



## <a name="version-1708-november-14"></a>版本 1708年： 年 11 月 14
*版本 1708 （組建 8431.2110）*

### <a name="access-non-security-updates"></a>Access： 的非安全性更新
-   修正問題嘗試在文字方塊或下拉式方塊中選取的文字出現的位置來選取所有文字，而不是指示選取項目。

### <a name="excel-security-updates"></a>Excel： 安全性更新
-   [CVE-2017年-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877)： Microsoft Excel 安全性功能旁路弱點
-   [CVE-2017年-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878)： Microsoft Excel 記憶體損毀弱點
-   [CVE-2017年-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884)： Microsoft Office 記憶體損毀弱點

### <a name="excel-non-security-updates"></a>Excel： 的非安全性更新
-   修正問題其中使用者無法關閉 [受保護的檢視中的活頁簿時的檔案名稱包含方括號。
-   修正的問題，當使用者嘗試以現有的活頁簿中插入一個物件，Excel 在當使用者按一下瀏覽]。
-   修正問題其中選取"調整圖案的修復文字"（在 [圖形格式] 窗格中的文字選項/文字方塊部分） 會導致不變更到圖案。
-   修正的問題，當開啟活頁簿，以在其上按兩下，儲存格的文字字型和格式不取得載入或兩個相同的活頁簿開啟單一的範本。
-   修正其中第一個活頁簿建立 Excel 啟動時不會關閉開啟或建立新的活頁簿時發生問題。
-   修正問題所在位置的工具提示時沒有對齊拖曳或拖曳填寫。
-   修正的問題，使用檔案儲存在活頁簿時\>另存新檔，包含期間的檔案名稱會出現空白或截斷的檔案儲存] 對話方塊中。
-   其中，將檔案儲存時同步處理備份、 Office 無法寫入至磁碟，但是將檔案上傳至 OneDrive Office 保持修正問題。 與此修正程式，使用者現在會看到錯誤訊息及上傳將不會繼續執行。
-   修正問題的轉譯因故障 graphics 驅動程式出現黑色線條和標頭的位置。
-   修正問題其中 Excel 損毀或無法儲存該活頁簿之後插入的圖表。
-   修正問題的不正確地位置] 頁面上換行符號的分頁預覽。

### <a name="outlook-non-security-updates"></a>Outlook： 的非安全性更新
-   修正問題其中使用者會看到 [訊息] 清單中跳意外刪除的郵件時將焦點。
-   修正問題導致使用者互動的附件時看到驗證提示。

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 的非安全性更新
-   其中，將檔案儲存時同步處理備份、 Office 無法寫入至磁碟，但是將檔案上傳至 OneDrive Office 保持修正問題。 與此修正程式，使用者現在會看到錯誤訊息及上傳將不會繼續執行。
-   修正問題其中編輯和格式化表格中的復原之後的文字會導致 PowerPoint 損毀。
-   修正問題其中 Flash Player 參考架構 YouTube 嵌入要播放影片新視窗開啟代碼結果。 舊內嵌程式碼可立即升級至參考 HTML5 基礎 YouTube 影片使正確就緒播放。

### <a name="word-security-updates"></a>Word： 安全性更新
-   [Advisory 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020)： 深度更新中的 Microsoft Office 防禦

### <a name="word-non-security-updates"></a>Word： 的非安全性更新
-   修正問題其中 Word 在當使用者嘗試執行另存新檔至現有的文件上 OneDrive for Business 然後取消儲存或會嘗試合併現有的變更。
-   其中，將檔案儲存時同步處理備份、 Office 無法寫入至磁碟，但是將檔案上傳至 OneDrive Office 保持修正問題。 與此修正程式，使用者現在會看到錯誤訊息及上傳將不會繼續執行。
-   修正問題其中 Word 可以 hang 如果不久後開啟 Word 使用者瀏覽至 [插入] 索引標籤。
-   其中之後按一下邊界、, 字元會顯示在螢幕的左上方輸入字元時修正問題。

### <a name="office-suite-security-updates"></a>Office 套件： 安全性更新
-   [CVE-2017年-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882)： Microsoft Office 記憶體損毀弱點

### <a name="office-suite-non-security-updates"></a>Office 套件： 的非安全性更新
-   修正縮放和擴充 Office 增益集下動態 DPI 環境中有問題。
-   修正問題即使 Office 365 ProPlus 目前安裝的 Office 設定服務提供者 (CSP) CurrentStatus 節點其中傳回空白字串。
-   修正造成問題.box 檔案格式變更，以影響功能更舊版本的 Office 安裝在同一部電腦，因為.box 檔案共用跨所有版本的 Office 應用程式在同一部電腦上。
-   其中，使用共用的電腦啟動時某些情況下，出現錯誤訊息表示應用程式有執行將會防止其運作正常及詢問使用者是否要執行修復錯誤修正問題。



## <a name="version-1708-october-10"></a>版本 1708年： 年 10 月 10 日
*版本 1708 （組建 8431.2107）*

### <a name="access-non-security-updates"></a>Access： 的非安全性更新
-   修正問題其中查詢不會執行查詢是否從 Microsoft Dynamics 連結資料表的主索引鍵聯結。
-   修正問題小數位數未顯示的貨幣值 Microsoft Dynamics 表格中的位置。

### <a name="excel-non-security-updates"></a>Excel： 的非安全性更新
-   修正問題時開啟 Excel 損毀。XLL 檔案。
-   修正問題所在的儲存格圖樣樣式不會轉譯之後將頁首或頁尾新增版面配置檢視中的正確。
-   其中一份樞紐分析表貼入另一個活頁簿可能會導致損毀修復問題。
-   修正的問題，當您選擇 [取代] 命令和 [尋找及取代] 對話方塊隨即開啟，焦點] 對話方塊的位於何處而不是 [取代] 索引標籤的 [尋找] 索引標籤。
-   修正問題時開啟的活頁簿的 [活動] 窗格從 SharePoint server 早於 SharePoint Server 2016 開啟 Excel 損毀。
-   修正問題 Excel 其中會開啟並啟用一或多個 XLL 增益集時，會顯示在空白的視窗。
-   Excel 其中具有已關閉的活頁簿中使用 [表單] 按鈕之後在修正問題。
-   修正的問題時使用 SheetBeforeRightClick 事件，插入與合併儲存格發生交集的資料行不會依序展開 [合併儲存格。

### <a name="outlook-security-updates"></a>Outlook： 安全性更新
-   [CVE-2017年-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774)： Microsoft Outlook 安全性功能旁路弱點
-   [CVE-2017年-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776)： Microsoft Outlook 資訊洩漏弱點

### <a name="outlook-non-security-updates"></a>Outlook： 的非安全性更新
-   修正問題其中"深入"中的連結原則提示不是可見時使用深灰色佈景主題。
-   當使用者嘗試設定新帳戶與他們關閉視窗不帳戶安裝完成 Outlook 損毀修正問題。
-   修正問題其中標示為已讀取並標記為未讀取會顯示為選項群組共用收件匣中的訊息。

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 的非安全性更新
-   從 SharePoint server 早於 SharePoint Server 2016 開啟簡報時 PowerPoint 損毀修正問題。

### <a name="word-security-updates"></a>Word： 安全性更新
-   [CVE-2017年-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826)： Microsoft Office 記憶體損毀弱點

### <a name="word-non-security-updates"></a>Word： 的非安全性更新
-   修正問題時開啟文件的 [活動] 窗格從 SharePoint server 早於 SharePoint Server 2016 開啟 Word 損毀。

### <a name="office-suite-security-updates"></a>Office 套件： 安全性更新
-   [CVE-2017年-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825)： Microsoft Office 程式碼執行弱點

### <a name="office-suite-non-security-updates"></a>Office 套件： 的非安全性更新
-   修正問題線上修復進度不顯示給使用者的位置。
-   修正問題出 Office 檔案屬性未出現在檔案總管]。
-   修正問題開啟的 Office 功能區上的第二個文件時消失的增益集] 按鈕的位置。
-   修正問題其中無法開啟一些 VBA 模組有雙位元組字元的名稱。



## <a name="version-1708-september-12"></a>版本 1708年： 年 9 月 12 日
*版本 1708 （組建 8431.2079）*

### <a name="access-feature-updates"></a>Access： 功能更新
-   **標籤名稱屬性：** 關聯表單上控制項的標籤，以提升協助工具。
-   **編輯新項目是更容易存取：** 若要編輯新項目從下拉式方塊或清單方塊使用快速的鍵盤快速鍵 (Ctrl + E)。
-   **動態連接器：** 從匯入資料或連結至資料儲存在 Microsoft Dynamics。 [更多資訊](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Salesforce 連接器：** 從匯入資料或連結至資料儲存在 Salesforce。 [更多資訊](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="excel-feature-updates"></a>Excel： 功能更新
-   **「 新增欄從範例 」 增強功能：** 支援多個日期/時間、 數學、 及索引資料欄的轉換。
-   **效能改良功能：** Excel 開啟複雜的活頁簿與多個工作表速度，讓您能夠吸收大範圍的公式，篩選大量資料列，或複製並貼上更快。
-   **插入線上圖片：** 新的選取圖像和屬性資訊的登陸頁面會自動插入圖像。
-   **Azure 資料湖儲存連接器：** 使用者現在可以將資料匯 Azure 資料湖存放區。
-   **"範例中的 [新增] 欄"增強功能：** 支援建議、 更多的日期/時間作業和其他的轉換。
-   **資料] 索引標籤**： [資料] 索引標籤上的功能區按鈕已重新編排成兩個新的群組： Get & 轉換資料和查詢 （s) 連線。
-   **共用的查詢**： 匯出至 Office 資料庫連線 (ODC) 檔案，任何查詢定義及不同的活頁簿或與其他人然後共用。
-   **載入資料：** 載入資料從查詢直接樞紐分析表或樞紐分析圖不必將資料儲存至資料模型。
-   **共用檔案活動：** 請參閱 onedrive for Business 的檔案共用時之檔案的右上角中選擇 [活動] 按鈕或 SharePoint 已共用、 編輯、 重新命名或還原。
-   **安全的連結：** 當使用者按一下連結時，Office 365 進階威脅保護 (ATP) 會檢查看看是否遭到惡意的連結。 如果連結會被視為惡意，使用者會重新導向至警告] 頁面上，而不是原始的目標 URL。 [更多資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **增強資料匯入功能：** 輕鬆地匯入及圖形從各種來源的資料。 管理活頁簿的查詢和連線以查詢連線側邊窗格中，並透過 ODC 檔案與其他人共用的查詢。 [更多資訊](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **共用檔案中的變更**： 檢視誰具有共用活頁簿中所做變更及還原更舊版本。 [更多資訊](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **套索選取 [使用畫筆按鈕：** 使用不含非常功能區支援套索選取筆跡數位畫筆按鈕。

### <a name="excel-security-updates"></a>Excel： 安全性更新
-   [並傳回 2017 CVE 8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501)： Microsoft Office 記憶體損毀弱點
-   [CVE-2017年-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502)： Microsoft Office 記憶體損毀弱點
-   [CVE-2017年-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631)： Microsoft Office 記憶體損毀弱點
-   [CVE-2017年-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632)： Microsoft Office 記憶體損毀弱點

### <a name="excel-non-security-updates"></a>Excel： 的非安全性更新
-   修正其中 Excel 暫時擱置當您展開或摺疊樞紐分析表和樞紐分析表標頭移動在螢幕以外的問題。
-   修正問題位置] 索引標籤會略過複製並貼至 tab 分隔格式 Word、 產生不剖析欄至文字中的文字。
-   修正問題時開啟 [發佈為網頁對話方塊 Excel 損毀。
-   修正其中的資料重新整理不會成功或 Excel 在使用從 SQL Server Analysis Services 伺服器的資料時與 Excel 的地區設定和 SQL Server Analysis Services 伺服器的地區設定不同的問題。
-   修正問題時嘗試將變更儲存至文件進行同步處理 OneDrive 用戶端錯誤出現的位置。
-   修正問題其中無法變更任何位置工作表中使用 [篩選] 區域中的欄位，但沒有其他地方的欄位在樞紐分析表時。

### <a name="outlook-feature-updates"></a>Outlook： 功能更新
-   **協助工具功能改良：** 我們已進行更容易閱讀及當您使用螢幕助讀程式編輯文字、 表格、 清單及電子郵件中的圖像。
-   **新帳戶組態：** 設定新帳戶需要較少的手動步驟新精靈]。
-   **Attach] 對話方塊的連結：** 當附加使用功能區上的 [附加檔案的連結，您可以選取是否要將其新增為連結或附件。 如果您不想查看此對話方塊每次，請移至檔案\>選項\>一般並指定您想要附加"[附件] 選項。 」 下的連結的方式
-   **支援在內部附件：** 從內部部署 SharePoint Server 的檔案顯示為最新訊息檔案\>附加檔案]，在內部 OneDrive for Business 和 SharePoint 小組網站會出現 [附加檔案] 下\>瀏覽 Web 位置及是否提供本機檔案可上傳至內部 OneDrive for Business 的網站。
-   **商務分類群組：** 建立或編輯群組時可指派定義租用戶系統管理員，例如 2 私人 3 機密、 商業分類層級與該分類會出現在群組首。
-   **來賓存取 Office 365 群組：** 與組織外的人共同作業所授與這些群組交談、 檔案、 行事曆邀請和群組筆記本的存取。 [更多資訊](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **可採取的郵件：** 開發人員可以建立以方便使用者採取簡單或快速右從 Outlook 不必切換至外部網站或個別的應用程式的訊息。 [更多資訊](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook： 安全性更新
-   [CVE-2017年-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571)： Microsoft Office Outlook 的安全性功能旁路弱點
-   [CVE-2017年-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572)： Microsoft Office Outlook 資訊洩漏弱點
-   [CVE-2017年-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663)： Microsoft Office Outlook 記憶體損毀弱點

### <a name="outlook-non-security-updates"></a>Outlook： 的非安全性更新
-   修正問題你無法在 Outlook 中設定 IMAP 帳戶。
-   修正問題導致間歇性損毀時開啟 Outlook。

### <a name="powerpoint-feature-updates"></a>PowerPoint： 功能更新
-   **插入線上圖片：** 新的選取圖像和屬性資訊的登陸頁面會自動插入圖像。
-   **關閉影片標題：** 將字幕新增使其更容易存取的影片。 [更多資訊](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **旁白錄製：** 包含自行 narrating 時進行簡報的錄製的影片。 錄製可以包含動畫、 筆跡、 音訊及視訊。
-   **共用檔案活動：** 請參閱 onedrive for Business 的檔案共用時之檔案的右上角中選擇 [活動] 按鈕或 SharePoint 已共用、 編輯、 重新命名或還原。
-   **替代文字架設：** 雲端式服務自動產生的簡報中的圖片的替代文字。
-   **安全的連結：** 當使用者按一下連結時，Office 365 進階威脅保護 (ATP) 會檢查看看是否遭到惡意的連結。 如果連結會被視為惡意，使用者會重新導向至警告] 頁面上，而不是原始的目標 URL。 [更多資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Designer 增強功能：** 建議動作導向清單專業設計的概念。
-   **共用檔案中的變更：** 檢視誰具有共用簡報中所做的變更及還原更舊版本。 [更多資訊](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint： 安全性更新
-   [CVE-2017年-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742)： PowerPoint 遠端程式碼執行弱點
-   [CVE-2017年-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743)： PowerPoint 遠端程式碼執行弱點

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 的非安全性更新
-   連結至字型的使用者定義字元 (EUDCs) 要顯示的失敗其中修正問題。

### <a name="project-non-security-updates"></a>專案： 的非安全性更新
-   修正問題其中開啟特定檔案從 Project Online 會導致專案損毀。
-   修正問題其中實際開始時間可能會錯誤時清除設定剩餘工時。
-   修正問題其中工作分派實際開始日期可能會顯示不同的資料超過所報告的資源透過 Project Web App 中的狀態。
-   修正問題其中實際工時可能會重新排程變更任務的完成日期。
-   修正問題出如果您將複製並貼上 [成本] 欄位，貼上的值可能無法完全符合因捨入的問題而複製的值。
-   修正問題其中時段式資料的預算資源不複製到另一個儲存從一個比較基準時。
-   其中 「 狀態 」 欄位不會自動計算正確的摘要任務修正問題。
-   修正問題其中實際工時錯誤取得轉接至企業資源時加以取代本機資源並啟用受保護的工作。
-   如果您有其中第一欄是任務名稱、 欄已鎖定，而您按一下 [工作表專案損毀修復問題。
-   修正問題其中您可以指派相同的資源多次到相同的任務到任務分派狀況] 檢視。
-   修正問題其中時開啟 XML 檔案中的數字的自訂欄位的值可能會遺失。
-   修正問題其中最上層的任務縮排不會同步處理正確專案從 SharePoint 任務清單。
-   修正問題其中若您匯入任務、 資源或工作分派資訊從 Excel 活頁簿中 [工時] 欄位的值可能會被忽略。
-   修正問題出按照時段的基準值不符合初始值將專案儲存至 XML 檔案格式。
-   修正問題 Project 用戶端將不會開啟其中一個專案由於它會認為時其確實並未取出專案。
-   使專案檔案從開啟的檔案伺服器具備高延遲開啟得更快修正問題。

### <a name="skype-for-business-security-updates"></a>Skype for Business： 月份的安全性更新
-   [CVE-2017年-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676)： Windows GDI + 資訊洩漏弱點
-   [CVE-2017年-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695)： 圖形元件資訊洩漏弱點
-   [CVE-2017年-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696)： Microsoft 圖形元件遠端執行程式碼

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 的非安全性更新
-   新增說明為何使用者無法封鎖特定連接埠或 Ip 不 whitelisted 時加入會議] 對話方塊。
-   修正問題其中常設聊天室中未閱讀的郵件會標示為已讀取時按一下 [IM 交談索引標籤。
-   修正問題傳入的 IM toasts 經驗的其中幾秒延遲。
-   修正問題時在何處 AD 連絡人會顯示為電話號碼，而非連絡人名稱與 Exchange 同步處理已停用。
-   修正問題匿名加入使用者會禁止加入已停用同盟和匿名加入未明確封鎖的會議召集人時。
-   受邀者數目不正確地顯示會議召集人的會議超過此限制的修正問題。
-   修正問題不在撥入 PSTN 通話吐司中顯示的電話號碼。
-   修正的問題，使用時的 Delete 鍵時重新命名的連絡人清單群組，會刪除整個群組。
-   修正共用停駐點之前先解除 IM 交談中的共用通知時發生問題。
-   其中的登入畫面是一些非英文語言的空白修正問題。
-   修正問題交談和聊天歷程記錄中的非英文字元混亂的位置。
-   顯示若已知的使用者名稱不是由組織的自動語音應答處理來電的發話者的電話號碼。
-   加入允許的"的任何人 （無限制）"做為選項的限制的"這些人員不需要在大廳中等候。"inband 設定
-   新增能夠開啟或關閉自助視訊的 P2P 視訊通話中 VDIv2。
-   修正問題重複的數字通話下拉功能表中的連絡人的顯示位置。
-   修正問題其中代理人已移除之企業版的 Skype 和 Skype 的商業基本之間移動的使用者。
-   修正問題其中顯示為離線不可見時使用啟用顯示為離線或自訂狀態 URL 用戶端原則。
-   加寬修正截斷的一些當地語系化語言加入會議] 按鈕。
-   增加高重要性郵件交談的重要性。
-   將 Office 和 Skype 的商務檔案副檔名類型新增至允許檔案傳輸 blocklists。
-   會議的頁尾文字 Outlook 會議邀請中的當地語系化校正將非英文版的設定。
-   出寄件者名稱可以交換的多個使用者的交談中修正的問題。
-   修正 [空白的交談] 視窗會顯示之前已成功加入會議失敗的問題。
-   修正問題部門] 欄位中資訊的連絡人卡片位置是在搜尋結果中空白如果是空的 [標題] 欄位。
-   修正登入失敗的使用者從內部部署遷移至 online 因為防火牆規則。
-   新增新 DWORD 登錄機碼以修正發生問題，當使用者登入執行 LyncAutoD 外部網路上的用戶端，用戶端 OAuthUsed 登錄機碼會重設為 false。 若要修正此問題，將值設定為 1 下 HKEY EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket\_目前\_使用者\\軟體\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>.

### <a name="visio-feature-updates"></a>Visio： 功能的更新
-   **製作圖表中的 Excel 資料從：** 自動建立基本流程圖] 或 [交互功能流程圖從 Excel 資料使用新的資料視覺化檢視範本。 [更多資訊](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **安全的連結：** 當使用者按一下連結時，Office 365 進階威脅保護 (ATP) 會檢查看看是否遭到惡意的連結。 如果連結會被視為惡意，使用者會重新導向至警告] 頁面上，而不是原始的目標 URL。 [更多資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio： 的非安全性更新
-   修正問題沒有收到 COM 增益集的位置開啟的文件事件來檔案圖示或檔案名稱上按兩下開啟 Visio 檔案時。

### <a name="word-feature-updates"></a>Word： 功能更新
-   **插入線上圖片：** 新的選取圖像和屬性資訊的登陸頁面會自動插入圖像。
-   **替代文字架設：** 雲端式服務會自動產生文件中的替代文字 （alt） 的圖片。
-   **共用檔案活動：** 請參閱 onedrive for Business 的檔案共用時之檔案的右上角中選擇 [活動] 按鈕或 SharePoint 已共用、 編輯、 重新命名或還原。
-   **安全的連結：** 當使用者按一下連結時，Office 365 進階威脅保護 (ATP) 會檢查看看是否遭到惡意的連結。 如果連結會被視為惡意，使用者會重新導向至警告] 頁面上，而不是原始的目標 URL。 [更多資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **共用檔案中的變更：** 檢視誰具有共用的文件中所做變更及還原更舊版本。 [更多資訊](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-non-security-updates"></a>Word： 的非安全性更新
-   修正問題 Grammarly 的增益集載入時意外關閉 Word。
-   修正的問題，在某些情況下 Word 在嘗試復原雲端架構檔案時。
-   修正問題無法旋轉圖形在繪圖畫布的位置。
-   其中，輸入在韓文、 時母音與母音不正確地用逗號修正問題。
-   將文件儲存成 PDF 儲存文件版本 1.7 為 PDF。

### <a name="office-suite-security-updates"></a>Office 套件： 安全性更新
-   [CVE-2017年-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570)： Microsoft Office 程式碼執行弱點
-   [CVE-2017年-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630)： Microsoft Office 記憶體損毀弱點
-   [CVE-2017年-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744)： Microsoft Office 記憶體損毀弱點

### <a name="office-suite-non-security-updates"></a>Office 套件： 的非安全性更新
-   修正防止什麼是從出現的 [新增] 對話方塊的問題。
-   修正問題其中繪製] 索引標籤上按一下 [會導致某些使用者的損毀的應用程式。
-   修正問題其中停留常見控制項在其有工具提示會導致損毀的應用程式。
-   修正問題授權的錯誤訊息出現時使用一般的控制項的位置。
-   修正問題如何簽署某些程式檔案、 導致防毒程式來標幟這些檔案，以及保護問題或存取 [Windows 資訊保護 (WIP) 的資料。
-   新增 support.to 允許使用者使用 64 位元版本的 Office 開啟包含 mscomctl.ocx 控制項的巨集檔案。
-   改善 mscomctl.ocx 中所使用的控制項的協助工具。
-   修正問題命令位於功能區] 或 [快速存取工具列自訂對話方塊中遺漏的位置。



## <a name="version-1705-august-8"></a>版本 1705年： 2010 年 8 月 8 日
*版本 1705 （組建 8201.2171）*

### <a name="outlook-non-security-updates"></a>Outlook： 的非安全性更新
-   修正問題的拖曳 scrollbar 移動到的郵件清單。

### <a name="office-suite-non-security-updates"></a>Office 套件： 的非安全性更新
-   修正問題如何簽署某些程式檔案、 導致防毒程式來標幟這些檔案，以及保護問題或存取 [Windows 資訊保護 (WIP) 的資料。
-   修正防止什麼是從出現的 [新增] 對話方塊的問題。



## <a name="version-1705-july-27"></a>版本 1705年： 年 7 月 27 日
*版本 1705 （組建 8201.2158）*

### <a name="excel-non-security-updates"></a>Excel： 的非安全性更新
-   修正問題時嘗試將變更儲存至文件進行同步處理 OneDrive 用戶端錯誤出現的位置。
-   修正問題其中 Excel 在將工作表資料新增至資料模型時，且高對比佈景主題設定為黑色。

### <a name="outlook-security-updates"></a>Outlook： 安全性更新
-   [CVE-2017年-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571)： Microsoft Office Outlook 的安全性功能旁路弱點
-   [CVE-2017年-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572)： Microsoft Office Outlook 資訊洩漏弱點
-   [CVE-2017年-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663)： Microsoft Office Outlook 記憶體損毀弱點

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 的非安全性更新
-   修正問題其中後另一位使用者變更版面配置新增一個圖案會導致合併失敗。

### <a name="word-non-security-updates"></a>Word： 的非安全性更新
-   其中，輸入在韓文、 時母音與母音不正確地用逗號修正問題。
-   信封上的傳遞地址太靠近列印到左邊緣修正問題。



## <a name="version-1705-july-13"></a>版本 1705年： 年 7 月 13 日
*版本 1705 （組建 8201.2136）*

### <a name="excel-security-updates"></a>Excel： 安全性更新
-   [並傳回 2017 CVE 8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501)： Microsoft Office 記憶體損毀弱點
-   [CVE-2017年-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502)： Microsoft Office 記憶體損毀弱點

### <a name="excel-non-security-updates"></a>Excel： 的非安全性更新
-   修正問題 Excel 活頁簿包含外部連結的損毀的位置。
-   修正問題其中貼上從 Excel 至字的儲存格顯示儲存格中零時即使未選取"零中有零值的儲存格的 Show"的設定。

### <a name="project-non-security-updates"></a>專案： 的非安全性更新
-   修正看圖表/表格窗格中選取圖表/資料表的值不發生問題。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 的非安全性更新
-   修正問題其中交談視窗不會顯示在背景中時加入會議及音訊裝置加入] 對話方塊會顯示給使用者。
-   修正問題其中從 Outlook 的 [會議] 連結不一定傳遞內部 URI 正確。
-   擴展修正截斷的一些當地語系化語言加入會議] 按鈕。

### <a name="word-non-security-updates"></a>Word： 的非安全性更新
-   修正其中資料表無法正確顯示特定動作後發生問題。
-   修正問題其中多個編輯引文一些時間顯示成單一復原動作而不是依個別的動作。
-   復原已停用特定動作後修正問題。
-   修正以防止資料可能會遺失某些復原動作後發生問題。

### <a name="office-suite-security-updates"></a>Office 套件： 安全性更新
-   [CVE-2017年-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570)： Microsoft Office 程式碼執行弱點

### <a name="office-suite-non-security-updates"></a>Office 套件： 的非安全性更新
-   修正會導致 Office 2016 失敗時使用 System Center Configuration Manager 的 Office 2013 的自動的升級問題。
-   其中不載入舊版增益集透過公司目錄存放區從部署修正問題。



## <a name="version-1705-june-13"></a>版本 1705年： 年 6 月 13 日
*版本 1705 （組建 8201.2102）*

### <a name="access-feature-updates"></a>Access： 功能更新
-   **什麼是 [新增] 對話方塊：** 會醒目提示新的 Access 功能對話方塊隨即顯示 Access 開啟後存取更新新功能時。 [] 對話方塊是也移至檔案\>帳戶\>的新功能。
-   **大量 (bigint) 支援：** 使用大量資料型別 Access 資料表中計算大的數字，以及連結到或匯入來自使用對等的資料類型，例如 bigint SQL Server 中的外部資料庫。 [更多資訊](https://blogs.office.com/2017/03/06/new-in-access-2016-large-number-bigint-support/)

### <a name="excel-feature-updates"></a>Excel： 功能更新
-   **Windows 資訊保護 (WIP) 支援：**  Excel 現在是開明應用程式，且能區分公司和個人資料，正確地判斷要 protect、 根據設定的原則。  [更多資訊](https://aka.ms/wiptechnet)
-   **取得 & 轉換改進：** 在查詢編輯器中，以提供範例值建立新的欄。 當您輸入時，Excel 會偵測所需的轉換及顯示新欄的預覽。
-   **插入最近的連結：** 輕鬆地附加至最近使用的雲端架構檔案或網站的超連結並建立使用螢幕助讀程式的人員的有意義的顯示名稱。 [更多資訊](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **個人化的預設樞紐分析表版面配置：** 設定樞紐分析表，以及每次您建立新的樞紐分析表的開頭的版面配置的方式。 [更多資訊](https://support.office.com/article/efd8569c-f07a-43c1-9db2-4f2912a0f94e)
-   **取得 & 轉換為增強功能：** 使用者可以範例建立新的欄和列配置分割表格欄。 指定用以 SAP HANA 參數與群組資料現在會比較容易。
-   **集中式部署的增益集**： 系統管理員可以部署和 Office 365 系統管理中心增益集更新為使用者或群組。 [更多資訊](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **快速存取工具列自訂：** 下標和上標圖示可以新增至快速存取工具列。
-   **取得 & 轉換為增強功能：** 自動偵測的分隔符號字元分割資料行使用查詢編輯器中，選擇要合併二進位檔搭配使用的範例檔案並指定套件集合時使用 DB2 連接器連線時。
-   **阿布達比字型：** 支援西歐語言以及使用阿拉伯指令碼的主要語言的字型系列。 [更多資訊](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景移除：** 移除的自由格式的繪圖工具的圖片背景。
-   **取得 & 轉換為增強功能：**「 選取相關資料表 」 在 [導覽] 對話方塊以使用 ODCB 和 OLEDB 連接器、 結合多個檔案直接從資料夾資料預覽] 對話方塊中，並使用新的快顯功能表選項 [查詢編輯器] 視窗中現有的查詢中插入新的步驟。
-   **用於選取及變更物件的畫筆：** 取得物件控點以調整大小、 旋轉、 移動、 數位畫筆等等。
-   **對應圖表：** 比較的值並顯示不同地理區域的類別。 [更多資訊](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)
-   **SVG 圖像：** 插入及編輯活頁簿中的可調整的向量圖形 (SVG)。 [更多資訊](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入圖示：** 使用標準文件庫的可擴充的向量圖形 (SVG) 檔案移至插入圖示\>圖例\>圖示。 [更多資訊](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **儲存至最新的資料夾：** 使用 [最近] 索引標籤當您移至 [檔案儲存至最近使用過資料夾的活頁簿\>另存新檔。
-   **協助工具功能改良：** 使用鍵盤、 [朗讀程式] 和其他輔助技術，閱讀並編輯活頁簿的改良的支援。 [更多資訊](https://support.office.com/article/51fcb17a-b15b-4b13-ae04-d4f38ece3f78)

### <a name="excel-security-updates"></a>Excel： 安全性更新
-   Microsoft 安全性公告[MS17 014](https://technet.microsoft.com/library/security/ms17-014)： Microsoft Office (3217868) 的安全性更新

### <a name="excel-non-security-updates"></a>Excel： 的非安全性更新
-   修正問題 Excel 不會將設定套用以程式設計方式建立 Excel 2010 中或更早版本的活頁簿時的工作表保護密碼。
-   修正問題其中合併為中心未作用群組工作表中。
-   修正問題其中已導入後版本的 Office 2016-例如的新功能、 TEXTJOIN、 CONCAT、 IFS、 MAXIFS、 和 MINIFS-均遺失。
-   當使用者嘗試將儲存格層級權限套用 Excel 當機修正問題。
-   修正問題其中將大型檔案儲存至 OneDrive for Business 會導致鎖定檔案，且使用者無法編輯檔案直到使用者關閉並重新開啟 Excel。
-   在新視窗出現的位置灰色.xls 活頁簿開啟時修正問題。
-   修正問題其中 Excel 可能會損毀插入超連結。
-   修正問題其中 Excel 可能會失敗時新增 XML 對應。
-   其中命令按鈕的增益集未作用中之增益集，以便在升級之後或移除和一次下載增益集來自 Office 市集後修正問題。
-   修正問題其中 Excel 可能會損毀操作透過 VBA 的 DLL 工作表。
-   選取圖表上的表單控制項下拉式方塊時 Excel 當機修正問題。

### <a name="onenote-feature-updates"></a>OneNote： 功能更新
-   **Windows 資訊保護 (WIP) 支援：** OneNote 現在是開明應用程式，且能區分公司和個人資料，正確地判斷要 protect、 根據設定的原則。 [更多資訊](https://aka.ms/wiptechnet)

### <a name="onenote-non-security-updates"></a>OneNote： 的非安全性更新
-   修正問題其中 OneNote 畫布隱藏內容或更新檢視中有許多段落。

### <a name="outlook-feature-updates"></a>Outlook： 功能更新
-   **Windows 資訊保護 (WIP) 支援：**  Outlook 現在是開明應用程式，且能區分公司和個人資料，正確地判斷要 protect、 根據設定的原則。  [更多資訊](https://aka.ms/wiptechnet)
-   **插入最近的連結：** 附加至最近使用的雲端架構檔案或網站的超連結，並建立使用螢幕助讀程式的人員的有意義的顯示名稱。 [更多資訊](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **阿布達比字型：** 支援西歐語言以及使用阿拉伯指令碼的主要語言的字型系列。 [更多資訊](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景移除：** 移除的自由格式的繪圖工具的圖片背景。
-   **檢查存取共用檔案：** Outlook 告訴使用者隨時若收件者可能無法存取附加的 OneDrive 或 SharePoint 檔案，並且建議如何修正問題。
-   **設定的權限的附件：** Onedrive for SharePoint 附件的使用者可以設定收件者組織或外部，擁有讀取或編輯附件的權限。
-   **Pinnable taskpane:** 增益集 taskpane 保持在開啟狀態時的信箱中的郵件之間切換。 [更多資訊](https://blogs.msdn.microsoft.com/exchangedev/2017/01/26/pinnable-taskpane-in-outlook-2016/)
-   **SVG 圖像：** 插入及編輯電子郵件中的可調整的向量圖形 (SVG)。 [更多資訊](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入圖示：** 使用標準文件庫的可擴充的向量圖形 (SVG) 檔案移至插入圖示\>圖例\>圖示。  [更多資訊](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-security-updates"></a>Outlook： 安全性更新
-   [CVE-2017年-0106年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106)： Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2017年-0204年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204)： Microsoft Office 安全性功能旁路弱點
-   [CVE-2017年-8506](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8506)： Microsoft Office 程式碼執行
-   [CVE-2017年-8507](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8507)： Microsoft Office 記憶體損毀弱點
-   [CVE-2017年-8508](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8508)： Microsoft Office 安全性功能旁路弱點

### <a name="outlook-non-security-updates"></a>Outlook： 的非安全性更新
-   修正問題時機器的記憶體不足 Outlook 功能窗格停止轉譯的位置。
-   附件寬以視覺方式展開以符合檔案名稱與權限資訊。
-   修正問題使用者無法搜尋 PST 檔案的位置。
-   修正問題其中使用者看見新"Microsoft Exchange"類型儲存在 「 新的 Outlook 資料檔"] 對話方塊中，選取 [這個新的資料類型會變成無法使用的使用者設定檔。
-   修正其中映像中一則訊息 blacked 出時傳送來自使用高 DPI 電腦發生問題。

### <a name="powerpoint-feature-updates"></a>PowerPoint： 功能更新
-   **Windows 資訊保護 (WIP) 支援：**  PowerPoint 現在是開明應用程式，且能區分公司和個人資料，正確地判斷要 protect、 根據設定的原則。  [更多資訊](https://aka.ms/wiptechnet)
-   **插入最近的連結：** 附加至最近使用的雲端架構檔案或網站的超連結，並建立使用螢幕助讀程式的人員的有意義的顯示名稱。 [更多資訊](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **集中式部署的增益集**： 系統管理員可以部署和 Office 365 系統管理中心增益集更新為使用者或群組。 [更多資訊](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **阿布達比字型：** 支援西歐語言以及使用阿拉伯指令碼的主要語言的字型系列。 [更多資訊](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景移除：** 移除的自由格式的繪圖工具的圖片背景。
-   **SVG 圖像：** 插入及編輯簡報中的可調整的向量圖形 (SVG)。 [更多資訊](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入圖示：** 使用標準文件庫的可擴充的向量圖形 (SVG) 檔案移至插入圖示\>圖例\>圖示。 [更多資訊](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **即時輸入時的共同撰寫：** 請參閱其中其他人所運作中的呈現方式和檢視變更為他們輸入。 [更多資訊](https://support.office.com/article/0c30ee3f-8674-4f0e-97be-89cf2892a34d)
-   **儲存至最新的資料夾：** 使用 [最近] 索引標籤當您移至 [檔案儲存至最近使用過資料夾的簡報 （英文）\>另存新檔。
-   **建立精確筆跡的圖形：** 拖曳線段橡皮擦移除寬幅個位元墨色、 從右至最接近的行。
-   **選取及操作物件與畫筆：** 使用數位畫筆移動、 調整或旋轉物件使用其控點，或使用套索選取筆跡支援的畫筆按鈕。
-   **協助工具功能改良：** 使用鍵盤、 [朗讀程式] 和其他輔助技術，閱讀並編輯簡報的改良的支援。 [更多資訊](https://support.office.com/article/3fce93f5-9ca8-42a6-bc1f-776749f6e32e)

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 的非安全性更新
-   修正問題時在使用者處於設計想法窗格如果 mfplat.dll 檔案不在電腦上安裝 PowerPoint 損毀。
-   其中命令按鈕的增益集未作用中之增益集，以便在升級之後或移除和一次下載增益集來自 Office 市集後修正問題。

### <a name="project-feature-updates"></a>專案： 功能更新
-   **快速下拉式管理來設定前置任務：** 使用甘特圖] 下拉式清單選擇哪一個前置任務或您想要連結至任務的後續任務。
-   **任務摘要名稱：** 會顯示任務的摘要任務名稱的唯讀的任務] 欄位。  

### <a name="project-non-security-updates"></a>專案： 的非安全性更新
-   修正 [建立專案網站] 對話方塊中顯示之網站的正確位置既然 Project Online 中每個企業專案範本 (EPT) 會有自己的專案網站的 URL。
-   修正問題 VBA BeforeClose 事件其中之前儲存提示就會引發與您不需要以程式設計的方式來判斷使用者的回應儲存提示。
-   修正問題其中實際完成百分比不彙總正確的專案狀態日期之後開始的工作。
-   修正問題時的成本與工時資源分派給相同的工作，您可能無法變更工作的狀態管理員。
-   其中特定資源撫平整個專案的專案可以讓您留在無限迴圈修正問題。
-   修正問題其中任務開始和完成日期不同步處理至 SharePoint 任務清單正確如果您有特定西班牙文的地區設定。
-   修正問題其中如果您啟動狀態核准程序從 Project 用戶端，它可能永遠無法完成，離開專案中無法使用的狀態。
-   修正問題其中預覽列印不會配置任務名稱正確如果您有中文和英文單字。
-   修正問題位置複製到 PowerPoint 的時間表作為個別的圖形不會運作。
-   修正問題"專案間的連結 」 對話方塊預期地顯示值 「 找不到檔案。 」
-   您要取得不一致的問題會產生指派資源的最大可用量為 0 時的修正程式。
-   修正其中任務開始日期取得重設為盡時刪除工作分派的開始日期、 忽略之類的前置任務，以工作分派前置分割時會導致發生問題。
-   修正問題其中您可以從 SharePoint 開啟檔案透過 [最近] 功能表中，如果專案會自動取出給您即使 「 需要之前可加以編輯已取出的文件？ 」 的設定 已啟用。
-   其中如果您直接移至專案設定檔應用程式，專案在修正問題。
-   修正問題其中手動排程的任務不會更新正確的 Project 2013 中升級的使用者。
-   修正問題其中時開啟專案從 SharePoint 任務清單、 專案可能會損毀為啟動 Project 任務同步處理程序。
-   修正問題其中 Project 有時損毀時要建立小組。
-   [比較基準資訊其中會遺失時儲存專案修正問題。
-   修正問題其中列印成品難以閱讀適用於大型專案計劃。
-   修正問題其中編輯 Project Web App 中的專案不顯示正確的公式欄位的值。
-   修正問題資源企業自訂欄位的資訊不儲存正確的專案計劃。
-   修正問題其中更新任務 %完成工時資訊更新工作的 %的完整資訊。
-   修正問題時儲存專案的專案擁有權變更的位置。
-   修正問題 CPI 不正確地計算摘要任務。
-   修正問題位置複製並貼上工作執行透過比較基準資料和儲存的資料，即使使用者不可儲存受保護的比較基準資料。
-   修正問題其中從 Excel 匯入資料產生的任務及工作分派的正確日期資訊。
-   其中之後開啟報表、, 專案損毀時關閉修正問題。
-   修正問題其中專案工作時停止儲存專案所在的自訂清單包含驗證設定。
-   修正問題其中輸入"\>"篩選器定義] 對話方塊中的 [測試] 欄中的字元未正確解譯為意義"大於。 」
-   修正問題的顯示進度線相對於"比較基準計劃 」。
-   修正問題其中自訂篩選器時不會顯示下拉式清單中的欄位名稱。
-   修正問題長條圖樣式預覽未出現在 [長條圖樣式] 對話方塊中的位置。

### <a name="publisher-non-security-updates"></a>Publisher： 的非安全性更新
-   修正問題 Publisher 不會顯示 CMYK TIF 圖像的位置。

### <a name="skype-for-business-feature-updates"></a>Skype for Business： 更新的功能
-   **插入的連結：** 將連結新增至 IM 與群組聊天並提供易記的文字，而不是完整的 URL 連結。
-   **螢幕共用通知：** 通知會顯示在 [交談] 視窗中正在共用螢幕 IM 交談中或螢幕共用會繼續執行後離開會議時。 通知會提醒您仍會共用您的螢幕並容易停止共用使用 「 停止共用 」 按鈕。
-   **Windows 資訊保護 (WIP) 支援：** 適用於企業的 Skype 現在已經支援為 WIP 工時僅應用程式。  允許應用程式清單中新增 Skype，它會指出 Windows 它不會處理個人資料。  Windows 會保護資料安全性代表 Skype for Business。  [更多資訊](https://aka.ms/wiptechnet)
-   **密碼重設] 選項：** 重設] 按鈕連結出現在視窗中登入使用者至少一次登入失敗時。

### <a name="skype-for-business-security-updates"></a>Skype for Business： 月份的安全性更新
-   Microsoft 安全性公告[MS17 013](https://technet.microsoft.com/library/security/ms17-013)： Microsoft 圖形元件 (4013075) 的安全性更新
-   [CVE-2017年-0281年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)： Microsoft Office 程式碼執行弱點
-   [CVE-2017年-0283年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0283)： Windows Uniscribe 遠端執行程式碼弱點
-   [CVE-2017年-8550](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8550)： 適用於商務遠端程式碼執行弱點 Skype

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 的非安全性更新
-   變更的使用者嘗試呼叫的訊息與音訊原則停用從 「 無法完成通話""無法撥打因為 IT 系統管理員具有受限的音訊。 嘗試改為使用立即訊息或電子郵件並檢查其 IT 系統管理員以要求"。
-   新增"忘記您的電話撥入 PIN"超連結到會議邀請的啟用 PSTN 會議使用者的 Skype 商務 online。
-   啟用 Business 線上從 Skype 小組會議加入。
-   從 40%變更預設喇叭工作階段大量 75%。
-   允許為較小的最小寬度] 索引標籤清單的調整大小。
-   更新要比對] 索引標籤的順序的快速鍵。
-   從行動裝置傳送時修正不正確的希伯來文字的方向。
-   修正問題 narrated 由螢幕助讀程式存在桌面/授與控制權] 功能的資訊。
-   選取 [會議室清單中顯示開啟的聊天室除了已瀏覽過的聊天室。
-   新增自訂 RCC 應用程式啟用時停用 VoIP 功能的能力。
-   變更離線 IM 標語以"嘗試的商務行動裝置應用程式 Skype"。
-   修正問題導致開啟為標準的視窗，而不是自動接受交談的交談] 視窗最小化狀態，並預期地從其他 windows 取得焦點。
-   與 Skype 會議選項] 對話方塊上使用螢幕助讀程式中修正的問題。
-   修正問題邀請中的第一個郵件不顯示未接的交談電子郵件中的位置。
-   修正問題時建立會議邀請從 Outlook 使用新的 Skype 會議] 按鈕在何處顯示重複的撥入號碼。
-   其中時出現捲軸、, IM 歷程記錄中的所有交談未都選取時若要選取所有使用 Ctrl + A 修正問題。
-   其中的輸出文字可能不完全相同格式的使用 Export-csarchivingdata cmdlet 時修正問題。
-   會議召集人所在無法立即開會使用 3 或更多位參與者時看到的遠端參與者的視訊修正問題。
-   修正問題所在的會議名冊第一行是空白的當使用者以滑鼠右鍵按一下在參與者清單中的另一位使用者的名稱。
-   修正使用者是無法登入內部和外部的公司網路之間切換時所發生問題。
-   修正問題聊天地區未從 IM 至在諮詢傳輸音訊自發性地擴大時關閉。
-   修正問題其中名稱無條件捨去吐司通知中的兩個端點同時響鈴使用時。
-   修正問題檔案名稱截斷檔案共用通知中的位置。
-   新增至通話和轉接] 按鈕後工具提示。
-   請在可用螢幕助讀程式，例如 [朗讀程式] 的 [諮詢轉接] 視窗中的保留所花費的時間。
-   新增為預設喜好設定諮詢傳輸時必須使用選擇 IM 或電話的能力。
-   新增功能、 諮詢傳輸，以滑鼠右鍵按一下 [查看連絡人的電話號碼清單"傳輸 」 按鈕時發生。
-   改善使其成為一般的錯誤訊息是在使用者具有無效的授權或尚未被指派授權的問題的清除。
-   修正問題時在何處不是所有連絡人都顯示在 [交談] 視窗標題中使用者啟動與連絡人的交談，然後新增另一位連絡人。
-   修正問題 [朗讀程式不會讀取通知 2nd 線條的字。
-   修正問題其中呼叫會轉接到 VOIP，而不是已諮詢的數字。
-   修正問題時使用者在 [內容] 視窗中瀏覽 [朗讀程式] 所在發佈不正確的資訊。
-   修正問題所在的建立者和修飾詞的名稱不會顯示停留在白板上註釋

### <a name="visio-feature-updates"></a>Visio： 功能的更新
-   **尋找協力廠商樣板：** 搜尋所選取的內容提供者提供的協力廠商樣板。
-   **投影片的程式碼片段：** 執行程式碼片段的 Visio 繪圖並將其匯出至 PowerPoint 投影片為。 [更多資訊](https://support.office.com/article/e7da404b-4208-49d1-9518-6fe1a4723657)

### <a name="word-feature-updates"></a>Word： 功能更新
-   **Windows 資訊保護 (WIP) 支援：**  Word 現在是開明應用程式，且能區分公司和個人資料，正確地判斷要 protect、 根據設定的原則。  [更多資訊](https://aka.ms/wiptechnet)
-   **插入最近的連結：** 附加至最近使用的雲端架構檔案或網站的超連結，並建立使用螢幕助讀程式的人員的有意義的顯示名稱。 [更多資訊](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **集中式部署的增益集**： 系統管理員可以部署和 Office 365 系統管理中心增益集更新為使用者或群組。  [更多資訊](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **阿布達比字型：** 支援西歐語言以及使用阿拉伯指令碼的主要語言的字型系列。 [更多資訊](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景移除：** 移除的自由格式的繪圖工具的圖片背景。
-   **並排：** 滑動它們以並行類似的紙張堆疊瀏覽整頁模式檢視中的頁面。 [更多資訊](https://support.office.com/article/21bfd0ff-0e1f-4c43-b188-8b36dfe6dcf4)
-   **用於選取及變更物件的畫筆：** 取得物件控點以調整大小、 旋轉、 移動、 數位畫筆等等。
-   **SVG 圖像：** 插入及編輯文件中的可調整的向量圖形 (SVG)。 [更多資訊](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入圖示：** 使用標準文件庫的可擴充的向量圖形 (SVG) 檔案移至插入圖示\>圖例\>圖示。  [更多資訊](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **儲存至最新的資料夾：** 使用 [最近] 索引標籤當您移至 [檔案儲存至最近使用過資料夾的文件\>另存新檔。
-   **改善讀取學習工具：** 在閱讀模式強化讀取技巧來調整間距的文字中的新命令，顯示音節、 間的分隔符號反白顯示每個 word 文件作為是助讀程式及。 [更多資訊](https://support.office.com/article/29efa413-e2da-4cac-b2a5-2defc6d34fd9)
-   **圖案辨識：** 自動使用 Draw 轉換成圖形在繪圖\>轉換成圖案。 [更多資訊](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="word-security-updates"></a>Word： 安全性更新
-   Microsoft 安全性公告[MS17 014](https://technet.microsoft.com/library/security/ms17-014)： Microsoft Office (3217868) 的安全性更新
-   [CVE-2017年-0254年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254)： Microsoft Office 記憶體損毀弱點
-   [CVE-2017年-0281年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)： Microsoft Office 程式碼執行弱點
-   [CVE-2017年-0292年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0292)： Windows PDF 遠端程式碼執行弱點 
-   [CVE-2017年-8509](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8509)： Microsoft Office 程式碼執行弱點  

### <a name="word-non-security-updates"></a>Word： 的非安全性更新
-   修正問題使用者無法搜尋 PST 檔案的位置。
-   修正問題其中使用者看見新"Microsoft Exchange"類型儲存在 「 新的 Outlook 資料檔"] 對話方塊中，選取 [這個新的資料類型會變成無法使用的使用者設定檔。

### <a name="office-suite-security-updates"></a>Office 套件： 安全性更新
-   [CVE-2017年-0199年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199)： Microsoft Office/WordPad 遠端程式碼執行弱點 w/Windows API
-   [CVE-2017年-0260年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0260)： Microsoft Office 程式碼執行
-   [CVE-2017年-0261年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261)： Microsoft Office 程式碼執行弱點
-   [CVE-2017年-0262年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262)： Microsoft Office 程式碼執行弱點
-   [CVE-2017年-0281年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)： Microsoft Office 程式碼執行弱點
-   [CVE-2017年-8510](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8510)： Microsoft Office 程式碼執行弱點
-   [CVE-2017年-8512](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8512)： Microsoft Office 程式碼執行弱點



## <a name="version-1701-may-9"></a>版本 1701年： 年 5 月 9 日
*版本 1701 （組建 7766.2084）*

### <a name="outlook-non-security-updates"></a>Outlook： 的非安全性更新
-   修正問題導致間歇性查看訊息中的選取範圍的訊息清單 jump 意外刪除的郵件時的使用者。
-   修正問題導致間歇性當機次數。
-   新增 HKEY\_目前\_使用者\\軟體\\Microsoft\\Office\\16.0\\Outlook\\選項\\一般\\DisableSupportBackstage 登錄機碼以允許隱藏支援的系統管理員選擇 [檔案] 索引標籤。
-   新增 HKEY\_目前\_使用者\\軟體\\Microsoft\\Office\\16.0\\Outlook\\選項\\一般\\DisableOutlookFeedbackFeatures 登錄機碼以允許關閉的系統管理員「 Outlook 2016 意見 」 及 「 Outlook 部落格"選項底下檔案\>意見反應。

### <a name="skype-for-business-security-updates"></a>Skype for Business： 月份的安全性更新
-   [CVE-2017年-0281年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)： Microsoft Office 程式碼執行弱點

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 的非安全性更新
-   修正問題導致開啟為標準的視窗，而不是自動接受交談的交談] 視窗最小化狀態，並預期地從其他 windows 取得焦點。

### <a name="word-security-updates"></a>Word： 安全性更新
-   [CVE-2017年-0254年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254)： Microsoft Office 記憶體損毀弱點
-   [CVE-2017年-0281年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)： Microsoft Office 程式碼執行弱點

### <a name="office-suite-security-updates"></a>Office 套件： 安全性更新
-   [CVE-2017年-0261年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261)： Microsoft Office 程式碼執行弱點
-   [CVE-2017年-0262年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262)： Microsoft Office 程式碼執行弱點
-   [CVE-2017年-0281年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)： Microsoft Office 程式碼執行弱點



## <a name="version-1701-april-11"></a>版本 1701年： 年 4 月 11 日
*版本 1701 （組建 7766.2076）*

### <a name="excel-non-security-updates"></a>Excel： 的非安全性更新
-   在新視窗出現的位置灰色.xls 活頁簿開啟時修正問題。

### <a name="outlook-security-updates"></a>Outlook： 安全性更新
-   [CVE-2017年-0106年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106)： Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2017年-0204年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204)： Microsoft Office 安全性功能旁路弱點

### <a name="outlook-non-security-updates"></a>Outlook： 的非安全性更新
-   修正問題其中使用者看見新"Microsoft Exchange"類型儲存在 「 新的 Outlook 資料檔"] 對話方塊中，選取 [這個新的資料類型會變成無法使用的使用者設定檔。

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 的非安全性更新
-   修正問題其中遺失錯誤映像發生於使用者執行 「 另存新檔 」 來儲存在抽取式媒體，例如 USB 縮圖磁碟機的 PowerPoint 檔案的替代位置。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 的非安全性更新
-   修正使用者是無法登入內部和外部的公司網路之間切換時所發生問題。

### <a name="office-suite-security-updates"></a>Office 套件： 安全性更新
-   [CVE-2017年-0199年](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199)： Microsoft Office/WordPad 遠端程式碼執行弱點 w/Windows API



## <a name="version-1701-march-14"></a>版本 1701年： 年 3 月 14
*版本 1701 （組建 7766.2071）*

### <a name="access-non-security-updates"></a>Access： 的非安全性更新
-   修正問題其中無法解除彈出式功能表。

### <a name="excel-security-updates"></a>Excel： 安全性更新
-   Microsoft 安全性公告[MS17 014](https://technet.microsoft.com/library/security/ms17-014)： Microsoft Office (3217868) 的安全性更新

### <a name="excel-non-security-updates"></a>Excel： 的非安全性更新
-   修正問題其中 Excel 可能會損毀插入超連結。
-   修正問題其中 Excel 可能會失敗時新增 XML 對應。
-   其中命令按鈕的增益集未作用中之增益集，以便在升級之後或移除和一次下載增益集來自 Office 市集後修正問題。
-   修正問題其中 Excel 可能會損毀操作透過 VBA 的 DLL 工作表。

### <a name="onenote-non-security-updates"></a>OneNote： 的非安全性更新
-   OneNote 頁面畫布停止回應按下滑鼠 Windows 10 版本 1607 (也稱為 Windows 紀念日 Update) 上使用 PIN 驗證後修正問題。
-   當使用者將插入的可編輯的文件，例如.docx 或.pptx 停用最佳化的 EDU 特有列印成品的行為。

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 的非安全性更新
-   修正問題合併衝突不正確時出現的位置的共同撰寫。
-   其中命令按鈕的增益集未作用中之增益集，以便在升級之後或移除和一次下載增益集來自 Office 市集後修正問題。
-   修正問題其中撥給 VBA 物件模型會導致執行階段錯誤時套用到圖表中的圖形。

### <a name="publisher-non-security-updates"></a>Publisher： 的非安全性更新
-   修正問題 Publisher 不會顯示 CMYK TIF 圖像的位置。

### <a name="skype-for-business-security-updates"></a>Skype for Business： 月份的安全性更新
-   Microsoft 安全性公告[MS17 013](https://technet.microsoft.com/library/security/ms17-013)： Microsoft 圖形元件 (4013075) 的安全性更新

### <a name="word-security-updates"></a>Word： 安全性更新
-   Microsoft 安全性公告[MS17 014](https://technet.microsoft.com/library/security/ms17-014)： Microsoft Office (3217868) 的安全性更新

### <a name="word-non-security-updates"></a>Word： 的非安全性更新
-   使用特定監視器組態時，與記憶體 consumptions 修正問題。
-   其中命令按鈕的增益集未作用中之增益集，以便在升級之後或移除和一次下載增益集來自 Office 市集後修正問題。



## <a name="version-1701-february-22"></a>版本 1701年： 年 2 月 22 日
*版本 1701 （組建 7766.2060）*

### <a name="excel-feature-updates"></a>Excel： 功能更新
-   **資料轉換] 和 [連線增強功能：** 展開清單將新文字欄與值之間的分隔字元並連線至 SQL 時指定容錯移轉] 選項。
-   **資料轉換] 和 [連線增強功能：** 現在已經支援百分比資料類型、 與二進位結合函數製作體驗目前已經強化功能。
-   **OLEDB 連接器：** 使用 OLEDB 連接器 Get 轉換中的建立資料匯入藉由指定連接字串以及選用的 SQL 陳述式來執行查詢。
-   **筆跡重新顯示：** 移至 [繪製\>筆跡重新顯示重新顯示手寫正向和回溯隱藏及顯示的內容，提供逐步指示，或更容易理解的其他人的想法流程。 [更多資訊](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **CSV (utf-8) 支援：** 開啟並使用 utf-8 字元編碼的 CSV 檔案的儲存位置。
-   **資料轉換和連線的增強功能：** 選取要匯入相關的資料表時載入資料的 OData 來源新增自訂欄值來自函數計算，或顯示查詢使用的專用的檢視之間的相依性。
-   **與我共用：** 查看其他人已移至 [檔案共用與您的文件\>開啟\>共用與我]。 [更多資訊](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **變更色彩：** 使用告訴我的色彩設定為字型、 醒目提示、 圖案填滿及其他。 [更多資訊](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="excel-security-updates"></a>Excel： 安全性更新
-   Microsoft 安全性佈告欄[MS16 148](https://technet.microsoft.com/library/security/ms16-148)： Microsoft Office (3204068) 的安全性更新

### <a name="excel-non-security-updates"></a>Excel： 的非安全性更新
-   修正的問題，當 Office 佈景主題設定為黑色，「 未預期的錯誤 」 時出現錯誤訊息以滑鼠右鍵按一下 [活頁簿的查詢] 窗格中的查詢。
-   當使用者嘗試存取樞紐分析表選項 Excel 當機修正問題。
-   修正問題其中雙引號括住的文字與儲存格的值不正確匯出為 CSV 或 CSV utf-8 儲存時。
-   修正問題 Excel 擱置或損毀時關閉的位置。
-   修正問題其中包含串連公式的超連結會略過串連結果的一部分。
-   修正問題貼上 Excel 表格 rtf 格式 (RTF) word 不出保留表格格式。
-   修正問題其中使用者無法另存新檔時執行活頁簿包含在 MS Excel 4.0 巨集表。
-   請 CTRL + ALT + 5 移動選取項目來比對其他應用程式的物件層級的捷徑。
-   修正的問題，當公式列中輸入及使用下拉式清單中，例如按 Enter 以完成該公式 VLOOKUP 函數最上層項目從選取 [自動] 下拉式清單，而不是 leavingthe 輸入的值為-是。
-   修正問題其中開啟 Excel 97-Excel 2003 二進位檔案格式 (BIFF8) 檔，包含受保護工作表中的超連結會使 Excel 認為該檔案已損毀和 Excel 會嘗試修復或移除無法讀取的內容。

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive for Business： 的非安全性更新
-   修正的問題，如果 GrooveIntlResource.dll 無法載入成功 （這是標準的情況下可能互不），Office 應用程式可能會損毀，則使用者會嘗試開啟或儲存檔案同步處理資料夾，如果使用者瀏覽至可以損毀 Windows 檔案總管使用 Windows 檔案總管中的同步處理的資料夾。
-   修正問題其中並未停用 OneDrive for Business，即使適當的登錄機碼設為停用，當 Office 設定為接收更新從非 Office 內容傳遞網路 (CDN) 的位置。

### <a name="onenote-feature-updates"></a>OneNote： 功能更新
-   **控制檔案和圖像的同步處理：** 移至 [檔案\>選項\>同步處理至控制項是否筆記本中的所有頁面的自動下載所有檔案及圖像。

### <a name="onenote-non-security-updates"></a>OneNote： 的非安全性更新
-   列印大於頁面映像時 OneNote 損毀修復問題。
-   修正問題其中使用者不能刪除自訂頁面範本。

### <a name="outlook-feature-updates"></a>Outlook： 功能更新
-   **上即時附件的共同作業：** 上傳至 OneDrive for Business，讓所有人處理最新版本的附件。 上傳或將其儲存在附件使用下拉式功能表。
-   **的摘要卡旅行社預定和套件：** 確認及追蹤差旅預定為套件傳遞，使用自動建立在 [收件匣] 和 [行事曆的摘要卡。 [更多資訊](https://blogs.office.com/2016/06/28/stay-on-top-of-your-travel-and-deliveries-with-outlook/)
-   **編輯器：** 提供進階、 關聯式校訂以協助提升的撰寫。 [更多資訊](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

### <a name="outlook-non-security-updates"></a>Outlook： 的非安全性更新
-   修正的問題，當以滑鼠右鍵按一下清單中的附件的附件進行交談，所有的快顯功能表項目是隱藏狀態，而不是只適用於功能表項目。
-   修正問題 Rtf 格式 (RTF) 電子郵件訊息其中無法開啟由收件者若使用資訊版權管理傳送郵件。

### <a name="powerpoint-feature-updates"></a>PowerPoint： 功能更新
-   **關閉標題：** 如果在投影片包含已關閉標題的影片，可以在投影片放映中播放標題。
-   **多個音訊追蹤：** 如果在投影片包含具有多個音訊追蹤的影片，可以在投影片放映中播放追蹤。
-   **區段複製：** 複製並貼上各節之間的簡報。
-   **與我共用：** 查看其他人已移至 [檔案共用與您的文件\>開啟\>共用與我]。 [更多資訊](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **筆跡重新顯示：** 重新顯示手寫正向和回溯隱藏和顯示內容、 提供逐步指示，或更容易理解的其他人的想法流程。 [更多資訊](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **更好的錄製：** 建立組成錄製張投影片螢幕錄製並插入的影片、 簡報，然後共用該記錄的內容從遠端檢視。 您也可以內嵌測驗協助進行遠端學習並讓您的簡報以及變更多互動式筆跡色彩及使用記錄旁白和音訊的簡化控制項。
-   **Designer 增強功能：** 提供使用 SmartArt 項目符號的程序清單的設計建議。
-   **錄製功能區索引標籤：** 自訂功能區以新增 [錄製] 索引標籤。
-   **變更色彩：** 使用告訴我的色彩設定為字型、 醒目提示、 圖案填滿及其他。 [更多資訊](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)
-   **縮放：** 建立您的簡報互動式摘要的自動導覽連結。 [更多資訊](https://support.office.com/article/9d6c58cd-2125-4d29-86b1-0097c7dc47d7)
-   **開啟超連結：** 使用 CTRL + 按一下即可編輯簡報時開啟超連結。
-   **文字反白顯示：** 使用文字螢光吸引重要的文字。

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 的非安全性更新
-   其中，當裁剪映像，映像的已裁剪的部分出現深色修正問題。
-   修正的問題，在投影片放映模式] 與 [朗讀程式執行時，當使用者按一下超連結及網站上的 PowerPoint 當機次數載入很慢。
-   修正問題其中即時輸入 coauthoring 時不會使用表格。
-   修正的位置，具有 Malwarebytes 3.0 安裝在電腦上開啟 PowerPoint 時, 出現 「 已停止工作 」 錯誤或 PowerPoint 在發生問題。
-   修正問題的預設範本不會出現 [檔案的位置\>新增]。
-   修正問題其中輸入的文字是中斷而延遲已經內嵌字型檔案時自動儲存。
-   與可擴充的向量圖形 (SVG) 圖像複製到 Adobe Illustrator 修正問題。

### <a name="project-feature-updates"></a>專案： 功能更新
-   **鎖定欄位：** 將值設定為 [是]，防止小組成員提交任務更新。
-   **時間表標籤：** 使用標籤來授與描述性名稱區分時間表長條圖。
-   **時間表進度指標：** 使用] 核取記號並彩色進度列顯示最以及 [時間表] 檢視中的每一項工作。
-   **協助工具功能改良：** 使用鍵盤、 [朗讀程式] 和其他輔助技術，閱讀並編輯專案的改良的支援。

### <a name="project-non-security-updates"></a>專案： 的非安全性更新
-   修正問題沒有連結線顯示時建立主專案和子專案之間的跨專案連結。
-   修正問題按照時段的基準值不一定儲存正確的 XML 格式以、 特別搭配使用和成本包含部分持續時間值。
-   修正的問題時套用的狀態更新、, 實際工時會新增至小組成員沒有報告的工作分派。
-   修正問題即使基準尚未已建立之資源的比較基準值的顯示資源的位置。
-   修正問題讓文字不是可見的預覽列印剪裁文字的位置。
-   修正問題時開啟從 SharePoint.mpp 檔案使用捷徑 URL，則檔案開啟為已取出，即使設定 「 需要它們可以編輯之前已取出的文件？ 」 已啟用。
-   從 Project Web Apps 用於材料資源更新不正確地變更時段式資料修正問題。
-   修正問題其中開啟專案的里程碑任務可能會新增實際開始時間日期至其即使無須在上次儲存的時間的日期。
-   修正問題與工作分解結構 (WBS) 並重新編號。
-   修正之專案損毀時不在方格檢視切換以及 [朗讀程式] 的問題。
-   修正問題其中不正確的錯誤訊息會顯示關於時段式資料截斷時開啟 XML 檔案。
-   修正問題其中儲存比較基準不正確地設定按照時段的值。
-   修正問題其中工作分派延遲就會略過從 XML 檔案中讀取專案資料。
-   修正的問題，從 Project Online 中開啟檔案時, 上次修改日期顯示 UTC 時間，而不是時區調整時間。
-   修正問題列印工作表] 檢視時分組色彩分隔寬線未顯示非分組資料列的位置。
-   修正問題其中修復] 選項不正確時顯示使用者會檢查具有超過最大單位問題的工作分派的任務。
-   修正其中大綱代碼欄位的值不能變更發佈專案之後發生問題。
-   修正問題其中甘特圖長條不大小 175%顯示在高 DPI 畫面上的正確。
-   修正問題其中使用者透過 [任務資訊] 對話方塊設定延遲時間，如果它不正確地設為 24 小時制的工期。
-   修正問題其中時開啟特定的 XML 檔案的任務開始日期未正確設定因為工作分派有問題。

### <a name="skype-for-business-feature-updates"></a>Skype for Business： 更新的功能
-   **Windows 通知樣式：** 變更的內送的通話和交談通知的外觀。 [更多資訊](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/New-Skype-for-Business-2016-on-Windows-Notifications-look-and/ba-p/39885)
-   **諮詢轉接：** 從內呼叫，請洽詢另一位使用者透過 IM 或電話之前傳送給該使用者的通話。 [更多資訊](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/Skype-for-Business-2016-on-Windows-Consultative-Transfer/ba-p/41122)
-   **麥克風通知：** 當麥克風設為靜音作業系統中或麥克風不會挑出任何音訊，[交談] 視窗中顯示的通知。
-   **停用 「 我的號碼 」：** 若要停用"My number"下撥號鍵台使用 DisableDisplayMyNumber 登錄項目。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 的非安全性更新
-   變更用來允許或拒絕參與者的文字 （X 或核取記號表示） 的圖像大廳按鈕。
-   變更會議提醒通知文字從"接受""加入"。
-   更新的 IM 寄件者收件者的狀態設為 [請勿打擾] 時顯示訊息。
-   更新時收件者已離線和"儲存歷程記錄 」 已停用，使其清除的 IM、 寄件者顯示的訊息收件者將不會收到訊息。
-   新增聊天歷程記錄和名冊中群組聊天之間移動垂直分割軸的功能。
-   新增調整大小的 IM] 或 [聊天室] 視窗中的索引標籤清單的功能。
-   新增選取搜尋建立主題摘要時的聊天室的功能。
-   修正問題訊息停止出現的聊天歷程記錄大西洋交談。
-   修正問題重複的訊息出現在 [交談] 視窗中的位置。
-   修正其中吐司通知動作 （接受並略過） 未正確顯示通知大量期間發生問題。
-   修正問題，使用者無法輸入其中一則訊息之後使用 Alt + tab 鍵來開啟 [最小化的交談] 視窗。
-   修正問題 IM] 按鈕會變為灰色出在使用者的連絡人卡片即使 IM 為可用。
-   修正問題其中多個交談視窗中不開啟回到其先前的大小和位置已經關閉並重新開啟。
-   修正問題其中自訂連結不時選取 [啟動]。
-   修正問題其中 [區域] 欄位中的線上會議文字不正確顯示非英文字元。
-   修正問題其中通知資訊，例如通話時間不正確地以呈現從右至左語言。
-   修正的問題，建立主題摘要時, 清除搜尋結果不會重設結果為已瀏覽過的會議室清單。
-   修正問題多個交談視窗中開啟時，同時適用於企業的 Skype 停止回應。
-   修正問題其中最後一個 [交談] 視窗變黑之後已關閉所有其他的索引標籤。
-   修正問題其中預設焦點時，無法在聊天室輸入] 區域中的公式會停用的分頁的交談。
-   修正問題其中"忘記您的電話撥入 PIN 嗎？ 」 連結不會出現在會議邀請。
-   在 [一般] 和 [音訊裝置頁面上修正的問題其中一些文字是裁剪，將會遭到截斷時使用高 DPI 螢幕顯示 175%或更高。
-   修正問題時電腦已暫停或繼續時沒有網路和電腦是"一律在、 永遠連線 (AOAC") 的電腦上的商務 Skype 損毀。
-   修正問題其中沒有麥克風中偵測到來電時使用 Polycom CX100 裝置。
-   修正問題其中例如選擇連結\\ \\servername 或 file:// IM 訊息中的會產生錯誤訊息而不是開啟該位置。
-   使用以位置為主路由，使用者無法進行或收到 PSTN 通話是因為伺服器會認為使用者的位置不是有效的 PSTN 通話其中虛擬桌面基礎結構 (VDI) 環境中修正問題。
-   變更使用者的狀態設為 [請勿打擾] 或簡報、 從時未接的郵件傳送的電子郵件的主旨行"未接的交談\<名稱\>"到"\<名稱\>傳送 Skype for Business 中的郵件。 」
-   啟動擷取第一次登入裝置上的時間戳記[普查資料](https://docs.microsoft.com/skypeforbusiness/legal-and-regulatory/data-collection-practices)來協助識別登入可靠性趨勢的一部分。
-   修正問題不某些監視器上具備設定視窗 10 版本 1607 (也稱為紀念日 Update) 會顯示共用次要監視器選項。
-   其中 Skype 商務當機次數時共享者會使用第 3 時將顯示比例都會共用內容的協力廠商的 RDP 實作修正問題。
-   修正問題當使用者按一下 [音訊通話虛擬桌面基礎結構 (VDI) 環境中的 [控制項] 按鈕上時不會出現的音訊控制台中的位置。
-   修正問題時使用者正在執行 Windows 7 和先、 共用的主要監視器，然後再切換共用第二個監視器的檢視器看到螢幕變黑的位置。
-   修正問題其中某些特殊字元，例如連字號 (&)、 無法輸入搜尋輸入的方塊或"今天有什麼新鮮事？ 」 區段] 方塊中。
-   修正的問題時有不顯示未讀取的數目的位置未接的 Im 離線。
-   其中 「 電子郵件邀請"範本提及 Lync，而不是 Skype 修正問題。
-   修正問題所在的行號遺漏撥號鍵台下方的"My Number"區域。
-   將滑鼠指標不所示在 IM 輸入區域在聊天室中傳送一則訊息之後修正問題。
-   修正問題時登入 Skype for Business 停止回應和有問題載入快取集區。
-   修正問題時登入和還原交談 for Business Skype 損毀。
-   修正問題時登入後繼續 for Business Skype 停止回應。
-   會議連結已停用如果在這兩個組織的 Exchange 伺服器已停用 TNEF 修正問題。
-   修正問題其中視訊通話無法重新移只有一個 IM 交談時。
-   白板上的文字註釋出都會遺失時為 PNG 檔案儲存在白板修正問題。
-   修正問題時輸入超過並列文字日文 IM 視窗中的第一行隱藏的位置。
-   修正問題其中 & 字元 (&) 不正確地以此名稱中有底線。
-   在排定的會議中的 「 加入線上會議 」 url 修正問題。
-   修正問題其中滑鼠停留在視窗不會啟動視窗即使作業系統設定若要這樣做。
-   修正問題其中傳出電話交談歷程記錄項目顯示來電者，而不是呼叫方。
-   修正問題之 F12 不會在本機上儲存交談。
-   其中的未接的交談電子郵件不包含初始 IM 修正問題。
-   其中 emoji 可以新增 IM 文字區域即使簡報者已停用 IM 參與修正問題。
-   使用 [鈴聲與音效] 選項] 對話方塊上的版面配置修正問題。
-   修正問題時關閉 [交談] 視窗的商務 Skype 損毀。
-   修正問題時網域註冊為虛名網域的 DNS 較不登入失敗時。
-   修正問題常設聊天室通知設定其不進行另存成或載入正確。
-   修正其中現有的對等交談視窗或聊天室不顯示即使並重新開啟交談設定登入之後發生問題。
-   修正問題靜音或解除靜音作用中的交談會使其他交談視窗中看起來像擁有未讀取的郵件。
-   修正設定媒體旁路的使用者是無法繼續來自 PSTN 閘道的通話他們將該來電放入保留之後所發生問題。
-   其中使用者會看到藍色方塊，而不是影片透過加入會議時更新 URL 時使用的第 3 協力廠商的 RDP 實作修正問題。
-   修正問題的 SIP 位址的使用者部分，而不吐司警示中的顯示名稱的顯示位置。
-   修正的問題，當 Skype for Business 連線至 SIP 伺服器連接埠 443 上與 proxy 伺服器 is present、 有大幅延遲登入程序中如果 proxy 不允許這類連線。 修正啟用新增下 HKEY EnableDetectProxyForAllConnections DWORD 登錄項目\_目前\_使用者\\軟體\\Microsoft\\UCCPlatform\\Lync，並將值設定為 1。
-   其中時使用的分頁的交談，按兩下 [] 索引標籤上，並啟動輸入有時會導致將焦點移至不同的索引標籤，並繼續在該交談] 視窗中輸入修正問題。
-   其中 Url 立即訊息中包含無法選取 [聊天歷程記錄] 視窗中使用鍵盤修正問題。
-   如果播放音效時檢視 IM 交談和某人輸入 」] 核取方塊已選取鈴聲與音效] 選項下其中聽到輸入聲音修正問題。
-   其中出現的對話方塊不使用螢幕助讀程式，例如 [朗讀程式] 時宣告該名修正問題。
-   修正問題其中第一個執行教學課程不能使用鍵盤導覽而無法讀取的螢幕助讀程式，例如 [朗讀程式]。
-   修正問題不會在高 DPI 設定向外工作列上顯示狀態圖示。
-   其中搜尋方塊中的 [清除欄位] 按鈕無法使用鍵盤選取修正問題。
-   修正問題其中使用者無法啟動會議邀請時從另一個集區中的使用者。
-   修正的問題本身新增至會議的使用者不正確地顯示以不同的使用者。
-   修正問題位置上的狀態變更通知的連絡人的顯示狀態圖示隱藏的來電轉接的主管。
-   修正問題不符 IM 視窗中的文字游標閃爍速率鍵盤屬性在 Windows 中設定。
-   修正問題其中螢幕助讀程式發佈群組交談不正確的連絡人名稱。
-   其中使用者無法使用鍵盤選取多名連絡人修正問題。
-   其中使用者相片無法加以擷取自 Exchange 修正問題。
-   修正問題其中 Skype 商務用戶端連線到 Skype Business server 在內部網路，而不是一個外部網路上時使用的直接存取使用者連線。
-   修正問題嘗試解析會議擁有者的名稱時 Skype 商務用戶端損毀。
-   其中變更設定時 for Business Skype 啟動或關閉 Windows 會導致 Skype 損毀的企業版 fix 發生問題。
-   修正問題時開啟常設聊天室中的參與者清單並嘗試移動鍵盤焦點放到參與者清單 for Business Skype 損毀。
-   修正其中 for Business Skype 上繼續當發生不未提供任何網路問題。

### <a name="visio-feature-updates"></a>Visio： 功能的更新
-   **資料庫模型增益集：** 使用增益集來建立現有資料庫以協助規劃新的資料庫或了一個現有的資料庫模型。 [詳細資訊](https://support.office.com/article/fb034862-acfc-45bc-88b2-f33d1e1f8614)，[下載增益集](https://go.microsoft.com/fwlink/p/?linkid=835953)
-   **協助工具功能改良：** 若要使用的圖案、 使用鍵盤、 [朗讀程式] 和其他輔助技術的改良的支援編輯與其他人，等等。
-   **協力廠商範本及圖表：** 瀏覽或搜尋的新範本及範例圖表可從選取的協力廠商內容提供者。 第三方提供者的名稱會列在縮圖。
-   **筆跡支援：** 使用您的畫筆或手指繪製並加上註解與新的繪圖] 索引標籤上的工具。

### <a name="word-feature-updates"></a>Word： 功能更新
-   **協助工具功能改良：** 使用鍵盤、 [朗讀程式] 和其他輔助技術，讀取及編輯文件的改良的支援。 [更多資訊](https://support.office.com/article/69aed572-336e-4722-a97e-23393cc481b2)
-   **編輯器：** 提供進階、 關聯式校訂以協助提升的撰寫。 [更多資訊](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)
-   **筆跡重新顯示：** 移至 [繪製\>筆跡重新顯示重新顯示手寫正向和回溯隱藏及顯示的內容，提供逐步指示，或更容易理解的其他人的想法流程。 [更多資訊](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **編輯與自然畫筆手勢：** 環繞選取並刪除交叉指向文件進行變更。 [更多資訊](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)
-   **與我共用：** 查看其他人已移至 [檔案共用與您的文件\>開啟\>共用與我]。 [更多資訊](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **變更色彩：** 使用告訴我的色彩設定為字型、 醒目提示、 圖案填滿及其他。 [更多資訊](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="word-non-security-updates"></a>Word： 的非安全性更新
-   修正問題其中檢視一個文件以閱讀模式會防止 TAB 鍵正檢視的整頁模式中的第二個文件中使用。
-   修正問題載入一個以上的文法檢查文件庫時 Word 損毀。
-   修正的問題有著色的筆劃其中兩個或三個筆劃後消失。
-   以引號消失時使用 Google 輸入法 (IME) 修正問題。
-   使用者無法使用筆跡具有內容控制項或不連續的選取項目會進行修正問題。

### <a name="office-suite-feature-updates"></a>Office 套件： 更新的功能
-   **提供意見反應：** 建議的新功能或告訴 Microsoft 您想要或項目無法正常運作移至檔案\>意見反應

### <a name="office-suite-security-updates"></a>Office 套件： 安全性更新
-   Microsoft 安全性佈告欄[MS16 148](https://technet.microsoft.com/library/security/ms16-148)： Microsoft Office (3204068) 的安全性更新

### <a name="office-suite-non-security-updates"></a>Office 套件： 的非安全性更新
-   修正問題其中德文鍵盤上使用 CTRL + ALT + 7 或 CTRL + ALT + 8 會開啟使用者的意見反應工具，而不是插入適當的字元。
-   修正問題 TraceLogging 使損毀時安裝或更新 Office 的 Windows 7 上的位置。
-   其中，當使用筆跡繪圖和使用滑鼠放開滑鼠按鈕造成稍微移動筆跡修正問題。
-   修正的問題，Office 文件中插入影像 SVG、 後 SVG 映像或隱藏當文件，儲存並重新開啟。
-   修正問題其中 Office 期間啟用非英文使用者會顯示下列錯誤訊息： 「"產品金鑰的長度上限是 25 個字元。
-   修正問題的可能會造成停止運作或不正確地顯示 frames 疊置順序的 VBA 表單。
-   修正問題其中 trigged System Center Configuration Manager 更新 UpdateChannel 設定變更登錄中為某個項目不是有效的更新通道。



## <a name="version-1609-january-10"></a>版本 1609年： 年 1 月 10 日
*版本 1609 （組建 7369.2102）*

附註： 不適用於此通道版本的 Word 版本的 Microsoft 安全性公告[MS17 002](https://technet.microsoft.com/library/security/ms17-002)的安全性更新。

### <a name="excel-non-security-updates"></a>Excel： 的非安全性更新
-   修正問題其中使用編輯量值] 對話方塊會導致 Excel 損毀。

### <a name="powerpoint-non-security-updates"></a>PowerPoint： 的非安全性更新
-   修正問題其中圖形使用有時會導致 PowerPoint 損毀。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business： 的非安全性更新
-   修正問題不某些監視器上具備設定視窗 10 版本 1607 (也稱為紀念日 Update) 會顯示共用次要監視器選項。
-   其中 Skype 商務當機次數時共享者會使用第 3 時將顯示比例都會共用內容的協力廠商的 RDP 實作修正問題。
-   修正的問題，當 Skype for Business 連線至 SIP 伺服器連接埠 443 上與 proxy 伺服器 is present、 有大幅延遲登入程序中如果 proxy 不允許這類連線。 修正啟用新增下 HKEY EnableDetectProxyForAllConnections DWORD 登錄項目\_目前\_使用者\\軟體\\Microsoft\\UCCPlatform\\Lync，並將值設定為 1。

### <a name="word-non-security-updates"></a>Word： 的非安全性更新
-   修正的問題時使用 InsertXML 方法，中斷的圖片連結的版面配置區顯示的位置，而不是實際的圖像。

