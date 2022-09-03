---
title: 每月企業通道版本的版本資訊
ms.author: nidos
author: nidos
manager: nidos
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 Microsoft 365 Apps 每月企業通道版本的版本資訊
ms.openlocfilehash: d53335eb31a41aba958db68438ff27c2b207df85
ms.sourcegitcommit: a4ba502347c4035df79b54846a8e2d59a0c26149
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/02/2022
ms.locfileid: "67587542"
---
# <a name="release-notes-for-monthly-enterprise-channel"></a>每月企業通道的版本資訊

這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的每月企業通道更新。


[//]: # (DO NOT REMOVE)

## <a name="version-2206-august-18"></a>版本 2206：8 月 18 日
*版本 2206 (組建 15330.20306)*



注意：此版本的可用性有限，因為其發佈時間超出當月第二個星期二的一般發行頻率。 當每月企業通道版本在頻外發佈時，我們不會將它們推送至客戶，而是改為讓它們可供隨選安裝。 使用工具來管理部署的客戶可以使用這些工具，將此組建散發給其組織。 使用者也可以檢查更新，以手動 [方式更新](https://support.microsoft.com/office/install-office-updates-2ab296f3-7f03-43a2-8e50-46de917611c5)裝置。



安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **減少條件式格式設定規則的不必要片段：** 我們將在將複製的儲存格貼到該儲存格範圍時，減少連續儲存格範圍中條件式格式設定規則的片段。

- **在資源受限的裝置上優化 Excel 重新計算:** 在資源受限的裝置上，(兩個核心或少於 8 GB 的 RAM 或更少)，Excel 現在預設會在單一線程上執行計算，讓重新計算更加優化。 在大部分情況下，使用者應該會看到這些裝置上的計算速度明顯變快。 請注意，在某些情況下需要大量計算，使用者可能會想要將計算執行緒數目設定為 2，以覆蓋此預設值。 如需詳細資訊，請參閱 Microsoft 支援服務網站上 [[進階選項]](https://support.microsoft.com/en-us/office/advanced-options-33244b32-fe79-4579-91a6-48b3be0377c4) 頁面的 [公式] 區段。

### <a name="outlook"></a>Outlook

- **在 Outlook 中使用建議的回覆：** 當您收到可以簡短回覆的電子郵件訊息時，Outlook 可以建議三個回應，只要按幾下滑鼠即可回覆。[深入了解](https://support.office.com/article/19316194-0434-43ba-a742-6b5890157379)<br />在[部落格文章](https://insider.office.com/en-us/blog/reply-faster-using-suggested-replies-in-outlook)中查看詳細資料

- **關閉建議回覆：** Outlook [使回覆更為簡單快速](https://insider.office.com/blog/reply-faster-using-suggested-replies-in-outlook) 透過提供僅需幾個字回覆的簡短建議回覆郵件，讓回覆電子郵件更為快速。 部分使用者可能不想看到此選項，因此現在可以關閉此功能。 若要這麼做，請選取檔案 > 選項> 郵件，前往回覆和轉寄區段，然後清除顯示建議的回覆核取方塊。

### <a name="word"></a>Word

- **使用新式註解來改善共同作業：** 您可以控制何時將註解傳送給共同作者、輕鬆 @提及通知，以及在 Word、Excel 和 PowerPoint 之間有一致的註解體驗來保持生產力。 [深入了解](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)<br />在[部落格文章](https://insider.office.com/en-us/blog/modern-commenting-in-word)中查看詳細資料

### <a name="office-suite"></a>Office 套件

- **新增 SketchUp 檔案至 Office 作品**：SketchUp 是熱門的 3D 圖形程式，可輕鬆地建立可共用的概念設計，例如工業設計、產品設計，以及土木和機械工程中所使用的脈絡完整的架構模型和其他圖形。 現在，這是第一次可以將 SketchUp 圖形 (.skp 檔案) 整合至您在 Word、Excel、PowerPoint 和 Outlook 中您的作品！<br />在[部落格文章](https://insider.office.com/en-us/blog/add-sketchup-files-to-office-creations)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正開啟 ACCDE/MDE 檔案時的問題。 使用者可能會收到錯誤訊息，其文字為「要求的類型文件庫或精靈不是 VBA 專案」。 [深入了解](https://support.microsoft.com/en-us/topic/error-when-trying-to-open-an-accde-mde-file-created-in-a-different-version-of-access-f4cd36cd-549e-42ba-b75a-dfe964294a81)


### <a name="excel"></a>Excel

- 我們已修正資料編輯列中的視覺問題。


- 我們已修正嘗試從大型 XML 資料來源使用 Power Query 重新整理資料時，可能會發生錯誤的問題。


- 我們已修正在啟用凍結窗格時，Excel 會使用非預期的大量 CPU，但並非每個凍結窗格都在畫面上顯示的問題。


- 我們已修正應用程式與字型互動時意外關閉檔案的問題。


### <a name="onenote"></a>OneNote

- 我們已修正導致應用程式意外關閉的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用瀏覽至位置時，儲存為不需要強制敏感度標籤的問題。


- 我們已修正當其他人共同撰寫時，變更文件的敏感度標籤，可能會失去挑選的敏感度標籤的問題。


### <a name="visio"></a>Visio

- 我們已修正 Visio 中導致應用程式在重複放大和縮小時停止回應的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正當您將滑鼠停留在人員名稱上以顯示連絡人卡片時，導致 Office 應用程式意外關閉的問題。

- 我們已修正在解決許多從 OneDrive 或 SharePoint 開啟 Word、Excel 或 PowerPoint 文件時，會導致意外關閉的案例問題。


## <a name="version-2205-august-09"></a>版本 2205：8 月 09 日
*版本 2205 (組建 15225.20394)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)

## <a name="version-2205-july-26"></a>版本 2205: 7 月 26 日
*版本 2205 (組建 15225.20370)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access


- 我們已修正嘗試開啟在 Access 中建立的 ACCDE 或 MDE 檔案時，導致錯誤的問題。 如需詳細資訊，請參閱 [嘗試開啟以不同 Access 版本建立之 ACCDE/MDE 檔案時發生錯誤。](https://support.microsoft.com/topic/f4cd36cd-549e-42ba-b75a-dfe964294a81)




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2205-july-12"></a>版本 2205: 7 月 12 日
*版本 2205 (組建 15225.20356)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **更快找到資料：** 自動篩選功能現在明顯加快了! 這些改善是藉由減少記憶體使用量，以及優化篩選條件比較演算法所進行的呼叫所達成。 在記憶體較少或 CPU 記憶體輸送量較慢的低階裝置上，優化特別明顯。 [深入了解](https://support.office.com/article/7d87d63e-ebd0-424b-8106-e2ab61133d92)

- **從狀態列複製資料：** 從狀態列快速從彙總複製資訊，例如「Sum」、「Average」和「Count」。<br />在[部落格文章](https://insider.office.com/en-us/blog/copy-values-quickly-from-the-status-bar-in-excel-for-windows)中查看詳細資料

### <a name="outlook"></a>Outlook


- **在行事曆上更快速地尋找活動：** 行事曆搜尋的改良功能表示可以更快速且更輕鬆地尋找事件，例如數列的下一個項目。


### <a name="project"></a>Project

- **未授權的使用者現在會處於檢視器模式：** 若為共用電腦啟用，如果裝置上也啟用了檢視器模式，未授權的使用者將會處於檢視器模式，而不是降低功能模式。


- **檢視器模式可辨識授權的使用者：** 檢視器模式現在會辨識使用者是否具有產品的有效授權，並將為使用者提供已啟用且功能完整的產品版本。 裝置上其他未授權的產品將維持在檢視器模式。


### <a name="visio"></a>Visio

- **未授權的使用者現在會處於檢視器模式：** 若為共用電腦啟用，如果裝置上也啟用了檢視器模式，未授權的使用者將會處於檢視器模式，而不是降低功能模式。


- **檢視器模式可辨識授權的使用者：** 檢視器模式現在會辨識使用者是否具有產品的有效授權，並將為使用者提供已啟用且功能完整的產品版本。 裝置上其他未授權的產品將維持在檢視器模式。


### <a name="office-suite"></a>Office 套件

- **未授權的使用者現在會處於檢視器模式：** 若為共用電腦啟用，如果裝置上也啟用了檢視器模式，未授權的使用者將會處於檢視器模式，而不是降低功能模式。


- **檢視器模式可辨識授權的使用者：** 檢視器模式現在會辨識使用者是否具有產品的有效授權，並將為使用者提供已啟用且功能完整的產品版本。 裝置上其他未授權的產品將維持在檢視器模式。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正在嘗試開啟 Viva Insights 增益集時，導致某些客戶看到灰色方塊的問題。


- 我們已修正來自使用者先前在 SA 頻道能即時執行的現有程式碼，在目前的頻道卻需花 13 分鐘來執行的問題。


- 我們已修正在使用 Access 資料庫引擎 OLEDB API 與包含 SharePoint 清單之連結的資料庫時，可能會導致應用程式意外關閉的問題。


- 我們已修正嘗試在唯一識別碼欄中支援 Unicode 字元時所造成的問題。


- 我們已修正 Dataverse 在 2019 功能區中顯示的問題。


- 我們已修正提示「沒有目前記錄」錯誤和其他訊息的問題。


### <a name="excel"></a>Excel

- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 我們已修正使用特定舊版 Windows 11 時，在 Excel 和 Project 中呈現的問題。


- 我們已修正在具有圖表工作表的活頁簿上執行 VBA 指令碼/增益集時，可能會導致 Excel 意外關閉的問題。


- 我們已修正 .xls 格式的共用活頁簿可能會不當合併變更的問題。


- 我們已修正 AMSI 掃描會導致應用程式意外關閉的問題。


### <a name="onenote"></a>OneNote

- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


### <a name="outlook"></a>Outlook

- 我們已修正使用 [開啟共用行事曆] 時，未在瀏覽窗格中選取行事曆的問題。


- 我們已修正使用者無法將會議室信箱新增至行事曆的問題。


- 我們已修正在 GCC-High 環境中導致會議室尋找工具無法載入的問題。


- 我們已修正導致使用者的問題，因此請參閱錯誤訊息「嘗試的操作失敗。 搜尋 LDAP 通訊錄時找不到物件」。


- 我們已修正啟用共用行事曆改進功能時，導致給會議室信箱代理人的所有轉寄會議邀請上顯示「不需要回應」的問題。


- 我們已修正導致使用者在某些情況下，會看到呈現多個共用行事曆複本的問題。


- 我們已修正即使具有正確權限，導致委派仍無法開啟共用連絡人資料夾的問題。


- 我們已修正會導致使用者看到「無法執行要求的作業...」錯誤的問題當嘗試展開本機連絡人群組時。


- 我們已修正導致某些 Outlook 使用者在間歇性地開機之後，突然遇到關閉的問題。


- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


### <a name="project"></a>Project

- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 已修正在已啟用共用電腦啟用和檢視器模式的裝置上，授權使用者不正確地置於檢視器模式的問題。


### <a name="visio"></a>Visio

- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 已修正在已啟用共用電腦啟用和檢視器模式的裝置上，授權使用者不正確地置於檢視器模式的問題。


### <a name="word"></a>Word

- 我們已修正了減少與具有相同超連結之檔的合併衝突的問題。


- 我們已修正標頭巢狀欄位在捲動時顯示不正確的問題。


- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 我們已修正 UI 有時候停止在 arm64 裝置上演繹的問題。


- 我們已修正在少數共同撰寫者實例中，某些註解的回復直到下次開啟文件時才會顯示的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正 SVG 物件的問題，以處理文字錨點結束屬性並正確維持目前文字位置。


- 我們已修正 Office 呈現程式碼中關閉的問題。


- 我們已修正在已知且預期字型下載在下載期間停止運作時嘗試下載字型的問題，這會造成使用不必要的資源。


- 我們已修正在 Excel 中開啟字型大小下拉式清單時，強調顯示字型大小不是文件中目前選取的字型大小的問題。


- 已修正在已啟用共用電腦啟用和檢視器模式的裝置上，授權使用者不正確地置於檢視器模式的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2204-july-12"></a>版本 2204: 7 月 12 日
*版本 2204 (組建 15128.20312)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2204-june-14"></a>版本 2204：6 月 14 日
*版本 2204 (組建 15128.20280)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="word"></a>Word

- **只追蹤您在文件中的變更：** 當您共同作業時，有時候您只想追蹤自己的變更，而不想強制此設定追蹤其他人的部分。 若只要追蹤您的變更，請前往 [校閱] 索引標籤，選取 [追蹤修訂]，然後選擇 [只有我]。 


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正使用特定舊版 Windows 11 時，在 Excel 和 Project 中呈現的問題。


- 我們已修正在具有圖表工作表的活頁簿上執行 VBA 指令碼/增益集時，可能會導致 Excel 意外關閉的問題。


- 我們已修正導致 Excel 耗用過多記憶體的問題。


### <a name="outlook"></a>Outlook

- 我們已修正使 Outlook 事件型增益集無法正常運作的問題。


- 我們已修正協助使用者找到正確的設定，以管理協力廠商會議提供者的預設線上會議選項的問題。


- 我們已修正當事件型增益集在背景中執行時，在回覆或轉寄電子郵件時應用程式意外關閉的問題。


- 我們已修正在嘗試開啟 Viva Insights 增益集時，導致某些客戶看到灰色方塊的問題。


- 我們已修正使用 [開啟共用行事曆] 時，未在瀏覽窗格中選取行事曆的問題。


- 我們已修正導致使用者在刪除資料時意外遇到關閉的問題。


- 我們已修正會導致使用者在嘗試回應特定連絡人時，遇到意外關閉的問題。


- 我們已修正導致使用者從委派分組討論區信箱轉寄出的所有會議邀請上看到特定「不需要回應」的問題。


- 我們已修正使用者在嘗試開啟具有編輯者或委派權限的共用連絡人資料夾時收到錯誤訊息的問題。


- 我們已修正會導致使用者看到「無法執行要求的作業...」錯誤的問題當嘗試展開本機連絡人群組時。


- 我們已修正在連線到沒有服務 URL 的商務用 OneDrive端點時，導致 Outlook 在啟動期間意外關閉的問題。


- 我們已修正會導致歐盟使用者看到人員卡片中遺失資訊的問題。


### <a name="word"></a>Word

- 我們已修正未登入使用者的 [大聲朗讀] 會意外關閉的問題。


- 我們已修正刪除段落標記之後，文件會捲動至結尾的問題。


- 我們已修正 Office「插入螢幕擷取畫面」 顯示 Office Apps 的空白/不完整螢幕擷取畫面的問題；我們已修正 Office 應用程式的部分 Windows 工作列縮圖螢幕擷取畫面可能會顯示空白的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正 Direct2D 和 Direct3D 互通性的多執行緒相關問題。


- 我們已修正在按一下滑桿時，允許新增漸層停駐點的問題。


- 我們已修正當 PowerShell 停用時，使用者會無法安裝 M365 應用程式的問題。


- 我們已修正在更新期間造成「發佈套件失敗」錯誤，導致檔案類型關聯遺失的問題。


- 我們已修正字型下拉式清單無法正確反映圖形中選取的字型的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2203-june-14"></a>版本 2203：6 月 14 日
*版本 2203 (組建 15028.20282)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正當事件型增益集在背景中執行時，在回覆或轉寄電子郵件時應用程式意外關閉的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2203-may-10"></a>版本 2203：5 月 10 日
*版本 2203 (組建 15028.20248)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Power BI 要求存取的改良功能:** 我們已為建立連接到 Power BI 資料集之樞紐分析表的使用者升級體驗。 在改善體驗之前，當使用者嘗試重新整理連接到他們無法存取之資料集的樞紐分析表時，會看到一般錯誤訊息。 現在會出現一個對話方塊，通知使用者他們沒有資料集的存取權，並允許他們點擊連結以向擁有者要求存取權。 一旦獲得存取權，使用者就可以返回樞紐分析表，然後重新更新以繼續分析。

### <a name="outlook"></a>Outlook

- **撰寫郵件時節省時間：** Outlook 會顯示書寫建議，協助您快速撰寫郵件。 若要接受建議，只需使用 Tab 鍵。<br />在[部落格文章](https://insider.office.com/en-us/blog/text-predictions-in-word-outlook)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正可能導致使用 DAO 或 OLEDB 介面讀取 Access 資料庫的應用程式記憶體使用量成長快速的問題。在某些情況下，這可能會導致異常程式終止。


- 我們已修正導致使用 OLEDB 介面的自訂應用程式開啟包含 SharePoint 清單連結的 Access 資料庫意外關閉的問題。


### <a name="excel"></a>Excel

- 我們已修正使用特定舊版 Windows 11 時，在 Excel 和 Project 中呈現的問題。


- 我們已修正復原的檔案以唯讀方式開啟的問題。


### <a name="outlook"></a>Outlook

- 我們已修正將多個訊息項目從 [焦點] 移至 [其他] 或從 [其他] 移至 [焦點] 時，導致使用者只看到訊息子集移動的問題。


- 我們已修正會導致使用者在回應特定連絡人時，遇到停止回應的問題。


- 我們已修正導致在部分診斷案例中，使用者在 Outlook 中預期停止回應的問題。


- 我們已修正會導致歐盟使用者看到人員卡片中遺失資訊的問題。


- 我們已修正在使用雲端設定時，導致某些切換類型選項進行錯誤同步處理的問題。


- 我們已修正使用 [僅加密] 和 [不要轉寄]範本的訊息透過物件模型傳回未預期權限的問題。


- 我們已修正導致「移至其他」功能停止正常回應的問題。


- 我們已修正使 Outlook 事件型增益集無法正常運作的問題。


### <a name="project"></a>Project

- 我們已修正應用程式在未完成資源撫平時停止回應的問題。


- 我們已修正遮罩分隔符號與清單分隔符號相符時，會使用星號 (*) 的問題。 在篩選器中 * 用於規則運算式，如果其包含值，就會導致錯誤和意外行為。 管道 (|) 現在已使用。


- 我們已修正應用程式開啟不再可用的畫面，導致專案隱藏的問題。


- 我們已修正當使用者無法開啟專案時，導致應用程式意外關閉的問題。


### <a name="word"></a>Word

- 我們已修正導致共用行事曆在新增後處於未選取狀態的問題。


- 我們已修正在其他應用程式中顯示內嵌 Excel 試算表的問題。


- 已修正使用 97-2003 檔案格式載入PowerPoint檔案時，無法辨識 VBA 專案數位簽章的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正錄製投影片放映時的穩定性問題。


- 我們已修正停止錄製投影片放映時的穩定性問題。


- 我們已修正 Direct2D 和 Direct3D 互通性的多執行緒相關問題。


- 我們已修正字型下拉式清單無法正確反映圖形中選取的字型的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2202-may-10"></a>版本 2202：5 月 10 日
*版本 2202 (組建 14931.20392)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


## <a name="version-2202-april-12"></a>版本 2202: 4 月 12 日
*版本 2202 (組建 14931.20274)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Lambda：不含程式碼自訂函數：** Lambda 函數可讓您接受任何現有的公式或運算式，並將之轉換成具有名稱的自訂函數。使用 Lambda 函數輕鬆重複使用並更新試算表中的邏輯。<br />在[部落格文章](https://insider.office.com/en-us/blog/lambda-excel-custom-functions)中查看詳細資料

- **Lambda: 協助程式函數:** 7 個運用 Lambdas 的新功能，以及在撰寫 Lambda 解決方案時提供協助!<br />在[部落格文章](https://insider.office.com/en-us/blog/new-lambda-functions-available-in-excel)中查看詳細資料

### <a name="powerpoint"></a>PowerPoint

- **錄製有旁白的影片：** 使用預先錄製的影片和旁白，讓您的下一次簡報更具活力且更吸引人。 或預先錄製整個簡報，以確保在簡報當天順利演講。 [深入了解](https://support.office.com/article/ddc4432c-79f6-4add-b85e-1009815d955c)<br />在[部落格文章](https://insider.office.com/en-us/blog/tell-your-story-with-video-recording-in-powerpoint)中查看詳細資料

### <a name="office-suite"></a>Office 套件

- **Office 應用程式的新視覺更新:** 我們很高興宣佈針對 Windows 11 版 Office 桌面應用程式進行完整的視覺更新! 根據客戶的意見，此更新在所有您最愛的 Office 應用程式中皆提供簡單且更一致的體驗，讓您能專注於工作。 全新的外觀以 [Fluent Design](https://medium.com/microsoft-design/m365future-815cf30a8be) 原則為基礎並與新的 Windows 11 具有一致性，能為您的電腦提供更順暢的體驗。 <br/>
[深入了解](https://insider.office.com/blog/visual-update-in-office-for-windows-now-available-in-current-channel-preview)

- **參與經驗：針對受保護通道上的企業客戶擴充支援：** 這項功能延伸了現有的功能，可協助使用者透過參與體驗到受保護的通道，從 Office 獲得最大價值。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們修正了應用程式停止運作的問題，並產生錯誤訊息，例如「無法開啟其他資料庫」；此問題也可能會導致 Access 無法正確關閉。


- 我們已修正會造成使用 OLEDB 介面的自訂應用程式開啟包含 SharePoint 清單連結的 Access 資料庫意外關閉的問題。


### <a name="excel"></a>Excel

- 我們已修正顯示某些 SVG 檔案的問題。


- 我們已修正使用自訂命令列可能會導致 Excel 意外關閉的問題。


- 我們已修正 [工作表] 檢視有時候會接收來自其他共同作者的排序和篩選的問題。


- 我們已修正了一個問題，以調整瀑布圖中資料數列的漸層填滿與直條圖中資料數列的漸層填滿如何對齊。


- 我們已修正當來源資料直接輸入圖表而非來自儲存格範圍時，圖表座標軸上的日期不會出現的問題。


### <a name="outlook"></a>Outlook

- 我們已修正在某些情況下，導致 Outlook 在關機期間意外關閉的問題。


- 我們已修正啟用 REST 共用行事曆功能時，已移除的共用行事曆會再次出現的問題。


- 我們已修正導致連絡人卡片成員資格清單不會正確顯示的問題。


- 我們修正了導致使用者在切換資料夾時因檢視設定損毀而出現效能問題之問題。


- 我們已修正在預期自訂圖示時，會針對附加的郵件顯示預設圖示的問題。


- 進行了一項資料變更，在英國行事曆中包含了新的英國假日。


- 我們已修正導致在部分診斷案例中，使用者在 Outlook 中預期停止回應的問題。


- 我們已修正導致螢幕閱讀器無法存取特定的智慧連結註標的問題。


- 我們已修正導致「索引過期」訊息太常顯示的問題。


- 我們已修正在使用雲端設定時，導致某些切換類型選項進行錯誤同步處理的問題。


- 我們已修正收到的電子郵件不會包含開啟郵件的連結的問題。


- 我們已修正使用 [僅加密] 和 [不要轉寄]範本的訊息透過物件模型傳回未預期權限的問題。


- 我們已修正顯示某些 SVG 檔案的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正從 C2R 安裝之 PowerPoint 在 [資訊] | [屬性] | [進階屬性] 對話方塊中顯示公司資訊的問題。


- 我們已修正儲存 PPAM 檔案類型時造成問題的案例。


### <a name="project"></a>Project

- 我們已修正問題，因此使用者在列印甘特圖上的進度線時，應該不會再遇到問題。


- 我們已修正使用者會看到安全性對話方塊，指出專案有一或多個資料來源的連結，即使專案沒有使用中連結的問題。現在，對話方塊只會在有使用中連結時出現。


### <a name="publisher"></a>發行者

- 我們已修正顯示某些 SVG 檔案的問題。


### <a name="visio"></a>Visio

- 我們已修復此問題：使用者現在可以順利插入圖表，而不會出現應用程式意外關閉的任何問題。


### <a name="word"></a>Word

- 我們已修正傳送電子郵件通知給留言已獲得其他使用者回覆的使用者時的問題。


- 我們已修正當開啟具有數千個追蹤變更的 Word 檔時的效能問題。


- 我們已修正導致共用行事曆在新增後處於未選取狀態的問題。


- 我們已修正在 Word 中 SVG 檔案可能會顯示為中斷連結的問題 (Red-X)。


- 我們已修正包含外部內容的 SVG 影像可能無法顯示的問題。


- 我們已修正顯示某些 SVG 檔案的問題。


- 我們已修正在其他應用程式中顯示內嵌 Excel 試算表的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正在啟動或錄製投影片放映時，與 Power BI 控制項和表單做為投影片內容相關的穩定性問題。


- 我們已修正 Direct2D 和 Direct3D 互通性的多執行緒相關問題。


- 我們已在 Outlook 預覽窗格中修正問題，允許 SVG 影像正確地轉譯。


- 我們已修正記憶體可能損毀之輸入來源的捲動繫結相關問題。


- 我們已修正影響在 Project 中自訂檢視顯示的問題。


- 我們已修正字型下拉式清單無法正確反映圖形中選取的字型的問題。


- 我們已修正會導致連絡人卡片無法顯示的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2201-april-12"></a>版本 2201: 4 月 12 日
*版本 2201 (組建 14827.20246)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)

## <a name="version-2201-march-08"></a>版本 2201: 3 月 8 日
*版本 2201 (組建 14827.20220)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **預設會停用 Excel 4.0 (XLM) 宏，以改善 Microsoft 365 客戶的安全性。** 為了協助保護客戶，預設會在 Microsoft 365 中停用 Excel 4.0 (XLM) 宏。 我們建議您將這些巨集遷移至最新版本的 Microsoft Visual Basic for Applications (VBA)。 [深入了解](https://support.office.com/article/ba8924d4-e157-4bb2-8d76-2c07ff02e0b8)

- **Office 應用程式現在支援 OpenDocument 格式 (ODF) 1.3：** ODF 1.3 對 OpenDocument 格式帶來許多改良功能，而且這些功能現在都可在 Word、Excel 及 PowerPoint (副檔名 .odt、.ods 和 .odp) 中受到支援。<br />在[部落格文章](https://insider.office.com/en-us/blog/office-apps-now-support-opendocument-format-odf-1-3)中查看詳細資料

### <a name="powerpoint"></a>PowerPoint

- **使用「簡報者教練」排練簡報:** 取得有助於維持對象參與的項目的意見反應，例如節奏、語調、填充字詞、敏感詞語等等。[深入了解](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)<br />在[部落格文章](https://insider.office.com/en-us/blog/presenter-coach-windows)中查看詳細資料

### <a name="word"></a>Word

- **解碼縮寫，而不需離開 Word：** 當您遇到縮寫時，Word 會試著根據其他人的使用方式來給予定義。[深入了解](https://support.office.com/article/89062352-e1ce-4f59-b58c-f94869521404)

- **使用編輯器來校對選取的文字:** 檢查拼寫、語法，並只對文件中選取的文字取得撰寫建議。<br />在[部落格文章](https://insider.office.com/en-us/blog/proof-selected-text-in-a-word-document)中查看詳細資料

### <a name="office-suite"></a>Office 套件

- **使用您的語音來傳送電子郵件和 @提及：** 新語音命令可讓您在聽寫時傳送郵件並 @提及其他人。 
<br />請參閱 [部落格文章](https://insider.office.com/en-us/blog/use-voice-commands-to-speed-up-email-dictation-in-outlook) 中的詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們修正了執行應用程式時可能導致錯誤的問題。


- 此更新修正了應用程式停止運作的問題，並產生錯誤訊息，例如「無法開啟其他資料庫」；此問題也可能會導致 Access 無法正確關閉。


### <a name="excel"></a>Excel

- 我們修正了當樞紐分析表中有隱藏的欄位時，小計最佳化的問題。


### <a name="outlook"></a>Outlook

- 我們修正了造成使用者無法開啟已套用數位版權管理原則之郵件的問題。


- 我們已修正收到的電子郵件不會包含開啟郵件的連結的問題。


- 我們修正了載入角色時導致停止回應的問題。


- 我們已修正導致螢幕助讀程式無法存取特定的 [智慧連結] 圖說文字上的問題。


- 我們已修正了資料夾階層未能同步處理超大型主要信箱 (超過 10000 個資料夾) 所有資料夾的問題。


### <a name="project"></a>Project

- 我們已修正使用者進入無法儲存的狀態問題。 此修正使得使用者一律可以儲存其工作。


- 我們已修正一個問題，使用者現在可以將專案儲存至 Project Web 應用程式，即使離線檔案中資源的名稱符合企業資源亦然。


### <a name="word"></a>Word

- 我們修正了重複樣式會套用 Normal，而不是重複樣式的問題。


### <a name="office-suite"></a>Office 套件

- 此更新修正 AIP UL 用戶端使用時受保護共同撰寫中的安全性問題。


- 我們修正了在無視窗模式中以程式化方式開啟簡報時，可能無法載入連結影像的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2112-march-08"></a>版本 2112: 3 月 8 日
*版本 2112 (組建 14729.20360)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)

## <a name="version-2112-february-08"></a>版本 2112：2 月 8 日
*版本 2112 (組建 14729.20322)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用動作手寫筆快速編輯：** 您可以使用動作手寫筆直接在儲存格中書寫，以會自動轉換成 Excel 資料的筆跡記下資料。

- **Word/Excel/PowerPoint 中的 DLP 原則提示:** 現在可以透過應用程式偵測到其他已設定為 OneDrive 和 SharePoint 資料外洩防護 (DLP) 部分原則的敏感性資訊類型, 以顯示原則提示。此更新也會提供準確性改善和全球化支援。 [[深入了解]](/microsoft-365/compliance/sensitive-information-type-learn-about)

### <a name="outlook"></a>Outlook

- **語文法檢查鼎力相助**：Outlook 會在你鍵入時標記文法錯誤，因此你只需按一下就可以套用建議。[深入了解](https://support.office.com/article/ddbadc42-4637-451d-b3f4-ecf295036fa9)<br />在[部落格文章](https://insider.office.com/en-us/blog/grammar-and-style-suggestions-available-in-outlook)中查看詳細資料

- **依訊息擁有者刪除交談：** 此功能可讓您依訊息擁有者刪除交談。

- **單鍵寫作建議：** 只要按一下，就能套用寫作建議。 編輯器會校正拼字和文法，並提供潤飾寫作的建議。 [深入了解](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br />在[部落格文章](https://insider.office.com/en-us/blog/microsoft-editor-gets-an-upgrade)中查看詳細資料

- **讓所有人都可以存取您的訊息：** Outlook 會在您傳送訊息時，自動讓您知道訊息中何時有協助工具問題，並協助您修正問題。<br />在[部落格文章](https://insider.office.com/en-us/blog/sending-accessible-emails-in-outlook-for-windows)中查看詳細資料

- **共用行事曆改良功能：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。 這項功能可提供更快速且更可靠的共用行事曆更新，現在會預設為開啟狀態。  [深入了解](https://support.microsoft.com/en-us/office/outlook-calendar-sharing-updates-c3aec5d3-55ce-4cea-84b0-80aab6d8dc26)

- **改良的通訊錄搜尋：您現在可以在通訊錄中搜尋其他欄位，包括名稱、標題、位置等等。**<br />在[部落格文章](https://insider.office.com/en-us/blog/improved-search-experience-in-the-outlook-address-book)中查看詳細資料

### <a name="powerpoint"></a>PowerPoint

- **Word/Excel/PowerPoint 中的 DLP 原則提示:** 現在可以透過應用程式偵測到其他已設定為 OneDrive 和 SharePoint 資料外洩防護 (DLP) 部分原則的敏感性資訊類型, 以顯示原則提示。此更新也會提供準確性改善和全球化支援。 [[深入了解]](/microsoft-365/compliance/sensitive-information-type-learn-about)

- **在單一位置尋找所有協助工具工具:** 開啟簡報，然後選取 [檢閱]，然後選擇 [檢查協助工具]。 [協助工具] 窗格和 [新的協助工具] 功能區將會自動顯示。<br />在[部落格文章](https://insider.office.com/en-us/blog/accessibility-ribbon-in-powerpoint-accessibility-made-easier)中查看詳細資料

### <a name="word"></a>Word

- **單鍵書寫建議：** 只要按一下，就能套用書寫建議。 更新的 [編輯器] 窗格讓您輕鬆在建議之間瀏覽。 [深入了解](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br />在[部落格文章](https://insider.office.com/en-us/blog/microsoft-editor-gets-an-upgrade)中查看詳細資料

- **Word/Excel/PowerPoint 中的 DLP 原則提示:** 現在可以透過應用程式偵測到其他已設定為 OneDrive 和 SharePoint 資料外洩防護 (DLP) 部分原則的敏感性資訊類型, 以顯示原則提示。此更新也會提供準確性改善和全球化支援。 [[深入了解]](/microsoft-365/compliance/sensitive-information-type-learn-about)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們修正了導致 Insights 增益集停止運作的問題。


- 這項變更可啟用針對 Outlook 增益集 1.11 和 1.9 需求集合的完全支援。


- 我們修正了阻止多個使用者在網路檔案共用上開啟資料庫的問題。[深入了解](https://support.microsoft.com/en-us/office/access-error-could-not-use-path-to-database-accdb-file-already-in-use-6cbc1560-62c2-46e7-9980-d079a46f5acc)


- 我們已修正使用多個執行緒連線到 Access 或 Jet 資料庫時會導致應用程式意外關閉的問題。


- 此變更修正了當資料庫中包含 SharePoint 清單的連結時，可能造成使用 OLEDB API 的應用程式開啟 Access 資料庫 (.accdb 檔案) 會意外關閉的問題。


### <a name="excel"></a>Excel

- 已修正使用 OLEDB API 和 ACE.OLEDB.12.0 或 ACE.OLEDB.16.0 提供者的應用程式意外關閉的問題。


- 在含兩個儲存格編輯方塊的多顯示器設定對話方塊中，會在選取儲存格時對使用者隱藏資料。 這個修正會取消隱藏 UI 對話方塊中的資料。 此變更會影響三個監視器安裝上的條件式格式設定或資料數列選取對話方塊。


- 當您有內嵌於另一個應用程式 (如 Word 文件) 中的 Microsoft Excel 97-2003 工作表物件，使用 [轉換] 功能將其轉換為 Microsoft Excel 工作表 (Office OpenXML) 時，該物件不一定會完成轉換，直到您開啟内嵌的物件並對其進行變更為止。已修正此項目，因此使用 [轉換] 功能時，可完全轉換物件。


- 我們修正了搜尋文字會在樞紐分析表欄位選取工作窗格中重設的問題。


### <a name="outlook"></a>Outlook

- 我們修正了使用者變更訊息中連結的權限時，導致智慧連結 URL 不會更新的問題。


- 我們修正了應用程式在載入連絡人卡片後變成無回應的問題。


- 我們修正了載入角色時導致停止回應的問題。


- 已修正將連絡人匯出至 CSV 時導致使用者在某些欄位中看到亂碼文字的問題。


### <a name="word"></a>Word

- 我們修正了重複樣式會套用 Normal，而不是重複樣式的問題。


### <a name="office-suite"></a>Office 套件

- 已修正與 SVG 轉譯中文字錨定相關的問題。


- 已修正使用觸控板時透過點兩下選取文字的問題。


- 已修正與重新整理可能包含文字的元素相關的可靠性問題。


- 我們已修正有關 Office 新外觀的教學圖說內容 (提示) 未出現在 Outlook 中的問題。  現在，Word、Excel、PowerPoint 和 OneNote 的使用者會收到 Office 新外觀變更的通知，其中包含變更內容以及如何變更設定或切換體驗的資訊。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2111-february-08"></a>版本 2111：2 月 8 日
*版本 2111 (組建 14701.20314)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)

## <a name="version-2111-january-11"></a>版本 2111: 1 月 11 日
*版本 2111 (組建 14701.20290)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)
<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)
### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正會防止多個使用者在網路檔案共用上開啟資料庫的問題。[深入了解](https://support.microsoft.com/en-us/office/access-error-could-not-use-path-to-database-accdb-file-already-in-use-6cbc1560-62c2-46e7-9980-d079a46f5acc)


### <a name="excel"></a>Excel

- 我們已修正 LOGEST 工作表函數的問題，該函數不會處理並清除暫時性溢位錯誤，且後續的計算不正確。


- 我們已修正 WEBSERVICE 工作表函數的問題，在極少數的情況下，Excel 會在使用者取消計算時停止運作。


- 我們已修正某些公式結果在輸入變更後無法更新的問題。


- 我們已修正此問題: 如果資料來源範圍變更，新建立的樞紐分析表可能會失去自訂的設定。


- 我們已修正與表單控制項互動可能會導致 Excel 意外關閉的問題。


- 我們修正了當資料中不再存在篩選值時，重新整理樞紐分析表資料可能會停止運作的問題，並且在缺少無效篩選值所產生的後續查詢陳述式，重試重新整理要求暫時遭到停用，而現在已重新啟用。


- 我們已修正在 SpreedsheetCompare 工具中開啟 xlsm 檔案會導致工具停止回應的問題。


### <a name="outlook"></a>Outlook

- 我們已修正在檢索角色時，造成使用者遇到意外關閉的問題。


- 我們已修正會導致使用者在載入人員相片時遇到意外關閉的問題。


- 我們已修正會導致顯示連絡人卡片時意外關閉的問題。


- 我們已修正會導致使用者在 PowerPoint 中載入角色時遇到意外關閉的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正無法按一下某些彈出 UI 元素的問題，例如，Outlook 中的 [加入會議] 快顯視窗，或 PowerPoint 中的 [歡迎回來] 快顯視窗。


### <a name="project"></a>Project

- 我們修正了一個問題，即當使用者開啟已儲存為其他名稱的專案時，已手動排程的工作被重新排程至更早的日期。 在開啟這些專案時，使用者不應再看到已手動排程的工作被重新排程。


- 我們已修正載入自訂報告時某些專案會意外關閉的問題。


### <a name="word"></a>Word

- 我們修復了在匯出為 PDF 後，書籤和目錄連結無法運作的問題。


- 我們已修正無法按一下某些彈出 UI 元素的問題，例如，Outlook 中的 [加入會議] 快顯視窗，或 PowerPoint 中的 [歡迎回來] 快顯視窗。


### <a name="office-suite"></a>Office 套件

- 我們修正了以下問題：在受保護的共同撰寫期間，敏感度標籤和加密可能會從 SharePoint 或 OneDrive 中託管的檔案中移除的問題。


- 我們已修正 Office 在 SSO 和 ADFS DRS 環境中顯示帳戶錯誤的問題。


- 已修正與 SVG 轉譯中文字錨定相關的問題。


- 已修正與重新整理可能包含文字的元素相關的可靠性問題。


- 我們已修正完成下列變更的問題: 
1. Outlook 中存在一個問題，即未顯示有關 Office 新外觀的教學圖說內容 (提示)。現在這些內容都會顯示。
2. 許多 Word、Excel、PowerPoint 和 OneNote 使用者都錯過了有關 Office 新外觀的教學圖說內容，其中包括有關變更內容以及如何變更設定或關閉體驗的資訊。此變更會重新觸發這些教學圖說內容，讓使用者收到有關變更的通知。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2110-january-11"></a>版本 2110: 1 月 11 日
*版本 2110 (組建 14527.20364)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)

## <a name="version-2110-december-17"></a>版本 2110：12 月 17 日
*版本 2110 (組建 14527.20344)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正會防止多個使用者在網路檔案共用上開啟資料庫的問題。[深入了解](https://support.microsoft.com/en-us/office/access-error-could-not-use-path-to-database-accdb-file-already-in-use-6cbc1560-62c2-46e7-9980-d079a46f5acc)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2109-december-17"></a>版本 2109：12 月 17 日
*版本 2109 (組建 14430.20386)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

安全性更新列於[此處](microsoft365-apps-security-updates.md)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2110-december-14"></a>版本 2110：12 月 14 日
*版本 2110 (組建 14527.20340)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **Microsoft 搜尋支援的撰寫 (收件者/副本/密件副本) 建議**：將人員新增至收件者/副本行，現在會由 Microsoft 搜尋提供支援。

- **針對郵件和行事曆撰寫之展開的 GAL 人員建議:** 現在，在為電子郵件和行事曆撰寫建議人員時，Outlook 將從完整的 GAL 傳回結果。(例如: 將某人新增到新電子郵件的 [收件者] 行)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正當我們開啟隱私權設定視窗時，應用程式停止回應的問題，因為對話方塊管理員是空白的新增不是空白檢查做為檢查。


### <a name="excel"></a>Excel

- 我們已修正當我們開啟隱私權設定視窗時，應用程式停止回應的問題，因為對話方塊管理員是空白的新增不是空白檢查做為檢查。


- 開啟 Dynamics 的連結資料表時，顯示資料時，數字可能會呈現為小型方塊。 若要解決此問題，請在資料表設計檢視中開啟連結，並清除任何受影響資料行的格式屬性。


- 我們已修正開啟 Excel 檔案時儲存格選擇取關閉的問題。


- 我們已修正部分工作表函數未針對使用特定語言使用者顯示的問題。


- 我們已修正在公式中使用儲存格參照導致使用者遇到高 CPU 使用量的問題。


- 我們已修復此問題: 如果來源檔案來自 OneDrive 位置且檔案名稱包含 HTML 編碼字元, 將 Excel、Word 或 PowerPoint 內嵌物件加入 Excel 檔時, 未正確顯示應用程式的原始圖示。


- 我們已修正查詢更新導致 Excel 停止回應的問題。


### <a name="outlook"></a>Outlook

- 我們已修正當我們開啟隱私權設定視窗時，應用程式停止回應的問題，因為對話方塊管理員是空白的新增不是空白檢查做為檢查。


- 我們已修正在繪製影像時，可能會停止回應的問題。


- 我們修正了導致使用者載入 [行事曆] 模組的功能窗格時，遇到「停止」回應的問題。


- 我們修正了預覽會議邀請時導致約會快速模式被裁掉的問題。


- 我們已修正以滑鼠右鍵按一下並選取檔案系統中的 [傳送郵件] 來傳送郵件，導致 explorer.exe 在 VDI 電腦上意外關閉的問題。


- 我們已修正導致使用者在 Outlook 中更新使用者目前狀態資訊時意外遇到停止回應的問題。


- 我們已修正在移動個人卡片時，導致使用者遇到無回應的問題。


- 我們已修正會導致使用 Windows 11 的使用者，或透過「即將推出」使用視覺效果的使用者，在調整 Outlook 視窗時，在功能區中看到一些對齊問題和奇怪的視覺效果構件的問題。


- 我們已修正導致使用者在 Outlook 重新啟動之後，無法將其預設簽名插入新電子郵件、回覆或轉寄的問題。


- 我們已修正導致使用者無法從受保護的語音信箱訊息下載 MP3 附件的問題。


- 我們修正了導致所有使用敏感度標籤所送出的電子郵件持續使用「僅加密」範本，導致不正確的行為，允許人員轉寄「僅收件者」電子郵件的問題。


- 我們已修正會在產生預覽時，導致同步處理停止運作的問題。


- 我們已修正會導致使用 Windows 11 的使用者，或透過「即將推出」使用視覺效果的使用者，在將游標停留在迷你行事曆日期時看到文字未對齊的問題。


- 我們已修正在展開交談時，導致使用者遇到停止回應的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正當我們開啟隱私權設定視窗時，應用程式停止回應的問題，因為對話方塊管理員是空白的新增不是空白檢查做為檢查。


- 我們已修正當使用者將原始直向和較大的紙張大小文件變更為較小的紙張大小 (例如，從 Letter 變更為 A5) 時，其列印可能會遭到截斷 (遺失資料) 的問題。


- 我們已修復在執行 [儲存複本] 作業時，當 [自動儲存] 關閉時產品更新無法儲存至原始雲端檔案的問題。


- 我們已修正在繪製影像時，可能會停止回應的問題。


### <a name="project"></a>Project

- 我們已修正當透過 CSOM 以程式設計方式將新工作新增到專案時，如果新工作的工作摘要已摺疊，工作可能無法插入正確位置的問題。


- 我們已修正在 Project 中重新排程工作時，手動排程的工作可能會早於其預定排程時間的問題。


### <a name="skype"></a>Skype

- 已修正部分膝上型電腦的混合式相機未在 SfB 用戶端中顯示的問題。


### <a name="word"></a>Word

- 我們已修正當我們開啟隱私權設定視窗時，應用程式停止回應的問題，因為對話方塊管理員是空白的新增不是空白檢查做為檢查。


- 我們已修正嘗試開啟 OneDrive 共用檔案時，應用程式意外關閉的問題。


- 我們已修正 x64 使用者的 Word [檔案] > [選項] 功能表中的主題選擇器無法套用所選佈景主題的問題。 [檔案] > [帳戶] 位置中的佈景主題選擇器仍可運作，且不受此變更影響。


- 我們已修正在繪製影像時，可能會停止回應的問題。


### <a name="office-suite"></a>Office 套件

- 我們修正了包含無效 SVGs 的文件會顯示點陣化遞補影像，而不是紅色 X 的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2109-december-14"></a>版本 2109：12 月 14 日
*版本 2109 (組建 14430.20380)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正少數 GCC-H 租用戶無法使用自動敏感度標籤的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2109-november-09"></a>版本 2109：11 月 09 日
*版本 2109 (組建 14430.20342)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **自動展開線上封存搜尋：** 啟用自動展開線上封存搜尋。 您可以在此找到與無限制封存相關的詳細資訊：[自動展開封存功能的概觀](/microsoft-365/compliance/unlimited-archiving)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正查詢更新導致 Excel 停止回應的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致新增到「捷徑」模組的行事曆，在 Outlook 重新啟動後會消失的問題。


- 我們已修正會導致使用者看到他們新增的共用行事曆預設未經過檢查，導致他們認為該行事曆尚未新增的問題。


- 我們已修正會導致 Outlook 使用者的「共用行事曆改良」功能遇到高 CPU 使用率的問題。


- 我們已修正在嘗試擷取 [自動探索] 設定時，導致某些使用者遇到停止回應的問題。


- 我們已修正會導致某些使用者在新增共用行事曆後遇到意外關閉的問題。


- 我們已修正會在產生預覽時導致同步處理失敗發生的問題。


### <a name="project"></a>Project

- 我們已修正當透過 CSOM 以程式設計方式將新工作新增到專案時，如果新工作的工作摘要已摺疊，工作可能無法插入正確位置的問題。


### <a name="office-suite"></a>Office 套件

- 我們修正了包含無效 SVGs 的文件會顯示點陣化遞補影像，而不是紅色 X 的問題。


- 我們修正了顯示以下錯誤「大聲朗讀沒有開始」的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2108-november-09"></a>版本 2108：11 月 09 日
*版本 2108 (組建 14326.20600)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會導致使用者看到他們新增的共用行事曆預設未經過檢查，導致他們認為該行事曆尚未新增的問題。


- 我們已修正在嘗試擷取 [自動探索] 設定時，導致某些使用者遇到停止回應的問題。


- 我們已修正會在產生預覽時導致同步處理失敗發生的問題。


### <a name="word"></a>Word

- 我們已修正在啟用 AIP 增益集的情況下儲存文件時，會發生檔案格式變更的問題。


- 我們已修正 RTF 格式的效能問題。


- 我們已修正 Word 不能呈現電子郵件本文中內嵌 base-64 編碼 GIF 的問題。


### <a name="office-suite"></a>Office 套件

- 我們修正了包含無效 SVGs 的文件會顯示點陣化遞補影像，而不是紅色 X 的問題。


- 已修正可能會讓 Word、Excel、PowerPoint 和 Outlook 用戶端進入一個狀態，在其中我們會對不正確的 URL 端點傳送要求的問題。 特別是，若沒有此修正，我們就可以將美國政府文件內容傳送至全球的 augloop.office.com 端點，或是傳送至較低層級的 USGov 端點 (例如，已傳送至 GCC 的 DoD 資料) 



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2108-october-12"></a>版本 2108: 10 月 12 日
*版本 2108 (組建 14326.20508)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **存取協助工具的新方法：** 協助工具功能區將您所需、用來建立可存取內容的所有工具放置在同一個位置。<br />在[部落格文章](https://insider.office.com/en-us/blog/check-out-the-accessibility-checker-in-excel)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正錯誤訊息中包含特殊字元的問題。


- 我們已修正現在會啟用 Outlook 增益集之啟動事件的問題。


- 我們已修正會導致放置查詢設計或系統關聯性視窗的資料表，會出現在與將其放置位置不同的問題。


### <a name="excel"></a>Excel

- 已修正此問題：連結或匯入 Dynamics 資料表時，並非所有的資料列都會出現。


- 我們已修正從 PowerPivot 視窗內連接到資料來源無法運作的問題。


- 已解決 Excel 在下列情況下，可能會在計算活頁簿時停止回應的問題。


### <a name="onenote"></a>OneNote

- 已將建立快速筆記的快速鍵更新為 Win + Alt + N。


### <a name="outlook"></a>Outlook

- 我們已修正導致位置欄位中的連結無法按一下的問題。


- 我們已修正導致某些使用者間歇性地重新顯示已刪除的會議邀請的問題。


- 我們已修正使用有多個帳戶的設定檔將 Outlook 啟動後，會導致網路活動短暫增加的問題。


- 已修正會議項目取消表單會出現，而不是預期的編輯表單的問題。


- 我們已修正導致應用程式在使用 Outlook 時停止回應的問題。


- 我們已修正會導致新增到「捷徑」模組的行事曆，在 Outlook 重新啟動後會消失的問題。


- 我們已修正會導致 Outlook 使用者的「共用行事曆改良」功能遇到高 CPU 使用率的問題。


- 我們已修正在 Outlook 中建立會議時且 Exchange 系統管理員未設定選項時，預設出現有關縮短會議之非預期資訊型通知提示的問題。


- 已修正以 ICAL 轉送一些大型或持續很久的週期性會議時所發生的錯誤。


- 我們已修正 Outlook 開機後，應用程式不久後停止回應的問題。


- 我們已修正使用 Outlook 撰寫電子郵件時，應用程式會意外關閉的問題。


- 我們已修正帳戶的 UPN/SMTP 名稱變更之後，電子郵件簽名會遺失的問題。


- 我們已修正在將行事曆新增至功能窗格，導致某些使用者遇到停止回應的問題。


- 我們已修正導致使用者在將電子郵件草稿儲存至磁片時，看到 HTML 格式設定遺失的問題。


- 我們已修正造成 [會議室尋找工具] 無法載入的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 Word 存檔時，所花時間超過預期的問題。


### <a name="skype"></a>Skype

- 我們已修正在交談視窗中，影片共用預覽會意外關閉的問題。


### <a name="word"></a>Word

- 我們已修正列印中未載入預覽列印的問題。


- Office 應用程式現在支援 [OpenDocument format 1.3](https://insider.office.com/en-us/blog/office-apps-now-support-opendocument-format-odf-1-3)。


- 我們已修正 Word 存檔時，所花時間超過預期的問題。


- 我們已修正非預設功能區設定可能導致樣式庫無法運作的問題。


- 我們已修正您無法在 [繼續] 區段中關閉任何編輯器選項的問題。


- 我們已修正插入線上影片按鈕被停用的問題。


- 已修正顯示新版視覺效果的對話方塊包含螢幕助讀程式無法讀取的文字的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正使用某些 Web 增益集後，某些文件無法載入的問題。


- 我們已修正與使用觸控或觸控板在 PPT 投影片的縮圖檢視中捲動相關的問題。


- 修正 Outlook 中的自訂 VSTO 控制項在開啟和切換多個視窗和視圖之後停止工作的錯誤。


- 我們已修正會導致樞紐分析表中的日期欄位分組錯誤的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2107-october-12"></a>版本 2107: 10 月 12 日
*版本 2107 (組建 14228.20340)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)

## <a name="version-2107-september-14"></a>版本 2107：9 月 14 日
*版本 2107 (組建 14228.20324)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **在干擾較少的情況下閱讀訊息：** 開啟沈浸式閱讀程式，以自訂文字間距、頁面色彩、欄寬和行聚焦，讓您更輕鬆地專注於訊息。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 在某些客戶設定中，我們發現文件從 Office 匯出為 PDF 或 XPS 格式可能會因為最近的更新而停止回應。此更新修正了這些回歸，並重新啟用了匯出為這些格式的功能。


- 我們已修正嘗試使用來自非 Office 應用程式的 DAO API 時，會停止回應並顯示「作業系統目前未配置成執行此應用程式」的問題。


### <a name="excel"></a>Excel

- 在某些客戶設定中，我們發現文件從 Office 匯出為 PDF 或 XPS 格式可能會因為最近的更新而停止回應。此更新修正了這些回歸，並重新啟用了匯出為這些格式的功能。


- 我們已修正可能造成某些連結 Dynamics 資料表停止回應的問題。


- 已修正如果 Application.DisplayAlerts 設定為 True，就無法從 VBA 開啟受 DRM 保護的活頁簿的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致共用日曆改進功能的使用者在 Outlook 重新開機之前，無法顯示新加入的共用日曆的問題。


- 我們已修正當會議開始與會議結束在不同的日期時，導致使用者在結束會議時間下拉式清單中看到重複時間項目的問題。


- 修正會導致使用者能夠下載受保護的語音信箱訊息的問題。


- 修正僅對簽章內容的變更不會在雲端式設定中更新的問題。


- 我們已修正會導致某些使用者在執行搜尋時遇到意外關閉的問題。


- 我們已修正會導致在 SendFromAliasEnabled 設定為 True 的組織中，由不同使用者重新傳送的電子郵件會顯示為由原始寄件者傳送的問題。


### <a name="powerpoint"></a>PowerPoint

- 在某些客戶設定中，我們發現文件從 Office 匯出為 PDF 或 XPS 格式可能會因為最近的更新而停止回應。此更新修正了這些回歸，並重新啟用了匯出為這些格式的功能。


### <a name="visio"></a>Visio

- 我們已修正使用者能夠順暢地存取檔案，而不需要遇到任何意外關閉的問題。


### <a name="word"></a>Word

- 在某些客戶設定中，我們發現文件從 Office 匯出為 PDF 或 XPS 格式可能會因為最近的更新而停止回應。此更新修正了這些回歸，並重新啟用了匯出為這些格式的功能。


- 修正使用 [此裝置] 選項編輯與新增圖片相關連絡人的問題。


- 已修正 Word 畫布旁的註解卡片大小不正確的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2106-september-14"></a>版本 2106：9 月 14 日
*版本 2106 (組建 14131.20384)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)

## <a name="version-2106-august-10"></a>版本 2106: 8 月 10 日
*版本 2106 (組建 14131.20360)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="word"></a>Word

- **Word 文件的深色模式：** 深色模式有助於減輕眼睛疲勞，並可在處理文件時適應對光線的敏感度。<br />在[部落格文章](https://insider.office.com/en-us/blog/try-dark-mode-in-word)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 修正可能導致使用 Access 資料庫引擎 ODBC API 的應用程式意外關閉的問題。


- 修正可能導致使用 Access 資料庫引擎 OLEDB API 的應用程式搭配的資料庫包含 SharePoint 清單連結時，會意外關閉的問題。


### <a name="excel"></a>Excel

- 修正針對部分使用者在 Excel 增益集清單中顯示的額外項目問題。


- 我們已修正某些使用者無法在受密碼保護的檔案上開啟進入編輯模式的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致擁有多個共用行事曆且擁有共用行事曆增進選項的使用者遇到一些效能問題的問題。


- 我們已修正啟用 [共用行事曆改進] 選項後，導致 SMTP 位址在多帳戶設定檔中使用者的主要行事曆旁無法顯示的問題。


- 我們已修正導致使用者在透過滑鼠右鍵操作功能表回應會議要求時，看到建立重複的行事曆項目的問題。


- 我們已修正導致雲端設定在發生衝突時，漫遊設定失敗的問題。


- 我們已修正當設定檔中出現未完整設定的帳戶時，造成雲端設定使用者遇到意外關閉的問題。


- 我們已修正導致某些使用者在擷取服務提供的搜尋建議時遇到意外關閉的問題。


- 我們已修正導致某些使用者的翻譯選項遭到停用的問題。  遇到此錯誤的客戶在瀏覽至檔案 -> 選項 -> 語言時，會看見其翻譯選項已遭停用。 有鑑於此，他們可能無法變更其偏好的翻譯語言和其他翻譯相關設定。


- 我們已修正導致 ARM64 裝置上發生效能問題的問題。


- 我們已修正在從 PST 重新傳送郵件時，導致由 [重新傳送此郵件] 選項所產生之訊息的修改會在傳送時遺失的問題。


- 我們已修正在載入收集診斷資料時，導致某些使用者遇到意外關閉的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用者因為阻礙性的 PowerPoint 特定對話方塊，而無法將憑證輸入 Windows 安全性對話方塊以開啟檔案的問題。


### <a name="visio"></a>Visio

- 具有來賓存取的 SPO/ODB 連結現在可繼續運作。


### <a name="office-suite"></a>Office 套件

- 修正使用者從 Office 應用程式中的 Me 控制項切換 Active Directory 身分時切換資料案例。


- 已修正 OMEX 與 ExCatalog 之間無法再共用設定的問題，例如建立了新 webextension 檔案之後，Web 增益集設定會更新至 webextension.xml。 只有在以原始方法部署該增益集，或將新的解決方案參考比較關閉時，才能存取前一個。


- 我們已修正在 DirectX 裝置遺失和復原期間不穩定的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2105-august-10"></a>版本 2105: 8 月 10 日
*版本 2105 (組建 14026.20352)*

安全性更新列於 [此處](microsoft365-apps-security-updates.md)

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

- 我們已新增一個登錄機碼，以停用新會議室尋找工具體驗 (與 Outlook 網頁版相同的體驗)，並啟用具有建議的時間的傳統會議室尋找工具。

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

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft Purview 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。

### <a name="powerpoint"></a>PowerPoint

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft Purview 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。

### <a name="word"></a>Word

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft Purview 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。


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
    
    登錄機碼：

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

- **自動使用新的資料類型**：當您輸入類似股票或地理位置的資料值時，Excel 會將它轉換為成正確的連線資料類型 - 股票或地理位置。。[深入了解](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **連結資料類型：實際生活中的真實資料：** 新的連結資料類型會提供有關數百個主題的事實和資料，幫助您直接在 Excel 中達成目標。

### <a name="outlook"></a>Outlook

- **使用內建翻譯工具打破語言障礙：** 不再需要翻譯的增益集！ 您現在可以在 Outlook 中使用 Intelligent Translator。 當您收到另一種語言的郵件時，郵件上會顯示提示，詢問您是否希望 Outlook 將它翻譯為您的預設語言。
您也可以按一下滑鼠右鍵以翻譯特定的文字、片語或整個郵件。 [深入了解](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

### <a name="visio"></a>Visio

- **適用於您的圖表的現成圖形：** 從可新增至 Visio 繪圖中的圖示、相片庫影像、人像紙板和圖戳的大型文件庫中進行選擇。[深入了解](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)<br />在[部落格文章](https://insider.office.com/en-us/blog/access-illustrations-icons-in-visio)中查看詳細資料


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

- 修正某些 Excel 自動化增益集無法載入的問題。

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

- 修正某些 Excel 自動化增益集無法載入的問題。


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

安全性更新列於[此處](/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用 [進階對話方塊] 來 [建立資料類型]:** [進階對話方塊] 可讓您手動選取合併您正在建立的 [資料類型] 欄位。

- **同時取消隱藏多個工作表:** 不再需要一次取消隱藏一個工作表，可以一次取消隱藏多個隱藏的工作表。[深入了解](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)


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

安全性更新列於[此處](/officeupdates/microsoft365-apps-security-updates)

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

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。[深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能現在可供 GCC 和 GCC-H 環境中的客戶使用。[深入了解](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。[深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **在連續的會議之間騰出時間：** 將會議預設晚 5-10 分鐘開始，讓出席者有時間休息，或移至不同的位置。[深入了解](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- **敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。

- **每個線上會議** 更新行事曆設定，使您建立的每個會議都預設為 Teams 會議，這樣您就不必再記得按一下 [Teams 會議] 選項。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能現在可供 GCC 和 GCC-H 環境中的客戶使用。[深入了解](/microsoft-365/compliance/sensitivity-labels)

- **每個線上會議** 更新行事曆設定，使您建立的每個會議都預設為 Teams 會議，這樣您就不必再記得按一下 [Teams 會議] 選項。

- **新的會議室尋找工具：** 依不同功能搜尋會議室。

- **新的會議室和工作區預約體驗：** 會議室預約體驗已更新，透過它我們新增了功能，以讓您也能夠排程個別工作區


### <a name="powerpoint"></a>PowerPoint

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。[深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br />在[部落格文章](https://insider.office.com/en-us/blog/svg-content-office-third-party-apps)中查看詳細資料

- **敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能現在可供 GCC 和 GCC-H 環境中的客戶使用。[深入了解](/microsoft-365/compliance/sensitivity-labels)

### <a name="visio"></a>Visio

- **新的 Azure 樣板與圖形：** 我們新增了許多其他樣板，以協助您建立最新的 Azure 圖表。[深入了解](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a>Word

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。[深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。

- **政府客戶：將敏感度標籤套用至您的文件和電子郵件：** 敏感度標籤功能現在可供 GCC 和 GCC-H 環境中的客戶使用。[深入了解](/microsoft-365/compliance/sensitivity-labels)


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


- 最佳化的二進位大小。


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

- **在 Power Query 中建立自訂資料類型:** 使用任何資料來源建立自訂資料類型，可讓您將多個相關資訊部分載入到一個欄位。[深入了解](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br />在[部落格文章](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)中查看詳細資料

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
[//]: # (|Win32|MEC|Production|Feature|16.0.15330.20298|version-2206-august-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.15225.20356|version-2205-july-12|)
[//]: # (|Win32|MEC|Production|Feature|16.0.15128.20280|version-2204-june-14|)
[//]: # (|Win32|MEC|Production|Feature|16.0.15028.20248|version-2203-may-10|)
[//]: # (|Win32|MEC|Production|Feature|16.0.14931.20274|version-2202-april-12|)
[//]: # (|Win32|MEC|Production|Feature|16.0.14827.20220|version-2201-march-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.14729.20322|version-2112-february-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.14701.20290|version-2111-january-11|)
[//]: # (|Win32|MEC|Production|Feature|16.0.14527.20344|version-2110-december-17|)
[//]: # (|Win32|MEC|Production|Feature|16.0.14527.20340|version-2110-december-14|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
