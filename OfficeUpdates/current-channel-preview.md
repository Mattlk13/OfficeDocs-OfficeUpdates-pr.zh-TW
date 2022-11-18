---
title: 版本資訊目前通道 (預覽)
ms.author: nidos
author: nidos
manager: nodos
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 慢」對象提供新功能、修正或已知問題的最新清單
ms.openlocfilehash: 43e33843b8215d3bf0371510d67c0ce8ceb0e152
ms.sourcegitcommit: 3af778564ac39ee5f6e4a85ff7c0575b9b7435b0
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/12/2022
ms.locfileid: "68541194"
---
# <a name="release-notes-for-office-current-channel-preview"></a>Office 版本資訊目前通道 (預覽)

本文包含 Windows 電腦版之 Word、Excel、PowerPoint、Outlook、Access、Project 與 Teams 目前通道 (預覽) 組建的版本資訊。 我們每週都強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。 請注意，我們通常會在一段時間內推出功能 (有時甚至推出修正程式) 至目前通道 (預覽)。 這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。 所以，如果你沒有看到下面描述的項目，不要擔心你最終會得到它。  


> [!NOTE]
> - 版本資訊發佈日期可能與實際組建發行日期不相符。
> - Microsoft Teams 功能可能會與最新的目前通道預覽中發行的功能不同，因為它們的發行頻率較高。

[//]: # (DO NOT REMOVE)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2210-october-11"></a>版本 2210：10 月 11 日
*版本 2210 (組建 15726.20096)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致某些設定檔已設定多個 Exchange 帳戶的電子郵件卡在發件匣中的問題。


### <a name="project"></a>Project

- 我們已修正使用表單型驗證時，Project 無法連線到 Project Server 的第二個問題。 在某些情況下，能夠連線的使用者，例如前一天無法連線到第二天。 刪除伺服器連線設定檔會暫時修正此問題。


### <a name="word"></a>Word

- 我們已修正將來源格式化結果貼到內容控制項中時，會顯示問號 (？) 或空白方塊等字元的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2210-october-03"></a>版本 2210：10 月 3 日
*版本 2210 (組建 15726.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **動態陣列與圖表整合：** 此功能可讓使用者將圖表連結至動態陣列計算，這會產生可變長度的結果。 重新計算陣列時，圖表會自動更新以擷取所有資料，而不是固定為特定數目的資料點。

### <a name="outlook"></a>Outlook

- **封鎖數位列印：** 如果強制開啟，請針對已加上標籤的電子郵件封鎖所有列印到數位印表機。

### <a name="powerpoint"></a>PowerPoint

- **編輯自動產生的替代文字：** 現在您可以在 PowerPoint 中編輯相片的智慧型替代文字。 [深入了解](https://support.office.com/article/6f7772b2-2f33-4bd2-8ca7-dae3b2b3ef25)

- **第一類檔復原：** 這是 PowerPoint for Windows 簡報的簡化復原體驗，可協助使用者在非預期的應用程式結束時快速恢復生產力。

### <a name="word"></a>Word

- **在內容中接受和拒絕建議：** 只要按一下或點選建議，即可輕鬆預覽建議的變更。 請使用核取記號來接受 ，而 X 則會在檔內容中立即拒絕。<br />在[部落格文章](https://insider.office.com/en-us/blog/review-tracked-changes-with-new-cards-in-word)中查看詳細資料

### <a name="office-suite"></a>Office 套件

- **協力廠商登入的 WebView2：** 這項功能會將目前瀏覽器引擎的登入對話方塊從 Internet Explorer 更新為以 chromium 為基礎的 WebView2 (Microsoft Edge) 。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正使用觸控板縮放之後，某些內容可能無法正確顯示的問題。


- 我們已修正當 alttext 沒有值時，函式會用完資源或顯示錯誤錯誤訊息的問題。


- 我們已修正文字格式設定導致 Excel 停止運作的問題。


- 我們已修正應用程式在 RTL 工作表上進行觸控式縮放時，會停止回應並耗用大量記憶體的問題。


- 我們已修正與圖形相關的間歇性、非預期關閉。


### <a name="onenote"></a>OneNote

- 我們已修正在畫布上插入圖形或線條之後，使用者無法拖曳或調整物件大小的問題。


- 我們已修正使用者無法搭配手寫筆使用移動流覽工具的問題。


### <a name="outlook"></a>Outlook

- 我們已修正 Web 檢視在重新開機和取消時顯示錯誤訊息的問題。


- 我們已修正讀取或撰寫訊息時看不到捲軸的問題。


- 我們已修正讀取或撰寫訊息時看不到捲軸的問題。


- 我們已修正中斷 IMAP IDLE 會話連線導致 IMAP 同步停止，直到重新開機的問題。


- 我們已修正 SharePoint 檔在附加為複本時，不會針對超過指定大小的 URL 下載的問題。


- 我們已修正搜尋一律會從主要帳戶傳回結果，而不是從選取的帳戶傳回的結果的問題。


- 我們已修正在嘗試為連絡人圖片空白的人載入連絡人卡片時，導致使用者意外遇到關閉的問題。


- 我們已修正導致使用者在開機後短暫意外關閉的問題。


- 我們已修正提交意見反應時導致 Outlook 意外關閉的問題。


- 我們已修正會導致停用服務通知的使用者看到已淘汰的 UI 顯示通知服務已停用的問題。


- 我們已修正在將附件拖放至郵件訊息時，導致附件大小限制無法評估的問題。


- 我們已修正關閉郵件控制台時，應用程式意外關閉的問題。


- 我們已修正與圖形相關的間歇性、非預期關閉。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正與圖形相關的間歇性、非預期關閉。


- 我們已修正當存取為 IOleObject 時，PowerPoint 無法關閉的問題。


### <a name="project"></a>Project

- 我們已修正當資源的名稱包含系統清單分隔符號時，有時無法將資源同步處理至 SharePoint 清單的問題。


- 我們已修正只套用一個跨專案連結選項的問題，即使已選取多個選項也一樣。


### <a name="publisher"></a>發行者

- 我們已修正與圖形相關的間歇性、非預期關閉。


### <a name="word"></a>Word

- 我們已修正與圖形相關的間歇性、非預期關閉。


- 我們已修正在 Windows Server 2016 上部署 Microsoft 365 時，無法使用大聲朗讀功能的問題。


- 我們已修正大型 URL 的問題: 如果其長度超過特定字元限制, 在此情況下無法開啟連結。


- 我們已修正超連結無法運作，且顯示錯誤的問題。


- 我們已修正應用程式防護在互動模式中的問題。


- 我們已修正使用輸入法編輯器 (輸入法) 時的即時輸入問題。


- 我們已修正分割文件視窗之後，下方視窗不會捲動到游標下方的預期位置的問題。


- 我們已修正共同撰寫時會移除標頭樣式的問題。


- 我們已修正下列問題：如果內建標籤新增了頁尾，它會不正確地移動現有的手動新增頁尾。


### <a name="office-suite"></a>Office 套件

- 我們已修正從 Sharepoint 2019 文件庫開啟的 Excel 檔案在 Windows 版 Excel 中間歇性開啟為唯讀的問題。


- 我們已修正導致鎖定的 Word 和 Excel 檔案無法開啟的問題。


- 我們已修正當圖示大小更新時，QAT 中標籤的字型大小意外增加的問題。


- 根據預設，在生產環境中從網際網路啟用功能封鎖宏。


- 我們已修正在包含文字的某些 SVG 圖形上執行 [轉換成圖形] 時的問題。


- 我們已修正將 SVG 內容的 PowerPoint 投影片儲存速度變慢為元檔案格式的問題。


- 我們已修正客戶憑證未正確顯示為已撤銷的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2209-september-26"></a>版本 2209：9 月 26 日
*版本 2209 (組建 15629.20156)*

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **在一起模式中指派基座：** 允許會議召集人將基座指派給在一起模式中的參與者。

- **群組聊天中的建議回復：** 建議的回復現在可在群組聊天中使用，可讓您在群組聊天中提及或在群組聊天中進行 1：1 交談時，選取快速回應。

- **在 Teams 會議中自動檢視最多 49 個影片 (7x7) ：** 根據預設，Microsoft Teams 會議在畫面上最多支援 9 部影片 (3x3) ， (也就是資源庫檢視) 。 若要查看超過 9 部影片，使用者必須手動選取 [大型資源庫] 檢視。 透過此更新，使用者預設可以自動在其螢幕上看到最多 49 個影片 (7x7) ，而不需要明確動作。 使用者實際看到的影片數目將取決於硬體/裝置功能。

- **VMware 的 HID 支援：** 此功能支援在虛擬桌面基礎結構 (VDI) 的 Microsoft Teams 中使用人性化介面裝置 (HID) 。

- **Microsoft Teams：** 管理員設定來關閉 Windows 上Teams 會議室的分割視訊版面配置。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2209-september-23"></a>版本 2209：9 月 23 日
*版本 2209 (組建 15629.20152)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致停用服務通知的使用者看到已淘汰的 UI 顯示通知服務已停用的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正預設封鎖網際網路宏執行的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2209-september-19"></a>版本 2209：9 月 19 日
*版本 2209 (組建 15629.20118)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正在行事曆模組中切換檢視時，導致使用者意外遇到關閉的問題。


- 我們已修正導致使用者在開機後短暫意外關閉的問題。


- 我們已修正提交意見反應時導致 Outlook 意外關閉的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2209-september-12"></a>版本 2209：9 月 12 日
*版本 2209 (組建 15629.20070)*
* 各種錯誤和效能修正。

## <a name="version-2209-september-07"></a>版本 2209：9 月 7 日
*版本 2209 (組建 15629.20058)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正在匯入或匯出時檢查 [儲存步驟] 方塊時，未顯示其他詳細資料和選項的問題。


- 我們已修正在 DAO 記錄集中迴圈時的 Access VBA 效能問題。


- 我們已修正以特定方式開啟資料庫損毀可能會導致 Access 意外關閉的問題。


- 我們已修正使用 DAO 或 OLEDB 介面讀取 Access 資料庫時，如果記憶體需求成長速度太快，應用程式會意外關閉的問題。


### <a name="excel"></a>Excel

- 我們已修正導致上傳至新儲存檔案 OneDrive 的問題，該檔案已套用敏感度標籤，並已進行編輯以停止運作。


- 我們已修正當檔案開啟但未修改時，SharePoint 中的 [修改日期] 欄位已更新的問題。


- 我們已修正存取其中包含豐富實體的檔案時，應用程式意外關閉的問題。


- 在 Office 2016 和 Office 365 Visual Refresh 中，已改善工作窗格和對話方塊中彩色和白色主題中暫留和按下滑杆的可見度。<br />
- 在已啟用 Fluent 視覺效果的Office 365中，已改善工作窗格和對話方塊中深灰色和黑色主題中暫留和按下滑杆的可見度。<br />
- 在具有 Visual Refresh Darky Gray 主題的Office 365中，防止捲動按鈕框線出現在功能區字型選擇器下拉式清單中的問題已解決。


- 我們已修正特定功能表庫專案上顯示不正確背景色彩的問題。


- 我們已修正當 [指導] 標記顯示在螢幕上時，使用者在選取 [插入資料表] 命令之後，無法選取資料表資料列和資料行的問題。


- 我們已修正只影響日文語言使用者導致宏無法再運作的問題。


- 我們已修正在資料列或資料行座標軸上樞紐分析表的某些儲存格上設定格式 (例如填滿色彩) ，然後將這些欄位移至樞紐分析表的 [篩選] 區域之後，Excel 檔案可能會損毀的問題。


- 我們已修正密碼快取函式無法與 MSQuery x64 組建搭配運作的問題。


- 我們已修正在從右至左方向使用工作表時，反轉工作表索引標籤導覽按鈕的問題。 此問題的原因是，Office UI 中左右按鈕的定義會翻轉，而且目前正在據以設定。


- 我們已修正將文字轉換成資料行時，Excel 不正確地使用固定寬度而非全形空間的問題。


- 我們已修正 LAMBDA 結構 MAKEARRAY 無法正確解決的問題。


### <a name="outlook"></a>Outlook

- 此變更會啟用協力廠商會議應用程式的 [每個會議線上] 選項。


- 我們已修正導致自訂快速存取工具列檔案 (.exportedUI) 在使用簡化功能區時無法匯入的問題。


- 我們已修正會導致使用者無法在 Outlook Desktop 中看到搜尋結果的到期日的問題。


- 我們已修正啟用自動回復時，朗讀程式未讀取辦公室外狀態的協助工具問題。


- 我們已修正回復或轉寄訊息時，連結的影像不會顯示的問題。


### <a name="powerpoint"></a>PowerPoint

- 在 Office 2016 和 Office 365 Visual Refresh 中，已改善工作窗格和對話方塊中彩色和白色主題中暫留和按下滑杆的可見度。<br />
- 在已啟用 Fluent 視覺效果的Office 365中，已改善工作窗格和對話方塊中深灰色和黑色主題中暫留和按下滑杆的可見度。<br />
- 在具有 Visual Refresh Darky Gray 主題的Office 365中，防止捲動按鈕框線出現在功能區字型選擇器下拉式清單中的問題已解決。


- 我們已修正導致圖片裁剪無法正常運作的問題。


- 我們已修正使用者因為加密許可權而無法結束應用程式的問題。


### <a name="project"></a>Project

- 我們已修正與語音存取相關的協助工具問題，其中資料行標題號碼不會出現在 [排程詳細資料] 頁面等方格中。


- 我們已修正無法再開啟專案的問題，因為儲存專案時會產生新的工作和工作分派 GUID。


- 我們已修正只有在 [工作資訊] 對話方塊中的 [資源] 索引標籤未在方格內顯示四個預期的資料行時，才會影響希伯來文的問題。


- 我們已修正可能導致長時間發佈作業、伺服器上的記憶體使用量過高，甚至是無法再開啟專案的問題。 在 Project 傳統型應用程式中，可能會不小心建立數十萬個空白工作。 修正有助於防止發生這種情況。


- 我們已修正修改時幅時，可能會檢視和報告不正確的實際成本值的問題。


- 我們已修正開啟未包含任何連結的專案時，訊息出現錯誤警告客戶可能不安全連結的問題。


### <a name="visio"></a>Visio

- Office 365安裝程式現在會在 IE 模式中將檔案關聯至 Edge，而不是 Internet Explorer。


### <a name="word"></a>Word

- 在 Office 2016 和 Office 365 Visual Refresh 中，已改善工作窗格和對話方塊中彩色和白色主題中暫留和按下滑杆的可見度。<br />
- 在已啟用 Fluent 視覺效果的Office 365中，已改善工作窗格和對話方塊中深灰色和黑色主題中暫留和按下滑杆的可見度。<br />
- 在具有 Visual Refresh Darky Gray 主題的Office 365中，防止捲動按鈕框線出現在功能區字型選擇器下拉式清單中的問題已解決。


- 我們已修正導致 Word 中間歇性停止運作的問題。


- 我們已修正在儲存包含 3D 內容的檔時，應用程式會停止回應的問題。


- 我們已修正從Microsoft 小畫家貼上圖片時，應用程式會顯示錯誤訊息的問題。


- 我們已修正使用者無法將資料表的資料列從版本歷程記錄中的舊版複製到目前版本的問題。


- 我們已修正 Outlook 無法開啟使用Outlook 網頁版傳送的訊息，且包含從 Word 複製的批註的問題。


- 我們已修正使用追蹤變更時，應用程式無法接受所有變更的問題。


- 我們已修正在許多檔使用工作管理員關閉，且稍後在 Word 再次開啟時還原之後，狀態列中的檢視模式切換器會在其中一份檔中停用，同時在所有其他檔中啟用的問題。


- 我們已修正使用者可能無法在追蹤變更中按一下超連結的問題。


- 我們已修正批註可能無法載入的問題。


- 我們已修正旋轉文字方塊中的內容變成水準，而文字藝術師文字效果在匯出至 PDF/A 時隱藏的問題。


- 我們已修正因為忙碌的伺服器錯誤而導致變更無法合併到共用檔的問題。


- 我們已修正合併衝突期間商務列中的問題。


- 我們已修正共同撰寫時移除標頭樣式的問題。


- 我們已修正當所有開啟的檔案視窗最小化時，Word 可能不會顯示正確的檔案的問題。


- 我們已修正 [檔案>資訊] 下可能會顯示過期屬性值的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正嘗試將 Office 檔案或 Outlook 附件儲存至網路共用路徑時，狀態訊息會顯示並在螢幕上停留數分鐘的問題。


- 我們已修正當檔案開啟但未修改時，SharePoint 中的 [修改日期] 欄位已更新的問題。


- 我們已修正在工具列 (預覽) 與傳統之間切換命令模式時，模式切換不適用於所有作用中應用程式視窗的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2208-august-29"></a>版本 2208：8 月 29 日
*版本 2208 (組建 15601.20088)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="word"></a>Word

- 我們已修正使用者無法將資料表的資料列從版本歷程記錄中的舊版複製到目前版本的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2208-august-26"></a>版本 2208：8 月 26 日
*版本 2208 (組建 15601.20078)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正在新應用程式行中以滑鼠右鍵按一下應用程式時，Outlook 有時會意外關閉的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2208-august-23"></a>版本 2208：8 月 23 日
*版本 2208 (組建 15601.20064)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此更新修正了在 Excel 中逐一查看 VBA 程式碼中的 DAO 記錄集時，可能會導致記憶體流失的問題。


### <a name="excel"></a>Excel

- 我們已修正編輯新建立的檔案時，商務列標籤未正確上傳的問題。


### <a name="outlook"></a>Outlook

- 此變更會啟用協力廠商會議應用程式的 [每個會議線上] 選項。


- 我們已修正會導致使用者在回復或轉寄訊息時無法載入連結影像的問題。


### <a name="project"></a>Project

- 我們已修正無法再開啟之前正常運作的專案的問題。 在此情況下，Project 意外關閉。


- 我們已修正此訊息的問題：「此專案包含一或多個可能不安全且已停用的資料來源連結。 您要啟用這些資料來源嗎？ 只有當您信任檔案的來源時，才能這麼做。」 開啟專案時可能會出現。 即使專案沒有任何作用中的貼上連結，訊息也會出現。 此外，在甘特圖類型檢視中找不到使用中的内嵌物件。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2208-august-16"></a>版本 2208：8 月 16 日
*版本 2208 (組建 15601.20044)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正某些使用者無法搭配現有匯入/匯出規格使用 DoCmd.TransferText 的問題


- 我們已修正關閉資料庫時，[關閉時清除快取] 選項不會刪除快取的問題。


- 我們已修正可能導致綁定物件框架的 [班級] 屬性會返回空字串的問題，即使控制項有值也一樣。


- 我們已修正客戶在匯出至 Excel 時，長文字欄位中的資料被截斷的問題。


### <a name="excel"></a>Excel

- 我們已修正應用程式與字型互動時意外關閉檔案的問題。


- 我們已修正工作窗格中標頭格式的問題。


- 我們已修正在放大 170% 以上時，Excel 圖表內容遺失的問題。


### <a name="outlook"></a>Outlook

- 我們修正了透過雲端設定進行設定時，導致某些郵件儲存空間相關的設定無法如預期般套用的問題。


- 我們已修正導致範本無法正確載入的敏感度標籤範本數量限制問題。


- 我們已修正會導致使用者在其左側滑軌導覽列中看到 [日誌] 模組的問題。


- 我們已修正 Outlook 搜尋中，綠色的 [已回覆] 圖示未在已回覆電子郵件旁出現的問題。


- 我們已修正使用者在 Outlook 訊息中選擇 [在瀏覽器中檢視] 選項之後，導致檔案無法在 Edge 中開啟的問題。


- 我們已修正導致在 Windows Server 2016 上對 Outlook 快顯通知執行的動作停止如預期方式執行的問題。


- 我們已修正嘗試擷取 EDP 電子郵件地址時影響 Windows 資訊保護 (WIP) 的問題。


- 我們已修正使用 [搜尋人員] 方塊時 Outlook 意外關閉的問題。


- 我們修正了嘗試展開群組時，商務用 Skype 意外關閉的問題。


- 我們已修正開啟、回復或轉寄一些包含複雜資料表的電子郵件，Outlook 停止回應的問題。 相同的資料表內容也會導致 Word 停止回應。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正在安全性警告上按一下 [啟用內容] 之後，圖片的縮圖內容無法在投影片上正確轉譯的問題。


- 我們已透過對快速存取工具列進行微幅更新以修正問題。


### <a name="project"></a>Project

- 我們已修正時程表中的實際小時總計不一定會正確重新計算的問題。


- 我們已修正本機自訂欄位停止運作、提示 [刪除自訂欄位] 對話方塊，且無法透過召集人刪除的問題。


- 我們已修正問題，因此當向上和向下捲動檢視甘特圖時，進度線現在會隨著工作垂直捲動。


- 我們已修正當配置模式設定為手動時，在 [網狀圖] 檢視中向下卷動時不一定會繪製節點的問題。


- 我們已修正在檢視和報告指派時段實際成本值時的問題。 這些值的總和可能不等於您在工作表檢視) 中看到的值 (純量值。 當時幅細微性從每日等非常詳細到較不詳細，例如每年，加總值和純量值之間的差異可能相當顯著。


### <a name="word"></a>Word

- 我們已修正開啟、回復或轉寄一些包含複雜資料表的電子郵件，Outlook 停止回應的問題。 相同的資料表內容也會導致 Word 停止回應。


- 我們已修正使用者無法開啟指向 SPO/OD4B 上檔案書籤之本地受管理檔案的連結問題。


- 我們已修正導致 Word 中間歇性停止回應的問題。


- 我們已修正應用程式在關閉文件後會封鎖其存取的問題，因此 OneDrive 在應用程式結束之前無法同步處理文件。


- 我們已修正 Outlook (WordMail) 訊息會在放大或縮小時出現白色背景閃爍的問題。


- 我們已修正註解可能會在將文件匯出為 PDF 後，從第二頁開始消失的問題。


- 我們已修正當相似性檢查程式無法使用時，新增使用者行為記錄的問題。


- 我們已修正在 Word 文件中列印多個頁面範圍的複本時，可能無法運作的問題。


- 我們已修正「以連結貼上」可能無法自動更新的問題。


- 我們已修正超連結可能會變更為錯誤的問題！ 超連結參考無效。」


- 我們已修正應用程式在開啟 Outlook 郵件的 HTML 檔案版本時發生延遲的問題。


- 我們已修正篇幅較長且具有欄位的文件效能可能會變慢的問題。


- 我們已修正的連結不會自動更新為內嵌的 Word 文件的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正某些使用者無法存取 SPO 上託管的最新版本 Excel 檔案，並且看到「重新更新建議」錯誤訊息的問題。


- 我們已修正開啟儲存在 OneDrive 和 SharePoint Online 上的 Excel 檔案時，應用程式可能會意外關閉，而且可能會發生資料遺失的問題。


- 我們已修正導致某些人員在開機之後，突然遇到關閉的問題。


- 我們已修正安全性標籤所指定的保護以及套用至文件的實際保護不對齊的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2207-august-08"></a>版本 2207：8 月 08 日
*版本 2207 (組建 15427.20210)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正導致某些人員在開機之後，突然遇到關閉的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正錄製簡報時發生錯誤且錄製會停止的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2207-august-03"></a>版本 2207：8 月 03 日
*版本 2207 (組建 15427.20194)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="project"></a>Project

- 我們已修正一個問題：在檢視和報告關於指派時段實際成本值時，這些值的總和可能不等於純量值 (您在工作表檢視中看到的值)。 隨著時幅細微性從詳細 (例如每日) 變為較不詳細 (例如每年)，差異可能會增加。


### <a name="word"></a>Word

- 我們已修正 Outlook (WordMail) 訊息會在放大或縮小時出現白色背景閃爍的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2207-july-29"></a>版本 2207: 7 月 29 日
*版本 2207 (組建 15427.20178)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致使用者在其左側滑軌導覽列中看到 [日誌] 模組的問題。


- 我們已修正導致 Exchange 2019 使用者看到 Outlook 無法在搜尋結果中的郵件上顯示回覆指標圖示的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2207-july-25"></a>版本 2207: 7 月 25 日
*版本 2207 (組建 15427.20156)*
* 各種錯誤和效能修正。

## <a name="version-2207-july-22"></a>版本 2207: 7 月 22 日
*版本 2207 (組建 15427.20148)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="word"></a>Word

- 我們已修正在列印含有索引的頁面時，可能無法列印的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2207-july-19"></a>版本 2207: 7 月 19 日
*版本 2207 (組建 15427.20130)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="office-suite"></a>Office 套件

- 我們已修正介紹新視覺效果的影片未顯示的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2207-july-14"></a>版本 2207：7 月 14 日
*版本 2207 (組建 15427.20090)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正 Dataverse 在 2019 功能區中顯示的問題。


- 我們已修正嘗試在唯一識別碼欄中支援 Unicode 字元時會發生的問題。


### <a name="excel"></a>Excel

- 我們已修正應用程式與字型互動時意外關閉檔案的問題。


- 我們已修正在某些情況下，在啟動 Excel 且 [開始] 畫面已停用之後，開啟活頁簿時，公式列背景的某些部分會不正確地顯示為白色的問題。


- 我們已修正當使用者在儲存和關閉之後立即重新開啟應用程式時，受保護標籤停止運作的問題。


- 我們已修正圖表中儲存格參照顯示不正確的問題。


- 我們已修正應用程式會針對特定電腦上的特定檔案產生錯誤，指出「無法在受保護的檢視中開啟檔案」的問題。


- 我們已修正在選擇 [檔案] > [關閉] 或按 Ctrl+W 關閉最後一個活頁簿時，導致 Excel 完全關閉的問題。


### <a name="onenote"></a>OneNote

- 我們已修正導致應用程式意外關閉的問題。


- 我們已修正在畫布上插入圖形或線條之後，選取圖形或線條來移動或調整大小時，游標不會變更的問題。


### <a name="outlook"></a>Outlook

- 我們已修正在 GCC High 環境中導致會議室尋找工具無法載入的問題。


- 我們已修正下列問題：如果在使用 Outlook 的 [插入連結] 選項插入的連結上，使用者的預設連結權限類型設定為「特定人員」，權限未如預期般授與收件者 (可能會產生錯誤)。


- 我們已修正使用者建立並共用的連絡人資料夾，已為收件者啟用可編輯連絡人資訊，但收到的資料夾具有僅檢視權限的問題。


- 我們已修正應用程式產生錯誤訊息的問題，指出「嘗試的作業失敗」。 搜尋 LDAP 通訊錄時找不到物件」。


- 我們已修正當使用者在未要求回應時，從讀取窗格按兩下會議的 [暫訂] 回應按鈕，應用程式會意外關閉的問題。


- 我們已修正導致未啟用的「在電話上播放」按鈕啟用的問題。


- 我們已修正應用程式會錯誤地為設定檔中其他 Exchange 帳戶建立新群組組態的問題。


- 我們已修正使用者無法將會議室信箱新增至行事曆的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用包含輔色字元的小型大寫字時，字元大小不正確的問題。


- 我們已修正自訂文件屬性的變更不一定會反映在使用者介面中的問題。


- 我們已修正表格樣式選項有時會由於資訊版權管理而不正確地停用的問題。


### <a name="publisher"></a>發行者

- 我們已修正將 3D 效果套用至應用程式中的圖片時所發生的問題。


### <a name="word"></a>Word

- 我們已修正 UI 有時候停止在 ARM64 裝置上呈現的問題。


- 我們已修正將 3D 效果套用至應用程式中的圖片時所發生的問題。


- 我們已修正導致應用程式未正確重新整理的問題。


- 我們已修正將檔案儲存為 Adobe PDF 時，應用程式會意外關閉的問題。


- 我們已修正當使用者按兩下以隱藏空白字元時，隱藏內容的問題。


- 我們已解決 Word 未列印多個選取檔案的問題。


- 我們已修正內建標籤所新增的頁尾不正確地移動現有、手動新增頁尾的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正在某些情況下，CLP 保護檔案的背景上傳會導致資料遺失或保護遺失的問題。


- 我們已修正使用儲存在 SharePoint Online 或 OneDrive 中的檔案可能會導致記憶體外洩的問題。


- 我們已修正功能區選項功能表未在 Excel 中轉譯的問題。


- 我們已修正按一下 [檔案] 索引標籤開啟 Backstage 時，Office 應用程式的視覺雜訊問題。


- 我們已修正裁剪的影像在預覽列印中顯示模糊的問題。


- 我們已修正問題，以便正確辨識並插入來自 Adobe 和 Inkscape 的 SVG 格式。


- 我們已修正會影響從各種網站辨識和插入 SVG 檔案的問題。


- 我們已修正此問題，讓共同撰寫功能的線上使用者在他們沒有存取權限的敏感度標籤由其他使用者套用時收到通知。


- 我們已修正使用筆跡進行數學運算時，應用程式會意外關閉的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2206-july-06"></a>版本 2206：7 月 6 日
*版本 2206 (組建 15330.20230)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正資料編輯列中的視覺問題。


### <a name="visio"></a>Visio

- 我們已修正 Visio 中導致應用程式在重複放大和縮小時停止回應的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2206-june-24"></a>版本 2206：6 月 24 日
*版本 2206 (組建 15330.20196)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正在 GCC-High 環境中導致會議室尋找工具無法載入的問題。


- 我們已修正使用者無法將會議室信箱新增至行事曆的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2206-june-14"></a>版本 2206：6 月 14 日
*版本 2206 (組建 15330.20114)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正可能導致朗讀程式停止工作以讀取 [輸入參數值] 對話方塊中的標記的問題。


- 我們已修正使用 DAO 欄位屬性集合，新增取得資料表欄位精確度和縮放屬性的能力的問題。


- 我們已修正 Dataverse 在 2019 功能區中顯示的問題。


- 我們已修正了在匯入文字檔案時，可能會導致使用 AM/PM 指定的日期/時間值剖析不正確的問題。


- 我們已修正當未顯示小數秒數時，可能會導致日期/時間延伸欄位格式不正確的問題。


- 我們已修正可能會導致日期/時間延伸欄位顯示不正確的一周日期的問題。


- 我們已修正將記錄插入已結合至 ADO 記錄集的表單時，先前建立的記錄會顯示為空白的問題。


- 我們已修正嘗試在唯一識別碼欄中支援 Unicode 字元時所造成的問題。


- 我們已修正在使用 Access 資料庫引擎 OLEDB API 與包含 SharePoint 清單之連結的資料庫時，可能會導致應用程式意外關閉的問題。


- 我們已修正嘗試在唯一識別碼欄中支援 Unicode 字元時所造成的問題。


- 我們已修正可能導致將報表匯出至 Excel 時停止運作，沒有錯誤訊息的問題。


- 我們已修正來自使用者先前執行未發生事件的現有程式碼耗費過長時間執行的效能問題。


- 我們已修正將 .csv 檔案匯入 Access 時影響效能的問題。


- 我們已修正可能造成版面配置格線無法正確繪製的問題。


- 新增表格工作窗格現在在您關閉或重新開啟或切換索引鍵時重新出現篩選。


- 在功能窗格中搜尋時，不再修剪前導和尾隨空格，導致更精確的搜尋結果。


- 當焦點位於功能窗格時，GoToRecord 動作現在可運作。


- 記錄導航器現在會適當調整大小，以在記錄計數很大時顯示完整數位。


- 我們已修正當焦點位於日期/時間延伸欄位時，可能會導致日期選擇器停止顯示的問題。


- 我們已修正可能導致綁定物件框架的 [班級] 屬性會返回空字串的問題，即使控制項有值也一樣。


- 我們已修正如果目前的控制項位於子表單中，可能會導致 DoCmd.RunCommand acCmdShowDatePicker 停止運作的問題。


- 我們已修正提示「沒有目前記錄」錯誤和其他訊息的問題。


- 我們已修正可能導致資料表因欄位名稱重複，而無法儲存的問題，即使沒有重複的欄位名稱也一樣。


- 我們已修正可能導致 Access 不正確地處理 UTF-8 格式的文字檔案的輸入問題。


### <a name="excel"></a>Excel

- 我們已修正在 VBA 巨集中執行程式碼以關閉 Application.ScreenUpdating 時，使用中的工作表會顯示空白的問題。


- 我們已修正在背景 (在 Windows 鎖定畫面中) Office 更新之後，導致 Excel 中資料標籤中的使用者設定檔圖片和資料類型區段遺失的問題。


- 我們已修復導致 Excel 停止回應的問題。


- 我們已修正 AMSI 掃描會導致應用程式意外關閉的問題。


- 我們已解決當套用帶有加密的預設敏感度標籤時，圖表不會插入 PowerPoint 投影片或 Word 文件的問題。


- 我們已修正當連結的 Excel 檔案開啟時，使用者無法更新 PowerPoint 中連結的問題。


- 我們已修正開啟從 SharePoint 清單匯出的 .iqy 檔案時，應用程式會意外關閉的問題。


- 我們已修正在具有圖表工作表的活頁簿上執行 VBA 指令碼/增益集時，可能會導致應用程式意外關閉的問題。


- 我們已修正 .xls 格式的共用活頁簿可能會不當合併變更的問題。


- 我們已修正使用特定舊版 Windows 11 時，在 Excel 和 Project 中呈現的問題。


- 我們已修正資料編輯列中的視覺問題。


- 我們已修正在將列插入到方向爲從右至左的工作表中時出現之與圖形錨定相關的問題。


- 我們已修正類似但不同的影像可能無法正確處理的問題。


- 我們已修正使用 [從剪貼簿變更圖片] 時出現的問題，以便 SVG 內容正確顯示。


- 我們已修正有關將圖示轉換為圖形，以在儲存和重新開啟後保留可見度的問題。


- 我們已修正導致 Excel 在顯示圖表即時預覽時意外關閉的問題。


- 我們已修正 [插入] 和 [取消] 標籤在高對比主題中未顯示的問題。


- 我們已修正可能導致朗讀程式停止工作以讀取 [輸入參數值] 對話方塊中的標記的問題。


- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


### <a name="onenote"></a>OneNote

- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 我們已修正在畫布上插入圖形或線條之後，使用者無法拖曳或調整物件大小的問題。


### <a name="outlook"></a>Outlook

- 我們已修正在嘗試開啟 Viva Insights 增益集時，導致某些客戶看到灰色方塊的問題。


- 我們已修正造成內部部署 Exchange 使用者不必要的網路流量的問題。


- 我們已修正導致某些 Outlook 使用者在間歇性地開機之後，突然遇到關閉的問題。


- 我們已修正使用 [重新顯示全部] 按鈕時發生錯誤指出作業停止運作的問題。


- 我們已修正導致使用者在開啟線上保存或共用信箱時意外遇到關閉的問題。


- 我們已修正會導致使用者看到「無法執行要求的作業...」錯誤的問題當嘗試展開本機連絡人群組時。


- 我們已修正啟用共用行事曆改進功能時，導致給會議室信箱代理人的所有轉寄會議邀請上顯示「不需要回應」的問題。


- 我們已修正導致使用者看到「嘗試的操作失敗」錯誤訊息的問題。 搜尋 LDAP 通訊錄時找不到物件」。


- 我們已修正導致使用者在某些情況下，會看到呈現多個共用行事曆複本的問題。


- 我們已修正導致使用者在嘗試開啟具有編輯者或代理人許可權的共用連絡人資料夾時看到錯誤訊息的問題。


- 我們已修正當挑選會議邀請中的結束時間大於或等於 12 小時/0.5 天時，導致會議結束時間跳到未來 (超過 12 小時) 的問題。


- 我們已修正回覆電子郵件並變更主旨時，會移除參照及回覆至標頭的問題。


- 我們已修正會導致使用者在某些情況下，會看到呈現多個共用行事曆複本的問題。


- 我們已修正使用 [開啟共用行事曆] 時，未在瀏覽窗格中選取行事曆的問題。


- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 我們已修正類似但不同的影像可能無法正確處理的問題。


- 我們已修正 [插入] 和 [取消] 標籤在高對比主題中未顯示的問題。


- 我們已修正使用瀏覽至位置時，儲存為不需要強制敏感度標籤的問題。


### <a name="project"></a>Project

- 我們已修正 [工作資訊] 等對話方塊內的資料行未以從右至左語言顯示的問題，例如希伯來文。


- 我們已修正使用者開啟先前設定為 100% 完成的專案，但發現進度狀態還原為較低值的問題。


- 我們已修正當表單型驗證與 Azure 應用程式 Proxy 搭配使用時，Project 無法連線至 Project Server 的問題。


- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


### <a name="visio"></a>Visio

- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


### <a name="word"></a>Word

- 我們已修正在少數共同撰寫者實例中，某些註解的回復直到下次開啟文件時才會顯示的問題。


- 我們已修正 UI 有時候停止在 arm64 裝置上呈現的問題。


- 我們已修正 Word 樣式視窗/窗格顯示為空白的問題。


- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 我們已修正在某些 Word 案例顯示內嵌影像的問題。


- 我們已修正 SVG 物件的問題，以便它們可以處理文字錨點結束屬性並正確維持目前文字位置。


- 我們已修正類似但不同的影像可能無法正確處理的問題。


- 我們已修正使用 [從剪貼簿變更圖片] 時出現的問題，以便 SVG 內容正確顯示。


- 我們已修正 [插入] 和 [取消] 標籤在高對比主題中未顯示的問題。


- 我們已修正導致使用者在檔中插入超連結時看到記憶體錯誤的問題。


- 我們已修正導致使用者無法在 [互動] 模式中切換至 [檢閱模式] 的問題。


- 我們已修正當文件處於唯讀模式時，互動模式會顯示「編輯中」的問題。


- 我們已修正文件保護問題 (當例外清單僅包含電子郵件時，「尋找下一個區域...」和「顯示所有區域...」命令可能會停止正常運作)。


- 我們已修正當檔案儲存為 PDF 並開啟 [追蹤修訂] 時，已删除影像上的紅線删除線未顯示的問題。


- 我們已修正以中文 (繁體) Windows 顯示語言匯出 PDF 時，某些特殊字元顯示為其他字型的問題。


- 我們已修正將自動儲存切換為關閉之後，使用者無法將其重新啟用的問題。


- 我們已修正會使得應用程式無法捨棄已停止回應的文件，導致週期性同步處理流程的問題。


- 我們已修正了減少與具有相同超連結之檔的合併衝突的問題。


- 我們已修正 Office 呈現程式碼中關閉的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正在 Excel 中開啟字型大小下拉式清單時，強調顯示字型大小不是文件中目前選取的字型大小的問題。


- 我們已修正 Office 呈現程式碼中意外關閉的問題。


- 我們已修正 SVG 物件的問題，以處理文字錨點結束屬性並正確維持目前文字位置。


- 我們已修正使用相機摘要錄製簡報時出現的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2205-may-23"></a>版本 2205：5 月 23 日
*版本 2205 (組建 15225.20204)*
* 各種錯誤和效能修正。

## <a name="version-2205-may-20"></a>版本 2205：5 月 20 日
*版本 2205 (組建 15225.20194)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **加速公式輸入：** Excel 藉由減少記憶體使用量、更有效率地利用配置的記憶體，以及最佳化重新繪製，明顯加快在儲存格中輸入公式的速度。 這些最佳化效果在慢速記憶體或慢速 CPU 記憶體輸送量的裝置上，以及較大的儲存格範圍上更為明顯。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正導致在 Office 轉譯代碼中意外關閉的問題。


### <a name="onenote"></a>OneNote

- 我們已修正導致在 Office 轉譯代碼中意外關閉的問題。


### <a name="outlook"></a>Outlook

- 我們已修正即使具有正確權限，導致委派仍無法開啟共用連絡人資料夾的問題。


- 我們已修正導致在 Office 轉譯代碼中意外關閉的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正導致在 Office 轉譯代碼中意外關閉的問題。


### <a name="project"></a>Project

- 我們已修正導致在 Office 轉譯代碼中意外關閉的問題。


### <a name="visio"></a>Visio

- 我們已修正導致在 Office 轉譯代碼中意外關閉的問題。


### <a name="word"></a>Word

- 我們已修正導致在 Office 轉譯代碼中意外關閉的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正導致在 Office 轉譯代碼中意外關閉的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2205-may-16"></a>版本 2205：5 月 16 日
*版本 2205 (組建 15225.20150)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致使用者看到「無法執行要求的作業...」錯誤的問題當嘗試展開本機連絡人群組時。


- 我們已修正使用 [開啟共用行事曆] 時，未在瀏覽窗格中選取行事曆的問題。


- 我們已修正在嘗試開啟 Viva Insights 增益集時，導致某些客戶看到灰色方塊的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2205-may-09"></a>版本 2205：5 月 9 日
*版本 2205 (組建 15225.20092)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="office-suite"></a>Office 套件

- **輕鬆存取桌面上的共用文件:** [登入組織] 選項可讓來賓使用者使用一次性密碼或協力廠商聯盟，存取已在其桌面版 Office 應用程式上與之共用的文件。 這項功能先前已在 Office 網頁版中提供，現在也是 Office 桌面應用程式的選項。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正當應用程式無法處理連結資料表上的大型 .csv 檔案時，產生的 Access 2016 錯誤「您的電腦磁碟空間不足」的問題。


- 我們已修正此問題，讓新式圖表在格式化貨幣值時，現在會顯示當地語系化貨幣符號。


- 我們已修正使用 IVS 字元的語言可能會發生非預期分行符號的問題。


- 我們已修正當使用者切換資料夾，並且使用釘選的網頁增益集時，讀取窗格可能會消失的問題。


### <a name="excel"></a>Excel

- 我們已修正字母 「j」 未正確插入的問題。


- 我們已修正在某些下拉式功能表中選取選取項目後，無法顯示或看不到的問題，特別是在深灰色主題中。


- 我們已修正當視窗調整大小時，功能區中的某些按鈕無法正確繪製的問題。


- 我們已修正新增標籤時對應圖表會重新著色的問題。


- 我們目前正在從資料驗證自動完成下拉式清單中移除重複項目。


- 我們已修正在具有圖表工作表的活頁簿上執行 VBA 指令碼/增益集時，可能會導致 Excel 意外關閉的問題。


- 我們已修正使用 TEXTSPLIT 函數與特定引數時可能會發生的問題。


- 我們已修正導致 Excel 耗用過多記憶體的問題。


- 我們已修正應用程式會因為 PowerQuery 資料處理而意外關閉的問題。


- 我們已修正 LET 函數中的名稱引數與欄參照相同，且資料列為絕對值的問題。


- 我們已修正在 Excel 網頁版中特定地區設定的使用者錯誤使用小數分隔符號的問題。


- 我們已修正使用特定舊版 Windows 11 時，在 Excel 和 Project 中呈現的問題。


- 我們已修正類似但不同的影像可能無法正確處理的問題。


- 我們已修正「重新連結清單至新網站」對話方塊的問題，其不允許重新連結至超過 63 個字元的新 SharePoint 清單 URL。


- 我們已修正在巨集建立器中停用關閉按鈕的問題。


- 我們已修正嘗試瀏覽至儲存在 SharePoint 中的文件時可能會造成錯誤的問題。


### <a name="outlook"></a>Outlook

- 我們已修正應用程式針對特定工作使用超過 500 個執行緒的問題。


- 我們已修正使用者在離線模式下按一下 「傳送\接收所有資料夾」時，會收到錯誤訊息的問題。


- 我們已修正會導致歐盟使用者看到人員卡片中遺失資訊的問題。


- 我們已修正應用程式在呼叫 ResolveContacts 數千次之後，嘗試回應特定連絡人時會停止回應的問題。


- 我們已修正導致使用者從委派分組討論區信箱轉寄出的所有會議邀請上看到特定「不需要回應」的問題。


- 我們已修正使 Outlook 事件型增益集無法正常運作的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正在某些下拉式功能表中選取選取項目後，無法顯示或看不到的問題，特別是在深灰色主題中。


- 我們已修正類似但不同的影像可能無法正確處理的問題。


- 我們已修正多行敏感度標籤頁腳會定位，讓只有第一行會出現在投影片底部的問題。


- 我們已修正使用者在插入另一個 PowerPoint 檔案做為連結化物件時看到空白區塊的問題。


### <a name="word"></a>Word

- 我們已修正關閉受標籤保護的檔案時，會發生 OneDrive 衝突的問題。


- 我們已修正 Word 中新式註解問題，將從 OneNote 複製的註解文字插入影像。


- 我們已修正在某些下拉式功能表中選取選取項目後，無法顯示或看不到的問題，特別是在深灰色主題中。


- 我們已修正讓表格內的圖示在調整大小時能正確顯示的問題。


- 我們已修正類似但不同的影像可能無法正確處理的問題。


- 我們已修正按一下「上一步」和「下一步」時，註解在迴圈中不正確顯示的問題。


- 我們已修正在 Word 中張貼新的新式註解之後，信任中心設定視窗無法開啟的問題。


- 我們已修正刪除段落標記之後，游標會卷至文件尾端的問題。


- 我們已修正在 LaTex 等式中切換 Linear 和 Professional 可能會導致顯示錯誤的問題。


- 我們已修正關閉註解時，擱置中的書簽也會關閉的問題。


- 我們已修正將方程式從一份 Word 檔案中貼到另一份檔案時，導致應用程式停止回應的問題。


- 我們已修正合併衝突警示未提供捨棄目前變更的選項的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正已設定為僅啟用/停用狀態的四個策略現在設定為接受數值並寫入 HKCU 的問題。


- 我們已修正字型下拉式清單無法正確反映圖形中選取的字型的問題。


- 我們已修正與特定範例文字相關的問題，此問題會因為 RICH-edit HTML 忽略 HTML 小元素，且未重設超連結結尾的字元格式遮罩而顯示不佳。


- 我們已修正在 Backstage 中具有更新視覺效果的客戶在特定應用程式和主題中看不到他們所選擇的 Office 背景的問題。


- 我們已修正當 PowerShell 停用時，使用者無法安裝 M365 應用程式的問題。


- 我們已修正在更新期間造成「發佈封裝失敗」錯誤，導致檔案類型關聯遺失的問題。


- 我們已修正 Direct2D 和 Direct3D 互通性的多執行緒相關問題。


- 我們已修正錄製投影片放映時的穩定性問題。


- 我們已修正 OCPS 用戶端程式代碼的問題，方法為啟用正確 URL 的 config 服務來代表 Federation Check。


- 我們已修正當使用者暫停 [大聲朗讀] 功能時，應用程式在重新啟動時會跳到下一個段落的問題。


- 我們已修正大聲朗讀會導致應用程式意外關閉的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2204-may-04"></a>版本 2204：5 月 4 日
*版本 2204 (組建 15128.20206)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="word"></a>Word

- **只追蹤您在文件中的變更：** 當您共同作業時，有時候您只想追蹤自己的變更，而不想強制此設定追蹤其他人的部分。 若只要追蹤您的變更，請前往 [校閱] 索引標籤，選取 [追蹤修訂]，然後選擇 [只有我]。<br />在[部落格文章](https://insider.office.com/en-us/blog/track-just-your-changes-in-word)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel


- 我們已修正導致 Excel 耗用過多記憶體的問題。


- 我們已修正使用特定舊版 Windows 11 時，在 Excel 和 Project 中呈現的問題。


### <a name="word"></a>Word

- 我們已修正刪除段落標記之後，文件會捲動至結尾的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2204-april-25"></a>版本 2204: 4 月 25 日
*版本 2204 (組建 15128.20178)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 這項變更可協助使用者找到正確的設定，以管理協力廠商會議提供者的預設線上會議選項。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2204-april-19"></a>版本 2204: 4 月 19 日
*版本 2204 (組建 15128.20146)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致歐盟使用者看到人員卡片中遺失資訊的問題。


- 我們已修正會導致使用者在嘗試回應特定連絡人時，遇到意外關閉的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2204-april-15"></a>版本 2204: 4 月 15 日
*版本 2204 (組建 15128.20126)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **在 Outlook 行事曆待辦事項列中顯示多個迷你月份：** 這項功能可讓您在 Outlook 行事曆待辦事項列，以水平和垂直方式顯示多個迷你月份。

### <a name="powerpoint"></a>PowerPoint

- **請記住移除預設標籤的時間，以免再次自動重新套用它：** 當使用者移除預設標籤時，Office 必須記住此動作，且不可再次自動重新套用預設標籤。

### <a name="word"></a>Word

- **請記住移除預設標籤的時間，以免再次自動重新套用它：** 當使用者移除預設標籤時，Office 必須記住此動作，且不可再次自動重新套用預設標籤。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正在使用 Access 資料庫引擎 OLEDB API 與包含 SharePoint 清單之連結的資料庫時，可能會導致應用程式意外關閉的問題。


- 我們已修正如果記憶體需求成長過快，造成使用 DAO 或 OLEDB 介面的應用程式無法讀取 Access 資料庫，可能會導致應用程式意外關閉的問題。


### <a name="excel"></a>Excel

- 我們已修正如果儲存後過早開啟，未受保護檔案上新增的標籤會遺失的問題。


- 我們已修正來自 Power BI 的樞紐分析表插入遺失的問題 (僅限 GCC 租用戶)。


- 我們已修正復原的檔案以唯讀方式開啟的問題。


- 我們已修正當試圖透過 [編輯連結] 對話方塊變更連結時，應用程式可能意外關閉的問題。


- 我們已修正導致 Excel 耗用過多記憶體的問題。


- 我們已修正 OnPrem 的問題，即在具有敏感性標籤和除完全控制之外的所有權限的文件中，Get Data 將遭停用。


- 我們已修正應用程式無法從 Power BI 轉譯具名格式的問題。


- 我們已修正與線上進階內容庫中選取項目相關的問題。


- 我們已修正顯示某些 SVG 檔案的問題。


- 我們已修正當使用建議圖表作業插入圖表時，導致應用程式意外關閉的問題。


- 我們已修正 [查看所有圖表] 按鈕的工具提示具有誤導性 ([查看所有圖表類型]) 的問題；行為實際上僅限於 [建議圖表]。


- 我們已修正在操作功能表中選擇搜尋命令會停用常用鍵盤快速鍵組合的問題。


### <a name="onenote"></a>OneNote

- 我們已修正使用者可能無法完全捲動以在螢幕上看到筆跡的問題。


- 我們已修正一個問題，確保數位筆跡筆劃具有適當粗細的問題。


### <a name="outlook"></a>Outlook

- 我們已修正按一下具有希伯來文的 mailto 連結，且數字無法正確顯示郵件內文中文字的問題


- 我們已修正檢視動畫 GIF 時的回應問題。


- 我們已修正使 Outlook 事件型增益集無法正常運作的問題。


- 我們已修正顯示某些 SVG 檔案的問題。


- 我們已修正導致「移至其他」功能停止正常運作的問題。


- 我們已修正重新傳送郵件會將郵件內文還原為純文字，並遺失所有變更 (資料遺失) 的問題。


- 我們已修正當資料夾移至線上封存時，會導致同步處理視窗外的資料夾項目遺失的問題。


- 我們已修正影響受 RMS 保護之郵件的問題。


- 我們已修正在使用雲端設定時，導致某些切換類型選項進行錯誤同步處理的問題。


- 我們已修正在連線到沒有服務 URL 的商務用 OneDrive端點時，導致 Outlook 在啟動期間意外關閉的問題。


- 我們已修正會導致歐盟使用者看到人員卡片中遺失資訊的問題。


- 我們已修正導致在部分診斷案例中，使用者在 Outlook 中預期停止回應的問題。


- 我們已修正會導致使用者在嘗試回應特定連絡人時，遇到停止回應的問題。


- 我們已修正當電子郵件寄件者也位於 [寄件者:] 或 [副本:] 行時，回覆共用信箱中的郵件會發生的問題。 使用者的電子郵件地址會從回覆上的收件者清單中移除，導致主要電子郵件寄件者未收到任何對話回覆。


- 進行了一項資料變更，在英國行事曆中包含了新的英國假日。


- 我們已修正在將多個郵件項目從 [焦點] 移至 [其他] 收件匣，或從 [其他] 移至 [焦點] 收件匣時，導致郵件子集無法移動的問題。


- 我們已修正可能導致使用者無法停用 [交談] 檢視的問題。


- 我們已修正啟用 REST 共用行事曆功能時，已移除的共用行事曆會再次出現的問題。


- 我們已修正導致使用者在刪除資料時意外遇到關閉的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正與線上進階內容庫中選取項目相關的問題。


- 我們已修正與在套用 3D 屬性的形狀中選擇文字相關的問題。


- 我們已修正有關在 SVG 檔案中正確處理多個連續空間的問題。


- 我們已修正了有關匯出錄製的簡報之穩定性問題。


- 我們已修正一個問題，以讓 [編輯] 檢視和 [簡報者] 檢視中的貼上行為一致。


### <a name="project"></a>Project

- 我們已修正影響 Project 中自訂檢視顯示的問題。


- 我們已修正無法完全顯示甘特圖類型視圖的問題；當視圖對它套用繪圖物件時，可能會發生此情況。


- 我們已修正執行 [另存為 PDF] 命令時未顯示進度線的問題。


- 我們已修正使用者無法開啟特定專案的問題；應用程式會意外關閉。


- 我們已修正從 Project 用戶端儲存或發佈專案不會儲存對自訂欄位的變更。


- 我們已修正在篩選中用作分隔符號的星號 (*) 導致錯誤和意外行為的問題；請用管線 (|) 取代。


- 我們已修正應用程式在未完成資源撫平時停止回應的問題。


- 我們已修正應用程式開啟不再可用的畫面，導致專案隱藏的問題。


- 我們已修正在高 DPI 系統上的問題：網狀圖上的節點被視為重疊或不可縮放，並且無法正確列印。


### <a name="publisher"></a>發行者

- 我們已修正顯示某些 SVG 檔案的問題。


### <a name="word"></a>Word

- 我們已修正停用文件共同作業模式的問題。


- 我們已修正在其他應用程式中顯示內嵌 Excel 試算表的問題。


- 我們已修正與線上進階內容庫中選取項目相關的問題。


- 我們已修正顯示某些 SVG 檔案的問題。


- 我們已修正 SVG 檔案可能會顯示為中斷連結的問題。


- 我們已修正導致共用行事曆在新增後處於未選取狀態的問題。


- 我們已修正在插入電子郵件時，畫面延遲為零的 GIF 無法以動畫顯示的問題。


- 我們已修正從 Excel 貼上表格並儲存篩選的 HTML 後，文字部分顏色變為白色的問題。


- 我們已修正在 Mac 上插入的註解和 Windows 上不同主題中顯示錯誤字型大小色彩的問題。


- 我們已修正即時預覽使用的縮放層級低於設定的問題。


- 我們已修正當開啟追蹤修訂時新增重複內容控制項時，應用程式有時會停止回應的問題。


- 我們已修正 Word 在方程式中使用時無法列印可見選用連字號 (Alt+173) 的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正字型下拉式清單無法正確反映圖形中選取的字型的問題。


- 我們已修正在按一下滑桿時，允許新增漸層停駐點的問題。


- 我們已修正 Direct2D 和 Direct3D 互通性的多執行緒相關問題。


- 我們已修正在 SVG 檔案中顯示線條和填滿屬性的問題。


- 我們已修正錄製投影片放映時的穩定性問題。


- 我們已修正停止錄製投影片放映時的穩定性問題。


- 我們已修正涉及動畫時間時，[錄製投影片放映] 無法運作的問題。


- 我們已修正工作階段與 RDS 工作階段主機中斷連接的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2203-march-30"></a>版本 2203：3 月 30 日
*版本 2203 (組建 15028.20160)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Power BI 資料集要求存取改進功能：** 此更新會在使用者嘗試在 Excel 中重新整理連線至目前無法存取之資料集的樞紐分析表時，提供一種方法來要求存取 Power BI 資料集。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正顯示某些 SVG 檔案的問題。


### <a name="outlook"></a>Outlook

- 我們已修正使用 [僅加密] 和 [不要轉寄]範本的訊息透過物件模型傳回未預期權限的問題。


- 我們已修正會導致某些切換類型選項在使用雲端設定時同步處理錯誤的問題。


- 我們已修正導致使用者在部分診斷案例中在 Outlook 預期停止回應的問題。


### <a name="publisher"></a>發行者

- 我們已修正顯示某些 SVG 檔案的問題。


### <a name="word"></a>Word

- 我們已修正在其他應用程式中顯示內嵌 Excel 試算表的問題。


- 我們已修正顯示某些 SVG 檔案的問題。


- 我們已修正在 Word 中 SVG 檔案可能會顯示為中斷連結的問題 (Red-X)。


- 我們已修正導致共用行事曆在新增後處於未選取狀態的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正在 Project 中顯示自訂檢視的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2203-march-21"></a>版本 2203: 3 月 21 日
*版本 2203 (組建 15028.20094)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- We fixed an issue that could cause memory usage of an application that used DAO or OLEDB interfaces to read Access databases to grow rapidly.  In some cases, this could cause abnormal program termination.


### <a name="excel"></a>Excel

- 我們已修正復原的檔案以唯讀方式開啟的問題。


### <a name="outlook"></a>Outlook

- 我們已修正將多個訊息項目從 [焦點] 移至 [其他] 或從 [其他] 移至 [焦點] 時，導致使用者只看到訊息子集移動的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2203-march-14"></a>版本 2203: 3 月 14 日
*版本 2203 (組建 15028.20050)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="office-suite"></a>Office 套件


- **預設會封鎖網際網路宏：** 為了協助改善 Office 中的安全性，我們正在變更 Office 應用程式的預設行為，以封鎖來自網際網路的檔案宏。 下列在 Windows 上執行的 Office 應用程式會受到影響：Access、Excel、PowerPoint、Visio 和 Word。 [深入了解](https://support.office.com/article/97f087d8-3136-4485-8e86-c5b12a8c4176)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正導致圖表資料數列的顯示名稱和趨勢線名稱無法在圖表設定窗格中編輯的問題。


- 此更新修正了應用程式停止運作的問題，並產生錯誤訊息，例如「無法開啟其他資料庫」；此問題也可能會導致 Access 無法正確關閉。


- 我們已修正如果資料庫中有 SharePoint 清單的連結，PowerBI 有時無法從 Access 資料庫重新整理資料的問題。


- 此更新修正了會造成使用 OLEDB 介面的自訂應用程式開啟包含 SharePoint 清單連結的 Access 資料庫意外關閉的問題。


### <a name="excel"></a>Excel

- 我們已修正修正西班牙縣市在地圖圖表中顯示方式的問題。


- 我們已修正導致使用者無法將複製的儲存格貼到 [自訂篩選工具] 對話方塊中的文字欄位的問題。


- 我們已修正當您開始鍵入值時，自訂篩選對話方塊中的文字欄位將自動完成的問題。


- 我們已修正輸入雙位元組字元時，有兩個建議，其中一個會自動插入的問題。


- 我們已修正使用自訂命令列可能會導致 Excel 意外關閉的問題。


- 我們已修正一個問題，以對齊瀑布圖中數列的填滿方式與直條圖中數列的填滿方式。


- 我們已修正敏感度標籤的工具提示顯示的位置離標籤本身太遠的問題。


### <a name="outlook"></a>Outlook

- 我們已修正應用程式因缺少寫入器執行緒而停止回應的問題。


- 我們已修正收到的電子郵件不會包含開啟郵件的連結的問題。


- 我們已修正導致智慧連結對話方塊無法如預期顯示的問題。


- 我們已修正導致使用者在刪除週期性工作之後，看到一次性工作意外出現的問題。


- 我們已修正「寄件者​​」帳戶選擇器下拉式功能表中缺少向下捲動按鈕的問題。


- 我們已修正將外寄郵件寄給特定人員的規則在 Exchange 快取記憶體模式中無法正常運作的問題。


- 我們已修正啟用 REST 共用行事曆功能時，已移除的共用行事曆會再次出現的問題。


- 我們已修正導致連絡人卡片成員資格清單不會正確顯示的問題。


- 我們已修正預期自訂圖示時，會為附加的郵件顯示預設圖示的問題。


- 我們修正了導致使用者在切換資料夾時因檢視設定損毀而出現效能問題之問題。


- 我們已修正除非是在草稿模式中查看大型影像，否則大型影像不會在郵件中顯示的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 PowerPoint 在 [檔案] > [資訊] 下無法顯示公司名稱的問題。


- 此變更會限制自動刪除舊復原檔案，而將舊復原檔案限制為儲存在預設復原檔案位置的復原檔案；這可防止意外刪除使用者所設定之復原檔案路徑中的非復原檔案。


- 我們已修正使用版權管理加密文件時，某些文字色彩作業不正確地停用的問題。


- 我們修正了當使用者變更文件的敏感度標籤時，Excel、Word 和 PowerPoint 有時意外關閉的問題。


- 我們已修正在 PowerPoint 中建立新文件時未正確套用預設敏感度標籤的問題。


- 我們已修正敏感度標籤的工具提示顯示的位置離標籤本身太遠的問題。


### <a name="project"></a>Project

- 我們已修正使用實體 % Complete 追蹤方法時，無法計算工作上大於 10，000，000，000 的 BCWP 值的問題。


- 我們已修正當使用者將伺服器型專案儲存為 MPP 檔案時，會覆寫本機格式設定的問題。


- We fixed an issue where the user would see a security dialog stating that the project had links to one or more data sources, even though the project had no active links. Now, the dialog appears only when there are active links.


- 我們已修正為各種基準欄位進行存存時，間歇性資料遺失的問題。


- 我們已修正使用另存成 PDF (*.pdf) 檔案類型時，將儲存作業儲存到網路磁碟機的速度變慢的問題。


- 我們已修正問題，以便使用者在甘特圖中列印進度線時就不會再遇到問題。


### <a name="word"></a>Word

- 我們已修正應用程式在檢查更新時間歇性地停止回應的問題。


- 我們已修正導致包含外部內容的 SVG 影像在某些情況下不會顯示的問題。


- 我們已修正敏感度標籤的工具提示顯示的位置離標籤本身太遠的問題。


- 我們已修正 [進階追蹤修訂選項] 中建立者色彩引起的問題。


- 我們已修正追蹤修訂中修訂標記未如預期作用的問題。


- 我們已修正除非是在草稿模式中查看大型影像，否則大型影像不會在郵件中顯示的問題。


- 我們已修正在使用者介面或按 Enter 之後，在 VBA 中，除了新插入的段落之外，會插入整個目前段落的問題。


- 我們已修正在 Microsoft 365 版本中無法開啟檔案，但可以在較舊的 Word 版本中開啟的問題。


- 我們修正了編輯文件時，[另存新檔] 對話方塊會意外出現的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正會導致連絡人卡片無法顯示的問題。


- 我們已修正 Outlook 預覽窗格導致 SVG 影像無法正確呈現的問題。


- 我們已修正無法解決問題的 SVG 影像存存數量減少的問題。


- 我們已修正使用者在應用程式防護中無法開啟檔案的問題。


- 我們已修正影響 [大聲朗讀] 選項的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2202-march-07"></a>版本 2202：3 月 07 日
*版本 2202 (組建 14931.20132)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正導致使用 OLEDB 介面的自訂應用程式開啟包含 SharePoint 清單連結的 Access 資料庫意外關閉的問題。


- 我們已修正導致較新版本的 Viva Insights 增益集載入效率較低的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致使用者在切換資料夾時因檢視設定損毀而出現效能問題之問題。


- 我們已修正導致附加郵件顯示預設圖示，而預期是出現自訂圖示的問題。


- 我們已修正導致連絡人卡片成員資格清單不會正確顯示的問題。


### <a name="visio"></a>Visio

- 我們已修正應用程式在插入圖表時停止回應的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2202-february-28"></a>版本 2202：2 月 28 日
*版本 2202 (組建 14931.20120)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="powerpoint"></a>PowerPoint

- **消費者客戶的新式註解：** 我們的新增新式註解功能包括新功能，例如已解決的註解。

### <a name="office-suite"></a>Office 套件

- **應用程式內續約：** 為使用者提供一種在應用程式內更新其訂閱的方式。

- **已取消佈建使用者的應用程式內購買：** 提供使用者停留在應用程式內購買 Office 的選項。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 此項更新會調整瀑布圖中數列的填滿方式，與直條圖中數列的填滿方式保持一致。


### <a name="outlook"></a>Outlook

- 我們已修正收到的電子郵件不會包含開啟郵件的連結的問題。


- 我們已修正導致螢幕閱讀器無法存取特定的智慧連結註標的問題。


### <a name="powerpoint"></a>PowerPoint

- 此修正會顯示從 C2R 安裝的 PowerPoint 在 [資訊] | [屬性] | [進階屬性] 對話方塊中的公司資訊。


### <a name="project"></a>Project

- 使用者在列印甘特圖上的進度線時，應該不會再遇到問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正 Outlook 預覽窗格中的問題，允許 SVG 影像正確呈現。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2202-february-22"></a>版本 2202：2 月 22 日
*版本 2202 (組建 14931.20094)*
* 各種錯誤和效能修正。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **快速尋找您要搜尋的資訊：** 當您搜尋諸如事件、人員、航班等內容時，它們會出現在搜尋結果的頂端。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2202-february-14"></a>版本 2202：2 月 14 日
*版本 2202 (組建 14931.20072)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="word"></a>Word

- 我們已修正包含外部內容的 SVG 影像可能無法顯示的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2202-february-07"></a>版本 2202：2 月 7 日
*版本 2202 (組建 14931.20010)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此更新已修正可能會導致應用程式停止運作而出現錯誤訊息 (例如「無法開啟其他資料庫」)，且可能導致 Access 無法正常關閉的問題。


- 我們已修正當使用者嘗試將超過 8,000 位元組的資料新增到 varchar(max) 欄位時，某些 SQL Server 驅動程式會顯示 [字串資料，右截斷 (#0)] 錯誤的問題。


- We fixed an issue that would prevent multiple users from opening a database when using network paths that include DFS Namespaces, short file names, or mapped drives. [Learn More](https://support.microsoft.com/en-us/office/error-in-access-when-opening-a-database-on-a-network-file-share-6cbc1560-62c2-46e7-9980-d079a46f5acc)


- 這項變更可啟用針對 Outlook 增益集 1.11 和 1.9 需求集合的完全支援。


- 我們修正了導致 Insights 增益集停止運作的問題。


### <a name="excel"></a>Excel

- 我們已修正功能區中的功能表圖示看起來位置錯誤的問題。


- 我們已修正如果使用者已離開功能區，則按一下 [協助工具檢查程式] 窗格時並不會再將焦點切換到 [協助工具] 功能區的問題。


- 我們已修正在 Excel 網頁版儲存之後，篩選圖表的格式會變更的問題。


- 我們已修正在樞紐分析表中有隱藏欄位時會發生的問題。


- 我們已修正從 Visio 匯出的 SVG 檔案不會正確顯示文字的問題。


### <a name="outlook"></a>Outlook

- 我們已修正 Outlook 不會同步處理具有大量資料夾之信箱的完整資料夾階層的問題 (例如 10000 個以上的資料夾)。


- 我們已修正此問題：如果使用者已變更 [寄件者] 欄位，但未變更新的撰寫，則標籤對齊提示顯示錯誤。


- 我們已修正按一下組織圖檢視中之多位使用者的連絡人卡片，會導致應用程式停止回應的問題。


- 我們已修正代理人在新的 REST 式行事曆共用模型中的會議邀請中開啟行事曆時，會無法判斷他們正在使用哪位管理員的共用行事曆的問題。


- 我們已修正當會議系列的一個執行個體已變更為 Teams 會議時，則無法使用 [加入] 按鈕的問題。


- 我們已修正當使用者刪除包含於伺服器端上之資料的「空白」資料夾時，使用者會遺失資料的問題 (警告會於此時在此案例中出現)。


- 我們已修正當使用 Outlook 的共用 OneDrive 連結變更後，超連結 URL 不會自動變更的問題。


- 我們已修正開啟連絡人個人檔案卡片後，Outlook 中的資料夾清單停止回應滑鼠按鍵的問題。


- 我們已修正當 RunContactLinking regkey 設定為 0 時，Outlook 正在合併連絡人資訊的問題。


- 我們已修正無法開啟使用數位版權管理 (DRM) 的郵件的問題。


- 我們已修正使用 OnPrem 服務搜尋時，Outlook 內容搜尋導致的結果不完整的問題。


- 我們已修正 (僅會影響 64 位元用戶端機器) 當轉寄 RTF 電子郵件時，應用程式會停止回應的問題。


- 我們已修正此問題：已從隱藏的視窗中移除約會快速檢視 (AQV) ，以啟用初始滾動。


- 我們已修正導致連絡人卡片無法適當顯示的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正功能區中的功能表圖示看起來位置錯誤的問題。


- 我們已修正以無視窗模式以程式化方式開啟簡報時，可能無法載入連結影像的問題。


- 我們已修正從 Visio 匯出的 SVG 檔案不會正確顯示文字的問題。


- 我們已修正會影響捲軸的問題。


### <a name="project"></a>Project

- 我們已修正當企業文字輸入欄位中的文字資訊包含問號 (? ) 或星號 (*) 時，自動篩選無法使用的問題。 收到的錯誤為：「輸入無效。 測試值無法與您要尋找或篩選之資料的欄位搭配使用」。 自動篩選現在允許包含具有保留字元的值。


- 我們已修正使用者進入無法執行儲存之狀態的問題。 此修正可讓使用者永遠可儲存其工作。


- 我們已修正問題，讓現在使用者可以將專案儲存至 Project Web App，即使離線檔案中的資源具有與企業資源相符的名稱。


### <a name="word"></a>Word

- 我們已修正功能區中的功能表圖示看起來位置錯誤的問題。


- 我們已修正從 Visio 匯出的 SVG 檔案不會正確顯示文字的問題。


- 我們已修正在對檔案進行其他內容編輯之前，透過自動或建議標籤套用的敏感度標籤會無法儲存的問題。


- 我們已透過在 Word 原生版本中變更完全符合醒目提示色彩的非白色背景色彩，使其具有醒目提示屬性來修正問題。


- 我們已修正在使用功能窗格選取特定頁面時，在整頁模式中只會顯示頁面的第一個部分的問題。


- 我們已修正 Outlook 連絡人進行合併列印時，可能會產生「記憶體不足或系統資源不足」的問題。


- 我們已修正導致應用程式在文件中選取移至註解的第一個註解時，應用程式意外關閉的問題。


- 我們已修正在 Word 365 或 Windows 10 中大型文件的效能比在 Word 2013 或 Windows 7 中更緩慢的問題。


- 我們已修正當文件為 [預覽列印] 模式時，[目錄] 頁碼會變更為單一數字的問題。


- 我們已修正更新 case 陳述式以對應至資料大小的問題。


- 我們已修正關閉包含清單樣式並啟用 [以此範本為基礎的新文件] 選項的任何文件時發生錯誤的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正現有 WOPI 通訊協定支援即時共同撰寫的問題，在其中，如果鎖定在重新整理中無法運作，則另一個鎖定會維持功能。


- 我們已修正當使用小型大寫字功能時，會導致文字轉譯錯誤的問題。


- 我們已修正在使用者收到新版視覺效果的存取權後，並未如即將推出功能的群組原則設定而啟用預期的單次快顯 (第一次開啟 Office 應用程式時) 的問題。


- 我們已修正某些預設應用程式在每月 Office 更新之後消失的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2201-february-04"></a>版本 2201：2 月 4 日
*版本 2201 (組建 14827.20186)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Office 應用程式現在支援 OpenDocument 格式 (ODF) 1.3：** ODF 1.3 對 OpenDocument 格式帶來許多改良功能，而且這些功能現在都可在 Word、Excel 及 PowerPoint (副檔名 .odt、.ods 和 .odp) 中受到支援。<br />在[部落格文章](https://insider.office.com/en-us/blog/office-apps-now-support-opendocument-format-odf-1-3)中查看詳細資料

### <a name="outlook"></a>Outlook

- **從您的帳號別名或 Proxy 電子郵件地址傳送電子郵件：** Outlook 傳統上可以接收電子郵件，而不是您的預設電子郵件地址 (稱為 Proxy 位址或別名)。 現在，您也可以選擇所需的寄送電子郵件位址，從這些 Proxy 帳戶傳送電子郵件。

### <a name="teams"></a>Teams

- **共同召集人會議角色：** 召集人現在可以將新的「共同召集人」角色指派給他們邀請的人員，以共用控制權。 共同召集人幾乎擁有召集人的所有功能，包括會議選項的管理。

- **在 Teams 會議中隱藏您自己的視訊：** 目前，使用者的視訊會顯示在會議畫面的右下角。 這項功能可讓使用者在會議期間隱藏自己的視訊。 這有助於減少通話期間干擾，同時讓其他參與者仍可觀看您的視訊。

- **聊天中的精簡檢視：** 允許使用者在特定空間內查看更多聊天。 更善加使用聊天中的空間。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="project"></a>Project

- 我們已修正使用者進入無法儲存的狀態問題。 此修正使得使用者一律可以儲存其工作。


- 我們已修正一個問題，使用者現在可以將專案儲存至 Project Web 應用程式，即使離線檔案中資源的名稱符合企業資源亦然。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2201-january-24"></a>版本 2201：1 月 24 日
*版本 2201 (組建 14827.20158)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **預設敏感度標籤現在適用於現有未標記的文件：** 已修復不會將預設敏感度標籤套用至現有未標記文件的問題。

### <a name="outlook"></a>Outlook

- **大聲朗讀功能變得更好：** 新的大聲朗讀工具列提供全新、聽起來很自然的語音選項。

### <a name="powerpoint"></a>PowerPoint

- **預設敏感度標籤現在適用於現有未標記的文件：** 已修復不會將預設敏感度標籤套用至現有未標記文件的問題。

### <a name="word"></a>Word

- **預設敏感度標籤現在適用於現有未標記的文件：** 已修復不會將預設敏感度標籤套用至現有未標記文件的問題。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們修正了導致 Insights 增益集停止運作的問題。


### <a name="outlook"></a>Outlook

- 我們修正了載入角色時導致停止回應的問題。


- 我們修正了應用程式在載入連絡人卡片後變成無回應的問題。


- 我們修正了使用者變更郵件中連結的權限時，導致智慧連結 URL 無法更新的問題。


- 我們修正了造成使用者無法開啟已套用數位版權管理原則之郵件的問題。


### <a name="word"></a>Word

- 我們修正了重複樣式會套用 Normal，而不是重複樣式的問題。


### <a name="office-suite"></a>Office 套件

- 我們修正了在無視窗模式中以程式化方式開啟簡報時，可能無法載入連結影像的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2201-january-18"></a>版本 2201：1 月 18 日
*版本 2201 (組建 14827.20122)*
* 各種錯誤和效能修正。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Want your workbook to take you places?:** Understand the layout of your workbook, see what elements exist, and navigate around quickly using the Navigation pane. [Learn more](https://support.office.com/article/ddd037e7-22e3-41f0-8bbd-07f5479e92bf)<br />在[部落格文章](https://insider.office.com/en-us/blog/see-the-big-picture-with-navigation-pane-for-excel)中查看詳細資料

### <a name="outlook"></a>Outlook

- **更新連絡人卡片中的相片連結：** 在您自己的連絡人卡片中顯示更新相片連結

### <a name="powerpoint"></a>PowerPoint

- **Office 應用程式現在支援 OpenDocument 格式 (ODF) 1.3：** ODF 1.3 對 OpenDocument 格式帶來許多改良功能，而且這些功能現在都可在 Word、Excel 及 PowerPoint (副檔名 .odt、.ods 和 .odp) 中受到支援。<br />在[部落格文章](https://insider.office.com/en-us/blog/office-apps-now-support-opendocument-format-odf-1-3)中查看詳細資料

- **錄製有旁白的影片：** 使用預先錄製的影片和旁白，讓您的下一次簡報更具活力。 或預先錄製整個簡報，以確保在簡報當天順利演講。 [深入了解](https://support.office.com/article/ddc4432c-79f6-4add-b85e-1009815d955c)<br />在[部落格文章](https://insider.office.com/en-us/blog/tell-your-story-with-video-recording-in-powerpoint)中查看詳細資料


### <a name="word"></a>Word

- **共同作業時更快速地恢復工作：** 在與其他人共同作業時若中斷連線，Word 將會自動以最新的變更重新整理您的文件。

### <a name="office-suite"></a>Office 套件

- **匯出：** 將簡報的所有元件彙集在一起，以便輕鬆共用和檢視。 匯出的影片包括所有錄製的時間、旁白、筆墨和雷射筆筆勢。 影片也會保留動畫、轉場和媒體。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2201-january-12"></a>版本 2201：1 月 12 日
*版本 2201 (組建 14827.20088)*
* 各種錯誤和效能修正。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2201-january-10"></a>版本 2201：1 月 10 日
*版本 2201 (組建 14827.20060)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 已修正可能導致使用 Access 資料庫引擎 OLEDB API 且其資料庫包含 SharePoint 清單之連結的應用程式，會意外關閉的問題。


- 我們已修正當連續使用多個執行緒連接 Access 或 Jet 資料庫時，可能導致應用程式停止回應的問題。


- We fixed an issue that would prevent multiple users from opening a database on a network file share. [Learn More](https://support.microsoft.com/en-us/office/access-error-could-not-use-path-to-database-accdb-file-already-in-use-6cbc1560-62c2-46e7-9980-d079a46f5acc)


### <a name="excel"></a>Excel

- 已修正在套用敏感度標籤保護文件後，[自動儲存] 可能會暫時停用的問題。


- 已修正以下問題：如果儲存格中的資料驗證下拉式清單包含空白值，則無法從該清單中選取值。


- 我們已修正圖形和表單控制項無法呼叫 VBA 巨集的問題。


- 我們已修正如果使用者沒有匯出權限，則 Excel 無法將活頁簿匯出至 XPS 的問題。


- 我們已修正使用自動化型工具 (包括交叉分析篩選器和協助工具) 時的效能問題。


- 已修正以下問題：在多重監視器設定中，當使用者選取儲存格時，對話方塊中的一些資料被隱藏。


- We fixed an issue where, when you had a Microsoft Excel 97-2003 Worksheet object embedded inside another application (such as a Word document), using the Convert feature to convert it to a Microsoft Excel Worksheet (Office OpenXML) object didn't complete the conversion until you opened the embedded object and made a change to it. The object is completely converted when using the Convert feature now.


- 已修正搜尋結果在樞紐分析表欄位清單工作窗格中遺失的問題。


- 已修正與 SVG 轉譯中文字錨定相關的問題。


### <a name="onenote"></a>OneNote

- 已修正平板電腦模擬器上的一般套索選取會導致應用程式意外關閉的問題。


### <a name="outlook"></a>Outlook

- 我們已實施設計變更要求，以防止顯示自動回覆橫幅。


- 已修正將連絡人匯出至 CSV 時導致使用者在某些欄位中看到亂碼文字的問題。


- 我們已修正當 RunContactLinking regkey 設定為 0 時，Outlook 正在合併連絡人資訊的問題。


- 已修正導致在啟用「共用行事曆改良」的情况下，使用者無法從連絡人新增共用行事曆的問題。


- 已修正以下問題：當 [寄件者] 地址與 [回覆] 地址不同時，郵件寄件者在全部回覆時未被包括在內。


- 已修正以下問題：當使用者的下載喜好設定設定為 [下載標題] 時，透過提醒開啟訊息時導致應用程式意外關閉的問題。


- 我們已修正啟用 REST 共用行事曆功能時，已移除的共用行事曆會再次出現的問題。


- 我們已修正 Outlook 在瀏覽至共用行事曆時停止回應的問題。


### <a name="powerpoint"></a>PowerPoint

- 已修正使用觸控板時透過點兩下選取文字的問題。


- 已修正與 SVG 轉譯中文字錨定相關的問題。


- 已修正將 Vimeo 影片插入簡報時造成錯誤的問題。


- 我們已修正在某些情況下，重設投影片未遵守特定圖片填滿屬性的問題。


### <a name="project"></a>Project

- 我們已修正大綱群組篩選無法運作的問題。


- 我們已修正會導致應用程式停止回應並造成資料遺失的問題。


- 我們已修正從 Windows Server 2008 移轉升級到 Windows Server 2016/2019 的專案停止儲存的問題。


- 我們已修正當工作完成之後，指派任務的工期設定為零時，材料資源的時間階段資料不會顯示的問題。


### <a name="word"></a>Word

- 我們已修正當使用者使用 OneDrive 用戶端同步處理之 CICO 文件庫中的伺服器路徑對位置執行另存新檔動作時，可能會遺失資料而不會發生錯誤的問題。


- 已修正與 SVG 轉譯中文字錨定相關的問題。


- 已修正當使用者重複點擊或使用快速鍵開啟或關閉 [大聲朗讀] 功能時，應用程式意外關閉的問題。


- 我們已修正連絡人卡片在 Office 中無法作用的問題。


- 我們已修正註解在 Sidetrack 中遺失，但在窗格中顯示的問題。


- 我們已修正即時預覽的縮放會關閉內容卡片的問題。


- 我們已修正輸入新資料時，表格中的值有時候不會重新整理的問題。


- 我們已修正選取鏡像邊緣時，水平尺規與頁面邊緣不符的問題。


### <a name="office-suite"></a>Office 套件

- 已修正與重新整理可能包含文字的元素相關的可靠性問題。


- 我們已修正使用者無法從應用程式首頁上 [與我共用] 區段開啟檔案的問題。


- 我們已修正 Office 在 SSO 和 ADFS DRS 環境中顯示帳戶錯誤的問題。


- 已修正以下問題：如果停用 EnableAudit 設定，則不再產生 Microsoft Purview 資訊保護敏感度標籤稽核資料。


- 已修正在連續啟動和停止 [大聲朗讀] 時應用程式停止回應的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2112-january-03"></a>版本 2112：1 月 3 日
*版本 2112 (組建 14729.20194)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 這項變更可啟用針對 Outlook 增益集 1.11 和 1.9 需求集合的完全支援。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2112-december-27"></a>版本 2112: 12 月 27 日
*版本 2112 (組建 14729.20178)*
* 各種錯誤和效能修正。

## <a name="version-2112-december-16"></a>版本 2112：12 月 16 日
*版本 2112 (組建 14729.20170)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 已修正使用多個執行緒連線至 Access 或 Jet 資料庫時造成應用程式意外關閉的問題。


### <a name="excel"></a>Excel

- 已修正導致使用 OLEDB API 和 ACE.OLEDB.12.0 或 ACE.OLEDB.16.0 提供者的應用程式意外關閉的問題。


### <a name="outlook"></a>Outlook

- 已修正將連絡人匯出至 CSV 時導致使用者在某些欄位中看到亂碼文字的問題。


### <a name="office-suite"></a>Office 套件

- 已修正與重新整理可能包含文字的元素相關的可靠性問題。


- 已修正使用觸控板時透過點兩下選取文字的問題。


- 已修正與 SVG 轉譯中文字錨定相關的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2112-december-13"></a>版本 2112：12 月 13 日
*版本 2112 (組建 14729.20108)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正當資料庫包含 SharePoint 清單的連結時，可能導致使用 OLEDB API 開啟 Access 資料庫 (.accdb 檔案) 的應用程式意外關閉的問題。


### <a name="excel"></a>Excel

- 我們已修正某些永久 2016 和 2019 使用者因移除快速存取工具列 (QAT) 中的復原/重做命令，以及 QAT 圖示未對齊而受到影響的問題。


- 我們已修正一個問題，以便預設控制項為文字欄位，並讓使用者可以在對話方塊開啟時立即開始輸入。


- 我們已修正在 SpreadsheetCompare 工具中開啟 XLSM 檔案時，會導致工具停止回應的問題。


- 我們已修正當資料中不再有已篩選的值時，重新整理 [樞紐分析表] 的資料可能會停止運作的問題。 現在重新啟用在沒有無效篩選值的情況下產生的用於重試整理要求的後續查詢語句。


- 我們已修正當 Wincomp 關閉時，因 Windows 11 上的 Mica 開啟而導致的問題。


- 我們已修正樞紐分析表欄位窗格中的文字很難看清楚 Excel 是否以 Office 深灰色主題運作的問題。


- 我們已修正與表單控制項互動可能會導致 Excel 意外關閉的問題。


- 我們已修正 LOGEST 工作表函數的問題，該函數不會處理並清除暫時性溢位錯誤，且後續的計算不正確。


- 我們已修正此問題: 如果資料來源範圍變更，新建立的樞紐分析表可能會失去自訂的設定。


- 我們已修正某些公式結果在輸入變更後無法更新的問題。


- 我們已修正 WEBSERVICE 工作表函數中，在極少數的情況下，Excel 會在使用者取消計算時停止運作的問題。


### <a name="outlook"></a>Outlook

- 我們已修正使用者寄給自己 (相同電子郵件地址) 所收到的電子郵件呈現空白郵件內文的問題。


- 我們已修正在檢索角色時，造成使用者遇到意外關閉的問題。


- 我們已修正在 Power Point 載入角色時，造成使用者遇到意外關閉的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正無法按一下某些彈出 UI 元素的問題，例如，Outlook 中的 [加入會議] 快顯視窗，或 PowerPoint 中的 [歡迎回來] 快顯視窗。


### <a name="project"></a>Project

- 我們已修正當使用者開啟以不同名稱儲存的專案時, 會將手動排程的任務重新排定為更早日期的問題。


- 我們已修正進度行顯示在錯誤位置的問題。 


- 我們已修正載入自訂報表時, 應用程式會意外關閉的問題。


- 我們已修正當摘要任務完成 0% 時，進度線無法正確繪製的問題。


### <a name="word"></a>Word

- 我們已修正在註解中加上文字會不必要地新增一行的問題。


- 我們修正了無法按一下某些彈出 UI 元素的問題，例如，Outlook 中的 [加入會議] 快顯視窗，或 PowerPoint 中的 [歡迎回來] 快顯視窗。


- 我們已修正插入新註解時，如果文件右側有開啟任何窗格，則游標不會出現在回覆方塊中的問題。


- 我們已修正在張貼具有右對齊的新註解時，前一個註解的對齊方式從右變更為左的問題。


- 我們已修正在多分頁文件中捲動時, 游標會從註解中消失的問題。


- 我們已修正在共同作業期間, 顯示 GUID 而不是作者名稱的問題。


- 我們已修正在重新整理目錄時, 應用程式有時候會停止回應的問題。


- 我們已修正在變更文件中的項目符號色彩後, [復原] 命令無法運作的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正應用程式在開啟檔案時會意外關閉的問題。


- 我們已修正在已設定 OneDrive 同步處理的情況下, 儲存並重新開啟具有加密標籤的新檔案時, 會出現上傳已封鎖的警告視窗的問題。


- 我們已修正有關 Office 新外觀的教學圖說內容 (提示) 未出現在 Outlook 中的問題。 現在，Word、Excel、PowerPoint 和 OneNote 的使用者會收到 Office 新外觀變更的通知，其中包含變更內容以及如何變更設定或切換體驗的資訊。


- 我們已修正觸發重新開機以完成移除現有安裝的問題。


- 我們已修正 TrialNotificationBarDismissed、DateHigh 和 DateLow DWORDS 的說明已移除的問題。

- 我們已修復大聲朗讀會在快速連續啟動和停止時意外關閉的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2111-december-10"></a>版本 2111：12 月 10 日
*版本 2111 (組建 14701.20248)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正在 SpreedsheetCompare 工具中開啟 xlsm 檔案會導致工具停止回應的問題。


- 我們已修正 WEBSERVICE 工作表函數的問題，在極少數的情況下，Excel 會在使用者取消計算時停止運作。


### <a name="outlook"></a>Outlook

- 我們已修正在檢索角色時，造成使用者遇到意外關閉的問題。


### <a name="office-suite"></a>Office 套件

- 這會修正兩件事：
1. There was a bug in Outlook where the teaching callouts (tips) about the new look of Office did not appear. These will now appear.
2. Many users of Word, Excel, PowerPoint, and OneNote have missed the teaching callouts about the new look of Office, which include information about what changed and how to change settings, or toggle off the experience. This change retriggers these teaching callouts for users to be notified about the changes.



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2111-december-07"></a>版本 2111：12 月 07 日
*版本 2111 (組建 14701.20230)*
* 各種錯誤和效能修正。

## <a name="version-2111-december-03"></a>版本 2111：12 月 03 日
*版本 2111 (組建 14701.20226)*
* 各種錯誤和效能修正。

## <a name="version-2111-december-01"></a>版本 2111：12 月 1 日
*版本 2111 (組建 14701.20210)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們修正了當資料中不再存在篩選值時，重新整理樞紐分析表資料可能會停止運作的問題，並且在缺少無效篩選值所產生的後續查詢陳述式，重試重新整理要求暫時遭到停用，而現在已重新啟用。


- 我們已修正某些公式結果在輸入變更後無法更新的問題。


### <a name="outlook"></a>Outlook

- 我們修正了導致使用者在 PowerPoint 中載入角色時遇到意外關閉的問題。


### <a name="project"></a>專案

- 我們修正了一個問題，即當使用者開啟已儲存為其他名稱的專案時，已手動排程的工作被重新排程至更早的日期。 在開啟這些專案時，使用者不應再看到已手動排程的工作被重新排程。


- 我們修正了載入自訂報告時某些專案意外關閉的問題。 


### <a name="office-suite"></a>Office 套件

- 我們修正了以下問題：在受保護的共同撰寫期間，敏感度標籤和加密可能會從 SharePoint 或 OneDrive 中託管的檔案中移除的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2111-november-29"></a>版本 2111：11 月 29 日
*版本 2111 (組建 14701.20170)*
* 各種錯誤和效能修正。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **Microsoft Teams：網路研討會的受管理模式：** 網路研討會中的召集人和簡報者可以輕鬆地設定、管理及控制觀眾的視圖、持續聚焦在簡報者和內容上，以及將干擾最小化。 透過在會議設定中啟用受管理模式，您可以在上播前設定內容和簡報者、控制出席者一直看到的內容和內容，以及在多個簡報者和參與者間切換。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2111-november-22"></a>版本 2111：11 月 22 日
*版本 2111 (組建 14701.20166)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們修正了無法按一下某些彈出 UI 元素的問題，例如，Outlook 中的 [加入會議] 快顯視窗，或 PowerPoint 中的 [歡迎回來] 快顯視窗。


- 我們修正了顯示連絡人卡片時，意外關閉的問題。


- 我們修正了導致使用者在載入人員相片時遇到意外關閉的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們修正了無法按一下某些彈出 UI 元素的問題，例如，Outlook 中的 [加入會議] 快顯視窗，或 PowerPoint 中的 [歡迎回來] 快顯視窗。


### <a name="word"></a>Word

- 我們修正了無法按一下某些彈出 UI 元素的問題，例如，Outlook 中的 [加入會議] 快顯視窗，或 PowerPoint 中的 [歡迎回來] 快顯視窗。


- 我們修復了在匯出為 PDF 後，書籤和目錄連結無法運作的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2111-november-15"></a>版本 2111：11 月 15 日
*版本 2111 (組建 14701.20100)*
* 各種錯誤和效能修正。

## <a name="version-2111-november-10"></a>版本 2111：11 月 10 日
*版本 2111 (組建 14701.20060)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 開啟 Dynamics 的連結資料表時，顯示資料時，數字可能會呈現為小型方塊。  若要解決此問題，請在資料表設計檢視中開啟連結，並清除任何受影響資料行的格式屬性。


### <a name="excel"></a>Excel

- 我們已修正在滑鼠移到 [儲存格格式] 功能區下拉式功能表上時，「欄」一詞消失的問題。


- 我們已修正在工作表的索引標籤中，當地語系化字元呈現太小的問題 (僅啟用 Fluent UI 即將推出切換開關的使用者才有此問題)。


- 我們已修正與具有凍結窗格之許多自訂視圖的活頁簿相關的問題，此問題會導致 Excel 在啟動後立即停止回應。


- 我們已修正查詢更新導致 Excel 停止回應的問題。


- 我們已修正在公式中使用儲存格參照導致使用者遇到高 CPU 使用量的問題。


- 我們已修復此問題: 如果來源檔案來自 OneDrive 位置且檔案名稱包含 HTML 編碼字元, 將 Excel、Word 或 PowerPoint 內嵌物件加入 Excel 檔時, 未正確顯示應用程式的原始圖示。


- 我們已修正此問題: 無法在動態陣列中對定義的名稱套用名稱。


- 我們已修正此問題: 如果資料來源範圍變更，新建立的樞紐分析表可能會失去自訂的設定。


- 我們已修正此問題: 在某些情況下, 即時預覽中無法看到 Excel 儲存格中的文字。


- 我們已修正輸入查詢之後選取新工作表中的範圍, 然後從該範圍載入, 導致查詢編輯器以錯誤的資料表名稱開啟的問題。


- 我們已修正部分工作表函數未針對使用特定語言使用者顯示的問題。


- 我們已修正使用者看到音樂資料類型按鈕，但未轉換演出者的問題。


- 我們已修正在方格中遠距傳輸時 (例如使用 Ctrl + 方向鍵), 導致呈現錯誤的問題。


- 我們已解決在按一下及拖曳以選取儲存格範圍時發生的視覺問題。


- 我們已修正開啟 Excel 檔案時儲存格選擇取關閉的問題。


- 我們已修正此問題: 切換工作表可能會造成工作表索引標籤無法正確顯示。


- 我們已修正按一下 [篩選] 的熱門鍵 [e] 會與操作功能表上的 [搜尋] 發生衝突的問題。


### <a name="outlook"></a>Outlook

- 我們已修復此問題: 行事曆在進行完整同步處理時遇到問題。


- 我們已修正會導致使用 Windows 11 的使用者，或透過「即將推出」使用視覺效果的使用者，在將游標停留在迷你行事曆日期時看到文字未對齊的問題。


- 我們已修正在產生預覽時發生的同步處理失敗。


- 我們修正了導致所有使用敏感度標籤所送出的電子郵件持續使用「僅加密」範本，導致不正確的行為，允許人員轉寄「僅收件者」電子郵件的問題。


- 我們已修正執行搜尋時應用程式停止回應的問題。


- 我們已修正如果使用者開啟收件匣電子郵件並在進入 [群組] 之前關閉，[群組] 電子郵件的讚按鈕未出現的問題。


- 我們已修正 Outlook 在建議中顯示較少連絡人清單/連絡人群組的問題。


- 我們已修正系統發出邀請給出席者，但無法儲存至 [召集人] 的行事曆的問題。


- 我們已修正「僅加密」敏感度標籤無法處理 EN 以外的所有 UI 語言的問題。


- 我們已修正預設敏感度標籤未在加密電子郵件上套用的問題。


- 我們已修正此問題: 由於網際網路連線測試, 將 Outlook 郵件儲存到 SharePoint 文件庫時產生錯誤。


- 我們已修正在行事曆檢視中顯示全天活動結束日期錯誤的問題。


- 我們已修正來自不同網域的兩個 LDAP 通訊錄時所產生的 LDAP 通訊錄搜尋錯誤。


- 我們已修正 Outlook 因同步處理失敗而停止回應的問題。


- 我們修正了導致使用者載入 [行事曆] 模組的功能窗格時，遇到「停止」回應的問題。


- 我們已修正預覽會議邀請時導致 [約會] 快速檢視遭到裁剪的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用拖放來重新排序項目符號清單項目的問題。


- 我們已修正當使用者以直向將文件從較大的紙張大小變更為較小的紙張大小時, 列印工作會中斷 (資料遺失) 的問題。


- 我們已修正複製內嵌物件導致内嵌物件儲存，以及重新儲存包含文件 (如果已啟用自動儲存，會建立新版本) 的問題。


- 我們已修正此問題: [另存新檔] 作業的自動儲存關閉, 將檔案儲存至原始雲端檔案, 而不是建立新的版本。


- 我們已修正問題, 因此如果使用者明確以唯讀模式開啟檔案, 應用程式就不會再提示輸入密碼來修改。


### <a name="project"></a>Project

- 我們已修正此問題: 貼上連結在專案中的資訊變更時並未更新。


- 我們已修正在 Project 中重新排程工作時，手動排程的工作可能會早於其預定的排程時間問題。


- 我們已修正當透過 CSOM 以程式設計方式將新工作新增到專案時，如果新工作的工作摘要已摺疊，工作可能無法插入正確位置的問題。


### <a name="visio"></a>Visio

- 焦點移往畫布中其他位置的問題已在最新組建中修正。 您現在可以使用文字的貼上捷徑方式，而不需要面臨文件移轉。 將在最新組建中提供修正程式


### <a name="word"></a>Word

- 我們已修正當使用者選取 [檔案] > [另存新檔] 時，應用程式停止回應的問題。


- 我們已修正此問題: 撰寫混合語言方向的註解 (像是英文和希伯來文) 導致文字順序出現錯誤。


- 我們已修正當使用者在聽寫註解回覆並按一下註解文字時，應用程式會意外關閉的問題。


- 我們已修正大型 URL 的問題: 如果其長度超過特定字元限制, 在此情況下無法開啟連結。


- 我們已修正應用程式在註解中「提及」(@mention) 某人時停止回應的問題。


- 我們已修正合併列印格式化的文件無法以.doc 儲存的問題。


- 我們已修正持續縮放比例的問題: 發生於重新執行並開啟以不同縮放比例儲存的文件時。


- 我們已修正大聲朗讀播放有時候會跳至文件中隨機位置的問題。


- 我們已修正當您已選取頁面寬度縮放功能而關閉註解窗格時, 與頁面寬度相關的問題。


- 我們已修正此問題: 當游標移離新式註解時, 錨點重點項目不會從新式註解移除。


- 我們已修正導致自動卷軸模式無法運作的問題。


- 我們已修正在無邊際網頁檢視中，某些跨越多個頁面的資料表會向上和向下彈跳 (由於重新繪製) 的問題。


- 我們已修正此問題: 選取並以滑鼠右鍵按一下鎖定內容控制項以進行刪除時, Word 沒有回應。


- 我們已修正共同撰寫模式可能無法儲存修改的問題。


- 我們已修正某些文件中可能會遺失圖形的問題。


- 我們已修正將文字以「保留純文字」貼上時, 某些字型樣式無法正確對應的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正「wdlor」+ GUID 查詢參數可能會新增到連結的結尾問題。


- We fixed an issue where an update would stop responding. The update would open Software Center as expected; it would start the "download and apply" phase, but then would stop responding and an error would appear: 0x87d00668 ("Software update still detected as actionable after apply").


- 我們已修正會影響 MSI Office 2007 catalyst 偵測邏輯，導致 Visio 和 Project 遭到意外移除的問題。


- 我們已修正此問題, 使以有限權限開啟的文件可以啟用色彩選擇工具的功能。


- 我們已修正 Office 文件中已損壞的 SVG 無法呈現 (顯示為紅色 X)，改以未損壞的影像點陣圖版本呈現的問題。


- 我們已修正在 PowerPoint 的投影片放映簡報模式中, 裁剪成非矩形圖案的動畫 GIF 無法呈現動畫的問題。


- 我們在 [錄製投影片放映] 對話方塊中新增了一個選項, 以移除關閉時 [匯出至視訊] 的提示。


- 我們已修正預設敏感度標籤未在加密電子郵件上套用的問題。


- 我們已修復此問題: Excel 無法開啟使用應用程式防護開啟的活頁簿儲存的活頁簿。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2110-november-05"></a>版本 2110：11 月 05 日
*版本 2110 (組建 14527.20268)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Excel 4.0 (xlm) 巨集預設為停用：** 對於沒有群組原則設定或尚未在 Excel 信任中心設定 XLM 巨集設定的使用者，預設會停用 Excel 4.0 巨集 (XLM)。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 開啟 Dynamics 的連結資料表時，顯示資料時，數字可能會呈現為小型方塊。 若要解決此問題，請在資料表設計檢視中開啟連結，並清除任何受影響資料行的格式屬性。

### <a name="outlook"></a>Outlook

- 我們已修正以滑鼠右鍵按一下並選取檔案系統中的「傳送郵件」來傳送郵件，導致 explorer.exe 在 VDI 電腦上意外關閉的問題。


### <a name="project"></a>Project

- 已修正在 Project 中重新排程工作時，手動排程的工作可能會早於其預定的排程時間問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2110-november-03"></a>版本 2110：11 月 3 日
*版本 2110 (組建 14527.20254)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **將 Teams 即時活動擴大至 10 萬個出席者：** 當您與 Microsoft LEAP 團隊接洽，以尋求產生與傳遞您的活動的協助時，現在支援 10 萬個 Teams 即時活動。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 開啟 Dynamics 的連結資料表時，顯示資料時，數字可能會呈現為小型方塊。  若要解決此問題，請在資料表設計檢視中開啟連結，並清除任何受影響資料行的格式屬性。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正當使用者將原始直向和較大的紙張大小文件變更為較小的紙張大小 (例如，從 Letter 變更為 A5) 時，其列印可能會遭到截斷 (遺失資料) 的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2110-october-28"></a>版本 2110: 10 月 28 日
*版本 2110 (組建 14527.20234)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **新的搜尋結果頁面體驗：** Teams 中的新搜尋結果頁面體驗可讓您更快速、更直觀地尋找郵件、人員、答案和檔案。 此頁面將會顯示每個網域的熱門結果、書籤和縮略字答案、整齊的搜尋結果片段、預覽訊息結果以取得更多內容、更多可探索的篩選條件、檔案預覽，以及根據 Teams 和其他 Microsoft 365 服務中大部分參與之人員與內容提供更好的相關性。

- **Bookings 應用程式中已排程的虛擬看診佇列檢視：** Bookings 應用程式中已排程的虛擬看診佇列視中的會議狀態即時更新。

- **Teams EHR 連接器 - Cerner 整合：** 整合 Microsoft Teams 和 Cerner 以進行虛擬看診。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 已修正在繪製影像時, 應用程式可能會停止回應的問題。


### <a name="powerpoint"></a>PowerPoint

- 已修正在繪製影像時, 應用程式可能會停止回應的問題。


### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新

- 已修正部分膝上型電腦的混合式相機未在 SfB 用戶端中顯示的問題。


### <a name="word"></a>Word

- 已修正在繪製影像時, 應用程式可能會停止回應的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2110-october-25"></a>版本 2110：10 月 25 日
*版本 2110 (組建 14527.20226)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **新的搜尋結果頁面體驗：** Teams 中的新搜尋結果頁面體驗可讓您更快速、更直觀地尋找郵件、人員、答案和檔案。 新的 [所有] 頁面會顯示每個網域的熱門結果、[書籤] 和 [縮略字答案]、整齊的搜尋結果片段、預覽訊息結果以取得更多內容、更多可探索的篩選條件、檔案預覽，以及根據 Teams 和其他 Microsoft 365 服務中大部分參與之人員與內容提供更好的相關性。

- **Bookings 應用程式中的已排程虛擬看診佇列檢視：** Bookings 應用程式中的已排程虛擬看診佇列視中的會議狀態即時更新。

- **Teams EHR 連接器 - Cerner 整合：** 整合 Microsoft Teams 和 Cerner 以進行虛擬看診。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正查詢更新導致 Excel 停止回應的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2110-october-22"></a>版本 2110：10 月 22 日
*版本 2110 (組建 14527.20216)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **新的搜尋結果頁面體驗：** Teams 中的新搜尋結果頁面體驗可讓您更快速、更直觀地尋找郵件、人員、答案和檔案。 新的 [所有] 頁面會顯示每個網域的熱門結果、[書籤] 和 [縮略字答案]、整齊的搜尋結果片段、預覽訊息結果以取得更多內容、更多可探索的篩選條件、檔案預覽，以及根據 Teams 和其他 Microsoft 365 服務中大部分參與之人員與內容提供更好的相關性。

- **Teams EHR 連接器 - Cerner 整合：** 整合 Microsoft Teams 和 Cerner，以進行虛擬看診


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會在產生預覽時導致同步處理失敗發生的問題。


- 我們已修正會導致使用 Windows 11 的使用者，或透過「即將推出」使用視覺效果的使用者，在將游標停留在迷你行事曆日期時看到文字未對齊的問題。


- 我們已修正會導致使用 Windows 11 的使用者，或透過「即將推出」使用視覺效果的使用者，在調整 Outlook 視窗時，在功能區中看到一些對齊問題和奇怪的視覺效果構件的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2110-october-18"></a>版本 2110：10 月 18 日
*版本 2110 (組建 14527.20178)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **新的搜尋結果頁面體驗：** Teams 中的新搜尋結果頁面體驗可讓您更快速、更直觀地尋找郵件、人員、答案和檔案。 新的 [所有] 頁面會顯示每個網域的熱門結果、[書籤] 和 [縮略字答案]、整齊的搜尋結果片段、預覽訊息結果以取得更多內容、更多可探索的篩選條件、檔案預覽，以及根據 Teams 和其他 Microsoft 365 服務中大部分參與之人員與內容提供更好的相關性。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="office-suite"></a>Office 套件

- 我們修正了包含無效 SVGs 的文件會顯示點陣化遞補影像，而不是紅色 X 的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2110-october-11"></a>版本 2110：10 月 11 日
*版本 2110 (組建 14527.20128)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們修正了導致所有使用敏感度標籤所送出的電子郵件持續使用「僅加密」範本，導致不正確的行為，允許人員轉寄「僅收件者」電子郵件的問題。


- 我們修正了導致使用者載入 [行事曆] 模組的功能窗格時，遇到「停止」回應的問題。


- 我們修正了預覽會議邀請時導致約會快速模式被裁掉的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2110-october-05"></a>版本 2110：10 月 05 日
*版本 2110 (組建 14527.20072)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正 Excel 的括住數字字元會顯示問號的問題。


- 我們已修正使用者報告很難從 Office 淺色主題中未選取的索引標籤中，判斷已選取索引標籤的問題 (只有啟用 Fluent UI 即將推出切換的使用者才會出現此問題)。


- 我們修正了部分選取範圍中的列和欄標題色彩無法從深灰色主題中的魚缸色彩辨別的問題 (只有啟用 Fluent UI 即將推出切換的使用者才會出現此問題)。


- 我們修正了 Excel 巨集語言中警示對話方塊未以適當類型顯示的問題。


- 我們已修復複製及貼上內容時出現記憶體不足警告的問題。


- 我們已修復此問題：其數字格式用於非英文區域系統設定的資料型別屬性值。


- 我們已修正少數 GCC-H 租用戶無法使用自動敏感度標籤的問題。


- 我們已修復此問題：在某些情況下，在已啟用凍結窗格的工作表中，最上層的列可能會重複出現。


- 我們已修復在 Office 應用程式之間，以不同方式轉譯 BizUD Gothic 日文字型的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致儲存至硬碟的 HTML 電子郵件草稿變更為純文字格式的問題。


- 我們已修正會導致某些使用者在新增共用行事曆後遇到意外關閉的問題。


- 我們已修正在執行人員搜尋時，導致某些使用者遇到意外關閉的問題。


- 我們已修正在執行人員搜尋時，導致某些使用者遇到意外關閉的問題。


- 我們已修正透過 [傳送至] 建立的郵件無法取得預設敏感度標籤的問題。


- 我們已修正按兩下以儲存不受信任的附件時，無法儲存至網路位置的問題。


- 我們已修正在嘗試擷取 [自動探索] 設定時，導致某些使用者遇到停止回應的問題。


- 我們已修正透過 [傳送至] 建立的郵件無法取得預設敏感度標籤的問題。


- 我們已修復代理人無法在排程助理員中查看召集人詳細資料的問題。


- 我們已修正某些使用者的框架控制視窗中已停用敏感度索引標籤的問題。


- 我們已修正搜尋未包含來自線上封存信箱的項目的問題。


- 我們已修正會導致 Outlook 使用者的共用行事曆改良功能遇到高 CPU 使用率的問題。


- 我們已修正會導致新增到「捷徑」模組的行事曆，在 Outlook 重新啟動後會消失的問題。


- 我們已修正會導致使用者看到他們新增的共用行事曆預設未經過檢查，導致他們認為無法新增該行事曆的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正在投影片放映中，子功能表在錯誤位置開啟的問題。


- 我們已修復在另一個程式中貼上 PowerPoint 投影片時不會顯示墨水的問題。


- 我們已修復此問題：嘗試為儲存至 OneDrive 或 SharePoint 的不受支援副檔名開啟檔案 AutoSave 會顯示 [共用] 對話方塊。


### <a name="project"></a>Project

- 我們已修正了當企業編號自訂欄位更新時，如果小數分隔符號不是句號，企業資源會無法儲存的問題。


- 我們已修復導致 Visual Basic 應用程式 (VBA) OrganizerMoveItem 方法，用來將自訂欄位資訊從一個專案移至另一個專案，使其在省略 Name 參數時無法正常運作的問題。


- 當 [前置任務] 欄位變更時，BeforeTaskChange 事件會引發兩次；第二個事件也包含不正確的資訊。


### <a name="word"></a>Word

- 我們已修復導致儲存指示器停止回應的問題。


- 我們已修正同步處理的檔案和本機備份的檔案中的變更無法同步處理及進度會遺失的問題。


- 我們已修復在使用高 CPU 百分比時，Word 的回應變得緩慢的問題。


- 我們已修正新式註解中自動校正無法運作的問題。


- 我們已修復文件出現並以閃爍動作消失的問題。


- 我們已修復轉寄包含長影像 URL 的電子郵件無法顯示的問題。


- 我們已修復在 Office 應用程式之間，以不同方式轉譯 BizUD Gothic 日文字型的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修復使用者無法在與具有讀取權限的 SharePoint 資料夾同步處理的資料夾中開啟 .xls/.ppt/.doc 檔案的問題。


- 我們已修復 Excel 中在開始進行維護之前，會出現錯誤 ERROR_DISK_FULL 的問題。


- 我們已修正符號字元在資料類型卡片中會錯誤顯示為底線的問題。


- 我們已修正 Excel 現在對輸入事件有更多的控制項，且使用者可以明確決定何時要啟動 PTP 手勢的問題。


- 我們已修復當播放動畫 GIF 時，會對電子郵件或文件中的輸入速度產生負面影響的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2109-september-27"></a>版本 2109：9 月 27 日
*版本 2109 (組建 14430.20234)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致某些使用者在新增共用行事曆後遇到意外關閉的問題。


- 我們已修正會導致 Outlook 使用者的「共用行事曆改良」功能遇到高 CPU 使用率的問題。


- 我們已修正會導致新增到「捷徑」模組的行事曆，在 Outlook 重新啟動後會消失的問題。


- 我們已修正會導致使用者看到他們新增的共用行事曆預設未經過檢查，導致他們認為無法新增該行事曆的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2109-september-24"></a>版本 2109：9 月 24 日
*版本 2109 (組建 14430.20220)*
* 各種錯誤和效能修正。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **用於取得範本的圖形 API：** 取得範本圖形 API 將提供組織中可用的團隊範本清單。 範本清單包含 Microsoft 提供的內建範本，以及租用戶建立的自訂企業營運範本。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2109-september-13"></a>版本 2109: 9 月 13 日
*版本 2109 (組建 14430.20148)*
* 各種錯誤和效能修正。

## <a name="version-2109-september-09"></a>版本 2109：9 月 09 日
*版本 2109 (組建 14430.20088)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正導致資料表進入查詢設計或系統關聯性視窗時，出現在與資料表被丟棄位置不同的位置的錯誤。


- 我們已修正在將記錄貼至子表單時發生錯誤之後，當表單關閉時，已新增到子表單的資料會被捨棄的問題。


- 我們已修正嘗試使用來自非 Office 應用程式的 DAO API 時會導致失敗並出現 [作業系統目前未設定成執行此應用程式] 訊息的問題。


- 我們已修正現在會啟用 Outlook 增益集事件的問題。


- 我們已修正錯誤訊息中包含特殊字元的問題。

- In certain customer configurations, it has been discovered that document exports to PDF or XPS formats from Office may fail due to recent updates. This update fixes these regressions and reenables export to these formats.


### <a name="excel"></a>Excel

- 我們已修正 [插入儲存格] 對話方塊的問題，其中有一個選項按兩下時，無法應用選取的選項並關閉對話方塊。


- 我們已修正導致對數資料圖表上趨勢線不平滑的問題。


- 我們已修正如果工作表中的最後一列或最後一欄已隱藏，使用滑鼠滾輪或觸控板捲動無法作用的問題。


- 我們已修正在使用特定自訂數字格式儲存檔案時可能會發生的意外關閉問題。


- 我們已修正某些字元集無法正確顯示在工作表分頁的問題。


- 我們已修正 Analysis ToolPak 增益集無法與特定 [自動化安全性] 設定一起使用的問題。


- 我們已修正 Excel 在下列情況下，可能會在計算活頁簿時停止回應的問題。


- 我們已修正 Excel 在非 MSI 的 Office 安裝中，HKEY_CURRENT_USER\SOFTWARE\Microsoft\Office\Common\UserInfo\Company 值遭到清除的問題。


- 我們修正了在 Selection.Parent.Copy 呼叫之後切換分隔符號的問題。


- 我們已修正 [尋找/取代] 對話方塊只儲存 [尋找] 但非 [取代] 的歷程記錄 (對話方塊未儲存 [取代] 時所取代的歷程記錄) 的問題。


- 我們已修正工作表中在某些捲動案例啟用 [凍結窗格] 的呈現問題。


- 我們已修正圖形在重新計算期間的穩定性相關問題。


- This version fixes an issue when the app closes unexpected. This happens during Save for some documents in tenants which have opted into protected coauthoring if the local file cache has tenant Id datum formatted incorrectly.


- In certain customer configurations, it has been discovered that document exports to PDF or XPS formats from Office may fail due to recent updates. This update fixes these regressions and reenables export to these formats.


### <a name="onenote"></a>OneNote

- 將建立快速筆記的熱門金鑰更新為 Win + Alt + N。


### <a name="outlook"></a>Outlook

- 已修正導致應用程式在使用 Outlook 時停止回應的問題。


- 我們已修正應用程式停止回應大量群組的問題。


- 我們已修正造成 [會議室尋找工具] 無法載入的問題。


- 我們已修正導致使用者能夠下載受保護的語音信箱檔案的問題。


- 我們已修正導致使用者在將電子郵件草稿儲存至磁片時，看到 HTML 格式設定遺失的問題。


- 我們已修正允許使用者下載受保護附件的問題。


- 我們已修正使用 Outlook 撰寫電子郵件時應用程式停止回應的問題。


- 我們已修正 Outlook 開機後，應用程式不久後停止回應的問題。


- 我們已修正帳戶的 UPN/SMTP 名稱變更之後，電子郵件簽名會遺失的問題。


- 已修正僅對簽章內容的變更不會在雲端式設定中更新的問題。


- 我們已修正將大型或長時間執行週期性會議以 ICAL 轉送時所造成的錯誤。


- 我們已修正從連絡人卡片中的郵件連結建立郵件主題時，會預先以非預期字元預先填充的問題。


- 我們已修正導致提醒間歇性延遲顯示，並顯示對話方塊中錯誤時間的問題。


- 我們已修正在 Outlook 中建立會議時且 Exchange 系統管理員未設定選項時，預設出現有關縮短會議之非預期資訊型通知提示的問題。


- 已修正會議項目取消表單會出現，而不是預期的編輯表單的問題。


- 我們已修正在 Outlook 開機後，使用具有多個帳戶的設定檔導致網路活動增加的問題。


- 我們已修正導致某些使用者間歇性地重新顯示已刪除的會議邀請的問題。


### <a name="powerpoint"></a>PowerPoint

- This version fixes an issue when the app closes unexpected. This happens during Save for some documents in tenants which have opted into protected coauthoring if the local file cache has tenant Id datum formatted incorrectly.


- In certain customer configurations, it has been discovered that document exports to PDF or XPS formats from Office may fail due to recent updates. This update fixes these regressions and reenables export to these formats.


- 已修正重新啟用 SmartArt 和 AutoShape 物件內圖片的「重設圖片和大小」的問題。


- 我們已修正預覽列印期間，投影片大小可能會變更的問題。


- 我們已修正 Word 存檔時，所花時間超過預期的問題。


### <a name="project"></a>Project

- 我們修正了當以程式設計方式將新任務新增到專案時，如果新任務的摘要任務已摺疊，任務可能無法插入正確的位置的問題。


### <a name="publisher"></a>發行者

- 我們已修正圖形在重新計算期間的穩定性問題。


### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新

- 我們已修正在交談視窗中，影片共用預覽會意外關閉的問題。


### <a name="visio"></a>Visio

- 我們已修正從 Visio 匯出至 PowerPoint 時，Visio 影像對來源來說為 True 的問題，且在呈現時沒有任何失真或問題。


### <a name="word"></a>Word

- This version fixes an issue when the app closes unexpected. This happens during Save for some documents in tenants which have opted into protected coauthoring if the local file cache has tenant Id datum formatted incorrectly.


- In certain customer configurations, it has been discovered that document exports to PDF or XPS formats from Office may fail due to recent updates. This update fixes these regressions and reenables export to these formats.


- 我們修正了使用書簽儲存及開啟文件的問題。


- 我們已修正啟用自動儲存會導致最新的編輯暫時消失的問題。


- 我們已修正在上傳檔案期間，應用程式停止回應且文件未同步的問題。


- 我們已修正註解中若將圖示、貼圖和圖例與註解中的文字一起貼上，就看不到的問題。


- 已修正顯示新版視覺效果的對話方塊包含螢幕助讀程式無法讀取的文字的問題。


- 我們已修正圖形在重新計算期間的穩定性相關問題。


- 我們已修正將圖表匯出為 EMF 的相關問題，使在 Office 中以圖片插入 EMF 時，EMF 具有可編輯的標籤。


- 已修正當使用 [此裝置] 選項編輯與新增圖片相關之連絡人的問題。


- This version fixes an issue when the app closes unexpected. This happens during Save for some documents in tenants which have opted into protected coauthoring if the local file cache has tenant Id datum formatted incorrectly.


- 我們已修正與應用程式在呼叫 DCompositionCreateDevice 時停止回應相關的問題。


- 我們已修正應用程式使用 RD 欄位代碼，在插入的目錄上無法正確顯示章節/文件頁碼的問題。


- 已修正在共同撰寫文件時發生的儲存錯誤。


- 我們已修正插入線上影片按鈕遭到停用的問題。


- 我們已修正 Word 無法呈現電子郵件本文中內嵌 base-64 編碼 GIF 的問題。


- 我們已修正表格中的重複標題列功能在某些情況下停用的問題。


- 我們已修正在使用日文輸入法 (IME) 輸入平假名時，開啟 At Mention 人員選擇器時導致 IME 停止運作的問題。



- 已修正從首頁 (Home) 索引標籤套用樣式時無法運作的問題。


- 我們已修正非預設功能區組態可能導致樣式庫無法運作的問題。


- 我們已修正 Document.Save 命令的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正與下列案例相關的問題: 使用建立視訊從預設 OneDrive 位置的簡報匯出視訊時，會出現錯誤訊息，指出該位置不可用。


- We improved behavior during file save to a location requiring user access approval. The Grant Access screen should now appear to allow user access approval.



- 已修正 Outlook 中的自訂 VSTO 控制項在開啟和切換多個視窗和視圖之後停止運作的問題。


- 我們已修正在某些 Windows 版本上插入或編輯列相關的效能問題。


- 我們已修正從 Word 複製的圖片，在貼入其他 Office 應用程式中的繪圖畫布上時，無法保留其 [鎖定長寬比] 設定的問題。


- 已修正從各種 URLs 中識別和插入 SVG 檔案的問題。


- 我們已修正使用某些 Web 增益集後，某些文件無法載入的問題。

- 我們已修正導致樞紐分析表中的日期欄位分組錯誤的問題。


- 我們已修正 [大聲朗讀] 神經語音迴歸停止回應的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2108-september-07"></a>版本 2108：9 月 7 日
*版本 2108 (組建 14326.20348)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正錯誤訊息中包含特殊字元的問題。


### <a name="onenote"></a>OneNote

- 已將建立 [快速筆記] 的熱門金鑰更新為 Win + Alt + N


### <a name="outlook"></a>Outlook

- 我們已修正造成 [會議室尋找工具] 無法載入的問題。


- 我們已修正在 Outlook 中建立會議時且 Exchange 系統管理員未設定選項時，預設出現有關縮短會議之非預期資訊型通知提示的問題。


- 我們已修正導致某些使用者間歇性地重新顯示已刪除的會議邀請的問題。


- 我們已修正導致位置欄位中的連結無法按一下的問題。


### <a name="word"></a>Word

- 已修正顯示新視覺重新整理的對話方塊包含螢幕閱讀程式無法讀取的文字的問題。


- 我們已修正列印中未載入預覽列印的問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2108-august-30"></a>版本 2108: 8 月 30 日
*版本 2108 (組建 14326.20282)*
* 各種錯誤和效能修正。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2108-august-24"></a>版本 2108: 8 月 24 日
*版本 2108 (組建 14326.20238)*
* 各種錯誤和效能修正。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **小組範本：** 在 Microsoft 提供之預先定義小組結構中使用其他應用程式與通道來重新整理至小組範本內容。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="teams"></a>Teams

- 我們已修復在交談視窗中影片共用預覽會意外關閉的問題。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2108-august-20"></a>版本 2108：8 月 20 日
*版本 2108 (組建 14326.20222)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **查閱/轉接的等候音樂：** 查閱/轉接的等候音樂案例，可確保通話保留中的使用者在查閱與轉接時聽到音樂，確保來電者知道通話仍在使用中。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正現在會啟用 Outlook 增益集之啟動事件的問題。


### <a name="excel"></a>Excel

- 已修正分析工具箱增益集無法與特定自動化安全性設定一起使用的問題。


- 我們已修正導致樞紐分析表中的日期欄位分組錯誤的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致使用者能夠下載受保護的附件的問題。


- 我們已修正 Outlook 開機後，應用程式不久後停止回應的問題。


- 我們已修正帳戶的 UPN/SMTP 名稱變更之後，電子郵件簽名會遺失的問題。


- 已修正以 ICAL 轉送一些大型或持續很久的週期性會議時所發生的錯誤。


- 已修正會議項目取消表單會出現，而不是預期的編輯表單的問題。


- 我們已修正導致應用程式在使用 Outlook 時停止回應的問題。


- 我們已修正在 Outlook 開機後，使用具有多個帳戶的設定檔導致網路活動增加的問題。


### <a name="word"></a>Word

- 我們已修正插入線上影片按鈕被停用的問題。


- 我們已修正無法關閉「繼續」區段中任何編輯器選項的問題。


- 我們已修正非預設功能區設定可能導致樣式庫無法運作的問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2108-august-16"></a>版本 2108：8 月 16 日
*版本 2108 (組建 14326.20136)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams


- **Citrix 的雙音多頻訊號：** Citrix 客戶 VDI 上的 Teams DTMF。適用於 Teams 的雙音多頻訊號 (DTMF) 現在可供 Citrix VDI 上的使用者使用。 之前，當 Citrix VDI 使用者使用撥入號碼撥入會議時，通話雖已連接，但您會因為未送出 DTMF 音調而未獲准加入會議。 現在，當同一位使用者輸入會議識別碼時，DTMF 會識別輸入的識別碼，並准許使用者加入會議。

- **聊天失敗時的錯誤畫面：** 萬一會議期間無法呈現聊天，使用者會看到聊天錯誤畫面。


### <a name="outlook"></a>Outlook


- **瀏覽群組 OPX：** 瀏覽群組的 OPX 體驗以支援工程靈活度。



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正使用 Outlook 撰寫電子郵件時應用程式停止回應的問題。


- 已修正僅對簽章內容的變更不會在雲端式設定中更新的問題。


### <a name="office-suite"></a>Office 套件

- 已修正 Outlook 中的自訂 VSTO 控制項在開啟和切換多個視窗和視圖之後停止運作的問題。


- 已修正使用觸控或觸控板在 PPT 投影片中捲動縮圖視圖的相關問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2108-august-06"></a>版本 2108：8 月 06 日
*版本 2108 (組建 14326.20074)*
* 各種錯誤和效能修正。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="word"></a>Word

- **Proofing is now available for selected text within the Document:** With this change we can now review spelling, grammar and other intelligent writing suggestions for just the selected text. Additionally we can also review suggestions for the whole document.<br />在[部落格文章](https://insider.office.com/en-us/blog/proof-selected-text-in-a-word-document)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2108-august-04"></a>版本 2108：8 月 04 日
*版本 2108 (組建 14326.20046)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Lambda: Custom Functions Without Code:** The lambda function allows you to take any existing formula or expression and turn it into a custom function with a name. Easily reuse and update logic in your spreadsheet with the lambda function.

### <a name="office-suite"></a>Office 套件

- **在 Word、Excel 和 PowerPoint 中使用 WebP 影像：** Office 現在推出了 WebP 支援，可支援更多影像。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- In certain customer configurations, it has been discovered that document exports to PDF or XPS formats from Office may fail due to recent updates. This update fixes these regressions and reenables export to these formats.

### <a name="excel"></a>Excel

- 我們已修正當來源 .xlsx 檔案已在背景執行，且兩個檔案都是從 ODB 本地同步處理資料夾開啟時，PowerPoint 連結檔案無法使用的問題。


- 在某些語言中，「檔案」索引標籤文字被裁切掉。


- 我們已修正當試算表縮小時，小型資料標記消失的問題。


- 我們已修正開啟 CSV 檔案時，現在可以識別當地語系化函數名稱的問題。


- 我們已修正當活頁簿因為另一個使用者進行修改和存檔而關閉並重新開啟時，卻開啟其他活頁簿的問題。


- 我們已修正從包含 XML 地圖的活頁簿中另存為 XML 資料 (.xml) 時發生的問題。


- 我們已修正使用觸控功能或觸控板捲動時，會還原回試算表起始位置的問題。



- 我們已修正受保護的檔案不具有標籤中繼資料的問題；此標籤是由保護所決定。 強制標籤現在使用標籤中繼資料和標籤策略。


- 我們已修正與文字游標動畫相關的穩定性問題。


- In certain customer configurations, it has been discovered that document exports to PDF or XPS formats from Office may fail due to recent updates. This update fixes these regressions and reenables export to these formats.




### <a name="outlook"></a>Outlook

- 我們已修正使用者無法開啟或預覽電子郵件的問題。


- 我們已修正在載入收集診斷資料時，導致某些使用者遇到意外關閉的問題。


- 我們已修正在從 PST 重新傳送郵件時，導致由 [重新傳送此郵件] 選項所產生之訊息的修改會在傳送時遺失的問題。


- 我們已修正會導致在 SendFromAliasEnabled 設定為 True 的組織中，由不同使用者重新傳送的電子郵件會顯示為由原始寄件者傳送的問題。


- 我們已修正在執行搜尋時，導致某些使用者遇到意外關閉的問題。


- 我們已修正在 Win Server 2016 上安裝 Office 時，Outlook 電腦版中的某些通知無法正常運作的問題。


- 我們已修正當設定檔中出現未完整設定的帳戶時，造成雲端設定使用者遇到意外關閉的問題。


- 我們已修正導致代理人嘗試在寄件備份檔案夾中查看轉寄的會議要求，會看到主管的會議副本，而非代理人所寄項目的問題。


- 我們已進行變更，允許系統管理員透過群組原則，停用以每個程式為基礎的 Always On Logging 功能。


- 我們已修正導致使用者能夠下載受保護的語音信箱檔案的問題。


- 我們已修正當會議開始與會議結束在不同的日期時，導致使用者在結束會議時間下拉式清單中看到重複時間項目的問題。


- 我們已修正在載入收集診斷資料時，導致某些使用者遇到意外關閉的問題。



### <a name="powerpoint"></a>PowerPoint

- 我們已修正例外導致應用程式意外關閉的問題。


- 我們已修正重新啟動 SmartArt 物件內圖片裁剪的問題。


- 我們已修正在某些情況下，使用者無法使用 Paste Special 將圖表內容從 Excel 貼到 PowerPoint 的問題。


- 我們已修正 Word 存檔時，所花時間超過預期的問題。


- In certain customer configurations, it has been discovered that document exports to PDF or XPS formats from Office may fail due to recent updates. This update fixes these regressions and reenables export to these formats.


### <a name="project"></a>Project

- 我們已修正專案具有跨專案連結和固定成本時，無法建立視覺報表的問題。


- 我們已修正當您套用視圖或表格時，並未實際顯示所有應該顯示之欄位的問題。



### <a name="word"></a>Word

- 我們已修正在註解中插入連結時，應用程式意外關閉的問題。


- 我們已修正 Word Mobile 中與列印尺寸太小相關的問題。


- 我們已修正在 [閱讀] 模式中，[下一頁/上一頁] 按鈕被截斷的問題。


- 我們已修正校對設定無法保留的問題。


- 我們已修正游標可能無法顯示在分頁線之後的問題。


- 我們已修正在共同撰寫期間，項目符號可能會從文字中消失的問題。


- 我們已修正新增到 SharePoint 文件庫的檔案在開啟後立即繼承設定「ShowDocument 資訊面板」的問題，如果檔案從 SharePoint 中移除，它也會保留。


- 我們已修正當 [追蹤修訂] 開啟時，Word 透過 VBA 更新 [內容表格] 欄位時沒有回應的問題。


- 我們已修正導致插入 GIF 以顯示安全性注意事項產生的問題。


- 我們已修正與儲存檔案相關的問題。


- 我們已修正 Word 存檔時，所花時間超過預期的問題。


- 我們已修正 URL 剖析器不正確地解譯未以「/」 結尾的資料夾名稱的問題。


- In certain customer configurations, it has been discovered that document exports to PDF or XPS formats from Office may fail due to recent updates. This update fixes these regressions and reenables export to these formats.

### <a name="office-suite"></a>Office 套件

- 我們已修正在轉換至 None 時，Fire 共同作者狀態會遭變更的問題。


- 我們已修正某些語言的文字因文字大小增加而遭截斷的問題。


- 在 Outlook 中從郵件視圖切換到行事曆視圖時，表示使用中功能區索引標籤的底線顯示在錯誤的位置


- 我們已修正在搜尋方塊上新增 DropShadow 屬性時，導致標題列太高，導致版面配置錯誤的問題。


- 我們已修正高 DPI 顯示器的工作窗格中文字換行錯誤的問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2107-august-02"></a>版本 2107：8 月 02 日
*版本 2107 (組建 14228.20222)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致在 SendFromAliasEnabled 設定為 True 的組織中，由不同使用者重新傳送的電子郵件會顯示為由原始寄件者傳送的問題。


- 我們已修正當會議開始與會議結束在不同的日期時，導致使用者在結束會議時間下拉式清單中看到重複時間項目的問題。


- 我們已修正導致共用日曆改進功能的使用者在 Outlook 重新開機之前，無法顯示新加入的共用日曆的問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2107-july-22"></a>版本 2107：7 月 22 日
*版本 2107 (組建 14228.20186)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="powerpoint"></a>PowerPoint

- **Add Flipgrid videos to your presentation:** PowerPoint now supports Flipgrid videos along with other video types. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正在載入收集診斷資料時，導致某些使用者遇到意外關閉的問題。


- 我們已修正在從 PST 重新傳送郵件時，導致由 [重新傳送此郵件] 選項所產生之訊息的修改會在傳送時遺失的問題。


- 我們已修正在執行搜尋時，導致某些使用者遇到意外關閉的問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2107-july-16"></a>版本 2107：7 月 16 日
*版本 2107 (組建 14228.20154)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **Use suggested replies in Outlook:** When you receive an email message that can be answered by a short response, Outlook can suggest three responses you can use to reply with just a couple of clicks. [Learn more](https://support.office.com/article/19316194-0434-43ba-a742-6b5890157379)<br />在[部落格文章](https://insider.office.com/en-us/blog/reply-faster-using-suggested-replies-in-outlook)中查看詳細資料

- **建立 Outlook.com 帳戶的連結：** 新增帳戶至 Outlook 時，視窗中會顯示 outlook.com 帳戶的連結。

- **關閉建議回覆：** Outlook [使回覆更為簡單快速](https://insider.office.com/blog/reply-faster-using-suggested-replies-in-outlook) 透過提供僅需幾個字回覆的簡短建議回覆郵件，讓回覆電子郵件更為快速。 部分使用者可能不想看到此選項，因此現在可以關閉此功能。 若要這麼做，請選取檔案 > 選項> 郵件，前往回覆和轉寄區段，然後清除顯示建議的回覆核取方塊。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正如果 Application.DisplayAlerts 設定為 True，就無法從 VBA 開啟受 DRM 保護的活頁簿的問題。


### <a name="outlook"></a>Outlook

- 我們已修正當設定檔中出現未完整設定的帳戶時，造成雲端設定使用者遇到意外關閉的問題。


### <a name="word"></a>Word

- 已修正在受密碼保護的 DOCX 檔案上維護引文的「最新清單」的問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2107-july-08"></a>版本 2107：7 月 8 日
*版本 2107 (組建 14228.20070)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **REST 轉寄會議要求：** 允許使用者轉寄先前拒絕的 REST 共用日曆會議。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="word"></a>Word

- 已修正 Word 畫布旁的註解卡片大小不正確的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2107-july-06"></a>版本 2107：7 月 6 日
*版本 2107 (組建 14228.20044)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **另存新檔案例支援的其他檔案類型：** 除了儲存檔案之外，您還可以將檔案儲存到其他檔案類型。

- **Government Customers: Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see. This is a silent functionality (no UI) for administrator benefit.

### <a name="powerpoint"></a>PowerPoint

- **另存新檔案例支援的其他檔案類型：** 除了儲存檔案之外，您還可以將檔案儲存到其他檔案類型。

- **Government Customers: Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see. This is a silent functionality (no UI) for administrator benefit.

### <a name="word"></a>Word

- **另存新檔案例支援的其他檔案類型：** 除了儲存檔案之外，您還可以將檔案儲存到其他檔案類型。

- **Government Customers: Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see. This is a silent functionality (no UI) for administrator benefit.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 修正可能導致使用 Access 資料庫引擎 ODBC API 的應用程式意外關閉的問題。


- 修正可能導致使用 Access 資料庫引擎 OLEDB API 的應用程式搭配的資料庫包含 SharePoint 清單連結時，會意外關閉的問題。


### <a name="excel"></a>Excel

- 我們已修正 CFR 執行發生例外情況的問題。


- 我們已修正如果千位和小數分隔符號都使用相同的符號，圖表座標軸值無法變更的問題。


- 已修正部分使用者在 Excel 增益集清單中顯示額外項目的問題。


- 我們已修正在儲存至 SPO 文件庫時，儲存的活頁簿會顯示在最近清單頂端的問題。


- 我們已修正啟用舊版增益集時，會開啟空白的重複視窗的問題。


### <a name="onenote"></a>OneNote

- 我們已修正在複製段落連結時，不一定會重新導向到正確頁面的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致某些使用者的翻譯選項遭到停用的問題。  遇到此錯誤的客戶在瀏覽至檔案 -> 選項 -> 語言時，會看見其翻譯選項已遭停用。 有鑑於此，他們可能無法變更其偏好的翻譯語言和其他翻譯相關設定。


- 我們已修正與「無法載入」回應狀態相關的問題。 預設的回應標幟已設定為「無」。 將游標停留在我們沒有編輯權限的行事曆上，無法在 UI 中顯示任何字串。


- 我們已修正預設的文字放大包含了文字縮放比例的問題，因此不需要再呼叫 LayoutChanged。


- 我們已修正單次位址的寄件提醒未顯示的問題。


- 我們新增了一個登錄機碼，允許語音信箱表單在 Outlook 電腦版 UI 中顯示，因為 Exchange Online 中的 Unified Messaging 中止服務 (https://techcommunity.microsoft.com/t5/exchange-team-blog/retiring-unified-messaging-in-exchange-online/ba-p/608991)。 對於想要語音信箱表單顯示的使用者、企業和組織，必須設定下列登錄機碼： [HKEY_CURRENT_USER\SOFTWARE\Microsoft\Office\Outlook\Addins] "AllowVoicemailForm"=dword:00000001


- 我們已修正在啟動 Outlook 時，會導致有大量群組的使用者遇到沒有回應的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正與 SmartArt 節點停用 [變更圖形] 功能相關的問題。


### <a name="project"></a>Project

- 我們已修正如果資源名稱具有特殊字元 (例如分號)，在 Project Web App 中建立之約定可能無法在 Project 桌面用戶端中正確載入的問題。


- 我們已修正當停用專案選項「專案應該計算成本」時，然後時間階段性成本值可能尚未正確地為成本型資源設定基準的問題。


- 我們已修正具有查詢表格的專案層級企業自訂欄位未在 Project 桌面用戶端中顯示值的問題。


- 我們已修正將本機專案儲存至 Project Web App 會變更先前已儲存的基準問題。


### <a name="visio"></a>Visio

- This hyperlink navigation issue has now been fixed in the latest build. Users can continue to access hyperlinks seamlessly to navigate to the desired linked file located in their OneDrive for business, using CTRL + click on the shape with the hyperlink.


### <a name="word"></a>Word

- 我們已修正啟用自動儲存會導致最新的編輯暫時消失的問題。


- 我們修正了改善 Word 和 JAWS 中新註解窗格的整合，這是一種熱門的螢幕助讀軟體。


- 我們已修正使用與 lTagNil 不同的 CommentId 進行清除選取和醒目提示的問題。


- 我們已修正註解在共同作業期間變成唯讀的問題。


- 我們已修正在註解窗格中捲動的問題。


- 我們已修正卸載佇列會變得沒有回應的問題。


- 我們已修正當 Office 佈景主題設定為黑色時，在預覽列印中無法清楚顯示頁首/頁尾文字的問題。


- 我們已修正使用 Microsoft Word Paper 增益集時出現方塊的問題。


- 我們已修正預覽列印中的部分頁面為空白的問題。


### <a name="office-suite"></a>Office 套件


- 我們已修正在 Outlook 中使用從右至左書寫的語言撰寫郵件時，含有數字的超連結會中斷的問題。


- 我們已修正 en-gb、fr-ca 和 es-mx 現在會與各自的父版本相符的當地語系化問題。


- 我們已修正 OMEX 與 ExCatalog 之間無法再共用設定的問題，例如建立了新 webextension 檔案之後，Web 增益集設定會更新至 webextension.xml。 只有在以原始方法部署該增益集，或將新的解決方案參考比較關閉時，才能存取前一個。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2106-june-29"></a>版本 2106：6 月 29 日
*版本 2106 (組建 14131.20278)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正導致 ARM64 裝置上發生效能問題的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2106-june-25"></a>版本 2106：6 月 25 日
*版本 2106 (組建 14131.20250)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正導致某些使用者的翻譯選項遭到停用的問題。  遇到此錯誤的客戶在瀏覽至檔案 -> 選項 -> 語言時，會看見其翻譯選項已遭停用。 有鑑於此，他們可能無法變更其偏好的翻譯語言和其他翻譯相關設定。


- 我們已修正導致擁有多個共用行事曆且擁有共用行事曆增進選項的使用者遇到一些效能問題的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用者因為阻礙性的 PowerPoint 特定對話方塊，而無法將憑證輸入 Windows 安全性對話方塊以開啟檔案的問題。


### <a name="visio"></a>Visio

- 具有來賓存取的 SPO/ODB 連結現在可繼續運作。


### <a name="word"></a>Word

- 已修正在受密碼保護的 docx 檔案上保存引文的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2106-june-21"></a>版本 2106：6 月 21 日
*版本 2106 (組建 14131.20194)*
* 各種錯誤和效能修正。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **在干擾較少的情況下閱讀訊息：** 開啟沈浸式閱讀程式，以自訂文字間距、頁面色彩、欄寬和行聚焦，讓您更輕鬆地專注於訊息。

- **上次登入/可疑的登入：** Outlook 現在會告知您上次登入帳戶的時間及位置，並警示您是否偵測到任何可疑的登入活動


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2106-june-14"></a>版本 2106：6 月 14 日
*版本 2106 (組建 14131.20162)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="word"></a>Word

- **使用您的語音搜尋：** 點一下或按一下搜尋欄中的麥克風，以在 Word 中使用您的聲音來尋找命令、內容等等。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正針對部分使用者在 Excel 增益集清單中顯示的額外項目問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2106-june-07"></a>版本 2106：6 月 7 日
*版本 2106 (組建 14131.20012)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已從 Range.valueTypes 移除 "RichValue"。 [連結的資料類型] 現在會傳回 "Error"，以符合 "#VALUE!" 的值 由 Range.values 傳回。

- 修正了阻止名稱管理員開啟包含大量隱藏名稱之書籍的問題。


- 我們已修正填滿大量資料時，影響 VLOOKUP 和 INDEX/MATCH 效能的問題。


- 我們已修正在 RealTimeData 函數參照時，會導致動態陣列無法更新儲存格值的問題。


- 已修正 IME 的 OverType 模式未在字元上輸入，而將字元留在字串結尾的問題。


- 我們已修正使用凍結窗格時，與使用雙指捲動相關的問題。


- 我們已修正在大型印表機上列印時，記憶體不足的相關問題。


### <a name="outlook"></a>Outlook

- 我們已修正以下問題：在 [僅下載標題] 模式下執行時，使用者看到可行動的訊息在下載後不斷重新整理或回復為標題。


- 我們已修正使用者無法在「非商務」授權 Outlook 版本中跨資料夾移動項目的問題。


- 我們已修正在從存放區移除資料夾時，導致使用者遇到意外關閉的問題。


- 我們已修正在載入個人卡片時，導致某些使用者遇到意外關閉的問題。


- 我們已修正導致 Outlook 中的人員選擇器針對擁有永久授權的使用者向上展開，而不是向下展開的問題。


- 我們已修正導致無法向 Office Perpetual 2021 預覽使用者顯示意見回應選項的問題。


- 已修正導致使用者看到所有寄件備份複本出現在其寄件匣資料夾中的問題。


- 我們已修正導致自訂網域使用者在將連結貼到電子郵件時，看到權限警告訊息的問題。


- 我們已新增一個登錄機碼，以停用新會議室尋找工具體驗 (與 Outlook 網頁版相同的體驗)，並啟用具有建議的時間的傳統會議室尋找工具。

    登錄機碼：

    >HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
    > REG_DWORD “ShowLegacyRoomFinder”</br></br>
    > 0 (預設值) - 當使用者按一下 [會議室尋找工具] 按鈕以搜尋可用的會議室時，Outlook 會使用新會議室尋找工具 OWA 提供的體驗  </br>
    > 1 - Outlook 使用舊版會議室尋找工具 UI 來搜尋可用的會議室 </br>


- 我們已修正在其他版本 Windows 中使用大聲朗讀功能時，導致 Word 意外關閉的問題。


- 我們已修正在從存放區移除資料夾時，導致使用者遇到當機的問題。


- 我們已修正會導致某些使用者在載入個人卡片時遇到意外關閉的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正在唯讀模式中，會導致無法從演講者備忘稿窗格複製的問題。


- 我們已修正問題，以確保使用工具列的 [重試儲存] 按鈕儲存的檔案會新增至 [最近的清單]。


- 修正少數使用者無法使用 [重複使用投影片] 選項的問題。


### <a name="project"></a>Project

- 我們已修正手動排程工作上的指派可能會移至不正確日期的問題。


- 我們已修正資源資料庫沒有回應且無法開啟的問題。


- 我們已修正當您建立使用具有特定日期或時間參數之 ProjectDate */ProjectDur* 函數的自訂欄位公式時，產生錯誤的問題。


### <a name="word"></a>Word

- 已修正註解張貼後，暫時呈現空白的問題。


- 我們已修正即使在使用者選擇捨棄變更之後，還是顯示另存新檔錯誤訊息的問題。


- 我們已修正會使得影像無法在新式註解中張貼的問題。


- 我們已修正按下 ctrl + shift + @ 等按鍵組合時，不會產生預期的重音符號 (在此案例中為 'å') 的問題。


- 我們已修正與影像壓縮相關的問題。


- 我們已修正 [檢閱] 窗格可能會捲動或似乎捲動，但未與選取的註解一致的問題。


- 我們已修正將文件匯出為 PDF 時，某些註解未儲存的問題。


- 我們已修正在套用 [限制編輯] 時，於文件未受保護的區域中無法編輯新註解的問題。


- 我們已修正不需要的捲動動畫相關的問題。


- 已修正導致 [註解] 窗格意外關閉的問題。


- 我們已修正選取註解時，未強調顯示註解的問題。


- 我們已修正在新建立的註解以外之處按一下時，導致文件中選取範圍無法清除的問題。


- 我們已修正若檔案名稱包含 DBSC 字元時，無法將電子郵件附件複製到其他非 Word 應用程式的問題。


- 我們已修正在其他版本 Windows 中使用大聲朗讀功能時，導致 Word 意外關閉的問題。


- 修正拼字及文法檢查用畫布內容卡顯示圖示按鈕，但那些按鈕沒有工具提示的問題。


- 我們已修正導致 [編輯器] 窗格佈景主題與系統佈景主題不一致的問題。


- 已修正 [編輯器] 窗格無法開啟的問題。


- 已修正在 [編輯器] 中切換至 [拼字類別] 時，相似性波浪線無法消失的問題。


- 我們已修正 Word 有時會在文字周圍顯示不應該出現的框線的問題。


- 我們已修正當特殊字型旋轉 90 度時，特殊字型的字元間距增加問題。


- 我們已修正當執行巨集時，如果已套用編輯限制，會更新錯誤欄位的問題。


- 我們已修正多位使用者在共同撰寫時，有時會遺失註解回覆的問題。


- 我們已修正處理大型文件相關的效能問題。


- 我們已修正部分 Word 檔案因為書籤損毀而無法開啟的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正 CLP 功能先前導致了自動儲存至 SyncBacked 檔案 (由 OneDrive 同步檔案) 的問題。


- 我們已修正使用者無法編輯儲存於 OnPrem 伺服器中的檔案問題。


- 已修正開啟 SyncBacked 檔案時出現效能迴歸的問題。


- 我們已修正 OneDrive 在確實無合併衝突發生時，顯示合併錯誤訊息的問題。


- 我們已修正使用不同帳戶登入可能會導致關機的問題。


- 我們已修正 SVG 物件轉換成圖形時 Z 順序的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-june-04"></a>版本 2105：6 月 04 日
*版本 2105 (組建 14026.20264)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **資料類型偵測設定：** 在 Excel 中使用Power Query 從未結構化來源匯入資料時，設定資料類型偵測行為

### <a name="word"></a>Word

- **書寫樣式：** 書寫樣式精選評論是以使用者已選取的正式性等級為依據


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正部分使用者在 Excel 增益集清單中顯示額外項目的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-june-01"></a>版本 2105：6 月 1 日
*版本 2105 (組建 14026.20254)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **上次登入/可疑的登入：** Outlook 現在會告知您上次登入帳戶的時間及位置，並警示您是否偵測到任何可疑的登入活動

- **開啟共用行事曆改良功能：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。 開啟預覽，以更快速且更可靠地更新共用行事曆。<br />在[部落格文章](https://insider.office.com/en-us/blog/shared-calendars-improvements-in-outlook-for-windows)中查看詳細資料

- **將電子郵件傳送給大型 DL、外部使用者時，協助工具檢查程式會進行微調：** 我們新增了功能，以在撰寫電子郵件給大量對象、外部使用者等時，透過郵件提示自動收到協助工具違規的提示。這些設定放在輕鬆存取中<br />在[部落格文章](https://insider.office.com/en-us/blog/sending-accessible-emails-in-outlook-for-windows)中查看詳細資料

### <a name="visio"></a>Visio

- **AWS stencils and shapes:** We now have stencils with the latest AWS shapes to help you create diagrams. [Learn more](https://support.office.com/article/138206bf-d10f-4583-9f31-885ce706af49)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正與 Outlook 郵件或行事曆檢視互動時，可能會導致意外關閉的問題。




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-may-23"></a>版本 2105：5 月 23 日
*版本 2105 (組建 14026.20246)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **推出出席資料儀表板檢視**：您不再需要手動下載報告，Teams 現在可讓您按一下儀表板檢視即可檢視所有彙總資料

- **Security, compliance, and data protection capabilities for apps:** For Microsoft 365 Certified Teams apps, admins can view security, compliance, and data protection capabilities in a new tab on the app's detail page in the Teams Admin Center. This transparency gives Microsoft customers trust in the applications that run their organizations.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致「縮短會議時間」功能的部分指示透過螢幕閱讀程式技術無法使用的問題。


- 我們已修正會導致某些使用者在載入個人卡片時遇到意外關閉的問題。


- 我們已新增一個登錄機碼，以停用新會議室尋找工具體驗 (與 Outlook 網頁版相同的體驗)，並啟用具有建議的時間的傳統會議室尋找工具。
    - 登錄機碼：

        > HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
        > REG_DWORD “ShowLegacyRoomFinder”</br></br>
        > 0 (預設值) - 當使用者按一下 [會議室尋找工具] 按鈕以搜尋可用的會議室時，Outlook 會使用新會議室尋找工具 OWA 提供的體驗  </br>
        > 1 - Outlook 使用舊版會議室尋找工具 UI 來搜尋可用的會議室 </br>


### <a name="project"></a>Project

- 修正手動排程工作上的指派可能會移至不正確日期的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-may-19"></a>版本 2105：5 月 19 日
*版本 2105 (組建 14026.20202)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **Teams 網路研討會與 Dynamics 365 Marketing 整合，以啟用潛在客戶培養：** 利用這項功能，網路研討會召集人可以運用 D365 Marketing 促進與報名者在活動後的參與。 出席者參與資料會與 D365 Marketin 組織同步，並啟用自動化的使用者旅程

- **Intelligent speakers:** Intelligent speakers are intelligent peripherals for Microsoft Teams Rooms on Windows. They will bring speaker attributed transcription for participants in the meeting room, enabling attendees to spend less time note-taking and easily follow along who said what in the room.

- **讓 Teams 使用者能夠透過 Teams 用戶端購買 Teams 應用程式：** Teams 使用者現在可以從 Teams Store 購買 Teams 應用程式訂閱。

- **使用 Teams 範本建立團隊：** 使用 Teams 中的範本，使用者可在建立新的團隊時從各種可自訂的範本中選擇，協助他們快速開始使用。 IT 系統管理員也可以為其組織建立新的自訂範本，讓他們能標準化團隊結構、預先安裝相關應用程式，以及擴大最佳做法。 IT 系統管理員可以選擇要在 Teams 系統管理中心向使用者顯示哪些團隊範本，也可以將 URL 新增到團隊範本中的網站索引標籤，以預先設定網站頁面。

- **在 Teams 中使用 PowerPoint Live 的雷射筆和筆跡標註：** 我們引進了虛擬雷射筆和標註，讓簡報者可以有效分享內容，並吸引觀眾注意 PowerPoint 投影片組的某些部分。 就像在會議室使用實體雷射筆一樣，PowerPoint Live 可讓您有效地指向不同位置，讓觀眾可以輕鬆地跟上投影片上的內容。

- **Power Automate 流程建議與 1P 團隊範本：** 適用於從 1P 團隊範本所建立之團隊的 Surface Power Automate 流程範本


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正導致無法向 Office Perpetual 2021 預覽使用者顯示意見回應選項的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-may-12"></a>版本 2105：5 月 12 日
*版本 2105 (組建 14026.20164)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **在桌面 (或) 瀏覽器 (或) Teams 中預設開啟檔案的使用者喜好設定：** 使用者可以在開啟 Teams 中共用的 Office (Word、Excel 和 Power Point) 檔案時，將預設喜好設定設定為瀏覽器、桌面或 Teams。如果已安裝並啟用最新的 Office 用戶端，就可以選取桌面設定

- **Teams 會議中的報告者與並排模式：** 現在您可以出現在內容旁邊，以提供更吸引人的簡報和消費體驗

- **Teams 網路研討會功能正式發行：** 排程，並使用您用於會議的相同 Teams 應用程式，提供 1，000 人網路研討會！ 網路研討會功能支援註冊頁面建立、報名者的電子郵件確認、出席者影片和音訊的主機管理、出席者報告，以及投票、聊天和回應等互動式功能。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="word"></a>Word

- 修正拼字及文法檢查用畫布內容卡顯示圖示按鈕，但那些按鈕沒有工具提示的問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2105-may-07"></a>版本 2105：5 月 7 日
*版本 2105 (組建 14026.20138)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **Teams 會議版面配置簡介：** 現在可以覆蓋在內容之上，以擁有更沈浸式的簡報和消費體驗

- **停用特定出席者的相機：** 會議召集人和簡報者可以在 Teams 會議中停用特定出席者的相機，以確保他們不會在會議中分享視訊。

- **停用所有出席者的相機：** 會議召集人和簡報者可以在 Teams 會議中停用所有出席者的相機，以確保他們不會在會議中分享視訊。

- **匿名使用者可以簡報：** 在主持 Teams 即時活動時，我們新增了匿名使用者加入即時活動的能力，因此他們也可以在活動期間進行簡報。

- **以程式化方式管理 Teams 中的標記 - Microsoft Teams 標記 API 現在為公開預覽：** 這組 API 可用來以程式化方式在小組中指派使用者標記，讓標記建立與維護更快速且更容易。  Teams 中的標記可讓使用者快速連絡一組人員，而不需要 @提及或輸入所有人。 如需 Teams 中標記的相關資訊，請參閱在 Teams 中使用標記。 使用這些新 API，開發人員可以在小組中 nowCreate 標記，並在小組中指派 usersGet 標記清單及更新 tagsDelete 標記

- **從 PowerPoint 到 Teams 進行簡報：** PowerPoint 應用程式直接透過 PowerPoint Live 將您的投影片展示到 Teams 會議。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="word"></a>Word

- 修正編輯器窗格無法開啟的問題。


### <a name="office-suite"></a>Office 套件

- RelNotesNotNeeded



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-may-03"></a>版本 2105：5 月 3 日
*版本 2105 (組建 14026.20052)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **在會議中同時聚焦多個使用者：** 召集人和簡報者現在可以在會議期間同時聚焦多個參與者。 會議階段會向會議中的每個人顯示這些焦點參與者及其影片或虛擬人偶。

- **從 PowerPoint 到 Teams 進行展示：** PowerPoint 應用程式直接透過 PowerPoint Live 將您的幻燈片展示到 Teams 會議。

- **New manage tag experience and other enhancements:** Tags in Teams let users quickly reach a group of people without having to @mention or type out everyone.The manage tags experience is now a Tab. Tags also now have a description field so that you can add more details to a tag. The new Tags Tab will be the landing page for tag notifications and search for tags, which is also coming soon.

- **Intelligent Speakers:** Intelligent speakers are intelligent peripherals for Microsoft Teams Rooms on Windows. They will bring speaker attributed transcription for participants in the meeting room, enabling attendees to spend less time note-taking and easily follow along who said what in the room.

- **Changing default to native notification from teams purple for new users:** Native Notifications provide a host of benefits like support for action center, accessibility, support for focus assist mode e.t.c.Currently the default notification style for a new user in Microsoft teams is Teams Purple. With this change the default for new user will change to Native Notification.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們修正了在 64 位元 Windows 上使用 32 位元 Office 時導致 Excel 意外關閉的問題。


- 我們已修正在 [註解] 窗格中的註解間移動時，會導致 Excel 意外關閉的問題。


- 已修正 Excel 某些自動化增益集無法載入的問題。


- 我們已修正導致 [朗讀程式] 錯誤讀取 [版面設定] 對話方塊中 [頁首/頁尾] 索引標籤上兩個按鈕的内容之問題。


- 我們已修正導致某些在其他 Office 應用程式中連結的活頁簿在執行更新連結時關閉而不儲存變更的問題。


- 已修正針對某些使用者流量分析工具箱增益集無法運作的問題。


- 我們已修正某些檔案偶爾無法以受保護的檢視開啟的問題


- 我們已修正在使用增益集時，會導致某些語言的日期格式顯示不正確的問題。


- 我們已修正造成部分使用者狀態列無法顯示 [準備就緒] 狀態的問題。


- 我們已進行變更，讓名稱管理員可以在具有大量隱藏名稱的書籍上開啟。


- We fixed an issue to support backward compatibility with older versions of Excel. The issue may cause a file that is saved in a more recent version of Excel failed to load properly in older versions of Excel due to  functions such as IFERROR and XLOOKUP added to Excel since Office 2007.


- 我們已修正在某些情況下，使用選擇性貼上搭配格式時可能會導致 Excel 意外關閉的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致 Outlook 覆寫 OWA 中已設定的焦點收件匣喜好設定問題。


- 我們已修正會導致漫遊設定的使用者遇到停止回應的問題。


- 我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，會造成名稱解析停用的問題。


- 我們已修正導致某些使用行事曆共用改進功能的使用者在功能窗格中與他們的行事曆互動時發生的問題。


- 我們已修正長時間使用高對比模式會導致 Outlook 意外關閉的問題。


- 我們已修正在 Outlook 中以從右至左語言撰寫郵件時，包括數字的超連結會停用的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正與連結圖片相關的問題。


### <a name="project"></a>Project

- 我們已修正透過規劃精靈完成的變更不一定會由變更事件擷取的問題。


- 我們已修正使用者無法從資源資料庫移除專案的問題。


### <a name="visio"></a>Visio

- 我們已修正導致 Visio 和新的組建一起意外關閉的問題。


### <a name="word"></a>Word

- 我們已修正在移除超連結後，文字格式仍會保留的問題。


- 我們已修正使用從右至左書寫的語言時，在註解中預留位置文字會被裁剪的問題。


- 我們已修正在依人員篩選後，不會顯示註解的問題。


- 我們已修正 Word 無法使用 Access 資料庫執行合併列印的問題。


- 我們已修正摺疊文件中邊緣的功能，會導致包含可供使用的多個欄位的問題。


- 我們已修正當文件中有註解時，表格儲存格中某些字元無法正確顯示的問題。


- 我們已修正在啟用 AIP 增益集的情況下儲存文件時，會發生檔案格式變更的問題。


- 我們已修正在編輯欄位時 Word 會變得沒有回應的問題。


- 我們已修正將檔案上傳到 SharePoint Online 之後，敏感度標籤會從 Word 中的檔案消失的問題。


- 我們已修正使用命令 (而不是 CTRL+S 鍵盤快速鍵) 來儲存文件時，系統不會提示使用者儲存文件的問題。


- 修正使用者登出或將電腦重新開機，導致 Word 在關機時意外關閉的問題。


- 我們已修正在移除超連結後，文字格式設定仍會保留的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正將註解新增至文件時，會導致 [聽寫] 按鈕對齊不當的問題。


- 已修正剖析 Emoji 處理的字串時，當讀取超出陣列範圍時，導致應用程式意外關閉的問題


- 我們已修正某些可縮放向量圖形 (SVG) 無法正確轉譯的問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2104-april-28"></a>版本 2104：4 月 28 日
*版本 2104 (組建 13929.20296)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **擴大的表情圖示選擇器：** 擴大的表情圖示更新可在 Teams 中提供使用者更多樂趣和表達力。 它也推出更廣泛的多樣性和呈現方式。 表情圖示集已由 85 個擴充到超過 800 個表情圖示，具有類別選取器、膚色選取器和簡短代碼選擇器。

- **Microsoft Teams：修訂會議內共用體驗：** Microsoft Teams 中會議內共用功能的使用者介面已重新設計，以協助簡報者更快速且輕鬆地找到所需的內容。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正某些 Excel 自動化增益集無法載入的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致漫遊設定的使用者遇到停滯的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正與連結圖片相關的問題。


### <a name="project"></a>Project

- 修正使用者無法從資源資料庫移除專案的問題。


### <a name="word"></a>Word

- 我們對編輯 OLE 物件進行了變更。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2104-april-26"></a>版本 2104：4 月 26 日
*版本 2104 (組建 13929.20254)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **開啟共用行事曆改良功能：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。 開啟預覽，以更快速且更可靠地更新共用行事曆。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正某些檔案偶爾無法以受保護的檢視開啟的問題


### <a name="outlook"></a>Outlook

- 我們已修正會導致 Outlook 覆寫 OWA 中已設定的焦點收件匣喜好設定問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2104-april-19"></a>版本 2104：4 月 19 日
*版本 2104 (組建 13929.20216)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Import data from dynamic arrays:** You can now import, shape and refresh data from dynamic arrays in the current workbook. [Learn more](https://support.office.com/article/205c6b06-03ba-4151-89a1-87a7eb36e531)

### <a name="outlook"></a>Outlook

- **改良的行事曆搜尋：** 已改善日曆搜尋功能，其中最大的改良處是更輕鬆地在搜尋結果中尋找下一個系料數列。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此變更可修正在某些情況下，執行 SQL Server 傳遞查詢時，可能會導致錯誤訊息指出「無效的 Cursor 狀態」的問題。


- 我們已修正當外部應用程式要求協助工具介面時，它會防止我們關機，直到它們釋出其參考為止的問題。


### <a name="excel"></a>Excel

- 我們已修正會導致無法以公式形式貼上到受保護工作表的問題。


- 我們已修正當檔案儲存為 PDF 文件時，使用 [超連結] 函數所建立的超連結無法運作的問題。


- 我們已修正在公式中使用參照空白範圍加入隱含運算子 (@) 符號，並可能提供不正確結果的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致某些使用者在同步處理資料夾階層變更時遇到 Outlook 意外關閉的問題。


- 我們已修正會導致使用者在新增行事曆時，錯誤地看到「這可能需要一些時間」訊息的問題。


- 我們已修正會導致代理人在新增的行事曆上所建立的會議中顯示為召集人的問題。  處於此狀態的會議不會出現在主體的行事曆上。


- 我們已修正導致使用者在搜尋時遇到意外關閉的問題。


- 我們已修復搜尋相關的意外關閉問題。


- 我們已修正會導致使用者看到簽名意外消失的問題。


- 我們已修正可能造成使用者看到正在撰寫的郵件失去 UI 焦點的問題。


- 我們已修正會導致 Outlook 覆寫 OWA 中已設定的焦點收件匣喜好設定問題。


- 我們已修正會導致雲端設定功能的使用者在新裝置上設定 Outlook 之後，會看到自訂設定遭到預設設定覆寫的問題。


- 我們已修正會導致部分使用者無法存取與次要郵件帳戶相關聯的簽章問題。


- 我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，造成名稱解析失敗的問題。


- 我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，造成名稱解析失敗的問題。


### <a name="project"></a>Project

- 已修正如果日期格式為 W4/4，日期選擇器可能會顯示錯誤的日期和年份的問題。


### <a name="visio"></a>Visio

- 修正 Visio 在關閉期間可能會停止運作的問題。


- 修正「搜尋圖形」功能以顯示所有結果



### <a name="word"></a>Word

- In this bug, specific policies weren't being honored by Office (a group of templates were being shown on the Home Page when they should have been disabled). With this fix, the policies are being honored.


- 共同撰寫文件時，若註解順序變更，不會清除作用中草稿。


- 修正新式註解中的錯誤，其中標點符號和數字的顯示方式對於某些國際語言是錯誤的。


- 修正 'B' 和 ')' 的組合會自動轉變成戴著墨鏡的表情圖示，且現在仍保留為個別字元的問題


- 更新在本機儲存的檔案自動儲存圖說文字上的文字。


- 我們已修正在共同撰寫期間的註解問題。


- 我們已修正與註解圖示相關的問題。


- 我們已修正貼上文字中的樣式與複製和貼上的樣式可能不同的問題。


- 最佳化提供文字預測的條件。


- 我們已修正與超連結相關的問題。


- 在閱讀模式中使用深色模式主題時，有些選取的文字無法顯示。


- 我們已修正 [自動儲存] 中的問題。


- 我們在 Application.OnTime 中修正了可能無法正確觸發的問題。


### <a name="office-suite"></a>Office 套件

- 已修正與文字反覆項目相關的效能問題。


- 已修正在 Office 中支援 GDI+ LineJoinMiterClipped 的問題。


- 此發行版本改善當關鍵字位於文件的第一行時，跨行敏感內容的處理。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-april-13"></a>版本 2103：4 月 13 日
*版本 2103 (組建 13901.20400)*

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **動態檢視** 動態檢視自動最佳化 Teams 會議中的共用內容和影片參與者。 新控制項可讓您個人化檢視以滿足您的喜好和需要，例如能够並排顯示共用內容和特定參與者。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2103-april-10"></a>版本 2103：4 月 10 日
*版本 2103 (組建 13901.20400)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正繪製影像時，Word 中的潛在資源爭用問題。

### <a name="outlook"></a>Outlook

- 我們已修正會導致使用者在新增行事曆時，錯誤地看到「這可能需要一些時間」訊息的問題。

- 我們已修正會導致代理人在新增的行事曆上所建立的會議中顯示為召集人的問題。  處於此狀態的會議不會出現在主體的行事曆上。

- 修正繪製影像時，Word 中的潛在資源爭用問題。

### <a name="powerpoint"></a>PowerPoint

- 修正繪製影像時，Word 中的潛在資源爭用問題。

### <a name="word"></a>Word

- 修正繪製影像時，Word 中的潛在資源爭用問題。

- 修正在預覽列印時沒有回應的問題。

- 更新在本機儲存的檔案自動儲存圖說文字上的文字。

### <a name="office-suite"></a>Office 套件

- 修正離線開啟 SyncBacked 檔案，然後於儲存檔案之前，在應用程式中重新命名檔案時重新命名失敗的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-april-02"></a>版本 2103：4 月 2 日
*版本 2103 (組建 13901.20336)*
* 各種錯誤和效能修正。

## <a name="version-2103-april-01"></a>版本 2103：4 月 1 日
*版本 2103 (組建 13901.20148)*

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **日期/時間格式** 利用此更新，Teams 中的日期/時間格式將會與 Mac 和 Windows 作業系統地區設定相符。 之前，Teams 只會以與應用程式語言對應的格式顯示日期/時間。 務必注意，無論作業系統的行事曆設定為何，都只支援西曆。 

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2103-march-30"></a>版本 2103：3 月 30 日
*版本 2103 (組建 13901.20312)*
* 各種錯誤和效能修正。

## <a name="version-2103-march-28"></a>版本 2103：3 月 28 日
*版本 2103 (組建 13901.20306)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致某些使用者在同步處理資料夾階層變更時遇到 Outlook 意外關閉的問題。


- 我們已修正會導致某些使用者在瀏覽窗格中看到主要和次要行事曆切換位置的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-march-22"></a>版本 2103：3 月 22 日
*版本 2103 (組建 13901.20230)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致使用者看到較預期更多的簽章的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-march-15"></a>版本 2103：3 月 15 日
*版本 2103 (組建 13901.20170)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="project"></a>Project

- 修正 Visio 在關閉期間可能會停止運作的問題。


### <a name="visio"></a>Visio

- 修正 Visio 在關閉期間可能會停止運作的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
## <a name="version-2103-march-11"></a>版本 2103：3 月 11 日
*版本 2103 (組建 13901.20148)*

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft Purview 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。

### <a name="outlook"></a>Outlook

- **新的會議室和工作區預約體驗：** 會議室預約體驗已更新，透過它我們新增了功能，以讓您也能夠排程個別工作區

### <a name="powerpoint"></a>PowerPoint

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft Purview 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。

### <a name="teams"></a>Teams

- **不在辦公室狀態** 設定訊息，讓其他人知道您不在工作狀態或是休假中，因此當他們傳送聊天訊息給您時，您無法回覆。 您的不在辦公室狀態也會與您 Outlook 日曆中的自動回覆同步。

### <a name="visio"></a>Visio

- **Office icons have a new look:** The product icons have been redesigned to reflect simple, powerful, and intelligent Office experiences. [Learn more](https://support.office.com/article/a6cdf19a-b2bd-4be1-9515-d74a37aa59bf)

### <a name="word"></a>Word

- **Word 文件的深色模式：** 深色模式有助於減輕眼睛疲勞，並可在處理文件時適應對光線的敏感度。

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft Purview 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。


- 我們已修正當外部應用程式要求協助工具介面時，它會防止我們關機，直到它們釋出其參考為止的問題。


### <a name="excel"></a>Excel

- 我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。


- 已修正因為無法擷取影像，所以 Excel 有時候會在嘗試顯示「資料類型」卡的時候意外關閉的問題。


- 已修正在日文字型中使用乘法或除號時，字型會意外改變的問題。 我們現在會繼續使用相同的字型 (如果支援該字元)。


- 我們已修正會導致使用者無法將 Excel 活頁簿匯出至 PDF 的問題。


- 我們已修正使用 [貼上連結圖片] 選項時，會導致影像小於預期的問題。


- 我們已修正在共同撰寫的同時複製工作表時，某些格式可能會遺失的問題。


- 我們已修正開啟活頁簿時，會意外顯示某些記事的問題。


- 我們已修正在儲存為 .xls 或 .xlt 格式時，會導致某些樞紐分析表格式損壞活頁簿的問題。


### <a name="outlook"></a>Outlook

- 我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。


- 我們已修正會導致使用者在建立新群組後看到重複的行事曆群組的問題。


- 我們已修正會導致共用行事曆改良功能的使用者無法將行事曆的色彩設定為黃色或褐色的問題。


- 我們已修正會導致使用者在 Outlook 重新啟動之前，在功能窗格中看不到新增的行事曆顯示的問題。


- 我們已修正匯出至 CSV 時，會導致非 ASCII 字元匯出錯誤的問題。


- 我們已修正會導致部分使用者無法存取與次要郵件帳戶相關聯的簽章的問題。


- 我們已修正會導致雲端設定功能的使用者在新裝置上設定 Outlook 之後，會看到自訂設定遭到預設設定覆寫的問題。


- 我們已修正會導致使用者看到包含 Unicode 內容的簽章損毀的問題。


- 我們已修正會導致內嵌翻譯的使用者無法提交意見反應的問題。


- 我們已修正在移除 DRM 保護時會導致使用者看到附件重複的問題。


- 我們已修正導致使用者在撰寫郵件時無法使用 [檢查名稱] 查詢連絡人群組的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。


- 我們已修正在 PowerPoint 投影片放映模式中，折線圖中的箭號未如預期顯示的問題。


- 已修正迴圈動畫和音訊書籤的問題。


### <a name="project"></a>Project

- 修正 Visio 在關閉期間可能會停止運作的問題。


- 我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。


- 已修正 100% 完成的工作可能會回復為 99% 完成的問題。


- 已修正當您執行 JAWS 並且移至任務資訊對話方塊時 Project 意外關閉的問題。


- 修正此問題：如果指標欄不在第一欄位置，當您剪下摘要任務時，系統不會警告您也會移除子任務。


- 修正以下問題：如果使用者在時程表上選取 [將您本身加入至任務] 功能，則建立的工作指派可能不會使用正確的資源可用性單位。


- 已修正從 Project Web App 將專案存到本機檔案時，可能會錯誤建立任務分割的問題。 如果使用非標準工作時間的任務行事曆，就會發生此情況。


### <a name="publisher"></a>Publisher

- 我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。


### <a name="visio"></a>Visio

- 修正 Visio 在關閉期間可能會停止運作的問題。


- 我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。


### <a name="word"></a>Word

- 我們已修正開啟受 Microsoft Purview 資訊保護標籤保護的檔案時，如果使用者未登錄可存取 MIP 受保護標籤的身分識別，則可能會無限期擱置的問題。 使用者必須取消開啟以顯示登錄提示，且開啟作業只會在這之後才成功。 允許在開啟/下載期間顯示登錄提示，以修正此問題。


- 我們已修正移除外部磁碟機時，可能會導致應用程式意外關閉的問題。


- 我們已修正在新的 Word 註解中使用 [聽寫] 時的問題，[註解] 卡片中的 [聽寫] 按鈕現在可以正確開啟和關閉。


- 共同撰寫文件時，若註解順序變更，不會清除作用中草稿。


- 修正當使用者在文件中進行聽寫時，文字之間沒有插入空格的問題。


- 修正在呈現捲動包含捲動或縮放動畫的圖層相關管線中的問題。


- 修正對具有 3D 效果的圖示和 SVG 圖形套用色彩的問題。


- 我們已修正自動儲存的問題。


- 我們已修正註腳中的問題。


- 我們已修正在 RTL 中張貼多行註解時，會導致第 2 行和開始行對齊左邊而非右邊的問題。


- 我們已修正多個註解的對齊問題。


- 我們已修正 [大聲朗讀] 工作窗格鍵盤快速鍵的問題。


- 我們已修正可能會略過段落的朗讀程式問題。


- 我們已修正拼字檢查會在兩個不同的拼字校正內容功能表之間切換的問題。


- 我們已修正 RTF 內容控制項的問題。


- 我們已修正在隱藏段落結尾輸入可能會導致應用程式懸置的問題。


- 我們已修正欄位可能有重疊文字的問題。


- 我們已修正與書籤相關的問題。


- 我們已修正解決共同撰寫時衝突的問題。


### <a name="office-suite"></a>Office 套件

- 系統現在會按照群組原則設定適當篩選出 OneDrive 位置。


- 已修正在包含數學方程式的文字內使用朗讀程式時可能發生的問題。


- 修正與支援在工作階段 0 中執行的 Office 應用程式相關的可靠性問題。


- 修正與支援在工作階段 0 中執行的 Office 應用程式相關的可靠性問題。


- 修正載入 EMF 影像時可能會發生的無回應問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-march-03"></a>版本 2102：3 月 3 日
*版本 2102 (組建 13801.20274)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="word"></a>Word

- 修正佈景主題資訊套用到圖示和 SVG 圖形的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-march-01"></a>版本 2102：3 月 1 日
*版本 2102 (組建 13801.20266)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **共用至 Teams：** 將 Outlook 的郵件與 Teams 中的某個人員或頻道共用。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致使用者在建立新群組後看到重複的行事曆群組的問題。


- 我們已修正會導致共用行事曆改良功能的使用者無法將行事曆的色彩設定為黃色或褐色的問題。


- 我們已修正會導致某些使用者在關閉訊息視窗時遇到應用程式關閉的問題。


- 我們已修正會導致使用者看到包含 Unicode 內容的簽章損毀的問題。


- 我們已修正會導致內嵌翻譯的使用者無法提交意見反應的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-february-21"></a>版本 2102：2 月 21 日
*版本 2102 (組建 13801.20182)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **使用語音草擬郵件：** 使用新的聽寫工具列、語音命令、自動標點符號等功能來撰寫郵件。

### <a name="word"></a>Word

- **使用語音草擬文件：** 使用新的聽寫工具列、語音命令、自動標點符號等功能來草擬文件。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正使用 [貼上連結圖片] 選項時，會導致影像小於預期的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-february-16"></a>版本 2102：2 月 16 日
*版本 2102 (組建 13801.20160)*
* 各種錯誤和效能修正。

## <a name="version-2102-february-15"></a>版本 2102：2 月 15 日
*版本 2102 (組建 13801.20158)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **聽寫提供更多語言：** 聽寫現在支援 7 個新的語言：印地文、俄文、波蘭文、葡萄牙文 (葡萄牙)、韓文、泰文、中文 (台灣)

### <a name="word"></a>Word

- **聽寫提供更多語言：** 聽寫現在支援 7 個新的語言：印地文、俄文、波蘭文、葡萄牙文 (葡萄牙)、韓文、泰文、中文 (台灣)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正會導致使用者無法將 Excel 活頁簿匯出至 PDF 的問題。


### <a name="word"></a>Word

- 我們已修正共同撰寫時衝突的問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)


## <a name="version-2102-february-11"></a>版本 2102：2 月 11 日
*版本 2102 (組建 13801.20158)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams

- **2x2 video on Edge and Chrome browsers on Windows and Mac** Users can see up to 4 participants' video in Teams meetings in Edge and Chrome browsers on Windows and Mac. [Learn more](https://support.microsoft.com/office/using-video-in-microsoft-teams-3647fc29-7b92-4c26-8c2d-8a596904cdae#bkmk_videolayout)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

## <a name="version-2102-february-08"></a>版本 2102：2 月 8 日
*版本 2102 (組建 13801.20084)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **Microsoft 搜尋支援的撰寫 (收件者/副本/密件副本) 建議**：將人員新增至收件者/副本行，現在會由 Microsoft 搜尋提供支援。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 您現在會在 Access 中看到已選取的索引標籤。


### <a name="excel"></a>Excel

- 修正重新開啟檔案時，使用非連續儲存格範圍的特定圖表無法載入的問題。


- 修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題。


- 我們已修正選取圖表的資料數列之後，Excel 會停止回應的問題。


- 我們已修正當您在 [定義名稱] 對話方塊中新增名稱時，Excel 會意外結束的問題。


- 已修正在裁剪作業期間，保持圖片長寬比的相關問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致郵件在使用者取消選取該選項之後，以數位簽章方式傳送的問題。


- 我們已修正會導致加密圖示無法對使用 [僅加密] 選項傳送的電子郵件顯示的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正與顯示有色彩的表情符號相關的問題。


- 修正在裁剪作業期間，與保持圖片的長寬比相關的問題。


### <a name="visio"></a>Visio

- 現已修正從 CAD 樣板呈現圖形的相關問題。 使用者將在最新組建中看到問題已解決。


### <a name="word"></a>Word

- 這會修正在失去網際網路連線一段時間後，會防止即時輸入和目前狀態還原的問題。


- 當使用者在註解中選取文字，Word 現在會取消選取在其他註解中選取的文字。


- Word 現在可讓您將註解文字複製到 Excel。


- 我們已修正執行 VBA 巨集 ExportAsFixedFormat2 失敗，出現說明「簡報 (未知的成員) 不合法值」錯誤的問題。


- 已修正在裁剪作業期間，保持圖片長寬比的相關問題。


- 我們已修正註解可能會因連結而被截斷的問題。


- 我們已修正儲存至 SharePoint Online 的問題


- 我們已修正將 Word 文件匯出為 PDF 的問題。


- 我們已修正自動回復的問題。

- 我們已修正當與受 DRM 保護的檔案共同撰寫會發生的問題


### <a name="office-suite"></a>Office 套件

- 修正在 PowerPoint 中以影像形式插入項目符號時，會導致項目符號消失的錯誤。 此修正可讓影像更可靠地呈現。

- 已修正 Office 在某些情況下在應該呈現某個已登入帳戶的敏感度標籤時，卻呈現不同已登入帳戶的敏感度標籤的問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2101-february-03"></a>版本 2101: 2 月 03 日
*版本 2101 (組建 13628.20330)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正在 OWA 中顯示正確預設簽名的問題。


- 我們已修正會導致加密圖示無法對使用 [僅加密] 選項傳送的電子郵件顯示的問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2101-february-02"></a>版本 2101：2 月 2 日
*版本 2101 (組建 13628.20320)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致雲端設定使用者在更新設定時遇到停止回應的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-january-25"></a>版本 2101：1 月 25 日
*版本 2101 (組建 13628.20274)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments. [Learn more](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments. [Learn more](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a>PowerPoint

- **Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments. [Learn more](/microsoft-365/compliance/sensitivity-labels).


### <a name="word"></a>Word

- **Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments. [Learn more](/microsoft-365/compliance/sensitivity-labels)


### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們修正了導致在其設定檔中具有大型階層的共用或委派信箱的使用者遇到停止回應的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)



## <a name="version-2101-january-18"></a>版本 2101：1 月 18 日
*版本 2101 (組建 13628.20158)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="project"></a>Project

- 修正在 [團隊規劃] 檢視中工作沒有顯示邊框的問題。


- 修正在 [團隊規劃] 檢視中拖放工作不起作用的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-january-13"></a>版本 2101：1 月 13 日
*版本 2101 (組建 13628.20118)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
### <a name="feature-updates"></a>功能更新
### <a name="teams"></a>Teams
- **更多主題：** 桌面和網頁用戶端可使用新的主題。

- **PPT 共用：** Teams 中的簡報者檢視畫面：當您從 Teams 共用區選取 PowerPoint 檔案之後，系統會自動開啟 [簡報者檢視畫面]。 您可以查看目前的投影片、投影片附註，以及投影片組中所有投影片的縮圖條，以輕鬆進行臨時的投影片瀏覽。 此檢視完全位於幕後，且由掌控螢幕的簡報者所專有。 您的觀眾只能看見您目前的投影片 (以大型紅色方塊醒目提示)，或他們所選擇要瀏覽的投影片 (如果您未鎖定觀眾瀏覽版面)。 

- **在 Mac 上共用桌面或視窗時包含電腦音效** 當您從 Mac 版 Teams 共用桌面或視窗時，現在可以包含電腦的聲音，讓已加入會議的人可以聽到從您的電腦播放的音訊。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)
<br/>

## <a name="version-2101-january-09"></a>版本 2101：1 月 9 日
*版本 2101 (組建 13628.20118)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **單鍵寫作建議：** 只要按一下，就能套用寫作建議。 編輯器會校正拼字和文法，並提供潤飾寫作的建議。 [深入了解](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br />在[部落格文章](https://insider.office.com/en-us/blog/microsoft-editor-gets-an-upgrade)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 異常關閉的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-january-07"></a>版本 2101：1 月 7 日
*版本 2101 (組建 13628.20030)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once. [Learn more](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- **Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click. [Learn more](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正以下問題：Excel 錯誤地顯示檔案新版本可用的訊息列，並強制使用者將變更儲存到活頁簿的副本中或捨棄變更。


- 修正了 Selection.Parent.Copy 通話后切換分隔符號的問題。


- 對將格式設定樣式套用至樞紐分析表時的效能進行改善。


- 修正在開啟含有 Excel 4.0 巨集的 Excel 增益集檔案時，Excel 可能會停用巨集而不提示的問題。


- 更新以便在從 Excel 複製圖表並貼上到 Word 中時保留小數點和千位分隔符號設定


- 修正了當開啟具有無效檔案内容 (建立時間、修改時間等) 的 UNC 檔案時，Excel 會意外關閉的問題


- 修正在使用 STOCKHISTORY 函數時，可能會導致「資源不足」警示的問題。


- 將 FuzzyClustering DLL 新增至 PQ DLL 清單。


- 此變更可解決與變更 SVG 影像的外框顏色相關的問題。


- 我們已修正 PowerPoint 中內嵌的 Excel 範圍預覽會顯示不正確大小的問題。


### <a name="onenote"></a>OneNote

- 此變更可解決影響 OneNote 的呈現問題。


### <a name="outlook"></a>Outlook

- 我們已修正以下問題：導致使用者無法指定在從 Word 啟動合併列印時允許存取時長，從而導致他們取得過多提示的問題。


- 此變更使得 Outlook 可以利用能夠向使用者隱藏 Exchange Online 封存信箱顯示的 Exchange Server 設定。


- 我們已修正會導致 Outlook 對基於兌換增益集的使用者意外關閉的問題。


- 我們已修正造成使用者無法選取多個類別進行搜尋的問題。


- 我們已修正當活動是從另一個約會複製而來時，造成部分行事曆項目的開始時間發生意外變更的問題。


- 解決了當純文字 S/MIME 郵件在傳送時發生亂碼的問題。


### <a name="powerpoint"></a>PowerPoint

- 此變更可解決合併圖案處理文字時的問題。


- 此變更可解決與變更 SVG 影像的外框顏色相關的問題。


- 此變更解决了在投影片放映中迴圈播放背景影片的問題。


- 我們已修正在 QAT 中新增的字型大小命令在更新時自動完成到最近定義的字型大小的問題。


### <a name="project"></a>Project

- 修正資源的最大可用量不一定會反映對最大可用量的最新更新的問題。


### <a name="visio"></a>Visio

- 此問題是由於最近的迴歸而造成。 我們已解決此問題。 [另存成網頁] 對話方塊現在會根據使用者的輸入正確填入欄位，且使用者可以將其檔案順暢地儲存為網頁。


- This issue has been fixed. You can now embed Visio files as objects in other Office applications like PowerPoint and Word and seamlessly access them from within these applications.


### <a name="word"></a>Word

- 修正使用自訂雜湊設定的電腦，在進入使用 sha512 以外雜湊設定的共同作業工作階段時會發生問題的問題。


- 此變更可解決與變更 SVG 影像的外框顏色相關的問題。


- 修正使用 @提及編輯註解文章時的問題。


- 修正問題以讓新式註解更穩定。


- 我們已修正有關删除標記為不可編輯的內容控制項中的新式註解的問題。


- 修正在註解卡片底部輸入文字時的動畫。


- 修正註解卡片上的回覆方塊不在畫面上的問題。


- 修正頁面頂端顯示的註解卡片問題。


- 修正註解中文字可能不在畫面上的錯誤。


- 修正註解窗格中巢狀捲軸的問題。


- 建立新的 Word 執行個體時註解草稿會消失。


- 我們已修正將文件儲存為含有隱藏文字的 PDF 時，Word 停滯的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-january-04"></a>版本 2012：1 月 4 日
*版本 2012 (組建 13530.20316)*
* 各種錯誤和效能修正。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **強制標籤：** 使用者若已設定強制標籤原則，其系統管理員將需要標記其文件和電子郵件。

### <a name="powerpoint"></a>PowerPoint

- **強制標籤：** 使用者若已設定強制標籤原則，其系統管理員將需要標記其文件和電子郵件。

### <a name="word"></a>Word

- **強制標籤：** 使用者若已設定強制標籤原則，其系統管理員將需要標記其文件和電子郵件。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2012-december-28"></a>版本 2012：12 月 28 日
*版本 2012 (組建 13530.20264)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致某些客戶在載入行事歷時遇到停滯的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-december-21"></a>版本 2012：12 月 21 日
*版本 2012 (組建 13530.20218)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see. This is a silent functionality (no UI) for administrator benefit.

### <a name="outlook"></a>Outlook

- **Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default. [Learn more](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- **Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see. This is a silent functionality (no UI) for administrator benefit.

### <a name="powerpoint"></a>PowerPoint

- **Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see. This is a silent functionality (no UI) for administrator benefit.

### <a name="word"></a>Word

- **Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see. This is a silent functionality (no UI) for administrator benefit.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="powerpoint"></a>PowerPoint

- 我們已修正一個問題，即在 QAT 中新增的字型大小命令在更新時，會自動完成到最接近的已定義字型大小。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-december-14"></a>版本2012：12 月 14 日
*版本 2012 (組建 13530.20144)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **雲端中的 Outlook 設定：** 選擇您的 Windows 版 Outlook 設定，例如自動回復、焦點收件匣和隱私權，並在任何電腦上使用這些功能。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="office-suite"></a>Office 套件

- 優化的二進位大小。


- Anaheim WebView 目前尚不支援 Windows 資訊保護(WIP)。 有了此修正程式，Office addin 平臺便會回到處於 WIP 啟用環境中的低層級 WebView。 根據客戶的電腦環境，這可以是 Edge Spartan WebView 或 Trident WebView。 兩個低層級 WebViews 皆支援 WIP。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-december-07"></a>版本2012：12 月 7 日
*版本 2012 (組建 13530.20064)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新

### <a name="teams"></a>Teams

- **Teams 現在支援 Windows 原生通知：** 使用者現在可以選取其偏好的通知傳送方式，即透過 Teams 內建橫幅或 Windows 原生橫幅。


- **Citrix 與 VMWare VDI 的 Teams 會議 2X2 圖庫檢視：** Teams 用戶端在 VDI 最佳化模式中時，Teams 的 VDI 2x2 圖庫檢視功能會啟用，可讓您在 2x2 圖庫中檢視 Citrix、VMWare 之 VDI 用戶端的最多四個出席者影片。


- **Meeting Reactions:**  Meeting reactions are a new way to interact in meetings. Participants can send reactions which are shown as a stream on content that is being shared, and on the individual who sent the reaction if they're displayed on the meeting stage. 


- **Web 會議的共聚模式和大型圖庫** 大型圖庫可讓您一次看到最多 49 個其他人員的影片。 當至少 10 人開啟相機時，即可使用此選項。 共聚模式可讓您感覺與會議中每個人處於相同的共用空間。 當會議中至少有五個人時，即可使用共聚模式。 


- **Call Merge** Call Merge allows users to merge a new call they place, or a new incoming call, into their 1-1 or group call. This applies to Teams VOIP calls and PSTN calls. 


### <a name="visio"></a>Visio

- **New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams. [Learn more](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正部分功能區元素未以簡體中文進行當地語系化的問題。


- 我們已修正更新時 Excel 意外終止的問題。


- 我們已修正從 OneDrive 本機同步處理資料夾插入檔案時，[插入物件] 命令沒有顯示正確圖示的問題。


- 已修正在覆寫模式下編輯時，使用需要使用 IME 的語言進行編輯時表現不佳的問題。


- 修正此問題：一些使用者在共同撰寫時會錯誤地看到通知他們檔案新版本的訊息列。


- 已修正在公式檢視中複製和貼上資料時 Excel 意外關閉的問題。


- 修正在自動儲存被停用時通知中說明文章的斷開連結。


- 我們已修正以下問題：當 Excel 以某些語言執行時輸入資料可能導致 Excel 停止運作。


- 此變更解决了在方程式中正確顯示字型的問題。


- 這修正了Power Pivot 無法正確導入定位字元分隔的文字檔的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致「收件者:」欄位在工作狀態報告中空白的問題。


- 我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。


- 我們已修正導致使用者在從 Outlook 以外的應用程式傳送 Outlook 郵件時遇到一些問題的問題。


- 我們已修正會導致 SmartLinks 在儲存至草稿時丟失其格式的問題。


- 我們已修正將附件新增到從 zip 檔案開啟的郵件時會失敗的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。


- 此變更解決筆跡分析期間發生的超時問題。


- 此變更解決建立動畫 GIF 使用者介面中的語法錯誤。


- 此變更解决對某些幾何圖形套用 [合併圖案] 作業時路徑填充的問題。


- 此變更解決了在方程式中正確顯示字型的問題。


- 此變更解決了處理載入影片期間可能發生錯誤的問題。


- 我們已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生意外關閉的 VBA 問題。


- 我們已修正一個問題，即未知的共同作者的狀態指示器在有關於共同作者的更多資訊可用時沒有完全重新整理。


- 修正當投影片檢視的大小在尺規開啟時被解除引用的 null 指標。


- 已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。


### <a name="project"></a>Project

- 我們已修正預期使用者開啟的專案應已儲存更新的資訊，但發現遺漏更新的問題。


- 我們已修正若交付項目相關聯的 SharePoint 網站已不再存在時，無法刪除交付項目的相依性的問題。


- 修正開啟具有大量資源的專案時所花費的時間很長的問題。


- 修正使用者可能會看到多個未指派工作分派與任務相關聯的問題。


- 已修正在大型專案中，輸入任務名稱的速度可能非常緩慢的問題。


- 已修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。


### <a name="word"></a>Word

- 貼上為純文字通常優於貼上為 RTF 文字。 此快顯功能表修正功能可讓使用者貼上純文字格式。 否則，使用者必須複製至純文字編輯器 (如 [記事本])，然後從 [記事本] 複製到所要的目標應用程式


- 修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。


- 此變更解決編輯檔時游標的問題。


- 我們已修正在縮放圖片時，圖片變得模糊的相關問題。


- 我們已修正長超連結被截斷的問題。


### <a name="office-suite"></a>Office 套件

- Office 套件已修復此問題：在某些較舊的版本上安裝較新版的 Office 時，可能會造成功能受損 (例如由於遺失登錄專案而無法使用 Power Query)。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-december-01"></a>版本2011：12 月1 日
*版本 2011 (組建 13426.20306)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **每個線上會議：** 使用新設定將所有會議預設設定為線上，讓您輕鬆安排線上會議。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致某些會議的原始出席者在另一個出席者轉寄會議時收到取消通知的問題。


- 我們已修正會導致某些使用者未設定一或多個簽章時，在 [簽名] 下拉式清單中看不到任何簽名的問題。


### <a name="project"></a>Project

- 已修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-24"></a>版本 2011：11 月 24 日
*版本 2011 (組建 13426.20294)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="office-suite"></a>Office 套件

- 修正從 Word 到 PowerPoint 複製/貼上方程式時發生的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-21"></a>版本 2011：11 月 21 日
*版本 2011 (組建 13426.20274)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="powerpoint"></a>PowerPoint

- **影片庫：** 在應用程式內使用精選的免版稅影片素材庫來提升您的文件


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。


- 我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含內容。 HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。 REG_DWORD IncludeFileTimesInDataObject。 0 = 不包含 filetimes。 1 = (預設) 包含 filetimes


- 我們已修正當回復含有「Azure 資訊保護」保護標籤的郵件時，會導致內嵌影像消失的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-18"></a>版本 2011：11 月 18 日
*版本 2011 (組建 13426.20250)*
* 各種錯誤和效能修正。

## <a name="version-2011-november-16"></a>版本 2011：10 月 16 日
*版本 2011 (組建 13426.20234)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **所有裝置都有相同的簽章：** 在雲端中儲存簽章。 只要建立一次，就能在所有使用 Outlook 的位置使用。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正傳送任務中的狀態報表時，導致 [收件者] 欄位為空白的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生意外關閉的 VBA 問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-09"></a>版本 2011：11 月 9 日
*版本 2011 (組建 13426.20184)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **從查詢建立 Power Platform 資料流程：** 您現在可以將查詢匯出至 Power Query 範本，以建立新的 Power Platform 資料流程


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 修正某些使用者在嘗試從其同步處理的 OneDrive 資料夾匯出査詢時看到「系統資源滿載」錯誤的問題。


- 我們已修正表單視窗之間發生「自動」切換而切換到另一個表單的問題。


- 我們已修正從非 Office 應用程式使用 DAO 時，會導致應用程式意外關閉的問題。


### <a name="excel"></a>Excel

- 我們已修正啟用 SaveAs 作業與 COM 增益集之後，檔案名稱未變更的問題。


- 修正 Power Pivot 使用 Oracle 資料庫連線時的問題。


- 我們已修正當 Excel 資料模型中有錯誤的度量定義時，自動儲存會失敗且顯示錯誤/令人誤解的錯誤訊息的問題。


- 我們已修正觸發 MTR 計算和群組原則物件更新 (例如，透過遠端群組原則重新整理) 的處理序時，Excel 異常終止的問題。


- 我們已修正使用者無法直接從 SharePoint 開啟 atomsvc (UTF8+BOM) 檔案的問題。


- 我們已修正放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。


- 我們已修正將 Excel 活頁簿插入 Word 文件時，Word 似乎停止回應的問題。


### <a name="outlook"></a>Outlook

- 解決在新增或儲存附件時，會導致 Outlook 停止運作的問題。


- We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture. Check the location, and then try again".


- 我們已修正會導致某些使用者看到 Outlook 在離線狀態下啟動，直到他們手動選擇線上工作的問題。


- 我們已修正將從會議位置複製的 URL 貼上到其他位置 (例如瀏覽器) 時，URL 的結尾會包含分號的問題。


- 我們已修正使用者無法在 [基本驗證] 中刪除 Microsoft 365 群組行事曆約會的問題。


- 我們已修正載入暱稱快取時啟動 Outlook 失敗的問題。


- 我們已修正信箱擁有者無法管理自己行事曆的共用權限的問題，因為該選項呈現灰色停用狀態。


- 我們已修正 Outlook 無法使用受限制的權限建立郵件的問題。


- 我們已修正將電子郵件範本儲存為 .OFT 時，會將中文字元變更為問號的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正放大和縮小簡報會造成縮放選取跑馬燈和滑鼠指標之間間隙的問題。


- 我們已修正 [圖片] 旁的內容預留位置圖示沒有工具提示的問題。


- 我們已修正 pptsx 檔案所顯示的投影片放映之受保護檢視，允許受 IRM 保護的文件螢幕擷取的問題。


- 我們已修正關閉設計窗格時，投影片的格線移位的問題。


- 我們已修正將投影片放映複製到次要監視器時，投影片可能會隱藏在其他視窗後面的問題。


- 我們已修正投影片在選取項目窗格開啟的情況下停止螢幕錄製後，投影片中的捲軸會自行開始調整的問題。


### <a name="project"></a>Project

- 修正如果 [工作表單] 類型檢視中的延遲變更，ProjectBeforeTaskChagne 事件中的 NewVal 值不正確的問題。


- 我們已修正在開啟以特定方式指定資源分佈的檔案時，Project 可能會意外終止的問題。


- 修正當您將專案從 PWA 儲存到本機 mpp 檔案時，會針對實際上使用者未變更的資料觸發 ProjectBeforeTaskChangeEvent 的問題。


- 修正資源預訂依名稱 (而不是 GUID) 搜尋資源時，如果有多個名稱相同的資源，會導致問題的問題。


- 已修正如果您在專案網站中有工作清單並將工作清單分組，您將無法快速編輯工作清單的問題。


- 修正如果您透過 CSOM 更新企業資源，可能會遺失資源最大單位。


### <a name="word"></a>Word

- 我們已修正放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。


- 我們已修正按一下註解提示時，註解提示不會放大以在檢視中顯示註解卡片的問題。


- 我們已修正欄位之間的線條可能已移位的版面配置問題。


- 我們已修正有時開啟 Word 文件可能會顯示錯誤對話方塊的追蹤修訂問題。


- 我們已修正將 Excel 活頁簿插入 Word 文件時，Word 似乎停止回應的問題。


- 我們已修正套用具有浮水印的敏感度標籤時的列印問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正 Office 部署工具中的一個問題，該問題是，在 Microsoft Office 2007 [Microsoft 應用程式錯誤回報工具] 產品存在的情況下使用 RemoveMSI 功能時設定失敗。


- 我們已修正 SSO API 互動式登入傳回錯誤碼的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-november-06"></a>版本 2010：11 月 6 日
*版本 2010 (組建 13328.20356)*
* 各種錯誤和效能修正。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2010-november-04"></a>版本 2010：11 月 04 日
*版本 2010 (組建 13328.20340)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps. [Learn more](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a>Outlook

- **SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps. [Learn more](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a>PowerPoint

- **SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps. [Learn more](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br />在[部落格文章](https://insider.office.com/en-us/blog/svg-content-office-third-party-apps)中查看詳細資料

- **使用透明背景建立 GIF：** 當匯出成動畫 GIF 時，您可以使用新選項讓背景變透明。<br />在[部落格文章](https://insider.office.com/en-us/blog/export-animated-gifs-transparent-backgrounds)中查看詳細資料

- **匯出一定範圍內的動畫 GIF** 在匯出成動畫 GIF 時，選取投影片的範圍

### <a name="word"></a>Word

- **SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps. [Learn more](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致使用者無法將 [編輯器] 權限授與代理人的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正在嘗試儲存已從 syncbacked 檔案轉換為僅限伺服器的檔案時，導致失敗的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-27"></a>版本 2010：10 月 27 日
*版本 2010 (組建 13328.20292)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致預設不會為使用者開啟雲端設定的問題。


- 我們已修正會導致對使用者簽章的變更無法儲存的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-24"></a>版本 2010：10 月 24 日
*版本 2010 (組建 13328.20278)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正在回覆或轉寄時，會導致中文郵件標題無法閱讀的問題。


- 我們已修正在儲存為 OFT 檔案時，會導致中文字元變更為問號的問題。


### <a name="project"></a>Project

- 修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。


- 修正如果工作表單類型檢視內的延隔時間變更，ProjectBeforeTaskChange 事件中的 NewVal 不會有正確值的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-19"></a>版本 2010：10 月 19 日
*版本 2010 (組建 13328.20210)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **撰寫郵件時節省時間：** Outlook 會顯示書寫建議，協助您快速撰寫郵件。 若要接受建議，只需使用 Tab 鍵。<br />在[部落格文章](https://insider.office.com/en-us/blog/text-predictions-in-word-outlook)中查看詳細資料

- **使用內建翻譯工具打破語言障礙：** 不再需要翻譯的增益集！ 在電子郵件中，按一下滑鼠右鍵以翻譯特定的文字、片語或整個郵件。 [深入了解](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- **工作的使用者體驗更新：** 工作項目的視覺效果更新

### <a name="powerpoint"></a>PowerPoint

- **Practice your presentation with Presenter Coach:** Get coaching on the things that help keep an audience engaged — like pacing, overused words, body language, and more. [Learn more](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a>Word

- **電腦版 Word 中的 Microsoft 編輯器窗格已更新：** 我們已將電腦版 Word 用戶端中編輯器窗格目前的體驗升級。

- **單鍵書寫建議：** 只要按一下，就能套用書寫建議。 更新的 [編輯器] 窗格讓您輕鬆在建議之間瀏覽。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="powerpoint"></a>PowerPoint

- 這是此問題的修正：當有增益集在接聽 PresentationBeforeClose 事件並隨著事件處理常式檢查 Presentation.Saved 內容時若關閉文件，儲存提示會以迴圈顯示。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-11"></a>版本 2010: 10 月 11 日
*版本 2010 (組建 13328.20154)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container. [Learn more](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a>PowerPoint

- **Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container. [Learn more](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a>Word

- **Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container. [Learn more](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正載入儲存的查詢/關聯視窗在捲動時，捲軸位置未正確設定的問題。


- 我們已修正 [新增表格] 工作窗格未正確顯示包含 '&' 名稱的問題。


### <a name="excel"></a>Excel

- 我們已修正多層次類別的手動間隔在圖表中無法運作的問題。


- 修正在使用 2D 地圖圖表時，無法使用 VBA 設定系列中最大值、中間值和最小值顏色的問題。


- 修正可能會導致「嘗試計算一個或多個公式時，Excel 資源不足」的錯誤問題。


- 修正當 Office 語言設定為西班牙文時，其中資料驗證清單可能無法顯示清單中所有項目的問題。


- 修正在啟用「分頁預覽」時，在含有大量資料的工作表之間切換時，可能會發生明顯延遲的問題。


- 我們已修正當新增至用於資料驗證的表格時，並未更新活頁簿中所有工作表選項的問題。


- 我們已修正在重新整理 OLAP 樞紐分析表時，可能會導致當機的問題。


- 已修正在使用資料編輯列輸入公式時，某些情況下 ChartSheet 出現意外關閉的問題。


- 我們已修正 Excel 公式列與設備失去連線後無法完全呈現的問題，例如遠端會話的連線/斷線或監視器變更。


### <a name="onenote"></a>OneNote

- 我們已修正使用者無法從 [外部空間檔案] > [資訊] 的文字方塊中選取及複製筆記本 URL 的問題。


- 我們已修正當您將游標移至筆記本色彩選擇器的綠色上方時，快顯會顯示「紅粉色」的問題。


- 我們已修正 OneNote 在自訂主題的畫布中不會採用高對比色彩的問題。


### <a name="outlook"></a>Outlook

- 已解決當主旨為空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。


- 我們已修正資料夾中快取錯誤資料夾 guid 的問題。


- 當使用者將電子郵件地址複製貼上到顯示名稱的 [收件者] 欄位時，電子郵件地址不一定可被正確分析，並導致出現了一個顯示電子郵件地址無效的警告。  已修正此問題，可正確分析名稱和電子郵件地址，因此不會再顯示警告。


- 我們已修正線上共用資料夾未傳回母資料夾名稱的問題。 它並非失敗，而是傳回了不正確地移至主要帳戶的空白路徑。


- 我們已修正傳統附件無法使用 [另存為] 選項的問題。


- 我們已修正讓使用者能在覆寫原則時自訂調整文字的問題。


- 我們已修正從唯讀預覽窗格中重新開啟 [草稿] 之後會開啟 [追蹤修訂] 的問題。


- 我們已修正關閉 [焦點收件匣] 並執行排序之後，電子郵件遭隱藏的問題。


- 我們已修正會導致 Outlook 為啟用雲端設定的使用者建立第二個空白簽名的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 PowerPoint 在匯出為 PDF 時，無法匯出矩形專案符號的問題。


- 我們已修正 GIF 在編輯器和投影片放映中的動畫只會執行一次的問題。


- 我們已修正當使用者將來源路徑變更為本機 OneDrive 資料夾時，連結的 Excel 圖表不正確變更為 Excel 工作表的問題。


- 我們已修正若您在最後一張投影片上，且您在按 [結束工作模式] 之後和顯示摘要之前，滑向下一張投影片，則會在 [摘要] 頁面上看到 [結束工作模式] 對話方塊。


### <a name="project"></a>Project

- 修正了如果您嘗試多次新增同一專案，且將 AttachToSources 設定為 false 時，ConsolidateProjects VBA 方法可能會發生出錯的問題。


- 修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。


- 修正了如果您嘗試多次新增同一專案，且將 AttachToSources 設定為 false 時，ConsolidateProjects VBA 方法可能會發生出錯的問題。


- 修正了如果您的自訂欄位包含公式，且正在使用實獲值分析，您可能會發現效能延遲切換檢視並開啟專案/工作詳細資料的問題。


- 修正了如果您將群組套用到 [資源使用狀況] 或 [工作表] 視圖，然後插入欄位，Project 可能會意外關閉的問題。


### <a name="word"></a>Word

- 我們己修正已啟用工作流程檔案的連結無法如預期開啟的問題。


- 修正當使用者在點擊追蹤的變更 (插入/刪除) 時，會彈出註解的問題。


- 我們已修正 Word 中刪除註解圖說文字的問題。


- 我們已修正 Outlook 有關將郵件設定為 [不要轉寄] 的問題。


- 我們已修正有關儲存含有引文和方程式的 Word 文件問題。


- 我們已修正 [樣式圖庫] 對話方塊的問題。


### <a name="office-suite"></a>Office 套件

- When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-07"></a>版本 2009：10 月 7 日
*版本 2009 (組建 13231.20360)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用 Power Query 建立資料類型：** 使用任何資料來源中的 Power Query 建立豐富的資料類型

### <a name="outlook"></a>Outlook

- **語文法檢查鼎力相助**：Outlook 會在你鍵入時標記文法錯誤，因此你只需按一下就可以套用建議。 <br />在[部落格文章](https://insider.office.com/en-us/blog/grammar-and-style-suggestions-available-in-outlook)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決了搜尋未緩存共用行事曆時導致搜尋不傳回結果的問題。


- 解決了導致某些使用者觀察到在離線狀態下意外啟動 Outlook 的問題。


- 解決了導致代理人在開啟另一個信箱中的共用資料夾時出現錯誤的問題。


### <a name="powerpoint"></a>PowerPoint

- 解決在受保護的檢視中開啟 PowerPoint 檔案時停用 IRM 保護的問題的安全性問題修正。


### <a name="office-suite"></a>Office 套件

- When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-26"></a>版本 2009：9 月 26 日
*版本 2009 (組建 13231.20262)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。


### <a name="project"></a>Project

- 修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-21"></a>版本 2009：9 月 21 日
*版本 2009 (組建 13231.20200)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a>Excel

- **Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office. No conversion required.<br />在[部落格文章](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)中查看詳細資料

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a>OneNote

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a>Outlook

- **依訊息擁有者刪除交談：** 此功能可讓您依訊息擁有者刪除交談。

- **Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office. No conversion required.<br />在[部落格文章](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)中查看詳細資料

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a>PowerPoint

- **Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office. No conversion required.<br />在[部落格文章](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)中查看詳細資料

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a>Project

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a>Publisher

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a>Visio

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a>Word

- **Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office. No conversion required.<br />在[部落格文章](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)中查看詳細資料

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [選項]，然後選取 [Office 佈景主題] 旁邊的 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="powerpoint"></a>PowerPoint

- 修正了在包含大量特定資料物件類型 (E2o) 的檔案上導致共同撰寫變慢的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-14"></a>版本 2009：9 月 14 日
*版本 2009 (組建 13231.20152)*
* 各種錯誤和效能修正。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2009-september-10"></a>版本 2009：9 月 10 日
*版本 2009 (組建 13231.20126)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此問題現在已解決，您不應該會再遇到意外關閉問題。


- 我們已修正 ODBC 資料庫的連線對協力廠商應用程式沒有作用的問題。


### <a name="excel"></a>Excel

- 我們已修正一個問題, 即如果您開啟包含LET 函數的檔案，它會顯示警示：”我們在您的檔案.xlsx 中發現內容有問題”。 您想要我們儘量嘗試復原嗎？ 如果您信任這個活頁簿的來源，請按一下 [是]。


- 我們已修正如果用戶鍵入包含括號的公式名稱並通過F1調用了協助，則該特定於公式的說明主題將不會顯示。


- 我們已修正使用巨集來設定某個範圍的 FormulaR1C1 屬性時，如果圖表工作表為作用中工作表，則儲存格參考會不正確的問題。


- 我們已修正使用者無法修改樞紐分析表篩選的問題，因為它已設定為Analysis Services數據庫中不再存在的值。


- 已修正與 XLAM 增益集參照和具名範圍相關的意外關閉問題。


- We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array". This was a legacy restriction that has been removed.


- 修正在還原檔案的舊版本後，指派給按鈕的巨集會中斷的問題。


- 我們已修正筆跡會導致 Excel 無法回應的問題。


### <a name="outlook"></a>Outlook

- 我們已修正一個問題, 讓您可透過群組政策來啟用/停用預設的登入選項。


- 我們已修正電子郵件草稿在助理和經理權限移動時, 寄件者的舊網域名稱仍被保留和顯示的問題。


- 修正會導致某些使用者看到 Outlook 在離線狀態中啟動，直到他們手動選擇線上工作為止的問題。


- 我們已修正在啟用單行功能區 (SLR) 後，執行 VBA 程式碼 ActiveInspector ("ShowSchedulingPage") 會導致執行階段錯誤的問題。


- 我們已修正一個問題, 即Automatic Replies自動回復對話方塊上的確定和取消按鈕以高解析度 (例如 1750 x 1920) 及較大文字 (例如 175%) 顯示的系統上的錯誤。


- 我們已修正將會議請求從空的聯繫人群組發送到另一個聯繫人組會導致意外關閉的情況。


- 修正導致使用者在開啟某些很大型電子郵件時會發生意外關閉的問題。


- 我們已修正一個問題, 它使的群組政策要求始終啟用增益集, 則 監視增益集的功能則無法使用，以防止使用者禁用增益集,。


- 解決一個問題，該問題導致使用者在選擇多個訊息時，能夠傳送 OneNote 所套用的「不可轉寄」原則的電子郵件內容。


- 我們已修正一個問題，使用者現在可以停用 Outlook 的 IRM (資訊版權管理)，而不需要為其餘 Office 應用程式停用它。


- 我們已修正 Active Directory 中的 "otherTelephone" 和 "otherHomePhone" 使用者帳戶屬性未對應到對應的 Outlook LDAP 屬性的問題。


- 此變更解決了在用戶將索引標籤從會議頁面切換到排程小幫手頁面後，會議頁面將繼續顯示的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用者在特定情況下看到功能區/標題列未顯示的問題。


- 我們已修正啟動 PowerPoint 之後，插入投影片並開啟和關閉批註窗格的問題，縮圖窗格中的投影片會顯示為重疊。


- 我們已修正插入影片的功能已停用的問題。


- 我們已修正影片在投影片放映中無法自動播放的問題。


### <a name="project"></a>Project

- 我們已修正如果資源有多個成本費率表的問題，則剩餘成本可能無法被正確計算.


- 我們已修正連結至 SharePoint 工作清單的專案的專案完成日期不會更新的問題。


### <a name="visio"></a>Visio

- 客戶回報文字對齊會在即時預覽時發生當機。 7 月分支所發生最多的當機情況。


### <a name="word"></a>Word

- 我們已修正一個問題, 即使用者點擊註解，註解卡將在註解文周圍顯示邊框。


- 我們已修正項目符號圖片無法正確顯示的問題。


- 我們已修正使用者在選取註解時無法退出頁首/頁尾的問題。


- 我們已修正刪除註解之後 Word 可能會當機的問題。


- 我們已修正一個問題，即如果使用者建立的評論草稿, 錨定在已包含提交的評論行上，則在SideTrack與提交評論相關的草案則以錯誤的順序排列。


- 我們已修正一個問題, 即如將文件縮放到160％或更高, 且註解窗格不可見，焦點將不會移至註解窗格。


- 我們已修正一個問題，該問題造成使用者無法看到超出邊界的註解，因為在邊界中無法下拉。


- 我們已修正在邊界窗格中，搜尋已解決的註解無法正常運作的問題。


- 我們已修正一個問題，即在多個打開的文件之間切換後，一個文件的註解會顯示在其他打開的文檔上。


- 我們已修正將文件儲存成 HTML 格式時，長連結無法換行的問題。


- 我們已修正在某些情況下，項目符號無法在電子郵件中正確顯示的問題。


- 我們已修正 AutoOpen 會在 AutoExec 之前執行的巨集問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正 Office 部署工具中的一個問題，該問題是，在 Microsoft Office 2007 [Microsoft 應用程式錯誤回報工具] 產品存在的情況下使用 RemoveMSI 功能時設定失敗。


- 我們在 [壓縮圖片] 對話方塊中，修正了某些使用者選取的 DPI 設定無法保留的問題。


- 此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-04"></a>版本2008：9月 4日
*版本 2008 (組建 13127.20378)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="office-suite"></a>Office 套件

- 此變更解決 [壓縮圖片] 對話方塊無法保留特定使用者設定的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-02"></a>版本 2008：9 月 2 日
*版本 2008 (組建 13127.20360)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere. [Learn more](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **使用 Excel 手寫筆進行快速編輯：**[手寫筆工具] 可協助您手寫並快速編輯資料



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正使用 [複製格式] 時，某些情況下，Excel 可能會當機的問題。


### <a name="word"></a>Word

- 我們已修正基本樣式並未以 [內文樣式] 更新的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-27"></a>版本2008：8月27日
*版本 2008 (組建 13127.20296)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 修正會導致使用者嘗試從次要帳戶建立會議邀請的問題，讓帳戶新增至他們的個人檔案，而不會看到空白的表格: 是欄位而不是其電子郵件地址。

- 修正新增共用信箱之後，導致使用者無法連線至公用資料夾的問題。

- 修正了當與雲端附件互動時，導致使用者偶爾當機的問題。

- 修正了編輯收件者時，導致使用者偶爾當機的問題。

- 修正會導致使用者在使用壓縮模式時發生異常的問題。

### <a name="word"></a>Word

- 此更改解決了一個問題，即在上一個協同合作的作業後，Microsoft Office 應用程式可能卡在未通知的儲存失敗狀態的問題。

- 我們已修正整體的 AutoOpen 在 AutoExec 之前執行的問題



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-25"></a>版本 2008：8 月 25 日
*版本 2008 (組建 13127.20268)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **依人員搜尋時，收到電子郵件的建議：** 當您在 Outlook 中輸入搜尋字詞時，您會在建議中看到出現最相關的電子郵件。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決會導致使用者在回覆或撰寫新電子郵件時收到下列錯誤的問題：「這個網頁中的某些檔案不存在預期的位置， 請問您一定要下載嗎? 如果您確定網頁來自信任的來源，請按 [是]」


### <a name="project"></a>Project

- 修正如果資源中定義了多個成本費率表，其餘成本並不一定都能正確地計算的問題。


### <a name="word"></a>Word

- 解決會導致使用者在回覆或撰寫新電子郵件時遇到當機的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-17"></a>版本2008：8月17日
*版本 2008 (組建 13127.20208)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決了當代理人在某些情況下遭到拒絕而導致會議無法從經理的行事曆中移除的問題。


- 解決了導致某些字元集的使用者在將 [智慧型連結] 新增至 SharePoint 檔案時，發現檔案名不正確的問題。


- 解決了當您從 POP 帳戶刪除4或多個電子郵件時，已選取 [僅下載標題] 選項時，導致使用者遇到當機的問題。


- 解決的問題導致在搜尋控制項中無法顯示滑鼠右鍵功能表。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-11"></a>版本 2008: 8月11日
*版本 2008 (組建 13127.20164)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此修正會解決嘗試執行之前會產生「查詢太複雜」錯誤訊息的特定查詢的問題。

- 如果您已安装 Office 365，您就不需要再安装 [ACE 可再發行引擎]，就能在 Office 生態友善系統外公開 ACE。 因此，如果您使用的是 Office 365，您將不需要 [ACE 可再發行引擎]，也因此不會再遭遇此問題。

- 已解决此問題 - 您現在可以使用 Office 的隨選即用應用程式外的 ODBC 驅動程式。

### <a name="excel"></a>Excel

- 我們已修正若圖表數列順序已變更，與該數列對齊的對應核取方塊未隨著該數列重新排序的問題。

- 嘗試使用 LET () 函數儲存含有公式的檔案時，可能會發生錯誤。

- 我們已修正當透過 VBA 啟用活頁簿的 [ForceFullCalculation] 時，圖表不一會更新的問題。

- 我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。

### <a name="onenote"></a>OneNote

- 我們已修正當應用程式視窗調整為小尺寸時，[搜尋] 編輯方塊中的預留位置文字發生溢出的問題。

### <a name="outlook"></a>Outlook

- 我們已修正從相同的電子郵件網域在 Outlook 中建立多個設定檔會產生的問題。

- 解决了導致使用 [共用行事曆改善] 的某些使用者無法查看剛新增的共用行事曆的問題。

- 解決了導致在 S/MIME 加密郵件的頁首中無法顯示鎖定圖示的問題。

- 我們已修正，如果未核取 [下載共用資料夾]，共用行事曆會議 [回覆選項] 中缺少 [允許轉寄] 選項的問題。

- 解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。

- 我們已修正，即使使用者具有適當的列印權限也會在停用狀態下顯示列印按鈕的問題。

- 解決了當以未加密郵件進行傳送時，會導致附件從 S/MIME 郵件中剝離出來的問題。

- 解決了當純文字 S/MIME 郵件在傳送時發生亂碼的問題。

- 解決了當傳送未加密的 S/MIME 電子郵件時，會導致附件損毀的問題。

- 解決了當寄件者授與 [另存為] 許可權時，會導致收件者無法儲存許可權保護郵件的問題。

- 這解決了當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，會導致使用者會無法新增簽名的問題。

- 此修正會解決導致 Outlook 無法在 markdown 內容中正確顯示換行符號的問題。

- 解決了某些 [進階搜尋] 選項標籤在某些語言中會被截斷的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。

- 我們已修正 PowerPoint 中的 [表單] 按鈕在不允許存取 Office Store 時不會允許建立表單的問題。

### <a name="project"></a>Project

- 我們已修正 [工作委員會] 畫面中列出的工作未與 [指派資源] 對話方塊中的任務同步處理的問題。

- 我們已修正如果您嘗試從 Project 將 PDF/XPS 儲存至 SharePoint 文件庫，沒有發生任何動作的問題。

- 我們已修正當您複製並貼上具有多個相關性的工作，並非所有相關性都能正確複製的問題。

- 修正針對 SharePoint 工作清單，第二個索引標籤上的功能區按鈕可能會停用的問題。

### <a name="skype"></a>Skype

- 將跳舞表情符號膚色變更為中性色彩

### <a name="visio"></a>Visio

- 在此修正程序完成之後，如果使用者在任何機制 (在此情况下是透過增益集) 停止執行刪除命令，內存便不會洩漏，而且也不會影響整台電腦。

### <a name="word"></a>Word

- 我們已修正將某些文字及影像貼到 [註解] 方塊之後，Word 停止回應的問題。

- 我們已修正具有放射狀漸層填滿的影像複本與原始不符的問題。

- 我們已修正當應用程式視窗調整為小尺寸時，[搜尋] 編輯方塊中的預留位置文字發生溢出的問題。

- 我們已修正如果新增註解來追蹤變更，將會意外開啟 [修訂] 窗格的問題。

- 我們已修正當焦點位於註解文字方塊中時，[編輯器] 命令會被停用的問題。

- 我們已修正當焦點位於註解文字方塊中時，[顯示標記] 命令會被停用的問題。

- 我們已修正刪除最後一個註解後，[新增批註] 按鈕停用的問題。

- 我們已修正 [追蹤修訂] 中的 [特定人員] 選項已停用的問題。

- 我們已修正文件連結未透過 [插入] > [連結] 下拉式功能表插入 [註解] 方塊的問題。

- 我們已修正了開啟 HTML 檔案時偶爾停止回應的問題。

- 我們已修正自訂 XML 中的註解狀態在開啟文件時可能會遺失的問題。

- 我們已修正 VBA 超連結集合中的超連結計數，在新增包含超連結的影像之後，未正確反覆運算的問題。

- For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash. This is now fixed.

- 我們已修正使用者從工作列開啟新應用程式視窗，並建立新的空白檔時，會造成額外檔案建立的問題。

- 我們已修正當使用者在編輯文件，但是許可權遺失時，我們並未通知使用者必須重新驗證的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-august-05"></a>版本 2007：8 月 5 日
*版本 2007 (組建 13029.20344)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決會導致 Outlook 無法擷取搜尋建議的問題。


- 解決會導致使用者在擷取角色資訊時有時候會當機的問題。


### <a name="project"></a>Project

- 修正無法開啟已進入錯誤狀態的專案的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-29"></a>版本 2007：7 月 29 日
*版本 2007 (組建 13029.20308)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 E5/A5 或 Microsoft 365 E5/A5 之組織的測試人員使用。 取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。 我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。 [深入了解](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料

### <a name="outlook"></a>Outlook

- **挑選搜尋的位置：** 新的搜尋範圍下拉式清單，可讓您更輕鬆地修改搜尋，並在目前資料夾和目前信箱之間切換。 感謝每個在 [即將推出] 為 [頂極體驗] 的 新 [搜尋] 提供意見反應的人。 因為有這份意見反應，才有這項設計與更新！

### <a name="word"></a>Word

- **Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience. [Learn more](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決了導致 CLP 使用者在從受保護的內容切換到未受保護之回復的 [寄件者] 位址時發生當機的問題。


- 解決了導致 [排程小幫手] 頁面無法顯示的問題。


- 解決了事件通知提醒中導致格式設定問題的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-27"></a>版本 2007：7 月 27 日
*Version 2007 (組建 13029.20292)*
* 各種錯誤和效能修正。

## <a name="version-2007-july-20"></a>版本 2007：7 月 20 日
*版本2007 (組建 13029.20236)*
* 各種錯誤和效能修正。

## <a name="version-2007-july-15"></a>版本 2007：7 月 15 日
*版本 2007 (組建 13029.20200)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet. [Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正在重新整理連結的 SQL 資料表時，連結資料表管理員會提示您輸入主要索引鍵的問題。

- 我們已修正 [查詢編輯器] 中的查詢捲出畫面的問題。

- 我們已修正執行查詢的時間大約比預期完成時間兩倍久的問題。

- 我們已修正導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。

### <a name="excel"></a>Excel

- 我們已修正非 HTTP 或 HTTPS 型 URL 未顯示在 [最近用過的] 清單中的問題。

- 修正在載入含有多張分頁預覽的活頁簿時，可能會發生錯誤或當機問題。

- 我們修正以下問題：在特定版本 Excel 中建立的資料模型表格無法在 [表格預覽] 中看到，即使與該表相關聯的查詢尚未編輯。

- 在 [定義名稱\套用名稱] 對話方塊中停用 [忽略相對/絕對] 參照會導致公式無法使用。

- 我們已修正將活頁簿儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 遭移除的問題。

- 我們已修正當建議以唯讀方式使用檔案時，活頁簿處於唯讀狀態的問題。

- 修正在載入含有多張分頁預覽的活頁簿時，可能會發生錯誤或當機問題。

- 我們已修正雷達圖的主要格線無法正確設定格式的問題。


- 我們已修正清除 [進階資料篩選] 可能會遺失表格格式設定的問題。


- 我們已修正嵌入式 PDF 文件的完整路徑顯示在文件標題，而不只是檔案名稱的問題。


- 我們已修正停用 Wolfram 雲端連接器之後，儲存並重新開啟 Excel 活頁簿可能會導致當機的問題。


- 我們已修正啟動 Excel 時啟用 [規劃求解] 增益集將導致當機的問題。


### <a name="outlook"></a>Outlook

- 我們已修正如果在 [收件者] 行上有超過 130 個收件者，Outlook 會當機的問題，且我們也改善了呈現文字的效能。


- 我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。


- 我們已修正「待辦事項列」中跨越兩天以上的活動，在後續的所有日期中顯示相同結束時間的問題。


- 解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。


- 我們已修正使用者無法使用通訊群組清單中的「傳送為」或「代理傳送者」的問題。


- 解決在編輯經理行事曆上的現有行事曆約會時，導致代理人收到錯誤的問題。


- We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window. Do you want to make a copy in the default folder for the item?"


- 解決會導致若「未」核取 [下載共用資料夾]，共用行事曆會議的 [回應選項] 中會遺失 [允許轉寄] 選項的問題。


- 解決選取安全性對話方塊上的 [儲存] 選項時，會導致使用者無法將來自其租用戶外部的 OneDrive 附件儲存至其本機電腦的問題。


- 我們已修正導致 Outlook 使用者在使用共用行事曆後，在幾分鐘內訊息清單停止更新的問題。


- 我們已修正行事曆提醒無法針對一週內即將到來的會議顯示確切時間的問題。 


- 我們已修正在郵件中插入影像內嵌，然後將郵件儲存為草稿將會重新調整影像大小的問題。


- 我們已修正在編輯主旨之後，導致 NDR 郵件的本文從 Unicode 變更為 ASCII 的問題。


- 我們已修正迷你行事曆中的日期無法針對日本使用者顯示粗體的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正在即時共同撰寫工作階段期間，使用者的目前狀態色彩指示器無法在共同撰寫文件庫中重新整理的問題。


- 我們已修正將 HTML 貼到投影片上的文字區域時，會改為貼上投影片最上方所建立的文字方塊中的問題。


- 我們已修正在 [簡報者檢視畫面] 中選取所有投影片、使用 Alt+Tab 退出 [簡報者檢視畫面] 並返回投影片放映，然後按一下 [結束放映] 時，將導致未處理例外狀況的問題。


### <a name="project"></a>Project

- 修正無法將從 Project 將 PDF/XPS 儲存至 SharePoint 文件庫的問題。


- 修正 URL 以 .com 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。


- 我們已修正 Project 在開啟特定 XML 檔案時可能當機的問題。


- 我們已修正 URL 以 '.com' 結尾時，無法從 Project Web App 在 Project 傳統型用戶端開啟專案的問題。


- 修正問題：如果您貼上具有多個相關性的工作，並不會正確複製所有相關性。


- 修正 [指派資源] 對話方塊中選取的工作與工作面板檢視中所選工作不同的問題。


- 我們已修正當專案摘要工作，或專案 [開始/工作] 欄位變更時，ProjectBeforeTaskChange 事件無法觸發的問題。


- 我們已修正以下問題：如果固定工期的任務已 100% 完成，但未指定 [實際完成日期]，則任務的完成 % 將顯示為低於 100%。

- 我們已修正以下問題：比較基準重設或更新可能會變更時間分段預算成本/工時資源，且比較基準反映不正確的預算值。


- 我們已修正政府社群雲端中的 Project Planner 連結已停用的問題。


- 我們已修正如果文件庫處於新式模式，您無法從 SharePoint 文件庫開啟 Project 檔案的問題。


### <a name="word"></a>Word

- 我們已修正使用 Office 功能區中的 [清除格式設定] 按鈕清除 [註解] 窗格中的格式設定時，無法運作的問題。


- 我們已修正將插入可縮放向量圖形 (SVG) 中的文字插入到 Word、Excel 或 PowerPoint 檔案、儲存並關閉檔案，然後重新開啟檔案後，難以辨識的問題。


- 我們已修正當尺規未顯示時變更表格大小，導致在背景中執行其他應用程式開始閃爍的問題。


- 我們已修正在共同撰寫模式中，註解回覆有時候不會顯示在 [註解] 窗格中，而是顯示在 [修訂] 窗格中的問題。


- 我們已修正在共同撰寫模式期間，當發生合併衝突且使用者已選取放棄變更時，我們不再顯示儲存或捨棄變更選項的問題。


- 我們已修正 HTML 超連結色彩無法正確呈現的問題。


- 我們已修正以下問題：如果 Word 經常開啟的文件清單多於 50 個，然後儲存並開啟文件後，即使該文件沒有進行任何修訂，也會顯示歷程記錄。


- 我們已修正共同撰寫期間的自動儲存問題。


- 我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以 .docx 副檔名和檔案名稱 'WRO0004.docx' 儲存，進而導致文件無法使用。


### <a name="office-suite"></a>Office 套件

- 關閉 Office 檔案時，計時問題可能會導致當機

- 此問題的修正程式是確保服務正確計算新增的產品。 我們已篩選出新增的產品 (確保它們同時存在於新的設定中)，並將它們新增到現有產品發行識別碼的結尾。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-july-09"></a>版本 2006：7 月 09 日
*版本 2006 (組建 13001.20384)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。 [深入了解](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- **建立變數以在公式中使用：** 使用 LET 函數改善效能、可讀性及可組合性。 此函數可讓您在新的或現有的公式中建立命名變數。 [深入了解](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />在[部落格文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看詳細資料

- **Excel 中的鍵盤快速鍵：** Excel 升級的鍵盤快速鍵

### <a name="outlook"></a>Outlook

- **在 Outlook 中使用 [快速投票] 建立投票：** 輕鬆建立投票，收集投票，並查看電子郵件中的結果 [深入瞭解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **將圖片作為電子郵件的一部分傳送時，讓圖片保持高畫質：** 一個新 Outlook 設定，可讓您在隨著電子郵件內容傳送圖片時限制圖片壓縮


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此問題已解決，您應該能成功地將包含身分識別(例如 [自動編號]) 欄位的連結的 SQL 資料表插入到 Access 中。

### <a name="excel"></a>Excel

- 修正當您從帳戶登出時，嘗試建立資料連線時，可能會發生的當機問題。

### <a name="outlook"></a>Outlook

- 解決了當選取安全性對話方塊上的 [儲存] 選項時，導致使用者無法將 OneDrive 外部的 OneDrive 附件儲存至他們的本機電腦的問題。

### <a name="office-suite"></a>Office 套件

- 我們會將新的 AppV51 向後移，以修正先前 AppV51 中的回歸。

- 當您啟用增益集，而登錄 TabProcGrowth 值為 REG_SZ 類型且其值為 "0"時，辦公主機視窗會當機。  這個登錄 TabProcGrowth 值可以在下列4個路徑中的任何一個中： HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER \Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE \Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER \Software\Policies\Microsoft\Internet Explorer\Main 此變更將修正此問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-25"></a>版本 2006：6 月 25 日
*版本 2006 (組建 13001.20266)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="visio"></a>Visio

- **在 Excel 中製作精美的 Visio 圖表：** 根據工作表上的資料，建立流程圖或組織圖。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- This problem is now resolved. Please let the team know if you experience more issues with this process.


### <a name="outlook"></a>Outlook

- 解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。


- 解決導致 [共用行事曆] 改善的使用者查看行事曆失敗的問題。


- 解決導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。


- 解決導致在[建議功能]中尋找功能沒有結果並未留給使用者選項以提交新功能點子的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-18"></a>版本 2006：6 月 18 日
*版本 2006 (組建 13001.20198)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel



- **儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案，我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。 <br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

### <a name="powerpoint"></a>PowerPoint

- **儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案，我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

### <a name="word"></a>Word

- **儲存至 [釘選資料夾]：** 釘選您的資料夾可讓您更輕鬆地儲存 Office 檔案。我們收到意見反應，使用者希望能在新檔案儲存時可以在可用的資料夾上有更多控制權。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。 <br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。

### <a name="outlook"></a>Outlook

- 解決了啟用雲端設定時，按下 Ctrl + 按一下會造成運作停止的問題。

### <a name="project"></a>專案

- 修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-11"></a>版本 2006：6 月 11 日
*版本 2006 (組建 13001.20144)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="powerpoint"></a>PowerPoint

- **Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience. Use your corporate videos from Microsoft Stream to create better presentations.

### <a name="word"></a>Word

- **以向量保留文字：** 現在當您在 Excel、Word 和 PowerPoint 中轉換地圖、圖表和其他 SVG 向量等物件時，您可以保留物件中的文字。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正在使用 OneDrive 時，Excel 偶爾會關閉的問題。

- 我們已修正圖表座標軸自訂值無法正確套用的問題。

- 我們已修正包含多個含有定義名稱的公式會導致儲存檔案時間加長的問題。

- 我們已修正導致印表機名稱在可用印表機清單中重複的問題。

- 我們已修正在使用者刪除合併的欄時，造成執行時間增加的問題。

- 我們已修正因為增益集是以字母順序裝載，而不是以使用者指定的順序載入，而造成出現「因為此活頁簿目前有他人進行參考，而無法關閉」的錯誤訊息的問題。

- 我們已修正管理 Excel 與部分協力廠商輔助技術應用程式之間的字型時發生記憶體損毀的問題。

- 我們已修正在相同活頁簿中按一下加上書簽的超連結會導致活頁簿隱藏的問題。

- 我們已修正某些複製和貼上的圖表連結使用的是映射磁碟機位址，而不是通用位址的問題。

- 我們已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。

- 我們已修正當增益集在工作表中詢問含有 noSelect 鎖定的圖形的主項目目時，Excel 會當機的問題。

- 解決了嘗試將樞紐分析表插入圖表時 Excel 可能會當機的問題。

### <a name="outlook"></a>Outlook

- 我們已修正以下問題：當使用多個不同解析度的監視器時，輸入法編輯器 (IEM) 視窗會覆蓋透過 IME 輸入的文字。

- 我們已修正在撰寫新電子郵件訊息時，檢視範本會導致當機的問題。

- 我們已修正在 Outlook 版本 1911之後，使用者無法使用 Exchange 2010 公用資料夾的問題。

- 我們已修正 Office 功能區中群組行事曆分類按鈕已停用的問題。

- 解決了 Outlook 無法啟用 [資料遺失保護原則] 提示使用 M365 商務版進階方案並為此服務付款的的使用者之問題。

- 已解決導致 Outlook 在某些 Windows 組建上當機的問題。

- 我們已修正使用者無法與來賓使用者共用行事曆的問題。

- 我們已修正使用者看到將午夜臨界值視為全天事件的行事曆專案的問題。

- 我們已修正會導致使用者在高 DPI 監視器上遺失 [線上封存] 摘要的問題。

- 我們已修正當使用者在資料夾之間移動專案時，BeforeItemMove 事件未正確觸發的問題。

- 我們已修正當兩個增益集將按鈕新增到功能區中相同群組時，Outlook 發生當端的問題。

- 我們已修正當處理純文字電子郵件中的超連結時，會導致使用者遇到 Outlook 當機的問題。

- 我們已修正會導致 Outlook 無法剖析使用 RFC2231 編碼的長檔名的問題。

- 我們已修正會導致 Outlook 使用者在使用螢幕閱讀器時遇到間歇性的問題。

- 我們已修正具有衝突連絡人的使用者在 Outlook 中遇到當機的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用表單型驗證開啟伺服器設定的檔案時發生的問題。

- 我們已修正內嵌圖表/活頁簿的 PowerPoint 檔案可能會導致儲存檔案失敗的問題。

- 我們已修正放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。

- 我們已修正使用滑鼠滾輪縮放後，投影片並未居中的問題。

- 我們已修正使用英文 (瑞士) (QWERTZ) 鍵盤時鍵盤快速鍵和拼字檢查無法正常運作的問題。

- 我們已修正使用者已關閉的註解窗格會自動開啟的問題。

- 我們已修正某張投影片的投影片編輯工具會在下一張投影片上重疊的問題。

### <a name="project"></a>Project

- 修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。

- 修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。

- 我們已修正在按一下 [選項] 之後 Project 會當機的問題。

- 我們已修正在刪除母計畫之後，無法刪除或重新指派孤立工作的問題。

### <a name="visio"></a>Visio

- 有已修復的依賴代碼迴歸分析。 現在，影像會在執行于 SharePoint Onprem 上的 Visio 服務中呈現。

### <a name="word"></a>Word

- 我們已修正註解窗格中的時間戳記不是根據系統區域設定時間所建立的問題。

- 已解決在 URL 包含查詢元件時，從自訂檔傳遞 (aspx) 開啟 Word 檔的問題。

- 我們已修正在註解窗格中複製及貼上文字不會顯示的問題。

- 我們已修正註解中的超連結無法正常運作的問題。

- 我們已修正放大和縮小簡報區域會造成縮放選取選框和滑鼠指標之間的間隙的問題。

- 我們已修正網頁應用程式與傳統型應用程式之間的註解未同步處理的問題。

- 我們已修正註解提示泡泡在100% 縮放比例中顯示模糊的問題。

- 我們已修正在空白文件中新增註解卻未執行任何動作的問題。

- 我們已修正無法將 HTML 貼入行事曆的 WordMail 的問題。

- 我們已修正在共同撰寫的會話中回復批註有時會導致 Word 停滯的問題。

- 我們已修正在含有一百個以上專案的檔中插入或更新索引會導致應用程式當機的問題。

- 我們已修正啟用原則 Word 2007 及更新版本的二進位檔案和範本會導致部分共同撰寫案例失敗的問題。

- 我們已修正具有自訂 xml 值的檔案在開啟時速度極度緩慢的問題。

- 我們已修正使用長路徑名稱 (大於32K) 的檔案無法開啟，且未顯示適當的錯誤訊息的問題。

### <a name="office-suite"></a>Office 套件

- 我們已經研究並解決了在作業系統關閉後，透過 InTune 進行的 Office 365 專業增強版部署會暫停的問題。

- 我們已修正 Microsoft Office 的 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。

- 此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-08"></a>版本 2005：6 月 08 日
*版本 2005 (組建 12827.20336)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="powerpoint"></a>PowerPoint

- 我們已修正取代字型對話方塊中，取代字型下拉清單只會顯示系統中安裝的字型，而不是所安裝的字型的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-04"></a>版本 2005：6 月 04 日
*版本 2005 (組建 12827.20320)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **隨時跟上改變！[日期/時間] 延伸資料類型具有更好的精確度。：** 引進新的和改良的資料類型。  為加強與 SQL 的語法相容性，並提高包含日期和時間之記錄的詳細資料和層級，我們正在將 DateTime2 資料類型實施到 Access 中。 這個額外的日期與時間資料類型，將會包含更大的日期範圍 (0001-01-01 到 9999-12-31) ，具有更高的指定時間精準度(以納秒取代秒為單位)，讓您可以提供和執行計算。 若要啟用，請選取 [新增欄位] > [日期與時間延長]。 [深入了解](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a>Excel

- **在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。  如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。 使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。

### <a name="outlook"></a>Outlook

- **可讓您從上一個 Outlook 會話中快速重新開啟專案的選項：** 我們新增了一個可快速重新開啟先前 Outlook 會話專案的選項。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="powerpoint"></a>PowerPoint

- 這可修正使用者在同一檔案中同時有新版和舊版批註，因此觸發批註的升級而當機的問題。


### <a name="office-suite"></a>Office 套件

- 我們透過設定Bing附加預設安裝驗證設定為true默認，並將MSI返回成功視為安裝成功，而解決了 ValidateInstall 失敗率問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-29"></a>版本 2005：5 月 29 日
*版本2005（組建12827.20268）*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新

### <a name="excel"></a>Excel

- **工作表視圖：** 排序/篩選，同時與其他人在 Excel 電腦版共同作業。

### <a name="outlook"></a>Outlook

- **新增至 Outlook 快顯通知的其他按鈕：** [快速動作] 按鈕，現在會於在 Windows 10 上執行 Outlook 時顯示在 Outlook 快顯通知中。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題



### <a name="outlook"></a>Outlook

- 解決了導致 Windows 10 伺服器版本的使用者看到警告防毒軟體狀態：無效的問題。 這個版本的 Windows 支援防毒軟體檢測，但即使已正確安裝防毒軟體，也無法找到防毒軟體。

### <a name="office-suite"></a>Office 套件

- The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero. This change would fix this issue.


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-21"></a>版本 2005：5 月 21 日
*版本 2005 (組建 12827.20210)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。


- 在某些情況下，按一下同一個活頁簿中某個位置的超連結會導致活頁簿被隱藏。


### <a name="outlook"></a>Outlook

- 已解決有回應/轉寄標註的clp審查活動的問題。


- 已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-may-14"></a>版本 2005：5 月 14 日
*版本 2005 (組建 12827.20160)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。

### <a name="powerpoint"></a>PowerPoint

- **不需要簡報導覽裝置：有耳塞式耳機就夠了：** 使用您的 Surface Earbuds 控制 PowerPoint 簡報。 重要：您必須在 Windows 10 的 Surface 音訊應用程式中配對 Surface Earbuds，才能使用手勢來控制簡報。 在此取得 Windows 10 上 Surface 音訊應用程式入門的指示。 [深入了解](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- **[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。

### <a name="word"></a>Word

- **[自動套用] 或 [建議敏感度] 標籤：** Office 可以根據偵測到的敏感性內容來推薦或自動套用靈敏度標籤。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel

- 已增加搭配圖表使用的 [自訂誤差線] 對話方塊上儲存格參照 [編輯] 控制項的大小。

- 修正圖表資料表無法正確呈現日期座標軸中的值的問題。

- 修正使用 [頁面配置] 或 [分頁預覽] 之後無法停用分頁符號的問題。

- 修正隱藏和取消隱藏具有系列資料的欄之後，圖表線條樣式可能會遺失的問題。

- 修正在已篩選清單中插入欄的時間會比預期更長的問題。

- 修正列印時表單控制項的核取方塊縮放的問題。

- 修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。

- 在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。

- 在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。

- 在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。

- 此變更會修正設定格式化的條件 (CF) 資訊無法正確儲存到 XLSB 檔案的問題。

- 這項變更修正了即使 LINEST 函式傳回正確的值，圖表趨勢線的 R 平方值 (在強制 y 截距的情況下) 仍然不正確的問題。

- 此變更修正了自訂圖表趨勢線格式不一定會儲存的問題。

- 當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。

- 修正啟用 [負值以補色顯示] 選項後，可能無法儲存樞紐分析表中的自訂格式設定的問題。

- 修正如果選取 [負值以補色顯示] 選項，可能無法儲存樞紐分析表中單一資料點的自訂格式設定的問題。

- 這項變更修正在 CSV 檔案中上傳 '@' 字元時，會導致將 '@' 字元之後的字串轉換成公式的問題。

- 修正無法正確捨入 SEQUENCE 函數中十進位值的問題。

### <a name="onenote"></a>OneNote

- 修正將分行符號儲存為垂直 Tab 的問題。

### <a name="outlook"></a>Outlook

- 解決會導致使用者無法將個人連絡人群組新增為會議出席者的問題。

- 修正 Office 功能區中群組行事曆分類按鈕已停用的問題。

- 已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。

- 修正企業客戶沒有執行或無法使用群組資料夾的問題，該問題會導致 Outlook 顯示「沒有回應」的訊息。

- 已解決導致使用者在 Outlook 桌面用戶端中按一下非常長的安全連結時，由於截斷而無法載入的問題。

- 修正當與伺服器同步處理時，名稱中包含 DBCS (雙位元組字元集) 字元的 Outlook 資料夾會間斷消失的問題。 為此，必須為 Outlook 設定 IMAP 帳戶，並在地區設定設定為日文的系統上執行。

- 已解決會導致為使用者主要信箱以外的信箱所建立的刪除規則變得無效的問題。

- 已解決在轉寄加密郵件時導致捨棄附件的問題。

- 已解決會導致還有 2 個月時間的會議，無法在排程小幫手中顯示會議主題的問題。

- 已解決會導致使用者在轉寄大型 HTML 郵件時，看到郵件內文截斷的問題。

- 新增透過群組原則強制執行 S/MIME 預設登入設定的功能。

### <a name="powerpoint"></a>PowerPoint

- 已修正問題：如果使用者建立了註解，但未張貼就關閉 [註解] 窗格，然後開啟新視窗、瀏覽多張投影片並關閉視窗，最後再開啟原始簡報中的 [註解] 窗格，將導致無法使用草稿註解。

- 修正了將滑鼠游標移到星號 (*) 符號，但不會顯示上一次更新文件的日期和使用者姓名。

### <a name="project"></a>Project

- 在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。

- 修正變更連結至 SharePoint 工作清單之專案的面板狀態欄位時，Project 可能當機的問題。

- 修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。

- 修正如果 Project 連線至 Project Web App，且小數分隔符號是逗號，當新增延遲時，TaskDependencies Add 方法會失敗的問題。


### <a name="word"></a>Word

- 修正在 [共同作業] 模式時，在文件中插入註解並不總是成功的問題。

- 此變更修正在按一下 @ 提及時，[人員卡片] 會閃動的問題。

- Enabling the option "Show bookmarks" would not display bookmarks. This has been fixed.

- Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments. Cancelling the prompt would close the document rather than leaving it open.

- 我們已修正複製及貼上標題的問題。

- 修正翻譯已張貼註解將導致「插入已翻譯的文字失敗」錯誤的問題。

- 此變更修正了下列問題：如果已啟用 [顯示功能變數代碼，而非其值] 選項，則含有超連結的文字可能不會顯示。

- In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view. This has been fixed.

- 我們已修正一個問題，當嘗試使用新名稱儲存包含巨集的檔案時，無論使用者輸入什麼名稱，都會導致該檔案以.docx 副檔名和檔案名稱 WRO0004.docx 儲存，進而導致文件無法使用。

### <a name="office-suite"></a>Office 套件

- 當使用者收到將他們移至 Teams Only 的原則時，他們仍然可以使用商務版 Skype Outlook 增益集來排程會議。  在此更新之後，當客戶端讀取指示用戶為 Teams Only 的策略並進入僅限會議加入模式後，您將不再能用商務版 Skype 安排會議。  此外，如果商務版 Skype Outlook 增益集發現商務版 Skype 用戶端處於 [僅限會議加入] 模式，就無法自行啟動。

- 此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-11"></a>版本 2004：5 月 11 日
*版本 2004 (組建 12730.20270)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。

### <a name="outlook"></a>Outlook

- **電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。 您可以變更權限，讓所有收件者都能存取。 [深入了解](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br />在[部落格文章](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)中查看詳細資料

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。

### <a name="powerpoint"></a>PowerPoint

- **Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.  [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a>Word

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決在顯示快顯通知時，使用者遇到當機的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-04"></a>版本 2004：5 月 4 日
*版本 2004 (組建 12730.20250)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever. [Learn more](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows. [Learn more](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="office-suite"></a>Office 套件

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a>版本 2004：4 月 29 日
*版本 2004 (組建 12730.20236)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決導致 Outlook 在某些 Windows 組建上當機的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-25"></a>版本 2004：4 月 25 日
*版本 2004 (組建 12730.20206)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。

### <a name="project"></a>Project

- 修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。


### <a name="office-suite"></a>Office 套件

- 此修正可解決同時防止限制存取和保護設有密碼之檔案的錯誤。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-21"></a>版本 2004：4 月 21 日
版本 2004 (組建 12730.20182)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決導致資料夾窗格寬度意外變更的問題。

- 解決導致使用者在退出 Outlook 時遇到掛斷的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-15"></a>版本 2004：4 月 15 日
*版本 2004 (組建 12730.20150)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Facebook 連接器支援即將結束：** 於 2020 年 4 月起，Excel 就不再支援使用 Facebook 連接器的外部資料連線。

### <a name="outlook"></a>Outlook

- **New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful? Now you can turn it off if you prefer.

### <a name="powerpoint"></a>PowerPoint

- **在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。

### <a name="word"></a>Word

- **標註私人複本：** 製作共用文件的私人複本，以建立只有您本人能夠看到的手寫筆記。 若要開始使用，請移至 [檢視] > [建立私人複本]。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 修正工作窗格中表格的重新調整及重新整理問題。

- 修正國際版 Access 在使用者介面中顯示英文字串的問題。

### <a name="excel"></a>Excel

- 修正在工作表上選取儲存格範圍會導致只選取單一儲存格的問題。

- 在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。

- 修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。

- 在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函式中運作。

- 修正使用者在以程式設計方式編輯大量儲存格範圍時可能遇到的效能問題。

- 修正以日文環境開啟 CSV 檔案時發生的效能問題。

- 修正插入使用者定義的圖表範本來作為預設值會導致其儲存為直條圖的問題。

- 修正當基礎資料儲存格沒有標題時，圖表上的資料標籤會以空白顯示的問題。

- 修正在為含有 X 軸範圍的圖表縮減大小時，可能會導致 Excel 停止回應的問題。

- 修正已啟用 R1C1 儲存格參照且正在共同撰寫/共用的 Excel 工作表，在將游標移到 [使用者目前狀態] 圖示上方時不會以 R1C1 模式顯示作用中儲存格的問題。

- 此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。

### <a name="outlook"></a>Outlook

- 此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。

- 此變更修正了電子郵件草稿最新變更未更新的問題。

- 已修正在檔案上按一下滑鼠右鍵並使用「傳送到」功能無法運作的問題。

- 已解決會導致代理人在不同機器上所看到的共用信箱有不同資料夾階層的問題。

- 已解決會導致類別有時候會從電子郵件訊息中消失的問題。

- 已解決在變更機器上的時區時，會導致某些提醒無法觸發的問題。

- 已解決在嘗試檢視組織表單的屬性時，會導致使用者遇到當機的問題。

- 已修正如果使用者有自訂的 [通訊錄] 搜尋路徑，則 Outlook 的名稱解析範圍會限制為自訂路徑，而不是包括全域通訊清單 (GAL) 的問題。

- 解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。

- 解決了以下問題：當使用者從檢查程式視窗回覆受到數位版權管理的郵件，卻沒有所回覆郵件的擁有者權限時，使用者會無法新增簽名。

- 解決了以下問題：使用者無法從網頁位置將其他附件新增到先前建立的會議。

- 解決將附件新增至郵件或從郵件拖放 (與透過功能表相對) 來儲存附件時，導致檔案的「上次修改」日期更新的問題。

- 解決會導致在展開的尋找窗格中按一下 Enter 時無法開始搜尋，而是會要求使用者按一下 [搜尋] 按鈕的問題。

- 已修正在一組傳回的搜尋結果中，依類別結果排序不會顯示類別色彩的問題。

- 修正將 [如果有，顯示使用者的照片] 選項停用時，搜尋不會顯示有關使用者的任何資訊的問題。


### <a name="powerpoint"></a>PowerPoint

- 此變更修正了會導致包含 emojis 的 PowerPoint 檔案在儲存時發生失敗的錯誤。

- 此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。

- 我們已修正將文字從 Excel 複製到 PowerPoint 時可能會導致其格式設定發生變更的問題。

- 此變更修正了使用 [全字拼寫須相符] 來尋找特殊字元時，不一定能正常運作的問題。

### <a name="project"></a>Project

- 修正無法正確計算摘要工作日期的問題。

- 修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。

- 修正當使用者按一下 [排程群組] 內 [工作] 功能區中的 [停用] 按鈕時，不會觸發 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) 事件的問題。

- 如果您在 [表單類型] 檢視中設定前置任務或後置任務詳細資訊，則 ProjectBeforeTaskChange Visual Basic Applications (VBA) 事件不會一律擷取變更。 例如，如果刪除了某個相依性，並在表單上按一下 [確定]，則不會觸發該事件。 修正此問題。

- 修正在進行變更 (例如日期變更) 之後，實際工作成本 (ACWP) 的最新值不會顯示的問題。

- 修正使用「最近使用」(MRU) 功能表開啟專案時，會使用 [讀取/寫入] 存取權開啟專案的問題。

- 這項變更修正了如果您建立包含開始日期和時間 (但無工期) 的手動工作，則時間表上的時間顯示不正確的問題。

- 修正使用回曆列印時間表時，會導致列印檢視中略過或重複一個月的問題。

- 這項變更解決了在團隊規劃中使用 GDI 物件時，可能導致 GDI 物件分配過多並產生記憶體不足的問題。

- 修正以下問題：如果執行 'CustomFieldValueListGetItem' 且自訂欄位的查閱資料表不存在，系統會建立一個不應建立的空白查閱資料表。

- 在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件

- 修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。

### <a name="word"></a>Word

- 此變更修正了將游標懸停在提示上並不會醒目提示其卡片的問題。

- 此變更修正了以下問題：從 [檢視] 功能表選取多個頁面時，其中的 [註解] 窗格會顯示為空白。

- 已修正張貼留言功能停用的問題。

- 此變更修正了使用套索選取工具時，群組圖形中的文字會暫時消失的問題。

- 此變更解決了處理格式錯誤或無效通訊協定資訊影像時所導致的延遲問題。

- 此變更修正了在 PowerPoint 或 Word 中呈現內嵌為 OLE 物件的舊版 Excel 圖表時可能不會永遠顯示圖表標題的問題。

- 這項變更解決了帳戶管理員不會分派訊息而導致協力廠商應用程式懸置的問題。

- 此變更修正了在雙頁檢視中建立註解時，註解錨點不一定會顯示的問題。

- 修正輸入或編輯備註然後使用 Ctrl+A 時，會導致選取畫布中的文字，而不只是選取備註卡片內文字的問題。

- 修正如果段落的樣式是連結至清單的樣式上階，則該清單的編號可能會遺失的問題。

- 這項變更修正了目錄會使用文件中未包含的標題樣式進行更新的問題。

- 我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。

- 我們已修正將兩份文件合併成一份文件時的問題。

- 已修正在寄送文件時，儲存在 Word 文件中的數位簽章會被刪除的問題。

- 修正標示的修訂若與方程式有關，在儲存檔案時可能會導致失敗的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-14"></a>版本 2003：4 月 14 日
*版本 2003 (組建 12624.20466)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

- 各種錯誤和效能修正。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-april-09"></a>版本 2003：4 月 9 日
*版本 2003 (組建 12624.20442)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **M365 進階版內容選擇器：** 讓您的文件栩栩如生！ 探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="outlook"></a>Outlook

- **M365 進階版內容選擇器：** 讓您的文件栩栩如生！ 探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="powerpoint"></a>PowerPoint

- **M365 進階版內容選擇器：** 讓您的文件栩栩如生！ 探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="word"></a>Word

- **M365 進階版內容選擇器：** 讓您的文件栩栩如生！ 探索數千個免費圖庫影像、圖示和貼圖 [深入了解](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-03"></a>版本 2003：4 月 3 日
*版本 2003 (組建 12624.20410)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 使用 VBA 應用程式的 Application.Evaluate 在某些情況下，對使用者定義的函數無法運作。

### <a name="outlook"></a>Outlook

- 解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。

### <a name="project"></a>Project

- 在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChangeevent。

### <a name="word"></a>Word

- 解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a>版本 2003：3 月 31 日
*版本 2003 (組建 12624.20382)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **「新增資料表」工作窗格：** Access 的全新「新增資料表」工作窗格終於推出！ 這項功能可讓您輕鬆選取/多重選取要在查詢視窗中新增/移除的資料表，而不需要瀏覽至查詢和關聯視圖的「顯示資料表」對話方塊。 這也包含新的「連結」索引標籤，可顯示連結的資料表、可篩選目前清單的搜尋方塊、「拖放」行為及更多功能！


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="project"></a>Project

- 修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-25"></a>版本 2003：3 月 25 日
*版本 2003 (組建 12624.20320)*

- 各種錯誤和效能修正。

## <a name="version-2003-march-23"></a>版本 2003：3 月 23 日
*版本 2003 (組建 12624.20296)*

- 各種錯誤和效能修正。

## <a name="version-2003-march-21"></a>版本 2003：3 月 21 日
*版本 2003 (組建 12624.20276)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。 將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。

- **行事曆新版視覺效果：** 去年，我們提供了全新的郵件體驗，而今年將為您帶來嶄新的行事曆！ 這些更新是全新但令人熟悉的，身為經驗豐富的 Outlook 使用者的您，可以立即上手並更具生產力。

### <a name="powerpoint"></a>PowerPoint

- **在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-march-16"></a>版本 2003：3 月 16 日
*版本 2003 (組建 12624.20224)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。

### <a name="outlook"></a>Outlook

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。

### <a name="powerpoint"></a>PowerPoint

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。

### <a name="word"></a>Word

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。

### <a name="office-suite"></a>Office 套件

- **索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。 只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已解決當來源活頁簿關閉時，外部連結無法在填滿時更新的問題。

### <a name="outlook"></a>Outlook

- 已解決導致使用者在工作管理員中看到 Outlook 處理序延遲的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-10"></a>版本 2003：3 月 10 日
*版本 2003 (組建 12624.20176)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)
### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel
- **Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions. [Learn more](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a>PowerPoint
- **Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions. [Learn more](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a>Word
- **Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions. [Learn more](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。

- 修正使用者在重新命名樞紐分析表度量值時可能遇到的問題。

- 修正交叉分析篩選器中的文字在預覽列印中無法正確縮放的問題。

- 已修正使用者在使用 VBA 巨集清除範圍內容時可能遇到的效能問題。

- 修正當使用者執行與功能區互動的巨集時，導致 UI 快閃的問題。

- 修正當檔案中的第一個字為 TABLE 時，CSV 檔案載入錯誤的問題。

- 已修正當您在兩個具有不同縮放比例的活頁簿之間切換時，使用者可能遇到的當機問題。

- 修正 CUBEVALUE 函數有時會傳回不正確結果的問題。

- 此變更可解決物件模型中的執行階段錯誤，以及當增益集要求的文件/工作表上的主機項目包含具有 noSelect 鎖定的圖形時，應用程式 (Excel、Word) 的潛在當機。

- 解決導致 Outlook 使用者在同步處理設定時發生當機的問題。



### <a name="outlook"></a>Outlook

- 修正使用 Outlook Web Access 建立規則時不會保存到 Exchange 伺服器，並導致衝突的問題。

- 解決導致 Outlook 使用者在同步處理設定時發生當機的問題。

- 修正 Outlook 在深色模式中不會在 [寄件者:] 欄位中顯示下拉式清單的問題。

- 解決即使已關閉記錄，在某些情況下仍導致 Outlook 異常產生記錄輸出的問題。

- 已解決當持續整夜執行 Outlook 時，導致使用者無法開啟公用資料夾訊息的問題。

- 已修正在新增 Gmail 帳戶的驗證工作流程中，[權限] 頁面上的 [允許] 和 [拒絕] 按鈕停用的爭用情況。

- 解決導致使用者無法存取 [空閒/忙碌選項] 行事曆權限對話方塊的問題。

- 修正開啟某些傳送自不同時區的週期性會議執行個體時，可能導致出現警示：「很抱歉，開啟此項目時發生問題」的問題。

- 已解決從該郵件拖放附件後造成使用者無法重新開啟 .msg 檔案的問題。

- 修正從 Outlook 上傳檔案附件到 OneDrive 後，造成包含括號之附件名稱的檔案名稱被變更。

- 解決在其他應用程式中開啟某個檔案時，導致使用者無法透過檔案總管將該檔案附加至郵件訊息的問題。

- 解決導致 Outlook 使用者在同步處理設定時發生當機的問題。

### <a name="powerpoint"></a>PowerPoint

- 修正將滑鼠移至縮圖上時，建議的縮圖閃動的問題。 在某些情況下，這可能會導致 PowerPoint 當機。

- 修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。

- 修正儲存包含 Excel 圖表的 PowerPoint 或 Word 文件會導致失敗的問題。



### <a name="project"></a>Project

- 修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。

- 修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。

- 修正無法正確計算摘要工作日期的問題。

### <a name="visio"></a>Visio

- Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop. It has now been fixed.

- 在 2016 之前版本中匯入的點陣圖，由於某些安全性檢查而未呈現。 我們已在 Visio 訂閱中修正此問題。

### <a name="word"></a>Word

- 修正當滑鼠指標暫留在註解卡片上方時，未醒目提示註解卡片的問題。

- 修正按 Tab 鍵導覽註解卡片時，註解編輯方塊上的焦點無法顯示的問題。

- 修正 [檔案]\[選項] 對話方塊上的 [確定] 按鈕顯示為灰色停用狀態，但功能並未受影響的外觀問題。

- During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag. This issue has been fixed.

- 在方程式中插入控制項 (例如文字內容控制項)，然後儲存再開啟檔案，便會導致內容無法讀取的錯誤。

- 修正將先前使用密碼保護的檔案儲存到雲端儲存空間無法運作的問題。

- 修正受保護無法編輯之文件的比較功能問題。




### <a name="office-suite"></a>Office 套件

- 當您將 Multichoice/Lookup/Managed-metadata 屬性與 Word/Excel/PowerPoint 文件一起使用並儲存至 SharePoint 文件庫時，這些屬性之前限制為 255 個字元。 當這些屬性超過 255 個字元時，這類文件就無法儲存。 在此變更中，此限制已增加到 2048 個字元。

- 修正 Word/Excel/PowerPoint 中的使用者主體名稱 (UPN) 不再區分大小寫，導致在 SharePoint 上使用檔案時較少發生失敗的問題。

- 修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-05"></a>版本 2002：3 月 5 日
*版本 2002 (組建 12527.20278)*

- 各種錯誤和效能修正。


## <a name="version-2002-march-04"></a>版本 2002：3 月 4 日
*版本 2002 (組建 12527.20264)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="project"></a>Project
- 修正無法正確計算摘要工作日期的問題。


### <a name="office-suite"></a>Office 套件
- 修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-01"></a>版本 2002：3 月 1 日
*版本 2002 (組建 12527.20242)*

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決導致協力廠商應用程式無法傳送電子郵件的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-24"></a>版本 2002：2 月 24 日
*版本 2002 (組建 12527.20194)*

- 各種錯誤和效能修正。

## <a name="version-2002-february-22"></a>版本 2002：2 月 22 日
*版本 2002 (組建 12527.20186)*

- 各種錯誤和效能修正。

## <a name="version-2002-february-21"></a>版本 2002：2 月 21 日
*版本 2002 (組建 12527.20174)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。 在 SQL 檢視中搜尋及取代文字。 在 [關聯圖] 視窗中選取多個資料表。

### <a name="outlook"></a>Outlook

- **New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with? Outlook now detects this and helps you get connected.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正 CUBEVALUE 函數有時會傳回不正確結果的問題。


### <a name="outlook"></a>Outlook

- 解決導致會議的位置欄位中的逗號變成分號的問題。


- 解決在多個視窗中檢視相同項目時可能會導致當機的問題。


- 解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。&nbsp;


- 解決會導致使用黑色佈景主題的使用者看到 [從]&quot;&quot; 下拉式功能表在白色背景上顯示白色文字的問題。


- 此變更會還原在郵件標頭中檢視多行主旨的功能。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-18"></a>版本 2002：2 月 18 日
*版本 2002 (組建 12527.20138)*

## <a name="version-2002-february-11"></a>版本 2002：2 月 11 日
*版本 2002 (組建 12527.20092)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。 您拖曳的郵件將會與所有群組成員共用。

### <a name="word"></a>Word

- **其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。

### <a name="office-suite"></a>Office 套件

- **更清楚的狀態列圖示：** 狀態列圖示現在更容易查看。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- Access 範本應不再導致資料庫中的附件欄出現故障。 個體化範本後，您現在應該可以將附件欄新增至資料庫。

- 此更新會修正使用 ADODB 的問題。 VB 程式碼中的記錄器物件可能會不正確地報告錯誤。

- 此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。


### <a name="excel"></a>Excel

- 修正未顯示操作功能表中的註解命令的問題。


- 修正以下問題：將文字轉換成具有溢出陣列之儲存格的欄時，某些使用者發生當機。


- 修正使用「資料剖析」搭配動態陣列時，Excel 會當機的問題。

### <a name="outlook"></a>Outlook

- 修正以月檢視在行事曆中捲動時，無法顯示之前的行事曆活動的問題。

- 儲存在左側瀏覽窗格 [我的最愛] 的資料夾可能會間歇性消失。


- 已解決導致使用者在指定無效寄件者地址時發生當機的問題。


- 已解決導致在某些情況下無法使用相關選項來停用標幟項目醒目提示的問題。

- 已解決導致使用者在取消帳戶設定時發生當機的問題。


- 修正根據保留原則到期的電子郵件會顯示兩個標籤的問題。 其中一個顯示郵件將在一天內過期，另一個則顯示將在兩天內到期。


- 已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正使用 PowerPoint 筆跡動畫時，無法完整轉譯或跳過的問題。

- 修正關閉檔案之後，如果有任何事件處理常式正在執行，PowerPoint 就不會立即將它從 [簡報] 集合中移除的問題。 因此，物件模型報告的開啟中簡報數目會不正確，且會防止關閉 PowerPoint。


- 修正具有深色螢光筆色彩的白色文字，在灰階中會以黑色列印的螢光筆問題。


### <a name="project"></a>Project

- 修正以下問題：固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成。


### <a name="word"></a>Word

- 更新和瀏覽目錄時，有時可能會在文件上顯示灰色區域的問題。


- 修正在已撰寫註解但未張貼，且使用者嘗試儲存檔案的情況下，使用 [瀏覽] 來儲存檔案沒有作用的問題。


- 已修正在註解卡片之間來回切換時，有時會顯示一開始選取的註解，並將某選取範圍醒目提示的問題。


- 修正在編輯備註之後將文字設為斜體然後再張貼，斜體格式設定遺失的問題。


- 修正在具有「反轉」頁面色彩的閱讀模式中，備註提示未顯示的問題。


- 修正共同撰寫文件時，可能不會保留根註解的草稿版本的問題。


- 將 SlideTrack 啟用且 [註解] 窗格關閉時，Ctrl+Alt+M 可能無法開啟 [註解] 窗格的問題。


- 修正在表格中新增 @提及時可能發生錯誤訊息：「文件中的表格已經毀損」的問題。


- 修正備註內容功能表中的備註命令 (編輯備註、回覆備註、刪除備註、解決備註) 未顯示的問題。


### <a name="office-suite"></a>Office 套件

- 解決可能導致挪威耐諾斯克 (nn-no) 校訂工具套件安裝不正確的問題。


- 此變更解決使用 Intel Integrated GPU 的圖形配接卡報告問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)
