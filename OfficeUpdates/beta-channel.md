---
title: Beta 通道的版本資訊
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 快」對象提供關鍵新功能、修正或已知問題的最新清單
ms.openlocfilehash: e754309f8f647f13b6db0a1b6f4cbcfac2f4ffe5
ms.sourcegitcommit: 1f8cb906d8d0af5eb26eaedf008180375d2fd55d
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/09/2020
ms.locfileid: "44668062"
---
# <a name="release-notes-for-office-insiders"></a>Office 測試人員的版本資訊

本文包含適用于 Word、Excel、PowerPoint、Outlook、Access 和 Project for Windows desktop 的 Beta 通道組建的版本資訊。 我們每週都會強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。 請注意，我們通常會在一段時間內針對 Beta 通道推出功能（甚至是修正）。 這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。 因此，如果您沒有在以下描述的內容中看到某些項目，請不用擔心，您最終還是會看到它。  

> [!IMPORTANT]
> 我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。 如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。

> [!NOTE]
> - 版本資訊會每週發佈，可能是多個組建的編譯。
> - 版本資訊發佈日期可能與實際組建發行日期不相符。

[//]: # (DO NOT REMOVE)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

## <a name="version-2006-june-05"></a>版本2006：5月5日
*版本2006（組建13001.20002）*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **在 Excel 中協同作業時排序/篩選：** 您現在可以在與其他人共同作業時，排序和篩選您的 Excel 檔案。 這項新功能可防止您在共同撰寫檔時，受到其他使用者的排序和篩選的影響。

- **在 Excel 內從 POWER BI 建立資料集的 PivotTables：** 您可以在 Excel 中建立連接至儲存于 Power BI 之資料集的 PivotTables，只需按幾下滑鼠即可。這樣做可讓您最適合 PivotTables 和 Power BI。 使用您的安全 Power BI 資料集的 PivotTables，計算、匯總及分析您的資料。 [深入了解](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a>Outlook

- **快速重新開啟先前會話中的專案：** 我們新增了一個選項，可快速重新開啟先前 Outlook 會話中的專案。 Outlook 是否會損毀或關閉它，您現在可以在重新開啟應用程式時快速重新開機專案。 此功能預設為開啟。 若要將它關閉，請移至 [選項] > 一般 > 啟動選項]。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正此問題：圖表座標軸上的自訂值將無法正確套用。
- 我們已修復此問題：在儲存檔案時，包含具有定義名稱之多個公式的工作表會導致較長的時間。

### <a name="outlook"></a>Outlook

- 我們修正了輸入法（輸入法編輯器）視窗會在使用多個具有不同解析度的監視器時，與使用 IME 輸入的基準文字重迭的問題。
- 我們已修復此問題：在撰寫新的電子郵件訊息時，查看範本會導致系統損毀。
- 我們修正了使用者無法在 Outlook 版本1911之後 Exchange 2010 公用資料夾的問題。
- 已修正此問題：已停用 Office 功能區中群組行事曆的分類按鈕。
- 我們已修復此問題：會使發生衝突之連絡人的使用者在 Outlook 中經歷損毀。
- 我們已修正此問題：在高 DPI 顯示器上，使用者已遺漏資料夾內容中的「線上封存」下拉式清單。
- 我們已修正此問題：當使用者使用純文字電子郵件中的超連結時，使用者在 Outlook 中遇到了損毀問題。
- 我們修正了導致 Outlook 無法剖析以 RFC2231 編碼的長檔名的問題。
- 我們修正了導致 Outlook 使用者在使用螢幕閱讀器時遇到間歇性懸掛的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用以表單驗證的方式開啟伺服器設定檔案的問題。
- 我們已修復此問題：具有內嵌圖表/活頁簿的 PowerPoint 檔案可能會導致儲存檔案失敗。
- 我們已修復此問題：使用者已關閉的批註窗格會自動重新開啟。
- 我們已修復此問題：一張投影片上的投影片編輯器會與下一張投影片交疊。

### <a name="project"></a>Project

- 已修正此問題：刪除其父項計畫後，無法刪除或重新指派孤立的工作。

### <a name="word"></a>Word

- 我們修正了批註窗格中的時間戳記不是以系統地區設定時間為基礎的問題。
- 我們修正了 web 應用程式與桌面應用程式之間的批註未同步處理的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version2006may29"></a>版本2006：5月29日
*版本2006（組建12920.20000）*

### <a name="featureupdates"></a>功能更新
### <a name="outlook"></a>Outlook

- **新增至 Outlook toast 通知的其他按鈕：** 快速動作按鈕現在會出現在 Windows 10 上執行 Outlook 的 Outlook toast 通知中。

### <a name="powerpoint"></a>PowerPoint

- **改進 PowerPoint 中的資料流程影片效能：** 我們已改進 Microsoft Stream 影片的播放效能，以盡可能縮短影片載入時間，並產生流暢的觀賞體驗。  使用 Microsoft Stream 的公司影片來建立更佳的簡報。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolvedissues"></a>解決的問題

### <a name="excel"></a>Excel

- 我們已修復此問題：在使用 OneDrive 時，Excel 會不時關閉。
- 我們已修復此問題：按一下相同活頁簿中的已加書簽的超連結時，將會隱藏該活頁簿。
- 已修正此問題：某些複本和貼上的圖表連結使用對應的磁片磁碟機位址，而不是通用位址。
- 我們已修復此問題：在使用 Ctrl + Shift + 箭號鍵以在 Excel 視窗透過團隊共用時，Excel 可能會變得無回應。

### <a name="powerpoint"></a>PowerPoint

- 我們修正了在使用滑鼠滾輪縮放後，投影片未居中的問題。

### <a name="word"></a>Word

- 我們已修復此問題：將文字複製並貼到批註窗格時，不會顯示。
- 我們已修正此問題：批註提示氣泡在100% 縮放顯示時會出現模糊。
- 我們已修復此問題：啟用原則 Word 2007 和更新版本的二進位檔案和範本會導致一些共同撰寫案例失敗。
- 我們已修復此問題：不會開啟具有長路徑名稱（大於32K）的檔案，也不會顯示適當的錯誤訊息。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a>版本2006：5月22日
*版本2006（組建12914.20000）*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **儲存至固定資料夾：** 固定資料夾可讓您更輕鬆地儲存 Office 檔案。 我們收到意見反應，讓使用者在儲存新檔案時，更能控制可使用的資料夾。 我們非常高興可為您提供新功能：在 [儲存] 對話方塊中固定您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 及 PowerPoint 檔案。<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

### <a name="powerpoint"></a>PowerPoint

- **儲存至固定資料夾：** 固定資料夾可讓您更輕鬆地儲存 Office 檔案。 我們收到意見反應，讓使用者在儲存新檔案時，更能控制可使用的資料夾。 我們非常高興可為您提供新功能：在 [儲存] 對話方塊中固定您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 及 PowerPoint 檔案。<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

### <a name="word"></a>Word

- **儲存至固定資料夾：** 固定資料夾可讓您更輕鬆地儲存 Office 檔案。 我們收到意見反應，讓使用者在儲存新檔案時，更能控制可使用的資料夾。 我們非常高興可為您提供新功能：在 [儲存] 對話方塊中固定您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 及 PowerPoint 檔案。<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們修正了錯誤訊息：「另一個使用者目前無法關閉此活頁簿」，因為增益集是以字母順序，而不是以使用者指定的順序載入，所以會出現此問題。
- 我們已修正此問題：在 Excel 與部分協力廠商的輔助技術應用程式之間管理字體時，記憶體遭到損毀。
- 我們已修復此問題：當增益集要求包含具有 noSelect 鎖定之圖形的工作表上的主項目目時，Excel 會損毀。

### <a name="outlook"></a>Outlook

- 已修正此問題：當使用者在資料夾之間移動專案時，未能正確地激發 BeforeItemMove 事件。
- 我們已修復此問題：使用者看到跨越午夜臨界值的行事曆專案，視為全天事件。
- 我們已修復此問題：當兩個增益集將按鈕新增至功能區中的相同群組時，Outlook 會當機。
- 我們修正了使用者無法與來賓使用者共用行事曆的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們修正了簡報區域的放大和縮小導致縮放選取專案選取範圍與滑鼠指標之間的間隙。

### <a name="project"></a>Project

- 已修正此問題：在按一下 [選項] 後，Project 會損毀。

### <a name="word"></a>Word

- 我們已修正問題：批註中的超連結無法運作。
- 我們修正了簡報區域的放大和縮小導致縮放選取專案選取範圍與滑鼠指標之間的間隙。
- 我們已修正此問題：在行事曆 WordMail 中粘貼 HTML 時無法運作。
- 我們已修復此問題：回復共同撰寫的會話中的批註有時會導致 Word 凍結。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-may-15"></a>版本2006：5月15日
*版本 2006 (組建 12905.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **進行 PDF 連線：** 連接至、匯入、重新整理 PDF 中的資料。 [深入了解](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a>Outlook

- **只尋找您需要**的專案：使用資料夾、寄件者、日期、附件資訊等選項來縮小搜尋範圍。

### <a name="powerpoint"></a>PowerPoint

- **不需要簡報導覽裝置：您的 earbuds 包括：** 使用表面 Earbuds 來控制您的 PowerPoint 簡報。 重要：您必須在適用于 Windows 10 的「表面音訊」應用程式中搭配您的 Surface Earbuds，以便使用筆勢控制簡報。 在 Windows 10 上開始使用表面音訊應用程式的指示可于這裡取得。 [深入了解](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a>Word

- **自動套用或建議敏感度標籤：** Office 可以建議或根據偵測到的敏感內容自動套用敏感度標籤。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel
- 我們修正了在使用者刪除合併欄時，改善使用者效能的問題。
- <div>我們修正了導致印表機名稱重複出現在可用印表機清單中的問題。</div>

### <a name="powerpoint"></a>PowerPoint
- 我們已修復此問題：使用英文（QWERTZ）鍵盤時，鍵盤快速鍵和拼寫檢查不會如預期的方式運作。

### <a name="word"></a>Word
- 我們已修復此問題：在空白檔上新增批註時，不會執行任何動作。
- 我們已修復此問題：在包含一百個專案的檔中插入或更新索引時，會導致應用程式當機。
- 我們已修復此問題：自訂 xml 值開啟的檔案非常緩慢。

### <a name="office-suite"></a>Office 套件
- 我們已在 Visual Basic for Applications 中修正了 Microsoft Office 中的問題，在此情況下，Office 應用程式會在載入時，由 Office 應用程式查看包含對文件庫名稱或文件庫路徑中之 DBCS 字元的程式碼庫參考的某些 VBA 專案。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-may-08"></a>版本 2006：5 月 8 日
*版本 2006 (組建 12829.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。

### <a name="outlook"></a>Outlook

- **更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。 [深入了解](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。

### <a name="powerpoint"></a>PowerPoint

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。 [深入了解](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a>Word

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="office-suite"></a>Office 套件

- 我們已經研究並解決了在作業系統關閉後，透過 InTune 進行的 Office 365 專業增強版部署會暫停的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-01"></a>版本 2005：5 月 1 日
*版本 2005 (組建 12827.20030)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。 您可以變更權限，讓所有收件者都能存取。 [深入了解](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正圖表資料表無法正確呈現日期座標軸中的值的問題。
- 修正使用 [頁面配置] 或 [分頁預覽] 之後無法停用分頁符號的問題。
- 修正隱藏和取消隱藏具有系列資料的欄之後，圖表線條樣式可能會遺失的問題。
- 在已篩選清單中插入欄的時間會比預期更長。
- 當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。
- 修正啟用 [負值以補色顯示] 選項後，可能無法儲存樞紐分析表中的自訂格式設定的問題。
- 修正如果選取 [負值以補色顯示] 選項，可能無法儲存樞紐分析表中單一資料點的自訂格式設定的問題。
- 這項變更修正在 CSV 檔案中上傳 '@' 字元時，會導致將 '@' 字元之後的字串轉換成公式的問題。
- 修正無法正確捨入 SEQUENCE 函數中十進位值的問題。

### <a name="outlook"></a>Outlook

- 解決導致使用者在 Outlook 桌面用戶端中按一下非常長的安全連結時，由於截斷而無法載入的問題。
- 修正當與伺服器同步處理時，名稱中包含 DBCS (雙位元組字元集) 字元的 Outlook 資料夾會間斷消失的問題。 為此，必須為 Outlook 設定 IMAP 帳戶，並在地區設定設定為日文的系統上執行。

### <a name="powerpoint"></a>PowerPoint

- 已修正問題：如果使用者建立了註解，但未張貼就關閉 [註解] 窗格，然後開啟新視窗、瀏覽多張投影片並關閉視窗，最後再開啟原始簡報中的 [註解] 窗格，將導致無法使用草稿註解。

### <a name="project"></a>Project

- 修正問題：如果 Project 連線至 Project Web App，且小數分隔符號是逗號，當新增延遲時，TaskDependencies Add 方法會失敗的問題。

### <a name="word"></a>Word

- 修正在 [共同作業] 模式時，在文件中插入註解並不總是成功的問題。
- 此變更修正在按一下 @ 提及時，[人員卡片] 會閃動的問題。
- 修正問題：關閉具有草稿註解的文件時，會在不儲存草稿註解的情況下，提示使用者是否要關閉文件。 取消提示會關閉文件，而不是保持文件開啟。
- 修正翻譯已張貼註解將導致「插入已翻譯的文字失敗」錯誤的問題。
- 在 Web 檢視/沉浸式閱讀器中，如果已在檢視中，按一下提示會捲動到最上方。 已修正這個問題。
- 我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以.docx 副檔名和檔案名稱 WRO0004.docx 儲存，進而導致文件無法使用。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2005-april-24"></a>版本 2005：4 月 24 日
版本 2005 (組建 12816.20006)**

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel
- 這項變更修正了即使 LINEST 函式傳回正確的值，圖表趨勢線的 R 平方值 (在強制 y 截距的情況下) 仍然不正確的問題。
- 此變更修正了自訂圖表趨勢線格式不一定會儲存的問題。

### <a name="outlook"></a>Outlook
- 修正了 Office 功能區中群組行事曆分類按鈕已停用的問題。
- 修正了企業客戶沒有執行或無法使用群組資料夾的問題，該問題會導致 Outlook 顯示「沒有回應」的訊息。

### <a name="powerpoint"></a>PowerPoint
- 修正了將滑鼠游標移到星號 (*) 符號，但不會顯示上一次更新文件的日期和使用者姓名。

### <a name="word"></a>Word
- 啟用「顯示書簽」選項卻不會顯示書簽。 已修正這個問題。
- 此變更修正了下列問題：如果已啟用 [顯示功能變數代碼，而非其值] 選項，則含有超連結的文字可能不會顯示。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2005-april-17"></a>版本 2005：4 月 17 日
*版本 2005 (組建 12810.20002)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel
- 已增加搭配圖表使用的 [自訂誤差線] 對話方塊上儲存格參照 [編輯] 控制項的大小。
- 在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。
- 修正列印時表單控制項的核取方塊縮放問題。
- 在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。
- 此變更會修正設定格式化的條件 (CF) 資訊無法正確儲存到 XLSB 檔案的問題。

### <a name="onenote"></a>OneNote
- 修正將分行符號儲存為垂直 Tab 的問題。

### <a name="outlook"></a>Outlook
- 解決會導致使用者無法將個人連絡人群組新增為會議出席者的問題。
- 解決會導致還有 2 個月時間的會議，無法在排程小幫手中顯示會議主題的問題。
- 解決會導致使用者在轉寄大型 HTML 郵件時看到郵件內文截斷的問題。
- 新增透過群組原則強制執行 S/MIME 預設登入設定的功能。
- 解決會導致為使用者主要信箱以外的信箱所建立的刪除規則變得無效的問題。
- 解決在轉寄加密郵件時導致捨棄附件的問題。

### <a name="project"></a>Project
- 在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。
- 修正變更連結至 SharePoint 工作清單之專案的面板狀態欄位時，Project 可能當機的問題。
- 修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2004-april-10"></a>版本 2004：4 月 10 日
*版本 2004 (組建 12730.20024)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **略過 [顯示資料表] 對話方塊，直接移至工作窗格，以及將資料表新增至關係和查詢的程序簡化：** 只要按一下四個索引標籤、將名稱多重選取、依文字搜尋，並從在您工作時維持開啟的工作窗格拖曳，即可新增資料表和查詢。

### <a name="excel"></a>Excel

- **M365 進階版內容選擇器：** 讓您的文件栩栩如生！ 探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="outlook"></a>Outlook

- **M365 進階版內容選擇器：** 讓您的文件栩栩如生！ 探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮

### <a name="powerpoint"></a>PowerPoint

- **M365 進階版內容選擇器：** 讓您的文件栩栩如生！ 探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。

### <a name="word"></a>Word

- **M365 進階版內容選擇器：** 讓您的文件栩栩如生！ 探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **標註私人複本：** 製作共用文件的私人複本，以建立只有您本人能夠看到的手寫筆記。 若要開始使用，請移至 [檢視] > [建立私人複本]。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 修正工作窗格中表格的重新調整及重新整理問題。

### <a name="excel"></a>Excel

- 修正在工作表上選取儲存格範圍會導致只選取單一儲存格的問題。

- 修正在為含有 X 軸範圍的圖表縮減大小時，可能會導致 Excel 停止回應的問題。

- 修正插入使用者定義的圖表範本來作為預設值會導致其儲存為直條圖的問題。

- 修正當基礎資料儲存格沒有標題時，圖表上的資料標籤會以空白顯示的問題。

- 修正已啟用 R1C1 儲存格參照且正在共同撰寫/共用的 Excel 工作表，在將游標移到 [使用者目前狀態] 圖示上方時不會以 R1C1 模式顯示作用中儲存格的問題。

### <a name="outlook"></a>Outlook

- 解決會導致類別有時候會從電子郵件訊息中消失的問題。

- 解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。

- 解決在嘗試檢視組織表單的屬性時，會導致使用者遇到當機的問題。

- 解決在變更機器上的時區時，會導致某些提醒無法觸發的問題。

### <a name="powerpoint"></a>PowerPoint

- 此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。

- 我們已修正將文字從 Excel 複製到 PowerPoint 時可能會導致其格式設定發生變更的問題。

- 此變更修正了使用 [全字拼寫須相符] 來尋找特殊字元時，不一定能正常運作的問題。

### <a name="project"></a>專案

- 修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。

### <a name="word"></a>Word

- 此變更修正了將游標暫留在提示上不會醒目提示其卡片的問題。

- 此變更修正了使用套索選取工具時，群組圖形中的文字會暫時消失的問題。

- 此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。

- 此變更修正了在雙頁檢視中建立註解時，註解錨點不一定會顯示的問題。

- 修正如果段落的樣式是連結至清單的樣式上階，則該清單的編號可能會遺失的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-27"></a>版本 2004：3 月 27 日
*版本 2004 (組建 12718.20010)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **在撰寫郵件時有新的選項可停用 @ 提及建議：** 您是否覺得 @ 提及的選擇器很煩人，一點都不好用？ 現在您可以視需要將其關閉了。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook
- 解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。
- 解決了以下問題：當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，使用者會無法新增簽名。
- 解決了以下問題：使用者無法從網頁位置將其他附件新增到先前建立的會議。

### <a name="powerpoint"></a>PowerPoint
- 此變更修正了會導致包含 emojis 的 PowerPoint 檔案在儲存時發生失敗的錯誤。

### <a name="project"></a>Project
- 修正了以下問題：如果執行 ' CustomFieldValueListGetItem' 且自訂欄位的查閱資料表不存在，系統會建立一個不應建立的空白查閱資料表。

### <a name="word"></a>Word
- 此變更修正了以下問題：從 [檢視] 功能表選取多個頁面時，其中的 [註解] 窗格會顯示為空白。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-20"></a>版本 2004：3 月 20 日
*版本 2004 (組建 12711.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **行事曆新版視覺效果：** 去年，我們提供了全新的郵件體驗，而今年將為您帶來嶄新的行事曆！ 有幾項更新是新穎卻令人孰悉的，您是經驗豐富的 Outlook 使用者，可以立即使用並提高生產力。

- **協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站

### <a name="powerpoint"></a>PowerPoint

- **在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。

### <a name="outlook"></a>Outlook

- 此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。

- 此變更修正了電子郵件草稿最新變更未更新的問題。

- 已修正在檔案上按一下滑鼠右鍵並使用「傳送到」功能無法運作的問題。

- 已修正如果使用者有自訂的 [通訊錄] 搜尋路徑，則 Outlook 的名稱解析範圍會限制為自訂路徑，而不是包括全域通訊清單 (GAL) 的問題。

- 已修正在一組傳回的搜尋結果中，依類別結果排序不會顯示類別色彩的問題。

### <a name="project"></a>Project

- 已修正當使用者按一下 [排程群組] 內 [工作] 功能區中的 [停用] 按鈕時，不會觸發 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) 事件的問題。

- 如果您在 [表單類型] 檢視中設定前置任務或後置任務詳細資訊，則 ProjectBeforeTaskChange Visual Basic Applications (VBA) 事件不會一律擷取變更。 例如，如果刪除了某個相依性，並在表單上按一下 [確定]，則不會觸發該事件。 已修正此問題。

- 已修正在進行變更 (例如日期變更) 之後，實際工作成本 (ACWP) 的最新值不會顯示的問題。

- 已修正使用「最近使用」(MRU) 功能表開啟專案時，會使用 [讀取/寫入] 存取權開啟專案的問題。

- 這項變更修正了如果您建立包含開始日期和時間 (但無工期) 的手動工作，則時間表上的時間顯示不正確的問題。

- 已修正使用回曆列印時間表時，會導致列印檢視中略過或重複一個月的問題。

- 這項變更解決了在團隊規劃中使用 GDI 物件時，可能導致 GDI 物件分配過多並產生記憶體不足的問題。

### <a name="word"></a>Word

- 已修正張貼留言功能停用的問題。

- 此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。

- 這項變更解決了帳戶管理員不會分派訊息而導致協力廠商應用程式懸置的問題。

- 這項變更修正了目錄會使用文件中未包含的標題樣式進行更新的問題。

- 已修正在寄送文件時，儲存在 Word 文件中的數位簽章會被刪除的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-13"></a>版本 2004：3 月 13 日
*版本 2004 (組建 12703.20010)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新

### <a name="excel"></a>Excel
- **敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。 [深入了解](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a>PowerPoint
- **敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。 [深入了解](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a>Word
- **敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。 [深入了解](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="access"></a>Access
- 修正國際版 Access 在使用者介面中顯示英文字串的問題。

### <a name="excel"></a>Excel
- 修正使用者在以程式設計方式編輯大量儲存格範圍時可能遇到的效能問題。
- 修正以日文環境開啟 CSV 檔案時發生的效能問題。

### <a name="outlook"></a>Outlook
- 解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。
- 解決會導致在展開的尋找窗格中按一下 Enter 時無法開始搜尋，而是會要求使用者按一下 [搜尋] 按鈕的問題。
- 修正將 [如果有，顯示使用者的照片] 選項停用時，搜尋不會顯示有關使用者的任何資訊的問題。

### <a name="project"></a>Project
- 修正無法正確計算摘要工作日期的問題。
- 修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。

### <a name="word"></a>Word
- 修正輸入或編輯備註然後使用 Ctrl+A 時，會導致選取畫布中的文字，而不只是選取備註卡片內文字的問題。
- 我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。
- 我們已修正將兩份文件合併成一份文件時的問題。
- 修正標示的修訂若與方程式有關，在儲存檔案時可能會導致失敗的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-06"></a>版本 2003：3 月 6 日
*版本 2003 (組建 12624.20086)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 修正使用 Outlook Web Access 建立規則時不會保存到 Exchange 伺服器，並導致衝突的問題。
- 修正 Outlook 在深色模式中不會在 [寄件者:] 欄位中顯示下拉式清單的問題。
- 解決在其他應用程式中開啟某個檔案時，導致使用者無法透過檔案總管將該檔案附加至郵件訊息的問題。

### <a name="powerpoint"></a>PowerPoint

- 修正將滑鼠移至縮圖上時，建議的縮圖閃動的問題。 在某些情況下，這可能會導致 PowerPoint 當機。

### <a name="word"></a>Word

- 修正受保護無法編輯之文件的比較功能問題。

### <a name="office-suite"></a>Office 套件

- 修正 Word/Excel/PowerPoint 中的使用者主體名稱 (UPN) 不再區分大小寫，導致在 SharePoint 上使用檔案時較少發生失敗的問題。

- 修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

## <a name="version-2003-february-28"></a>版本 2003：2 月 28 日
*版本 2003 (組建 12619.20002)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **IT 系統管理員的事件通知：** Microsoft 365 租用戶全域系統管理員和 Office 應用程式系統會在 Windows 版 Outlook 的新右側面板中收到影響其使用者的 Outlook 和 O365 Exchange 事件通知。

### <a name="powerpoint"></a>PowerPoint

- **改善筆跡轉換圖形圖表製作體驗：** 繪製更完善的圖表，並將它轉換成您可處理的 Office 物件。[深入了解](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正交叉分析篩選器中的文字在預覽列印中無法正確縮放的問題。

### <a name="outlook"></a>Outlook

- 解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。

### <a name="word"></a>Word

- 修正按 Tab 鍵導覽註解卡片時，註解編輯方塊上的焦點無法顯示的問題。

- 在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。

- 修正將先前使用密碼保護的檔案儲存到雲端儲存空間無法運作的問題。

### <a name="office-suite"></a>Office 套件

- 修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-february-21"></a>版本 2003：2 月 21 日
*版本 2003 (組建 12615.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="office-suite"></a>Office 套件

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel
- 已修正使用者在重新命名樞紐分析表度量值時可能遇到的問題。
- 已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。
- 已修正當使用者執行與功能區互動的巨集時，導致 UI 快閃的問題。
- 已修正當檔案中的第一個字為 TABLE 時，CSV 檔案載入錯誤的問題。
- 已修正當您在兩個具有不同縮放比例的活頁簿之間切換時，使用者可能遇到的當機問題。

### <a name="outlook"></a>Outlook
- 已解決當持續整夜執行 Outlook 時，導致使用者無法開啟公用資料夾訊息的問題。
- 已修正在新增 Gmail 帳戶的驗證工作流程中，[權限] 頁面上的 [允許] 和 [拒絕] 按鈕停用的爭用情況。
- 已解決即使已關閉記錄，在某些情況下仍導致 Outlook 異常產生記錄輸出的問題。

### <a name="word"></a>Word
- 已修正當滑鼠指標暫留在註解卡片上方時，未醒目提示註解卡片的問題。
- 在使用中的文件共同撰寫工作階段中，直接在註解卡片中新增影像可能會導致新增標籤。 我們已修正此問題。

### <a name="office-suite"></a>Office 套件
- 當您將 Multichoice/Lookup/Managed-metadata 屬性與 Word/Excel/PowerPoint 文件一起使用並儲存至 SharePoint 文件庫時，這些屬性之前限制為 255 個字元。 當這些屬性超過 255 個字元時，這類文件就無法儲存。 在此變更中，此限制已增加到 2048 個字元。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-february-14"></a>版本 2003：2 月 14 日
*版本 2003 (組建 12607.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？ Outlook 現在會偵測這項要求並協助您取得連結。

### <a name="word"></a>Word

- **在繪圖工具箱中找到筆跡編輯器：** 選取 [繪圖]，然後選擇 [筆跡編輯器] 手寫筆以使用手指或數位筆編輯文件。 [深入了解](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a>Office 套件

- **更清楚的狀態列圖示：** 狀態列圖示現在更容易查看

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 已解決導致使用者無法存取「空閒/忙碌選項」行事曆權限對話方塊的問題。

- 修正了開啟某些從不同時區傳送的週期性會議執行個體時，可能會導致出現警示：「很抱歉，無法開啟這此項目」的問題。

- 已解決從該郵件拖放附件後造成使用者無法重新開啟 .msg 檔案的問題。

- 修正從 Outlook 上傳檔案附件到 OneDrive 後，造成包含括號之附件名稱的檔案名稱被變更。

### <a name="powerpoint"></a>PowerPoint

- 修正儲存包含 Excel 圖表的 PowerPoint 或 Word 文件會導致失敗的問題。

### <a name="word"></a>Word

- 修正文件中的圖片在匯出成 PDF 後，會失去透明度的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-07"></a>版本 2002：2 月 7 日
*版本 2002 (組建 12527.20040)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。 在 SQL 檢視中搜尋及取代文字。 在 [關聯圖] 視窗中選取多個資料表。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此更新會修正使用 ADODB 的問題。 VB 程式碼中的記錄器物件可能會不正確地報告錯誤。

- 此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。

### <a name="excel"></a>Excel

- 修正使用「資料剖析」搭配動態陣列時，Excel 會當機的問題。

### <a name="outlook"></a>Outlook

- 修正以月檢視在行事曆中捲動時，無法顯示之前的行事曆活動的問題。

- 解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。

### <a name="powerpoint"></a>PowerPoint

- 修正關閉檔案之後，如果有任何事件處理常式正在執行，PowerPoint 就不會立即將它從 [簡報] 集合中移除的問題。 因此，物件模型報告的開啟中簡報數目會不正確，且會防止關閉 PowerPoint。

- 修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。

### <a name="word"></a>Word

- 更新和瀏覽目錄時，有時可能會在文件上顯示灰色區域的問題。

- 修正共同撰寫文件時，可能不會保留根註解的草稿版本的問題。

- 已修正在註解卡片之間來回切換時，有時會顯示一開始選取的註解，並將某選取範圍醒目提示的問題。

- 修正在已撰寫註解但未張貼，且使用者嘗試儲存檔案的情況下，使用 [瀏覽] 來儲存檔案沒有作用的問題。

- 將 SlideTrack 啟用且 [註解] 窗格關閉時，Ctrl+Alt+M 可能無法開啟 [註解] 窗格的問題。

- 修正在表格中新增 @提及時可能發生錯誤訊息：「文件中的表格已經毀損」的問題。

### <a name="office-suite"></a>Office 套件

- 解決可能導致挪威耐諾斯克 (nn-no) 校訂工具套件安裝不正確的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)
