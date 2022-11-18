---
title: 2022 年半年企業通道 (預覽) 版本的版本資訊
ms.author: nidos
author: nidos
manager: nidos
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2022 年 Microsoft 365 Apps 半年通道 (已設定目標) 版本的版本資訊
ms.openlocfilehash: ec716ea63160cb75e22376e09fb76f611be57ab1
ms.sourcegitcommit: 88a3e983436c7d90f1727d4bf3f20470cb6dafa7
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/12/2022
ms.locfileid: "68525620"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a>半年企業通道 (預覽版) 的版本資訊

這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含在 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的半年企業通道 (預覽) 更新。 

新增或更新的功能會在 3 月和 9 月的第二個星期二發行至半年企業通道 (預覽)。

## <a name="version-2208-october-11"></a>版本 2208：10 月 11 日
*版本 2208 (組建 15601.20230)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正資料區中樞紐分析表操作功能表中缺少 [顯示詳細資料] 選項的問題。


- 我們已修正密碼快取函式無法與 MSQuery x64 組建搭配運作的問題。


### <a name="outlook"></a>Outlook

- 我們已修正導致新式群組相關對話方塊嚴重中斷的問題。


- 我們已修正會導致使用者在出現一些個人卡片時意外遇到關閉的問題。


- 我們已修正導致使用者在開機後短暫意外關閉的問題。


- 我們已修正提交意見反應時導致 Outlook 意外關閉的問題。


- 我們已修正會導致停用服務通知的使用者看到已淘汰的 UI 顯示通知服務已停用的問題。


- 我們已修正會導致使用者在提交意見反應或連絡支援人員時收到驗證提示的問題。


### <a name="project"></a>Project

- 我們已修正在專案中心等Project Web App頁面上，使用檢視、篩選和分組依據控制項，輕鬆存取語音控制項無法正常運作的問題。


- 請參考此案例：

    * 您已將 [內容編輯器] 網頁元件放在 [專案詳細資料] 頁面上， (PDP) 。
    * 您正在編輯Project Web App中的專案。
    * 編輯時，SharePoint 網頁安全性驗證逾時。
    * 您關閉專案，然後選擇簽入專案。

    在此情況下，會出現「處理」快顯通知，但永遠不會消失。 此外，專案不會存回。  此問題已修正，因此現在會出現下列預期的訊息：

    此頁面的安全性驗證已逾時。在網頁瀏覽器中按一下 [上一步]，重新整理頁面，然後再操作一次。


### <a name="word"></a>Word

- 已解決具有樣式的清單在共同撰寫檔案時遺失縮排的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正預設封鎖網際網路宏執行的問題。


- 使用者在應用程式開機時使用增益集命令的效能改進。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2208-september-13"></a>版本 2208：9 月 13 日
*版本 2208 (組建 15601.20148)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用 [進階對話方塊] 來 [建立資料類型]:** [進階對話方塊] 可讓您手動選取合併您正在建立的 [資料類型] 欄位。 [深入了解](https://support.office.com/article/2b433a85-ddfb-420b-9cda-fe0e60b82a94)

- **從狀態列複製資料：** 從狀態列快速複製彙總的資訊，例如「Sum」、「Average」和「Count」。
在[部落格文章](https://insider.office.com/en-us/blog/copy-values-quickly-from-the-status-bar-in-excel-for-windows)中查看詳細資料

- **享受改良的捲動體驗** ：當您瀏覽大型或極寬的儲存格時，您的工作表可捲動得更為順暢。 [深入了解](https://support.office.com/article/06fc34b8-64bb-4d78-9b62-34656d700f82)

- **Lambda: 協助程式函數:** 7 個運用 Lambdas 的新功能，以及在撰寫 Lambda 解決方案時提供協助!
在[部落格文章](https://insider.office.com/en-us/blog/new-lambda-functions-available-in-excel)中查看詳細資料

- **字型庫的最佳載入可加速 Excel 啟動。：** 字型庫的最佳載入可加速 Excel 啟動。

- **更快找到資料：** 自動篩選功能現在明顯加快了! 這些改善是藉由減少記憶體使用量，以及優化篩選條件比較演算法所進行的呼叫所達成。 在記憶體較少或 CPU 記憶體輸送量較慢的低階裝置上，優化特別明顯。 [深入了解](https://support.office.com/article/7d87d63e-ebd0-424b-8106-e2ab61133d92)

### <a name="outlook"></a>Outlook

- **在 Outlook 中使用建議的回覆：** 當您收到可以簡短回覆的電子郵件訊息時，Outlook 可以建議三個回應，只要按幾下滑鼠即可回覆。 [瞭解更多資訊](https://support.office.com/article/19316194-0434-43ba-a742-6b5890157379)請參閱[部落格文章](https://insider.office.com/en-us/blog/reply-faster-using-suggested-replies-in-outlook)中的詳細資料

- **單鍵寫作建議：** 只要按一下，就能套用寫作建議。 編輯器會校正拼字和文法，並提供潤飾寫作的建議。 [瞭解更多資訊](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)請參閱[部落格文章](https://insider.office.com/en-us/blog/microsoft-editor-gets-an-upgrade)中的詳細資料

- **語文法檢查鼎力相助**：Outlook 會在你鍵入時標記文法錯誤，因此你只需按一下就可以套用建議。 [瞭解更多資訊](https://support.office.com/article/ddbadc42-4637-451d-b3f4-ecf295036fa9)請參閱[部落格文章](https://insider.office.com/en-us/blog/grammar-and-style-suggestions-available-in-outlook)中的詳細資料

- **在 Outlook 行事曆待辦事項列中顯示多個迷你月份：** 這項功能可讓您在 Outlook 行事曆待辦事項列，以水平和垂直方式顯示多個迷你月份。

- **關閉建議回覆：** Outlook [使回覆更為簡單快速](https://insider.office.com/blog/reply-faster-using-suggested-replies-in-outlook) 透過提供僅需幾個字回覆的簡短建議回覆郵件，讓回覆電子郵件更為快速。 部分使用者可能不想看到此選項，因此現在可以關閉此功能。 若要這麼做，請選取檔案 > 選項> 郵件，前往回覆和轉寄區段，然後清除顯示建議的回覆核取方塊。

### <a name="powerpoint"></a>PowerPoint

- **文字錨定註解：** 客戶現在可以將註解錨定到特定範圍的文字，這是 PowerPoint 新式註解的一部分。

### <a name="word"></a>Word

- **用其他方式表達：** 當您想要以不同方式表達時，「重寫」功能可以幫助您。 重寫提供其他不同方式來表達您的詞彙。
在[部落格文章](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/)中查看詳細資料

- **使用編輯器來校對選取的文字:** 檢查拼寫、語法，並只對文件中選取的文字取得撰寫建議。
在[部落格文章](https://insider.office.com/en-us/blog/proof-selected-text-in-a-word-document)中查看詳細資料

- **單鍵書寫建議：** 只要按一下，就能套用書寫建議。 更新的 [編輯器] 窗格讓您輕鬆在建議之間瀏覽。 [瞭解更多資訊](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)請參閱[部落格文章](https://insider.office.com/en-us/blog/microsoft-editor-gets-an-upgrade)中的詳細資料

- **只追蹤您在文件中的變更：** 當您共同作業時，有時候您只想追蹤自己的變更，而不想強制此設定追蹤其他人的部分。 若只要追蹤您的變更，請前往 [校閱] 索引標籤，選取 [追蹤修訂]，然後選擇 [只有我]。
在[部落格文章](https://insider.office.com/en-us/blog/track-just-your-changes-in-word)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正某些使用者無法搭配現有匯入/匯出規格使用 DoCmd.TransferText 的最近回歸。


- 我們已修正提示「沒有目前記錄」錯誤和其他訊息的問題。


- 我們已修正當地語系化十進位分隔符號無法正確運作的問題


- 我們已修正 Dataverse 在 2019 功能區中顯示的問題。


- 我們已修正嘗試在唯一識別碼欄中支援 Unicode 字元時所造成的問題。


- 我們已修正在使用 Access 資料庫引擎 OLEDB API 與包含 SharePoint 清單之連結的資料庫時，可能會導致應用程式意外關閉的問題。


- 我們已修正來自使用者先前在 SA 頻道能即時執行的現有程式碼，在目前的頻道卻需花 13 分鐘來執行的問題。


- 我們已修正開啟 ACCDE/MDE 檔案時的問題。 使用者可能會收到錯誤訊息，其文字為「要求的類型文件庫或精靈不是 VBA 專案」。 [深入了解](https://support.microsoft.com/en-us/topic/error-when-trying-to-open-an-accde-mde-file-created-in-a-different-version-of-access-f4cd36cd-549e-42ba-b75a-dfe964294a81)


- 選取 [附件] 或 [多重值] 欄位的資料表時，啟動 [報表]、[標籤] 或 [查詢精靈] 可能會導致 Access 沒有回應。  此更新會修正此問題，讓這些精靈在所有資料表中再次正常運作。


- 我們已修正某些使用者無法搭配現有匯入/匯出規格使用 DoCmd.TransferText 的最近問題。


- 此更新修正了在 Excel 中逐一查看 VBA 程式碼中的 DAO 記錄集時，可能會導致記憶體流失的問題。


- We fixed an issue that could cause memory usage of an application that uses DAO or OLEDB interfaces to read Access databases to grow rapidly.  In some cases, this could cause abnormal program termination.


### <a name="excel"></a>Excel

- 我們已修正編輯新建立的檔案時，商務列標籤未正確上傳的問題。


- 我們已修正應用程式與字型互動時意外關閉檔案的問題。


- 我們已修正字母 「j」 未正確插入的問題。


- 在 Office 2016 和 Office 365 Visual Refresh 中，已改善工作窗格和對話方塊中彩色和白色主題中暫留和按下滑杆的可見度。<br />
- 在已啟用 Fluent 視覺效果的Office 365中，已改善工作窗格和對話方塊中深灰色和黑色主題中暫留和按下滑杆的可見度。<br />
- 在具有 Visual Refresh Darky Gray 主題的Office 365中，防止捲動按鈕框線出現在功能區字型選擇器下拉式清單中的問題已解決。


- 我們已修正當人員嘗試在不受支援區域中使用地圖圖表時提供詳細資訊的問題。


- 我們已修正針對不支援的區域更正 3D 地圖顯示的問題。


- 我們已修正復原的檔案以唯讀方式開啟的問題。


- 我們已修正導致 Excel 耗用過多記憶體的問題。


- 我們已修正在具有圖表工作表的活頁簿上執行 VBA 指令碼/增益集時，可能會導致 Excel 意外關閉的問題。


- 我們已修正在某些情況下，當資料格有資料驗證規則時，可能會影響效能的問題。


- 我們已修正在啟用凍結窗格時，Excel 會使用非預期的大量 CPU，但並非每個凍結窗格都在畫面上顯示的問題。


- 我們已修正圖表中儲存格參照顯示不正確的問題。


- 我們已修正在選擇 [檔案] > [關閉] 或按 Ctrl+W 關閉最後一個活頁簿時，導致 Excel 完全關閉的問題。


- 我們已修正 .xls 格式的共用活頁簿可能會不當合併變更的問題。


- 我們已修正 AMSI 掃描會導致應用程式意外關閉的問題。


- 我們已修正嘗試從大型 XML 資料來源使用 Power Query 重新整理資料時，可能會發生錯誤的問題。


- 我們已修正非英文地區設定的問題，其中一般數位格式的地區設定特定值計算不正確。


- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 我們已修正使用特定舊版 Windows 11 時，在 Excel 和 Project 中呈現的問題。


- 我們已修正使用特定舊版 Windows 11 時，在 Excel 和 Project 中呈現的問題。


- 我們已修正資料編輯列中的視覺問題。


- 我們已修正 Excel 中包含在篩選或隱藏儲存格中的影像問題。


- 我們已修正導致 Excel 在顯示圖表即時預覽時意外關閉的問題。


### <a name="onenote"></a>OneNote

- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 我們已修正導致應用程式意外關閉的問題。


### <a name="outlook"></a>Outlook

- 我們已修正當人員嘗試在不受支援區域中使用地圖圖表時提供詳細資訊的問題。


- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 我們已修正當事件型增益集在背景中執行時，在回覆或轉寄電子郵件時應用程式意外關閉的問題。


- 我們已修正使 Outlook 事件型增益集無法正常運作的問題。


- 我們已修正在嘗試開啟 Viva Insights 增益集時，導致某些客戶看到灰色方塊的問題。


- 我們已修正當事件型增益集在背景中執行時，在回覆或轉寄電子郵件時應用程式意外關閉的問題。


- 我們已修正協助使用者找到正確的設定，以管理協力廠商會議提供者的預設線上會議選項的問題。


- 我們已修正使 Outlook 事件型增益集無法正常運作的問題。


- 此變更會啟用協力廠商會議應用程式的 [每個會議線上] 選項。


- 我們已修正導致「移至其他」功能停止正常回應的問題。


- 我們已修正導致某些 Outlook 使用者在間歇性地開機之後，突然遇到關閉的問題。


- 我們已修正使用 [僅加密] 和 [不要轉寄]範本的訊息透過物件模型傳回未預期權限的問題。


- 我們已修正在使用雲端設定時，導致某些切換類型選項進行錯誤同步處理的問題。


- 我們已修正會導致使用者在其左側滑軌導覽列中看到 [日誌] 模組的問題。


- 我們已修正導致某些人在開機後很快就會遇到非預期關閉的問題。


- 我們已修正在新應用程式行中以滑鼠右鍵按一下應用程式時，Outlook 有時會意外關閉的問題。


- 我們已修正會導致歐盟使用者看到人員卡片中遺失資訊的問題。


- 我們已修正在連線到沒有服務 URL 的商務用 OneDrive端點時，導致 Outlook 在啟動期間意外關閉的問題。


- 我們已修正會導致使用者看到「無法執行要求的作業...」錯誤的問題當嘗試展開本機連絡人群組時。


- 我們已修正導致自訂快速存取工具列檔案 (.exportedUI) 在使用簡化功能區時無法匯入的問題。


- 我們已修正導致在部分診斷案例中，使用者在 Outlook 中預期停止回應的問題。


- 我們已修正會導致使用者在回應特定連絡人時，遇到停止回應的問題。


- 我們已修正回覆電子郵件並變更主旨時，會移除參照及回覆至標頭的問題。


- 我們已修正將多個訊息項目從 [焦點] 移至 [其他] 或從 [其他] 移至 [焦點] 時，導致使用者只看到訊息子集移動的問題。


- 我們已修正即使具有正確權限，導致委派仍無法開啟共用連絡人資料夾的問題。


- 我們已修正使用者在嘗試開啟具有編輯者或委派權限的共用連絡人資料夾時收到錯誤訊息的問題。


- 我們已修正啟用共用行事曆改進功能時，導致給會議室信箱代理人的所有轉寄會議邀請上顯示「不需要回應」的問題。


- 我們已修正導致使用者從委派分組討論區信箱轉寄出的所有會議邀請上看到特定「不需要回應」的問題。


- 我們已修正會導致使用者在嘗試回應特定連絡人時，遇到意外關閉的問題。


- 我們已修正會導致使用者在回復或轉寄訊息時無法載入連結影像的問題。


- 我們已修正導致 Exchange 2019 使用者在搜尋結果中看到 Outlook 未在郵件上顯示回復指標圖示的問題。


- 我們已修正導致使用者在某些情況下，會看到呈現多個共用行事曆複本的問題。


- 我們已修正導致使用者的問題，因此請參閱錯誤訊息「嘗試的操作失敗。 搜尋 LDAP 通訊錄時找不到物件」。


- 我們已修正在 GCC-High 環境中導致會議室尋找工具無法載入的問題。


- 我們已修正使用者無法將會議室信箱新增至行事曆的問題。


- 我們已修正使用 [開啟共用行事曆] 時，未在流覽窗格中選取行事曆的問題。


- 我們已修正導致使用者在刪除資料時意外遇到關閉的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正當其他人共同撰寫時，變更文件的敏感度標籤，可能會失去挑選的敏感度標籤的問題。


- 在 Office 2016 和 Office 365 Visual Refresh 中，已改善工作窗格和對話方塊中彩色和白色主題中暫留和按下滑杆的可見度。<br />
- 在已啟用 Fluent 視覺效果的Office 365中，已改善工作窗格和對話方塊中深灰色和黑色主題中暫留和按下滑杆的可見度。<br />
- 在具有 Visual Refresh Darky Gray 主題的Office 365中，防止捲動按鈕框線出現在功能區字型選擇器下拉式清單中的問題已解決。


- 我們已修正當人員嘗試在不受支援區域中使用地圖圖表時提供詳細資訊的問題。


- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 我們已修正使用瀏覽至位置時，儲存為不需要強制敏感度標籤的問題。


### <a name="project"></a>Project

- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 我們已修正與語音存取相關的協助工具問題，其中資料行標題號碼不會出現在 [排程詳細資料] 頁面等方格中。


- 我們已修正當使用者無法開啟專案時，導致應用程式意外關閉的問題。


- 我們已修正應用程式在未完成資源撫平時停止回應的問題。


- 我們已修正遮罩分隔符號與清單分隔符號相符時，會使用星號 (*) 的問題。 在篩選器中 * 用於規則運算式，如果其包含值，就會導致錯誤和意外行為。 管道 (|) 現在已使用。


- 我們已修正應用程式開啟不再可用的畫面，導致專案隱藏的問題。


- 我們已修正無法再開啟之前正常運作的專案的問題。 在此情況下，Project 意外關閉。


- 我們已修正訊息「此專案包含一或多個可能不安全且已停用的資料來源連結的問題。 您要啟用這些資料來源嗎？ 只有當您信任檔案的來源時，才能這麼做。」 開啟專案時可能會出現。 即使專案沒有任何作用中的貼上連結，訊息也會出現。 此外，在甘特圖類型檢視中找不到使用中的内嵌物件。


- 我們已修正在檢視和報告指派時段實際成本值時，這些值的總和可能不等於純量值， (您在工作表檢視中看到的值) 。 隨著時幅細微性從詳細 (例如每日) 變為較不詳細 (例如每年)，差異可能會增加。


### <a name="visio"></a>Visio

- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 我們已修正 Visio 中導致應用程式在重複放大和縮小時停止回應的問題。


### <a name="word"></a>Word

- 我們已修正在少數共同撰寫者實例中，某些註解的回復直到下次開啟文件時才會顯示的問題。


- 我們已修正 UI 有時候停止在 arm64 裝置上演繹的問題。


- 在 Office 2016 和 Office 365 Visual Refresh 中，已改善工作窗格和對話方塊中彩色和白色主題中暫留和按下滑杆的可見度。<br />
- 在已啟用 Fluent 視覺效果的Office 365中，已改善工作窗格和對話方塊中深灰色和黑色主題中暫留和按下滑杆的可見度。<br />
- 在具有 Visual Refresh Darky Gray 主題的Office 365中，防止捲動按鈕框線出現在功能區字型選擇器下拉式清單中的問題已解決。


- 我們已修正使用 97-2003 檔案格式載入 PowerPoint 檔案時，無法辨識 VBA 專案數位簽章的問題。


- 我們已修正當人員嘗試在不受支援區域中使用地圖圖表時提供詳細資訊的問題。


- 我們已修正在其他應用程式中顯示內嵌 Excel 試算表的問題。


- 我們已修正 Office 呈現程式碼中意外停止回應的問題。


- 我們已修正 Office「插入螢幕擷取畫面」 顯示 Office Apps 的空白/不完整螢幕擷取畫面的問題；我們已修正 Office 應用程式的部分 Windows 工作列縮圖螢幕擷取畫面可能會顯示空白的問題。


- 我們已修正導致 Word 中間歇性停止回應的問題。


- 我們已修正導致共用行事曆在新增後處於未選取狀態的問題。


- 我們已修正使用者無法將資料表的資料列從版本歷程記錄中的舊版複製到目前版本的問題。


- 我們已修正 Outlook 無法開啟使用Outlook 網頁版傳送的訊息，且包含從 Word 複製的批註的問題。


- 我們已修正 Outlook (WordMail) 訊息會在放大或縮小時出現白色背景閃爍的問題。


- 我們已修正列印含有索引的頁面可能無法列印的問題。


- 我們已修正標頭巢狀欄位在捲動時顯示不正確的問題。


- 我們已修正使用中文匯出至 PDF 時，某些特殊字元會顯示替代字型的問題 (傳統) Windows 顯示語言。


- 我們已修正刪除段落標記之後，文件會捲動至結尾的問題。


- 我們已修正「以連結貼上」可能無法自動更新的問題。


- 我們已修正了減少與具有相同超連結之檔的合併衝突的問題。


- 我們已修正共同撰寫時移除標頭樣式的問題。


- 我們已修正連結不會自動更新至內嵌 Word 檔的問題。


- 我們已修正未登入使用者的 [大聲朗讀] 會意外關閉的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正在解決許多從 OneDrive 或 SharePoint 開啟 Word、Excel 或 PowerPoint 文件時，會導致意外關閉的案例問題。


- 我們已修正導致連絡人卡片無法適當顯示的問題。


- 我們已修正在 Excel 中開啟字型大小下拉式清單時，強調顯示字型大小不是文件中目前選取的字型大小的問題。


- 我們已修正字型下拉式清單無法正確反映圖形中選取的字型的問題。


- 我們已修正針對不支援字型服務的端點發出字型下載要求的問題。 這些要求已知會針對這些端點停止運作，因此我們甚至不應該嘗試針對不支援的端點發出這些要求。


- 我們已修正在已知且預期字型下載在下載期間停止運作時嘗試下載字型的問題，這會造成使用不必要的資源。


- 我們已修正引入新視覺效果的影片無法顯示的問題。


- 我們已修正使用圖形和 SmartArt 的色彩選擇器文字選取案例中的問題。


- 我們已修正作業會重新安裝 Office 的問題。


- 我們已修正在更新期間造成「發佈封裝失敗」錯誤，導致檔案類型關聯遺失的問題。


- 我們已修正當 PowerShell 停用時，使用者會無法安裝 M365 應用程式的問題。


- 我們已修正 Office 呈現程式碼中關閉的問題。


- 我們已修正與使用者介面動畫相關的不穩定問題。


- 我們已修正在按一下滑桿時，允許新增漸層停駐點的問題。


- 我們已修正 Direct2D 和 Direct3D 互通性的多執行緒相關問題。


- 我們已修正與 SVG 圖形內的文字配置相關的問題。


- 我們已修正 SVG 物件處理 text-anchor：end 屬性並正確維護目前文字位置的問題。


- 我們已修正在 Outlook 中轉譯 SVG 圖形的相關問題。


- 我們已修正錄製投影片放映時的穩定性問題。


- 我們已修正停止錄製投影片放映時的穩定性問題。


- 我們已修正錄製簡報時發生錯誤且錄製會停止的問題。


- 我們已修正在儲存檔案期間，Web 增益集中的設定可能會遺失的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2202-august-09"></a>版本 2202：8 月 09 日
*版本 2202 (組建 14931.20660)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正 Excel 可能會顯示訊息列指出需要強制敏感度標籤的問題，即使檔案已經有標籤也一樣。


### <a name="outlook"></a>Outlook

- 我們已修正導致半年通道 (版本 2202 中 Outlook Desktop 的使用者) 遇到設定檔損毀問題，導致共用資料夾和行事曆中的同步處理失敗、接收已傳遞訊息的 NDR，以及共用資料夾中的搜尋失敗等徵兆。  遇到此問題的使用者必須重新建立其設定檔，才能還原正常作業。


- 我們已修正使用者無法將會議室信箱新增至行事曆的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用瀏覽至位置時，儲存為不需要強制敏感度標籤的問題。


### <a name="word"></a>Word

- 我們已修正複製和貼上編號清單可能不會產生正確編號的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2202-july-26"></a>版本 2202: 7 月 26 日
*版本 2202 (組建 14931.20646)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access


- 我們已修正嘗試開啟在 Access 中建立的 ACCDE 或 MDE 檔案時，導致錯誤的問題。 如需詳細資訊，請參閱 [嘗試開啟以不同 Access 版本建立之 ACCDE/MDE 檔案時發生錯誤。](https://support.microsoft.com/topic/f4cd36cd-549e-42ba-b75a-dfe964294a81)




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2202-july-12"></a>版本 2202：7 月 12 日
*版本 2202 (組建 14931.20604)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正如果資料庫中有 SharePoint 清單的連結，PowerBI 有時會停止從 Access 資料庫重新整理資料的問題。


### <a name="excel"></a>Excel

- 我們已修正在使用 Power Pivot 時，嘗試連線到資料摘要時會發生錯誤的問題。


- 我們已修正 .xls 格式的共用活頁簿可能會不當合併變更的問題。


- 我們已修正 AMSI 掃描會導致應用程式意外關閉的問題。


- 我們已修正啟用導致 XL4 巨集停用的群組原則時，求解器無法運作的問題。


- 我們已修正使用使用者介面自動化和處理具有許多隱藏資料列和/或資料行的大型資料集時，效能緩慢或凍結的問題。


### <a name="outlook"></a>Outlook

- 我們已修正在 GCC-High 環境中導致會議室尋找工具無法載入的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正在 PowerPoint 中建立新文件時未正確套用預設敏感度標籤的問題。


### <a name="word"></a>Word

- 我們已修正特定的紙張在 Outlook 中列印時會重疊的問題。


- 我們已修正從不同用戶端合併註解之後，Word 文件中註解的 UTC 時間戳記不一致的問題。


### <a name="office-suite"></a>Office 套件

- 此更新修正了可能導致使用 Microsoft.ACE.OLEDB.12.0 或 Microsoft.ACE.OLEDB.16.0 提供者連線到 SharePoint 資料的應用程式意外關閉的問題。


- 變更將允許 IT 系統管理員在 Microsoft 365 應用程健康情況的 [增益集健康情況] 頁面中，查看半年企業通道中裝置的私人增益集。 增益集是 Office 意外關閉的主要來源，而透過 [增益集健康情況] 頁面，系統管理員會看到其部署在其租用戶中的增益集健康情況，並辨識出潛在問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2202-june-14"></a>版本 2202: 6 月 14 日
*版本 2202 (組建 14931.20494)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正嘗試在唯一識別碼欄中支援 Unicode 字元時所造成的問題。


### <a name="excel"></a>Excel

- 我們已修正使用 Inquire 巨集的比較檔案功能，或從開始處運行試算表比較時，在某些情況下無法偵測到巨集差異的問題。


- 我們已修正在具有圖表工作表的活頁簿上執行 VBA 指令碼/增益集時，可能會導致 Excel 意外關閉的問題。


### <a name="outlook"></a>Outlook

- 我們已修正當事件型增益集在背景中執行時，在回覆或轉寄電子郵件時應用程式意外關閉的問題。


- 我們修正了使用者嘗試從功能區按鈕、資訊列或 Outlook win32 中可採取動作的郵件開啟增益集 (Viva Insights) 時，看到灰色方塊 (Viva Insights 的增益集載入體驗) 的問題。 只有在使用信任的沙箱來託管 Viva Insights 時，才會發生此問題。


- 我們已修正啟用共用行事曆改進功能時，導致給會議室信箱代理人的所有轉寄會議邀請上顯示「不需要回應」的問題。


- 我們已修正使用者在嘗試開啟具有編輯者或委派權限的共用連絡人資料夾時收到錯誤訊息的問題。


- 我們已修正導致使用者的問題，因此請參閱錯誤訊息「嘗試的操作失敗。 搜尋 LDAP 通訊錄時找不到物件」。


- 我們已修正導致未啟用的「在電話上播放」按鈕啟用的問題。


- 我們已修正導致使用者在某些情況下，會看到呈現多個共用行事曆複本的問題。


- 我們已修正使用 [開啟共用行事曆] 時，未在瀏覽窗格中選取行事曆的問題。


### <a name="project"></a>Project

- 我們已修正遮罩分隔符號與清單分隔符號相符時，會使用星號 (*) 的問題。 在篩選器中 * 用於規則運算式，如果其包含值，就會導致錯誤和意外行為。 管道 (|) 現在已使用。


### <a name="word"></a>Word

- 我們已修正使用巨集在 Word 文件集合中查看頁面時，發生意外關閉的問題。


- 我們已修正刪除段落標記之後，游標會卷至文件尾端的問題。


- 我們已修正在大型 Word 文件中搜尋關鍵字時的潛在績效問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正在 Excel 中開啟字型大小下拉式清單時，強調顯示字型大小不是文件中目前選取的字型大小的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2202-may-10"></a>版本 2202：5 月 10 日
*版本 2202 (組建 14931.20392)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正 Outlook 在呼叫 ResolveContacts 數千次之後，嘗試回應特定連絡人時會停止回應的問題。


- 我們已修正在會議自動儲存之後，會傳送給出席者，但不會儲存在召集人行事曆上的問題。


- 我們已修正使 Outlook 事件型增益集無法正常運作的問題。


### <a name="project"></a>Project

- 我們已修正應用程式開啟不再可用的畫面，導致專案隱藏的問題。


### <a name="word"></a>Word

- 我們已修正使用 97-2003 檔案格式載入 PowerPoint 檔案時，無法辨識 VBA 專案數位簽章的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正 Outlook 事件型增益集的跨原始來源要求意外停止運作的情況。


- 我們已修正改善 ARM64 上 Office 可靠性和安全性的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2202-april-12"></a>版本 2202: 4 月 12 日
*版本 2202 (組建 14931.20274)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正當來源資料直接輸入圖表而非來自儲存格範圍時，圖表座標軸上的日期不會出現的問題。


- 我們已修正使用自訂命令列可能會導致 Excel 意外關閉的問題。


- 我們已修正顯示某些 SVG 檔案的問題。


### <a name="outlook"></a>Outlook

- 我們已修正使用 [僅加密] 和 [不要轉寄]範本的訊息透過物件模型傳回未預期權限的問題。


- 我們已修正在使用雲端設定時，導致某些切換類型選項進行錯誤同步處理的問題。


- 我們已修正導致「索引過期」訊息太常顯示的問題。


- 我們已修正導致在部分診斷案例中，使用者在 Outlook 中預期停止回應的問題。


- 我們已修正啟用 REST 共用行事曆功能時，已移除的共用行事曆會再次出現的問題。


- 進行了一項資料變更，在英國行事曆中包含了新的英國假日。


- 我們已修正在某些情況下，導致 Outlook 在關機期間意外關閉的問題。


- 我們已修正顯示某些 SVG 檔案的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修儲存 PPAM 檔案類型時造成問題的案例。


### <a name="project"></a>Project

- We fixed an issue where the user would see a security dialog stating that the project had links to one or more data sources, even though the project had no active links. Now, the dialog appears only when there are active links.


### <a name="publisher"></a>發行者

- 我們已修正顯示某些 SVG 檔案的問題。


### <a name="word"></a>Word

- 我們已修正在其他應用程式中顯示內嵌 Excel 試算表的問題。


- 我們已修正顯示某些 SVG 檔案的問題。


- 我們已修正在 Word 中 SVG 檔案可能會顯示為中斷連結的問題 (Red-X)。


- 我們已修正導致共用行事曆在新增後處於未選取狀態的問題。


- 我們已修正當開啟具有數千個追蹤變更的 Word 檔時的效能問題。


- 我們已修正傳送電子郵件通知給留言已獲得其他使用者回覆的使用者時的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正字型下拉式清單無法正確反映圖形中選取的字型的問題。


- 我們已修正記憶體可能損毀之輸入來源的捲動繫結相關問題。


- 我們已修正影響在 Project 中自訂檢視顯示的問題。


- 我們已修正在啟動或錄製投影片放映時，與 Power BI 控制項和表單做為投影片內容相關的穩定性問題。


- 我們已修正 Direct2D 和 Direct3D 互通性的多執行緒相關問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2202-march-08"></a>版本 2202：3 月 8 日
*版本 2202 (組建 14931.20132)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新

### <a name="excel"></a>Excel

- **Create a custom data type in Power Query:** Use any data source to create a custom data type that lets you load multiple related pieces of information into one column. [Learn more](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br />在[部落格文章](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)中查看詳細資料

- **Office 應用程式現在支援 OpenDocument 格式 (ODF) 1.3：** ODF 1.3 對 OpenDocument 格式帶來許多改良功能，而且這些功能現在都可在 Word、Excel 及 PowerPoint (副檔名 .odt、.ods 和 .odp) 中受到支援。<br />在[部落格文章](https://insider.office.com/en-us/blog/office-apps-now-support-opendocument-format-odf-1-3)中查看詳細資料

- **敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft Purview 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。


- **DLP policy tips in Word/Excel/PowerPoint:** Additional sensitive information types configured as part of OneDrive and SharePoint data loss prevention (DLP) policies can now be detected by the app to show a policy tip. This update also brings accuracy improvements and globalization support. [Learn more](/microsoft-365/compliance/sensitive-information-type-learn-about)

- **Excel 4.0 (XML) 巨集會預設停用以提升 Microsoft 365 客戶的安全性。:** 為協助保護客戶，Excel 4.0 (XML) 巨集在 Microsoft 365 中會預設停用。 我們建議您將這些巨集遷移至最新版本的 Microsoft Visual Basic for Applications (VBA)。 [深入了解](https://support.office.com/article/ba8924d4-e157-4bb2-8d76-2c07ff02e0b8)

### <a name="outlook"></a>Outlook

- **Microsoft 搜尋支援的撰寫 (收件者/副本/密件副本) 建議**：將人員新增至收件者/副本行，現在會由 Microsoft 搜尋提供支援。

- **在干擾較少的情況下閱讀訊息：** 開啟沈浸式閱讀程式，以自訂文字間距、頁面色彩、欄寬和行聚焦，讓您更輕鬆地專注於訊息。

- **自動展開線上封存搜尋：** 啟用自動展開線上封存搜尋。 您可以在此找到與無限制封存相關的詳細資訊：[自動展開封存功能的概觀](/microsoft-365/compliance/unlimited-archiving)

- **瀏覽群組 OPX：** 瀏覽群組的 OPX 體驗以支援工程靈活度。

- **敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。

- **開啟共用行事曆改良功能：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。 開啟預覽，以更快速且更可靠地更新共用行事曆。<br />在[部落格文章](https://insider.office.com/en-us/blog/shared-calendars-improvements-in-outlook-for-windows)中查看詳細資料

- **讓所有人都可以存取您的訊息：** Outlook 會在您傳送訊息時，自動讓您知道訊息中何時有協助工具問題，並協助您修正問題。<br />在[部落格文章](https://insider.office.com/en-us/blog/sending-accessible-emails-in-outlook-for-windows)中查看詳細資料

- **Expanded GAL people suggestions for mail and calendar compose:** Outlook will now return results from the complete GAL when suggestions people for email and calendar compose. (Ex: Adding someone to the To line of a new email)

### <a name="powerpoint"></a>PowerPoint

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦 [深入了解](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

- **Support for Windows 10 Large Text setting:** You can use the Large Text setting in Windows 10 (version 1809 and later) to make text larger so that it is easier to read.  It works well in PowerPoint for Windows.

- **Office 應用程式現在支援 OpenDocument 格式 (ODF) 1.3：** ODF 1.3 對 OpenDocument 格式帶來許多改良功能，而且這些功能現在都可在 Word、Excel 及 PowerPoint (副檔名 .odt、.ods 和 .odp) 中受到支援。<br />在[部落格文章](https://insider.office.com/en-us/blog/office-apps-now-support-opendocument-format-odf-1-3)中查看詳細資料

- **敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft Purview 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。

- **DLP policy tips in Word/Excel/PowerPoint:** Additional sensitive information types configured as part of OneDrive and SharePoint data loss prevention (DLP) policies can now be detected by the app to show a policy tip. This update also brings accuracy improvements and globalization support. [Learn more](/microsoft-365/compliance/sensitive-information-type-learn-about)

- **從 PowerPoint 到 Teams 進行展示：** PowerPoint 應用程式直接透過 PowerPoint Live 將您的幻燈片展示到 Teams 會議。

### <a name="word"></a>Word

- **敏感度標籤稽核記錄**：現在當使用者在文件和電子郵件上套用、變更或移除敏感度標籤時，系統就會將該資訊提供給 Microsoft 365 稽核記錄中的系統管理員使用。

- **自動儲存並在敏感性加密文件上進行共同撰寫：** 不要為了安全性而犧牲生產力。 有了 Microsoft Purview 資訊保護，使用敏感度標籤加密的文件現在可以自動儲存，並與他人進行即時共同撰寫，就彷彿文件未加密一樣便利。 需要租用戶選擇加入 (詳細資訊： https://aka.ms/mipcoauth)。

- **DLP policy tips in Word/Excel/PowerPoint:** Additional sensitive information types configured as part of OneDrive and SharePoint data loss prevention (DLP) policies can now be detected by the app to show a policy tip. This update also brings accuracy improvements and globalization support. [Learn more](/microsoft-365/compliance/sensitive-information-type-learn-about)

### <a name="office-suite"></a>Office 套件


- **首頁橫幅可讓 Microsoft 在其裝置上推薦使用者在其Microsoft 365 Apps 企業版中擁有的功能：** 從 2202 版開始，從每月企業通道取得更新的使用者、Semi-Annual Enterprise Channel (Preview) 和 Semi-Annual Enterprise Channel 也會看到這些建議。 當使用者按一下 [檔案] 功能表時，[首頁] 索引標籤可能會顯示具有功能建議的橫幅。 每個建議都會隨附 [學習] 按鈕，讓使用者前往說明檔或功能相關教學課程。 另外還有關閉橫幅的 [關閉] 選項。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此更新修正了應用程式停止運作的問題，並產生錯誤訊息，例如「無法開啟其他資料庫」；此問題也可能會導致 Access 無法正確關閉。


- 我們已修正錯誤嘗試使用來自非 Office 應用程式的 DAO API 時，會停止回應並顯示訊息「作業系統目前未配置成執行此應用程式」的問題。


- 此變更可修正當資料庫包含 SharePoint 清單的連結時，可能導致使用 OLEDB API 開啟 Access 資料庫 (.accdb 檔案) 的應用程式意外關閉的問題。


- 我們已修正使用多個執行緒連線到 Access 或 Jet 資料庫時會導致應用程式意外關閉的問題。


- 我們已修正會造成使用 OLEDB 介面的自訂應用程式開啟包含 SharePoint 清單連結的 Access 資料庫意外關閉的問題。


- We fixed an issue that would prevent multiple users from opening a database on a network file share. [Learn More](https://support.microsoft.com/en-us/office/access-error-could-not-use-path-to-database-accdb-file-already-in-use-6cbc1560-62c2-46e7-9980-d079a46f5acc)


- 我們修正了執行應用程式時可能導致錯誤的問題。


- 我們修正了導致 Insights 增益集停止運作的問題。


- 這項變更可啟用針對 Outlook 增益集 1.11 和 1.9 需求集合的完全支援。


- 我們修正了導致更新版本 Viva Insights 增益集載入效率較低的問題。


- In certain customer configurations, it was discovered that document exports to PDF or XPS formats from Office would fail due to recent updates. This update fixed these regressions and reenabled export to these formats.


- 我們已修正當我們開啟隱私權設定視窗時，應用程式停止回應的問題，因為對話方塊管理員是空白的新增不是空白檢查做為檢查。


### <a name="excel"></a>Excel

- 我們已修正當資料中不再存在篩選值時，重新整理樞紐分析表資料可能會停止運作的問題，並且在缺少無效篩選值所產生的後續查詢陳述式，重試重新整理要求暫時遭到停用，而現在已重新啟用。


- 我們已修正在 SpreedsheetCompare 工具中開啟 a .xlsm 檔案可能導致工具停止回應的問題。


- 我們已修正圖形和表單控制項無法呼叫 VBA 巨集的問題。


- 我們已修正使用交叉分析篩選器和協助工具時的效能問題。


- 我們已修正 LOGEST 工作表函數的問題，該函數不會處理並清除暫時性溢位錯誤，且後續的計算不正確。


- 我們已修正在樞紐分析表欄位選取工作窗格中，搜尋文字會重設的問題。


- 我們修正了當樞紐分析表中有隱藏的欄位時，小計最佳化的問題。


- 應用程式在非 MSI 的 Office 安裝中清除 HKEY_CURRENT_USER\SOFTWARE\Microsoft\Office\Common\UserInfo\Company 的值。 我們已修正主要影響使用非 MSI 版本 Office 客戶的問題。


- 我們已修正應用程式在下列情況下，可能會在計算活頁簿時停止回應的問題。


- 我們已修復當樞紐分析表中有隱藏的欄位時，小計最佳化的問題。


- 我們已修正在公式中使用儲存格參照導致使用者遇到高 CPU 使用量的問題。


- 我們已修復此問題: 如果來源檔案來自 OneDrive 位置且檔案名稱包含 HTML 編碼字元, 將 Excel、Word 或 PowerPoint 內嵌物件加入 Excel 檔時, 未正確顯示應用程式的原始圖示。


- 我們已修正查詢更新導致應用程式停止回應的問題。


- 我們已修正 LOGEST 工作表函數的問題，該函數不會處理並清除暫時性溢位錯誤，且後續的計算不正確。


- 我們已修正與表單控制項互動可能會導致 Excel 意外關閉的問題。


- 我們已修正 WEBSERVICE 工作表函數的問題，在極少數的情況下，Excel 會在使用者取消計算時停止運作。


- 我們已修正此問題: 如果資料來源範圍變更，新建立的樞紐分析表可能會失去自訂的設定。


- 我們已修正某些公式結果在輸入變更後無法更新的問題。


- 我們已修復當樞紐分析表中有隱藏的欄位時，小計最佳化的問題。


- 我們已修正了一個問題，以調整瀑布圖中資料數列的漸層填滿與直條圖中資料數列的漸層填滿如何對齊


- 在含兩個儲存格編輯方塊的多顯示器設定對話方塊中，會在選取儲存格時對使用者隱藏資料。 這個修正會取消隱藏 UI 對話方塊中的資料。 變更會影響三個監視器安裝上的條件式格式設定或資料數列選取對話方塊。


- When you have an Microsoft Excel 97-2003 Worksheet object embedded inside another application such as a Word document, using the Convert feature to convert it to an Microsoft Excel Worksheet (Office OpenXML) object doesn't complete the conversion until you open the embedded object and make a change to it.  This has been fixed so that the object is completely converted upon using the Convert feature.


- 我們已修正在樞紐分析表欄位選取工作窗格中，搜尋文字會重設的問題。


- 我們已修正某些工作表函數未針對使用特定語言使用者顯示的問題。


- 我們已修正少數 GCC-H 租用戶無法使用自動敏感度標籤的問題。


- 我們已修正開啟 Excel 檔案時儲存格選擇取關閉的問題。


- 開啟 Dynamics 的連結資料表時，顯示資料時，數字可能會呈現為小型方塊。 若要解決此問題，請在資料表設計檢視中開啟連結，並清除任何受影響資料行的格式屬性。


- 已修正使用 OLEDB API 和 ACE.OLEDB.12.0 或 ACE.OLEDB.16.0 提供者的應用程式意外關閉的問題。


- 此版本修正了在儲存租用戶中的某些文件時發生的意外關閉問題，如果本地檔案快取的租用戶識別碼資材格式不正確，在 [儲存] 租用戶選擇加入保護共同撰寫的一些文件時，就會發生此情況。


- In certain customer configurations, it was discovered that document exports to PDF or XPS formats from Office would fail due to recent updates. This update fixed these regressions and reenabled export to these formats.


- 我們已修復在 Office 應用程式之間，以不同方式轉譯 BizUD Gothic 日文字型的問題。


- 我們已修正當我們開啟隱私權設定視窗時，應用程式停止回應的問題，因為對話方塊管理員是空白的新增不是空白檢查做為檢查。


### <a name="onenote"></a>OneNote

- 我們已修正將建立 [快速筆記] 的熱門金鑰更新為 Win + Alt + N 的問題。


### <a name="outlook"></a>Outlook

- 我們已修正在展開交談時，導致使用者遇到停止回應的問題。


- 我們已修正會在產生預覽時，導致同步處理停止運作的問題。


- 我們已修正會導致使用 Windows 11 的使用者，或透過「即將推出」使用視覺效果的使用者，在將游標停留在迷你行事曆日期時看到文字未對齊的問題。


- 我們已修正了資料夾階層未能同步處理超大型主要信箱 (超過 10000 個資料夾) 所有資料夾的問題。


- 我們已修正收到的電子郵件不會包含開啟郵件的連結的問題。


- 我們修正了導致所有使用敏感度標籤所送出的電子郵件持續使用「僅加密」範本，導致不正確的行為，允許人員轉寄「僅收件者」電子郵件的問題。


- 我們已修正導致使用者無法從受保護的語音信箱訊息下載 MP3 附件的問題。


- 我們已修正導致使用者在 Outlook 重新啟動之後，無法將其預設簽名插入新電子郵件、回覆或轉寄的問題。


- 我們已修正造成 [會議室尋找工具] 無法載入的問題。


- 我們已修正導致使用者能夠下載受保護的語音信箱檔案的問題。


- 我們已修正會導致某些使用者在新增共用行事曆後遇到意外關閉的問題。


- 我們已修正導致螢幕閱讀器無法存取特定的智慧連結註標的問題。


- 已修正將連絡人匯出至 CSV 時導致使用者在某些欄位中看到亂碼文字的問題。


- 我們已修正會導致使用 Windows 11 的使用者，或透過「即將推出」使用視覺效果的使用者，在調整 Outlook 視窗時，在功能區中看到一些對齊問題和奇怪的視覺效果構件的問題。


- 我們已修正在移動個人卡片時，導致使用者遇到停止回應的問題。


- 我們已修正導致使用者在 Outlook 中更新使用者目前狀態資訊時意外遇到停止回應的問題。


- 我們已修正在檢索角色時，造成使用者遇到意外關閉的問題。


- 我們已修正會導致使用者在 PowerPoint 中載入角色時遇到意外關閉的問題。


- 我們已修正會導致顯示連絡人卡片時意外關閉的問題。


- 我們已修正會導致使用者在載入人員相片時遇到意外關閉的問題。


- 我們修正了載入角色時導致停止回應的問題。


- 我們修正了應用程式在載入連絡人卡片後變成無回應的問題。


- 我們已修正收到的電子郵件不會包含開啟郵件的連結的問題。


- 我們修正了造成使用者無法開啟已套用數位版權管理原則之郵件的問題。


- 我們修正了使用者變更訊息中連結的權限時，導致智慧連結 URL 無法更新的問題。


- 我們已修正以滑鼠右鍵按一下並選取檔案系統中的「傳送郵件」來傳送郵件，導致 explorer.exe 在 VDI 電腦上意外關閉的問題。


- 我們已修正會導致 Outlook 使用者的「共用行事曆改良」功能遇到高 CPU 使用率的問題。


- 我們已修正在嘗試擷取 [自動探索] 設定時，導致某些使用者遇到停止回應的問題。


- 我們修正了導致會議約會檢視中的捲軸水平縮小的問題。


- 我們修正了導致使用者在切換資料夾時因檢視設定損毀而出現效能問題之問題。


- 我們已修正在預期自訂圖示時，會針對附加的郵件顯示預設圖示的問題。


- 我們已修正會導致成員資格清單無法針對連絡人卡片顯示的問題。


- 我們已修正會導致使用者看到他們新增的共用行事曆預設未經過檢查，導致他們認為無法新增該行事曆的問題。


- 我們已修正會導致新增到「捷徑」模組的行事曆，在 Outlook 重新啟動後會消失的問題。


- 我們修正了導致使用者載入 [行事曆] 模組的功能窗格時，遇到「停止」回應的問題。


- 我們修正了預覽會議邀請時導致約會快速模式被裁掉的問題。


- 我們已修正在繪製影像時，可能會停止回應的問題。


- 我們已修正當我們開啟隱私權設定視窗時，應用程式停止回應的問題，因為對話方塊管理員是空白的新增不是空白檢查做為檢查。


### <a name="powerpoint"></a>PowerPoint

- 我們修正了無法按一下某些彈出 UI 元素的問題，例如，Outlook 中的 [加入會議] 快顯視窗，或 PowerPoint 中的 [歡迎回來] 快顯視窗。


- 產品已更新，不會在執行儲存複製作業時，將變更儲存到原始雲端檔案，並關閉自動儲存。


- 我們已修正當使用者將原始直向和較大的紙張大小文件變更為較小的紙張大小 (例如，從 Letter 變更為 A5) 時，其列印可能會遭到截斷 (遺失資料) 的問題。


- 我們已修正從 C2R 安裝之 PowerPoint 在 [資訊] | [屬性] | [進階屬性] 對話方塊中顯示公司資訊的問題。


- 我們已修正問題, 因此如果使用者明確以唯讀模式開啟檔案, 應用程式就不會再提示輸入密碼來修改。


- 此版本修正了在儲存租用戶中的某些文件時發生的意外關閉問題，如果本地檔案快取的租用戶識別碼資材格式不正確，在 [儲存] 租用戶選擇加入保護共同撰寫的一些文件時，就會發生此情況。


- In certain customer configurations, it was discovered that document exports to PDF or XPS formats from Office would fail due to recent updates. This update fixed these regressions and reenabled export to these formats.


- 我們已修正 Word 存檔時，所花時間超過預期的問題。


- 我們已修正當我們開啟隱私權設定視窗時，應用程式停止回應的問題，因為對話方塊管理員是空白的新增不是空白檢查做為檢查。


- 我們已修正在繪製影像時，可能會停止回應的問題。


### <a name="project"></a>Project

- 我們已修正一個問題，使用者現在可以將專案儲存至 Project Web 應用程式，即使離線檔案中資源的名稱符合企業資源亦然。


- 當使用者將以伺服器為基礎的專案儲存為 MPP 檔案時，我們不再覆寫本機格式設定。


- 我們已修正當透過 CSOM 以程式設計方式將新工作新增到專案時，如果新工作的工作摘要已摺疊，工作可能無法插入正確位置的問題。


- 我們已修正在 Project 中重新排程工作時，手動排程的工作可能會早於其預定排程時間的問題。


- 我們修正了一個問題，即當使用者開啟已儲存為其他名稱的專案時，已手動排程的工作被重新排程至更早的日期。 在開啟這些專案時，使用者不應再看到已手動排程的工作被重新排程。


- 我們已修正載入自訂報告時某些專案會意外關閉的問題。


- 我們已修正使用者進入無法儲存的狀態問題。 此修正使得使用者一律可以儲存其工作。


- 我們已修正一個問題，使用者現在可以將專案儲存至 Project Web 應用程式，即使離線檔案中資源的名稱符合企業資源亦然。


- 使用者在列印甘特圖上的進度線時，應該不會再經歷問題。


### <a name="skype"></a>Skype

- 已修正部分膝上型電腦的混合式相機未在 SfB 用戶端中顯示的問題。


- 我們已修復在交談視窗中影片共用預覽會意外關閉的問題。


### <a name="visio"></a>Visio

- 我們已修復此問題：使用者現在可以順利插入圖表，而不會出現應用程式意外關閉的任何問題。


### <a name="word"></a>Word

- 我們修正了無法按一下某些彈出 UI 元素的問題，例如，Outlook 中的 [加入會議] 快顯視窗，或 PowerPoint 中的 [歡迎回來] 快顯視窗。


- 我們已修正 x64 使用者的 Word [檔案] > [選項] 功能表中的主題選擇器無法套用所選佈景主題的問題。 [檔案] > [帳戶] 位置中的佈景主題選擇器仍可運作，且不受此變更影響。


- 我們已修正包含外部內容的 SVG 影像可能無法顯示的問題。


- 此版本修正了在儲存租用戶中的某些文件時發生的意外關閉問題，如果本地檔案快取的租用戶識別碼資材格式不正確，在 [儲存] 租用戶選擇加入保護共同撰寫的一些文件時，就會發生此情況。


- In certain customer configurations, it was discovered that document exports to PDF or XPS formats from Office would stop working due to recent updates. This update fixed these regressions and reenabled export to these formats.


- 我們已修正與應用程式在呼叫 DCompositionCreateDevice 時停止回應相關的問題。


- 我們已修正導致應用程式在文件中選取移至註解的第一個註解時，應用程式意外關閉的問題。


- 我們已修正插入線上影片按鈕遭到停用的問題。


- 我們已修復在 Office 應用程式之間，以不同方式轉譯 BizUD Gothic 日文字型的問題。


- 我們已修正在啟用 AIP 增益集的情況下儲存文件時，會發生檔案格式變更的問題。


- 我們已修正在使用日文輸入法 (IME) 輸入平假名時，開啟 At Mention 人員選擇器時導致 IME 停止運作的問題。


- 我們已修正嘗試開啟 OneDrive 共用檔案時，應用程式停止回應的問題。


- 我們已修正從首頁 (Home) 索引標籤套用樣式時無法運作的問題。


- 我們修正了重複樣式會套用 Normal，而不是重複樣式的問題。


- 我們已修正 Word 存檔時，所花時間超過預期的問題。


- 我們修復了在匯出為 PDF 後，書籤和目錄連結無法運作的問題。


- 我們已修正當我們開啟隱私權設定視窗時，應用程式停止回應的問題，因為對話方塊管理員是空白的新增不是空白檢查做為檢查。


- 我們已修正在繪製影像時，可能會停止回應的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修復將文件儲存至雲端時，Word、Excel 或 PowerPoint 會意外關閉的問題。


- 我們已修正在快取大量檔案的用戶端上閒置時，Office 應用程式可能會意外關閉的問題。


- 我們已修正會導致連絡人卡片無法顯示的問題。


- 我們已修正 Outlook 中的自訂 VSTO 控制項在開啟和切換多個視窗和視圖之後停止運作的問題。


- 我們已修正完成下列變更的問題:
1. There was a bug in Outlook where the teaching callouts (tips) about the new look of Office did not appear. These will now appear.
2. Many users of Word, Excel, PowerPoint, and OneNote have missed the teaching callouts about the new look of Office, which include information about what changed and how to change settings, or toggle off the experience. This change retriggers these teaching callouts for users to be notified about the changes.


- 我們已修正有關 Office 新外觀的教學圖說內容 (提示) 未出現在 Outlook 中的問題。  現在，Word、Excel、PowerPoint 和 OneNote 的使用者會收到 Office 新外觀變更的通知，其中包含變更內容以及如何變更設定或切換體驗的資訊。


- 已修正與重新整理可能包含文字的元素相關的可靠性問題。


- 已修正使用觸控板時透過點兩下選取文字的問題。


- 我們修正了在無視窗模式中以程式化方式開啟簡報時，可能無法載入連結影像的問題。


- 我們已在 Outlook 預覽窗格中修正問題，允許 SVG 影像正確地轉譯。


- 我們修正了包含無效 SVGs 的文件會顯示點陣化遞補影像，而不是紅色 X 的問題。


- 已修正與 SVG 轉譯中文字錨定相關的問題。


- 我們已修正 Office 在 SSO 和 ADFS DRS 環境中顯示帳戶錯誤的問題。


- 此更新修正 AIP UL 用戶端使用時受保護共同撰寫中的安全性問題。


- 我們修正了以下問題：在受保護的共同撰寫期間，敏感度標籤和加密可能會從 SharePoint 或 OneDrive 中託管的檔案中移除的問題。


- 我們修正了顯示以下錯誤「大聲朗讀沒有開始」的問題。


- 我們修正了偶爾會導致應用程式在啟動時意外關閉的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2108-february-08"></a>版本 2108：2 月 8 日
*版本 2108 (組建 14326.20784)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正關閉檔案時應用程式可能會停止回應的問題。


- 我們已修正嘗試使用 Power Pivot 搭配 Azure Analysis Services 時發生的問題。


- 我們已修正圖形和表單控制項無法呼叫 VBA 巨集的問題。


- 我們已修正在樞紐分析表欄位選取工作窗格中，搜尋文字遭到重設的問題。


- When you had a Microsoft Excel 97-2003 Worksheet object embedded inside another application such as a Word document, using the Convert feature to convert it to an Microsoft Excel Worksheet (Office OpenXML) , in some cases, the object didn't complete the conversion until you opened the embedded object and made a change to it. This issue has been fixed so that the object is completely converted upon using the Convert feature.


### <a name="outlook"></a>Outlook

- 我們已修正當寄件者與全部回覆位址不同且同時是收件者時，會導致全部回覆無法包含該寄件者的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 PowerPoint 中的來源圖表若在 Excel 中調整大小，其格式會不正確的問題。


### <a name="project"></a>專案

- 已修正此問題：報告表中的狀態管理員未更新。 使用者現在應該會看到狀態管理員中反映的變更。


### <a name="word"></a>Word

- 我們已修正關閉檔案時應用程式可能會停止回應的問題。


- 我們已修正選取並以滑鼠右鍵按一下經鎖定而無法刪除的內容控制項時，Word 會沒有回應的問題。


### <a name="office-suite"></a>Office 套件

- 已修正使用觸控板時透過點兩下選取文字的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2108-january-11"></a>版本 2108: 1 月 11 日
*版本 2108 (組建 14326.20738)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正 LOGEST 工作表函數的問題，該函數不會處理並清除暫時性溢位錯誤，且後續的計算不正確。


- 我們已修正與表單控制項互動可能會導致 Excel 意外關閉的問題。


- 我們已修正與具有筆記的活頁簿互動時的效能問題。


### <a name="project"></a>專案

- 已修正此問題：報告表中的狀態管理員未更新。 使用者現在應該會看到狀態管理員中反映的變更。


### <a name="office-suite"></a>Office 套件

- 我們已修正使用者在 Word 或 Outlook 畫布中播放動畫 GIF 時，可能遇到輸入延遲回應的問題，不論是在畫面上或捲動到螢幕外。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2108-december-16"></a>版本 2108：12 月 16 日
*版本 2108 (組建 14326.20702)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- We fixed an issue that would prevent multiple users from opening a database on a network file share.
[Learn More](https://support.microsoft.com/en-us/office/access-error-could-not-use-path-to-database-accdb-file-already-in-use-6cbc1560-62c2-46e7-9980-d079a46f5acc)


### <a name="excel"></a>Excel

- 我們已修復此問題: 如果來源檔案來自 OneDrive 位置且檔案名稱包含 HTML 編碼字元, 將 Excel、Word 或 PowerPoint 內嵌物件加入 Excel 檔時, 未正確顯示應用程式的原始圖示。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2108-december-14"></a>版本 2108：12 月 14 日
*版本 2108 (組建 14326.20692)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正在 SpreedsheetCompare 工具中開啟 xlsm 檔案會導致工具停止回應的問題。


- 我們已修正當資料中不再有已篩選的值時，重新整理 [樞紐分析表] 的資料可能會停止運作的問題。 在缺少無效篩選值所產生的後續查詢陳述，重試重新整理要求暫時遭到停用，而現在已重新啟用。  


- 我們已修正 WEBSERVICE 工作表函數的問題，在極少數的情況下，Excel 會在使用者取消計算時停止運作。


- 我們已修正開啟檔案後，某些公式結果會不正確的問題。


- 我們已修正在公式中使用儲存格參照導致使用者遇到高 CPU 使用量的問題。


- 我們已修正某些公式結果在輸入變更後無法更新的問題。


- 我們已修正少數 GCC-H 租用戶無法使用自動敏感度標籤的問題。


- 我們已修復在 Office 應用程式之間，以不同方式轉譯 BizUD Gothic 日文字型的問題。


### <a name="outlook"></a>Outlook

- 我們已修正當權限應該受到限制時，導致使用者能從受保護的語音信箱訊息中儲存 MP3 附件的問題。


- 我們已修正導致系統管理員無法存取 CLP 稽核功能的問題。


- 我們已修復代理人無法在排程助理員中查看召集人詳細資料的問題。


- 我們已修正以滑鼠右鍵按一下並選取檔案系統中的 [傳送郵件] 來傳送郵件，導致 explorer.exe 在 VDI 電腦上意外關閉的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正當使用者將原始直向和較大的紙張大小文件變更為較小的紙張大小 (例如，從 Letter 變更為 A5) 時，其列印可能會遭到截斷 (遺失資料) 的問題。


- 我們已修復在執行 [儲存複本] 作業時，當 [自動儲存] 關閉時產品更新無法儲存至原始雲端檔案的問題。


### <a name="project"></a>Project

- 我們已修正 XML 還原序列化的安全性問題。


- 我們已修正從遠端來源重新導向 URL 的安全性問題。


- 我們已修正遺失 XML 驗證的安全性問題。


- 我們已修正在還原序列化委派時遠端執行程式碼的安全性問題。


- 我們已修正在 Project 中重新排程工作時，手動排程的工作可能會早於其預定排程時間的問題。


### <a name="skype"></a>Skype

- 已修正部分膝上型電腦的混合式相機未在 SfB 用戶端中顯示的問題。


### <a name="word"></a>Word

- 我們已修正使用放大鏡功能時 Outlook 停止回應的問題。


- 我們已修復在 Office 應用程式之間，以不同方式轉譯 BizUD Gothic 日文字型的問題。


- 我們已修正某些文件的圖形遺失問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2108-november-09"></a>版本 2108：11 月 09 日
*版本 2108 (組建 14326.20600)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正會在產生預覽時導致同步處理失敗發生的問題。


- 我們已修正在嘗試擷取 [自動探索] 設定時，導致某些使用者遇到停止回應的問題。


- 我們已修正會導致使用者看到他們新增的共用行事曆預設未經過檢查，導致他們認為該行事曆尚未新增的問題。


### <a name="word"></a>Word

- 我們已修正 Word 無法呈現電子郵件本文中內嵌 base-64 編碼 GIF 的問題。


- 我們已修正在啟用 AIP 增益集的情況下儲存文件時，會發生檔案格式變更的問題。


- 我們已修正 RTF 格式的效能問題。


### <a name="office-suite"></a>Office 套件

- 我們修正了包含無效 SVGs 的文件會顯示點陣化遞補影像，而不是紅色 X 的問題。


- 已修正可能會讓 Word、Excel、PowerPoint 和 Outlook 用戶端進入一個狀態，在其中我們會對不正確的 URL 端點傳送要求的問題。 特別是，若沒有此修正，我們就可以將美國政府文件內容傳送至全球的 augloop.office.com 端點，或是傳送至較低層級的 USGov 端點 (例如，已傳送至 GCC 的 DoD 資料) 



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2108-october-12"></a>版本 2108: 10 月 12 日
*版本 2108 (組建 14326.20508)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已解決 Excel 在少數情況下，可能會在計算活頁簿時停止回應的問題。


### <a name="outlook"></a>Outlook

- 我們已修正在將行事曆新增至功能窗格，導致某些使用者遇到停止回應的問題。


- 我們已修正會導致 Outlook 使用者的「共用行事曆改良」功能遇到高 CPU 使用率的問題。


- 我們已修正會導致新增到「捷徑」模組的行事曆，在 Outlook 重新啟動後會消失的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2108-september-14"></a>版本 2108：9 月 14 日
*版本 2108 (組建 14326.20404)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere. [Learn more](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps. [Learn more](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography. [Learn more](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦

- **Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once. [Learn more](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- **Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click. [Learn more](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)

- **Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container. [Learn more](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

- **要求使用者套用敏感度標籤：** 當使用者的組織原則要求時，會提示使用者套用敏感度標籤。

- **Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC, GCC-H and DoD environments. [Learn more](/microsoft-365/compliance/sensitivity-labels)

- **Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the DoD environments. [Learn more](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **依訊息擁有者刪除交談：** 此功能可讓您依訊息擁有者刪除交談。

- **電子郵件中的改良連結：** 當您包含檔案的連結時，檔案名會取代 URL。 您可以變更權限，讓所有收件者都能存取。 [深入了解](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br />在[部落格文章](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)中查看詳細資料

- **焦點收件匣設定在不同裝置之間會保持相同：** 您的焦點收件匣喜好設定現在會儲存在雲端。 這麼一來，當您在任何電腦上使用 Windows 版 Outlook 和 Outlook 網頁版時便可享有相同的體驗。 [深入了解](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- **SVG 剪貼簿支援：** 您現在可以將 SVG 內容從 Office 貼上協力廠商應用程式。 [深入了解](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦

- **雲端中的 Outlook 設定：** 選擇您的 Windows 版 Outlook 設定，例如自動回復、焦點收件匣和隱私權，並在任何電腦上使用這些功能。

- **挑選搜尋的位置：** 新的搜尋範圍下拉式清單，可讓您更輕鬆地修改搜尋，並在目前資料夾和目前信箱之間切換。 感謝每個在 [即將推出] 為 [頂極體驗] 的 新 [搜尋] 提供意見反應的人。 因為有這份意見反應，才有這項設計與更新！

- **Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default. [Learn more](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- **每個線上會議** 更新行事曆設定，使您建立的每個會議都預設為 Teams 會議，這樣您就不必再記得按一下 [Teams 會議] 選項。

- **搜尋人員時取得會議建議：** 當您在搜尋方塊中輸入人員的名稱時，包含行事曆邀請的最相關電子郵件訊息會包括在您的搜尋建議中。

- **搜尋時取得相關的檔案建議：** 當您在 [搜尋方塊] 中輸入時，與搜尋相關的最相關檔案將會包含在您的建議中。

- **使用內建翻譯工具打破語言障礙：** 不再需要翻譯的增益集！ 您現在可以在 Outlook 中使用 Intelligent Translator。 當您收到另一種語言的郵件時，郵件上會顯示提示，詢問您是否希望 Outlook 將它翻譯為您的預設語言。
您也可以按一下滑鼠右鍵以翻譯特定的文字、片語或整個郵件。 [深入了解](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- **共用至 Teams：** 將 Outlook 的郵件與 Teams 中的某個人員或頻道共用。

- **Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages. [Learn more](https://support.office.com/article/4010d238-bb25-45e9-89f6-8f9b54fcc0fc)

- **Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC, GCC-H and DoD environments. [Learn more](/microsoft-365/compliance/sensitivity-labels)

- **建立 Outlook.com 帳戶的連結：** 將帳戶新增至 Outlook 時，視窗中會顯示建立新的 outlook.com 帳戶的連結。

- **每個線上會議** 更新行事曆設定，使您建立的每個會議都預設為 Teams 會議，這樣您就不必再記得按一下 [Teams 會議] 選項。

- **Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the DoD environments. [Learn more](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a>PowerPoint

- **SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps. [Learn more](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br />在[部落格文章](https://insider.office.com/en-us/blog/svg-content-office-third-party-apps)中查看詳細資料

- **使用透明背景建立 GIF：** 當匯出成動畫 GIF 時，您可以使用新選項讓背景變透明。<br />在[部落格文章](https://insider.office.com/en-us/blog/export-animated-gifs-transparent-backgrounds)中查看詳細資料

- **協助保護您的資料免受惡意檔案的侵害：**[應用程式防護] 可讓您在獨立的容器中讀取、列印和儲存 Office 檔案，協助保護您免受惡意程式碼的侵害。

- **匯出某範圍的動畫 GIF：** 匯出成動畫 GIF 時，選取某範圍的投影片

- **要求使用者套用敏感度標籤：** 當使用者的組織原則要求時，會提示使用者套用敏感度標籤。

- **Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC, GCC-H and DoD environments. [Learn more](/microsoft-365/compliance/sensitivity-labels)

- **Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the DoD environments. [Learn more](/microsoft-365/compliance/sensitivity-labels)

### <a name="word"></a>Word

- **Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere. [Learn more](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps. [Learn more](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **使用動畫 GIF 分享您的故事：** Office 編輯器現已支援動畫 GIF，讓您的文件更加時髦

- **Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container. [Learn more](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

- **使用語音草擬文件：** 使用新的聽寫工具列、語音命令、自動標點符號等功能來草擬文件。

- **要求使用者套用敏感度標籤：** 當使用者的組織原則要求時，會提示使用者套用敏感度標籤。

- **Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC, GCC-H and DoD environments. [Learn more](/microsoft-365/compliance/sensitivity-labels)

- **Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the DoD environments. [Learn more](/microsoft-365/compliance/sensitivity-labels)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正嘗試使用來自非 Office 應用程式的 DAO API 時，會停止回應並顯示「作業系統目前未配置成執行此應用程式」的問題。


- 我們已修正會導致放置查詢設計或系統關聯性視窗的資料表，會出現在與將其放置位置不同的問題。


- 我們已修正關閉時可能導致 Access 無法正常終止，而可能導致資料庫鎖定的問題。


- 我們已修正外部應用程式會要求協助工具介面的問題。 它會防止應用程式在釋出參考之前意外關閉。


- 我們已修正執行 SQL Server 傳遞查詢時，可能會導致「無效的游標狀態」錯誤的問題。


- 修正可能導致使用 Access 資料庫引擎 ODBC API 的應用程式意外關閉的問題。


- 修正可能導致使用 Access 資料庫引擎 OLEDB API 的應用程式搭配的資料庫包含 SharePoint 清單連結時，會意外關閉的問題。


- 我們已修正現在會啟用 Outlook 增益集事件的問題。


- 我們已修正錯誤訊息中包含特殊字元的問題。


- In certain customer configurations, it has been discovered that document exports to PDF or XPS formats from Office may stop responding due to recent updates. This update fixes these regressions and reenables export to these formats.


### <a name="excel"></a>Excel

- 我們已修正某些使用者無法在受密碼保護的檔案上開啟進入編輯模式的問題。


- 修正復原主要版本組建可能會導致應用程式在開啟檔案時意外終止的問題。


- 我們已修正某些語言中的 [檔案] 索引標籤文字遭截斷的問題。


- 修正 Excel 某些自動化增益集無法載入的問題。


- 我們已修正如果千位和小數分隔符號使用相同符號，圖表座標軸值無法變更的問題。


- 我們已修正分析工具箱增益集沒有回應的問題。


- 修正流量分析工具箱增益集對某些使用者無法運作的問題。


- 修正問題，讓名稱管理員可以在具有大量隱藏名稱的書籍上開啟。


- 我們已修正部分檔案有時無法在受保護的檢視中開啟的問題。


- 我們已修正一個問題，在開啟 CSV 檔案時，將可識別當地語系化的函數名稱。


- 修正從包含 XML Map 的活頁簿中另存為 XML 資料 (.xml) 的問題。


- 我們已修正啟用舊版增益集時，會開啟空白的重複視窗的問題。


- 修正分析工具箱增益集無法與特定自動化安全性設定搭配使用的問題。


- 我們已修正從 PowerPivot 視窗內連接到資料來源無法運作的問題。


- 修正如果 Application.DisplayAlerts 設定為 True，就無法從 VBA 開啟受 DRM 保護的活頁簿的問題。


- 我們已修正可能造成某些連結 Dynamics 資料表停止回應的問題。


- 修正連結至或從 Dynamics 資料表匯入時，並非所有的資料行都會出現的問題。


- In certain customer configurations, it has been discovered that document exports to PDF or XPS formats from Office may stop responding due to recent updates. This update fixes these regressions and reenables export to these formats.


- 修正繪製影像時 Office 應用程式沒有回應的問題。


- 我們已修正同時有多個 Office 應用程式執行時，會導致 Office 應用程式停止回應的問題。  這也解決了由於事件而在整個系統中發生的其他穩定性問題。


### <a name="onenote"></a>OneNote

- 已將建立快速筆記的快速鍵更新為 Win + Alt + N。


### <a name="outlook"></a>Outlook

- 我們已修正與 Outlook 郵件或行事曆檢視互動時，可能會導致意外關閉的問題。


- 我們已修正會導致使用者在關閉已回覆或轉寄的郵件時，遇到未預期的屬性變更提示的問題。


- 我們已修正在載入收集診斷資料時，導致某些使用者遇到意外關閉的問題。


- 我們已修正在從 PST 重新傳送郵件時，導致由 [重新傳送此郵件] 選項所產生之訊息的修改會在傳送時遺失的問題。


- 我們已修正會導致在 SendFromAliasEnabled 設定為 True 的組織中，由不同使用者重新傳送的電子郵件會顯示為由原始寄件者傳送的問題。


- 我們已修正會導致某些使用者在同步處理資料夾階層變更時遇到 Outlook 意外關閉的問題。


- 我們已修正啟用 MAPI 的應用程式在具有 ARM 處理器的電腦上使用 Outlook 元件的問題。 此問題可能導致搜尋失敗，或因為背景應用程式重複重新啟動而造成電腦上額外的負載。


- 我們已修正從 Windows 檔案總管使用 [傳送至] -> [郵件收件者] 後，會使得 Outlook 無法啟動的問題。


- 我們已修正會導致「縮短會議」功能的部分指示，在透過螢幕閱讀程式技術時會停用的問題。


- 我們已修正會導致使用者在新增行事曆時，錯誤地看到「這可能需要一些時間」訊息的問題。


- 我們已修正會導致代理人在新增的行事曆上所建立的會議中顯示為召集人的問題。  處於此狀態的會議不會出現在主體的行事曆上。


- 我們已修正會導致某些使用者在功能窗格中看到主要和次要行事曆位置交換的問題。


- 我們已修正會導致 ARM64 裝置上發生效能問題的問題。


- 我們已修正會導致會議室尋找工具無法載入的問題。


- 我們已修正會導致使用者在將電子郵件草稿儲存至磁碟時，看到 HTML 格式設定遺失的問題。


- 我們已修正會導致某些使用者的翻譯選項遭到停用的問題。  遇到此問題的客戶在瀏覽至 [檔案] -> [選項] -> [語言] 時，會看見其翻譯選項已停用。 有鑑於此，他們可能無法變更其偏好的翻譯語言和其他翻譯相關設定。


- 我們已修正會導致使用者能夠下載受保護附件的問題。


- 我們已修正在從封存區移除資料夾時，會導致使用者遇到意外關閉的問題。


- 我們已修正會導致某些使用者在執行搜尋時遇到意外關閉的問題。


- 我們已修正會導致某些使用者在載入個人卡片時遇到意外關閉的問題。


- 我們已修正導致使用者在從電子郵件收件者的右鍵操作功能表選取 [開啟 Outlook 內容] 時出現錯誤的問題。


- 我們已修正會導致 Outlook 中的人員選擇器針對擁有永久授權的使用者向上展開，而不是向下展開的問題。


- 我們已修正會導致使用者在搜尋時，遇到處里程序意外終止的問題。


- 我們已修正與搜尋相關的意外關閉問題。


- 我們已修正會導致某些使用者在擷取服務提供的搜尋建議時遇到意外關閉的問題。


- 我們已修正使用 Outlook 撰寫電子郵件時，應用程式會意外關閉的問題。


- 我們已修正 Outlook 開機後，應用程式不久後停止回應的問題。


- 我們已修正帳戶的 UPN/SMTP 名稱變更之後，電子郵件簽名會遺失的問題。


- 我們已修正當設定檔中出現未完整設定的帳戶時，造成雲端設定使用者遇到意外關閉的問題。


- 修正僅對簽章內容的變更不會在雲端式設定中更新的問題。


- 我們已修正會導致使用者看到簽名意外消失的問題。


- 我們已修正可能造成使用者看到正在撰寫的郵件失去 UI 焦點的問題。


- 我們已修正會導致部分使用者無法存取與次要郵件帳戶相關聯簽章的問題。


- 我們已修正會導致 Outlook 覆寫 OWA 中已設定的焦點收件匣喜好設定的問題。


- 我們已修正會導致漫遊設定的使用者遇到沒有回應的問題。


- 我們已修正會導致雲端設定在發生衝突時，漫遊設定會失敗的問題。


- 我們已修正會導致意見回應選項無法向 Office Perpetual 2021 預覽使用者顯示的問題。


- 我們已修正會導致意見回應選項對 Office Perpetual 2021 預覽使用者停用的問題。


- 我們已進行一項變更，可讓使用者透過我們新的意見反應系統提交意見反應。


- 我們已修正在代表另一個使用者進行傳送，並且針對非全域通訊清單的通訊錄進行解析時，造成名稱解析失敗的問題。


- 我們已修正會導致使用者能夠下載受保護的語音信箱檔案的問題。


- 已修正導致使用者能夠下載受保護的語音信箱訊息的問題。


- 已修正以 ICAL 轉送一些大型或持續很久的週期性會議時所發生的錯誤。


- 我們已修正在 Outlook 中建立會議時且 Exchange 系統管理員未設定選項時，預設出現有關縮短會議之非預期資訊型通知提示的問題。


- 已修正會議項目取消表單會出現，而不是預期的編輯表單的問題。


- 我們已修正導致應用程式在使用 Outlook 時停止回應的問題。


- 我們已修正導致共用日曆改進功能的使用者在 Outlook 重新開機之前，無法顯示新加入的共用日曆的問題。


- 我們已修正當會議開始與會議結束在不同的日期時，導致使用者在結束會議時間下拉式清單中看到重複時間項目的問題。


- 我們已修正使用有多個帳戶的設定檔將 Outlook 啟動後，會導致網路活動短暫增加的問題。


- 我們已修正會導致已刪除的會議邀請會向某些使用者間歇性重複顯示的問題。


- 我們已修正啟用 [共用行事曆改進] 選項後，導致 SMTP 位址在多帳戶設定檔中使用者的主要行事曆旁無法顯示的問題。


- 我們已修正導致使用者在透過滑鼠右鍵操作功能表回應會議要求時，看到建立重複的行事曆項目的問題。


- 我們已修正會導致 [共用行事曆改善] 選項的使用者 (且擁有多個共用行事曆) 遇到一些效能問題的問題。


- 我們已修正導致某些使用行事曆共用改進功能的使用者在功能窗格中與他們的行事曆互動時發生的問題。


- 我們已修正會導致位置欄位中的連結無法點按的問題。


- 修正繪製影像時 Office 應用程式沒有回應的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正復原主要版本組建可能會導致應用程式在開啟檔案時意外終止的問題。


- 我們已修正使用者因為阻礙性的 PowerPoint 特定對話方塊，而無法將憑證輸入 Windows 安全性對話方塊以開啟檔案的問題。


- 修正少數使用者無法使用 [重複使用投影片] 選項的問題。


- In certain customer configurations, it has been discovered that document exports to PDF or XPS formats from Office may stop responding due to recent updates. This update fixes these regressions and reenables export to these formats.


- 修正繪製影像時 Office 應用程式沒有回應的問題。


- 我們已修正 Word 存檔時，所花時間超過預期的問題。


### <a name="project"></a>Project

- 修正關閉期間應用程式變得沒有回應的問題。


- 修正使用者無法從資源集區移除專案的問題。


- 修正手動排程工作上的指派可能會移至不正確日期的問題。


### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新

- 我們已修正在交談視窗中，影片共用預覽會意外關閉的問題。


### <a name="visio"></a>Visio

- 修正關閉期間應用程式變得沒有回應的問題。


- 我們已修正一個問題，使得使用者現在能夠順暢地存取檔案，而不會遇到任何意外關閉。


- 我們已修正具有來賓存取的 SPO/ODB 連結無法運作的問題。


### <a name="word"></a>Word

- 已修正 Word 畫布旁的註解卡片大小不正確的問題。


- 修正復原主要版本組建可能會導致應用程式在開啟檔案時意外終止的問題。


- 修正共同撰寫文件時，若註解順序變更，則不會清除作用中草稿的問題。


- 修正顯示新版視覺效果的對話方塊包含螢幕助讀程式無法讀取的文字的問題。


- 修正使用 [此裝置] 選項編輯與新增圖片相關連絡人的問題。


- In certain customer configurations, it has been discovered that document exports to PDF or XPS formats from Office may stop responding due to recent updates. This update fixes these regressions and reenables export to these formats.


- 修正由於使用者登出或重新啟動電腦而關閉電腦時，可能導致 Word 意外關閉的問題。


- 修正繪製影像時 Office 應用程式沒有回應的問題。


- 我們已修正插入線上影片按鈕遭到停用的問題。


- 修正一個問題，以將提供文字預測情況最佳化。


- 我們已修正在閱讀模式中使用深色模式主題時，某些選取的文字無法顯示的問題。


- 我們已修正預覽列印將意外關閉的問題。


- 修正拼字及文法檢查的畫布關聯式卡片會顯示圖示按鈕但沒有工具提示的問題。


- 我們已修正您無法在 [繼續] 區段中關閉任何編輯器選項的問題。


- 我們已修正 [編輯器] 窗格無法開啟的問題。


- 修正將文件儲存到本機時顯示「自動儲存已停用」的問題。


- 我們已修正對檔案的自動儲存圖說文字進行更新會在本機儲存的問題。


- 我們已修正 styleref 欄位可能會顯示截斷結果的問題。


- 我們已修正非預設功能區設定可能導致樣式庫無法運作的問題。


- 修正在受密碼保護的 DOCX 檔案上維護引文的「目前清單」的問題。


- 已修正在受密碼保護的 .docx 檔案上保存引文的問題。


- 我們已修正儲存檔案時，Word 耗費較預期更多時間的問題。


- Office 應用程式現在支援 [OpenDocument format 1.3](https://insider.office.com/en-us/blog/office-apps-now-support-opendocument-format-odf-1-3)。


- 我們已修正編輯 OLE 物件時需要變更的問題。


- 我們已修正列印中未載入預覽列印的問題。


- 我們已修正同時有多個 Office 應用程式執行時，會導致 Office 應用程式停止回應的問題。  這也解決了由於事件而在整個系統中發生的其他穩定性問題。


- 修正插入線上圖片時，與應用程式未回應相關的問題。


- 我們已修正在隱藏段落結尾輸入可能會導致應用程式停止回應的問題。


- 我們已修正 Wordmail 中當連結的第 2084 個字元是逸出字元時，某人無法傳送此項目的問題。



### <a name="office-suite"></a>Office 套件

- 修正使用者無法編輯儲存在內部部署 SharePoint 伺服器中的特定文件的問題。


- 修正開啟 SyncBacked 檔案時的效能迴歸問題。


- 修正重新開啟特定檔案時意外關閉的問題。


- 修正會導致雲端文件無法開啟的問題。


- 修正 Outlook 中的自訂 VSTO 控制項在開啟並在多個視窗和檢視之間切換後停止運作的問題。


- 修正當地語系化問題，其中的 en-gb、fr-ca 和 es-mx 現在將符合其各自的上層版本。


- 我們已修正在 DirectX 裝置遺失和復原情況期間與不穩定相關的問題。


- 我們已修正與使用觸控或觸控板在 PPT 投影片的縮圖檢視中捲動相關的問題。


- 我們已修正使用某些 Web 增益集後，某些文件無法載入的問題。


- 已修正 OMEX 與 ExCatalog 之間無法再共用設定的問題，例如建立了新 webextension 檔案之後，Web 增益集設定會更新至 webextension.xml。 只有在以原始方法部署該增益集，或將新的解決方案參考比較關閉時，才能存取前一個。


- 我們已修正會導致樞紐分析表中的日期欄位分組錯誤的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-august-10"></a>版本 2102: 8 月 10 日
*版本 2102 (組建 13801.20864)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正共同作者時，變更可能不會儲存於罕見情況的問題。


- 我們已修正在儲存至 SPO 文件庫時，儲存的活頁簿會顯示在最近清單頂端的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正使用者因為阻礙性的 PowerPoint 特定對話方塊，而無法將憑證輸入 Windows 安全性對話方塊以開啟檔案的問題。


- 我們已修正問題，以確保使用工具列的 [重試儲存] 按鈕儲存的檔案會新增至 [最近的清單]。


### <a name="word"></a>Word

- 我們已修正 Word 在校對期間可能無法回應的問題。


- 我們已修正在 Word 中更新欄位時的錯誤。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-july-13"></a>版本 2102：7 月 13 日
*版本 2102 (組建 13801.20808)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 我們已修正當使用者選取雲端設定選項時，無法啟用的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正在某些情況下，PowerPoint 簡報內嵌的 Excel 物件未如預期顯示的問題。


### <a name="office-suite"></a>Office 套件

- 我們已修正使用者從 Office 應用程式中的 Me 控制項切換 Active Directory 身分時，切換資料案例的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-june-08"></a>版本 2102：6 月 8 日
*版本 2102 (組建 13801.20738)*

安全性更新列於[此處](microsoft365-apps-security-updates.md)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 我們已修正會移除在柏拉圖上顯示的額外邊框間距，並減少可用圖表空間的問題。


- 已修正部分使用者在 Excel 增益集清單中顯示額外項目的問題。


- 我們已修正造成部分使用者的狀態列無法顯示 [準備就緒] 狀態的問題。


- 我們已透過改進重新整理 Power BI 數資料型且使用者無權存取某些資料類型時顯示的錯誤訊息來解決問題。


- 我們已透過將可在屬性自動完成下拉清單中顯示的屬性數量增加到 256 個屬性，以解決問題。


### <a name="outlook"></a>Outlook

- 我們已修正當內部和外部 EWS 端點不同且內部端點呼叫失敗時，導致使用者發生連線錯誤的問題。


- 我們已修正重新傳送電子郵件時，導致寄件者地址顯示為 LegacyExchangeDN 的問題。


- 已修正使用者和系統管理員無法開啟雲端設定的問題。


- 我們已修正導致 ZeroConfigExchange 在已使用混合式 Azure AD 而聯結的電腦 (已連線到外部網路) 上無法正常運作的問題。


- 我們已修正導致自訂網域使用者在將連結貼到電子郵件時，看到權限警告訊息的問題。
</br>

- 我們已新增一個登錄機碼，以停用新會議室尋找工具體驗 (與 Outlook 網頁版相同的體驗)，並啟用具有建議的時間的傳統會議室尋找工具。

  登錄機碼：
  
  > HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
  > REG_DWORD “ShowLegacyRoomFinder”</br></br>
  > 0 (預設值) - 當使用者按一下 [會議室尋找工具] 按鈕以搜尋可用的會議室時，Outlook 會使用新會議室尋找工具 OWA 提供的體驗  </br>
  > 1 - Outlook 使用舊版會議室尋找工具 UI 來搜尋可用的會議室</br>


### <a name="powerpoint"></a>PowerPoint

- 我們已修正儲存區更新為版本 1.0.0.2 以支援集中部署的問題。 使用者必須更新 PowerPoint 中的版本資訊，才能存取儲存區。


### <a name="project"></a>Project

- 修正當您建立的自訂欄位公式使用 ProjectDate */ProjectDur* 函數，且若第二個參數是 Date()、Now() 或 Time() 日期和時間函數時，會導致 #ERROR 結果的問題。


- 已修正資源資料庫沒有回應且無法開啟的問題。


### <a name="visio"></a>Visio

- 我們已修正有關在圖形搜尋中輸入搜尋關鍵字時，遺失結果的問題。


### <a name="word"></a>Word

- 已修正插入線上圖片時，應用程式未回應的問題。


- 我們已修正在貼上的文字中，複製和貼上的樣式可能會不同的問題。


- 我們已修正會移除內容控制項允許的字串大小限制的問題。


- 我們已修正與編輯 OLE 物件相關的問題。


### <a name="office-suite"></a>Office 套件

- 已修正開啟預留位置檔案時的問題。 Office 無回應，無法開啟 sync-backed 檔案。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-may-11"></a>版本 2102：5 月 11 日
*版本 2102 (組建 13801.20638)*

安全性更新清單列於此處：[Microsoft Office 安全性更新的版本資訊](microsoft365-apps-security-updates.md)。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正 Excel 的部分自動化增益集無法載入的問題。


- 我們已修正在使用增益集時，會導致某些語言的日期格式顯示不正確的問題。


- 我們已修正會導致無法以公式形式貼上到受保護工作表的問題。


### <a name="outlook"></a>Outlook

- 這可讓使用者設定 Outlook 以將線上會議新增至他們建立的每一個會議。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正與連結圖片相關的問題。


### <a name="word"></a>Word

- 修正 Wordmail 中當連結的第 2084 個字元是逸出字元時，某人無法傳送項目的問題。


### <a name="office-suite"></a>Office 套件

- 修正即使 GPO 已設為停用要求，Office 範本也會開啟的問題。


- 修正會導致 Word 在列印長篇文件時意外關閉的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-april-13"></a>版本 2102：4 月 13 日
*版本 2102 (組建 13801.20506)*

安全性更新清單列於此處：[Microsoft Office 安全性更新的版本資訊](microsoft365-apps-security-updates.md)。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 修正在某些情況下，執行 SQL Server 傳遞查詢時，可能會導致錯誤訊息指出「無效的 Cursor 狀態」的問題。


### <a name="excel"></a>Excel

- 修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。


- 我們已修正將資料列新增至另一個工作表上的表格後，可能會非預期地對儲存格套用資料驗證的問題。


- 我們已修正 DialogSheets show 函數在 32 位元版本的 Excel 上無法運作的問題


### <a name="outlook"></a>Outlook

- 我們已修正會導致 Outlook 在閒置時當機的問題。


- 我們已修正會導致雲端設定功能的使用者在新裝置上設定 Outlook 之後，會看到自訂設定遭到預設設定覆寫的問題。


- 我們已修正會導致使用者看到較預期更多的簽章的問題。


### <a name="powerpoint"></a>PowerPoint

- 修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。


### <a name="word"></a>Word

- 修正 Office 功能區中已停用的命令，在深灰色 Office 佈景主題中只會使圖示而非文字呈現灰色的錯誤。


- 我們已修正有關複製和貼上的問題。


- 我們已修正在隱藏段落結尾輸入可能會導致應用程式懸置的問題。


### <a name="office-suite"></a>Office 套件

- 修正使用者在開啟先前開啟的檔案具有未儲存的編輯但現在檔案已遭到刪除時，無法儲存檔案的問題。 修正之後，使用者將會收到一則友善的訊息，通知他們已刪除該檔案，因此使用者可以選擇捨棄變更，或將檔案另存為新檔。


- 修正離線開啟 SyncBacked 檔案，然後於儲存檔案之前，在應用程式中重新命名檔案時重新命名失敗的問題。


- 修正針對使用者停用 GCC 聽寫的問題


- 修正有時可能會導致 Outlook 中的文字變得透明，因而無法辨認的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2102-march-09"></a>版本 2102：3 月 9 日
*版本 2102 (組建 13801.20294)*

安全性更新清單列於此處：[Microsoft Office 安全性更新的版本資訊](microsoft365-apps-security-updates.md)。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。<br />在[部落格文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看詳細資料

- **建立 PDF 連線：** 連線至、匯入、重新整理 PDF 中的資料。 [深入了解](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- **建立變數以在公式中使用：** 使用 LET 函數改善效能、可讀性及可組合性。 此函數可讓您在新的或現有的公式中建立命名變數。 [深入了解](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />在[部落格文章](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)中查看詳細資料

- **儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。  我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。 [深入了解](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

- **使用資料類型從 Power BI 取得組織資料：** 現在，來自 Power BI 的 Excel 資料類型將推出給使用 Office 365 / Microsoft 365 和 Power BI Pro 服務方案的組織測試人員使用。 取得您所需的資訊，輕鬆地重新整理，對許多日常工作流程而言至關重要。 我們允許您透過 Excel 中的資料類型從 Power BI 存取公司或組織資訊，從而擴充您在試算表中引入連結資訊的能力。 [深入了解](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />在[部落格文章](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)中查看詳細資料

- **Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office. No conversion required.<br />在[部落格文章](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)中查看詳細資料

- **在 Excel 中製作精美的 Visio 圖表：** 在工作表中從資料建立資料驅動的圖表，如流程圖或組織結構圖。 [深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


- **與 Office 的 XLM 巨集的 AMSI 整合：** AMSI 是 Windows 10 上可用的開放式介面，可供應用程式在執行階段要求由已安裝的防毒軟體或安全性解決方案同步掃描記憶體緩衝區。 偵測到惡意活動時，Excel 會通知使用者，並關閉該應用程式工作階段以避免任何進一步損毀。 這麼做可阻止在其軌跡中的攻擊，同時保護裝置和使用者。 在[部落格文章](https://www.microsoft.com/security/blog/2021/03/03/xlm-amsi-new-runtime-defense-against-excel-4-0-macro-malware/)中查看詳細資料。

- **在 Excel 中建立來自 Power BI 資料的樞紐分析表：** 您可以在 Excel 中建立樞紐分析表，只要按幾下滑鼠，就能連線到儲存在 Power BI 的樞紐分析表。  如此一來，您就能獲得樞紐分析表和 Power BI 的最佳效果。 使用安全 Power BI 資料集的樞紐分析表以計算、摘要及分析資料。 [深入了解](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a>Outlook

- **協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站。

- **Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows. [Learn more](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- **在 Outlook 中使用 [快速投票] 建立投票：** 輕鬆建立投票，收集投票，並檢視電子郵件中的結果 [深入了解](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office. No conversion required.<br />在[部落格文章](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)中查看詳細資料

- **新的會議室尋找工具：** 依不同功能搜尋會議室。

- **以您說話的方式搜尋：** 使用日常語言如「上週獸醫的預約」來篩選和縮小搜尋範圍。

- **快速重新開啟上一個 Outlook 工作階段的項目：** 我們新增了一個選項，可快速重新開啟上一個 Outlook 工作階段的項目。<br />在[部落格文章](https://insider.office.com/en-us/blog/automatically-restore-windows-in-outlook)中查看詳細資料

### <a name="powerpoint"></a>PowerPoint

- **[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。<br />在[部落格文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看詳細資料

- **儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。  我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。 [深入了解](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

- **Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office. No conversion required.<br />在[部落格文章](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)中查看詳細資料

### <a name="visio"></a>Visio

- **New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams. [Learn more](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a>Word

- **[筆跡工具箱] 中的 [套索工具] 和 [橡皮擦]:** 使用繪圖工具時，[筆跡工具箱] 現在提供 [套索工具] 和 [橡皮擦] 功能。<br />在[部落格文章](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)中查看詳細資料

- **儲存至釘選資料夾：** 釘選資料夾可讓您更輕鬆地儲存 Office 檔案。  我們收到了意見反應，使用者想更進一步控制儲存新檔案時可用的資料夾。 我們很高興地能為您提供新功能：在 [儲存] 對話方塊中釘選您的資料夾。 這項新功能可讓您更輕鬆地儲存 Word、Excel 和 PowerPoint 檔案。 [深入了解](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />在[部落格文章](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)中查看詳細資料

- **Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office. No conversion required.<br />在[部落格文章](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)中查看詳細資料

### <a name="office-suite"></a>Office 套件

- **索引標籤式窗格：** 現在您可以使用應用程式右側的索引標籤 UI，在多個窗格之間切換。 只有當您開啟 2 個以上的窗格時，該 UI 才會顯示。<br />在[部落格文章](https://blog-insider.office.com/2020/02/20/improved-pane-management/)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 我們已修正從非 Office 應用程式使用 DAO 時，會導致應用程式意外關閉的問題。


- 我們已修正使用者收到「資料指標狀態無效」錯誤對話方塊的問題。


### <a name="excel"></a>Excel

- 我們已修正會破壞一些舊版 Excel 4.0 和 Excel 5.0 巨集以及對 dialogsheets.show 的一些 VBA 呼叫的問題。


- 修正使用樞紐分析表的 [值的顯示方式] 功能表時，Excel 可能會意外關閉的問題。


- 我們已修正會導致使用者無法將 Excel 活頁簿匯出至 PDF 的問題。


- 我們已修正使用 [貼上連結圖片] 選項時，會導致影像小於預期的問題。


- 我們已修正在儲存為 .xls 或 .xlt 格式時，會導致某些樞紐分析表格式損壞活頁簿的問題。


- 修正在開啟含有 Excel 4.0 巨集的 Excel 增益集檔案時，Excel 可能會將巨集停用而不提示的問題。


- 修正以下問題：Excel 錯誤地顯示檔案新版本可用的訊息列，並強制使用者將變更儲存到活頁簿的副本中或捨棄變更。


- 修正當某些使用者在共同撰寫時會不正確地在訊息列中看到通知他們檔案有新版本的問題。


- 修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題。


- 我們已修正選取圖表的資料數列之後，Excel 會停止回應的問題。


- 此變更解決了在方程式中正確顯示字型的問題。


### <a name="outlook"></a>Outlook

- 我們已修正會導致使用者無法將 [編輯器] 權限授與代理人的問題。


- 我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 異常關閉的問題。


- 我們已修正導致在其設定檔中具有大型階層的共用或委派信箱的使用者遇到停止回應的問題。


- 已解決當主旨行空白時，會導致傳送的自動產生電子郵件含有空白內文的問題。


- 解決了導致某些使用者觀察到在離線狀態下意外啟動 Outlook 的問題。


- 已解決在開啟另一個信箱中的共用資料夾時，會導致代理人看到間歇性失敗的問題。


- 我們已修正會導致使用者在選取搜尋結果時遇到非預期終止的問題。


- 我們已修正會導致某些客戶在載入行事曆時遇到懸置的問題。


- 我們已修正會導致某些會議的原始出席者在另一個出席者轉寄會議時收到取消通知的問題。


- 我們已修正會導致使用者在建立新群組後看到重複的行事曆群組的問題。


- 我們已修正會導致共用行事曆改良功能的使用者無法將行事曆的色彩設定為黃色或褐色的問題。


- 我們已修正會導致使用者在 Outlook 重新啟動之前，在功能窗格中看不到新增的行事曆顯示的問題。


- 已解決在搜尋未快取的共用行事曆時，會導致搜尋未傳回結果的問題。


- 我們已修正會導致某些使用者在關閉訊息視窗時遇到應用程式關閉的問題。


- 修正在傳送工作的狀態報告時，造成 [收件者] 欄位為空白的問題。


- 我們已修正會導致 MailItem.BeforeAttachmentAdd 事件中斷的問題。


- 我們已修正會導致某些使用者在特定搜尋案例中遇到 Outlook 未預期關閉的問題。


- 我們已修正使用者在 Outlook 中進行搜尋時，有時候會導致應用程式未預期關閉的問題。


- 我們已修正會導致雲端設定使用者在更新設定時遇到懸置的問題。


- 我們已修正在提示使用者儲存已編輯的簽章後，會導致該動作無法執行的問題。


- 我們已修正會導致某些使用者未設定一或多個簽章時，在 [簽名] 下拉式清單中看不到任何簽名的問題。


- 我們已修正會導致預設不會為使用者開啟雲端設定的問題。


- 我們已修正會導致對使用者簽章的變更無法儲存的問題。


- 我們已修正會導致 Outlook 為已啟用雲端設定的使用者建立第二個空白簽名的問題。


- 我們已修正會導致在 OWA 中顯示正確的預設簽章時發生問題的問題。


- 我們已修正會導致使用者看到包含 Unicode 內容的簽章損毀的問題。


- 我們已修正會導致內嵌翻譯的使用者無法提交意見反應的問題。


- 我們已修正當回覆或轉寄郵件時，會導致中文郵件標題無法閱讀的問題。


- 我們已修正在儲存為 OFT 檔案時，會導致中文字元變更為問號的問題。


- 我們新增了一個 RegKey，可讓客戶停用 IDataObject 操作 (例如，拖曳拖放、剪貼簿) 中附件的 FileTime 包含。  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments。  REG_DWORD IncludeFileTimesInDataObject。  0 = 不包含 filetimes。  1 = (預設) 包含 filetimes。


- 修正當回覆含有「Azure 資訊保護」保護標籤的郵件時，導致內嵌影像消失的問題。


- 我們已修正會導致加密圖示無法對使用僅加密選項傳送的電子郵件顯示的問題。


- 我們已修正會導致郵件在使用者取消選取該選項之後，以數位簽章方式傳送的問題。


### <a name="powerpoint"></a>PowerPoint

- 已修正如果文件儲存失敗，可能會導致應用程式非預期關閉的問題。


- 修正將方程式從 Word 複製/貼上到 PowerPoint 時的問題。


- 此變更解決對某些幾何圖形套用 [合併圖案] 作業時路徑填充的問題。


- 此變更解決了在方程式中正確顯示字型的問題。


- 此變更解決了處理載入影片期間可能發生錯誤的問題。


- 我們已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生非預期關閉的 VBA 問題。


- 我們已修正在 QAT 中新增的字型大小命令在更新時自動完成到最接近的已定義字型大小的問題。


- 我們已修正在複製含有新錄製音訊的投影片後，儲存檔案時發生錯誤的問題。


- 我們已修正 Forms 內容增益集在插入之後不會呈現，除非使用者按一下另一張投影片讓它顯示才會呈現的問題。


- 我們已修正在受保護的檢視中開啟 PowerPoint 檔案時，會停用 IRM 保護的問題。


- 修正會導致共同撰寫在包含大量特定資料物件類型 (E2o) 的檔案上變慢的問題。


- 修正以解決在合併錯誤期間使用 IRM/受保護文件的問題。


- 這是此問題的修正：當有增益集在接聽 PresentationBeforeClose 事件並隨著事件處理常式檢查 Presentation.Saved 內容時若關閉文件，儲存提示會以迴圈顯示。


- 已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。


- 解決在某些情況下，選取設計構想會移除簡報的資料分類標籤的問題。


### <a name="project"></a>Project

- 修正當您將專案從 PWA 儲存到本機 mpp 檔案時，ProjectBeforeTaskChangeEvent 會對實際上未由使用者變更的資料觸發的問題。


- 修正如果工作表單類型檢視內的延隔時間變更，ProjectBeforeTaskChange 事件中的 NewVal 不會有正確值的問題。


- 修正若您的事件程式碼執行中，並嘗試透過工作 [表單檢視] 進行變更，按一下 [確定] 按鈕可能不會提交變更的問題。


- 修正 Project 在開啟以特定方式指定資源分佈的檔案時可能會意外終止的問題。


- 已修正如果特定專案在負載的特定部分發生問題，可能會開啟特定專案的問題。


- 修正在 [團隊規劃] 檢視中工作沒有顯示邊框的問題。


- 修正在 [團隊規劃] 檢視中拖放工作不起作用的問題。


- 修正將成本資源指派給里程碑工作時，比較基準成本沒有正確彙總的問題。


### <a name="visio"></a>Visio

- 修正使用者將可在自訂 Visio 樣板和內建範本中使用適用於 Office 365 的 Visio 連接器建立直線的問題。


### <a name="word"></a>Word

- 修正如果文件儲存失敗，可能會導致應用程式非預期關閉的問題。


- 修正將方程式從 Word 複製/貼上到 PowerPoint 時的問題。


- 此變更可解決編輯文件時游標的問題。


- 修正對具有 3D 效果的圖示和 SVG 圖形套用色彩的問題。


- 我們已修正可能會略過段落的朗讀程式問題。


- 我們已修正 RTF 內容控制項的問題。


- 我們已修正 [樣式庫] 對話方塊的問題。


- 我們已修正解決共同撰寫時衝突的問題。


- 我們已修正文件樣式會以範本中的其他樣式取代的問題。


- 修正會影響 Word 的最佳化閘道所暴露的宣告錯誤。


### <a name="office-suite"></a>Office 套件

- 我們已修正在嘗試儲存已從 syncbacked 檔案轉換為僅限伺服器的檔案時，導致失敗的問題。


- 修正在某些情況下，嘗試執行另存新檔會失敗的問題。


- 我們已修正 SaveRequestManagerCam 會導致應用程式關閉，而非傳回錯誤的問題。


- 修正檔案關閉順序，使得所有相互依賴的元件都能正常關閉。


- 修正當來自快取的 URL 與來自 OneDrive 的 URL 不相符時，檔案將被開啟為 NOT SyncBacked 的問題。


- 修正在商務用 Skype 訊息中複製/貼上時，會導致出現對話方塊顯示「貼上您的內容時發生問題」的錯誤。


- 修正將註解中的文字複製/貼上到 Excel 時會發生錯誤的問題。


- 修正在包含數學方程式的文字內使用朗讀程式時可能發生的損毀。


- When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".


- 已修復在某些較舊的版本上安裝較新版的 Office 時，可能會造成功能受損 (例如由於遺失登錄專案而無法使用 Power Query) 的問題。


- 修正 Microsoft 365 端點資料外洩防護無法分類磁碟上 Office 文件的問題。


- 我們已修正 [壓縮圖片] 對話方塊未保留某些使用者設定的問題。


- 修正與媒體控制器事件通知相關的問題。


- 修正與媒體播放程式引擎時間相關的問題。


- 優化的二進位大小。


- Anaheim WebView 目前尚不支援 Windows 資訊保護(WIP)。 有了此修正程式，Office addin 平臺便會回到處於 WIP 啟用環境中的低層級 WebView。 根據客戶的電腦環境，這可以是 Edge Spartan WebView 或 Trident WebView。 兩個低層級 WebViews 皆支援 WIP。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-february-09"></a>版本 2008：2 月 9 日
*版本 2008 (組建 13127.21216)*

安全性更新清單列於此處：[Microsoft Office 安全性更新的版本資訊](microsoft365-apps-security-updates.md)。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正了當開啟具有無效檔案内容 (建立時間、修改時間等) 的 UNC 檔案時，Excel 會意外關閉的問題


- 我們已修正將圖表從 Excel 複製並貼到 Word 或 PowerPoint 時，小數位和千分位分隔符號設定不會執行的問題。


- 我們已修正執行涉及樞紐分析表範圍格式設定的巨集，在每次執行巨集時效能都會變差的問題。


- 我們已修正將工作表複製或移動到另一個活頁簿時，設定格式化的條件規則的問題。


- 我們已修正當應用程式啟動時停用開始頁面，使用者無法將敏感度標籤套用至 Excel 檔案的問題。


- 我們已修正從 OneDrive 同步處理資料夾開啟雲端檔案的問題。


### <a name="outlook"></a>Outlook

- 解決在新增或儲存附件時，會導致 Outlook 停止運作的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正一個問題，即在 QAT 中新增的字型大小命令在更新時，會自動完成到最接近的已定義字型大小。


- 修正使用保留來源格式設定選項複製及貼上投影片時，有時會將此設定意外地複製到新的投影片母片的問題


### <a name="word"></a>Word

- 我們已修正有時開啟 Word 文件可能會顯示錯誤對話方塊的追蹤修訂問題。


- 我們已修正從 OneDrive 同步處理資料夾開啟雲端檔案的問題。


### <a name="office-suite"></a>Office 套件

- 修正無法在 Office 中成功開啟檔案的問題。


- 修正使用複製格式將包含草繪外框的文件套用至連接器可能會損毀的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-january-12"></a>版本 2008：1 月 12 日
*版本 2008 (組建 13127.21064)*

安全性更新清單列於此處：[Microsoft Office 安全性更新的版本資訊](microsoft365-apps-security-updates.md)。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正唯讀書籍在開啟時無法再重新整理樞紐分析表資料的問題。


- 這項變更提供下列問題的修正程式：從 OneDrive 本機同步處理資料夾插入檔案時，Excel 的 [插入物件] 不會顯示正確的圖示。


- 修正客戶在共同撰寫時會錯誤地得到有關文件新版本通知的問題。


- 修正即使用 IME 和覆寫模式將錯誤地推進額外的字元的編輯問題。


- 修復了將即時資料與多執行緒 recalc 功能結合使用時出現的問題。


- 修正當使用特定 Windows 安全性漏洞防護設定(SimExec、CallerCheck) 時，Excel 無法正常啟動或關閉的問題


### <a name="outlook"></a>Outlook

- 我們已修正導致 SmartLinks 在儲存至草稿時格式遺失的問題。


- 我們已修正讓使用者能在覆寫原則時自訂調整文字的問題。


- 我們已修正會導致中文字元在儲存為 OFT 檔案時變更為問號的問題。


### <a name="powerpoint"></a>PowerPoint

- 我們已修正 Slide.Shapes.AddMediaObject2 會對舊版影片格式 (MPG-1、Mpeg-2) 發生意外關閉的 VBA 問題。


- 已修正無法正確開啟部分損壞的 PowerPoint 檔案 (即使在文件修復之後) 的問題。


### <a name="project"></a>Project

- 我們已修正在開啟以特定方式指定資源分佈的檔案時，Project 可能會意外終止的問題。


### <a name="skype"></a>Skype

- 修正使用者的 TLS-DSK 憑證不會在預期時間續訂，而只在有效期剩餘不到 12 小時才續訂的問題。


- 修正當 Office 尚未獲得授權時，商務用 Skype UI 在登入後顯示為空白的問題。


### <a name="office-suite"></a>Office 套件

- 此變更解決了與開啟包含舊圖表之檔案相關的問題。


- 此變更解決了 SVG 回復 Proxy 導致存取衝突的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> 如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|FRDC|測試人員| |16.0.15601.20230|version-2208-october-11|)
[//]: # (|Win32|FRDC|測試人員| |16.0.15601.20148|version-2208-september-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.14931.20660|version-2202-august-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.14931.20604|version-2202-july-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.14931.20588|version-2202-july-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.14931.20494|version-2202-june-14|)
[//]: # (|Win32|FRDC|Insiders| |16.0.14931.20482|version-2202-june-14|)
[//]: # (|Win32|FRDC|測試人員| |16.0.14931.20392|version-2202-may-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.14931.20274|version-2202-april-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.14931.20132|version-2202-march-08|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
