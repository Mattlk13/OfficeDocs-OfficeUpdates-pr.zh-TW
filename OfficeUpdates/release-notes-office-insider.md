---
title: Office 測試人員的版本資訊
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 快」對象提供關鍵新功能、修正或已知問題的最新清單
ms.openlocfilehash: 4bfa4d71cd6f4170f56df5b159c747b59e4da74d
ms.sourcegitcommit: 48ebf0ac6da9e208ff6242200d07013ea3c12dad
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/03/2020
ms.locfileid: "43131101"
---
# <a name="release-notes-for-office-insiders"></a>Office 測試人員的版本資訊

本文包含 Windows 電腦版 Word、Excel、PowerPoint、Outlook、Access 和 Project 測試人員組建的版本資訊。 我們每週都會強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。 請注意，我們在一段時間內會經常推出新功能 (某些時候還有修正) 給測試人員。 這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。 因此，如果您沒有在以下描述的內容中看到某些項目，請不用擔心，您最終還是會看到它。  

> [!NOTE]
> - 版本資訊會每週發佈，可能是多個組建的編譯。
> - 版本資訊發佈日期可能與實際組建發行日期不相符。
> - 現有 Office 365 專業增強版安裝上的 Microsoft Teams - 從 6 月底開始，Microsoft Teams 將在更新這些安裝時，新增至 Office 365 專業增強版的 (和 Office 365 商務版) 的現有安裝中。 新增 Teams 的日期取決於您使用的更新通道。 如需詳細資訊，請參閱[隨著 Office 365 專業增強版部署 Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install)。

[//]: # (DO NOT REMOVE)

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

## <a name="version-2002-january-31"></a>版本 2002：1 月 31 日
*版本 2002 (組建 12513.20010)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。

- **查詢編輯器中的資料分析：** 取得欄位資料的概覽分析、識別錯誤和空白值，查看分佈長條圖等。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 修正根據保留原則到期的電子郵件會顯示兩個標籤的問題。 其中一個顯示郵件將在一天內過期，另一個則顯示將在兩天內到期。

### <a name="word"></a>Word

- 修正在具有「反轉」頁面色彩的閱讀模式中，備註提示未顯示的問題。

- 修正在編輯備註之後將文字設為斜體然後再張貼，斜體格式設定遺失的問題。

- 修正備註內容功能表中的備註命令 (編輯備註、回覆備註、刪除備註、解決備註) 未顯示的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-january-17"></a>版本 2002：1 月 17 日
*版本 2002 (組建 12508.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="word"></a>Word

- **提及和註解通知電子郵件目前包含預覽：** 提及和註解的電子郵件通知現在包含註解文字的預覽，以及該註解所參照的內容。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 在某些情況下，協助工具檢查程式不會顯示圖案​​建議的問題。

### <a name="outlook"></a>Outlook

- 儲存在左側瀏覽窗格 [我的最愛] 的資料夾可能會間歇性消失。

### <a name="powerpoint"></a>PowerPoint

- 已修正使用 PowerPoint 筆跡動畫時，無法完整轉譯或跳過的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-january-10"></a>版本 2001：1 月 10 日
*版本 2001 (組建 12430.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel
- **將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。 [深入了解](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a>Outlook
- **使用者現在可以將 Word/Excel/Outlook 中的物件另存為 Windows 的圖片：** 如同在 PowerPoint 中已具有的功能，使用者現在可以將 Word、Excel 和 Outlook 中的物件另存為圖片。 物件包括圖形、圖示、圖片及其他內容！ 此功能只要按滑鼠右鍵的功能表就能存取。

### <a name="word"></a>Word
- **只要在 Word 中繪製圖形即可輕鬆選取筆跡：** [繪圖] 索引標籤上的 [套索] 工具可協助您選取使用筆跡繪製的物件。 選取個別筆劃或整個字。 當您有大量筆跡但只想要使用其中一部分時，這功能尤其方便。 [深入了解](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。 [深入了解](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="onenote"></a>OneNote
- 100% 解析度時，頁面索引標籤可能會顯得太小並過於接近。

### <a name="word"></a>Word
- 在大量的註解組合中，刪除接近註解清單結尾附近的註解，可能會導致窗格捲動到最上方。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-january-03"></a>版本 2001：1 月 3 日
*版本 2001 (組建 12425.20000)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel
- 有些框線在 A4 大小的紙張上可能無法如預期列印。
- 使用 VBA 將影像新增到工作表圖表物件的頁首/頁尾可能會導致錯誤。
- 設定圖表座標軸格式時，標籤之間的間隔限制為 255。
- 已修正嘗試重新整理 XML 查詢 (資料來源 URL 遭截斷) 時發生錯誤的問題。
- 活頁簿統計資料會報告所有開啟的活頁簿 (包括個人巨集活頁簿) 中的巨集計數。

### <a name="outlook"></a>Outlook
- 切換資料夾可能會導致郵件清單/郵件預覽中「快閃」短暫的空白。 此行為在深色模式中更明顯。

### <a name="powerpoint"></a>PowerPoint
- 已修正呼叫 Shape.Paste 方法會導致貼上的圖形置於焦點下的物件模型問題。&nbsp;
- 已改善複製貼上案例：&nbsp;以程式設計方式從 PowerPoint 投影片複製圖形，並將其貼到循環播放中的另一張投影片會失敗並發生異常錯誤。&nbsp;
- 折疊及展開節標頭後，投影片節標頭的動畫無法正確呈現。

### <a name="project"></a>Project
- 已修正文字換行在任務和資源使用狀況檢視中無法正常運作的問題。
- 已修正如果某資源有多個成本比率，則工作分派的成本值可能不正確的問題。

### <a name="word"></a>Word
- 在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。
- 共同撰寫時，Word 電腦版可能不會顯示使用 Word Online 新增註解的功能。

### <a name="office-suite"></a>Office 套件
- 嘗試在只有一個授權的情況下變更授權時，不再顯示有效授權的錯誤到期日。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-december-13"></a>版本 2001：12 月 13 日
*版本 2001 (組建 12410.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。 您拖曳的郵件將會與所有群組成員共用。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access
- 執行可參考連結之 ODBC 資料表且包含 Order By 子句的聯集查詢，會導致 64 位元 Access 當機。
- Access (O365) 中由聯集查詢的資料匯合可能會導致小數資料的截斷。
- ACE 的 COM 介面並未公開於 Office 應用程式的外部使用。

### <a name="excel"></a>Excel
- 無法執行插入3D 模型 (動態或靜態)，且嘗試 [另存成圖片]。
- 從 Backstage 啟動意見反應的 Shortkey (Alt+Ctrl + 7/8) 與 AZERTY 鍵盤 (Alt-Gr + 7/8) 有衝突。 影響：使用者可能無法使用下列字元，例如：'\'。

### <a name="outlook"></a>Outlook
- 解決導致電子郵件傳送到收件者錯誤地址的問題。
- 解決了導致 Outlook 不正確地允許使用者具有信箱的 &quot;[讀取]&quot; 存取權，而變更郵件之讀取/未讀取狀態的問題。
- 網站上安全性憑證的撤銷無法由 [產品支援] 重新製造。 需要新增 [記錄] 以協助根本解決問題。
- 解決導致使用者看到同步處理失敗的問題。

### <a name="powerpoint"></a>PowerPoint
- 無法執行插入3D 模型 (動態或靜態)，且嘗試 [另存成圖片]。

### <a name="project"></a>Project
- [工作] 不會在 [手動排程的子工作] 彙總中計算。
- 嘗試儲存伺服器架構專案時，從 [功能區] 按鈕叫用的 Project VBA 程式碼可能無法使用。
- 除非 Project 已在執行，從 SharePoint 文件庫中開啟專案檔案會顯示錯誤，且檔案無法開啟。

### <a name="word"></a>Word
- 儲存現有檔案可能會無法執行。
- 在 [拼字及文法檢查編輯器] 視窗中使用方向鍵可能會導致間歇性閃爍。
- 解決待處理時，相關註解可能不會轉換成指向註解。
- 無法執行插入3D 模型 (動態或靜態)，且嘗試 [另存成圖片]。

### <a name="office-suite"></a>Office 套件
- 修正了 Office 更新訊息不以預期語言顯示的問題。 自此以後，Office 更新訊息會正確符合 Windows 顯示語言。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-december-06"></a>版本 1912：12 月 06 日
*版本 1912 (組建 12325.20012)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **進階群組電子郵件設定：** 此功能可協助使用者自訂要在收件匣中接收/追蹤哪些電子郵件或活動。

- **群組命名原則：** 群組命名原則可讓 IT 系統管理員將組織中使用者所建立群組的名稱標準化及管理。 系統管理員可以要求在建立群組時，將特定首碼和尾碼新增至群組的名稱，而且可以封鎖使用特定字詞。 這有助於將群組名稱中使用不當字詞的情況最小化，以及 IT 管理其目錄中群組的表示方式。 命名原則也可協助部署小組網站的組織根據部門來分類。

### <a name="office-suite"></a>Office 套件

- **索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。 只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel
- 使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。
- 使用者在存取隱藏的命名範圍時可能會發生錯誤。
- 停用使用 4K 解析度的硬體圖形加速的情況下，可能會在捲動時發生延遲儲存格呈現的問題。
- 清除與儲存格界限重疊的長型公式，可能仍舊會跨儲存格界限顯示出來。
- 解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。
- 邊界下拉式功能表可能無法正確呈現。

### <a name="onenote"></a>OneNote
- OneNote 可能無法透過「會議記事」Outlook 增益集開啟。

### <a name="outlook"></a>Outlook
- 保留原則標籤可能會將保留時間顯示於括弧中。
- 空格可能會顯示於日文語言套件的連絡人卡片中。
- 內嵌插入至 Outlook 電子郵件訊息中的影像有時候會改變大小。

### <a name="powerpoint"></a>PowerPoint
- 如果使用者雲端檔案的投影片上有兩個 (或多個) 不同的影片，影片影像可正確呈現，但是當使用者按一下每一個檔案來播放時，影片內容會是相同的。
- 在某些情況下，使用觸控裝置進行捲動將無法運作。
- 邊界下拉式功能表可能無法正確呈現。
- Office 應用程式之間的安全性連結可能無法啟動連結的應用程式。

### <a name="project"></a>Project
- 當您使用 [比較專案] 功能時，Project 可能會當機。
- 如果您在 [深色] 模式中，當您移至含有過度分配資源之工作上的工作檢查面板時，將無法讀取資料表。
- 將沒有作業的任務進行進位設定為 1 天。

### <a name="word"></a>Word
- 在特定條件下，完成合併列印之後儲存的檔案可能無法使用。
- 建置組塊召集人可能會顯示不正確通知：&quot;您已修改過樣式、建置組塊&quot;。
- 使用複製/貼上時，有時會重新載入註解窗格。
- 註解有時不會以正確的順序貼上。
- 將含有自訂樣式的多層級清單範本套用至現有的文件時，可能在特定條件下不會保留該樣式。
- 調整分割螢幕邊界的大小可能會造成其他的分割螢幕。
- 邊界下拉式功能表可能無法正確呈現。
- @提及註解卡中的使用者可能會顯示 JSON。
- Office 應用程式之間的安全性連結可能無法啟動連結的應用程式。

### <a name="office-suite"></a>Office 套件
- 針對日文產品，帳戶使用者的姓名可能會以錯誤的順序出現。
- 將滑鼠指標暫留於註解上方時，可能會在註解周圍顯示文字方塊外框的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-november-15"></a>版本 1912：11 月 15 日
*版本1912 (組建 12307.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="insights-services"></a>深入解析服務
- **Excel 構想中的自然語言查詢：** Excel 構想的新功能，詢問關於您資料的自然語言問題。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel
- 某些當地語系化版本的 [文字到欄] 功能可能會失敗。
- 編輯儲存格中的動態陣列公式可能會導致文字在儲存格邊界以外對齊。

### <a name="outlook"></a>Outlook
- 新增透過群組原則強制執行 S/MIME 設定的功能。
- 內嵌影像可能會比預期小。

### <a name="powerpoint"></a>PowerPoint
- 當您將焦點移出文字後，游標可能會消失。

### <a name="project"></a>Project
- 使用者可能會遇到授權錯誤。
- 日期選擇器中的 [今日] 按鈕有時候可能會設定不正確的日期。

### <a name="word"></a>Word
- 以滑鼠右鍵按一下有時不會選取整個字詞。
- 轉換成建議格式之後，游標在物件內可能仍處於使用中狀態。
- 訊息中的影像在某些情況下可能會不正確的縮放。
- 某些主題可能會導致難以判斷所選取的註解。
- 選取註解提示之後，在窗格切換器中隱藏時，現在會顯示新式註解窗格。

### <a name="office-suite"></a>Office 套件
- 回覆註解可能會導致文字方塊垂直延伸到窗格的邊緣以外。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-november-08"></a>版本 1912：11 月 8 日
*版本 1912 (組建 12231.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="user-lifecycle"></a>使用者生命週期
- **AFO 啟用的經驗改進：** 對客戶啟用新電腦隨附的 Office 時，所會看到的畫面進行更新。

### <a name="word"></a>Word
- **Word 中的全新和改良的線上影片體驗：** 全新和更安全的線上影片體驗，可協助您在 Word 中插入新的影片並播放現有影片。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook
- 與跨資料夾內容有關的間歇性損毀。

### <a name="office-suite"></a>Office 套件
- 將圖表從 Excel 貼上至 PowerPoint 可能會造成圖表的大小縮小。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-november-01"></a>版本 1911：11 月 1 日
*版本 1911 (組建 12228.20020)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel
- **將內容與 SVG 物件一起顯示！：** 在 Office 中轉換地圖、圖表和其他 SVG 向量等物件時，現在您可以保留物件中的文字。

- **拿起 Surface 手寫筆時查看手寫筆選項：** 當您在 Word、Excel 或 PowerPoint 中先拿起 Surface 手寫筆時，[繪圖] 索引標籤將會啟動，讓您輕鬆地選取畫筆色彩。

### <a name="powerpoint"></a>PowerPoint
- **將內容與 SVG 物件一起顯示！：** 在 Office 中轉換地圖、圖表和其他 SVG 向量等物件時，現在您可以保留物件中的文字。

- **拿起 Surface 手寫筆時查看手寫筆選項：** 當您在 Word、Excel 或 PowerPoint 中先拿起 Surface 手寫筆時，[繪圖] 索引標籤將會啟動，讓您輕鬆地選取畫筆色彩。

### <a name="visio"></a>Visio
- **在 Excel 中製作精美的 Visio 圖表：** 在 Excel 中快速且輕鬆地將資料呈現為精美的 Visio 圖表。 [深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)。

### <a name="word"></a>Word
- **拿起 Surface 手寫筆時查看手寫筆選項：** 當您在 Word、Excel 或 PowerPoint 中先拿起 Surface 手寫筆時，[繪圖] 索引標籤將會啟動，讓您輕鬆地選取畫筆色彩。

- **改善共同撰寫：** 改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。

- **其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel
- 解決從不受信任的網路共用編輯受保護的檔案時，Excel 可能會當機的問題。
- 解決在刪除含有的走勢圖參考另一個資料表中資料的資料表時，會導致重新開啟檔案時，將檔案識別為已損毀的問題。
- 解決當您將報表篩選隨著其餘的樞紐分析表一起轉換，以用於 SQL 表格式伺服器的查詢時，可能會遇到結果不正確的問題。
- 同時使用朗讀程式和放大鏡，可能會導致當機。
- 同時使用朗讀程式和放大鏡，可能會導致當機。

### <a name="outlook"></a>Outlook
- 轉寄的電子郵件可能會遺失內嵌的影像。
- 會議室尋找工具可能會對可用的會議室顯示 &quot;[無]&quot;。
- 使用者可能無法建立具有嚴格租用戶限制的 Outlook 設定檔。

### <a name="powerpoint"></a>PowerPoint
- 同時使用朗讀程式和放大鏡，可能會導致當機。

### <a name="project"></a>Project
- 使用者無法將工作標示為已完成，並將它設為 99%。
- 資源撫平無法解決資源過度分派問題。

### <a name="word"></a>Word
- 同時使用朗讀程式和放大鏡，可能會導致當機。
- 開啟舊版文件，然後移至 [資訊] 索引標籤會導致當機。
- 內容功能表中未顯示校訂建議。
- 對註解套用不正確的內容原則。
- 以深色文字編寫的舊版註解在深色模式中不會顯示。
- 使用韓文/英文自動校正時，可能出現不正確的字元。
- 在應優先套用較高的原則標籤前，可能已套用了較低的原則標籤。
- 來自 Outlook 郵件中的 cid: 影像連結&nbsp;現在能在要求時成功中斷。
- 同時使用朗讀程式和放大鏡，可能會導致當機。
- 從瀏覽窗格搜尋可能會失敗。

### <a name="office-suite"></a>Office 套件
- 某些繪圖可能不會在預覽或投影片放映中顯示。
- 在垂直文字方塊中，部分片假名字元可能無法正確顯示。
- 嘗試將檔案儲存到已中斷連線的網路共用時可能會導致當機。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-october-25"></a>版本 1911：10 月 25 日
*版本 1911 (組建 12215.20006)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="visio"></a>Visio

- **在 Excel 中製作精美的 Visio 圖表：** 在 Excel 中快速且輕鬆地將資料呈現為精美的 Visio 圖表。 [深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **改善共同撰寫：** 改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。

- **其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- <div><span>記錄計數可能不正確</span></div>


### <a name="excel"></a>Excel

- <div><span>我們已大幅改善刪除合併儲存格的資料行的效能</span></div>


- <div><span>可能已防止使用者以 Office 365 Excel 活頁簿格式儲存</span></div>


- <div><span>核取方塊無法正確呈現</span></div>


- <div><span>無法儲存對圖表大小的變更</span></div>


- <div><span>某些 VBA 函數會針對新的圖表類型傳回錯誤</span></div>


- <div><span>[選取資料來源] 對話方塊上的部分欄位並未區分大小寫</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>無法儲存對圖表大小的變更</span></div>


### <a name="publisher"></a>Publisher

- <div><span>圖形可能會顯示在圖形框線以外</span></div>


### <a name="word"></a>Word

- <div><span>圖形可能會顯示在圖形框線以外</span></div>


- <div><span>醒目提示文字可能很困難</span></div>


- <div><span>可能已防止使用者在編輯器中瀏覽個別項目</span></div>


- <div><span>可能不會將文法或拼寫錯誤醒目提示</span></div>


- <div><span>無法儲存對圖表大小的變更</span></div>


- <div><span>將格式設定套用到 @ 提及之後，可能會防止開啟連絡人卡片</span></div>


- <div><span>已解決使用者無法儲存 Word、Excel 和 PowerPoint 文件的問題。&nbsp;此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存成模型對話方塊]&quot;&quot; 選項的使用者。</span></div>


### <a name="office-suite"></a>Office 套件

- <div><span>在 Windows 7 上使用圖形時的效能問題</span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-october-18"></a>版本 1911：10 月 18 日
*版本 1911 (組建 12209.20010)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **傳送可存取的郵件給最需要它的人員：** Outlook 會顯示郵件提示，協助確保將您的內容傳送給偏好可存取內容的使用者時可供其存取

### <a name="powerpoint"></a>PowerPoint

- **最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。

### <a name="office-suite"></a>Office 套件

- **上傳中心將由需要注意的檔案體驗取代：**「上傳中心」將由會顯示在 Office 應用程式的 [檔案] > [開啟] 下的「需要注意的檔案」體驗取代。 相較於上傳中心，此新體驗更為現代化、整合且更不具侵入性。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="excel"></a>Excel

- <div><span>解決使用自動調整來調整列高時，核取方塊控制項可能收縮的問題</span></div>


- <div><span>解決捲動後選取儲存格時，可能導致選取錯誤的儲存格的問題</span></div>


### <a name="outlook"></a>Outlook

- <div><span>發現簽署具有數位簽署附件的電子郵件時，可能導致數位簽章遭到破壞的問題</span></div>


- <div><span>發現在將長檔名拖放至郵件內文時，長檔名遭到截斷的問題</span></div>


- <div>發現當功能區設定為自動隱藏時，搜尋方塊可能消失的問題</div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>發現投影片預覽的長寬比未正確鎖定/解除鎖定的問題</span></div>

### <a name="project"></a>Project

- <div>發現在執行更新工作時，若輸入記事，可能不會保留記事的問題<br></div>


- <div>發現檔案可能遭某個使用者鎖定，但不會在錯誤訊息中顯示任何使用者名稱的問題。</div>


- <div><span>發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題</span></div>


### <a name="word"></a>Word

- <div><span>發現使用螢幕閱讀器檢視註解時的問題</span></div>


- <div><span>發現將某些評論錯誤地識別為拼寫或文法評論的問題</span></div>


- <div><span>發現新留言對話方塊有時候未取得焦點的問題</span></div>


### <a name="office-suite"></a>Office 套件

- <div><span>我們已修正了&quot;另一個安裝正在進行中&quot;的不正確錯誤訊息，可能導致無法升級的問題</span></div>

- <div><span>發現可能會影響從本機資源同步至雲端資源的問題</span></div>

- <div><span>發現歡迎訊息含有無效連結的問題</span></div>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-october-11"></a>版本 1910：10 月 11 日
*版本 1910 (組建 12130.20112)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)
[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="excel"></a>Excel

- <div>解決從 OneDrive 以物件形式插入檔案的問題</div>


- <div>解決無法將超連結格式正確套用至部分內容的問題</div>


- <div>解決含有結構化絕對參考的公式可能無法正確調整的問題</div>


- <div>解決在目前的 Office 版本中開啟在舊版 Office 中建立的活頁簿時，可能導致 Excel 懸置的問題</div>


- <div>解決從 Excel 複製的內容，在貼上到其他 Office 應用程式時，可能無法正確顯示的問題</div>


- <div>修正以校正使用圖表範本插入圖表時，預覽中使用的色彩</div>


### <a name="powerpoint"></a>PowerPoint

- <div>已發現 ARC 裝置在 AirSpace WinComp 下執行時，可能會遺失連線的問題</div>


### <a name="word"></a>Word

- <div>解決從 OneDrive 以物件形式插入檔案的問題</div>


- <div>改善復原步驟，以<span>修正會導致從電子郵件執行緒中刪除圖形內容的問題。&nbsp;</span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-october-04"></a>版本 1910：10 月 4 日
*版本 1910 (組建 12126.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。 [深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="excel"></a>Excel

- <div><span>我們已修正 [預覽列印] 中的列印範圍不正確的問題</span></div>


- <div><span>我們已修正可能會讓樞紐分析表在共同撰寫工作階段期間無法重新整理的問題</span></div>


### <a name="access"></a>Access

- <div>我們已修正當使用共用資料庫時，使用者可能收到&quot;不一致的狀態&quot;錯誤訊息的問題。</div>


### <a name="outlook"></a>Outlook

- <div><span>我們已修正導致郵件資料夾重複的問題</span></div>


- <div><span>我們已修正當嘗試傳送 s/MIME 加密電子郵件時，可能會導致錯誤訊息的問題</span></div>


- <div><span>我們已修正當使用者收到來自 Skype 的「未接的交談」訊息時，有時可能會導致當機的問題</span></div>


- <div><span>我們已修正可能會造成記憶體洩漏的問題</span></div>


- <div><span>我們已修正當儲存為草稿時，可能會導致寄件者名稱變更的問題</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span></span></div>我們已修正以下問題：在您將文字貼到投影片母片和投影片版面配置上的頁首/頁尾/投影片編號預留位置之後，造成 TextRanges 損壞


- <div><span></span></div>我們已修正在使用超連結貼上文字時，無法建立超連結的問題


- <div>我們已修正造成統計資料無法正常運作的問題</div>


### <a name="word"></a>Word

- <div><span>我們已修正未確認字型色彩的問題</span></div>


### <a name="office-suite"></a>Office 套件

- <div>我們已修正在停用功能後，可能會提供版本歷程記錄的問題</div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-27"></a>版本 1910：9 月 27 日
*版本：1910 (組建 12119.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)
[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="excel"></a>Excel

- <div><span>我們已修正當變更系列集合時，可能會導致散佈折線圖無法正確呈現的問題。</span></div>


### <a name="outlook"></a>Outlook

- <div><span>我們已修正了當與共享行事曆資料夾互動時，可能會報告權限錯誤的問題。</span></div>


- <div><span>我們已修正了使用者可能會無法新增附件至行事曆的問題。</span></div>


- <div><span>我們已修正了當回覆數位簽章的郵件時，導致顯示錯誤訊息的問題。</span></div>


### <a name="word"></a>Word

- <div><span>我們已修正列印到 Deskjet 印表機時，可能會導致縮放問題的問題</span></div>


### <a name="office-suite"></a>Office 套件

- <div><span>我們已修正中等粗體文字樣式不正確的問題</span></div>


- <div><span>我們已修正當關閉具有擱置上傳的檔案時，使用者收到不正確錯誤訊息的問題</span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-20"></a>版本 1910：9 月 20 日
*版本：1910 (組建 12112.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="excel"></a>Excel

- <div><span>我們已修正 Excel 有時候會在啟動時發生懸置的問題。</span></div>

### <a name="outlook"></a>Outlook

- <div><span>我們大幅改善了當有大量會議室可供選擇時，會議室選取的效能。</span></div>


- <div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">我們已修正在 Office 365.中移轉至新式驗證時，擁有 Outlook 多個信箱的客戶無法進行信箱同步處理的問題。</span><br></div>


- <div><span>我們已修正簽章標籤中某些字元不會顯示在下拉式功能表中的問題。</span></div>


### <a name="project"></a>Project

- <div><span>我們修正了使用本機資源取代企業資源時，可能會導致當機的問題。</span></div>


### <a name="word"></a>Word

- <div><span>我們已修正 [草稿模式] 中可能會導致同步捲動無法正常運作的問題。</span></div>


- <div>我們已修正第一次儲存文件後可能導致 [工具提示] 無法正確顯示的問題</div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-13"></a>版本 1910：9 月 13 日
*版本 1910 (組建 12105.20000)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="excel"></a>Excel

- <div><span>我們已修正使用者在部分受保護的工作表中無法貼上超連結的問題</span></div>


### <a name="outlook"></a>Outlook

- <div><span>我們已修正 UI 可能停滯在精簡檢視中的問題</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>我們已修正使用者可能會在列印為 PDF 時發生錯誤的問題</span></div>


### <a name="project"></a>Project

- <div><span>我們已修正在摘要任務上<span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">變更工時值時，如果已啟用受保護的工作則可能會造成當機的問題</span></span></div>


- <font size=2 style="background-color:rgb(255, 255, 255);">我們已修正可能會禁止將事件同步處理到企業行事曆功能的問題</font>


### <a name="office-suite"></a>Office 套件

- <div><span>我們已修正可能會導致重複警告以捨棄本機檔案版本的問題</span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-06"></a>版本 1910：9 月 6 日
*版本 1910 (組建 12030.20004)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **準備、設定、繪圖：** 抓取 Surface 手寫筆之後, 您就可以開始繪製。 [深入了解](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a>PowerPoint

- **準備、設定、繪圖：** 抓取 Surface 手寫筆之後, 您就可以開始繪製。 [深入了解](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a>Word

- **準備、設定、繪圖：** 抓取 Surface 手寫筆之後, 您就可以開始繪製。 [深入了解](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="excel"></a>Excel

- <div><span>我們已修正可能會導致功能區中的字型名稱與正在使用的字型不同的問題</span></div>


### <a name="outlook"></a>Outlook

- <div><span>我們已修正當 Internet Explorer 中的受限制網站停用受保護模式時，可能會導致 Outlook 不適當的資源消耗的問題。</span></div>


- <div><span>我們已修正當貼上 ANSI 原始碼的文字時, 有時可能會導致顯示 Unicode 字元的問題</span></div>


- <div><span>我們已修正有些使用者在群組排程檢視中會不正確地顯示為離線的問題</span></div>


### <a name="word"></a>Word

- <div><span>我們已修正表格格式設定可能遺失的問題</span></div>


- <div><span>我們已修正導致 Ctrl+V 鍵盤快速鍵中斷的問題</span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1909-august-30"></a>版本 1909：8 月 30 日
*版本 1909 (組建 12026.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新

### <a name="access"></a>Access

- **快速尋找連結資料表：** 新的搜尋方塊可讓您輕鬆尋找連結資料表。

### <a name="powerpoint"></a>PowerPoint

- **將圖例另存成 SVG：** 將圖表、圖形或其他圖例另存成可縮放向量圖形，其可調整大小，且不損失影像品質。 [深入了解](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="excel"></a>Excel

- <div><span>我們已修正&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">敏感度</span>的 keytip &nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">與其他 keytip 相衝突的問題。</span></span></div>

- <div><span>我們已修正在嘗試儲存的同時使用共用活頁簿時所發生的問題。</span></div>

- <div><span>我們已修正 Excel 只列出位於「\Excel\Add-in Manager」登錄值中前 16 個增益集的問題。<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></div>


- <div><span>我們已修正 Frequency 函數會傳回不正確結果的問題。</span></div>


- <div><span>我們已大幅提升透過色彩篩選的效能。</span></div>


- <div><span>我們已修正 Surface 使用者移動滑鼠可能解譯為按一下滑鼠事件的問題。</span></div>


- <div><span>我們已修正在 [尋找/取代] 對話方塊中鍵盤無法瀏覽的問題</span></div>


- <div><span>我們已修正某些字型名稱無法正確顯示的問題</span></div>


- <div><span>我們已修正 CSV 無法顯示為支援的檔案類型的問題</span></div>


### <a name="access"></a>Access

- <div>我們已修正當使用共用資料庫時，使用者可能收到&quot;不一致的狀態&quot;錯誤訊息的問題。</div>


- <div><span>我們已修正可能導致日期選擇器在不該出現時出現的問題</span></div>


### <a name="outlook"></a>Outlook

- <div><span>我們已修正部分 POP3 使用者無法顯示 HTML 內容的問題</span></div>


- <div><span>我們已修正在無法使用的環境中工作時，從連絡人卡片的溢位功能表移除非功能性「Planner」連結的問題。</span></div>

### <a name="onenote"></a>OneNote

- <div><span>我們已修正 &nbsp;OneNote 背景同步處理有時候會竊取焦點的問題。</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>我們已修正會影響 3D 盤旋的旋轉方向的問題。</span></div>

- <div><span>我們已修正如果超連結包含特殊字元便無法運作的問題。</span></div>

- <div><span>我們已修正會造成的同時開啟多個註解窗格的問題。</span></div>

### <a name="project"></a>Project

- <div><span>我們已修正在列印團隊規劃檢視之後可能會導致當機的問題。</span></div>

### <a name="word"></a>Word

- <div>我們已<span>修正直排文字方塊中多位元組字元在閱讀檢視中顯示重疊的問題。<br></span></div>

- <div><span>我們&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">已修正當使用者在增益集中採取動作時，找不到日文明信片和賀卡相關增益集資源的問題。</span></span></div>

- <div><span>我們已修正在受保護的檢視中的標題列使用者介面會造成問題的問題</span></div>

### <a name="office-suite"></a>Office 套件

- <div><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> 我們已修正當您在含有一般圖形和連接器圖形的選擇上變更圖形時的損毀檔案問題。</span></span></div>

- <div><span>我們已修正<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">從多個外部顯示器使用固定/解除固定時會造成問題的問題。</span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="august-23-2019br"></a>**2019 年 8 月 23 日**<br/>
版本 1909 (組建 12015.20004)<br/>



## <a name="non-security-updates"></a>非安全性更新：

### <a name="excel"></a>Excel

- <div><span>我們已大幅改善刪除合併儲存格的資料行的效能</span></div>


### <a name="office-suite"></a>Office 套件

- <div><span>我們已修正在瀏覽器中檢視時，部分的 Unicode 字元可能會無法顯示的問題</span></div>


### <a name="outlook"></a>Outlook

- <div><span>我們已修正可能會無法儲存檔案到 WebDAV 的位置的問題</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>我們已修正當使用者點擊一個註解，但可能是另一個註解被選取的問題</span></div>





## <a name="august-16-2019br"></a>**2019 年 8 月 16 日**<br/>
版本 1909 (組建 12013.20000)<br/>

### <a name="powerpoint-feature-updates"></a>PowerPoint 功能更新：

- **列印講義上的投影片編號：** 投影片編號會自動包含在講義上。 由您決定將其保留或關閉。




## <a name="non-security-updates"></a>非安全性更新：

### <a name="excel"></a>Excel

- <div><span>我們已修正可能會導致 AutoSave 自動開啟的問題</span></div>


- <div>我們已修正可能會導致不正確計算儲存格高度的問題</div>


### <a name="office-suite"></a>Office 套件

- <div><span>我們已修正了一個問題，將能大幅改善註解功能的效能</span></div>


- <div><span>我們已修正搜尋時使用方向鍵可能會造成當機的問題</span></div>


- <div><span>我們已修正如果將 @ 符號放在特定字元後，可能會無法使用 @ 提及的問題</span></div>


- <div><span>我們已修正在刪除 @ 提及時，可能會導致當機的問題</span></div>


- <div><span>我們已修正無法在註解卡正確顯示 Emoji 的問題</span></div>


- <div><span>我們已修正使用中​的​剪貼簿​​有時可能會導致當機的問題</span></div>


- <div><span>我們已修正可能會導致快速存取工具列按鈕停止運作的問題</span></div>


- <div><span>我們已修正無法讓文件格式設定預覽切換到背景的問題</span></div>

### <a name="onenote"></a>OneNote

- 我們已修正當 Office 佈景主題設為黑色，區段下拉式清單中的區段名稱顯示為空白的問題。

### <a name="outlook"></a>Outlook

- <div><span>我們已修正在傳送​​事件時可能會導致 Outlook 重複獲取和失去焦點的問題</span></div>


- <div><span>我們已修正無法從工作資料夾的捷徑張貼回覆的問題</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>我們已修正受保護的檢視有時候可能會在合作時造成問題的問題</span></div>


- <div><span>我們已修正可能無法正確顯示註解窗格中工作的問題</span></div>


- <div><span>我們已修正插入新投影片時可能會造成當機的問題</span></div>


### <a name="user-lifecycle"></a>使用者生命週期

- <div><span>我們已修正有時候可能會導致訂閱功能消失的問題</span></div>


### <a name="word"></a>Word

- <div><span>我們已修正如果超連結包含特定字元，則超連結可能會中斷的問題</span></div>


- <div><span>我們已修正在檢視影像註解時，影像可能會調整至不正確大小的問題</span></div>


- <div><span>我們已修正項目符號清單下拉式功能表有時可能會導致當機的問題</span></div>





## <a name="august-09-2019br"></a>**2019 年 8 月 9 日**<br/>
版本 1909 (組建 12001.20000)<br/>

### <a name="excel-feature-updates"></a>Excel 功能更新：

- **共同作業變得更容易：** 共同撰寫的增強功能表示，使用條件式格式設定、儲存格樣式等等時，您的變更會與共同作業者的變更順暢地合併。


- **搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。 而當您選取時，[插入] 按鈕會告知您已經選取的數量。


### <a name="office-suite-feature-updates"></a>Office 套件功能更新：

- **新的 Office 應用程式圖示：** 重新設計的應用程式圖示，可反映簡單、功能強大且智慧型的 Office 體驗


### <a name="outlook-feature-updates"></a>Outlook 功能更新：

- **抵禦攻擊的進階防護：** 使用 Office 365 進階威脅防護，您會受到保護，不受電子郵件主旨、附加的郵件、簽署的郵件、網路路徑內超連結的攻擊。


- **搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。 而當您選取時，[插入] 按鈕會告知您已經選取的數量。


### <a name="powerpoint-feature-updates"></a>PowerPoint 功能更新：

- **搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。 而當您選取時，[插入] 按鈕會告知您已經選取的數量。


### <a name="word-feature-updates"></a>Word 功能更新：

- **其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。


- **搜尋並享受：** 我們對插入圖示新增了搜尋，讓您易於找到您要的圖示。 而當您選取時，[插入] 按鈕會告知您已經選取的數量。




## <a name="non-security-updates"></a>非安全性更新：

### <a name="outlook"></a>Outlook

- <div><span>我們已修正會導致會議收件者在取消會議後收到兩次通知的問題</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>我們已修正當使用者對圖形與圖示選取 [無外框] 或 [無填滿] 時會導致損毀的問題</span></div>





## <a name="august-02-2019br"></a>**2019 年 8 月 2 日**<br/>
版本 1908 (組建 11929.20002)<br/>

### <a name="excel-feature-updates"></a>Excel 功能更新：

- **轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。


- **將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。


### <a name="outlook-feature-updates"></a>Outlook 功能更新：

- **將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。


### <a name="powerpoint-feature-updates"></a>PowerPoint 功能更新：

- **轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。


- **將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。


### <a name="word-feature-updates"></a>Word 功能更新：

- **轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。


- **用其他方式表達：** 當您想要以不同方式表達時，「重寫」功能可以幫助您。 重寫提供其他不同方式來表達您的詞彙。


- **將敏感度標籤套用至您的文件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合貴組織的資訊保護原則。




## <a name="non-security-updates"></a>非安全性更新：

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="excel"></a>Excel

- <div><span>我們已修正了列印至 PDF 時，&quot;重複所有標籤&quot;看起來像已套用的問題</span></div>

### <a name="office-suite"></a>Office 套件

- <div><span>我們已修正了使用者可能無法從桌面開啟文件的問題</span></div>

- <div><span>我們已修正了&quot;另一個安裝正在進行中&quot;的不正確錯誤訊息，可能導致無法升級的問題</span></div>

- <div><span>我們已修正了安全性更新安裝後，使用者可能會看到錯誤訊息的問題</span></div>

- <div><span>我們已修正了可能會造成游標消失的問題</span></div>

- <div><span>我們已修正了使用者可能預設前往 [繪圖] 索引標籤而不是 [常用] 索引標籤的問題</span></div>

- <div><span>我們已修正了大型樹狀檢視可能會導致當機的問題</span></div>

### <a name="outlook"></a>Outlook

- <div></div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">我們已修正了可能導致系統重複提示輸入密碼的問題</span>

- <div><span>我們已修正了可能無法正確查詢電子郵件地址的問題</span></div>

- <div><span>我們已修正了可能導致使用者無法開啟由舊版 Outlook 建立之行事曆項目的問題</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>我們已修正了部分動畫無法開始的問題</span></div>

### <a name="project"></a>Project
- 修正多項效能和穩定性

### <a name="word"></a>Word

- <div><span>我們已修正了註解的回覆以錯誤順序顯示的問題</span></div>

- <div><span>我們已修正了在某些情況下，會顯示提示而非顯示註解的問題</span></div>

- <div><span>我們已修正了當使用者嘗試新增註解時，可能會顯示 [修訂窗格] 的問題</span></div>

- <div><span>我們已修正了可能無法顯示 [復原] 下拉式清單的問題</span></div>

- <div><span>我們已修正了有時無法新增註解的問題</span></div>


## <a name="july-26-2019"></a>2019 年 7 月 26 日
版本 1908 (組建 11916.20000)

## <a name="whats-new"></a>新功能：

### <a name="word-excel-powerpoint"></a>Word、Excel、PowerPoint

#### <a name="create-more-accessible-pdfs"></a>建立更易於存取的 PDF

建立 PDF 檔案，然後協助工具檢查程式會指出在儲存之前應該修正的協助工具問題。

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="all"></a>全部

- 我們修正了 Office 更新後 Office 文件類型關聯和圖示有時會中斷的問題

### <a name="word"></a>Word 
- 修正多項效能和穩定性

### <a name="excel"></a>Excel
- 我們修正了移動圖表有時會導致當機的問題
- 我們修正了在更改圖表類型後從 Chart 物件獲取 Workbook 物件有時會導致錯誤的問題

### <a name="powerpoint"></a>PowerPoint
- 修正多項效能和穩定性

### <a name="outlook"></a>Outlook
- 我們修正了在簡化版的功能區中，停用的控制項有時不會呈現灰色的問題

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>

## <a name="july-19-2019"></a>2019 年 7 月 19 日
版本 1908 (組建 11911.20000)

## <a name="whats-new"></a>新功能：

### <a name="word"></a>Word

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a>了解在 Word Online 中閱讀時，縮略字代表的意義

當您遇到縮略字時，我們會嘗試使用組織的資料來定義縮略字。


## <a name="notable-fixes"></a>值得注意的修正：

### <a name="word"></a>Word 
- 我們已修正 BookMarkEnd 標記遺失的問題。
- 我們已修正字型選項會在使用者輸入特殊字元時變更的問題。
- 我們已修正有時候可能會造成新註解卡片有空白回覆的問題。
- 我們已修正共用電子郵件時可能會造成格式遺失的問題。

### <a name="excel"></a>Excel
- 我們已修正大範圍的陣列有時可能會造成當機的問題。
- 我們已大幅改善從篩選範圍複製資料的效能。
- 我們已修正如果檔案名稱包含特殊字元便無法開啟某些檔案的問題。

### <a name="powerpoint"></a>PowerPoint
- 我們已修正 PowerPoint 中預設未選取新建區段的區段名稱問題。
- 我們已修正使用 4:3 顯示器時 UI 變得難以使用的問題。

### <a name="outlook"></a>Outlook
- 我們已修正無法列出可用會議室的問題。
- 我們已修正部分 POP3 使用者無法使用 HTML 格式的問題。

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>

## <a name="july-12-2019"></a>2019 年 7 月 12 日
版本 1907 (組建 11901.20038)

## <a name="whats-new"></a>新功能：

### <a name="powerpoint"></a>PowerPoint
 
#### <a name="use-ink-replay-in-your-presentations"></a>在簡報中使用筆跡重播
 
套用 PowerPoint 的筆跡重播動畫，使簡報的表達和溝通更加生動。 

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="word"></a>Word 
- 修正多項效能和穩定性

### <a name="excel"></a>Excel
- 修正多項效能和穩定性

### <a name="powerpoint"></a>PowerPoint
- 修正多項效能和穩定性

### <a name="outlook"></a>Outlook
- 修正多項效能和穩定性

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>

## <a name="july-5-2019"></a>2019 年 7 月 5 日
版本 1907 (組建 11901.20018)

## <a name="whats-new"></a>新功能：

### <a name="word-excel-powerpoint"></a>Word、Excel、PowerPoint

#### <a name="sketchy-shapes"></a>素描形狀！

仍在編寫簡報的草稿嗎？ 套用素描樣式來顯示您仍在處理文件。 此功能可在不將物件轉換成自由格式、手繪形狀的情況下，為您的物件賦與個人風格。

### <a name="excel"></a>Excel

- **更快速共用檔案**：不需開啟檔案，即可從最近使用清單直接共用您的檔案。
### <a name="powerpoint"></a>PowerPoint

- **[在講義上列印投影片編號] 設定已移至 [列印] 功能表，以易於存取：** 選取講義版面配置時，可在 [列印] > [整頁模式] 下拉式清單中找到它。 這也會使得每個簡報的設定易於切換。 [深入了解](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。

### <a name="word"></a>Word

- **更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="all"></a>全部
- 我們已大幅提高功能區 KeyTip 的效能
- 我們已修正無法正常顯示 [查看即將推出的新功能] 方塊的問題
- 我們已修正可能會導致共同撰寫圖庫飛出視窗中的相片排列錯誤的問題

### <a name="word"></a>Word 
- 我們已修正有時無法加入新註解的問題
- 我們已修正表格有時可能會造成當機的問題
- 我們已修正無效的資料有時可能會新增至合併列印結尾的問題
- 我們已修正可能會導致不正確呈現部分 LaTeX 方程式的問題

### <a name="excel"></a>Excel
- 我們已修正變更圖表類型有時可能會導致執行階段例外狀況的問題
- 我們已修正開啟多個視窗時會顯示不正確功能區的問題
- 我們已修正巨集開啟活頁簿的第二個執行個體時可能會造成錯誤的問題
- 我們已修正開啟或建立活頁簿，或切換使用不同的活頁簿時可能會造成當機的問題
- 我們已修正使用者無法在 Teams 中開啟透過 Word 建立之 PDF 的問題

### <a name="powerpoint"></a>PowerPoint
- 我們已修正匯出成 PDF 時會降低圖表品質的問題
- 我們已修正工具提示無法顯示到達中心之距離的問題

### <a name="outlook"></a>Outlook
- 我們已修正有時可能會導致 [磁碟已滿] 錯誤訊息無法顯示的問題
- 我們已修正更新會議邀請時可能會導致附件重複的問題

### <a name="access"></a>Access
- 我們已修正某些查詢無法傳回大整數值的問題
- 我們已修正可能會引起 SQL 文字方塊無法編輯的問題
- 我們已修正工具提示可能難以在某些高 DPI 顯示器上查看的問題

### <a name="project"></a>Project
- 我們已修正在新工作中可能會導致旗標值無法編輯的問題
- 我們已修正可能導致狀態更新在 [工作分派] 和 [任務] 上不正確地設定 [實際開始日期] 的問題
- 我們已修正可能會導致部分資源錯誤顯示為過度分派的問題
- 我們已修正新增延隔時間、小數點分隔符號是逗號，以及連線至伺服器時，工作相依性新增方法可能會出錯的問題
- 我們已修正透過 CSOM 更新本機自訂欄位的查閱表格值可能會損毀 PCS 的問題
- 我們已修正總工時值示內如果含有小數點時將不正確顯示的問題

</BR></BR>

## <a name="june-28-2019"></a>2019 年 6 月 28 日
版本 1907 (組建 11819.20002)

## <a name="whats-new"></a>新功能：

### <a name="excel"></a>Excel

- **使用 Power Query 的增強功能快速撰寫程式碼：** 使用自動完成和語法色彩快速完成程式碼。 同時輕鬆探索函數、資料行和參數

- **聯結類似欄位上的表格：** 在比較合併表格的欄位時，取得及轉換 (Power Query) 現在具有近似文字比對邏輯 (也稱為模糊比對)。

### <a name="word"></a>Word

- **共同撰寫的增強功能**：增強共同撰寫時的可靠性。
 
### <a name="word-excel-powerpoint-and-visio"></a>Word、Excel、PowerPoint 和 Visio

#### <a name="recommended-documents"></a>建譯的文件

透過建議您的相關活動尋找文件。

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="word"></a>Word 
- 我們已修正可能會導致有些 .DOC 檔案無法開啟的問題
- 我們已修正可能會導致註解無法正確載入的問題

### <a name="excel"></a>Excel
- 我們已改善 Power Query 的效能

### <a name="powerpoint"></a>PowerPoint
- 我們已修正在 Surface 裝置上使用手寫筆可能會導致螢幕閃爍的相關問題

### <a name="outlook"></a>Outlook
- 我們已修正將約會轉換成會議時可能會變更約會的空閒/忙碌狀態問題
- 我們已修正電子郵件有臨時範本的保護時會顯示錯誤範本和描述的問題

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>

## <a name="june-21-2019"></a>2019 年 6 月 21 日
版本 1907 (組建 11815.20002)

## <a name="whats-new"></a>新功能：

### <a name="outlook"></a>Outlook

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a>Outlook 電腦版中用於黑色佈景主題的深色模式

使用深色模式時，黑色佈景主題中的使用者現在也會在讀取電子郵件時看到讀取窗格具有深色背景，並在撰寫電子郵件時擁有深色背景的撰寫體驗。 如果使用者想要預覽郵件在淺色背景下的外觀，在讀取窗格或功能區中有太陽/月亮切換。

#### <a name="getting-started"></a>開始使用：

1. 開啟黑色佈景主題，深色模式預設就會處於開啟狀態。
2. 使用月亮/太陽切換 (在讀取窗格和功能區中) 可為不在深色模式的使用者預覽郵件的外觀

#### <a name="scenarios-to-try"></a>可嘗試使用的案例

1. 在深色模式中讀取電子郵件。 如果您無法讀取某些項目，請使用讀取窗格中的太陽切換來切換為淺色背景。 
2. 在深色模式中撰寫電子郵件。 使用功能區中的太陽切換，預覽您的郵件使用淺色背景時的外觀。 

如果您遇到未正確顯示的任何電子郵件，請將其 (當作附件) 傳送到 OutlookDarkModeFail@service.microsoft.com

#### <a name="get-location-suggestions"></a>取得位置建議

開始輸入，Outlook 就會尋找符合的位置。

建立約會和會議時，這適用於 [位置] 欄位。

#### <a name="getting-started"></a>開始使用：

- 在 Outlook 中的 O365 或 Outlook.com 行事曆上，建立約會或會議。 
- 按一下 [位置] 欄位，然後開始輸入…

#### <a name="scenarios-to-try"></a>可嘗試使用的案例

當您將會議室加入至會議時，按一下 [位置] 欄位，而不是使用會議室尋找工具增益集或通訊錄。
若是在公共場所 (如餐廳、咖啡廳，甚至是牙醫診所) 的實體位置進行會議，請嘗試使用新的選擇器找到確切的位置。 如此一來，您將可以在該離開時，收到 Outlook Mobile 的通知。

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="all"></a>全部
- 我們已修正在離線時會導致搜尋方塊啟用的問題

### <a name="word"></a>Word 
- 我們已修正有時候可能難以查看鍵盤焦點的問題
- 我們已修正貼到新文件的文字，有時候文字對齊可能會不正確的問題
- 我們已修正將使用者的電腦暫停之後，可能防止部分使用者儲存變更的問題
- 我們已修正在某些情況下會列印整份文件，而非所選範圍的問題
- 我們已修正可能會讓註解在較小型的顯示器上難以閱讀的問題
- 我們已修正擷取到裝置時可能會造成當機的問題

### <a name="excel"></a>Excel
- 修正多項效能和穩定性

### <a name="powerpoint"></a>PowerPoint
- 我們已修正有時候可能難以查看鍵盤焦點的問題

### <a name="outlook"></a>Outlook
- 我們已修正不正確地將未啟用的增益集顯示為已啟用的問題。
- 我們已修正會在有大量原則時，使得客戶無法檢視所有保留原則的問題

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>

## <a name="june-14-2019"></a>2019 年 6 月 14 日
版本 1907 (組建 11807.20000)

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="word"></a>Word 
- 我們已修正了儲存到 OneDrive 時，使用者可能無法登入的問題
- 我們已修正了使用者可能無法變更限制存取模式中之 SharePoint 內容的問題
- 我們已修正了調整邊界時，可能會變更頁首及頁尾內容的問題
- 我們已修正了切換成網頁檢視時，格式設定可能會中斷的問題
- 我們已修正了從 SharePoint 開啟時，使用者無法使用自訂欄位的問題

### <a name="excel"></a>Excel
- 我們已修正了刪除篩選集之資料列時的效能問題
- 我們已修正了有時可能會造成滑鼠在受保護檢視模式中閃爍的問題
- 我們修正了刪除系列時，可能會導致當機的問題
- 我們已修正了某些使用者即使在沒有提供的情況下，仍舊有新增版本歷程記錄之選項的問題
- 我們已修正了使用試算表比較工具時，可能導致例外狀況的問題

### <a name="powerpoint"></a>PowerPoint
- 我們已修正了按一下連結到 SharePoint 時，可能會發生當機的問題
- 我們已修正了使用 Surface 手寫筆輸入時，可能將使用者切換到下一個頁面的問題

### <a name="outlook"></a>Outlook
- 我們已修正了在某些情況下 [收件者] 欄位大於正常的問題

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>

## <a name="june-7-2019"></a>2019 年 6 月 7 日
版本 1907 (組建 11727.20064)

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="word"></a>Word 
- 我們已修正當 Word 中的自動校正設定為使句中的第一個字母均為大寫時，偶爾會當機的問題
- 我們已改善在 SharePoint 上編輯文件時的效能。
- 我們已修正在 Adobe Illustrator 中所建立之向量影像無法正確顯示的問題

### <a name="excel"></a>Excel
- 我們已修正錄製巨集時，排序欄位有時未正確設定的問題
- 我們已修正重新計算陣列公式期間導致停止回應或當機的問題

### <a name="powerpoint"></a>PowerPoint
- 修正多項效能和穩定性

### <a name="outlook"></a>Outlook
- 我們已修正內嵌附件有時未正確縮放的問題

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 我們已修正固定工期的時程表有時會變更工作分派完成日期的問題
- 我們已修正從舊版本中開啟專案時顯示的完成百分比值可能有誤的問題

</BR></BR>

## <a name="may-31-2019"></a>2019 年 5 月 31 日
版本 1906 (組建 11722.20008)

## <a name="whats-new"></a>新功能：

### <a name="outlook"></a>Outlook

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a>[連絡支援人員] 對話方塊現在可停駐，且會顯示在右側

用於 [連絡支援人員] 的對話方塊現在會顯示在右側窗格中，並且會以停駐視窗形式開始。

#### <a name="ink-in-your-email"></a>在您的電子郵件中使用筆跡！

您現在可以在您的 Outlook 電子郵件中繪製圖片並加上註釋。

### <a name="word"></a>Word

#### <a name="open-document-links-in-word"></a>在 Word 中開啟文件連結

當您在 Office 中按一下文件連結時，您可以更新您的喜好設定，以預設在 Word App 中開啟該連結。  若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。 深入了解：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>開始使用：

此功能將預設為關閉。 使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。
當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。

若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：

[檔案] -> [選項] -> [進階] -> [連結處理]

此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。

##### <a name="scenarios-to-try"></a>可嘗試使用的案例：

若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 Word 文件的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。 在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。

### <a name="powerpoint"></a>PowerPoint

#### <a name="open-presentation-links-in-powerpoint"></a>在 PowerPoint 中開啟簡報連結

當您在 Office 中按一下連結連結時，您可以更新您的喜好設定，以預設在 PowerPoint App 中開啟該連結。 若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。 深入了解：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>開始使用：

此功能將預設為關閉。 使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。
當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。

若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：

[檔案] -> [選項] -> [進階] -> [連結處理]

此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。

##### <a name="scenarios-to-try"></a>可嘗試使用的案例：

若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 PowerPoint 簡報的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。 在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。

### <a name="excel"></a>Excel

#### <a name="open-workbook-links-in-excel"></a>在 Excel 中開啟活頁簿連結

當您在 Office 中按一下活頁簿連結時，您可以更新您的喜好設定，以預設在 Excel App 中開啟該連結。 若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。 深入了解：https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>開始使用：

此功能將預設為關閉。 使用者可以透過 [選項] -> [進階] -> [連結處理] 設定來開啟它，也可以在 Win32 WXP 應用程式帶他們進行選擇加入體驗時選擇加入。
當使用者按一下透過 Outlook/Word/PowerPoint/Excel 儲存在 OneDrive/商務用 OneDrive/SharePoint 上的 Word/PowerPoint/Excel 檔案時，這些連結依預設會在適當的 Office 應用程式中 (而非瀏覽器中) 開啟。

若要變更此預設值，使用者可以更新 Outlook/Word/Excel/PowerPoint 中的下列設定：

[檔案] -> [選項] -> [進階] -> [連結處理]

此設定會在 Outlook/Word/PowerPoint/Excel 之間共用，而且可以在任一應用程式中設定。

##### <a name="scenarios-to-try"></a>可嘗試使用的案例：

若要觸發選擇加入體驗 - 從 Outlook/Word/PowerPoint/Excel 開啟儲存在 OneDrive/SharePoint 中 Excel 活頁簿的連結 - 按一下 [在來自 Office Online 的用戶端中開啟] - 在 30 天內執行此動作兩次。 在您選擇加入之後，依預設會在 Win32 應用程式中啟動連結。

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="all"></a>全部
- 我們已修正即使在已停用自動儲存的情況下，檔案有時會自動儲存的問題

### <a name="word"></a>Word 
- 我們已修正可能會導致部分使用者無法儲存至 SharePoint 的問題

### <a name="excel"></a>Excel
- 我們已修正可能對非作用中篩選器顯示不正確圖示的問題。

### <a name="powerpoint"></a>PowerPoint
- 修正多項效能和穩定性

### <a name="outlook"></a>Outlook
- 我們已修正有些使用者在群組排程檢視中會不正確地顯示為離線的問題
- 我們已修正可能會防止 SafeLink 剖析包含尾端空格 URL 的問題
- 我們已修正會議室在非工作時間外顯示為可用的問題

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>

## <a name="may-24-2019"></a>2019 年 5 月 24 日
版本 1906 (組建 11715.20002)

## <a name="whats-new"></a>新功能：

#### <a name="user-experience-updates"></a>使用者體驗更新

[即將推出] 中的更新現已發佈，其中包括簡化功能區、資料夾窗格的新版視覺效果、郵件清單，以及讀取窗格。

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="all"></a>全部

- 我們已修正 [聊天] 窗格無法顯示的問題

### <a name="word"></a>Word 
- 我們已修正在某些情況下 Word 無法為文法錯誤正確醒目提示文字的問題

### <a name="excel"></a>Excel
- 我們已修正 [圖表項目] 使用不正確圖示的問題
- 我們已修正開啟同樣的活頁簿時，可能會啟動 VBA 指令碼中不正確活頁簿的問題

### <a name="powerpoint"></a>PowerPoint
- 修正多項效能和穩定性

### <a name="outlook"></a>Outlook
- 修正多項效能和穩定性

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 我們已修正 Project 在切換工作列後可能會當機的問題

</BR></BR>

## <a name="may-17-2019"></a>2019 年 5 月 17 日
版本 1906 (組建 11708.20006)

## <a name="whats-new"></a>新功能：

### <a name="outlook"></a>Outlook

#### <a name="user-experience-updates"></a>使用者體驗更新

[即將推出] 中的更新現已發佈，其中包括簡化功能區、資料夾窗格的新版視覺效果、郵件清單，以及讀取窗格。

##### <a name="getting-started"></a>開始使用：

這些變更會成為新的預設 UI。自 12 月中旬起，即可透過 [即將推出] 開關切換使用這套 UI，協助您徹底發揮生產力

#### <a name="customizable-simplified-ribbon"></a>自訂簡化功能區

提供輕鬆自訂功能，方便在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。

##### <a name="getting-started"></a>開始使用：

使用者可以使用簡化功能區，方法是開啟 [即將推出] (在一開始)，然後按一下功能區中的＞形箭號，即可在傳統的多行功能區與新式的簡化單行功能區之間切換。

##### <a name="scenarios-to-try"></a>可嘗試使用的案例：

從傳統功能區切換到簡化功能區

#### <a name="pick-your-favorite-action"></a>挑選您的最愛動作

不使用 [標幟] 和 [刪除] 嗎？ 那麼 [封存] 或 [標示為已讀取] 呢？ 自訂快速動作功能表，加上您最常使用的命令。

##### <a name="getting-started"></a>開始使用：

若要選取 [快速動作]，請以滑鼠右鍵按一下郵件清單中的 [電子郵件]，以顯示內容功能表。 然後按一下 [設定快速動作...]

##### <a name="scenarios-to-try"></a>可嘗試使用的案例：

將 [標幟] 和 [刪除] 的預設值變更為 [封存]、[移動]、[標示為已讀取] 或 [無]，以便清除郵件清單

#### <a name="relaxed-or-tighter-layout-you-choose"></a>寬鬆或緊密的版面配置？ 由您選擇

若您想讓郵件之間能有更多空間，可以採用「緊密間距」；或者，您也可以採用緊密的版面配置，以便查看更多郵件。

##### <a name="getting-started"></a>開始使用：

前往 [檢視] 索引標籤，勾選 [更緊密的間距] 核取方塊。若是使用傳統功能區，該核取方塊位於「郵件」群組內；若是使用簡化功能區，則是位於「目前檢視」設定當中

##### <a name="scenarios-to-try"></a>可嘗試使用的案例：

使用 Outlook 在未啟用設定的情況下分類及撰寫電子郵件。 如果開啟 [使用更緊密的間距]，即可讓每個頁面能夠容納得下更多郵件，並讓撰寫表單的控制項更為簡潔。

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a>使用 OneDrive 同步處理用戶端時的刪除重複資料 MRU 項目

透過刪除重複資料 MRU 項目，改善 OneDrive 同步處理用戶端與雲端附件的整合度並加快附加速度，讓其速度足以媲美同步處理資料的複製行為

##### <a name="getting-started"></a>開始使用：

若您使用的是 OneDrive 同步處理用戶端，將再也看不到「附加檔案 MRU」的檔案重複項目。

##### <a name="scenarios-to-try"></a>可嘗試使用的案例：

啟用 OneDrive 同步處理用戶端，並使用 Outlook 電腦版的 [附加檔案] 功能表

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a>已改善擁有多個資料夾的信箱共用資料夾同步處理

Outlook 多年來在同步共用信箱時，其資料夾的數量限制最多為 500 個。 透過這項變更已讓 Outlook 獲得改善，您在同步時將不會再遇到這 500 個資料夾的數量限制。

##### <a name="getting-started"></a>開始使用：

在信箱中新增 1000 個資料夾、讓其他人存取信箱、新增「其他人」的 Outlook 設定檔，然後確認同步處理是否可正常運作。

### <a name="word"></a>Word

#### <a name="erase-just-a-little-bit"></a>小面積清除

##### <a name="getting-started"></a>開始使用：

前往 [繪圖] 索引標籤。選取 [橡皮擦] 下拉式清單。 選擇 [小型橡皮擦] 或 [中型橡皮擦]。

##### <a name="scenarios-to-try"></a>可嘗試使用的案例：

前往 [繪圖] 索引標籤。選取畫筆。 畫出一道筆跡線條。 選取 [橡皮擦] 下拉式清單。 選擇 [小型橡皮擦] 或 [中型橡皮擦]。 清除一小塊的筆跡線條。

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="all"></a>全部 
- 我們已修正可能會導致部分使用者無法儲存成 PDF 的問題
- 我們已修正可能會影響使用者在 32 位元系統上儲存大型檔案的問題

### <a name="word"></a>Word 
- 我們已大幅改善 [聽寫] 功能的反應能力

### <a name="excel"></a>Excel
- 我們已修正按兩下事件在觸控式螢幕裝置上可能會失靈的問題
- 我們已修正可能會導致部分使用者無法編輯 VBA 巨集的問題
- 我們已修正使用交叉分析篩選器時可能會影響效能的問題

### <a name="powerpoint"></a>PowerPoint
- 修正多項效能和穩定性

### <a name="outlook"></a>Outlook
- 我們已修正從所選範本中會出現錯誤範本的問題

### <a name="access"></a>Access
- 我們已修正在使用縮放建立器顯示完整 RTF 格式時，可能難以閱讀的問題

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>

## <a name="may-10-2019"></a>2019 年 5 月 10 日
版本 1906 (組建 11702.20000)

## <a name="whats-new"></a>新功能：

### <a name="outlook"></a>Outlook

**在螢幕上容納更多郵件：** 選取 [檢視] > [使用更緊密的間距] 來調整郵件之間的間距。

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="all"></a>全部
- 我們已修正 [另存新檔] 對話方塊顯示不正確路徑的問題

### <a name="word"></a>Word 
- 我們已修正有些「告訴我」選項無法插入的問題

### <a name="excel"></a>Excel
- 修正多項效能和穩定性

### <a name="powerpoint"></a>PowerPoint
- 修正多項效能和穩定性

### <a name="outlook"></a>Outlook
- 修正多項效能和穩定性

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 我們已修正任務識別碼需要醒目提示才能看見的問題

</BR></BR>

## <a name="may-3-2019"></a>2019 年 5 月 3 日
版本 1906 (組建 11629.20008)

## <a name="whats-new"></a>新功能：

### <a name="outlook"></a>Outlook

**集中所有加密選項：** 只要前往 [選項] > [加密]，即可選擇要用來保護電子郵件訊息的方法。

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="all"></a>全部
- 我們已修正有些使用者使用商務用 OneDrive 同步處理時遇到的問題

### <a name="word"></a>Word 
- 我們已修正在某些情況下，Word 會花很長時間啟動的問題

### <a name="excel"></a>Excel
- 我們已修正升級至較新版 Excel 後活頁簿的外部連結有時會被移除的問題
- 我們已修正有些使用者可能會遇到無法在新活頁簿中選取儲存格的問題

### <a name="powerpoint"></a>PowerPoint
- 我們已修正將繪圖轉換成文字時字型大小不一致的問題

### <a name="outlook"></a>Outlook
- 我們已修正從 .VCF 檔案儲存連絡人可能會導致空白欄位的問題
- 我們已修正即使郵件已寄出卻仍卡在寄件匣資料夾的問題
- 我們已修正檢視 DRM 訊息時 Outlook 可能會當機的問題

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 我們已修正編輯器會從中文切換為英文的問題
- 我們已修正主專案的已發佈複本中出現未發佈工作的問題

</BR></BR>

## <a name="april-26-2019"></a>2019 年 4 月 26 日
版本 1905 (組建 11617.20002)

## <a name="new-features"></a>新功能

### <a name="outlook"></a>Outlook

**共用行事曆更新的速度更快：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。 開啟預覽以更快且更可靠地更新共用行事曆。

### <a name="excel"></a>Excel

#### <a name="coauthoring-improvements"></a>共同撰寫的增強功能

改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。

### <a name="visio"></a>Visio

- **從 Power BI 匯出 Visio 視覺效果：** 當匯出 Power BI 報表為 PDF 或 PowerPoint 等更多檔案時，Power BI Visio 視覺效果會正常顯示。

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="word"></a>Word 
- 修正多項效能和穩定性

### <a name="excel"></a>Excel
- 我們已修正 Solver 巨集無法執行的問題
- 我們已修正阻止 Excel 檔案匯入到 SharePoint 的問題

### <a name="powerpoint"></a>PowerPoint
- 修正多項效能和穩定性

### <a name="outlook"></a>Outlook
- 修正多項效能和穩定性

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>

## <a name="april-19-2019"></a>2019 年 4 月 19 日
版本 1905 (組建 11609.20002)

## <a name="whats-new"></a>新功能：

### <a name="outlook"></a>Outlook

**搜尋人員時取得電子郵件建議：** 當您在 [搜尋] 方塊中輸入人員的名稱時，最相關的電子郵件訊息會包括在您的搜尋建議中。

### <a name="excel"></a>Excel

#### <a name="improved-filled-maps-experience-using-data-types"></a>使用資料類型改善區域分布圖體驗

此功能是針對使用 Excel 的地理資料類型繪製區域分布圖圖表使用者的增強功能。 對使用者的優點是功能之間有更豐富的整合，以及使用者要對應的區域會有更好的精確度。 其他優點包括功能能夠對應城市多邊形。

##### <a name="getting-started"></a>開始使用：

- 此功能是 Excel 內現有功能的增強功能。 若要使用增強功能，請將位置轉換為豐富的實體，並使用區域分布圖繪製。 

##### <a name="scenarios-to-try"></a>可嘗試使用的案例：

- 使用者可以嘗試對應城市、省/市、縣/市、國家/地區和郵遞區號。 


## <a name="notable-fixes"></a>值得注意的修正：

### <a name="all-applications"></a>所有應用程式
- 我們已修正每當應用程式啟動時會顯示 [初次執行] 對話方塊的問題
- 我們已修正 [另存新檔] 對話方塊中 SharePoint 連結可能遺失的問題。
- 我們已修正使用者錯誤地看到 [立即修復] 對話方塊的問題

### <a name="word"></a>Word 
- 我們已修正某些使用者在要求字型時，可能會收到記憶體或磁碟空間不足錯誤的問題
- 我們已修正視窗從 [註解] 窗格切換時，焦點可能會遺失的問題

### <a name="excel"></a>Excel
- 修正多項效能和穩定性

### <a name="powerpoint"></a>PowerPoint
- 我們已修正會妨礙調整商標圖形大小的問題
- 我們已修正在受保護的檢視模式中開啟檔案時，PowerPoint 會當機的問題

### <a name="outlook"></a>Outlook
- 我們已修正會防礙一些使用者選取中文文字的問題
- 我們已修正未正確計算到期日的問題

### <a name="access"></a>Access
- 我們已修正會防礙一些使用者使用巨集建立器的問題
- 我們已修正列印報表只會列印第一頁的問題
- 我們已修正將游標移到超連結上時，應用程式會當機的問題
- 我們已修正使用關聯性檢視檢視時，造成某些項目在螢幕上消失的問題

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>

## <a name="april-12-2019"></a>2019 年 4 月 12 日
版本 1905 (組建 11601.20042)

## <a name="whats-new"></a>新功能：

### <a name="access"></a>Access

#### <a name="get-smart-with-microsoft-graph"></a>充分發揮 Microsoft Graph

使用智慧型技術匯入或連結到智慧型資料，並重新打造您的桌面資料庫。

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="all-applications"></a>所有應用程式
 - 我們已修正會防止使用者將檔案儲存到雲端位置的問題
 - 我們已修正可能從功能區開啟錯誤窗格的問題

### <a name="word"></a>Word 
- 修正多項效能和穩定性

### <a name="excel"></a>Excel
- 我們已修正當活頁簿不包含連結資料類型時，使用者會看到連結資料類型之錯誤訊息的問題
- 我們已修正在本機與線上檢視 Word 文件時，文件中的 URL 連結可能變更的問題

### <a name="powerpoint"></a>PowerPoint
- 我們已修正應用程式可能會在從 [動畫] 索引標籤復原變更之後當機的問題

### <a name="outlook"></a>Outlook
- 我們已修正會防止一些使用者修改公用資料夾中連絡人 [備註] 欄位的問題
- 我們已修正到期日與刪除日期之間可能發生衝突的問題

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>

## <a name="april-5-2019"></a>2019 年 4 月 5 日
版本 1904 (組建 11527.20014)

## <a name="whats-new"></a>新功能：

### <a name="outlook"></a>Outlook

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a>Windows 版 Outlook：設定並共用您的 [焦點收件匣] 設定

[焦點收件匣] 喜好設定會儲存在雲端內，因此當您在任何電腦上使用 Windows 版 Outlook 和 Outlook 網頁版時，都可以取得相同的一致體驗。

#### <a name="getting-started"></a>開始使用：

在 [檔案] > [選項] > [一般] 索引標籤下，還有一個名為 [將我的 Outlook 設定儲存在雲端中] 的新喜好設定。 使用者需要核取方塊，才能讓他們的 [焦點收件匣] 設定漫遊到其他電腦的 Outlook 安裝和 OWA。

#### <a name="scenarios-to-try"></a>可嘗試使用的案例：

在已開啟雲端設定喜好設定的電腦上變更 [焦點收件匣]。 瀏覽至 OWA，然後查看那裡也同樣套用了喜好設定。 在 OWA 變更 [焦點收件匣]，然後啟動電腦版 Outlook 查看已反映喜好設定。

### <a name="word"></a>Word

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a>[學習工具] 模式額外支援更多頁面色彩

Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。  許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 版和 Mac 版 Word 中擴大了色彩選項。

#### <a name="getting-started"></a>快速入門：

若要試用，請移至 [檢視] 索引標籤，選擇 [學習工具]，然後選擇 [頁面色彩]。

#### <a name="scenarios-to-try"></a>可嘗試使用的案例：

若要試用，請移至 [檢視] 索引標籤，選擇 [學習工具]，然後選擇 [頁面色彩]。

### <a name="excel"></a>Excel

#### <a name="elevate-creativity-with-animated-3d-models"></a>以具備動畫效果的 3D 模型提高創意

Office 現在支援動畫模型，這類模型能在編輯器中播放，讓您的試算表更生動！

#### <a name="getting-started"></a>開始使用：

1. 開啟 Excel
2. 插入具備動畫效果的 3D 模型 (很快會進到 Remix，但現在請在此位置存取動畫模型：\\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)
3. 動畫模型會在編輯器中播放！ [檢查投影片放映] 模式 - 動畫模型也會在那裡播放！
4. 在 3D 格式功能區中，探索模型中更多的動畫場景

#### <a name="scenarios-to-try"></a>可嘗試使用的案例：

1. 插入動畫模型，然後看它在編輯器中播放
2. 透過 3D 格式功能區中的 [場景庫]，探索動畫模型中可用的動畫場景
3. 透過功能區、浮動工具列或空格鍵輕鬆地播放/暫停動畫

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="all-applications"></a>所有應用程式
- 我們已修正 Excel 的內容功能表中會出現錯誤應用程式圖示的問題
- 我們已修正在安裝更新之後 [檔案功能表] 按鈕會消失的問題
- 我們已修正會變更您的使用者授權的問題

### <a name="word"></a>Word 
- 我們已修正文字在特定縮放比例中無法正常顯示的問題

### <a name="excel"></a>Excel
- 我們已修正使用者在進行編輯之後未收到儲存活頁簿提示的問題
- 我們已修正當使用者共用活頁簿時未觸發 BeforeSave 事件的問題。
- 我們已修正將欄的大小重新調整為小於 6 像素會擲回不正確錯誤訊息的問題。
- 我們已修正 Excel 忽略 Application.Visible 旗標的問題
- 我們已修正追蹤箭號保留在非作用中凍結窗格的問題
- 我們已修正在開啟活頁簿時日期和貨幣儲存格格式會變更的問題
- 我們已修正工具提示會意外移動的問題
- 我們已修正 Power Query 編輯器的當地語系化問題
- 我們已修正在透過電子郵件傳送時活頁簿附件會遭到移除的問題

### <a name="powerpoint"></a>PowerPoint
- 我們已修正複製圖形會比預期還要久的問題

### <a name="outlook"></a>Outlook
- 我們已修正在使用繪圖工具時 Outlook 可能會當機的問題
- 我們已修正當撰寫 html 電子郵件時的當地語系化問題
- 我們已修正使用者在選取下面窗格時會遇到困難的問題

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>

## <a name="march-22-2019"></a>2019 年 3 月 22 日
版本 1904 (組建 11514.20004)

## <a name="new-features"></a>新功能

- **隱私權控制：** 用於診斷資料和連線體驗的新增、更新及改良的控制項。 深入了解 <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json>

- **Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="word"></a>Word 
- 我們已修正 UI 經常會顯示「正在檢查變更」的問題

### <a name="excel"></a>Excel
- 我們已修正應用程式可能在移動工作表之後當機的問題
- 我們已修正應用程式可能在儲存為 PDF 之後當機的問題
- 我們已修正儲存對話方塊不會接受某些韓文字元的問題

### <a name="powerpoint"></a>PowerPoint
- 修正多項效能和穩定性

### <a name="outlook"></a>Outlook
- 修正多項效能和穩定性

### <a name="access"></a>Access
- 我們已修正 Access 中對 Access 建立額外捷徑的錯誤訊息
- 我們已修正來自連結 SharePoint 的資料無法正確顯示的問題

### <a name="project"></a>Project
- 我們已修正語言設定會從中文切換為英文的問題
- 我們已修正應用程式可能在同步處理到 SharePoint 時當機的問題

</BR></BR>

## <a name="march-15-2019"></a>2019 年 3 月 15 日
版本 1904 (組建 11504.20000)

## <a name="whats-new"></a>新功能：

### <a name="word"></a>Word

#### <a name="focus-mode"></a>焦點模式

切換到 [檢視] 功能表中的 [焦點] 以移除令人分心的事物，讓您更能專注於工作。 僅供 Office 365 訂閱者使用。

#### <a name="getting-started"></a>開始使用：

[檢視] 索引標籤 功能區狀態列中的 [焦點] 按鈕 [焦點] 按鈕

#### <a name="scenarios-to-try"></a>可嘗試使用的案例：

進入焦點模式，享受專注的體驗

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="word"></a>Word 
- 我們已修正以 PDF 格式儲存文件時，文件中影像的 DPI 會不正確的問題

### <a name="excel"></a>Excel
- 修正多項效能和穩定性

### <a name="powerpoint"></a>PowerPoint
- 我們已修正註解窗格無法正確開啟或關閉的問題
- 我們已修正應用程式會在刪除影片時當機的問題
- 我們已修正於某些情況下應用程式會無法啟動的問題

### <a name="outlook"></a>Outlook
- 我們已修正以日文檢視時讀信回條不正確的問題

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>

## <a name="march-8-2019"></a>2019 年 3 月 8 日 
版本 1903 (組建 11425.20036)

## <a name="whats-new"></a>新功能：

### <a name="word"></a>Word

### <a name="find-what-youre-looking-for-with-microsoft-search"></a>使用 Microsoft Search 尋找您要的內容

您可以使用 Microsoft Search 找到所有檔案、動作、人員，協助您完成工作所需。

#### <a name="getting-started"></a>開始使用：

- 這個功能在標題中的 UI 上方強調顯示。

#### <a name="scenarios-to-try"></a>可嘗試使用的案例：

- 搜尋某間大學、最近使用過的文件或搜尋最常用的功能區命令
- 尋找某個主題或主旨並取得更多相關資訊
- 
#### <a name="coauthoring"></a>共同撰寫

厭倦於被包含巨集的文件阻礙了嗎？ 現在商務用 OneDrive 的 docm 檔案允許同時由多個作者編輯。

#### <a name="getting-started"></a>開始使用：

使用者在 UI 中不需要按下任何按鈕，就能存取這項功能。 商務用 OneDrive 的 docm 檔案預設已啟用此功能。
因此，使用者應該將 docm 檔案儲存至商務用 OneDrive 試用看看。

#### <a name="scenarios-to-try"></a>可嘗試使用的案例：

在商務用 OneDrive 建立 docm 檔案、與同事共用並且共同作業！

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="word"></a>Word 
- 我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題
- 我們已修正回覆註解時發生的當機問題
- 我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題

### <a name="excel"></a>Excel
- 我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題

### <a name="powerpoint"></a>PowerPoint
- 修正多項效能和穩定性

### <a name="outlook"></a>Outlook
- 我們已修正 Outlook 搜尋未依所選時間順序排序的問題
- 我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題
- 我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題

### <a name="access"></a>Access
- 我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題
- 我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 DisplayControl 屬性的問題

### <a name="project"></a>Project
- 修正多項效能和穩定性


## <a name="march-1-2019"></a>2019 年 3 月 1 日 
版本 1903 (組建 11414.20014)

## <a name="whats-new"></a>新功能

### <a name="word"></a>Word

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a>追蹤修訂、註解和即時共同作業的色彩會同步

我們產品中的修正現在可確保註解、追蹤修訂及共同作業者的游標會以相同色彩顯示。

#### <a name="getting-started"></a>開始使用：

開啟其他人已開啟的 SharePoint 或 OneDrive 文件。 確認使用者的追蹤修訂和註解色彩符合該使用者游標的色彩。

#### <a name="scenarios-to-try"></a>可嘗試使用的案例：

開啟其他人已開啟的 SharePoint 或 OneDrive 文件。 確認使用者的追蹤修訂和註解色彩符合該使用者游標的色彩。

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="word"></a>Word 
- 我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題
- 我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題

### <a name="excel"></a>Excel
- 我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題

### <a name="powerpoint"></a>PowerPoint
- 我們已修正在 PowerPoint 中使用 @提及的投影片圖像大小問題

### <a name="outlook"></a>Outlook
- 我們已修正 Outlook 搜尋未依所選時間順序排序的問題
- 我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題
- 我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題

### <a name="access"></a>Access
- 我們已更新確認使用資料來源重新連結資料表時顯示的提示文字
- 我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題
- 我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 [顯示控制項] 屬性的問題

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>



## <a name="february-15-2019"></a>2019 年 2 月 15 日 
版本 1903 (組建 11310.20016)

## <a name="whats-new"></a>新功能：

### <a name="powerpoint"></a>PowerPoint


### <a name="morph-transition-enhancements---morph-by-name"></a>轉化轉場增強效果 - 依名稱轉化

選取要轉化的圖形

#### <a name="getting-started"></a>開始使用：

- 若要使轉化將兩個物件視為同一個物件，使用者可以使用 [選取窗格] 重新命名圖形。
- 名稱前面必須加上「!!」 (兩個半形驚嘆號)，轉化才能用來覆寫預設比對行為，例如「!!名稱」
- 使用者可以繼續將圖形重新命名為不是以「!!」為開頭的任何名稱 不必擔心會變更轉化的運作方式

#### <a name="scenarios-to-try"></a>可嘗試使用的案例：

- 在投影片中插入圖形，讓我們假設是矩形
- 建立新投影片
- 在第 2 張投影片中插入不同的圖形，讓我們假設是三角形
- 開啟 [選取窗格]，將投影片 1 中的矩形重新命名為「!!圖形」，將投影片 2 中的三角形重新命名為「!!圖形」
- 將 [轉化] 套用至第 2 張投影片

</BR>

### <a name="morph-transition-enhancements---smartart"></a>轉化轉場增強效果 - SmartArt

轉場更順暢的 SmartArt 轉化

#### <a name="getting-started"></a>開始使用：

您使用 SmartArt 的方式與轉化相同

#### <a name="scenarios-to-try"></a>可嘗試使用的案例：

- 在投影片中插入 SmartArt
- 複製投影片
- 在複製的投影片上調整大小/變更/移動 SmartArt
- 在複製的投影片上套用 [轉化]

</BR>

### <a name="morph-transition-enhancements---tables"></a>轉化轉場增強效果 - 表格​​

轉場更順暢的表格轉化

#### <a name="getting-started"></a>開始使用：
您使用表格的方式與轉化相同

#### <a name="scenarios-to-try"></a>可嘗試使用的案例：

- 在投影片中插入表格
- 複製投影片
- 在複製的投影片上調整大小/變更/移動表格
- 在複製的投影片上套用 [轉化]

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a>Word、Excel、PowerPoint、OneNote、Access、Project、Publisher 和 Visio

### <a name="seamlessly-switch-between-accounts"></a>在不同帳戶之間順暢切換

全新的帳戶管理員會在同一個地方顯示您所有的工作和個人帳戶，讓您能控制在其間切換。 這項更新的經驗能清楚知道您的登入方法，因此您現在不需要先登出或處理複雜的對話方塊就可以切換工作和個人帳戶。


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a>可嘗試使用的案例：
- 在不同的帳戶之間切換
- 新增帳戶 [附註：您可能想要先移至 [檔案] | [帳戶] | [已連線服務]，移除任何已連線至工作帳戶的個人服務或是反向服務]
- 登出帳戶
</BR>

## <a name="notable-fixes"></a>值得注意的修正：

### <a name="word"></a>Word 
- 我們已修正表格和影像的內容預覽問題

### <a name="excel"></a>Excel
- 我們已修正在黑色佈景主題中，自動篩選的搜尋欄位中文字是白色的問題
- 我們已修正新 Office 增益集的同意 UI 問題

### <a name="powerpoint"></a>PowerPoint
- 我們已修正在膝上型電腦或平板電腦上進行投影片簡報時自動延伸顯示的問題。

### <a name="outlook"></a>Outlook
- 我們已修正 [傳送至 OneNote] 按鈕的顯示問題

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 修正多項效能和穩定性


</BR></BR>
## <a name="february-11-2019"></a>2019 年 2 月 11 日
版本 1903 (組建 11330.20014)


## <a name="notable-fixes"></a>值得注意的修正：

### <a name="word"></a>Word 
- 我們已修正某些自訂樣式無法套用至線上 Word 的問題
- 我們已修正 Word 中豐富物件的內容預覽問題
- 我們已修正貼上清單會導致 Word 當機的問題

### <a name="excel"></a>Excel
- 我們已修正無貨幣符號時，數字格式後的附加空白不再顯示的問題
- 我們已修正自動偵測股票的問題

### <a name="powerpoint"></a>PowerPoint
- 修正多項效能和穩定性

### <a name="outlook"></a>Outlook
- 修正多項效能和穩定性

### <a name="access"></a>Access
- 修正多項效能和穩定性

### <a name="project"></a>Project
- 修正多項效能和穩定性

</BR></BR>


## <a name="february-1-2019"></a>2019 年 2 月 1 日 
版本 1902 (組建 11326.20000)


## <a name="notable-fixes"></a>值得注意的修正

### <a name="word"></a>Word 
- 我們已修正內嵌 Excel 表格中調整儲存格大小的問題
- 我們已修正繪圖畫布中複製/貼上圖形的問題

### <a name="excel"></a>Excel
- 我們已修正從 Excel Web App 開啟檔案的問題
- 我們已修正因為檔名大小造成 CSV 檔案儲存為 XLSX 失敗的問題
- 我們已修正快顯功能表顯示快顯功能表選項的問題

### <a name="powerpoint"></a>PowerPoint
- 我們已修正使用者無法使用鍵盤快速鍵 ctrl+alt+7/ctrl+alt+8 輸入方括號的問題
- 我們已修正將本機影片插入至 PPT 會減少 'C' 磁碟機磁碟空間的問題
- 我們已修正 [發佈至 Microsoft Stream] 按鈕無法向某些使用者顯示的問題

### <a name="outlook"></a>Outlook
- 我們已修正行事曆中工作檢視無法正確顯示工作主旨的問題

### <a name="access"></a>Access
- 我們已修正圖表的縮放比例的問題

### <a name="project"></a>Project
- 修正多項效能和穩定性
