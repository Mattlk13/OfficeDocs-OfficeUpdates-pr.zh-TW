---
title: Office 測試人員的版本資訊
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 7/5/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 快」對象提供關鍵新功能、修正或已知問題的最新清單
ms.openlocfilehash: 69d4e3cbe3bf6c57f08e5b8f3eb90f8abb47e459
ms.sourcegitcommit: cb86c338e3a58b21bd6ed9dc5480388075c0194d
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/05/2019
ms.locfileid: "35575164"
---
# <a name="release-notes-for-office-insiders"></a>Office 測試人員的版本資訊

本文包含 Windows 電腦版 Word、Excel、PowerPoint、Outlook、Access 和 Project 測試人員組建的版本資訊。 我們每週都強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。 請注意，我們在一段時間內會經常推出新功能 (某些時候還有修正) 給測試人員。 這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。 所以，如果你沒有看到下面描述的項目，不要擔心你最終會得到它。  

> [!NOTE]
> - 版本資訊會每週發佈，可能是多個組建的編譯
> - 版本資訊發佈日期可能與實際組建發行日期不相符

 > [!NOTE]
> - 現有 Office 365 專業增強版安裝上的 Microsoft Teams - 從 6 月底開始，Microsoft Teams 將在更新這些安裝時，新增至 Office 365 專業增強版的 (和 Office 365 商務版) 的現有安裝中。 新增 Teams 的日期取決於您使用的更新通道。 如需其他資訊，請參閱[隨著 Office 365 專業增強版部署 Microsoft Teams](https://docs.microsoft.com/zh-TW/deployoffice/teams-install)。

## <a name="july-5-2019"></a>2019 年 7 月 5 日
版本 1908 (組建 11901.20002)

## <a name="whats-new"></a>新功能：

### <a name="word-excel-powerpoint"></a>Word、Excel、PowerPoint

#### <a name="sketchy-shapes"></a>素描形狀！

仍在編寫簡報的草稿嗎？ 套用素描樣式來顯示您仍在處理文件。 此功能可在不將物件轉換成自由格式、手繪形狀的情況下，為您的物件賦與個人風格。

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

如果您遇到未正確顯示的任何電子郵件，請將其 (當作附件) 傳送到 OutlookDarkModeFail，

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

當您在 Office 中按一下文件連結時，您可以更新您的喜好設定，以預設在 Word App 中開啟該連結。  若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。 深入了解：https://support.office.com/zh-TW/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

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

當您在 Office 中按一下連結連結時，您可以更新您的喜好設定，以預設在 PowerPoint App 中開啟該連結。 若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。 深入了解：https://support.office.com/zh-TW/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

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

當您在 Office 中按一下活頁簿連結時，您可以更新您的喜好設定，以預設在 Excel App 中開啟該連結。 若要更新您的喜好設定，請移至 [檔案] -> [選項] -> [進階] -> [連結處理]。 深入了解：https://support.office.com/zh-TW/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

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

Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。  許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 和 Mac 的 Word 中增加了色彩選項。

#### <a name="getting-started"></a>開始使用：

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

#### <a name="scenarios-to-try"></a>可嘗試使用的範例：

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
- 名稱前面必須加上「!!」 (兩個半形驚嘆號)，例如「!!名稱」，轉化才能用來覆寫預設比對行為
- 使用者可以繼續將圖形重新命名為不是以「!!」為開頭的任何名稱 不必擔心會變更轉化的運作方式

#### <a name="scenarios-to-try"></a>可嘗試使用的範例：

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

#### <a name="scenarios-to-try"></a>可嘗試使用的範例：

- 在投影片中插入 SmartArt
- 複製投影片
- 在複製的投影片上調整大小/變更/移動 SmartArt
- 在複製的投影片上套用 [轉化]

</BR>

### <a name="morph-transition-enhancements---tables"></a>轉化轉場增強效果 - 表格​​

轉場更順暢的表格轉化

#### <a name="getting-started"></a>開始使用：
您使用表格的方式與轉化相同

#### <a name="scenarios-to-try"></a>可嘗試使用的範例：

- 在投影片中插入表格
- 複製投影片
- 在複製的投影片上調整大小/變更/移動表格
- 在複製的投影片上套用 [轉化]

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a>Word、Excel、PowerPoint、OneNote、Access、Project、Publisher 和 Visio

### <a name="seamlessly-switch-between-accounts"></a>在不同帳戶之間順暢切換

全新的帳戶管理員會在同一個地方顯示您所有的工作和個人帳戶，讓您能控制在其間切換。 這項更新的經驗能清楚知道您的登入方法，因此您現在不需要先登出或處理複雜的對話方塊就可以切換工作和個人帳戶。


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a>可嘗試使用的範例：
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
- 我們已修正將本機影片插入至 PPT 會減少 C 磁碟機磁碟空間的問題
- 我們已修正 [發佈至 Microsoft Stream] 按鈕無法向某些使用者顯示的問題

### <a name="outlook"></a>Outlook
- 我們已修正行事曆中工作檢視無法正確顯示工作主旨的問題

### <a name="access"></a>Access
- 我們已修正圖表的縮放比例的問題

### <a name="project"></a>Project
- 修正多項效能和穩定性
