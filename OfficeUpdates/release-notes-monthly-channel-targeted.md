---
title: 每月通道版本資訊 (已設定目標)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 慢」對象提供關鍵新功能、修正或已知問題的最新清單
ms.openlocfilehash: 219abb58ae3fc51b869adf52885e4cce2bbdb9d1
ms.sourcegitcommit: e46d02cd54b8c164b853a130ca07ce9c85f586c5
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/12/2019
ms.locfileid: "38282111"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a>Office 每月通道的版本資訊 (已設定目標)

本文包含 Windows 電腦版 Word、Excel、PowerPoint、Outlook、Access 和 Project 每月通道 (已設定目標) 組建的版本資訊。 我們每週都強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。 請注意，我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至每月通道 (已設定目標)。 這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。 所以，如果你沒有看到下面描述的項目，不要擔心你最終會得到它。  

> [!NOTE]
> - 版本資訊發佈日期可能與實際組建發行日期不相符。
> - 現有 Office 365 專業增強版安裝上的 Microsoft Teams - 從 6 月底開始，Microsoft Teams 將在更新這些安裝時，新增至 Office 365 專業增強版的 (和 Office 365 商務版) 的現有安裝中。 新增 Teams 的日期取決於您使用的更新通道。 如需詳細資訊，請參閱[隨著 Office 365 專業增強版部署 Microsoft Teams](https://docs.microsoft.com/zh-TW/deployoffice/teams-install)。

[//]: # (DO NOT REMOVE)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

## <a name="version-1911-november-12"></a>版本 1911：11 月 12 日
*版本 1911 (組建 12228.20120)*

安全性更新列於[此處](https://docs.microsoft.com/zh-TW/officeupdates/office365-proplus-security-updates)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。 [深入了解](https://support.office.com/zh-TW/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a>Outlook

- **傳送可存取的郵件給最需要它的人員：** Outlook 會顯示郵件提示，協助確保將您的內容傳送給偏好可存取內容的使用者時可供其存取。

### <a name="powerpoint"></a>PowerPoint

- **最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。

### <a name="visio"></a>Visio

- **在 Excel 中製作精美的 Visio 圖表：** 在 Excel 中快速且輕鬆地將資料呈現為精美的 Visio 圖表。 [深入了解](https://support.office.com/zh-TW/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **改善共同撰寫：** 改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。

### <a name="office-suite"></a>Office 套件

- **上傳中心將由需要注意的檔案體驗取代：**「上傳中心」將由會顯示在 Office 應用程式的 [檔案] > [開啟] 下的「需要注意的檔案」體驗取代。 相較於上傳中心，此新體驗更為現代化、整合且更不具侵入性。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 記錄計數可能不正確。

### <a name="excel"></a>Excel

- 解決在刪除含有的走勢圖參考另一個資料表中資料的資料表時，會導致重新開啟檔案時，將檔案識別為已損毀的問題。
- 無法儲存對圖表大小的變更。
- 核取方塊無法正確呈現。
- [選取資料來源] 對話方塊上的部分欄位並未區分大小寫。
- 某些 VBA 函數會針對新的圖表類型傳回錯誤。
- 可能已防止使用者以 Office 365 Excel 活頁簿格式儲存。
- 解決使用自動調整來調整列高時，核取方塊控制項可能收縮的問題。
- 解決當您將報表篩選隨著其餘的樞紐分析表一起轉換，以用於 SQL 表格式伺服器的查詢時，可能會遇到結果不正確的問題。
- 解決從不受信任的網路共用編輯受保護的檔案時，Excel 可能會失敗的問題。
- 同時使用朗讀程式和放大鏡，可能會導致失敗。
- 解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。
- 我們已大幅改善刪除有合併儲存格之欄的效能。

### <a name="onenote"></a>OneNote

- 發現可能會影響從本機資源同步至雲端資源的問題。

### <a name="outlook"></a>Outlook

- 會議室尋找工具可能會對可用的會議室顯示 [無]&quot;&quot;。
- 發現當功能區設定為自動隱藏時，搜尋方塊可能消失的問題。
- 發現簽署具有數位簽署附件的電子郵件時，可能導致數位簽章遭到破壞的問題。
- 轉寄的電子郵件可能會遺失內嵌的影像。
- 使用者可能無法建立具有嚴格租用戶限制的 Outlook 設定檔。
- 發現在將長檔名拖放至郵件內文時，長檔名遭到截斷的問題。

### <a name="powerpoint"></a>PowerPoint

- 無法儲存對圖表大小的變更。
- 同時使用朗讀程式和放大鏡，可能會導致失敗。
- 發現投影片預覽的長寬比未正確鎖定/解除鎖定的問題。

### <a name="project"></a>Project

- 發現在執行更新工作時，若輸入記事，可能不會保留記事的問題。
- 使用者無法將工作標示為已完成，並將它設為 99%。
- 資源撫平無法解決資源過度分派問題。
- 發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。
- 發現檔案可能遭某個使用者鎖定，但不會在錯誤訊息中顯示任何使用者名稱的問題。

### <a name="publisher"></a>Publisher

- 圖形可能會顯示在圖形框線以外。

### <a name="word"></a>Word

- 內容功能表中未顯示校訂建議。
- 無法儲存對圖表大小的變更。
- 圖形可能會顯示在圖形框線以外。
- 發現使用螢幕閱讀器檢視註解時的問題。
- 發現將某些評論錯誤地識別為拼寫或文法評論的問題。
- 來自 Outlook 郵件中的 cid: 影像連結現在能在要求時成功中斷。
- 使用韓文/英文自動校正時，可能出現不正確的字元。
- 從瀏覽窗格搜尋可能會失敗。
- 同時使用朗讀程式和放大鏡，可能會導致失敗。
- 對註解套用不正確的內容原則。
- 在應優先套用較高的原則標籤前，可能已套用了較低的原則標籤。
- 開啟舊版文件，然後移至 [資訊] 索引標籤會導致失敗。
- 發現新留言對話方塊有時候未取得焦點的問題。
- 將格式設定套用到 @ 提及之後，可能會防止開啟連絡人卡片。
- 醒目提示文字可能很困難。
- 解決使用者可能無法儲存 Word、Excel 和 PowerPoint 文件的問題。 此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存新檔] 選項的使用者。
- 以深色文字編寫的舊版註解在深色模式中不會顯示。
- 可能已防止使用者在編輯器中瀏覽個別項目。
- 可能不會將文法或拼寫錯誤醒目提示。

### <a name="office-suite"></a>Office 套件

- 某些繪圖可能不會在預覽或投影片放映中顯示。
- 我們已修正了「另一個安裝正在進行中」的不正確錯誤訊息可能導致無法升級的問題。
- 在垂直文字方塊中，部分片假名字元可能無法正確顯示。
- 嘗試將檔案儲存到已中斷連線的網路共用時可能會導致失敗。
- 在 Windows 7 上使用圖形時的效能問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

