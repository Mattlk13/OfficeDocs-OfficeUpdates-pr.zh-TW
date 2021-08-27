---
title: 目前通道版本的版本資訊
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 Microsoft 365 Apps 每月通道版本的版本資訊
ms.openlocfilehash: fce8b2b1e9e28a6dba280ddc64a09cae60edd11d
ms.sourcegitcommit: 5edddd5222e10c8516ab51425e4a3551f0bc7186
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/26/2021
ms.locfileid: "58541650"
---
# <a name="release-notes-for-current-channel"></a>目前通道的版本資訊

這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含在 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的目前通道更新。

 > [!NOTE]
>
>- 我們通常會在一段時間對「目前」通道推出功能 (有時甚至推出修正程式)。  如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。 [深入了解](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- Microsoft Teams 功能可能會與最新的目前通道中發行的功能不同，因為後者的發行頻率較高。




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2108-august-25"></a>版本 2108: 8 月 25 日
*版本 2108 (組建 14326.20238)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **開啟共用行事曆改良功能：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。 開啟預覽，以更快速且更可靠地更新共用行事曆。<br />在[部落格文章](https://insider.office.com/zh-tw/blog/shared-calendars-improvements-in-outlook-for-windows)中查看詳細資料

### <a name="teams"></a>Teams

- **分組討論區預先會議室的建立和參與者指派:** 介紹召集人在會議開始之前，執行分組討論區設定和參與者指派的功能。

- **Teams 會議之其他語言的 [即時輔助字幕]：** 以其中一種支援的語言所召開的會議現在會受到即時輔助字幕的支援。 我們已從只提供英語 (US)，擴充為包含英文 (加拿大)、英文 (印度)、英文 (英國)、英文 (澳大利亞)、英文 (國際)、Deutsch (Deutschland)、Português (巴西)、Nederlands (Nederland)、Nederlands (比利時)、Français (法國)、Español (España, alfabetización internacional)、日本語 (日本)、Français (法國)、中文 (粵語 (傳統中文))、中文 (簡體中文)、印度文 (印度)、義大利文 (義大利)、韓文 (韓國)、西班牙文 (墨西哥)、瑞典文 (瑞典)、波蘭文 (波蘭)、阿拉伯文 (阿拉伯聯合大公國)、阿拉伯文 (沙烏地阿拉伯)。

- **將 Teams 會議串流至自訂 RTMP 端點：** 串流流讓貴組織擴展您的連絡範圍，並提供會議參與者更多會議選項。 當您啟用串流時，召集人可以透過提供即時訊息協定 (RTMP) URL 及 Teams 中內建 [自訂串流] 應用程式的金鑰，將會議和網路研討會串流送至外部端點。

- **在桌面和行動裝置之間轉接通話：** Teams 通話參與者很快就可以轉接 Teams 裝置間進行中的一對一 Teams VoIP 通話、PSTN 通話或群組通話，亦即從您的桌面用戶端轉接到行動裝置用戶端，或到其他桌面用戶端。 除此之外，使用者也可以將另一部裝置隨附於其通話加以新增。 此訊息會與 Microsoft 365 藍圖識別碼 68776 相關聯。

- **透過 AJA 或 Blackmagic 設計硬體將視訊串流送出：** 隔離的視訊串流可以透過 AJA 和 Blackmagic Design 硬體裝置從 Teams 會議送出。

- **[分組討論區] 強制回應視窗中的新指派體驗：** 參與者指派的增強型 UX。 這包括排序參與者與會議室，以及對會議室執行多重選項和指派等新功能。

- **Teams 即時活動的 Peer5 eCDN 支援：** 很快的您就可以使用 Peer5 做為 eCDN 提供者，以符合 Teams 即時活動網路的需求。

- **GCC 雲端之 Teams 會議 [即時文字記錄] 中的發言者屬性：** GCC 雲端中的 Teams 會議現在具有屬於表達發言者的即時文字記錄表達。

- **核准 - 循序准者支援：** 要求者現在可切換循序核准，以指定要求的核准順序。

- **從 PowerPoint 到搭配 Microsoft 365 Apps 商務版授權使用 Teams 進行簡報：** 透過 Teams 的 PowerPoint Live 直接從 PowerPoint 應用程式在會議中簡報投影片功能，現在已擴充為到可搭配商務用 Microsoft 365 Apps 授權使用。

- **Teams 會議的內嵌 CART 輔助字幕支援：** Teams 會議現在支援整合即時輔助字幕提供者和 CART 作者 (通訊存取即時文字記錄)，讓利用 CART 輔助字幕的使用者可以在會議進行相同的視窗中檢視輔助字幕。

- **Citrix 的雙音多頻訊號：** Citrix 客戶 VDI 上的 Teams DTMF。適用於 Teams 的雙音多頻訊號 (DTMF) 現在可供 Citrix VDI 上的使用者使用。  之前，當 Citrix VDI 使用者使用撥入號碼撥入會議時，通話雖已連接，但您會因為未送出 DTMF 音調而未獲准加入會議。 現在，當同一位使用者輸入會議識別碼時，DTMF 會識別輸入的識別碼，並准許使用者加入會議。

- **聊天失敗時的錯誤畫面：** 萬一會議期間無法呈現聊天，使用者會看到聊天錯誤畫面。

- **教育學習管理系統 (LMS) 的 Microsoft Teams 會議 LTI 應用程式：** Microsoft Teams 會議是 LTI 應用程式，可協助教育者和學生輕鬆地將 Teams 會議納入其 LMS 課程。 使用者可以檢視過去與即將到來的會議、排程個別或週期性會議，以及加入與課程相關的 Teams 會議，通通在其 LMS 內即可做到。

- **在一起模式擴充性：** 擴充了在一起模式功能

- **Teams 教育版簡化的課程團隊瀏覽：** 從主要課程團隊瀏覽中更輕鬆地存取 [作業]、[成績]、[課程筆記本] 和 [深入解析]。

- **開始錄製也會啟動 [即時文字記錄]：** 假設同時啟用錄製和原則設定，開啟錄製也會啟動即時文字記錄。

- **DOD 中 [錯過活動的電子郵件]：** 錯過活動的電子郵件可讓使用者全面掌握 Microsoft 團隊。 當使用者不在 Microsoft 團隊且尚未檢閱其通知時，就會產生錯過活動的電子郵件。 使用者可以移至 [設定] -> [通知] -> [選擇頻率] 來選擇接收 [錯過活動的電子郵件]。

- **[搜尋自動建議] 中的熱門點閱：** 熱門點閱是搜尋中自動建議結果頂端的新區段，使用者可以在此查看所有人員、聊天、檔案等最相關的結果。 這項功能會改善探索，並縮短搜尋時間。

- **Teams 應用程式的 [管理裝置權限]：** 個人化權限以在每個應用程式內使用相機、位置及其他功能。

- **未排程 Teams 會議中的 [即時文字記錄]：** 現在 [即時文字記錄] 會支援未排程/臨時的 Teams 會議。

- **Teams 頻道會議中的 [即時文字記錄]：**[即時文字記錄] 現在會支援 Teams 中的頻道會議。

- **網路版 Teams 會議中的 [即時輔助字幕]：** Teams 會議的 Web 使用者現可使用 [即時輔助字幕]。

- **Teams 會議中的報告者與並排模式：** 現在您可以出現在內容旁邊，以提供更吸引人的簡報和消費體驗

- **Teams 會議的內嵌 CART 輔助字幕支援：** Teams 會議現在支援整合即時輔助字幕提供者和 CART 作者 (通訊存取即時文字記錄)，讓利用 CART 輔助字幕的使用者可以在會議進行相同的視窗中檢視輔助字幕。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 已修正導致放入查詢設計或系統關聯性視窗的資料表會出現在與將其放入位置不同地點的錯誤。


- 已修正嘗試使用來自非 Office 應用程式的 DAO API 時，會停止運作，並顯示「作業系統目前未設定為執行此應用程式」的錯誤。


- 我們已修復此問題，現在會啟用 Outlook 增益集的啟動事件。


### <a name="excel"></a>Excel

- 我們已修正某些語言中的 [檔案] 索引標籤文字遭截斷的問題。


- 我們已修正從 PowerPivot 視窗內連接到資料來源無法運作的問題。


- 我們已修正 Analysis ToolPak 增益集無法與特定 [自動化安全性] 設定一起使用的問題。


- 我們已修正同時有多個 Office 應用程式執行時，會導致 Office 應用程式停止回應的問題。  這也會修正由於回應問題而引起之整個系統的其他穩定性問題。


- 我們已修正導致樞紐分析表中的日期欄位分組錯誤的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致使用者能夠下載受保護的附件的問題。


- 我們已修正使用 Outlook 撰寫電子郵件時，應用程式停止運作的問題。


- 我們已修正 Outlook 開機後，應用程式不久後停止回應的問題。


- 我們已修正帳戶的 UPN/SMTP 名稱變更之後，電子郵件簽名會遺失的問題。


- 已修正僅對簽章內容的變更不會在雲端式設定中更新的問題。


- 已修正導致使用者能夠下載受保護的語音信箱訊息的問題。


- 已修正以 ICAL 轉送一些大型或持續很久的週期性會議時所發生的錯誤。


- 已修正會議項目取消表單會出現，而不是預期的編輯表單的問題。


- 我們已修正導致應用程式在使用 Outlook 時停止回應的問題。


- 我們已修正在 Outlook 開機後，使用具有多個帳戶的設定檔導致網路活動增加的錯誤。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 Word 存檔時，所花時間超過預期的問題。


### <a name="skype"></a>Skype

- 我們已修復在交談視窗中影片共用預覽會意外關閉的問題。


### <a name="word"></a>Word

- 已修正當使用 [此裝置] 選項編輯與新增圖片相關之連絡人的問題。


- 我們已修正插入線上影片按鈕被停用的問題。


- 我們已修正無法關閉「繼續」區段中任何編輯器選項的錯誤。


- 我們已修正非預設功能區設定可能導致樣式庫無法運作的問題。


- 我們已修正 Word 存檔時，所花時間超過預期的問題。


- 我們已修正同時有多個 Office 應用程式執行時，會導致 Office 應用程式停止回應的問題。  這也會修正由於回應問題而引起之整個系統的其他穩定性問題。



### <a name="office-suite"></a>Office 套件

- 修正 Outlook 中的自訂 VSTO 控制項在開啟和切換多個視窗和視圖之後停止工作的錯誤。


- 已修正使用觸控或觸控板在 PPT 投影片中捲動縮圖視圖的相關問題。


- 我們已修正使用某些 Web 增益集後，某些文件無法載入的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2107-august-10"></a>版本 2107: 8 月 10 日
*版本 2107 (組建 14228.20250)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正嘗試使用來自非 Office 應用程式的 DAO API 時，會停止回應並顯示「作業系統目前未配置成執行此應用程式」的問題。


- 在某些客戶設定中，我們發現文件從 Office 匯出為 PDF 或 XPS 格式可能會因為最近的更新而停止回應。此更新修正了這些回歸，並重新啟用了匯出為這些格式的功能。


### <a name="excel"></a>Excel

- 我們已修正可能造成某些連結 Dynamics 資料表停止回應的問題。


- 在某些客戶設定中，我們發現文件從 Office 匯出為 PDF 或 XPS 格式可能會因為最近的更新而停止回應。此更新修正了這些回歸，並重新啟用了匯出為這些格式的功能。


### <a name="powerpoint"></a>PowerPoint

- 在某些客戶設定中，我們發現文件從 Office 匯出為 PDF 或 XPS 格式可能會因為最近的更新而停止回應。此更新修正了這些回歸，並重新啟用了匯出為這些格式的功能。


### <a name="word"></a>Word

- 在某些客戶設定中，我們發現文件從 Office 匯出為 PDF 或 XPS 格式可能會因為最近的更新而停止回應。此更新修正了這些回歸，並重新啟用了匯出為這些格式的功能。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2107-august-03"></a>版本 2017：8 月 3 日
*版本 2107 (組建 14228.20226)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致在 SendFromAliasEnabled 設定為 True 的組織中，由不同使用者重新傳送的電子郵件會顯示為由原始寄件者傳送的問題。


- 我們已修正當會議開始與會議結束在不同的日期時，導致使用者在結束會議時間下拉式清單中看到重複時間項目的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2107-july-26"></a>版本 2107：7 月 26 日
*版本 2107 (組建 14228.20204)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **Microsoft 搜尋支援的撰寫 (收件者/副本/密件副本) 建議**：將人員新增至收件者/副本行，現在會由 Microsoft 搜尋提供支援。

- **在干擾較少的情況下閱讀訊息：** 開啟沈浸式閱讀程式，以自訂文字間距、頁面色彩、欄寬和行聚焦，讓您更輕鬆地專注於訊息。

### <a name="powerpoint"></a>PowerPoint

- **在簡報中新增 Flipgrid 影片：** PowerPoint 現在支援 Flipgrid 視訊與其他視訊類型。 [深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正如果 Application.DisplayAlerts 設定為 True，就無法從 VBA 開啟受 DRM 保護的活頁簿的問題。


### <a name="outlook"></a>Outlook

- 我們已修正在載入收集診斷資料時，導致某些使用者遇到意外關閉的問題。


- 我們已修正在從 PST 重新傳送郵件時，導致由 [重新傳送此郵件] 選項所產生之訊息的修改會在傳送時遺失的問題。


- 我們已修正在執行搜尋時，導致某些使用者遇到意外關閉的問題。


- 我們已修正當設定檔中出現未完整設定的帳戶時，造成雲端設定使用者遇到意外關閉的問題。


- 我們已修正導致共用日曆改進功能的使用者在 Outlook 重新開機之前，無法顯示新加入的共用日曆的問題。


### <a name="visio"></a>Visio

- 我們已修正使用者能夠順暢地存取檔案，而不需要遇到任何意外關閉的問題。


### <a name="word"></a>Word

- 已修正 Word 畫布旁的註解卡片大小不正確的問題。


- 已修正在受密碼保護的 DOCX 檔案上維護引文的「最新清單」的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2106-july-20"></a>版本 2106：7 月 20 日
*版本 2106 (組建 14131.20332)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正在載入收集診斷資料時，導致某些使用者遇到意外關閉的問題。


- 我們已修正在從 PST 重新傳送郵件時，導致由 [重新傳送此郵件] 選項所產生之訊息的修改會在傳送時遺失的問題。


- 我們已修正當設定檔中出現未完整設定的帳戶時，造成雲端設定使用者遇到意外關閉的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2106-july-13"></a>版本 2106：7 月 13 日
*版本 2106 (組建 14131.20320)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正導致某些使用者在擷取服務提供的搜尋建議時遇到意外關閉的問題。


- 我們已修正導致雲端設定在發生衝突時，漫遊設定失敗的問題。


- 我們已修正啟用 [共用行事曆改進] 選項後，導致 SMTP 位址在多帳戶設定檔中使用者的主要行事曆旁無法顯示的問題。


- 我們已修正導致使用者在透過滑鼠右鍵操作功能表回應會議要求時，看到建立重複的行事曆項目的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正在 DirectX 裝置遺失和復原期間不穩定的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2106-june-29"></a>版本 2106：6 月 29 日
*版本 2106 (組建 14131.20278)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **上次登入/可疑的登入：** Outlook 現在會告知您上次登入帳戶的時間及位置，並警示您是否偵測到任何可疑的登入活動

- **將電子郵件傳送給大型 DL、外部使用者時，協助工具檢查程式會進行微調：** 我們新增了功能，以在撰寫電子郵件給大量對象、外部使用者等時，透過郵件提示自動收到協助工具違規的提示。這些設定放在輕鬆存取中<br />在[部落格文章](https://insider.office.com/zh-tw/blog/sending-accessible-emails-in-outlook-for-windows)中查看詳細資料

- **搜尋時取得相關的檔案建議：** 當您在 [搜尋方塊] 中輸入時，與搜尋相關的最相關檔案將會包含在您的建議中。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正針對部分使用者在 Excel 增益集清單中顯示的額外項目問題。


### <a name="outlook"></a>Outlook

- 我們已修正以下問題：當您檢視信箱資料夾的內容時，商務用 Skype 或 Microsoft Teams 的保留原則顯示為預設資料夾原則，而不是套用於資料夾的信箱保留原則。

- 我們已修正導致 ARM64 裝置上發生效能問題的問題。

- 我們已修正導致某些使用者的翻譯選項遭到停用的問題。  遇到此錯誤的客戶在瀏覽至檔案 -> 選項 -> 語言時，會看見其翻譯選項已遭停用。 有鑑於此，他們可能無法變更其偏好的翻譯語言和其他翻譯相關設定。


- 我們已修正導致擁有多個共用行事曆且擁有共用行事曆增進選項的使用者遇到一些效能問題的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用者因為阻礙性的 PowerPoint 特定對話方塊，而無法將憑證輸入 Windows 安全性對話方塊以開啟檔案的問題。


### <a name="visio"></a>Visio

- 具有來賓存取的 SPO/ODB 連結現在可繼續運作。


### <a name="word"></a>Word

- 已修正在受密碼保護的 docx 檔案上保存引文的問題。


### <a name="office-suite"></a>Office 套件

- 修正使用者從 Office 應用程式中的 Me 控制項切換 Active Directory 身分時切換資料案例。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-june-18"></a>版本 2105：6 月 18 日
*版本 2105 (組建 14026.20308)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致使用者在關閉已回覆或轉寄的郵件時，遇到未預期的屬性變更提示的問題。


- 此變更可讓使用者透過我們新的意見反應系統提交意見反應。


- 我們已修正會導致 ZeroConfigExchange 在已連線到外部網路的已加入混合式 Azure AD 電腦上無法正常運作的問題。


### <a name="office-suite"></a>Office 套件

- 修正使用者無法編輯儲存在內部部署 SharePoint 伺服器中的特定文件的問題。


- 修正重新開啟特定檔案時意外關閉的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-june-08"></a>版本 2105：6 月 8 日
*版本 2105 (組建 14026.20270)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正部分使用者在 Excel 增益集清單中顯示額外項目的問題。


### <a name="outlook"></a>Outlook

- 我們已修正與 Outlook 郵件或行事曆檢視互動時，可能會導致意外關閉的問題。


- 我們已修正在從存放區移除資料夾時，導致使用者遇到意外關閉的問題。


### <a name="office-suite"></a>Office 套件

- 已修正開啟 SyncBacked 檔案時出現效能迴歸的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-may-24"></a>版本 2105：5 月 24 日
*版本 2105 (組建 14026.20246)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入。

### <a name="powerpoint"></a>PowerPoint

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入。

### <a name="teams"></a>Teams

- **透過 AJA 或 Blackmagic 設計硬體將視訊串流送出：** 隔離的視訊串流可以透過 AJA 和 Blackmagic Design 硬體裝置從 Teams 會議送出。

- **匿名使用者可以簡報：** 在主持 Teams 即時活動時，我們新增了匿名使用者加入即時活動的能力，因此他們也可以在活動期間進行簡報。

- **核准 - 重新指派支援：** 核准者現在可以委派/重新指派核准要求給其他使用者。

- **Microsoft Word 內的核准應用程式增益集：** 使用者將可以在 Microsoft Word 內透過增益集來為整個文件或文件的一個區段建立核准要求。

- **VDI 的在一起模式：** VDI 上的在一起模式在會議中使用 AI 分割技術，以數位方式將參與者放在共用背景中，讓每個人覺得你們正坐在同一間會議室中。

- **受監督的聊天：** 使用 Teams 系統管理原則，以確保學生在私人一對一或群組聊天期間受到授課者監督。 使用受監督的聊天時，學生將不被允許在沒有監督授課者出席的情況下參與聊天。

- **Microsoft Teams：修訂會議內共用體驗：** Microsoft Teams 中會議內共用功能的使用者介面已重新設計，以協助簡報者更快速且輕鬆地找到所需的內容。

- **停用特定出席者的相機：** 會議召集人和簡報者可以在 Teams 會議中停用特定出席者的相機，以確保他們不會在會議中分享視訊。

- **停用所有出席者的相機：** 會議召集人和簡報者可以在 Teams 會議中停用所有出席者的相機，以確保他們不會在會議中分享視訊。

- **Teams 網路研討會功能正式發行：** 排程，並使用您用於會議的相同 Teams 應用程式，提供 1，000 人網路研討會！ 網路研討會功能支援註冊頁面建立、報名者的電子郵件確認、出席者影片和音訊的主機管理、出席者報告，以及投票、聊天和回應等互動式功能。

- **使用 Teams 範本建立團隊：** 使用 Teams 中的範本，使用者可在建立新的團隊時從各種可自訂的範本中選擇，協助他們快速開始使用。 IT 系統管理員也可以為其組織建立新的自訂範本，讓他們能標準化團隊結構、預先安裝相關應用程式，以及擴大最佳做法。 IT 系統管理員可以選擇要在 Teams 系統管理中心向使用者顯示哪些團隊範本，也可以將 URL 新增到團隊範本中的網站索引標籤，以預先設定網站頁面。

- **從 PowerPoint 到 Teams 進行簡報：** PowerPoint 應用程式直接透過 PowerPoint Live 將您的投影片展示到 Teams 會議。

- **擴大的表情圖示選擇器：** 擴大的表情圖示更新可在 Teams 中提供使用者更多樂趣和表達力。 它也推出更廣泛的多樣性和呈現方式。 表情圖示集已由 85 個擴充到超過 800 個表情圖示，具有類別選取器、膚色選取器和簡短代碼選擇器。

- **在群組聊天中與外部使用者聊天：** 使用此功能，使用者可以使用 Teams 建立包含其組織外部人員的群組聊天 (需要所有使用者都啟用外部存取功能)。

- **更新至網路規劃中心工具以估計頻寬：** 將更新網路規劃中心工具，以反映 Teams 用戶端的最新頻寬需求。 這將協助 IT 系統管理員更能夠評估及規劃其辦公室頻寬需求。

- **在桌面 (或) 瀏覽器 (或) Teams 中預設開啟檔案的使用者喜好設定：** 使用者可以在開啟 Teams 中共用的 Office (Word、Excel 和 Power Point) 檔案時，將預設喜好設定設定為瀏覽器、桌面或 Teams。如果已安裝並啟用最新的 Office 用戶端，就可以選取桌面設定

- **在會議中同時聚焦多個使用者：** 召集人和簡報者現在可以在會議期間同時聚焦多個參與者。 會議階段會向會議中的每個人顯示這些焦點參與者及其影片或虛擬人偶。

### <a name="word"></a>Word

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正流量分析工具箱增益集對某些使用者無法運作的問題。


- 修正問題，讓名稱管理員可以在具有大量隱藏名稱的書籍上開啟。


### <a name="outlook"></a>Outlook

- 我們已修正會導致「縮短會議時間」功能的部分指示會透過螢幕閱讀程式技術停用的問題。


- 我們已修正會導致某些使用者在載入個人卡片時遇到意外關閉的問題。


- 我們已修正會導致意見回應選項向 Office Perpetual 2021 預覽的使用者停用的問題。


- 我們已新增一個登錄機碼，以可停用新會議室尋找工具體驗 (與網頁版 Outlook 相同的體驗)，並啟用具有建議的時間的傳統會議室尋找工具。

    登錄機碼:

    >HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
    >REG_DWORD “ShowLegacyRoomFinder”</br></br>
    >0 (預設值) - 當使用者按一下 [會議室尋找工具] 按鈕以搜尋可用的會議室時，Outlook 會使用新會議室尋找工具 OWA 提供的體驗  </br>
    >1 - Outlook 使用舊版會議室尋找工具 UI 來搜尋可用的會議室 </br>


### <a name="powerpoint"></a>PowerPoint

- 修正少數使用者無法使用 [重複使用投影片] 選項的問題。


### <a name="project"></a>Project

- 修正手動排程工作上的指派可能會移至不正確日期的問題。


- 修正當您建立的自訂欄位公式使用 ProjectDate */ProjectDur* 函數，且若第二個參數是 Date()、Now() 或 Time() 日期和時間函數時，會導致 #ERROR 結果的問題。


### <a name="word"></a>Word

- 修正拼字及文法檢查用畫布內容卡顯示圖示按鈕，但那些按鈕沒有工具提示的問題。


- 修正編輯器窗格無法開啟的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2104-may-18"></a>版本 2104：5 月 18 日
*版本 2104 (組建 13929.20386)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正導致 Outlook 中的人員選擇器針對擁有永久授權的使用者向上展開，而不是向下展開的問題。


- 我們已修正導致無法向 Office Perpetual 2021 預覽使用者顯示意見回應選項的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2104-may-11"></a>版本 2104：5 月 11 日
*版本 2104 (組建 13929.20372)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正主要版本組建的復原可能會導致檔案開啟時當機的問題。


- 修正流量分析工具箱增益集對某些使用者無法運作的問題。


- 我們已修正在使用增益集時，會導致某些語言的日期格式顯示不正確的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致某些使用行事曆共用改進功能的使用者在功能窗格中與他們的行事曆互動時發生的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正主要版本組建的復原可能會導致檔案開啟時當機的問題。


- 修正少數使用者無法使用 [重複使用投影片] 選項的問題。


### <a name="word"></a>Word

- 修正主要版本組建的復原可能會導致檔案開啟時當機的問題。


- 修正由於使用者登出或將電腦重新開機關機時，可能導致 Word 意外關閉的問題。


### <a name="office-suite"></a>Office 套件

- 此變更會剖析 Cobalt 回應上傳送的新 TenantId 屬性，並儲存在中央資料表中。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2104-april-29"></a>版本 2104：4 月 29 日
*版本 2104 (組建 13929.20296)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **連結資料類型：實際生活中的真實資料：** 新的連結資料類型會提供有關數百個主題的事實和資料，幫助您直接在 Excel 中達成目標。

### <a name="teams"></a>Teams

- **動態檢視：** 動態檢視會自動將 Teams 會議中的共用內容和影片參與者最佳化。 新控制項可讓您個人化檢視以滿足您的喜好和需要，例如能够並排顯示共用內容和特定參與者。

- **不在辦公室狀態：** 設定訊息，讓其他人知道您不在工作狀態或是休假中，因此當他們傳送聊天訊息給您時，您無法回覆。 您的不在辦公室狀態也會與可在您 Outlook 行事曆中找到的「自動回覆」同步。

### <a name="visio"></a>Visio

- **圖表的現成圖形**：從可新增至 Visio 繪圖中的圖示、相片庫影像、人像紙板和圖戳的大型文件庫中進行選擇。 [深入了解](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)<br />在[部落格文章](https://insider.office.com/zh-tw/blog/access-illustrations-icons-in-visio)中查看詳細資料

### <a name="word"></a>Word

- **以新式註解更輕鬆地進行共同作業：** 新增註解到物件、@提及 同事，並解決註解執行緒，以獲得更佳的共同作業體驗。 [深入了解](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)<br />在[部落格文章](https://insider.office.com/zh-tw/blog/modern-commenting-in-word)中查看詳細資料

- **Word 文件的深色模式：** 深色模式有助於減輕眼睛疲勞，並可在處理文件時適應對光線的敏感度。<br />在[部落格文章](https://insider.office.com/zh-tw/blog/try-dark-mode-in-word)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正某些檔案偶爾無法在受保護的檢視中開啟的問題


### <a name="outlook"></a>Outlook

- 我們已修正會導致使用者在搜尋時遇到預期關閉的問題。


- 我們已修正會導致使用者看到簽名意外消失的問題。


- 我們已修正可能造成使用者看到正在撰寫的郵件失去 UI 焦點的問題。


- 我們已修正會導致 Outlook 覆寫 OWA 中已設定的焦點收件匣喜好設定問題。


- 我們已修正會導致漫遊設定的使用者遇到沒有回應的問題。


- 我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，會造成名稱解析停用的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正與連結圖片相關的問題。


### <a name="project"></a>Project

- 修正使用者無法從資源資料庫移除專案的問題。


### <a name="word"></a>Word

- 修正更新儲存在本機檔案上的自動儲存圖說文字的問題。


- 修正在閱讀模式中使用深色模式主題時，某些選取的文字無法顯示的問題。


- 我們對編輯 OLE 物件進行了變更。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-april-23"></a>版本 2103：4 月 23 日
*版本 2103 (組建 13901.20462)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正安裝 2021 年 4 月安全性更新之後，Excel 的自動化增益集無法載入的問題。 請針對未使用目前通道的使用者使用所提供的因應措施。[深入了解](https://support.microsoft.com/en-us/office/automation-add-ins-for-excel-are-not-loading-after-installing-april-2021-security-update-8b2927a1-4a24-4ae6-8855-60827b7632fb)。 


### <a name="outlook"></a>Outlook

- 我們已修正會導致 Outlook 覆寫 OWA 中已設定的焦點收件匣喜好設定問題。


- 我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，造成名稱解析失敗的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正與連結圖片相關的問題。


### <a name="word"></a>Word

- 最佳化提供文字預測的條件。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-april-13"></a>版本 2103：4 月 13 日
*版本 2103 (組建 13901.20400)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


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

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正啟用 MAPI 的應用程式在具有 ARM 處理器的電腦上使用 Outlook 元件的問題。 此問題會導致搜尋失敗，或因為背景應用程式重複重新啟動而造成電腦額外負載。

## <a name="version-2103-march-30"></a>版本 2103：3 月 30 日
*版本 2103 (組建 13901.20312)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 DoD 環境中的客戶取得。 [深入了解](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **撰寫郵件時節省時間：** Outlook 會顯示書寫建議，協助您快速撰寫郵件。 若要接受建議，只需使用 Tab 鍵。<br />在[部落格文章](https://insider.office.com/zh-tw/blog/text-predictions-in-word-outlook)中查看詳細資料

- **新的會議室和工作區預約體驗：** 會議室預約體驗已更新，透過它我們新增了功能，以讓您也能夠排程個別工作區

- **挑選搜尋的位置：** 新的搜尋範圍下拉式清單，可讓您更輕鬆地修改搜尋，並在目前資料夾和目前信箱之間切換。 感謝每個在 [即將推出] 為 [頂極體驗] 的 新 [搜尋] 提供意見反應的人。 因為有這份意見反應，才有這項設計與更新！

- **搜尋人員時取得會議建議：** 當您在搜尋方塊中輸入人員的名稱時，包含行事曆邀請的最相關電子郵件訊息會包括在您的搜尋建議中。

- **共用至 Teams：** 將 Outlook 的郵件與 Teams 中的某個人員或頻道共用。

- **使用語音草擬郵件：** 使用新的聽寫工具列、語音命令、自動標點符號等功能來撰寫郵件。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 DoD 環境中的客戶取得。 [深入了解](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a>PowerPoint

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 DoD 環境中的客戶取得。 [深入了解](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="teams"></a>Teams

- **會議反應：** 會議反應是在會議中互動的新方式。 參與者可以傳送反應且反應會以資料流的形式顯示在共用的內容上，以及在傳送該反應的個人上 (如果他們有在會議階段上顯示)。

- **在 Teams 會議中管理出席者音訊權限的改進：** 即使在出席者沒有舉手的情況下，會議簡報者和召集人現在可以允許出席者取消靜音。 以前，被禁止取消靜音 (停用麥克風) 的出席者必須舉手才能取消靜音。

- **在 Teams 會議中管理出席者音訊權限的改進：** 以前，會議簡報者或召集人無法停用會議中單一出席者的麥克風。 召集人或簡報者只能將「允許出席者取消靜音」設定為關閉，從而停用每個出席者的麥克風。 有了這項變更，會議簡報者和召集人可以臨時禁止單一出席者在 Teams 會議期間取消靜音。

- **改進了會議參與者名冊中的體驗：** 我們現在正在變更 Teams 會議中大廳、會議、簡報者和出席者區段顯示參與者清單的方式。 在初始檢視中，每個區段最多可顯示 20 名參與者，並可選擇在該區段中深入和檢視更多參與者。 對於大廳，您可以在允許所有人參加會議之前檢閱 完整清單。 名册將按字母順序顯示最活躍與會者的詳細資訊。 參與者動作功能表沒有變更。

- **從名冊中搜尋會議參與者：** 使用者現在可以從名冊中的搜尋方塊中搜尋目前會議參與者，以瞭解特定人員是否已加入會議。 他們可以繼續在會議之外搜尋參與者，並要求他們加入會議。

- **從 Outlook 共用至 Teams：** 從 Outlook 共用至 Teams 可讓您將電子郵件或交談 (包括附件) 的複本傳送至 Teams 聊天和頻道。 在 Outlook 功能區或電子郵件的動作功能表中找到 [共用至 Teams] 選項。 [共用至 Teams] 支援 Outlook 網頁版、Windows 版 Outlook 和新 Mac 版 Outlook Preview。

- **分組討論區計時器和會議室指派保留：** 召集人現在可以從分組討論區設定中為分組討論區設定計時器。 計時器過期後，會議室將自動關閉，與會者將返回主會議。 會議室指派保留提供了在多個工作階段上持久保留會議室設定和指派的功能。有了與參與者重新指派功能，召集人現在可以在會議室和主會議室開啟時移動已加入的參與者。

- **離線存取檔案：** 即使沒有網際網路連線，使用者現在也可以存取以前開啟的檔案。

- **共用 PowerPoint 檔案時的方格檢視：** 在會議中共用 PowerPoint 檔案時，使用者現在可以使用方格檢視查看投影片組中的所有投影片，以便進行臨時投影片導覽。

### <a name="word"></a>Word

- **使用語音草擬文件：** 使用新的聽寫工具列、語音命令、自動標點符號等功能來草擬文件。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 DoD 環境中的客戶取得。 [深入了解](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)


### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此變更可修正在某些情況下，執行 SQL Server 傳遞查詢時，可能會導致錯誤訊息指出「無效的 Cursor 狀態」的問題。

- 我們已修正當外部應用程式要求協助工具介面時，它會防止我們關機，直到它們釋出其參考為止的問題。

### <a name="project"></a>Project

- 修正 Office 功能區中停用的命令只會使圖示變灰，而不會使文字變為深灰色 Office 佈景主題的錯誤。

### <a name="excel"></a>Excel

- 修正 Office 功能區中停用的命令只會使圖示變灰，而不會使文字變為深灰色 Office 佈景主題的錯誤。


### <a name="outlook"></a>Outlook

- 我們已修正會導致某些使用者在同步處理資料夾階層變更時遇到 Outlook 意外關閉的問題。


- 我們已修正會導致某些使用者在瀏覽窗格中看到主要和次要行事曆切換位置的問題。


- 我們已修正會導致使用者看到較預期更多的簽章的問題。


- 我們已修正會導致部分使用者無法存取與次要郵件帳戶相關聯的簽章的問題。


- 我們已修正會導致雲端設定功能的使用者在新裝置上設定 Outlook 之後，會看到自訂設定遭到預設設定覆寫的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正 Office 功能區中停用的命令只會使圖示變灰，而不會使文字變為深灰色 Office 佈景主題的錯誤。


### <a name="visio"></a>Visio

- 修正 Visio 在關閉期間可能會停止運作的問題。


### <a name="word"></a>Word

- 共同撰寫文件時，若註解順序變更，不會清除作用中草稿。


- 修正 Office 功能區中停用的命令只會使圖示變灰，而不會使文字變為深灰色 Office 佈景主題的錯誤。


- 我們已修正有關複製和貼上的問題。


### <a name="office-suite"></a>Office 套件

- 修正停用 GCC 使用者聽寫功能的錯誤


- 修正有時可能導致文字在 Outlook 變得透明，從而無法辨認的錯誤。


- 修正與支援在工作階段 0 中執行的 Office 應用程式相關的可靠性問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-march-18"></a>版本 2102：3 月 18 日
*版本 2102 (組建 13801.20360)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此變更可修正在某些情況下，執行 SQL Server 傳遞查詢時，可能會導致錯誤訊息指出「無效的 Cursor 狀態」的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致雲端設定功能的使用者在新裝置上設定 Outlook 之後，會看到自訂設定遭到預設設定覆寫的問題。


- 我們已修正會導致使用者看到較預期更多的簽章的問題。


### <a name="word"></a>Word

- 我們已修正在隱藏段落結尾輸入可能會導致應用程式懸置的問題。


### <a name="office-suite"></a>Office 套件


- 修正使用者在開啟先前開啟的檔案具有未儲存的編輯但現在檔案已遭到刪除時，無法儲存檔案的問題。 修正之後，使用者將會收到一則友善的訊息，通知他們已刪除該檔案，因此使用者可以選擇捨棄變更，或將檔案另存為新檔。


- 我們已修正與支援在工作階段 0 中執行的 Office 應用程式相關的可靠性問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-march-09"></a>版本 2102：3 月 9 日
*版本 2102 (組建 13801.20294)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致使用者在 Outlook 重新啟動之前，在功能窗格中看不到新增的行事曆顯示的問題。


### <a name="word"></a>Word

- 修正對具有 3D 效果的圖示和 SVG 圖形套用色彩的問題。


- 我們已修正可能會略過段落的朗讀程式問題。


- 我們已修正 RTF 內容控制項的問題。


### <a name="office-suite"></a>Office 套件

- 修正在包含數學方程式的文字內使用朗讀程式時可能發生的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-march-01"></a>版本 2102：3 月 1 日
*版本 2102 (組建 13801.20266)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **同時取消隱藏多個工作表：** 不再需要一次取消隱藏一個工作表，可以一次取消隱藏多個隱藏的工作表。 [深入了解](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- **改善條件式格式設定對話方塊：**[條件式格式設定] 對話方塊現在可以調整大小，且現在您只要按一下就能複製規則。 [深入了解](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)

- **要求使用者套用敏感度標籤：** 當使用者的組織原則要求時，會提示使用者套用敏感度標籤。

### <a name="outlook"></a>Outlook

- **更新的連絡人清單檢視：** 連絡人清單現在會顯示電子郵件地址，以及更新的相片和文字大小。

- **使用內建翻譯工具打破語言障礙：** 不再需要翻譯的增益集！ 您現在可以在 Outlook 中使用 Intelligent Translator。 當您收到另一種語言的郵件時，郵件上會顯示提示，詢問您是否希望 Outlook 將它翻譯為您的預設語言。
您也可以按一下滑鼠右鍵以翻譯特定的文字、片語或整個郵件。 [深入了解](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

### <a name="powerpoint"></a>PowerPoint

- **要求使用者套用敏感度標籤：** 當使用者的組織原則要求時，會提示使用者套用敏感度標籤。

### <a name="teams"></a>Teams

- **共用 PowerPoint 檔案時的簡報者檢視畫面**：在會議中共用 PowerPoint 檔案時，簡報者現在會有投影片組中所有投影片的縮圖區域檢視，以便輕鬆進行臨機操作的投影片瀏覽。

- **佈景主題和圖示更新：** 我們對預設和深色佈景主題色彩和圖示進行了更新。

- **iPad 上的即時活動簡報者支援：** 您可以透過支援的 iPad 裝置在即時活動中進行簡報。

- **使用 Microsoft Forms 讓會議參與者投票：** Teams 會議的投票是可輕鬆探索且順暢的體驗，可協助您進行更吸引人且更具生產力的會議。 利用由 Microsoft Forms 提供支援的「投票」功能，會議簡報者可以分別在會議之前、期間和之後準備、啟動及評估投票，這一切都可以在 Teams 會議的一個索引標籤下進行。 身為會議簡報者，您可以將 Forms 應用程式新增為 Teams 會議中的索引標籤，然後從一個位置建立、啟動及評估您的投票。 建立投票以在會議期間啟動，甚至在會議開始之前啟動。 然後，在會議之後，您可以選擇在索引標籤中、在匯出的 Excel 活頁簿或在 Forms 應用程式的網頁上評估回應。 簡報者有各種不同的控制項，例如啟用匿名回應、關閉投票，以及將結果匯出至 Excel。 來自任何端點 (行動裝置、網頁、桌面) 的出席者可以在投票出現在會議畫面或會議聊天中時檢視和回答投票，以及即時查看非匿名的投票結果。

- **會議反應：** 會議反應是在會議中互動的新方式。 參與者可以傳送反應且反應會以資料流的形式顯示在共用的內容上，以及在傳送該反應的個人上 (如果他們有在會議階段上顯示)。

- **桌面用戶端的歷程記錄功能表：** Teams 桌面用戶端中的歷程記錄功能表，可讓您輕鬆回到最近瀏覽過的位置。 只要將游標停留在桌面用戶端的下一頁或上一頁瀏覽選項上，然後選取位置即可。 也可使用鍵盤快速鍵來開啟功能表。

- **適用於美國的 Microsoft Teams 會議室中的 Cortana：** Microsoft Teams 會議室中的 Cortana 語音協助可讓您有不需觸控，即可從會議室撥打號碼、加入或結束會議或新增號碼至會議的體驗。

- **遮罩電話號碼：** 我們發佈了新的系統管理員設定，用於在撥入參與者加入會議時遮罩其電話號碼。 系統管理員可以選擇為來自會議中的每個人 (會議召集人除外)、僅來自外部的人員遮罩電話號碼，或是將遮罩功能停用。 如果系統管理員選擇停用此設定，將會在會議中完整顯示電話號碼。  (10 月底之前屬於私人發行)

- **行事曆共用：** 我們新增了將頻道新增到行事曆索引標籤的功能。

- **為在一起模式增加更多場景：** Teams 現已推出可讓會議召集者或簡報者變更在一起模式場景的功能，讓出席者可以一起以不同的體驗顯示。

### <a name="word"></a>Word

- **單鍵書寫建議：** 只要按一下，就能套用書寫建議。 更新的 [編輯器] 窗格讓您輕鬆在建議之間瀏覽。 [深入了解](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br />在[部落格文章](https://insider.office.com/zh-tw/blog/microsoft-editor-gets-an-upgrade)中查看詳細資料

- **要求使用者套用敏感度標籤：** 當使用者的組織原則要求時，會提示使用者套用敏感度標籤。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正使用者收到「資料指標狀態無效」錯誤對話方塊的問題。


### <a name="excel"></a>Excel

- 我們已修正會導致使用者無法將 Excel 活頁簿匯出至 PDF 的問題。


- 我們已修正使用 [貼上連結圖片] 選項時，會導致影像小於預期的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致共用行事曆改良功能的使用者無法將行事曆的色彩設定為黃色或褐色的問題。


- 我們已修正會導致使用者在建立新群組後看到重複的行事曆群組的問題。


- 我們已修正會導致某些使用者在關閉訊息視窗時遇到應用程式關閉的問題。


- 我們已修正會導致使用者看到包含 Unicode 內容的簽章損毀的問題。


- 我們已修正會導致內嵌翻譯的使用者無法提交意見反應的問題。


### <a name="word"></a>Word

- 我們已修正共同撰寫時衝突的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-february-16"></a>版本 2101：2 月 16 日
*版本 2101 (組建 13628.20448)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正使用者在 Outlook 中進行搜尋時，有時候會導致應用程式未預期關閉的問題。


- 我們已修正會導致在使用者取消選取數位簽章選項之後，仍以數位簽章方式傳送郵件的問題。


### <a name="office-suite"></a>Office 套件

- 修正與媒體控制器事件通知相關的問題。


- 修正與媒體播放程式引擎時間相關的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-february-09"></a>版本 2101：2 月 9 日
*版本 2101 (組建 13628.20380)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致雲端設定使用者在更新設定時遇到停止回應的問題。


- 我們已修正在 OWA 中顯示正確預設簽名的問題。


- 我們已修正會導致加密圖示無法對使用 [僅加密] 選項傳送的電子郵件顯示的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-january-26"></a>版本 2101：1 月 26 日
*版本 2101 (組建 13628.20274)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。 此項幕後功能 (無 UI) 為系統管理員權益。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。 [深入了解](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **依訊息擁有者刪除交談：** 此功能可讓您依訊息擁有者刪除交談。

- **在連續會議之間置入時間：** 將會議預設為延後 5-10 分鐘開始，讓出席者有時間休息，或前往下一個地點。 [深入了解](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- **每個線上會議** 更新行事曆設定，使您建立的每個會議都預設為 Teams 會議，這樣您就不必再記得按一下 [Teams 會議] 選項。

- **將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。 此項幕後功能 (無 UI) 為系統管理員權益。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。 [深入了解](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a>PowerPoint

- **將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。 此項幕後功能 (無 UI) 為系統管理員權益。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。 [深入了解](/microsoft-365/compliance/sensitivity-labels)

### <a name="word"></a>Word

- **將敏感度標籤的相關稽核資料傳送給 M365 系統管理員：** 當使用者套用、變更或移除其檔案和電子郵件上的靈敏度標籤時，Office 會將稽核資料發送到 M365 稽核後端，供系統管理員查看。 此項幕後功能 (無 UI) 為系統管理員權益。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。 [深入了解](/microsoft-365/compliance/sensitivity-labels)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題


- 我們已修正破壞了一些舊的 Excel 4.0和 Excel 5.0 巨集以及一些至 dialogsheets.show 的 VBA 呼叫。


### <a name="outlook"></a>Outlook

- 我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 異常關閉的問題。


- 我們修正了導致在其設定檔中具有大型階層的共用或委派信箱的使用者遇到停止回應的問題。


### <a name="project"></a>Project

- 修正在 [團隊規劃] 檢視中工作沒有顯示邊框的問題。


- 修正在 [團隊規劃] 檢視中拖放工作不起作用的問題。


- 修正了將成本資源指派給里程碑工作時，比較基準成本沒有正確彙總的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-january-21"></a>版本 2012：1 月 21 日
*版本 2012 (組建 13530.20440)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們修正了導致在其設定檔中具有大型階層的共用或委派信箱的使用者遇到停止回應的問題。


- 我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 異常關閉的問題。


### <a name="office-suite"></a>Office 套件

- 修正檔案關閉順序，使所有相互依存的元件都能正常關閉。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-january-12"></a>版本 2012：1 月 12 日
*版本 2012 (組建 13530.20376)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致在提示使用者儲存已編輯的簽名後，該動作會無法執行的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-january-05"></a>版本 2012：1 月 05 日
*版本 2012 (組建 13530.20316)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **雲端中的 Outlook 設定：** 選擇您的 Windows 版 Outlook 設定，例如自動回復、焦點收件匣和隱私權，並在任何電腦上使用這些功能。

- **新的會議室尋找工具：** 依不同功能搜尋會議室。

### <a name="powerpoint"></a>PowerPoint

- **利用簡報者教練排練簡報：** 取得有助於維持對象參與的項目方面的意見反應，例如節奏、語調、填充字詞、敏感詞語等等。 [深入了解](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="visio"></a>Visio

- **新 Azure 樣板和圖案：** 我們新增了更多的樣板來協助您建立最新的 Azure 圖表。 [深入了解](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正使用樞紐分析表的「將值顯示為」功能表時，Excel 可能會意外關閉的問題。


- 修正當開啟含有 Excel 4.0 巨集的 Excel 增益集檔案時，Excel 可能會在不提示的情況下停用巨集的問題。


- 修正當某些使用者在共同撰寫時會錯誤地看到通知他們檔案新版本的訊息列之問題。


- 此變更解決了在方程式中正確顯示字型的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致某些客戶在載入行事歷時遇到停滯的問題。


### <a name="powerpoint"></a>PowerPoint

- 此變更解决對某些幾何圖形套用 [合併圖案] 作業時路徑填充的問題。


- 此變更解決了在方程式中正確顯示字型的問題。


- 我們已修正在 QAT 中新增的字型大小命令在更新時，會自動完成到最接近的已定義字型大小之問題。


### <a name="office-suite"></a>Office 套件

- 優化的二進位大小。


- Anaheim WebView 目前尚不支援 Windows 資訊保護(WIP)。 有了此修正程式，Office addin 平臺便會回到處於 WIP 啟用環境中的低層級 WebView。 根據客戶的電腦環境，這可以是 Edge Spartan WebView 或 Trident WebView。 兩個低層級 WebViews 皆支援 WIP。





[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> 如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。

[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|CC|Production| |16.0.14326.20238|version-2108-august-25|)
[//]: # (|Win32|CC|Production| |16.0.14228.20250|version-2107-august-10|)
[//]: # (|Win32|CC|Production| |16.0.14228.20226|version-2107-august-03|)
[//]: # (|Win32|CC|Production| |16.0.14228.20204|version-2107-july-26|)
[//]: # (|Win32|CC|Production| |16.0.14131.20332|version-2106-july-20|)
[//]: # (|Win32|CC|Production| |16.0.14131.20320|version-2106-july-13|)
[//]: # (|Win32|CC|Production| |16.0.14131.20278|version-2106-june-29|)
[//]: # (|Win32|CC|Production| |16.0.14026.20308|version-2105-june-18|)
[//]: # (|Win32|CC|Production| |16.0.14026.20270|version-2105-june-08|)
[//]: # (|Win32|CC|Production| |16.0.14026.20246|version-2105-may-24|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
