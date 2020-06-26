---
title: 在2020中的半年 Enterprise 通道（預覽）版本的版本資訊
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2020 年 Microsoft 365 Apps 半年通道 (已設定目標) 版本的版本資訊
ms.openlocfilehash: be72a3d95178f0fde5bbe48428abb0895d5afefd
ms.sourcegitcommit: cc48ae789324e085a976c3a7a388353447b10d42
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/12/2020
ms.locfileid: "44724955"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a>在2020中的半年 Enterprise 通道（預覽）版本的版本資訊

這些版本資訊中提供的有關新功能和非安全性更新的資訊，在2020中的 Microsoft 365 應用程式適用于企業、Microsoft 365 應用程式，以及適用于 Project 和 Visio 的桌面應用程式訂閱版本，都包含在的半年 Enterprise 通道（預覽）更新中。

> [!IMPORTANT]
> 我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。 如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。


## <a name="version-2002-june-09"></a>版本2002：6月9日
*版本2002（組建12527.20720）*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正此問題：如果檔路徑過長，外部連結會在重新開啟檔案後停止運作。

- 已修正此問題：使用 Ctrl + Shift + 箭號鍵，在 Excel 視窗透過團隊共用時，Excel 可能會停止回應。

- 修正列印時表單控制項的核取方塊縮放問題。

- 當您使用舊版的「共用活頁簿」模式，嘗試為活頁簿的新工作表列出變更時，就會發生當機。

- 在已篩選清單中插入欄的時間會比預期更長。

- 已修正此問題： @ 符號開始公式會被視為隱含的交運算子。

### <a name="outlook"></a>Outlook

- 啟用透過原小組用戶端直接加入小組會議。

- 解決了 Outlook 無法啟用資料遺失保護原則秘訣的問題。使用者已向其支付服務的使用者，M365 Business Plus 方案。

- 解決問題，造成使用者無法完成 Gmail 的驗證提示時，瀏覽器模擬設定不正確。

- 解決問題，導致伺服器作業系統上的 Outlook 使用者看到錯誤 "防毒程式狀態：無效。 此版本的 Windows 支援防病毒偵測，但未找到任何防毒軟體，但未正確設定反病毒。

### <a name="word"></a>Word

- 我們已修正文件中的文字對齊，在使用 [快速列印] 進行列印之後嘗試進行編輯時變得混亂的問題。

### <a name="office-suite"></a>Office 套件

- 我們解決這項問題的方法是，將 backstage 中的通道名稱更新為2020年1月的新通道名稱。

- 我們已修復此問題，如果裝置受到原則管理，將不會呼叫 DMS 物件 API。

- 已解決此問題：在單一交易中新增及移除應用程式時，未完成移除。

- Office 主應用程式在 windows 中已崩潰，當登錄機碼 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 設定為0時，便會啟用增益集。 這種變更可修正此問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-may-12"></a>版本 2002：5 月 12 日
*版本 2002 (組建 12527.20612)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel

- 開啟含有許多其他活頁簿 (尤其是含有隱藏視窗) 參照的活頁簿時，速度比預期慢。

- 在某些情況下，開啟 CSV 檔案所花費的時間超過預期。

- 在某些情況下，當您切換不同縮放比例的活頁簿時，Excel 可能會當機。

- 已修正 VBA 將值寫入範圍時，速度比預期慢的問題。

- 從有色彩篩選的欄複製的資料有時候無法正確貼上。

- 已修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。

- 在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。

- 已解決在儲存並重新開啟檔案時，圖表軸上的 "Value Crosses At" 屬性發生意外變更的問題。

- 使用 Range.Value 和 Range.Value2 (VBA) 會導致公式以動態陣列的形式輸入。

### <a name="onenote"></a>OneNote

- 對通知進行本地化，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。

- 顯示通知，讓使用者可以了解更多 OneNote 使用者體驗中正在採取的臨時措施的資訊，以改善同步處理和服務穩定性。

- 在 OneNote 2016 中暫時降低版本歷程記錄頁面的數目和同步處理頻率，以改善同步處理與服務穩定性。

- 透過暫時停用 OneNote 2016 中的資源回收筒，來改善同步處理與服務的穩定性。 當使用者嘗試刪除通常會傳送到 [資源回收筒] 的資料時，系統會詢問使用者是否希望保留或永久刪除資料。

- 透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。

- 暫時延遲下載線上筆記本中內嵌的檔案和影像，直到使用者瀏覽至 OneNote 2016 中的頁面，以改善同步處理與服務的穩定性。

- 透過暫時停用 OneNote 2016 中的應用程式內視訊錄製，來改善同步處理與服務的穩定性。 本機筆記本不受這個值的影響。

- 透過暫時將 OneNote 2016 中新嵌入附件的最大允許大小減少為 50MB，來改善同步處理與服務的穩定性。 對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。

### <a name="outlook"></a>Outlook

- 已解決導致資料夾窗格寬度意外變更的問題。

- 解決以下問題：Windows 更新之後，使用者開啟 .msg 和 .oft 檔案時遇到當機。

- 解決會導致使用者在轉寄大型 HTML 郵件時，看到郵件內文截斷的問題。

- 此更新修正在查看或撰寫郵件時，Microsoft Outlook 未顯示目前的敏感度標籤的問題。

- 解決導致使用者無法將電子郵件地址傳送至個人通訊群組清單的問題。

### <a name="powerpoint"></a>PowerPoint

- 已修正以下問題：當開啟的檔案複本具有增強式註解時，為使用者轉送正確的訊息。

### <a name="word"></a>Word

- 解決了 Access 和 Publisher 因所安裝的語言而無法正常啟動的問題。

- 修正受保護無法編輯之文件的比較功能問題。

- 我們已修正將兩份文件合併成一份文件時的問題。

### <a name="office-suite"></a>Office 套件

- 此修正解決了當檔案已在用戶端中進行快取時，Project 應用程式不應封鎖網路。

- 我們已解決內部作業在失敗時擲出例外狀況，而不是記錄和繼續進行的問題。 受影響的使用者將不會再無法收到更新。

- 這項變更可確保草繪大綱可在功能區中正常運作。

- 已修正使用一些特定 proxy 設定時，從內部部署位置開啟檔案時發生的問題。

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。

- 此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。

- 此更新解決了 Microsoft Word 中的一個問題：如果標籤原則套用了頁首或頁尾或浮水印，那麼在套用敏感度標籤時，插入長度超過 255 個字元的文字後續將無法透過變更或刪除標籤來識別和刪除。

- 修正問題，可在 Office 遞交工作階段期間消除當機，並改善使用者體驗中的可靠性。  

- 這個錯誤會更新增強的設定服務 (ECS) url 端點。 呼叫這個較新的端點，可從 ECS 進行提取獲得更高的成功率。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-april-14"></a>版本 2002：4 月 14 日
*版本 2002 (組建 12527.20442)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **輸入會傳回多個值的公式：** 快速輸入公式來傳回多個值，並且值會自動溢出至相鄰的儲存格。 [深入了解](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- **六個功能強大的函數：** 我們新增了六個新的函數，讓您的試算表功能更強大：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。  [深入了解](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- **向左看，向右看... XLOOKUP 在這裡！：** 一列接著一列，在含有 XLOOKUP 的表格或範圍中尋找您需要的項目。  [深入了解](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 重複開啟內嵌在 Word 或 PowerPoint 中的活頁簿時，在某些情況下，Excel 會當機。

- 儲存為 CSV 檔案時，在某些情況下，Excel 會將所有欄合併成單一欄。

- 在受保護工作表中的範圍使用 Range.ClearContents 可能會比預期花的時間更長。

- 修正了在 [預覽列印] 中顯示表單控制項時的文字縮放比例問題。

- 與功能區互動的 VBA 宏可能會意外以 ScreenUpdating 設定為 True 執行。

- 解決了當來源活頁簿關閉時，外部連結無法在填滿時 (向下填滿、跨表填滿等) 更新的問題。

- 在某些情況下，使用 VBA 的 Application.Evaluate 對使用者定義的函數無法運作。

- 解決從範本建立圖表時的效能問題。


### <a name="outlook"></a>Outlook

- 解決了在某些情況下，[群組] 標題會意外展開的問題。

- 解決了導致使用者在選取特定搜尋結果時發生當機的問題。

- 解決了使用滑鼠上的 X 按鈕時，導致使用者偶爾發生當機的問題。

- 解決了會讓 [附件工具] 中的 [儲存至雲端] 按鈕不見的問題。

### <a name="powerpoint"></a>PowerPoint

- 已改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並貼到迴圈中的其他投影片，可能會出現例外狀況而失敗。


### <a name="project"></a>Project

- 修正了儲存使用舊版 [專案] 建立的專案時，[專案] 可能當機的問題。

- 修正了透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。

### <a name="word"></a>Word

- 解決了使用滑鼠上的 X 按鈕時，導致使用者偶爾發生當機的問題。

- 我們修正了表格中最適文字大小的問題。

- 我們修正了插入水平線無法更短並置中的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-10"></a>版本 2002：3 月 10 日
*版本 2002 (組建 12527.20278)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **快速尋找連結資料表：** 新的搜尋方塊可讓您輕鬆尋找連結資料表。 [深入了解](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **使用 \@提及取得他人注意：** 在註解中使用 @提及功能，讓同事知道您需要他們提供建議。 [深入了解](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **找到您要尋找的項目：** 搜尋命令、人員、檔案、相片、網頁文章等。 [深入了解](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **勾勒草圖：** 為活頁簿中的 Office 圖形提供隨意的手繪外觀。 [深入了解](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。

- **專注在待辦事項上：** 選取 [解決] 來摺疊註解，使得開啟中的項目能夠突顯。

- **建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。 [深入了解](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **轉換檔案，以提升存取性：** 將您的檔案升級為現代格式，讓所有人更容易存取。

- **資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。 [深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。

- **在活頁簿上取得統計資料：** 活頁簿統計資料提供活頁簿內容的概觀，協助您更輕鬆地探索其內容。





### <a name="outlook"></a>Outlook



- **將您的 LinkedIn 人際網路連接至 Outlook：** 安全地將您的 LinkedIn 帳戶與 Microsoft 帳戶連結，以直接在人員卡片中查看 LinkedIn 個人資料中的資訊。 [深入了解](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- **All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)

- **Outlook 中的 [插入連結] 功能表會插入含有租用戶系統管理員所定義的權限的連結：** Outlook 中使用 [插入連結] 所插入的連結，只有具有連結權限的使用者可使用。 這常會造成使用者來回傳送電子郵件，要求對方授與文件的存取權。 我們已更新這項體驗，現在插入的連結將具有由租用戶系統管理員設定的預設權限。針對 MSIT，這是「組織可以編輯」，使得以此方式收到共用連結的所有內部使用者將可以存取它。

- **具有拼字問題或錯字的搜尋：** 即使您的拼寫不相符，Outlook 也會找到您要尋找的內容。

- **網路釣魚郵件很容易找到：** 垃圾郵件和網路釣魚訊息的外觀不同，因此您可以從收件匣輕鬆找出並加以清除。

- **抵禦攻擊的進階防護：** 使用 Office 365 進階威脅防護，您會受到保護，不受電子郵件主旨、附加的郵件、簽署的郵件、網路路徑內超連結的攻擊。

- **讓我繪製：** 使用筆跡在圖片上徒手畫或新增繪圖畫布來傳達您的想法。 [深入了解](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- **在搜尋結果中查看相關郵件：** Outlook 會分析搜尋字詞，然後在搜尋結果的最上方顯示最相關的電子郵件。 您也可以在 [最佳結果] 區段中查看依日期排列順序的所有結果。 [深入了解](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- **取得位置建議：** 排程約會和會議時，請在 [位置] 中開始輸入，Outlook 會建議會議室、地址，以及其他最近使用的位置。 [深入了解](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- **在螢幕上容納更多郵件：** 選取 [檢視] > [使用更緊密的間距] 來調整郵件之間的間距。 [深入了解](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- **在不同燈光下查看郵件：** 使用太陽/月亮按鈕以在讀取窗格中於淺色和深色背景之間切換。 [深入了解](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)



### <a name="powerpoint"></a>PowerPoint

- **在 PowerPoint 中快速即時共同作業：** 在 PowerPoint 中快速即時共同作業

- **新的校對工具：** 不著重您的文字。 PowerPoint 現在提供文法及書寫建議。 [深入了解](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)


- **即時的輔助字幕和翻譯字幕：** 簡報者的文字會自動顯示為畫面上的標題，或翻譯為所選語言的字幕。 [深入了解](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。 [深入了解](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **尋找並修正遺失的投影片標題：** 投影片標題可為您的企劃加分，並讓所有功能的使用者都能存取投影片。 協助工具檢查程式會顯示缺少標題的地方，這樣您就可以快速新增標題。 [深入了解](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **勾勒草圖：** 為簡報中的 Office 圖形提供隨意的手繪外觀。 [深入了解](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。

- **將圖例另存成 SVG：** 將圖表、圖形或其他圖例另存成可縮放向量圖形，其可調整大小，且不損失影像品質。 [深入了解](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **列印講義上的投影片編號：** 投影片編號會自動包含在講義上。 由您決定將其保留或關閉。 [深入了解](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **筆跡立即重播：** 當您在投影片上進行手寫時，套用重播動畫可在投影片放映期間重播真實手繪的筆跡。 [深入了解](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- **建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。

- **全方位最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。

- **轉換檔案以增強協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。

- **更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。

- **當您可以重複使用時為什麼要重新打造？** 重複使用您所建立的投影片或其他人與您共用的投影片來以節省時間。 [深入了解](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- **在 Office 365 的 PowerPoint 中將手寫筆跡變更為圖形、文字或數學：** 從任意格式的筆跡變成 Office 圖形、文字，或以幾個筆劃變成數學運算式。 [深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **運用筆跡製作精彩的投影片：** 將筆跡轉換成標準圖形和文字，然後從 PowerPoint 設計工具吸取智慧的投影片設計概念。 [深入了解](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

### <a name="visio"></a>Visio

- **回到犯罪場景：** 在犯罪場景調查範本中使用新的證據、室內、室外樣板，重建犯罪場景的細節。

- **在 Excel 中製作精美的 Visio 圖表：** 將資料放在工作表上，以建立流程圖或組織圖。 [深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **簡歷編輯器加入 LinkedIn 簡歷小幫手：** 簡歷編輯器提供特別為簡歷量身打造的文法和樣式檢查選項，讓您的寫作更準確且更專業。

- **修正合併 3D 物件所造成的文件損毀問題：** 修正合併 3D 物件所造成的文件損毀問題。

- **尋找您要尋找的項目：** 使用搜尋方塊來尋找文字、命令、說明等。 [深入了解](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **在生動色彩中進行共同作業：** 註解和變更都依參與者加上色彩標示，讓您可以輕鬆查看您的共同作業者。

- **共同編輯啟用巨集的文件：** 將 docm 檔案儲存在商務用 OneDrive，並與共同作業者即時編輯。

- **共同撰寫的增強功能**：在具有追蹤修訂的文件中共同撰寫來強化 Word 效能。

- **符合您情境的更多圖示：** 我們新增了超過 300 個新圖示。 其位置：[插入] > [圖示]。 [深入了解](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。

- **勾勒草圖：** 為文件中的 Office 圖形提供隨意的手繪外觀。 [深入了解](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **精確橡皮擦：** 從兩個橡皮擦尺寸中選擇，以修正小型筆跡缺陷。 [深入了解](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。 [深入了解](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- **其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。

- **共同撰寫的增強功能**：增強共同撰寫時的可靠性。

- **建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。 [深入了解](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **轉換檔案，以改善協助工具功能：** 將您的檔案升級為現代格式，讓所有人更容易存取。

- **更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。 [深入了解](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- **將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。 [深入了解](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此更新可修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致發生錯誤「查詢已損壞」&quot;&quot;的問題。

- 此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。

- 此更新會修正使用 ADODB 的問題。 VB 程式碼中的記錄器物件可能會不正確地報告錯誤。

- Access 範本應不再導致資料庫中的附件欄出現故障。 個體化範本後，您現在應該可以將附件欄新增至資料庫。

### <a name="excel"></a>Excel

- 解決重新命名簽名時，使用者遇到當機的問題。

- 這項變更透過利用軟體轉譯來避免特定 Intel 圖形驅動程式的問題。

- 修正對具有溢出陣列之儲存格進行資料剖析的轉換時，導致某些使用者發生當機的問題。

- 此更新可修正導致資料編輯列以預期不同的字型顯示文字的問題。

- [資料剖析] 功能對某些地區設定可能會失敗。

- 使用者在存取隱藏的命名範圍時可能會發生錯誤。

- 使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。

- 解決捲動後選取儲存格時，可能導致選取錯誤儲存格的問題。

- 從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。

- 某些當地語系化版本的 [資料剖析] 功能可能會失敗。

- 使用者在存取隱藏的命名範圍時可能會遇到錯誤。

- 使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。

- 修正某些使用者使用內嵌和連結化物件 (OLE) 時可能發生的問題。

- 我們修正了樞紐分析圖的右鍵功能表，以啟用 [顯示詳細資料] 選項。

- 解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。

- 修正當活頁簿中有外部連結時，有些使用者可能會遇到多個彈出式視窗的問題。

- 修正操作功能表中未顯示註解命令的問題。

- 解決開啟內嵌活頁簿時，功能區自訂無法載入的問題。

- 修正 CUBEVALUE 函數有時會傳回不正確結果的問題。

### <a name="outlook"></a>Outlook

- 已解決導致在搜尋意見反應體驗中懸置的問題。

- 解決在擷取雲端設定時，導致使用者在 Outlook 中遇到當機的問題。

- 解決導致搜尋方塊在高 DPI 模式中未正確對齊的問題。

- 解決導致使用者在 Outlook 處理序中看到記憶體流失的問題。

- 解決在某些情況下，導致使用者看到電子郵件傳送到與顯示的 SMTP 位址不相符之地址的問題。

- 此變更會還原在郵件標頭中檢視多行主旨的功能。

- 我們已修正會防止將檔案儲存到 WebDAV 位置的問題。

- 修正 SMIME 演算法選取的問題。

- 解決導致協力廠商應用程式無法傳送電子郵件的問題。

- 解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定]&quot;&quot; 按鈕的空白訊息方塊的問題。

- 已解決導致使用者在建立設定檔時遇到當機的問題。

- 解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。

- 解決導致使用黑色佈景主題的使用者看到 [寄件者]&quot;&quot; 下拉式清單在白色背景上顯示白色文字的問題。

- 解決導致使用者在取消帳戶設定時發生當機的問題。

- 解決重新命名簽名時，使用者遇到當機的問題。

- 解決導致在某些情況下，用來停用標幟項目醒目提示的選項無法使用的問題。

- 解決會導致使用者在開啟 [規則] 對話方塊時看到「在這部電腦中建立的規則和 Microsoft Exchange 上的規則衝突」提示的問題。

- 解決導致使用者在指定無效寄件者地址時發生當機的問題。

- 解決導致非常長時間的 Outlook 工作階段記憶體流失的問題。

- 解決在多個視窗中檢視相同項目時可能會導致當機的問題。

- 解決當使用者透過鍵盤快速鍵與信箱資料夾互動時，導致明顯延遲的問題。

- 解決導致使用者無法開啟某些週期性行事曆項目執行個體的問題。

- 解決導致使用 Exchange 2010 伺服器上信箱的使用者在將附件新增至行事曆項目時遇到問題的問題。

- 解決導致使用者在回覆數位簽章的郵件時發生問題的問題。

- 解決會導致會議中的 [位置] 欄位意外更新的問題。

- 解決導致會議的位置欄位中的逗號變成分號的問題。

- 解決導致會議位置在清除之後，又會不預期地重新加回會議的問題。

- 解決與在巴西時區中設定的會議和約會相關的問題。

- 解決當您關閉協助工具檢查程式窗格之後按 &quot;S&quot; 鍵時，導致使用者看到郵件意外傳送的問題。

- 這會更新 Outlook 中的附件封鎖邏輯，以同時封鎖 Python 附件。

- 解決導致網頁增益集存取數位版權管理郵件的問題。

- 解決導致使用者在建立設定檔時遇到當機的問題。

- 解決重新命名簽名時，使用者遇到當機的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正 Shape.Paste 方法的問題：當使用者使用 Shape.Paste 方法複製並貼上圖形時，它會將選取範圍變更為貼上的圖形。

- 解決在舊版 PPT 註解中使用操作功能表時可能發生當機的問題。

### <a name="project"></a>Project

- 發現在開啟唯讀專案時，使用者可能會收到數個訊息的問題。

- 修正固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成的問題。

- 修正無法正確計算摘要工作日期的問題。

- 修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。

### <a name="word"></a>Word

- 我們已修正在某些情況下，儲存現有檔案永遠會導致出現 [另存新檔] 對話方塊且檔案永遠不會儲存的問題。

- 建置組塊召集人可能會顯示不正確通知：&quot;您已修改過樣式、建置組塊&quot;。

### <a name="office-suite"></a>Office 套件

- 此變更可解決轉譯某些含有資料標記的散佈圖緩慢的問題。

- 此變更可解決所報告使用 Intel 整合式 GPU 圖形配接卡的問題。

- 修正相對期限只有在第一次設定時才會有效的 ODT 和 GPO 更新期限設定中的錯誤，此修正可啟用後續更新的相關期限。

- 解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。

- 修正在 Word/Excel/PowerPoint 中開啟來自相同 SharePoint 文件庫的多個文件時，僅掃描開啟的第一個文件是否符合原則的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-february-11"></a>版本 1908：2 月 11 日
*版本 1908 (組建 11929.20606)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 此更新已修正使用 VBA 將影像新增到圖表的頁首/頁尾時發生錯誤的問題。

- 已修正在預覽列印或列印時群組方塊控制項的框線無法顯示的問題。

- 使用者在使用某些非英文字元集的情況下，儲存變更時可能會遇到錯誤的問題。

- 已修正圖表標題中影像檔案大小在儲存包含圖表的活頁簿時增加的問題。


- 已修正以下問題：將選取範圍與交互參照的活頁簿保持同步時，導致交互參照的活頁簿中的 DBCS 字元損毀。

- 已解決使用自動調整來調整列高時，核取方塊可能收縮的問題。


### <a name="outlook"></a>Outlook

- 已解決導致使用者在指定無效寄件者地址時發生當機的問題。

- 已解決導致使用者處理衝突郵件時同步失敗的問題。

- 已解決導致使用者在啟動 Outlook 時，「正在載入設定檔」畫面時停滯的問題。

- 已解決導致使用者在變更檢視時發生當機的問題。


- 已解決在 Citrix 環境中檢視 30 個以上的行事曆時，導致使用者遇到當機的問題。 [此處](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)是記錄舊版問題的個別 KB。

- 已解決以下問題：使用者將共用行事曆資料夾同步到 OST 時發生問題，這導致嘗試與這些資料夾互動時發生權限錯誤。


### <a name="powerpoint"></a>PowerPoint

- 已改善複製貼上的案例，即將 PowerPoint 投影片中的圖形複製並貼到其他投影片可能會因為異常而失敗。


- 已修正導致共同作業使用者之間效能較低的問題。

- 已修正以下問題：當檔案以漸進式開啟時，若其中一個投影片包含多個內嵌媒體串流可能會發生問題。

- 已修正以下問題：首次啟動 PowerPoint 時，不受信任的增益集可能不會顯示安全性警告訊息列。

### <a name="project"></a>Project

- 已修正以下問題：由於基準行事曆變更時未更新資源行事曆，而導致時程表和專案計劃之間的實際工作可能不同。

### <a name="word"></a>Word

- 已從遭取代的 API 移除，以修正 Word 的當機問題。

### <a name="office-suite"></a>Office 套件

- 此變更解決開啟損毀的檔案時正確呈現影像的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a>版本 1908：1 月 14 日
*版本 1908 (組建 11929.20562)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 文件標題的荷蘭文按鍵提示已變更為 Alt-G。

- 解決了開啟內嵌活頁簿時，功能區自訂無法載入的問題。

- 發生您無法從增益集開啟的 WPF (Windows Presentation Foundation) 表單的下拉式方塊選取項目的問題。

### <a name="outlook"></a>Outlook

- 解決當使用者透過鍵盤快速鍵與信箱資料夾互動時會造成明顯延遲的問題。

- 解決使用其他寄件者時導致無法顯示原則提示的問題。

- 解決了導致使用者在更新目前狀態資訊時遇到間歇性當機的問題。

### <a name="powerpoint"></a>PowerPoint

- 我們已修正將投影片從一個簡報複製到另一個簡報時可能會造成母片重複的問題。
- 如果在不支援的版本中開啟含有新的新式註解的檔案，將會顯示黃色警告

### <a name="office-suite"></a>Office 套件

- 修正了 Office 更新訊息不以預期語言顯示的問題。 自此以後，Office 更新訊息會正確符合 Windows 顯示語言。

- 解決在某些情況下，如果使用者不是系統管理員且系統帳戶沒有網路連線，將無法套用更新的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> 如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。