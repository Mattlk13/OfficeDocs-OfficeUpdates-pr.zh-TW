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

 ### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935)：Microsoft Excel 遠端程式碼執行弱點

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：使用者使用巨集開啟 Office 2007 或較舊的活頁簿 (.xls 或 .xla) 時，會看到不正確的「重大失敗」錯誤訊息。
-   修正此問題：從命令列開啟活頁簿可能會導致儲存格中的 RTF 格式遺失。

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939)：Microsoft Office 資訊洩漏弱點

### <a name="powerpoint-security-updates"></a>PowerPoint：安全性更新
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934)：Microsoft PowerPoint 資訊洩漏弱點

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正此問題：專案層級自訂欄位的資料可能在儲存時遺失。
-   修正此問題：儲存失敗會導致檔案損毀，並造成專案在開啟時當機。
-   修正此問題：開啟專案計劃可能會導致當機。

### <a name="word-security-updates"></a>Word：安全性更新
-   [Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新



## <a name="version-1708-november-14"></a>版本 1708年： 年 11 月 14
*版本 1708 （組建 8431.2110）*

### <a name="access-non-security-updates"></a>Access：非安全性更新
-   修正此問題：嘗試在文字方塊或下拉式方塊中選取文字似乎會選取所有文字，而不是表示選取範圍。

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877)：Microsoft Excel 安全性功能略過的弱點
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878)：Microsoft Excel 記憶體損毀弱點
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884)：Microsoft Office 記憶體損毀弱點

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：在檔案名稱包含方括弧時，使用者無法在受保護的檢視中關閉活頁簿。
-   修正此問題：當使用者嘗試在現有的活頁簿中插入物件時，Excel 會在使用者按一下 [瀏覽] 時損毀。
-   修正此問題：選取 [調整圖形大小以修正文字] (在 [圖形格式] 窗格的 [文字選項]/[文字方塊] 部分中)，結果圖形不變。
-   修正此問題：在活頁簿上按兩下以開啟活頁簿時，不會載入儲存格的文字字型和格式，或兩個完全相同的活頁簿會針對一個範本開啟。
-   修正此問題：開啟或建立新的活頁簿時，在 Excel 啟動時所建立的第一個活頁簿不會關閉。
-   修正此問題：在拖曳或拖曳填滿時，工具提示的放置位置沒有對齊。
-   修正此問題：使用 [檔案] \> [另存新檔] 來儲存活頁簿時，包含句點的檔案名稱在檔案儲存對話方塊中會出現空白或截斷。
-   修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。
-   修正轉譯問題：由於錯誤的圖形驅動程式而出現黑色線條和標頭。
-   修正此問題：在插入圖表後，Excel 毀損或無法儲存活頁簿。
-   修正此問題：分頁預覽中的分頁線位置不正確。

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：使用者看到郵件清單中的焦點會在刪除郵件時意外跳轉。
-   修正導致使用者在與附件互動時看到驗證提示的問題。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。
-   修正此問題：在表格中復原後編輯和格式化文字會導致 PowerPoint 毀損。
-   修正此問題：以 Flash Player 為基礎之 YouTube 內嵌程式碼的參考，導致開啟新視窗來播放影片。舊的內嵌程式碼現已升級為參考以 HTML5 為基礎的 YouTube 影片，以便正確地就地播放。

### <a name="word-security-updates"></a>Word：安全性更新
-   [Advisory 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020)：Microsoft Office 深度防禦更新

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：當使用者嘗試對商務用 OneDrive 上的現有文件執行 [另存新檔] 時，Word 會當機，並取消儲存作業或嘗試合併現有變更。
-   修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。
-   修正此問題：如果使用者在開啟 Word 後立刻瀏覽至 [插入] 索引標籤，Word 可能會停止回應。
-   修正此問題：按一下邊界之後，輸入字元時，字元會顯示在畫面左上角。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882)：Microsoft Office 記憶體損毀弱點

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正在動態 DPI 環境下的 Office 增益集中縮放與調整大小的問題。
-   修正此問題：即使目前已安裝 Office 365 ProPlus，Office 設定服務提供者 (CSP) 的 CurrentStatus 節點仍會傳回空字串。
-   修正此問題：因為同一部電腦上所有的 Office 應用程式版本會共用 .box 檔案，而導致 .box 檔案格式變更；該問題會影響同一部電腦上所安裝舊版 Office 的功能。
-   修正此問題：在使用共用電腦啟用的某些情況下，出現一則錯誤訊息，表示應用程式發生錯誤，以致無法正常運作並詢問使用者是否要執行修復。



## <a name="version-1708-october-10"></a>版本 1708年： 年 10 月 10 日
*版本 1708 （組建 8431.2107）*

### <a name="access-non-security-updates"></a>Access：非安全性更新
-   修正此問題：如果查詢與 Microsoft Dynamics 連結的資料表中的主索引鍵有聯接，則查詢不會執行。
-   修正此問題：Microsoft Dynamics 資料表中的貨幣值未顯示小數位數。

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：Excel 在開啟 XLL 檔案時損毀。
-   修正此問題：在頁面配置檢視中新增頁首或頁尾後，其儲存格的圖樣樣式無法正確呈現。
-   修正此問題：將樞紐分析表的副本貼上到另一個活頁簿可能會導致當機。
-   修正此問題：當選擇 [取代] 命令時，[尋找] 及 [取代] 對話方塊隨即開啟，但對話方塊的焦點位於 [尋找] 索引標籤，而不是 [取代] 索引標籤。
-   修正此問題：從比 SharePoint Server 2016 更早版本的 SharePoint Server 開啟活頁簿的 [活動] 窗格時，Excel 會當機。
-   修正此問題：當啟用一或多個 XLL 增益集時，Excel 會開啟並顯示一個空白視窗。
-   修正此問題：在已關閉的活頁簿中使用 [表單] 按鈕之後，Excel 會當機。
-   修正此問題：使用 SheetBeforeRightClick 事件時，插入與合併儲存格相交的資料行不會展開合併的儲存格。

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774)：Microsoft Outlook 安全性功能略過的弱點
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776)：Microsoft Outlook 資訊洩漏弱點

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：使用深灰色佈景主題時，「原則提示」中的「深入了解」連結無法顯示。
-   修正此問題：當使用者嘗試設定新帳戶，並且在未完成帳戶設定之前即關閉該視窗時，Outlook 會當機。
-   修正此問題：「標記為已讀取」時，「標記為未讀取」為群組的共用收件匣中的郵件選項。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：從比 SharePoint Server 2016 更早版本的 SharePoint Server 開啟簡報時，PowerPoint 會當機。

### <a name="word-security-updates"></a>Word：安全性更新
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826)：Microsoft Office 記憶體損毀弱點

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：從比 SharePoint Server 2016 更早版本的 SharePoint Server 開啟文件的 [活動] 窗格時，Word 會當機。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825)：Microsoft Office 遠端程式碼執行弱點

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正此問題：線上修復進度不會向使用者顯示。
-   修正此問題：Office 檔案屬性未顯示在 [檔案總管] 中。
-   修正此問題：開啟第二份文件時，Office 增益集按鈕會從功能區消失。
-   修正此問題：無法開啟某些名稱具有雙位元組字元的 VBA 模組。



## <a name="version-1708-september-12"></a>版本 1708年： 年 9 月 12 日
*版本 1708 （組建 8431.2079）*

### <a name="access-feature-updates"></a>Access：功能更新
-   **標籤名稱屬性：** 藉由使標籤與表單上的控制項相關聯來增強協助工具。
-   **編輯新項目變得更無障礙：** 您可以使用快速鍵盤快速鍵 (Ctrl + E) 從下拉式方塊或清單方塊編輯新項目。
-   **動態連接器：** 從 Microsoft Dynamics 匯入資料或連結到儲存在其中的資料。 [詳細資訊](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Salesforce 連接器：** 匯入資料或連結到儲存在 Salesforce 的資料。 [詳細資訊](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="excel-feature-updates"></a>Excel：功能更新
-   **「從範例新增資料行」增強功能：** 支援多個日期/時間、數學、和索引資料行轉換。
-   **效能改善：** Excel 能更快速地開啟具有多個工作表的複雜活頁簿，讓您可以使用大範圍的公式、篩選大量資料列，或更快地複製和貼上。
-   **插入線上圖片：** 用以選取影像和屬性資訊的新登陸頁面會隨著影像自動插入。
-   **Azure Data Lake Store 連接器：** 使用者現在可以從 Azure Data Lake Store 匯入資料。
-   **「從範例新增資料行」增強功能：** 支援建議、更多日期/時間作業及其他轉換。
-   **[資料] 索引標籤**：在 [資料] 索引標籤上的功能區按鈕，已重新排列成兩個新的群組：「取得與轉換資料」及「查詢與連線」。
-   **共用查詢**：將任何查詢定義匯出至 Office 資料庫連線 (ODC) 檔，然後在活頁簿之間共用或與其他人共用。
-   **載入資料：** 從查詢直接將資料載入到樞紐分析表或樞紐分析圖中，而不必將資料儲存到資料模型內。
-   **共用的檔案活動︰** 選擇檔案右上角的 [活動] 按鈕，以查看在商務用 OneDrive 或 SharePoint 中共用檔案的共用、編輯、重新命名或還原。
-   **安全連結：** 當使用者按一下連結時，Office 365 進階威脅防護 (ATP) 會檢查是否為惡意的連結。如果連結被視為惡意，系統就會將使用者重新導向至警告頁面而非原始的目標 URL。 [詳細資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **增強的資料匯入功能︰** 輕鬆地從各種來源匯入圖形資料。使用 [查詢和連線] 側邊窗格來管理活頁簿查詢和連線，並透過 ODC 檔與他人共用查詢。 [詳細資訊](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **共用檔案中的變更**：檢視誰在共用活頁簿中進行了變更，以及將活頁簿還原到舊版。 [詳細資訊](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **具有畫筆按鈕的套索工具：** 使用套索工具筆跡支援的數位畫筆按鈕，而不造訪功能區。

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632)：Microsoft Office 記憶體損毀弱點

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：展開或摺疊樞紐分析表時，Excel 暫時停止回應且樞紐分析表標頭移出螢幕。
-   修正此問題：從 Word 複製和貼上 Tab 分隔的文字時，會忽略索引標籤，導致文字無法被剖析成多個欄位。
-   修正此問題：開啟 [發佈為網頁] 對話方塊時，Excel 會當機。
-   修正此問題：使用來自 SQL Server Analysis Services 伺服器的資料，且 Excel 的地區設定和 SQL Server Analysis Services 伺服器的地區設定不同時，資料重新整理不成功或 Excel 當機。
-   修正此問題：當嘗試儲存與 OneDrive 用戶端同步的文件變更時出現錯誤。
-   修正此問題：當「篩選」區域中有 PivotTable，其他地方並沒有任何欄位時，無法在工作表中進行任何變更。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **協助工具的改善：** 我們讓您在使用螢幕助讀程式時，能夠容易地閱讀及編輯電子郵件中的文字、表格、清單和圖像。
-   **新帳戶設定：** 使用新的精靈設定新帳戶，所需的手動步驟更少。
-   **附加連結的對話方塊：** 在功能區使用「附加檔案」附加連結時，您可以選擇要將其新增為連結或作為附件傳送。如果您不希望每次都看到此對話方塊，請移至 [檔案] \> [選項] \> [一般]，並指定想要在 [附件選項] 下附加連結的方式。
-   **內部部署附件的支援：** 內部部署 SharePoint 伺服器上的檔案會在 [訊息] \> [附加檔案] 下顯示為最近使用的檔案，而內部部署商務用 OneDrive 和 SharePoint 團隊網站會顯示在 [附加檔案] \> [瀏覽網頁位置]，此外本機檔案可以上傳至內部部署商務用 OneDrive 網站。
-   **群組的業務分類︰**  租用戶系統管理員定義的業務分類層級 (如機密)，可在建立或編輯群組時指派，且該分類會顯示在群組標題中。
-   **來賓存取 Office 365 群組︰** 透過授予存取組織對話、檔案、行事曆邀請和群組筆記本的存取權限，與組織外部的人員協同合作。 [詳細資訊](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **可採取的郵件：** 開發人員可以建立以方便使用者將無須切換至外部網站或個別 app[更多資訊](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)帶簡單或快速動作右從 Outlook 的郵件

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571)：Microsoft Office Outlook 安全性功能略過的弱點
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572)：Microsoft Office Outlook 資訊洩漏弱點
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663)：Microsoft Office Outlook 記憶體損毀弱點

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：無法在 Outlook 中設定 IMAP 帳戶。
-   修正此問題：開啟 Outlook 時會間歇性當機。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **插入線上圖片：** 用以選取影像和屬性資訊的新登陸頁面會隨著影像自動插入。
-   **影片的隱藏式輔助字幕：** 可將隱藏式輔助字幕新增至影片，使其變得更無障礙。 [詳細資訊](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **製作錄製的旁白︰** 當您錄製簡報時，可加入自己旁白的視訊。錄製可以包含動畫、筆跡、音訊和視訊。
-   **共用的檔案活動︰** 選擇檔案右上角的 [活動] 按鈕，以查看在商務用 OneDrive 或 SharePoint 中共用檔案的共用、編輯、重新命名或還原。
-   **Alt 文字建立︰** 雲端式服務會自動為簡報中的圖片產生替代文字。
-   **安全連結：** 當使用者按一下連結時，Office 365 進階威脅防護 (ATP) 會檢查是否為惡意的連結。如果連結被視為惡意，系統就會將使用者重新導向至警告頁面而非原始的目標 URL。 [詳細資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **設計工具改進功能：** 針對動作取向的清單提供專業的設計構想建議。
-   **共用檔案中的變更：** 檢視誰在共用簡報中進行了變更，以及將簡報還原到舊版。 [詳細資訊](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint：安全性更新
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742)：PowerPoint 遠端程式碼執行弱點
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743)：PowerPoint 遠端程式碼執行弱點

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：已連結字型的使用者定義字元 (EUDC) 無法顯示。

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正此問題：從 Project Online 開啟某些檔案會造成 Project Online 當機。
-   修正此問題：設定剩餘工時時，可能會錯誤清除「實際開始時間」。
-   修正此問題：「指派實際開始時間」顯示的資料，可能會與透過 Project Web App 中狀態的資源所回報的資料不同。
-   修正此問題：若變更工作的完成日期，則實際工時可能會重新排程。
-   修正此問題：如果您複製並貼上成本欄位，由於進位的問題，貼上的值可能與複製的值不完全符合。
-   修正此問題：從一個比較基準儲存到另一個基準時，不會複製預算資源的時段資料。
-   修正此問題：[狀態] 欄位對摘要任務的計算不一定正確。
-   修正此問題：當實際工時取代本機資源並啟用受保護的工時，實際工時會錯誤地轉移到企業資源。
-   修正此問題：如果您有一個資料表，其中第一欄是 [工作名稱]，該欄已被鎖定，而按一下工作會導致專案損毀。
-   修正此問題：您可以透過 [任務分派狀況] 檢視，將相同的資源多次指定至相同的工作。
-   修正此問題：開啟 XML 檔案時，數字自訂欄位的值可能會遺失。
-   修正此問題：最高層級任務縮排無法從 Project 正確同步到 SharePoint 工作清單。
-   修正此問題：如果您從 Excel 活頁簿匯入任務、資源或工作分派資訊，[工時] 欄位中的值可能會被忽略。
-   修正此問題：分時段的基準值不符合 (您將專案儲存為 XML 檔案格式時的) 初始值。
-   修正此問題：由於 Project 用戶端認為專案已簽出，因此不會開啟專案，但實際上並未簽出。
-   修正此問題：從高延遲的檔案伺服器開啟 Project 檔案，現在速度已加快。

### <a name="skype-for-business-security-updates"></a>商務用 Skype：安全性更新
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676)：Windows GDI + 資訊洩漏弱點
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695)：圖形元件資訊洩漏弱點
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696)：Microsoft 圖形元件遠端程式碼執行

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   新增對話方塊，說明特定連接埠被封鎖或 IP 未列入白名單時，使用者為何無法加入會議。
-   修正此問題：當您按一下 IM 交談分頁時，常設聊天室中的未讀訊息會標示成已讀。
-   修正此問題：傳入的 IM 快顯通知會發生幾秒延遲。
-   修正此問題：停用 Exchange 同步處理時，AD 連絡人會顯示為電話號碼，而不是連絡人名稱。
-   修正此問題：停用同盟且會議召集人未明確封鎖匿名加入時，匿名加入使用者會被封鎖而無法加入。
-   修正此問題：超過人數限制的會議中，對會議召集人顯示的受邀者數目不正確。
-   修正此問題：內送 PSTN 通話的快顯通知中不顯示電話號碼。
-   修正此問題：重新命名連絡人清單群組時，使用 Delete 鍵會刪除整個群組。
-   修正此問題：共用停止之前，會關閉 IM 交談中的共用通知。
-   修正此問題：某些非英文語言的登入畫面是空白的。
-   修正此問題：在聊天和聊天歷程記錄中的非英文字元是亂碼。
-   若使用者的名稱未知，則會顯示由組織的自動語音應答所處理的來電者電話號碼。
-   新增 Inband 設定，可選擇性地限制「這些人不需要在大廳中等候」中的「任何人 (沒有限制)」。
-   新增在 VDIv2 中 P2P 視訊呼叫己方視訊的開/關功能。
-   修正此問題：呼叫下拉功能表中連絡人會顯示重複的號碼。
-   修正此問題：在商務用 Skype 和商務用 Skype 基本版之間移動的使用者委派會遭到移除。
-   修正此問題：使用「啟用顯示為離線」和「自訂狀態 URL」用戶端原則時，會看不到 [顯示為離線]。
-   加寬 [加入會議] 按鈕，以修正某些當地語系化語言的截斷問題。
-   更加凸顯高重要性的訊息在聊天中的重要性。
-   在允許的檔案傳輸封鎖清單中新增 Office 和商務用 Skype 副檔名類型。
-   在設為非英文的 Outlook 會議邀請中，修正會議頁尾文字的當地語系化。
-   修正此問題：在多個使用者的情況下，對話中的傳送者名稱可能會切換。
-   修正此問題：在成功加入會議前，空白的對話視窗都不會出現。
-   修正此問題：若職稱欄位空白，則搜尋結果中連絡人卡片上的部門欄位資訊也會空白。
-   修正此問題：從內部部署移轉到線上的使用者，會因為防火牆規則而造成登入失敗。
-   新增新的 DWORD 登錄機碼來修正此問題：當使用者從執行 LyncAutoD 的外部網路登入用戶端，用戶端會將 OAuthUsed 登錄機碼重設為 False。若要修正此問題，請將 HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\> 下的 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 值設定為 1。

### <a name="visio-feature-updates"></a>Visio：功能更新
-   **從 Excel 資料製作圖表︰** 使用新的「資料視覺化工具」範本，從 Excel 資料自動建立「基本流程圖」或「交互功能流程圖」。 [詳細資訊](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **安全連結：** 當使用者按一下連結時，Office 365 進階威脅防護 (ATP) 會檢查是否為惡意的連結。如果連結被視為惡意，系統就會將使用者重新導向至警告頁面而非原始的目標 URL。 [詳細資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio：非安全性更新
-   修正此問題：在檔案圖示或檔案名稱上按兩下以開啟 Visio 檔時，COM 增益集沒有收到文件開啟的事件。

### <a name="word-feature-updates"></a>Word：功能更新
-   **插入線上圖片：** 用以選取影像和屬性資訊的新登陸頁面會隨著影像自動插入。
-   **Alt 文字建立︰** 雲端式服務會自動為文件中的圖片產生替代文字 (Alt 文字)。
-   **共用的檔案活動︰** 選擇檔案右上角的 [活動] 按鈕，以查看在商務用 OneDrive 或 SharePoint 中共用檔案的共用、編輯、重新命名或還原。
-   **安全連結：** 當使用者按一下連結時，Office 365 進階威脅防護 (ATP) 會檢查是否為惡意的連結。如果連結被視為惡意，系統就會將使用者重新導向至警告頁面而非原始的目標 URL。 [詳細資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **共用檔案中的變更：** 檢視誰在共用文件中進行了變更，以及將文件還原到舊版。 [詳細資訊](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：載入 Grammarly 增益集時 Word 會意外關閉。
-   修正此問題：在某些情況下，嘗試復原雲端型檔案時 Word 會損毀。
-   修正此問題：無法旋轉繪圖畫布中圖形。
-   修正此問題：當輸入韓文時，母音和元音會不正確地分開。
-   將文件儲存為 PDF 格式 (儲存文件為版本 1.7 PDF)。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744)：Microsoft Office 記憶體損毀弱點

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正此問題：「新增功能」對話方塊無法顯示。
-   修正此問題：按一下 [繪圖] 索引標籤會造成部分使用者的應用程式損毀。
-   修正此問題：在其上有工具提示的「通用控制項」停留時，會造成應用程式損毀。
-   修正此問題：使用「通用控制項」時，出現授權錯誤訊息。
-   修正此問題：某些程式檔案簽章的方式發生問題，導致防毒程式標幟這些檔案，以及在 Windows 資訊保護 (WIP) 底下保護或存取資料的問題。
-   新增 support.to 可允許使用者在 64 位元版本的 Office 開啟含有 mscomctl.ocx 控制項的巨集檔案。
-   改善在 mscomctl.ocx 中使用之控制項的協助工具。
-   修正此問題：Ribbon 或快速存取工具列自訂對話方塊中缺少指令。



## <a name="version-1705-august-8"></a>版本 1705年： 2010 年 8 月 8 日
*版本 1705 （組建 8201.2171）*

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：拖曳捲軸以移動郵件清單。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正此問題：某些程式檔案簽章的方式發生問題，導致防毒程式標幟這些檔案，以及在 Windows 資訊保護 (WIP) 底下保護或存取資料的問題。
-   修正此問題：「新增功能」對話方塊無法顯示。



## <a name="version-1705-july-27"></a>版本 1705年： 年 7 月 27 日
*版本 1705 （組建 8201.2158）*

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：當嘗試儲存與 OneDrive 用戶端同步的文件變更時出現錯誤。
-   修正此問題：將工作表資料新增到資料模型中，且高對比佈景主題設定為黑色時 Excel 發生當機。

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571)：Microsoft Office Outlook 安全性功能略過的弱點
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572)：Microsoft Office Outlook 資訊洩漏弱點
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663)：Microsoft Office Outlook 記憶體損毀弱點

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：另一位使用者變更版面配置後，新增圖形會造成合併失敗。

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：當輸入韓文時，母音和元音會不正確地分開。
-   修正此問題：信封上收件者地址列印的位置太靠近左側邊緣。



## <a name="version-1705-july-13"></a>版本 1705年： 年 7 月 13 日
*版本 1705 （組建 8201.2136）*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502)：Microsoft Office 記憶體損毀弱點

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：包含外部連結的活頁簿導致 Excel 當機。
-   修正此問題：將儲存格從 Excel 貼到 Word 時，即使未選取「在具有零值的儲存格顯示零」設定，儲存格仍顯示為零。

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正此問題：在圖表/資料表窗格中，看不到為圖表/資料表選取的值。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正此問題：加入會議且使用者看到音訊裝置加入對話方塊時，交談視窗沒有在背景顯示。
-   修正此問題：Outlook 的會議連結不一定會傳遞正確的內部 URI。
-   擴大 [加入會議] 按鈕，以修正某些當地語系化語言的截斷問題。

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：執行某些動作之後，資料表無法正確顯示。
-   修正此問題：多次編輯引文有時候會導致其顯示為單一復原動作，而不是連續的個別動作。
-   修正此問題：執行某些動作之後，復原動作被停用。
-   修正問題以防止執行某些復原動作之後可能造成資料遺失。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570)：Microsoft Office 遠端程式碼執行弱點

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正此問題：在使用 System Center Configuration Manager 時，會導致 Office 2013到 Office 2016 的自動升級失敗。
-   修正此問題：透過公司目錄從市集部署的舊版增益集不會載入。



## <a name="version-1705-june-13"></a>版本 1705年： 年 6 月 13 日
*版本 1705 （組建 8201.2102）*

### <a name="access-feature-updates"></a>Access：功能更新
-   **[新增功能] 對話方塊：** 在 Access 更新了新功能之後開啟 Access 時，會出現醒目提示新的 Access 功能對話方塊。您也可以使用 [檔案] \> [帳戶] \> [新增功能] 來開啟對話方塊。
-   **大型數字 (bigint) 支援︰** 使用 Access 表格中的大型數字資料類型來計算大型數字，並且連結至或從使用相同資料類型 (例如 SQL Server 中的 bigint) 的外部資料庫匯入。 [詳細資訊](https://blogs.office.com/2017/03/06/new-in-access-2016-large-number-bigint-support/)

### <a name="excel-feature-updates"></a>Excel：功能更新
-   **Windows 資訊保護 (WIP) 支援：** Excel 現在是已啟用的應用程式，而且可以區別公司與個人資料，根據設定的原則來正確判斷要保護的資料。 [詳細資訊](https://aka.ms/wiptechnet)
-   **「取得與轉換」功能的改善︰** 在查詢編輯器中，藉由提供範例值來建立新資料行。隨著您鍵入，Excel 會偵測所需的轉換並顯示新資料行的預覽。
-   **插入最近的連結︰** 輕鬆地將超連結附加到最近使用的雲端型檔案或網站，並使用螢幕助讀程式為使用者建立有意義的顯示名稱。 [詳細資訊](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **個人化預設樞紐分析表版面配置︰** 依您喜好的方式設定樞紐分析表，並在每次建立新的樞紐分析表時，以該版面配置開始作業。 [詳細資訊](https://support.office.com/article/efd8569c-f07a-43c1-9db2-4f2912a0f94e)
-   **取得與轉換功能的改善︰** 使用者可以依範例建立新的欄，並將表格欄分割成列。指定 SAP HANA 參數以及分組資料現在簡單許多。
-   **增益集的集中式部署**：系統管理員可以從 Office 365 系統管理中心部署並更新使用者或群組的增益集。 [詳細資訊](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **快速存取工具列自訂：** 下標和上標圖示可以新增至快速存取工具列。
-   **取得與轉換功能的改善︰** 使用「查詢編輯器」分割資料行時自動偵測分隔符號字元，選擇要與合併二進位檔一起使用的範例檔案，並指定使用 DB2 連接器時要連線的封裝集合。
-   **杜拜字型：** 支援西歐語系以及使用阿拉伯文字集為主要語言的字型系列。 [詳細資訊](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景移除：** 使用任意格式的繪圖工具移除圖片背景。
-   **取得與轉換功能的改善︰** 透過 ODCB 和 OLEDB 連接器使用 [導覽] 對話方塊中的「選取相關資料表」，直接從資料夾 [資料預覽] 對話方塊合併多個檔案，並且使用 [查詢編輯器] 視窗中的新內容功能表選項，在現有的查詢中插入新的步驟。
-   **使用畫筆來選取及變更物件︰** 使用數位畫筆選取物件控點，來調整大小、旋轉、移動以及執行更多動作。
-   **地圖圖表：** 比較數值及顯示跨地理區域的類別。 [詳細資訊](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)
-   **SVG 影像：** 插入並編輯活頁簿內的可縮放向量圖形 (SVG)。 [詳細資訊](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入圖示：** 使用來自標準程式庫的可縮放向量圖形 (SVG) 檔案之圖示，方式為移至 [插入] \> [圖例] \> [圖示]。 [詳細資訊](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **儲存至最近使用的資料夾︰** 在您移至 [檔案] \> [另存新檔] 時，使用 [最近] 索引標籤來儲存活頁簿至最近使用的資料夾。
-   **協助工具的改善：** 針對使用鍵盤、朗讀程式，以及其他輔助技術來讀取及編輯活頁簿的支援已獲改善。 [詳細資訊](https://support.office.com/article/51fcb17a-b15b-4b13-ae04-d4f38ece3f78)

### <a name="excel-security-updates"></a>Excel：安全性更新
-   Microsoft 資訊安全佈告欄 [MS17-014](https://technet.microsoft.com/library/security/ms17-014)：Microsoft Office 的安全性更新 (3217868)

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：以程式設計方式套用建立於 Excel 2010 或更早版本中的活頁簿時，Excel 不會設定工作表保護密碼。
-   修正此問題：在群組工作表中無法使用 [跨欄置中] 功能。
-   修正此問題：遺失 Office 2016 版本之後所引入的新功能 (例如 TEXTJOIN、CONCAT、IFS、MAXIFS 和 MINIFS)。
-   修正此問題：使用者嘗試套用儲存格層級權限時，發生 Excel 當機。
-   修正此問題：將大型檔案儲存到商務用 OneDrive 造成檔案鎖定，除非使用者關閉並重新開啟 Excel，否則無法編輯該檔案。
-   修正此問題：開啟 .xls 活頁簿時，新視窗會變成灰色。
-   修正此問題：插入超連結時，Excel 可能會當機。
-   修正此問題：新增 XML 對應時，Excel 可能會失敗。
-   修正此問題：升級增益集之後，或從 Office 市集移除並再次下載增益集後，增益集的指令按鈕無法運作。
-   修正此問題：透過 VBA 處理 DLL 工作表時，Excel 可能會當機。
-   修正此問題：在圖表工作表上選擇表單控制項下拉式方塊時，Excel 會發生當機。

### <a name="onenote-feature-updates"></a>OneNote：功能更新
-   **Windows 資訊保護 (WIP) 支援：** OneNote 現在是已啟用的應用程式，而且可以區別公司與個人資料，根據設定的原則來正確判斷要保護的資料。 [詳細資訊](https://aka.ms/wiptechnet)

### <a name="onenote-non-security-updates"></a>OneNote：非安全性更新
-   修正此問題：當畫面中有許多段落時，OneNote 畫布會隱藏內容或更新。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **Windows 資訊保護 (WIP) 支援：** Outlook 現在是已啟用的應用程式，而且可以區別公司與個人資料，根據設定的原則來正確判斷要保護的資料。 [詳細資訊](https://aka.ms/wiptechnet)
-   **插入最近的連結︰** 將超連結附加到最近使用的雲端型檔案或網站，並使用螢幕助讀程式為使用者建立有意義的顯示名稱。 [詳細資訊](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **杜拜字型：** 支援西歐語系以及使用阿拉伯文字集為主要語言的字型系列。 [詳細資訊](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景移除：** 使用任意格式的繪圖工具移除圖片背景。
-   **檢查共用檔案的存取權︰** Outlook 會事先告訴使用者，收件者可能無法存取附加的 OneDrive 或 SharePoint 檔案，並建議如何修正這個問題。
-   **設定附件的權限：** 針對 OneDrive 或 SharePoint 的附件，使用者可以設定收件者不論在組織內部或外部，是否有讀取或編輯文件的權限。
-   **可釘選的工作窗格：** 在信箱中切換郵件時，讓增益集工作窗格保持開啟。 [詳細資訊](https://blogs.msdn.microsoft.com/exchangedev/2017/01/26/pinnable-taskpane-in-outlook-2016/)
-   **SVG 影像：** 插入並編輯電子郵件內的可縮放向量圖形 (SVG)。 [詳細資訊](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入圖示：** 使用來自標準程式庫的可縮放向量圖形 (SVG) 檔案之圖示，方式為移至 [插入] \> [圖例] \> [圖示]。 [詳細資訊](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204)：Microsoft Office 安全性功能略過的弱點
-   [CVE-2017-8506](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8506)：Microsoft Office 遠端程式碼執行
-   [CVE-2017-8507](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8507)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-8508](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8508)：Microsoft Office 安全性功能略過的弱點

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：電腦的記憶體不足時，Outlook 瀏覽窗格會停止轉譯。
-   附件寬度視覺化展開以容納檔名及權限資訊。
-   修正此問題：使用者無法搜尋 PST 檔案。
-   修正此問題：使用者在 [新的 Outlook 資料檔] 對話方塊中看到新的 Microsoft Exchange 存放區類型，並選取這個新的資料類型，導致使用者設定檔無法使用。
-   修正此問題：從使用高 DPI 的電腦傳送時，訊息中的影像會遭到封鎖。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **Windows 資訊保護 (WIP) 支援：** PowerPoint 現在是已啟用的應用程式，而且可以區別公司與個人資料，根據設定的原則來正確判斷要保護的資料。 [詳細資訊](https://aka.ms/wiptechnet)
-   **插入最近的連結︰** 將超連結附加到最近使用的雲端型檔案或網站，並使用螢幕助讀程式為使用者建立有意義的顯示名稱。 [詳細資訊](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **增益集的集中式部署**：系統管理員可以從 Office 365 系統管理中心部署並更新使用者或群組的增益集。 [詳細資訊](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **杜拜字型：** 支援西歐語系以及使用阿拉伯文字集為主要語言的字型系列。 [詳細資訊](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景移除：** 使用任意格式的繪圖工具移除圖片背景。
-   **SVG 影像：** 插入並編輯簡報內的可縮放向量圖形 (SVG)。 [詳細資訊](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入圖示：** 使用來自標準程式庫的可縮放向量圖形 (SVG) 檔案之圖示，方式為移至 [插入] \> [圖例] \> [圖示]。 [詳細資訊](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **即時輸入時的共同撰寫：** 請參閱其中其他人所運作中的呈現方式和檢視變更為他們輸入。[更多資訊](https://support.office.com/article/0c30ee3f-8674-4f0e-97be-89cf2892a34d)
-   **儲存至最近使用的資料夾︰** 在您移至 [檔案] \> [另存新檔] 時，使用 [最近] 索引標籤來儲存簡報至最近使用的資料夾。
-   **建立精確的筆跡圖形︰** 請拖曳線段橡皮擦來移除多餘的筆跡像素，並向最接近的線段貼齊。
-   **使用畫筆來選取並操作物件︰** 使用數位畫筆來移動、調整大小或旋轉物件，使用它們的控點，或使用套索工具筆跡支援的畫筆按鈕。
-   **協助工具的改善：** 針對使用鍵盤、朗讀程式，以及其他輔助技術來讀取及編輯簡報的支援已獲改善。 [詳細資訊](https://support.office.com/article/3fce93f5-9ca8-42a6-bc1f-776749f6e32e)

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：如果 mfplat.dll 檔案未安裝在電腦上，則使用者在 [設計構想] 窗格中會使 PowerPoint 毀損。
-   修正此問題：升級增益集之後，或從 Office 市集移除並再次下載增益集後，增益集的指令按鈕無法運作。

### <a name="project-feature-updates"></a>Project：功能更新
-   **設定前置任務的快速下拉式清單︰** 您可以使用甘特圖下拉式清單選擇您想要連結至任務的前置任務或後續任務。
-   **任務摘要名稱︰**  顯示任務摘要任務名稱的唯讀任務欄位。  

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正了 [建立專案網站] 對話方塊，以顯示網站的正確位置；現在 Microsoft Project Online 中每個企業專案範本 (EPT) 都會有自己的專案網站 URL。
-   修正了 VBA BeforeClose 事件會在 [儲存] 提示之前觸發的問題，使您不需要以程式設計方式來判斷使用者對儲存提示的回應。
-   修正此問題：針對專案狀態日期之後所開始的工作，無法正確計算其 [實際完成百分比]。
-   修正此問題：成本與工時資源已指派給相同工作時，可能無法變更工作的狀態管理員。
-   修正此問題：在某些專案中，撫平整個專案可能會陷入無限迴圈。
-   修正此問題：有某些西班牙文的區域設定時，工作的開始和結束日期無法正確同步到 SharePoint 工作清單。
-   修正此問題：從 Project 用戶端初始狀態核准程序時，可能永遠無法完成，而使專案停留在不穩定的狀態。
-   修正此問題：版面上同時有中文和英文字的情況下，預覽列印無法正確配置工作名稱。
-   修正此問題：將時間表以個別圖形複製到 PowerPoint 時沒有作用。
-   修正此問題：「專案間的連結」對話方塊意外顯示值「找不到檔案」。
-   修正此問題：指派最大可用量為 0 的資源時，會產生不一致的結果。
-   修正此問題：在刪除工作分派的開始日期時，將任務的開始日期重設為「越快越好」，忽略前置任務之類的內容，而導致工作分派的前置分割。
-   修正此問題：如果透過「最近」功能表從 SharePoint 開啟檔案，即使已啟用「是否要求在編輯文件前先取出文件?」設定，專案仍會自動簽出。
-   修正此問題：如果直接進入「專案設定檔」應用程式，專案會發生當機。
-   修正此問題：對於從 Project 2013 進行升級的使用者，手動排定的任務無法正確更新。
-   修正此問題：從 SharePoint 任務清單開啟專案時，專案可能會當機，因為專案開始任務同步處理程序。
-   修正此問題：專案有時候會在建立小組時當機。
-   修正此問題：儲存專案時基準資訊會遺失。
-   修正此問題：大型專案計劃的列印成品難以閱讀。
-   修正此問題：在 Project Web App 中編輯的專案不會顯示公式欄位的正確值。
-   修正此問題：專案計劃的資源企業自訂欄位資訊不會正確儲存。
-   修正此問題：更新任務的工作完成百分比資訊也會更新任務的完成百分比資訊。
-   修正此問題：專案擁有權會在儲存專案時變更。
-   修正此問題：摘要任務的 CPI 會計算錯誤。
-   修正此問題：複製和貼上任務會攜帶基準資料並儲存資料，即便使用者不允許儲存受保護的基準資料。
-   修正此問題：從 Excel 匯入資料會導致任務及指派的日期資訊不正確。
-   修正此問題：開啟報告後，專案會在關閉時毀損。
-   修正此問題：自訂清單包含驗證設定時，專案會在儲存專案時停止運作。
-   修正此問題：在 [篩選器定義] 對話方塊中的 [測試] 欄中輸入「\>」字元不會正確解譯為「大於」的意義。
-   修正此問題：與「比較基準計劃」相關的進度線顯示。
-   修正此問題：自訂篩選器時，欄位名稱的下拉式清單不會出現。
-   修正此問題：長條圖樣式預覽不會出現在 [長條圖樣式] 對話方塊中。

### <a name="publisher-non-security-updates"></a>Publisher：非安全性更新
-   修正此問題：Publisher 不會顯示 CMYK TIF 影像。

### <a name="skype-for-business-feature-updates"></a>商務用 Skype：功能更新
-   **插入連結：** 將連結新增至 IM 與群組聊天中，並提供連結的易記文字而非完整的 URL。
-   **共用畫面的通知：** 在 IM 交談中共用畫面時，或在您離開會議之後仍繼續共用畫面時，對話視窗中所顯示的通知。該通知會提醒您仍在共用畫面，並方便您藉由「停止共用」按鈕來停止共用。
-   **Windows 資訊保護 (WIP) 支援：** 現在已支援商務用 Skype 作為「僅適用於 WIP (WIP Work Only)」應用程式。透過在您允許的應用程式清單中加入 Skype，向 Windows 指示其不處理個人資料。Windows 會代表商務用 Skype保護資料。 [詳細資訊](https://aka.ms/wiptechnet)
-   **密碼重設選項：** 當使用者至少登入失敗一次時，登入視窗會顯示 [重設] 按鈕連結。

### <a name="skype-for-business-security-updates"></a>商務用 Skype：安全性更新
-   Microsoft 資訊安全佈告欄 [MS17-013](https://technet.microsoft.com/library/security/ms17-013)：Microsoft 圖形元件 (3148522) 的安全性更新 (4013075)
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2017-0283](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0283)：Windows Uniscribe 遠端程式碼執行弱點
-   [CVE-2017-8550](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8550)：商務用 Skype 遠端程式碼執行弱點

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   變更了在原則停用音訊的情況下，嘗試呼叫使用者時所顯示的訊息，從「無法完成撥號」變更為「因為 IT 系統管理員已限制音訊而無法呼叫。請嘗試改用立即訊息或電子郵件，並要求洽詢 IT 系統管理員」。
-   對已啟用 PSTN 會議的商務用 Skype® Online 使用者，在其會議邀請中新增了「忘記您的撥入 PIN」超連結。
-   啟用從商務用 Skype® Online 加入 Teams 會議。
-   將預設的喇叭工作階段音量從 40% 變更為 75%。
-   允許將索引標籤清單的最小寬度調整為較小的大小。
-   更新了快速鍵以符合索引標籤的順序。
-   修正此問題：從行動裝置傳送時，希伯來文字的方向不正確。
-   修正此問題：螢幕助讀程式朗讀 [展示桌面/授與控制權] 功能的資訊時所發生的問題。
-   在「選取聊天室」清單中，除了顯示已瀏覽過的聊天室之外，還顯示開啟的聊天室。
-   新增功能，以在啟用自訂 RCC 應用程式時停用 VoIP 功能。
-   變更離線 IM 標語為「試用商務用 Skype 行動應用程式」。
-   修正此問題：自動接受交談的交談視窗沒有最小化，反而開啟為一般視窗，而意外將焦點轉移至其他視窗。
-   修正此問題：在 [Skype 會議選項] 對話方塊中使用螢幕助讀程式的問題。
-   修正此問題：邀請中的第一個訊息並未顯示在「未接的交談」電子郵件中。
-   修正此問題：在 Outlook 使用 [新增 Skype 會議] 按鈕建立會議邀請時，會顯示重複的撥打號碼。
-   修正此問題：垂直捲軸出現時，使用 Ctrl + A 全選時，不會選取 IM 記錄中的所有交談。
-   修正此問題：使用 Export-CsArchivingData Cmdlet 時，輸出文字的格式可能不相同。
-   修正此問題：會議召集人使用「立即開會」與 3 位以上的參與者開會時，無法看到遠端參與者的視訊。
-   修正此問題：使用者在參與者清單中，以滑鼠右鍵按一下其他使用者的名稱時，會議名冊的第一行是空白的。
-   修正此問題：在公司網路內部和外部之間切換時，使用者無法登入。
-   修正此問題：從 [諮詢轉接] 中的 IM 升級為音訊時，聊天區域無法關閉。
-   修正此問題：兩個端點同時使用響鈴時，快顯通知中的名稱會被截斷。
-   修正此問題：檔案名稱在檔案共用通知中被截斷。
-   為 [返回通話] 和 [轉接] 按鈕新增工具提示。
-   請在 [諮詢轉接] 視窗中保留所花費的時間給螢幕助讀程式，例如 [朗讀程式]。
-   新增選擇 IM 或來電作為諮詢轉接預設喜好的能力。
-   加入新的能力：進行諮詢的傳輸時，以滑鼠右鍵按一下 [傳輸] 按鈕可查看連絡人的電話號碼清單。
-   改善一般性錯誤訊息，使問題清楚明瞭：使用者有無效的授權，或尚未被指派授權。
-   修正此問題：當使用者與連絡人開始對話並加入其他連絡人時，並非所有連絡人都會顯示在對話視窗標題中。
-   修正此問題：朗讀程式不會讀出通知的第二行。
-   修正此問題：呼叫會傳送到 VOIP 而不是接受諮詢的號碼。
-   修正此問題：使用者在內容視窗中導覽時，朗讀程式宣告錯誤的資訊。
-   修正此問題：將滑鼠停留在白板上的註釋時，建立者和修改者的名稱不會出現。

### <a name="visio-feature-updates"></a>Visio：功能更新
-   **尋找協力廠商樣板︰** 搜尋選取的內容提供者所提供的協力廠商樣板。
-   **投影片的程式碼片段︰** 擷取 Visio 繪圖的程式碼片段，並將其匯出為 PowerPoint 投影片。 [詳細資訊](https://support.office.com/article/e7da404b-4208-49d1-9518-6fe1a4723657)

### <a name="word-feature-updates"></a>Word：功能更新
-   **Windows 資訊保護 (WIP) 支援：** Word 現在是已啟用的應用程式，而且可以區別公司與個人資料，根據設定的原則來正確判斷要保護的資料。 [詳細資訊](https://aka.ms/wiptechnet)
-   **插入最近的連結︰** 將超連結附加到最近使用的雲端型檔案或網站，並使用螢幕助讀程式為使用者建立有意義的顯示名稱。 [詳細資訊](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **增益集的集中式部署**系統管理員可以從 Office 365 系統管理中心部署並更新使用者或群組的增益集。 [詳細資訊](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **杜拜字型：** 支援西歐語系以及使用阿拉伯文字集為主要語言的字型系列。 [詳細資訊](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景移除：** 使用任意格式的繪圖工具移除圖片背景。
-   **並排：** 在整頁模式檢視中，將頁面如同一疊紙張般並排滑動以進行導覽。 [詳細資訊](https://support.office.com/article/21bfd0ff-0e1f-4c43-b188-8b36dfe6dcf4)
-   **使用畫筆來選取及變更物件︰** 使用數位畫筆選取物件控點，來調整大小、旋轉、移動以及執行更多動作。
-   **SVG 影像：** 插入並編輯文件內的可縮放向量圖形 (SVG)。 [詳細資訊](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **插入圖示：** 使用來自標準程式庫的可縮放向量圖形 (SVG) 檔案之圖示，方式為移至 [插入] \> [圖例] \> [圖示]。 [詳細資訊](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **儲存至最近使用的資料夾︰** 在您移至 [檔案] \> [另存新檔] 時，使用 [最近] 索引標籤來儲存文件至最近使用的資料夾。
-   **透過學習工具來改善閱讀：** 在閱讀模式中，透過調整字距、顯示音節之間的停頓，以及在大聲朗讀文件時，反白顯示每個字的新命令來提升閱讀技巧。 [詳細資訊](https://support.office.com/article/29efa413-e2da-4cac-b2a5-2defc6d34fd9)
-   **圖形辨識︰** 使用 [繪圖] \> [轉換為圖形] 自動將繪圖轉換成圖形。 [詳細資訊](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="word-security-updates"></a>Word：安全性更新
-   Microsoft 資訊安全佈告欄 [MS17-014](https://technet.microsoft.com/library/security/ms17-014)：Microsoft Office 的安全性更新 (3217868)
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2017-0292](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0292)：Windows PDF 遠端程式碼執行弱點 
-   [CVE-2017-8509](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8509)：Microsoft Office 遠端程式碼執行弱點  

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：使用者無法搜尋 PST 檔案。
-   修正此問題：使用者在 [新的 Outlook 資料檔] 對話方塊中看到新的 Microsoft Exchange 存放區類型，並選取這個新的資料類型，導致使用者設定檔無法使用。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199)：Microsoft Office/WordPad 遠端程式碼執行弱點與 Windows API
-   [CVE-2017-0260](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0260)：Microsoft Office 遠端程式碼執行
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2017-8510](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8510)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2017-8512](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8512)：Microsoft Office 遠端程式碼執行弱點



## <a name="version-1701-may-9"></a>版本 1701年： 年 5 月 9 日
*版本 1701 （組建 7766.2084）*

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：使用者會間歇性地看到郵件清單中的郵件選項會在刪除郵件時意外跳轉。
-   修正此問題：間歇性地當機。
-   新增 HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableSupportBackstage 登錄機碼，以允許系統管理員隱藏 [檔案] 索引標籤下的 [支援] 選項。
-   新增 HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableOutlookFeedbackFeatures 登錄機碼，以允許系統管理員關閉 [檔案 \> 意見反應] 下的「Outlook 2016 意見反應」和「Outlook 部落格」選項 。

### <a name="skype-for-business-security-updates"></a>商務用 Skype：安全性更新
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)：Microsoft Office 遠端程式碼執行弱點

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正此問題：自動接受交談的交談視窗沒有最小化，反而開啟為一般視窗，而意外將焦點轉移至其他視窗。

### <a name="word-security-updates"></a>Word：安全性更新
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)：Microsoft Office 遠端程式碼執行弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281)：Microsoft Office 遠端程式碼執行弱點



## <a name="version-1701-april-11"></a>版本 1701年： 年 4 月 11 日
*版本 1701 （組建 7766.2076）*

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：開啟 .xls 活頁簿時，新視窗會變成灰色。

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204)：Microsoft Office 安全性功能略過的弱點

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：使用者在 [新的 Outlook 資料檔] 對話方塊中看到新的 Microsoft Exchange 存放區類型，並選取這個新的資料類型，導致使用者設定檔無法使用。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：當使用者對儲存在抽取式媒體 (例如，USB 隨身碟) 上的 PowerPoint 檔案，執行 [另存新檔] 到其他位置時，發生影像遺失錯誤。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正此問題：在公司網路內部和外部之間切換時，使用者無法登入。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199)：Microsoft Office/WordPad 遠端程式碼執行弱點與 Windows API



## <a name="version-1701-march-14"></a>版本 1701年： 年 3 月 14
*版本 1701 （組建 7766.2071）*

### <a name="access-non-security-updates"></a>Access：非安全性更新
-   修正此問題：無法關閉飛出視窗功能表。

### <a name="excel-security-updates"></a>Excel：安全性更新
-   Microsoft 資訊安全佈告欄 [MS17-014](https://technet.microsoft.com/library/security/ms17-014)：Microsoft Office 的安全性更新 (3217868)

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：插入超連結時，Excel 可能會當機。
-   修正此問題：新增 XML 對應時，Excel 可能會失敗。
-   修正此問題：升級增益集之後，或從 Office 市集移除並再次下載增益集後，增益集的指令按鈕無法運作。
-   修正此問題：透過 VBA 處理 DLL 工作表時，Excel 可能會當機。

### <a name="onenote-non-security-updates"></a>OneNote：非安全性更新
-   修正此問題：在 Windows 10 版本 1607 (亦稱為「Windows 年度更新版」) 上使用 PIN 進行驗證後，OneNote 頁面畫布對滑鼠按鍵動作停止回應。
-   當使用者插入可編輯的文件，例如 .docx 或 .pptx 時，請停用最佳化的 EDU 特定列印成品行為。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：共同撰寫時，顯示合併衝突錯誤。
-   修正此問題：升級增益集之後，或從 Office 市集移除並再次下載增益集後，增益集的指令按鈕無法運作。
-   修正此問題：套用至圖表中的圖形時，呼叫 VBA 物件模型導致執行階段錯誤。

### <a name="publisher-non-security-updates"></a>Publisher：非安全性更新
-   修正此問題：Publisher 不會顯示 CMYK TIF 影像。

### <a name="skype-for-business-security-updates"></a>商務用 Skype：安全性更新
-   Microsoft 資訊安全佈告欄 [MS17-013](https://technet.microsoft.com/library/security/ms17-013)：Microsoft 圖形元件 (3148522) 的安全性更新 (4013075)

### <a name="word-security-updates"></a>Word：安全性更新
-   Microsoft 資訊安全佈告欄 [MS17-014](https://technet.microsoft.com/library/security/ms17-014)：Microsoft Office 的安全性更新 (3217868)

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：使用特定的監視器設定時會耗用記憶體。
-   修正此問題：升級增益集之後，或從 Office 市集移除並再次下載增益集後，增益集的指令按鈕無法運作。



## <a name="version-1701-february-22"></a>版本 1701年： 年 2 月 22 日
*版本 1701 （組建 7766.2060）*

### <a name="excel-feature-updates"></a>Excel：功能更新
-   **資料轉換與連線能力增強功能︰** 將清單展開到新的文字行，且值之間以分隔符號分隔，並在連線到 SQL 時指定容錯移轉選項。
-   **資料轉換與連線能力增強功能︰** 現在支援百分比資料類型，並增強二進位組合函數撰寫體驗。
-   **OLEDB 連接器：** 使用 [取得及轉換] 中的新 [OLEDB 連接器]，透過指定連接字串 (或者要執行的 SQL 陳述式) 來建立查詢以匯入資料。
-   **筆跡重播：** 移至 [繪圖] \> [筆跡重播]，可往前和往後重播手寫來隱藏和顯示內容、提供逐步指示，或進一步了解他人想法的流程。 [詳細資訊](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **CSV (UTF-8) 支援︰** 開啟和儲存使用 UTF-8 字元編碼的 CSV 檔案。
-   **資料轉換與連線能力增強功能︰** 選取此選項後，您可以在從 OData 來源載入資料時匯入相關表格、透過函數計算的值新增自訂欄，或使用專用檢視顯示查詢之間的相依性。
-   **與我共用的項目：** 移至 [檔案] \> [開啟] \> [與我共用的項目]，查看其他人與您共用的文件。 [詳細資訊](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **變更色彩：** 請使用 [操作說明搜尋] 來設定字型、醒目提示、圖形填滿等等。 [詳細資訊](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="excel-security-updates"></a>Excel：安全性更新
-   Microsoft 資訊安全佈告欄 [MS16-148](https://technet.microsoft.com/library/security/ms16-148)：Microsoft Office 的安全性更新 (3204068)

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：Office 佈景主題設定為黑色時，若在 [活頁簿查詢] 窗格中，以滑鼠右鍵按一下查詢時，會出現「未預期的錯誤」錯誤訊息。
-   修正此問題：使用者嘗試存取 [樞紐分析表] 選項時，Excel 發生當機。
-   修正此問題：儲存為 CSV 或 CSV UTF-8 格式時，無法正確匯出有文字的儲存格值和雙引號。
-   修正此問題：Excel 在關閉時停止回應或當機。
-   修正此問題：包含 concatenate 公式的超連結會忽略部分 concatenate 結果。
-   修正此問題：將 RTF 格式內的 Excel 表格貼到 Word 時，不會保留表格格式。
-   修正此問題：當活頁簿包含 MS Excel 4.0 巨集工作表時，使用者無法另存新檔。
-   請將 CTRL+ALT+5 設為移動選取範圍至物件圖層的快速鍵，以便與其他應用程式相符。
-   修正此問題：如果在資料編輯列輸入資料及透過下拉式清單使用函數，如 VLOOKUP，按下 Enter 鍵以完成公式時，會選取自動完成下拉式清單最上方的項目，而不是保留輸入值的原狀。
-   修正此問題：開啟 Excel 97 - Excel 2003 二進位檔案格式 (BIFF8) 的檔案時，若在其受保護的工作表中包含超連結，則 Excel 會認定該檔案損毀，而且 Excel 會嘗試修復或移除無法讀取的內容。

### <a name="onedrive-for-business-non-security-updates"></a>商務用 OneDrive：非安全性更新
-   修正此問題：如果系統無法成功載入 GrooveIntlResource.dll (通常不太可能發生)，將導致 Office App 在使用者嘗試開啟同步資料夾中的檔案或將檔案存入時當機，或 Windows 檔案總管在使用者使用它瀏覽至同步資料夾時當機。
-   修正此問題：Office 設定為從 Office 內容傳遞網路 (CDN) 以外的位置接收更新時，無法停用商務用 OneDrive，即使已設定適當的登錄機碼將其停用。

### <a name="onenote-feature-updates"></a>OneNote：功能更新
-   **控制檔案和影像的同步處理︰** 移至 [檔案] \> [選項] \> [同步]，控制是否自動下載筆記本中所有頁面的所有檔案和影像。

### <a name="onenote-non-security-updates"></a>OneNote：非安全性更新
-   修正此問題：列印比頁面大的影像時，OneNote 發生當機。
-   修正此問題：使用者無法刪除自訂頁面範本。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **對附件進行即時共同作業︰** 將附件上傳到商務用 OneDrive，讓每個人都能處理最新版本。使用附件上的下拉式功能表，來加以上傳或儲存。
-   **差旅預定以及封裝的摘要卡片︰** 使用在 [收件匣] 和 [行事曆] 中自動建立的摘要卡片，確認並追蹤差旅預定及封裝傳遞。 [詳細資訊](https://blogs.office.com/2016/06/28/stay-on-top-of-your-travel-and-deliveries-with-outlook/)
-   **Editor：** 提供進階與關聯式校訂，以協助改善書寫內容。 [詳細資訊](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：若在對話附件的附件清單中，以滑鼠右鍵按一下附件時，會看見所有的操作功能表項目，而不是只顯示適用的功能表項目。
-   修正此問題：如果郵件是使用資訊版權管理送出，收件者無法開啟 RTF 格式的電子郵件訊息。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **隱藏式輔助字幕︰** 如果投影片中所包含的視訊具有隱藏式輔助字幕，就可以在投影片放映時播放字幕。
-   **多個音軌：** 如果投影片中所包含的視訊具有多個音軌，就可以在投影片放映時播放音軌。
-   **複製區段︰** 複製並貼上簡報間的區段。
-   **與我共用的項目：** 移至 [檔案] \> [開啟] \> [與我共用的項目]，查看其他人與您共用的文件。 [詳細資訊](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **筆跡重播：** 往前和往後重播手寫可隱藏和顯示內容、提供逐步指示，或進一步了解他人想法的流程。 [詳細資訊](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **更好的錄製內容︰** 建立由錄製的投影片、螢幕錄製和插入的視訊所組成的簡報，然後分享該錄製的內容，以便從遠端檢視。您也可以內嵌測驗來協助進行遠端學習，並且讓您的簡報更具互動性，以及變更筆跡色彩和使用較簡單的控制項來記錄旁白和音訊。
-   **設計工具改進功能：** 提供將 SmartArt 使用於分項流程清單的設計建議。
-   **錄製功能區索引標籤︰** 藉由自訂功能區來新增 [錄製] 索引標籤。
-   **變更色彩：** 請使用 [操作說明搜尋] 來設定字型、醒目提示、圖形填滿等等。 [詳細資訊](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)
-   **縮放：** 使用自動導覽連結建立簡報的互動摘要。 [詳細資訊](https://support.office.com/article/9d6c58cd-2125-4d29-86b1-0097c7dc47d7)
-   **開啟超連結︰** 使用 CTRL+按一下以在編輯簡報時開啟超連結。
-   **文字醒目提示：** 使用文字螢光筆，以強調重要的文字。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：在裁剪影像時，所裁剪的影像部份會顯示為黑色。
-   修正此問題：在 [投影片放映] 模式下且正在執行 [朗讀程式] 時，若使用者按一下超連結而網站載入很慢，PowerPoint 會發生當機。
-   修正此問題：在共同撰寫時，即時鍵入無法在表格上使用。
-   修正此問題：在安裝 Malwarebytes 3.0 的電腦上開啟 PowerPoint 時，出現「停止運作」的錯誤或 PowerPoint 發生當機。
-   修正此問題：在 [檔案] \> [新增] 下，沒有出現預設的範本。
-   修正此問題：自動儲存有內嵌字型的檔案時，文字輸入中斷或延遲。
-   修正此問題：從 Adobe Illustrator 複製可縮放向量圖形 (SVG) 影像時，會發生問題。

### <a name="project-feature-updates"></a>Project：功能更新
-   **鎖定的欄位︰** 將值設定為 [是] 以防止小組成員提交工作的更新。
-   **時間表標籤：** 透過標籤以使用描述性名稱命名，以便區分各個時間表列。
-   **時間表進度指示器︰** 在時間表檢視上使用核取記號及彩色進度列，進而顯示您在各項工作上已花費多少時間。
-   **協助工具的改善：** 針對使用鍵盤、朗讀程式，以及其他輔助技術來讀取及編輯專案的支援已獲改善。

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正此問題：在主專案與子專案之間建立跨專案連結時，不會顯示連結線。
-   修正此問題：分時段的基準值不一定能正確儲存為 XML 格式，尤其是包含部分工期的工作和成本值。
-   修正此問題：在套用狀態更新時，實際工時會新增到小組成員沒有報告的工作分派中。
-   修正此問題：即使未對資源建立基準，該資源仍會顯示基準值。
-   修正此問題：預覽列印剪輯文字時看不到文字。
-   修正此問題：即使已啟用 [文件必須先簽出才能編輯嗎?] 設定，但在使用捷徑 URL 從 SharePoint 開啟 .mpp 檔案時，檔案仍會開啟為簽出狀態。
-   修正此問題：來自 Project Web Apps 的材料資源更新會以不正確的方式變更分時段資料。
-   修正此問題：開啟具有里程碑任務的專案時可能會在其中新增實際開始日期，即使專案在上次儲存時沒有此日期也是如此。
-   修正此問題：分工結構圖 (WBS) 重新編號。
-   修正此問題：從方格式檢視切換到其他類型的檢視，且已開啟 [朗讀程式] 時，Project 發生當機。
-   修正此問題：開啟 XML 檔案時，會顯示關於分時段資料截斷的不正確錯誤訊息。
-   修正此問題：儲存基準時，無法正確地設定分時段的值。
-   修正此問題：從 XML 檔案讀取專案資料時，會忽略工作分派延遲。
-   修正此問題：從 Project Online 開啟檔案時，[上次修改日期] 會顯示 UTC 時間而不是依照時區調整的時間。
-   修正此問題：列印工作表檢視時，不會針對非群組資料列顯示分組色彩橫紋。
-   修正此問題：使用者檢查具有超過最大單位指派問題的工作時，會顯示不正確的修復選項。
-   修正此問題：發佈專案之後，無法變更 [大綱代碼] 欄位的值。
-   修正此問題：在高 DPI 螢幕上使用 175% 顯示時，甘特圖長條調整大小不正確。
-   修正此問題：在使用者透過「工作資訊」對話方塊設定延隔時間時，系統會錯誤地設定成 24 小時制工期。
-   修正此問題：在開啟特定 XML 檔案時，由於指派的問題所致，工作開始日期位置無法正確設定。

### <a name="skype-for-business-feature-updates"></a>商務用 Skype：功能更新
-   **Windows 通知樣式︰** 來電和交談的通知外觀變更。 [詳細資訊](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/New-Skype-for-Business-2016-on-Windows-Notifications-look-and/ba-p/39885)
-   **諮詢轉接：** 從內呼叫，請洽詢另一位使用者透過 IM 或電話之前傳送給該使用者的通話。[更多資訊](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/Skype-for-Business-2016-on-Windows-Consultative-Transfer/ba-p/41122)
-   **麥克風通知︰** 當麥克風在作業系統中處於靜音狀態，或如果麥克風未挑選任何音訊，則在交談視窗中顯示通知。
-   **停用「我的號碼」：** 使用 DisableDisplayMyNumber 登錄項目來停用撥號鍵台下的「我的號碼」。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   變更用來准許或拒絕參與者的大廳按鈕，從文字變更為影像 (X 或核取記號)。
-   變更會議提醒通知文字，從 [接受] 變更為 [加入]。
-   更新收件者的狀態設為 [請勿打擾] 時，顯示給 IM 傳送者的訊息。
-   更新當收件者離線且 [儲存到歷程記錄] 停用時，顯示給 IM 傳送者的訊息，以讓其清楚知道收件者不會收到訊息。
-   新增功能，以在群組聊天的聊天記錄和名冊之間移動垂直分隔列。
-   新增功能，以調整 IM 或聊天室視窗中的索引標籤清單大小。
-   新增功能，以在建立主題摘要時選取所搜尋到的聊天室。
-   修正此問題：聊天記錄中間的交談不再出現訊息。
-   修正此問題：交談視窗中出現重複訊息。
-   修正此問題：出現大量通知時，無法正確顯示快顯通知動作 ([接受] 和 [忽略])。
-   修正此問題：使用者在使用 Alt + Tab 開啟已最小化的交談視窗後無法輸入訊息。
-   修正此問題：即使 IM 可用，但使用者的連絡人卡片中，IM 按鈕仍會變為灰色。
-   修正此問題：多個交談視窗在關閉並重新開啟後並不會開啟回到其先前的大小和位置。
-   修正此問題：自訂連結在選取時不會啟動。
-   修正此問題：在 [區域] 欄位中的線上會議文字不會正確顯示非英文字元。
-   修正此問題：在由右至左的語言中，通話持續時間等通知資訊不會正確呈現。
-   修正此問題：在建立主題摘要時，清除搜尋結果並不會將結果重設為已瀏覽過的聊天室清單。
-   修正此問題：同時開啟多個交談視窗時，商務用 Skype 發生當機。
-   修正此問題：一旦關閉所有其他的索引標籤，最後一個對話視窗就會變成空白。
-   修正此問題：停用 [分頁對話] 之後，預設的焦點不在聊天輸入區域中。
-   修正此問題：會議邀請中未出現「忘記您的撥入 PIN 嗎？」連結。
-   修正此問題：在 [一般] 和 [音訊裝置] 頁面上，使用高 DPI 的螢幕而顯示比例為 175%或更高時，某些文字會遭到裁剪而截斷。
-   修正此問題：當電腦是「永遠可用，永遠連線 (AOAC)」的電腦，若暫停電腦或在沒有網路的情況下繼續時，商務用 Skype 發生當機。
-   修正此問題：使用 Polycom CX100 裝置通話時，未偵測到麥克風。
-   修正此問題：在 IM 訊息中擇類似 \\\\servername 或 file:// 的連結時，會導致錯誤訊息而不會開啟位置。
-   修正此問題：在使用位置型路由的虛擬桌面基礎結構 (VDI) 環境中，使用者無法進行或接收 PSTN 通話，因為伺服器認為使用者位置不是有效的 PSTN 通話位置。
-   使用者狀態設定為 [請勿打擾] 或 [正在進行簡報] 時，將針對未接訊息而傳送的電子郵件主旨列，從「來自 \<name\> 的未接交談」變更為「\<Name\> 已在商務用 Skype 中傳送訊息給您。」
-   開始擷取裝置上第一次登入的時間戳記，做為 [普查資料的一部分，](https://docs.microsoft.com/skypeforbusiness/legal-and-regulatory/data-collection-practices) 以協助識別登入可靠性的趨勢。
-   修正此問題：在 Window 10 版本 1607 (也稱為「年度更新版」) 上，共用次要監視器的選項沒有在特定監視器設定中出現。
-   修正此問題：當共用者使用 RDP 的協力廠商實作並聚焦至共用內容時，商務用 Skype 發生當機。
-   修正此問題：在虛擬桌面基礎結構 (VDI) 環境內，當使用者在進行語音通話時按一下 [音訊控制項]面板但並未出現。
-   修正此問題：在使用者執行 Windows 7 時，首先共用了主要顯示器，接著切換為共用第二個顯示器，而檢視者看到黑色畫面。
-   修正此問題：在搜尋輸入方塊或「今日新鮮事？」區段方塊中，無法輸入特定符號 (例如：& 符號)。
-   修正此問題：當有未讀離線 IM 時，未讀計數不會顯示。
-   修正此問題：「以電子郵件邀請」範本提及了 Lync，而非 Skype。
-   修正此問題：在撥號鍵台下方的「我的號碼」區域內，缺少 LINE 號碼。
-   修正此問題：在聊天過程中，傳送訊息後滑鼠指標不會在 IM 輸入區域中顯示。
-   修正此問題：在登入商務用 Skype 時，當載入快取集區發生問題的時候，出現當機情況。
-   修正此問題：在登入商務用 Skype 並還原交談時當機。
-   修正此問題：在恢復後，登入商務用 Skype 時當機。
-   修正此問題：在雙方組織內的 Exchange Server 皆已停用 TNEF 的情況下，會議連結遭到停用。
-   修正此問題：若僅有一個進行中的 IM 交談，視訊通話無法重新啟動。
-   修正此問題：將白板內容儲存為 PNG 檔案時，白板上的文字注釋會消失。
-   修正此問題：在 IM 視窗中輸入兩行以上的日文字時，第一行會消失。
-   修正此問題：名稱中的 & 符號字元會錯誤地由底線字元所取代。
-   修正此問題：在已排程會議中的「加入線上會議」URL 所發生的問題。
-   修正此問題：即使已在作業系統內設定「將滑鼠暫留在視窗上方以啟動視窗」，仍然無法啟動視窗。
-   修正此問題：撥出電話交談歷程記錄項目中，顯示了來電者而非受話者。
-   修正此問題：按 F12 時無法將交談儲存在本機。
-   修正此問題：遺漏的交談電子郵件並未包含初始 IM。
-   修正此問題：即使簡報者已停用 IM 參與功能，仍可在 IM 文字區域新增 Emoji。
-   修正此問題：[鈴聲] 和 [聲音選項] 對話方塊的版面配置。
-   修正此問題：在關閉交談視窗時，商務用 Skype 發生當機情況。
-   修正此問題：當網域註冊為虛名網域時，無 DNS 的登入會失敗。
-   修正此問題：不會正確地儲存/載入常設聊天室通知設定。
-   修正此問題：即使已設置重新開啟交談的設定，在登入後，現有的端對端交談視窗或聊天室不會出現。
-   修正此問題：將作用中的交談靜音或取消靜音時，若其他交談視窗有未讀訊息，會使這些視窗顯示於畫面中。
-   修正此問題：已設定為略過媒體的使用者，在保留通話之後，無法透過 PSTN 閘道繼續通話。
-   修正此問題：在使用協力廠商的 RDP 實作時，當使用者透過 URL 加入會議時，會看到藍色方塊而不是影像。
-   修正此問題：SIP 位址的使用者部份會顯示，而非顯示快顯警示中的顯示名稱。
-   修正此問題：當商務用 Skype 透過連接埠 443 與 SIP 伺服器連線，且 Proxy 伺服器已存在時，如果 Proxy 不允許這些連線，則登入程序中會發生嚴重的延遲。透過在 HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync 下新增 EnableDetectProxyForAllConnections DWORD 登錄項目，並將值設為 1，可啟用修正程式。
-   修正此問題：如果使用分頁對話，在分頁上連按兩下並開始輸入文字時，有時候可能會造成焦點移至不同的分頁，然後繼續在該對話視窗中輸入文字。
-   修正此問題：使用鍵盤時，無法在聊天記錄視窗中選取立即訊息中所包含的 URL。
-   修正此問題：如果選取 [鈴聲] 和 [音效] 選項下方的 [檢視 IM 交談及有人正在輸入時播放音效] 核取方塊，應該會聽到輸入音效。
-   修正此問題：使用螢幕助讀程式 (例如 [朗讀程式]) 時，未宣告出現的對話方塊。
-   修正此問題：初次執行教學課程無法使用鍵盤進行瀏覽，而且螢幕助讀程式 (例如 [朗讀程式]) 無法進行讀取。
-   修正此問題：在 [高 DPI] 設定中，工作列顯示狀態圖示未調整。
-   修正此問題：無法使用鍵盤選取搜尋方塊中的清除欄位按鈕。
-   修正此問題：如果邀請來自另一個集區中的使用者，使用者無法啟動會議。
-   修正此問題：將自己新增至會議的使用者錯誤地顯示為不同的使用者。
-   修正此問題：老闆來電時，狀態變更通知上的連絡人顯示狀態圖示遭到隱藏。
-   修正此問題：IM 視窗中的文字游標閃爍率不符合 Windows 中的鍵盤內容設定。
-   修正此問題：螢幕助讀程式宣告群組交談中不正確的連絡人名稱。
-   修正此問題：使用者無法使用鍵盤選取多位連絡人。
-   修正此問題：無法從 Exchange 擷取使用者相片。
-   修正此問題：使用者使用直接存取進行連線時，商務用 Skype 用戶端會連線到內部網路上的商務用 Skype Server，而不是外部網路上的商務用 Skype Server。
-   修正此問題：商務用 Skype 用戶端在嘗試解析會議擁有人的名稱時當機。
-   修正此問題：在啟動或關閉商務用 Skype 時變更 Windows 設定，導致商務用 Skype 當機。
-   修正此問題：在常設聊天室中開啟參與者清單並嘗試將鍵盤焦點移到參與者清單時，商務用 Skype 當機。
-   修正此問題：商務用 Skype 在沒有網路可用的狀態下恢復執行時發生當機。

### <a name="visio-feature-updates"></a>Visio：功能更新
-   **資料庫模型化增益集︰** 使用增益集建立現有資料庫的資料庫模型，以協助您規劃新的資料庫或了解現有資料庫。 [詳細資訊](https://support.office.com/article/fb034862-acfc-45bc-88b2-f33d1e1f8614)、[下載增益集](https://go.microsoft.com/fwlink/p/?linkid=835953)
-   **協助工具的改善：** 使用鍵盤、朗讀程式以及其他輔助技術來使用圖形，以及與他人一起編輯等等的支援已獲改善。
-   **協力廠商範本和圖表：** 瀏覽或搜尋所選協力廠商內容提供者供應的新範本與範例圖表。協力廠商提供者的名稱會列在縮圖上。
-   **手寫筆跡支援︰** 使用您的手寫筆或手指來繪製，並以新的 [繪圖] 索引標籤上的工具來加上註解。

### <a name="word-feature-updates"></a>Word：功能更新
-   **協助工具的改善：** 針對使用鍵盤、朗讀程式，以及其他輔助技術來讀取及編輯文件的支援已獲改善。 [詳細資訊](https://support.office.com/article/69aed572-336e-4722-a97e-23393cc481b2)
-   **Editor：** 提供進階與關聯式校訂，以協助改善書寫內容。 [詳細資訊](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)
-   **筆跡重播：** 移至 [繪圖] \> [筆跡重播]，可往前和往後重播手寫來隱藏和顯示內容、提供逐步指示，或進一步了解他人想法的流程。 [詳細資訊](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **使用自然的畫筆筆勢進行編輯︰** 使用畫圈代表選取和畫叉代表刪除來變更文件。 [詳細資訊](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)
-   **與我共用的項目：** 移至 [檔案] \> [開啟] \> [與我共用的項目]，查看其他人與您共用的文件。 [詳細資訊](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **變更色彩：** 請使用 [操作說明搜尋] 來設定字型、醒目提示、圖形填滿等等。 [詳細資訊](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：以「閱讀模式」檢視一份文件時，會導致以「整頁模式」檢視的第二份文件中無法使用 TAB 鍵。
-   修正此問題：載入一個以上的文法檢查資料庫時，Word 發生當機。
-   修正此問題：在繪製兩到三條筆跡線條後，發生線條消失的情況。
-   修正此問題：使用 Google 輸入法 (IME) 時，發生引號消失的情況。
-   修正此問題：使用者無法搭配使用筆跡與內容控制項，或無法在進行非連續選取時使用筆跡。

### <a name="office-suite-feature-updates"></a>Office 套件：功能更新
-   **提供意見反應：** 前往 [檔案] \> [意見反應]，提供新功能建議或告訴 Microsoft 您喜歡的功能或無法使用的功能

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   Microsoft 資訊安全佈告欄 [MS16-148](https://technet.microsoft.com/library/security/ms16-148)：Microsoft Office 的安全性更新 (3204068)

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正此問題：在德文鍵盤上使用 CTRL + ALT + 7 或 CTRL + ALT + 8 時，會開啟使用者意見反應工具，而非插入適當的字元。
-   修正此問題：在安裝或更新 Office 時，TraceLogging 會在 Windows 7 上造成當機。
-   修正此問題：使用滑鼠並以筆跡繪圖時，放開滑鼠按鈕時會導致筆跡稍微偏移。
-   修正此問題：在 Office 文件中插入 SVG 影像後，SVG 影像會在儲存和重新開啟文件時消失。
-   修正此問題：非英文版使用者在啟動 Office 期間，顯示下列錯誤訊息：「產品金鑰的最大長度為 25 個字元。」
-   修正此問題：VBA 表單造成框架圖層順序停止運作或顯示不正常的情況。
-   修正此問題：由 System Center Configuration Manager 觸發的更新會將登錄中的 UpdateChannel 設定變更成某個無效的更新通道。



## <a name="version-1609-january-10"></a>版本 1609年： 年 1 月 10 日
*版本 1609 （組建 7369.2102）*

附註： 不適用於此通道版本的 Word 版本的 Microsoft 安全性公告[MS17 002](https://technet.microsoft.com/library/security/ms17-002)的安全性更新。

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：使用 [編輯量值] 對話方塊會造成 Excel 當機。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：使用圖形有時會造成 PowerPoint 當機。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正此問題：在 Window 10 版本 1607 (也稱為「年度更新版」) 上，共用次要監視器的選項沒有在特定監視器設定中出現。
-   修正此問題：當共用者使用 RDP 的協力廠商實作並聚焦至共用內容時，商務用 Skype 發生當機。
-   修正此問題：當商務用 Skype 透過連接埠 443 與 SIP 伺服器連線，且 Proxy 伺服器已存在時，如果 Proxy 不允許這些連線，則登入程序中會發生嚴重的延遲。透過在 HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync 下新增 EnableDetectProxyForAllConnections DWORD 登錄項目，並將值設為 1，可啟用修正程式。

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：使用 InsertXML 方法時，顯示的是中斷的圖片連結預留位置，而非實際影像。

