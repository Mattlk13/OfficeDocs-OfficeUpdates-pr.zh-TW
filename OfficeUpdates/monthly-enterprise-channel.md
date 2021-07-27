---
title: 每月企業通道版本的版本資訊
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 Microsoft 365 Apps 每月企業通道版本的版本資訊
ms.openlocfilehash: 4b73ac3bfd364835eb933c530c9b399f5ef91381
ms.sourcegitcommit: d70605f689ddab4ddef193d526426fafa8e301b3
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/16/2021
ms.locfileid: "53463770"
---
# <a name="release-notes-for-monthly-enterprise-channel"></a>每月企業通道的版本資訊

這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的每月企業通道更新。


[//]: # (DO NOT REMOVE)



## <a name="version-2105-july-13"></a>版本 2105：7 月 13 日
*版本 2105 (組建 14026.20334)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **搜尋時取得相關的檔案建議：** 當您在 [搜尋方塊] 中輸入時，與搜尋相關的最相關檔案將會包含在您的建議中。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正問題，讓名稱管理員可以在具有大量隱藏名稱的書籍上開啟。


- 已修正部分使用者在 Excel 增益集清單中顯示額外的問題項目。


- 修正分析工具箱增益集對某些使用者無法運作的問題。


### <a name="outlook"></a>Outlook

- 變更是停止動作和在變更閘道下進行，因此如果發生問題，可以快速關閉。


- 我們已新增一個登錄機碼，以可停用新會議室尋找工具體驗 (與網頁版 Outlook 相同的體驗)，並啟用具有建議的時間的傳統會議室尋找工具。

   登錄機碼:

    >HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar REG_DWORD “ShowLegacyRoomFinder”

    >0 (預設值) - 當使用者按一下 [會議室尋找工具] 按鈕以搜尋可用的會議室時，Outlook 會使用新會議室尋找工具 OWA 提供的體驗</br>
    >1 - Outlook 使用舊版會議室尋找工具 UI 來搜尋可用的會議室


- 此變更可讓使用者透過我們新的意見反應系統提交意見反應。


- 我們已修正導致意見反應選項對 Office Perpetual 2021 預覽的使用者停用的問題。


- 我們已修正導致使用者在從電子郵件收件者的右鍵操作功能表選取 [開啟 Outlook 內容] 時出現錯誤的問題。


- 我們已修正在載入個人卡片時，導致某些使用者遇到應用程式意外關閉的問題。


- 我們已修正在從封存區移除資料夾時，導致使用者遇到意外關閉的問題。


- 我們已修正透過螢幕閱讀程式技術導致「縮短會議」功能的一些指示停用的問題。


- 我們已修正會導致使用者在關閉已回覆或轉寄的郵件時，遇到未預期的屬性變更提示的問題。


- 我們已修正可能導致操作 Outlook 郵件或檢視行事曆時意外關閉的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正少數使用者無法使用 [重複使用投影片] 選項的問題。


### <a name="project"></a>Project

- 已修正手動排程任務的工作分派移至不正確日期的問題。


- 修正當您建立的自訂欄位公式使用 ProjectDate */ProjectDur* 函數，且若第二個參數是 Date()、Now() 或 Time() 日期和時間函數時，會導致 #ERROR 結果的問題。


### <a name="word"></a>Word

- 已修正 [編輯器] 窗格無法開啟的問題。


- 已修正拼字及文法檢查的畫布關聯式卡片的顯示圖示按鈕沒有工具提示的問題。


### <a name="office-suite"></a>Office 套件

- 已修正 en-gb、fr-ca 和 es-mx 現在會與其各自的來源版本相符合的當地語系化問題。


- 已修正重新開啟特定檔案時意外關閉的問題。


- 已修正開啟 SyncBacked 檔案時出現效能迴歸的問題。


- 已修正使用者無法編輯儲存在 OnPrem SharePoint 伺服器中特定文件的問題。



[//]: # (請勿移除 BUGDETAILS 內容結尾)

## <a name="version-2104-july-13"></a>版本 2104：7 月 13 日
*版本 2104 (組建 13929.20434)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)

## <a name="version-2104-june-08"></a>版本 2104：6 月 08 日
*版本 2104 (組建 13929.20408)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。

### <a name="powerpoint"></a>PowerPoint

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。

### <a name="word"></a>Word

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正部分檔案有時無法在 [受保護的檢視] 中開啟的問題。


- 我們已修正在使用增益集時，會導致某些語言的日期格式顯示不正確的問題。


- 修正流量分析工具箱增益集對某些使用者無法運作的問題。


- 修正針對部分使用者在 Excel 增益集清單中顯示的額外項目問題。


- 修正主要版本組建的復原可能會導致檔案開啟時當機的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致某些使用行事曆共用改進功能的使用者在功能窗格中與他們的行事曆互動時發生的問題。


- 我們已新增一個登錄機碼，以停用新會議室尋找工具體驗 (與 Outlook 網頁版相同的體驗)，並啟用具有建議的時間的傳統會議室尋找工具。
    
    登錄機碼:

    >HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
    >REG_DWORD “ShowLegacyRoomFinder”</br></br>
    > 0 (預設值) - 當使用者按一下 [會議室尋找工具] 按鈕以搜尋可用的會議室時，Outlook 會使用新會議室尋找工具 OWA 提供的體驗  </br>
    > 1 - Outlook 使用舊版會議室尋找工具 UI 來搜尋可用的會議室 </br>


- 我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，造成名稱解析失敗的問題。


- 我們已修正導致無法向 Office Perpetual 2021 預覽使用者顯示意見回應選項的問題。


- 我們已修正可能造成使用者看到正在撰寫的郵件失去 UI 焦點的問題。


- 我們已修正會導致 Outlook 覆寫 OWA 中已設定的焦點收件匣喜好設定問題。


- 我們已修正會導致使用者看到簽名意外消失的問題。


- 我們已修正會導致漫遊設定的使用者遇到無回應的問題。


- 我們已修正會導致使用者在搜尋時，遇到處里程序意外終止的問題。


- 我們已修正與搜尋相關的意外關閉問題。


- 我們已修正造成 Oulook 中的人員選擇器針對具永久授權的使用者向上展開而非向下展開的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正少數使用者無法使用 [重複使用投影片] 選項的問題。


- 我們已修正與連結圖片相關的問題。


- 已修正主要版本組建的復原可能會導致檔案開啟時意外關閉的問題。


### <a name="project"></a>Project

- 修正使用者無法從資源資料庫移除專案的問題。


### <a name="word"></a>Word

- 已修正編輯 OLE 物件時需要變更的問題。


- 已修正在閱讀模式中使用深色模式主題時，某些選取的文字無法顯示的問題。


- 已修正由於使用者登出或重新啟動電腦而電腦關機時，可能導致 Word 意外關閉的問題。


- 已修正對本機儲存之檔案的自動儲存圖說文字進行更新的問題。


- 已修正主要版本組建的復原可能會導致檔案開啟時意外關閉的問題。


### <a name="office-suite"></a>Office 套件

- 已修正會導致雲端文件無法開啟的問題。


- 此變更會剖析 Cobalt 回應上傳送的新 TenantId 屬性，並儲存在中央資料表中。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-june-08"></a>版本 2103：6 月 8 日
*版本 2103 (組建 13901.20554)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正針對部分使用者在 Excel 增益集清單中顯示的額外項目問題。


### <a name="office-suite"></a>Office 套件

- 已修正如果回復到先前的組建，Word、Powerpoint 和 Excel 無法開啟雲端文件的問題



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2103-may-11"></a>版本 2103：5 月 11 日
*版本 2103 (組建 13901.20516)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **自動使用新的資料類型**：當您輸入的資料值類似股票或地理位置時，Excel 會將該值轉換為正確的連結資料類型 - 股票或地理位置。 [深入了解](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **連結資料類型：實際生活中的真實資料：** 新的連結資料類型會提供有關數百個主題的事實和資料，幫助您直接在 Excel 中達成目標。

### <a name="outlook"></a>Outlook

- **使用內建翻譯工具打破語言障礙：** 不再需要翻譯的增益集！ 您現在可以在 Outlook 中使用 Intelligent Translator。 當您收到另一種語言的郵件時，郵件上會顯示提示，詢問您是否希望 Outlook 將它翻譯為您的預設語言。
您也可以按一下滑鼠右鍵以翻譯特定的文字、片語或整個郵件。 [深入了解](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

### <a name="visio"></a>Visio

- **圖表的現成圖形**：從可新增至 Visio 繪圖中的圖示、相片庫影像、人像紙板和圖戳的大型文件庫中進行選擇。 [深入了解](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)<br />在[部落格文章](https://insider.office.com/zh-TW/blog/access-illustrations-icons-in-visio)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正當外部應用程式要求協助工具介面時，它會防止我們關機，直到它們釋出其參考為止的問題。


- 此變更可修正在某些情況下，執行 SQL Server 傳遞查詢時，可能會導致錯誤訊息指出「無效的 Cursor 狀態」的問題。


### <a name="excel"></a>Excel

- 我們已修正在使用增益集時，會導致某些語言的日期格式顯示不正確的問題。


- 修正流量分析工具箱增益集對某些使用者無法運作的問題。


- 修正在繪製影像時 Word 中可能會當機的問題。


### <a name="outlook"></a>Outlook

- 我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，造成名稱解析失敗的問題。


- 我們已修正會導致 Outlook 覆寫 OWA 中已設定的焦點收件匣喜好設定的問題。


- 我們已修正會導致部分使用者無法存取與次要郵件帳戶相關聯簽章的問題。


- 我們已修正會導致使用者看到較預期更多簽章的問題。


- 我們已修正會導致某些使用者在功能窗格中看到主要和次要行事曆切換位置的問題。


- 我們已修正會導致使用者在新增行事曆時，錯誤地看到「這可能需要一些時間」訊息的問題。


- 我們已修正會導致代理人在新增的行事曆上所建立的會議中顯示為召集人的問題。  處於此狀態的會議不會出現在主體的行事曆上。


- 我們已修正啟用 MAPI 的應用程式在具有 ARM 處理器的電腦上使用 Outlook 元件的問題。 此問題可能導致搜尋失敗，或因為背景應用程式重複重新啟動而造成電腦上額外的負載。


- 我們已修正會導致某些使用者在同步處理資料夾階層變更時遇到 Outlook 意外關閉的問題。


- 修正在繪製影像時 Word 中可能會當機的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正與連結圖片相關的問題。


- 修正在繪製影像時 Word 中可能會當機的問題。


### <a name="project"></a>Project

- 修正 Visio 在關閉期間可能會停止運作的問題。


### <a name="visio"></a>Visio

- 修正 Visio 在關閉期間可能會停止運作的問題。


### <a name="word"></a>Word

- 修正將提供文字預測情況最佳化的問題。


- 修正對儲存在本機檔案上的自動儲存圖說文字進行更新的問題。


- 修正共同撰寫文件時，若註解順序變更，則不會清除作用中草稿的問題。


- 修正預覽列印會意外關閉的問題。


- 修正在繪製影像時 Word 中可能會當機的問題。



### <a name="office-suite"></a>Office 套件

- 修正與支援在工作階段 0 中執行的 Office 應用程式相關的可靠性問題。


- 修正離線開啟 SyncBacked 檔案，然後於儲存檔案之前，在應用程式中重新命名檔案時，重新命名會停止回應的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-may-11"></a>版本 2102：5 月 11 日
*版本 2102 (組建 13801.20638)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正在使用增益集時，會導致某些語言的日期格式顯示不正確的問題。


- 我們已修正會導致無法以公式形式貼上到受保護工作表的問題。


### <a name="outlook"></a>Outlook

- 這可讓使用者設定 Outlook 以將線上會議新增至他們建立的每一個會議。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正與連結圖片相關的問題。


### <a name="word"></a>Word

- 修正 Wordmail 中當連結的第 2084 個字元是逸出字元時，某人無法傳送此項目的問題。


### <a name="office-suite"></a>Office 套件

- 修正會導致 Word 在列印長篇文件時意外關閉的問題。


- 在此變更之前，即使已開啟用於停用 Office 範本的 GPO，Office 範本還是會顯示。 利用此變更，範本現在會正確地遵循 GPO，並按要求顯示/隱藏。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-april-13"></a>版本 2102：4 月 13 日
*版本 2102 (組建 13801.20506)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用 [進階對話方塊] 來 [建立資料類型]:** [進階對話方塊] 可讓您手動選取合併您正在建立的 [資料類型] 欄位。

- **同時取消隱藏多個工作表：** 不再需要一次取消隱藏一個工作表，可以一次取消隱藏多個隱藏的工作表。 [深入了解](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)


### <a name="outlook"></a>Outlook

- **焦點收件匣設定在不同裝置之間會保持相同：** 您的焦點收件匣喜好設定現在會儲存在雲端。 這麼一來，當您在任何電腦上使用 Windows 版 Outlook 和 Outlook 網頁版時便可享有相同的體驗。 [深入了解](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- **雲端中的 Outlook 設定：** 選擇您的 Windows 版 Outlook 設定，例如自動回復、焦點收件匣和隱私權，並在任何電腦上使用這些功能。

- **挑選搜尋的位置：** 新的搜尋範圍下拉式清單，可讓您更輕鬆地修改搜尋，並在目前資料夾和目前信箱之間切換。 感謝每個在 [即將推出] 為 [頂極體驗] 的 新 [搜尋] 提供意見反應的人。 因為有這份意見反應，才有這項設計與更新！

- **使用語音草擬郵件：** 使用新的聽寫工具列、語音命令、自動標點符號等功能來撰寫郵件。

### <a name="word"></a>Word

- **使用語音草擬文件：** 使用新的聽寫工具列、語音命令、自動標點符號等功能來草擬文件。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 修正在某些情況下，執行 SQL Server 傳遞查詢時，可能會導致錯誤訊息指出「無效的 Cursor 狀態」的問題。



### <a name="excel"></a>Excel

- 我們已修正將資料列新增至另一個工作表上的表格後，可能會非預期地對儲存格套用資料驗證的錯誤。


- 我們已修正 DialogSheets show 函數在 32 位元版本的 Excel 上無法運作的問題


- 我們已修正使用 [貼上連結圖片] 選項時，會導致影像小於預期的問題。


- 我們已修正在儲存為 .xls 或 .xlt 格式時，會導致某些樞紐分析表格式損壞活頁簿的問題。


- 我們已修正會導致使用者無法將 Excel 活頁簿匯出至 PDF 的問題。


- 修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。


### <a name="outlook"></a>Outlook

- 我們已修正會導致內嵌翻譯的使用者無法提交意見反應的問題。


- 我們已修正會導致使用者看到包含 Unicode 內容的簽章損毀的問題。


- 我們已修正會導致使用者看到較預期更多的簽章的問題。


- 我們已修正會導致 Outlook 在閒置時當機的問題。


- 我們已修正會導致某些使用者在關閉訊息視窗時遇到應用程式關閉的問題。


- 我們已修正會導致共用行事曆改良功能的使用者無法將行事曆的色彩設定為黃色或褐色的問題。


- 我們已修正會導致使用者在建立新群組後看到重複的行事曆群組的問題。


- 我們已修正會導致使用者在 Outlook 重新啟動之前，在功能窗格中看不到新增的行事曆顯示的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。


### <a name="word"></a>Word

- 我們已修正共同撰寫時衝突的問題。


- 我們已修正 RTF 內容控制項的問題。


- 我們已修正在隱藏段落結尾輸入可能會導致應用程式懸置的問題。


- 我們已修正可能會略過段落的朗讀程式問題。


- 我們已修正有關複製和貼上的問題。


- 修正對具有 3D 效果的圖示和 SVG 圖形套用色彩的問題。


- 修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。


### <a name="office-suite"></a>Office 套件

- 我們已修正與支援在工作階段 0 中執行的 Office 應用程式相關的可靠性問題。


- 修正有時可能會導致 Outlook 中的文字變得透明，因而無法辨認的問題。


- 修正在包含數學方程式的文字內使用朗讀程式時可能發生的問題。


- 修正針對使用者停用 GCC 聽寫的問題


- 修正使用者在開啟先前開啟的檔案具有未儲存的編輯但現在檔案已遭到刪除時，無法儲存檔案的問題。 修正之後，使用者將會收到一則友善的訊息，通知他們已刪除該檔案，因此使用者可以選擇捨棄變更，或將檔案另存為新檔。


- 修正離線開啟 SyncBacked 檔案，然後於儲存檔案之前，在應用程式中重新命名檔案時重新命名失敗的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2101-april-13"></a>版本 2101：4 月 13 日
*版本 2101 (組建 13628.20664)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2101-march-09"></a>版本 2101：3 月 9 日
*版本 2101 (組建 13628.20528)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題


### <a name="outlook"></a>Outlook

- 我們已修正會導致加密圖示無法對使用僅加密選項傳送的電子郵件顯示的問題。


- 我們已修正會導致在使用者取消選取數位簽章選項之後，仍以數位簽章方式傳送郵件的問題。


- 我們已修正會導致在 OWA 中顯示正確的預設簽章時發生問題的問題。


- 我們已修正會導致雲端設定使用者在更新設定時遇到懸置的問題。


- 我們已修正使用者在 Outlook 中進行搜尋時，有時候會導致應用程式未預期關閉的問題。


- 我們已修正會導致在其設定檔中具有大型階層的共用或委派信箱的使用者遇到懸置的問題。


- 我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 未預期關閉的問題。


### <a name="project"></a>Project

- 修正將成本資源指派給里程碑工作時，比較基準成本沒有正確彙總的問題。


- 修正在 [團隊規劃] 檢視中工作沒有顯示邊框的問題。


- 修正在 [團隊規劃] 檢視中拖放工作不起作用的問題。


### <a name="office-suite"></a>Office 套件

- 修正與媒體控制器事件通知相關的問題。


- 修正與媒體播放程式引擎時間相關的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2012-march-09"></a>版本 2012：3 月 9 日
*版本 2012 (組建 13530.20628)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **要求使用者套用敏感度標籤：** 當使用者的組織原則要求時，會提示使用者套用敏感度標籤。

### <a name="powerpoint"></a>PowerPoint

- **要求使用者套用敏感度標籤：** 當使用者的組織原則要求時，會提示使用者套用敏感度標籤。

### <a name="word"></a>Word

- **要求使用者套用敏感度標籤：** 當使用者的組織原則要求時，會提示使用者套用敏感度標籤。


## <a name="version-2012-february-09"></a>版本 2012：2 月 9 日
*版本 2012 (組建 13530.20528)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。 [深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。 [深入了解](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。 [深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **在連續會議之間置入時間：** 將會議預設為延後 5-10 分鐘開始，讓出席者有時間休息，或前往下一個地點。 [深入了解](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- **敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。

- **每個線上會議** 更新行事曆設定，使您建立的每個會議都預設為 Teams 會議，這樣您就不必再記得按一下 [Teams 會議] 選項。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。 [深入了解](/microsoft-365/compliance/sensitivity-labels)

- **每個線上會議** 更新行事曆設定，使您建立的每個會議都預設為 Teams 會議，這樣您就不必再記得按一下 [Teams 會議] 選項。

- **新的會議室尋找工具：** 依不同功能搜尋會議室。

- **新的會議室和工作區預約體驗：** 會議室預約體驗已更新，透過它我們新增了功能，以讓您也能夠排程個別工作區


### <a name="powerpoint"></a>PowerPoint

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。 [深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br />在[部落格文章](https://insider.office.com/zh-TW/blog/svg-content-office-third-party-apps)中查看詳細資料

- **敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。 [深入了解](/microsoft-365/compliance/sensitivity-labels)

### <a name="visio"></a>Visio

- **新 Azure 樣板和圖案：** 我們新增了更多的樣板來協助您建立最新的 Azure 圖表。 [深入了解](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a>Word

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。 [深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能目前可供 GCC 和 GCC-H 環境中的客戶取得。 [深入了解](/microsoft-365/compliance/sensitivity-labels)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 此變更解決了在方程式中正確顯示字型的問題。


- 修正當某些使用者在共同撰寫時會錯誤地看到通知他們檔案新版本的訊息列之問題。


- 修正在開啟含有 Excel 4.0 巨集的 Excel 增益集檔案時，Excel 可能會停用巨集而不提示的問題。


- 修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題。


- 修正使用樞紐分析表的「將值顯示為」功能表時，Excel 可能會意外關閉的問題。


- 我們已修正破壞了一些舊的 Excel 4.0 和 Excel 5.0 巨集以及一些對 dialogsheets.show 的 VBA 呼叫的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致在提示使用者儲存已編輯的簽名後，該動作會無法執行的問題。


- 我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 異常關閉的問題。


- 我們已修正會導致某些客戶在載入行事歷時遇到停滯的問題。


- 我們修正了導致在其設定檔中具有大型階層的共用或委派信箱的使用者遇到停止回應的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正一個問題，即在 QAT 中新增的字型大小命令在更新時，會自動完成到最接近的已定義字型大小。


- 此變更解決了在方程式中正確顯示字型的問題。


- 此變更解决對某些幾何圖形套用 [合併圖案] 作業時路徑填充的問題。


### <a name="office-suite"></a>Office 套件

- Anaheim WebView 目前尚不支援 Windows 資訊保護(WIP)。 有了此修正程式，Office addin 平臺便會回到處於 WIP 啟用環境中的低層級 WebView。 根據客戶的電腦環境，這可以是 Edge Spartan WebView 或 Trident WebView。 兩個低層級 WebViews 皆支援 WIP。


- 優化的二進位大小。


- 修正檔案關閉順序，使所有相互依存的元件都能正常關閉。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-february-09"></a>版本 2011：2 月 9 日
*版本 2011 (組建 13426.20658)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)

## <a name="version-2011-january-12"></a>版本 2011：1 月 12 日
*版本 2011 (組建 13426.20526)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a>Excel

- **建立變數以在公式中使用：** 使用 LET 函數改善效能、可讀性及可組合性。 此函數可讓您在新的或現有的公式中建立命名變數。 [深入了解](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />在[部落格文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看詳細資料

- **在 Power Query 中建立自訂資料類型：** 使用任何資料來源建立自訂資料類型，可讓您將多個相關資料部分載入到一個欄位。 [深入了解](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br />在[部落格文章](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)中查看詳細資料

- **在來源查詢之後命名新的工作表：** 將資料載入新工作表時，會根據來源查詢的名稱來為工作表命名。

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a>OneNote

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a>Outlook

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


### <a name="powerpoint"></a>PowerPoint

- **影片庫：** 在應用程式內使用精選的免版稅影片素材庫來提升您的文件。

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a>Project

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a>Publisher

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a>Visio

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a>Word

- **自動切換 Office 佈景主題：** Office 可以自動切換佈景主題，以符合您的 Windows 10 佈景主題設定。 移至 [檔案] > [帳戶]，然後在 [Office 佈景主題] 下拉式清單底下，選擇 [使用系統設定]。 [深入了解](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正了以下問題：Excel 錯誤地顯示檔案新版本可用的訊息列，並強制使用者將變更儲存到活頁簿的副本中或捨棄變更。


- 修正當開啟含有 Excel 4.0 巨集的 Excel 增益集檔案時，Excel 可能會在不提示的情況下停用巨集的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致某些使用者未設定一或多個簽章時，在 [簽名] 下拉式清單中看不到任何簽名的問題。


- 我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含內容。  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。 REG_DWORD IncludeFileTimesInDataObject。 0 = 不包含 filetimes。 1 = (預設) 包含 filetimes。


- 修正當回覆含有「Azure 資訊保護」保護標籤的郵件時，導致內嵌影像消失的問題。


- 我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。


- 我們已修正傳送任務中的狀態報表時，導致 [收件者] 欄位為空白的問題。


- 我們已修正會導致某些會議的原始出席者在另一個出席者轉寄會議時，收到取消通知的問題。


### <a name="powerpoint"></a>PowerPoint

- 已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。


- 修正在複製含有新錄製音訊的投影片後，儲存檔案時發生錯誤的問題。


- 我們已修正 Slide.Shapes.AddMediaObject2 會導致舊版影片格式 (MPG-1、Mpeg-2) 發生當機的 VBA 問題。


- 此變更解決了處理載入影片期間可能發生錯誤的問題。


- 修正將方程式從 Word 複製/貼上到 PowerPoint 時發生錯誤的問題。


### <a name="project"></a>Project

- 已修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。


### <a name="word"></a>Word

- 修復影響 Word 的最佳化閘道所暴露的宣告錯誤。


- 我們已修正文件樣式會以範本中的其他樣式取代的問題。


- 此變更解決編輯檔時游標的問題。


- 修正將方程式從 Word 複製/貼上到 PowerPoint 時發生錯誤的問題。


### <a name="office-suite"></a>Office 套件

- 已修復在某些較舊的版本上安裝較新版的 Office 時，可能會造成功能受損 (例如由於遺失登錄專案而無法使用 Power Query) 的問題。


- 修正當快取中的 URL 與 OneDrive 中的 URL 不相符時，檔案將被開啟為 NOT SyncBacked 的問題。


- 我們已修正 SaveRequestManagerCam 導致應用程式會關閉，而非回傳錯誤的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-january-12"></a>版本 2010：1 月 12 日
*版本 2010 (組建 13328.20550)*

安全性更新列於[此處](./microsoft365-apps-security-updates.md)



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE END)

> [!NOTE]
> 如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|MEC|生產|功能|版本16.0.14026.20334|-2105-7-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13929.20408|version-2104-june-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13901.20516|version-2103-may-11|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13628.20528|version-2101-march-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13530.20528|version-2012-february-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13426.20526|version-2011-january-12|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13328.20478|version-2010-december-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13231.20514|version-2009-november-10|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13127.20638|version-2008-october-13|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
