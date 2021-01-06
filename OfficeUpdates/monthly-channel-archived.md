---
title: 每月通道版本的封存版本資訊
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 Office 365 專業增強版每月通道版本的版本資訊
ms.openlocfilehash: 04f7cf6f6b4ed2841d68f0ad8aed28e989261d03
ms.sourcegitcommit: 96185aa6c5a06095c58b57ac36cb2800add8bea0
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/06/2021
ms.locfileid: "49760712"
---
# <a name="archived-release-notes-for-monthly-channel"></a>每月通道的封存版本資訊
這些版本資訊可提供 Office 365 專業增強版、Visio Pro for Office 365、Project Online 電腦版用戶端以及 Office 365 商務版的每月通道更新所含新功能和非安全性更新的相關資訊。

 > [!NOTE]
>- 我們通常會在一段時間每個月推出功能 (有時甚至推出修正程式)。  如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。 [深入了解](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- 現有 Office 365 專業增強版安裝上的 Microsoft Teams - 從 7 月初開始，對 Office 365 專業增強版 (和 Office 365 商務版) 的更新將包含 Microsoft Teams。  新增 Teams 的日期取決於您使用的更新通道。 如需詳細資訊，請參閱[隨著 Office 365 專業增強版部署 Microsoft Teams](https://docs.microsoft.com/DeployOffice/teams-install)。

## <a name="version-1911-december-10"></a>版本 1911：12 月 10 日
*版本 1911 (組建 12228.20364)*

安全性更新列於[此處](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。

- 我們修正了樞紐分析圖的右鍵功能表，以啟用 [顯示詳細資料] 選項。

### <a name="outlook"></a>Outlook

- 解決造成網頁增益集存取數位版權管理郵件的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-december-03"></a>版本 1911：12 月 3 日
*版本 1911 (組建 12228.20332)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **輸入會傳回多個值的公式**：現在您可以快速輸入公式來傳回多個值，並且值會自動溢出至相鄰的儲存格。 [深入了解](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)

- **六個功能強大的函數：** 我們新增了六個新的函數，讓您的試算表功能更強大：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。 [深入了解](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- **資料視覺化工具增益集：** 從 Excel 快速建立 Visio 流程圖。 [深入了解](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **改善共同撰寫：** 改善共同撰寫的體驗，盡可能讓其他人即時收到修改過的內容。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 修正 Microsoft Access 中的「更新查詢」執行時或在 SQL 中使用 UPDATE 陳述式時，可能導致發生錯誤「查詢已損壞」&quot;&quot;的問題。

### <a name="excel"></a>Excel

- 從不受信任的網路共用編輯受保護的檔案時，Excel 可能會發生問題。

- 解決在未開啟活頁簿時，搜尋最近使用的檔案會造成當機的問題。

### <a name="outlook"></a>Outlook

- 解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定]&quot;&quot; 按鈕的空白訊息方塊的問題。

- 在 2019 年使用巴西時區時，週期性會議和約會以 2020 年的錯誤時段顯示。 此變更與設定使用巴西時區的用戶端或設定使用該時區的會議和約會相關。 

- 解決會導致使用者在開啟 [規則] 對話方塊時看到「在這部電腦中建立的規則和 Microsoft Exchange 上的規則衝突」提示的問題。

- 修正 SMIME 演算法選取的問題。

- 解決會導致會議中的 [位置] 欄位意外更新的問題。

### <a name="office-suite"></a>Office 套件

- 解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。

- 修正 ODT 和 GPO 更新期限設定中的問題，在其中，相對期限只有在第一次設定時才會有效，此修正可啟用後續更新的相關期限。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-november-22"></a>版本 1910：11 月 22 日
*版本 1910 (組建 12130.20410)*
* 各種錯誤和效能修正。

## <a name="version-1910-november-18"></a>版本 1910：11 月 18 日
*版本 1910 (組建 12130.20390)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="access"></a>Access

- 已修正執行更新查詢會不正確顯示「查詢損毀」錯誤訊息的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-november-12"></a>版本 1910：11 月 1 2日
*版本 1910 (組建 12130.20344)*

安全性更新列於[此處](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決會導致使用者在會議中看到位置欄位意外變更的問題。

- 解決會導致使用者在嘗試從 [帳戶建立] 內容連絡支援服務時，看到具有 [確定]&quot;&quot; 按鈕的空白訊息方塊的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-october-30"></a>版本 1910：10 月 30 日
*版本 1910 (組建 12130.20272)*

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決會導致在搜尋意見反應體驗中懸置的問題。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新

### <a name="excel"></a>Excel

- **建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。 [深入了解](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **轉換檔案，以提升存取性：** 將您的檔案升級為現代格式，讓所有人更容易存取。

- **將敏感度標籤套用至您的文件和電子郵件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合組織的資訊保護原則。 [深入了解](https://aka.ms/officemipdocs)

### <a name="outlook"></a>Outlook

- **將敏感度標籤套用至您的文件和電子郵件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合組織的資訊保護原則。 [深入了解](https://aka.ms/officemipdocs)

### <a name="powerpoint"></a>PowerPoint

- **建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。 [深入了解](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **轉換檔案，以提升存取性：** 將您的檔案升級為現代格式，讓所有人更容易存取。

- **將敏感度標籤套用至您的文件和電子郵件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合組織的資訊保護原則。 [深入了解](https://aka.ms/officemipdocs)

### <a name="word"></a>Word

- **共同撰寫的增強功能**：在具有追蹤修訂的文件中共同撰寫來強化 Word 效能。

- **建立更易於存取的 PDF：** 建立 PDF 檔案，在儲存之前，協助工具檢查程式會指出應該修正的協助工具問題。 [深入了解](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **轉換檔案，以提升存取性：** 將您的檔案升級為現代格式，讓所有人更容易存取。

- **已修正合併 3D 物件所造成的文件損毀問題：** 已修正由合併 3D 物件所造成的文件損毀問題。

- **將敏感度標籤套用至您的文件和電子郵件**：將敏感度標籤套用至您的檔案和電子郵件，使其符合組織的資訊保護原則。 [深入了解](https://aka.ms/officemipdocs)

### <a name="office-suite"></a>Office 套件

- **在現有的 Office 365 專業增強版上安裝 Microsoft Teams：** 從 6 月底開始，Microsoft Teams 將在更新這些安裝時，新增至 Office 365 專業增強版 (和 Office 365 商務版) 的現有安裝中。 新增 Teams 的日期取決於您使用的更新通道。 如需詳細資訊，請參閱隨著 Office 365 專業增強版部署 Microsoft Teams。 [深入了解](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-1909-october-22"></a>版本 1909：10 月 22 日
*版本 1909 (組建 12026.20344)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="project"></a>Project
- 解決開啟唯讀專案時，使用者可能會取得多個訊息的問題。

### <a name="office-suite"></a>Office 套件

- 為了保護 Office 客戶的安全性，我們現在專門使用 SHA-2 演算法來簽署 Microsoft Office 更新。<br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="october-15"></a>10 月 15 日

### <a name="non-security-updates"></a>非安全性更新

### <a name="office-suite"></a>Office 套件
- 我們已暫時停用 [雲端儲存] 對話方塊以解決在 2019 年 10 月14 日針對早於 12130.20184 的組建所發佈的儲存問題。 這項功能即將重新啟用。


## <a name="version-1909-october-14"></a>版本 1909：10 月 14 日
*版本 1909 (組建 12026.20334)*

### <a name="non-security-updates"></a>非安全性更新

### <a name="office-suite"></a>Office 套件

- 解決使用者使用早於 12130.20184 的組建時，可能無法儲存 Word、Excel 和 PowerPoint 2019 文件的問題。  此問題會影響建立新檔案並在按一下 [儲存] 圖示或按 Ctrl + S 之後帶出 [另存新檔] 對話方塊的使用者。


## <a name="version-1909-october-08"></a>版本 1909：10 月 8 日
*版本 1909 (組建 12026.20320)*

安全性更新列於[此處](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新

### <a name="outlook"></a>Outlook

- 已修正 Outlook 中的附件封鎖邏輯也會封鎖 python 附的問題。

- 已解決導致使用者無法開啟某些週期性行事曆項目執行個體的問題。

- 已解決導致使用者在 Outlook 處理序中看到記憶體洩漏的問題。

- 已解決導致使用者在建立設定檔時遇到當機的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1909-september-30"></a>版本 1909：9 月 30 日
*版本 1909 (組建 12026.20264)*
* 不同的錯誤 (bug) 和效能修正。

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **快速尋找連結資料表：** 新的搜尋方塊可讓您輕鬆尋找連結資料表。 [深入了解](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。

### <a name="outlook"></a>Outlook

- **Outlook 中的 [插入連結] 功能表會插入含有租用戶系統管理員所定義的權限的連結：** Outlook 中使用 [插入連結] 所插入的連結，只有具有連結權限的使用者可使用。 這常會造成使用者來回傳送電子郵件，要求對方授與文件的存取權。 我們已更新這項體驗，現在插入的連結將具有由租用戶系統管理員設定的預設權限。

- **Outlook 視覺更新**：這是 Outlook 核心體驗的視覺更新的一部分，其中更新 [讀取窗格] 和 [檢查] 中的 [郵件訊息] 版面配置。

- **共用行事曆更新的速度更快：** 針對 Office 365 中的共用行事曆，Outlook 可以使用 REST API 更新這些行事曆。 開啟預覽以更快且更可靠地更新共用行事曆。

- **在搜尋結果中查看相關郵件：** Outlook 會分析搜尋字詞，然後在搜尋結果的最上方顯示最相關的電子郵件。 您也可以在 [最佳結果] 區段中查看依日期排列順序的所有結果。

- **傳送郵件給正確的人員：** 只需按一下 [收件者：] 行，然後從 [建議的連絡人] 中選擇。 圖片和目前狀態指示器可協助您選擇正確的人員。

- **抵禦攻擊的進階防護：** 使用 Office 365 進階威脅防護，您會受到保護，不受電子郵件主旨、附加的郵件、簽署的郵件、網路路徑內超連結的攻擊。

- **在不同燈光下查看郵件：** 使用太陽/月亮按鈕以在讀取窗格中於淺色和深色背景之間切換。 [深入了解](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

### <a name="powerpoint"></a>PowerPoint

- **將圖例另存成 SVG：** 將圖表、圖形或其他圖例另存成可縮放向量圖形，其可調整大小，且不損失影像品質。 [深入了解](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **筆跡重播：** 對筆跡繪圖進行動畫處理，以使其在投影片放映過程中向前或向後重播。 [深入了解](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- **更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。

### <a name="visio"></a>Visio

- **使用 Microsoft Flow 和 Visio 來設計和自動化業務工作流程：** 使用 Visio 來設計工作流程圖，並將它匯出到 Microsoft Flow 以進行自動化。

### <a name="word"></a>Word

- **用其他方式表達：** 當您想要以不同方式表達時，「重寫」功能可以幫助您。 重寫提供其他不同方式來表達您的詞彙。

- **共同撰寫的增強功能**：增強共同撰寫時的可靠性。

- **更快速共用檔案：** 不需開啟檔案，即可從最近使用清單直接共用您的檔案。

- **其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="excel"></a>Excel

- <div><span style="background-color:rgb(255, 255, 255);display:inline !important;">解決會導致將超連結貼到一些受保護工作表中的問題。</span><br></div>


- <div>&nbsp;<span style="font-size:13.3333px;background-color:rgb(255, 255, 255);display:inline !important;">當在增益集管理員中瀏覽時</span>，顯示 16 個以上的增益集。</div>
- <div>已修正在 Excel 構想功能中，在 Win32 用戶端中按一下 [構想] 按鈕來載入增益集時會發生錯誤的問題。&nbsp;</div>

### <a name="outlook"></a>Outlook

- <div>已解決導致部分安全連結無法顯示簡單動態顯示 URL 的問題。</div>


- <span style="background-color:rgb(255, 255, 255);display:inline !important;">已更新 Outlook 中的附件封鎖邏輯，以同時封鎖 python 附件。</span>


- <span style="background-color:rgb(255, 255, 255);display:inline !important;">已解決導致使用者在 Outlook 處理序中看到記憶體洩漏的問題。</span>

- 我們已修正了檔案可能無法儲存到 WebDAV 位置的問題。


### <a name="office-suite"></a>Office 套件

- <div><p style="margin:0in 0in 0.0001pt;font-size:11pt;font-family:Calibri, sans-serif;">我們已修正使用者在開啟檔案時會發生的問題。</p></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-september-10"></a>版本 1908：9 月 10 日
*版本 1908 (組建 11929.20300)*

安全性更新列於[此處](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>非安全性更新
### <a name="outlook"></a>Outlook

- 修正會導致使用者無法透過螢幕助讀程式存取位置建議的問題。

- 修正嘗試擷取使用者的 Outlook 雲端設定時，導致一些使用者遇到驗證錯誤的問題。

### <a name="powerpoint"></a>PowerPoint

- 修正還原 PowerPoint 影片控制項的協助工具名稱的問題。

- 修正部分動畫無法開始的問題。

### <a name="word"></a>Word

- 修正嘗試共用儲存在 SharePoint 2016 上的檔案時，導致使用者遇到「很抱歉，發生問題，無法共用」訊息的問題。

### <a name="office-suite"></a>Office 套件

- 修正大型樹狀檢視失敗的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-august-26"></a>版本 1908：8 月 26 日
*版本 1908 (組建 11929.20254)*
* 各種錯誤和效能修正。

### <a name="excel-feature-updates"></a>Excel：功能更新

- **勾勒草圖：** 為活頁簿中的 Office 圖形提供隨意的手繪外觀。 [深入了解](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。 而當您選取時，[插入] 按鈕會告知您已經選取的數量。 [深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

- **專注在待辦事項上：** 選取 [解決] 來摺疊註解，使得開啟中的項目能夠突顯。

### <a name="office-suite-feature-updates"></a>Office 套件：功能更新

- **Office 圖示有新的外觀：** Office 圖示經過重新設計，以反映簡單、功能強大且智慧型的 Office 體驗。

### <a name="outlook-feature-updates"></a>Outlook：功能更新

- **取得位置建議：** 排程約會和會議時，請在 [位置] 中開始輸入，Outlook 會建議會議室、地址，以及其他最近使用的位置。 [深入了解](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- **搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。 而當您選取時，[插入] 按鈕會告知您已經選取的數量。 [深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新

- **勾勒草圖：** 為簡報中的 Office 圖形提供隨意的手繪外觀。 [深入了解](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。 而當您選取時，[插入] 按鈕會告知您已經選取的數量。 [深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-feature-updates"></a>Word：功能更新

- **勾勒草圖：** 為文件中的 Office 圖形提供隨意的手繪外觀。 [深入了解](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **搜尋並享受：** 我們新增了 [搜尋以插入] 圖示，讓您輕鬆找到您要的圖示。 而當您選取時，[插入] 按鈕會告知您已經選取的數量。 [深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

## <a name="version-1907-august-13"></a>版本 1907：8 月 13 日
*版本 1907 (組建 11901.20218)*

安全性更新列於[此處](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

### <a name="excel-non-security-updates"></a>Excel：非安全性更新

- 修正在與其他使用者共同撰寫的工作階段中變更樞紐分析表排序的方式，然後重新整理可能觸發的問題。

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新

- 修正使用者將信箱從基本驗證升級為新式驗證後造成錯誤的帳戶與 Outlook 設定檔相關聯的問題。

## <a name="version-1907-july-29"></a>版本 1907：7 月 29 日

*版本 1907 (組建 11901.20176)*
* 各種錯誤和效能修正。

### <a name="excel-feature-updates"></a>Excel：功能更新

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或 App 中開啟。

- **使用 Power Query 的增強功能快速撰寫程式碼：** 使用自動完成和語法色彩快速完成程式碼。 同時輕鬆探索函數、資料行和參數。

- **建立地圖圖表：** 此功能是針對使用 Excel 的地理資料類型繪製區域分布圖圖表使用者的增強功能。 對使用者的優點是功能之間有更豐富的整合，以及使用者要對應的區域會有更好的精確度。 其他優點包括功能能夠對應城市多邊形。 [深入了解](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **聯結類似欄位上的表格：** 在比較合併表格的欄位時，取得及轉換 (Power Query) 現在具有近似文字比對邏輯 (也稱為模糊比對)。 [深入了解](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

### <a name="outlook-feature-updates"></a>Outlook：功能更新

- **搜尋人員時取得電子郵件建議：** 當您在 [搜尋] 方塊中輸入人員的名稱時，最相關的電子郵件訊息會包括在您的搜尋建議中。 [深入了解](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或 App 中開啟。

- **線上影片有新的首頁：** 將影片儲存至 Microsoft Stream，讓組織中的任何人都看得到。 插入影片連結，享受檔案大小只有原來一小部分的多媒體簡報。 [深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **建立地圖圖表：** 此功能是針對使用 Excel 的地理資料類型繪製區域分布圖圖表使用者的增強功能。 對使用者的優點是功能之間有更豐富的整合，以及使用者要對應的區域會有更好的精確度。 其他優點包括功能能夠對應城市多邊形。 [深入了解](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **新增投影片標題以讓簡報更易於使用：** 協助工具檢查程式可協助您找出並修正遺失的投影片標題。 [深入了解](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **[在講義上列印投影片編號] 設定已移至 [列印] 功能表，以易於存取：** 選取講義版面配置時，可在 [列印] > [整頁模式] 下拉式清單中找到它。 這也會使得每個簡報的設定易於切換。 [深入了解](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

### <a name="word-feature-updates"></a>Word：功能更新

- **跟分心說再見：** Mac 中最受歡迎的功能來到 Windows。 切換到 [檢視] 功能表中的 [焦點] 以移除令人分心的事物，讓您更能專注於工作。 [深入了解](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或 App 中開啟。

- **建立地圖圖表：** 此功能是針對使用 Excel 的地理資料類型繪製區域分布圖圖表使用者的增強功能。 對使用者的優點是功能之間有更豐富的整合，以及使用者要對應的區域會有更好的精確度。 其他優點包括功能能夠對應城市多邊形。 [深入了解](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **精確橡皮擦：** 從兩個橡皮擦尺寸中選擇，以修正小型筆跡缺陷。 [深入了解](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

## <a name="version-1906-july-09"></a>版本 1906：7 月 9 日
*版本 1906 (組建 11727.20244)*

安全性更新列於[此處](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新

- 解決導致目前的資料夾搜尋間歇性失敗的問題。

## <a name="version-1906-june-27"></a>版本 1906：6 月 27 日
*版本 1906 (組建 11727.20230)*

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新

- 解決導致部分 POP3 使用者查看所有純文字格式電子郵件 (無論設定) 的問題。  此修正將會還原 HTML 格式郵件的檢視。

## <a name="version-1906-june-26"></a>版本 1906：6 月 26 日
*版本 1906 (組建 11727.20224)*

### <a name="excel-non-security-updates"></a>Excel：非安全性更新

- 已修正 Excel 中，巨集指派給圖形或表單控制項時，可能會顯示不正確的錯誤訊息，或者可能會處理不正確目標範圍的問題。
- 已解決導致表格旁的剪下並貼上作業在與其他人共同撰寫時失敗的問題。

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新

- 解決導致經理對於代理人是否已經回覆特定會議邀請含混不清的問題。

## <a name="version-1906-june-24"></a>版本 1906：6 月 24 日
*版本 1906 (組建 11727.20210)*
* 不同的錯誤 (bug) 和效能修正。

### <a name="excel-feature-updates"></a>Excel：功能更新

- **觀看工作表生動地呈現：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在工作表內橫衝直撞。 [深入了解](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

### <a name="outlook-feature-updates"></a>Outlook：功能更新

- **簡化且也能自訂的功能區：** 輕鬆使用簡化、以單一列方式陳列的常用按鈕。 輕鬆在傳統與 [簡化] 檢視之間切換，以及釘選/取消釘選命令。 [深入了解](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **挑選您的最愛動作：** 不使用 [標幟] 和 [刪除] 嗎？ 那麼 [封存] 或 [標示為已讀取] 呢？ 在您最常使用的命令，自訂快速動作功能表。

- **已改善擁有多個資料夾的信箱共用資料夾同步處理：** Outlook 多年來在同步處理共用信箱時，將其資料夾的數量限制最多為 500 個。 這項變更改善了 Outlook，同步處理時將不會再發生 500 個資料夾的數量限制。

- **焦點收件匣設定在不同裝置之間會保持相同：** 您的焦點收件匣喜好設定現在會儲存在雲端。 這麼一來，當您在任何電腦上使用 Windows 版 Outlook 和 Outlook 網頁版時便可享有相同的體驗。 [深入了解](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- **想要寬鬆或緊密的版面配置？您可自由選擇：** 若您想讓郵件之間能有更多空間，可以採用「緊密間距」；或者，您也可以採用緊密的版面配置，以便查看更多郵件。

- **我們已為您更新 Outlook 使用者體驗：** 先前利用「即將推出」提供預覽的簡化體驗，專門設計來幫助您專注於最重要的事物上。 [深入了解](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **讓我繪製：** 使用筆跡在圖片上徒手畫或新增繪圖畫布來傳達您的想法。 [深入了解](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

### <a name="word-feature-updates"></a>Word：功能更新

- **共同撰寫：** 厭倦於被包含巨集的文件阻礙了嗎？ 現在商務用 OneDrive 的 docm 檔案允許同時由多個作者編輯。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新 

 - 修正當監視器縮放超過 100% 時，在會議中會顯示來自 Polycom CX5500 和相關裝置的所有攝影機串流

- 啟用 [在會議中裁剪我的視訊並置中對齊] 設定時，在 4K 監視器上進行的會議可正確裁剪視訊

- 允許從具有多張網路介面卡的 Windows 10 電腦將檔案傳輸到舊版 Office Communicator 用戶端。

- 改善了商務用 Skype 和 Microsoft Teams 參與者之間的通訊體驗


## <a name="version-1905-june-11"></a>版本 1905：6 月 11 日
*版本 1905 (組建 11629.20246)*
<br/>安全性更新列於[此處](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

### <a name="excel-non-security-updates"></a>Excel：非安全性更新

- 已解決以下問題：當插入或刪除儲存格時，瀑布圖和漏斗圖無法與表格同步處理。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新

- 已修正某些增益集會在圖表的圖形周圍擲出未預期錯誤的問題。

### <a name="visio-non-security-updates"></a>Visio：非安全性更新

- 有多個圖形無法從 Visio 匯出至 SVG。

## <a name="version-1905-june-3"></a>版本 1905：6 月 3 日
*版本 1905 (組建 11629.20214)*

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新

- 已修正某些增益集會在圖表的圖形周圍擲出未預期錯誤的問題。

## <a name="version-1905-may-29"></a>版本 1905：5 月 29 日
*版本 1905 (組建 11629.20196)*

### <a name="access-feature-updates"></a>Access：功能更新

- **順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。 在帳戶間切換就是這麼簡單。 [深入了解](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel-feature-updates"></a>Excel：功能更新

- **順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。 在帳戶間切換就是這麼簡單。 [深入了解](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **即將推出：** 查看 Office 即將推出的新鮮變更，立即試用並給予我們意見反應。 [深入了解](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- **在註解中使用 @Mentions 提及功能，讓共同作業更有效率：** 共同作業變得更容易了！ 現在您可以在文件註解中 @提及小組成員，而他們會自動收到電子郵件通知，並將他們帶至該文件中。

- **共同撰寫合併增強功能：** 共同撰寫已改善使用條件式格式設定、儲存格樣式、範圍保護、檢視格線和跨工作表剪下/貼上時的合併成功率。 

### <a name="outlook"></a>Outlook

- **快速新增帳戶的方式：** 由於帳戶設定已改善，您現在可以更輕鬆地將使用雙因素驗證的 Outlook.com 和 Gmail 帳戶新增到 Outlook。 [深入了解](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新

- **順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。 在帳戶間切換就是這麼簡單。 [深入了解](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **即時的輔助字幕和翻譯字幕：** 簡報者的文字會自動顯示為畫面上的標題，或翻譯為所選語言的字幕。 [深入了解](https://support.office.com/article/d68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **即將推出：** 查看 Office 即將推出的新鮮變更，立即試用並給予我們意見反應。 [深入了解](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- **在註解中使用 @Mentions 提及功能，讓共同作業更有效率：** 共同作業變得更容易了！ 現在您可以在文件註解中 @提及小組成員，而他們會自動收到電子郵件通知，並將他們帶至該文件中。

### <a name="project-feature-updates"></a>Project：功能更新

- **順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。 在帳戶間切換就是這麼簡單。 [深入了解](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio-feature-updates"></a>Visio：功能更新

- **順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。 在帳戶間切換就是這麼簡單。 [深入了解](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **匯出成 PDF、PPT 或針對電子郵件訂閱而設定的 Power BI 報表現在也將具備 Visio 視覺效果：** 如果您將 Power BI 報表匯出成 PDF、PPT，或為其設定電子郵件訂閱，Visio 視覺效果將會以這些匯出的格式完美地呈現。 [深入了解](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word-feature-updates"></a>Word：功能更新  

- **在註解中使用 @Mentions 提及功能，讓共同作業更有效率：** 共同作業變得更容易了！ 現在您可以在文件註解中 @提及小組成員，而他們會自動收到電子郵件通知，並將他們帶至該文件中。

- **順暢地切換：** 全新的帳戶管理員會在同一個地方顯示您所有的 Office 365 公司和個人帳戶。 在帳戶間切換就是這麼簡單。 [深入了解](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **[學習工具] 模式額外支援更多頁面色彩：** Word 中的 [學習工具] 新增更多頁面佈景主題色彩的支援，讓您能夠變更頁面的背景色彩。  許多人在背景全白或全黑時閱讀會有困難，因此我們在 PC 和 Mac 的 Word 中增加了色彩選項。

- **即將推出：** 查看 Office 即將推出的新鮮變更，立即試用並給予我們意見反應。 [深入了解](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新

- 為商務用 Skype Online 使用者提供選項以停用 [新增相片 - 幫助人們了解您] 上下文提示。 若要啟用此修正程式，您可以[深入了解](https://support.microsoft.com/help/4503469)。

- 防止在重新啟動商務用 Skype 後，總是啟用第二個響鈴設定。 若要啟用此修正程式，您可以[深入了解](https://support.microsoft.com/help/4503470)。

 - 修正當加入大型會議同時使用 Lync SDK 型應用程式時，商務用 Skype 停止回應的問題。 若要啟用此修正程式，您可以[深入了解](https://support.microsoft.com/help/4503472)。

## <a name="version-1904-may-22"></a>版本 1904：5 月 22 日
*版本 1904 (組建 11601.20230)*

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新

- 這解決了使用者在選取並提交其隱私權等級的選項後，在每次啟動應用程序時都會看到新隱私權提示的問題。

## <a name="version-1904-may-14"></a>版本 1904：5 月 14 日 
*版本 1904 (組建 11601.20204)*

- 安全性更新列於[此處](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

## <a name="version-1904-may-8"></a>版本 1904：5 月 8 日
*版本 1904 (組建 11601.20178)*

- 各種錯誤和效能修正。

## <a name="version-1904-april-29"></a>版本 1904：4 月 29 日
*版本 1904 (組建 11601.20144)*

### <a name="excel-feature-updates"></a>Excel：功能更新

- **快速找到該檔案：** 想要尋找最近使用過的檔案嗎？ 只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。

### <a name="outlook-feature-updates"></a>Outlook：功能更新

- **將您的 LinkedIn 人際網路連接至 Outlook：** 安全地將您的 LinkedIn 帳戶與 Microsoft 帳戶連結，以直接在人員卡片中查看 LinkedIn 個人資料中的資訊。 [深入了解](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新

- **快速找到該檔案：** 想要尋找最近使用過的檔案嗎？ 只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。

### <a name="word-feature-updates"></a>Word：功能更新

- **追蹤修訂、註解和即時共同作業的色彩會同步：** 我們產品中的修正現在可確保註解、追蹤修訂及共同作業者的游標會以相同色彩顯示。

- **快速找到該檔案：** 想要尋找最近使用過的檔案嗎？ 只要在 [檔案] > [常用] 頁面的 [搜尋] 方塊中輸入，就能找到所需的檔案。

### <a name="visio-feature-updates"></a>Visio：功能更新

- **將進度圖表匯出到 Word：** 在 Word 文件中自動新增圖表內容，如圖案和中繼資料。 然後，自訂文件來建立程序指導方針和操作手冊。 [深入了解](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="office-suite-feature-updates"></a>Office 套件：功能更新

- **新圖示：** 根據您的意見反應，我們新增了超過 300 個新圖示。 使用功能區 [插入] 索引標籤上的 [圖示] 按鈕，即可以找到它們。

- **隱私權控制：** 用於診斷資料的連線體驗的新增、更新及改良的控制項。 [深入了解](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新

- 修正導致將主旨顯示得極小的問題。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
- 修正不正確地將平假名和漢字中的日本新年號 "Reiwa" (令和) 識別為拼字錯誤或不合文法的運算式的問題。

- 修正以 SYSTEM 身分執行 Proxy 驗證時會封鎖 Office 更新的問題。

## <a name="version-1903-april-23"></a>版本 1903：4 月 23 日
版本 1903 (組建 11425.20244)

- 不同的錯誤 (bug) 和效能修正。

## <a name="version-1903-april-17"></a>版本 1903：4 月 17 日
*版本 1903 (組建 11425.20228)*

- 不同的錯誤 (bug) 和效能修正。

## <a name="version-1903-april-16"></a>版本 1903：4 月 16 日
*版本 1903 (組建 11425.20218)*

- 不同的錯誤 (bug) 和效能修正。

## <a name="version-1903-april-9"></a>版本 1903：4 月 9 日
*版本 1903 (組建 11425.20204)* 

- 安全性更新列於[此處](https://docs.microsoft.com/OfficeUpdates/microsoft365-apps-security-updates)

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
- 已修正 Lync (商務用 Skype) 中的問題，在其中，當任何線上會議具有 7 位以上參與者時，會議視窗可能會消失。

## <a name="version-1903-april-01"></a>版本 1903：4 月 1 日
*版本 1903 (組建 11425.20202)* 

### <a name="excel-feature-updates"></a>Excel：功能更新

- **Excel 的深入解析：** 深入分析可為廣泛的使用者帶來價值。 深入分析為資料分析提供較柔和的方法，並為其他人提供您的資料的不同觀點。 [深入了解](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)


- **提高內容的方便使用性：** 想要讓您的試算表更易於使用嗎？ 讓協助工具檢查程式來幫助您，您不需要自行處理。 按一下 [校閱] > [檢查協助工具] 試試看這個功能，我們會在狀態列上告訴您需要留意的部分。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新

- **更順暢的變形** 為圖形命名，進一步控制圖形的轉化效果。 [深入了解](https://support.office.com/article/9bc7f48ff-f152-4ee8-9081-d3121788024f)

- **提高內容的方便使用性：** 想要讓您的簡報更易於使用嗎？ 讓協助工具檢查程式來幫助您，您不需要自行處理。 按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。

- **當您可以重複使用時為什麼要重新打造？**  重複使用您所建立的投影片或其他人與您共用的投影片來以節省時間。

### <a name="excel-non-security-updates"></a>Excel：非安全性更新

- 修正 Excel 中合併衝突的問題，此問題會造成提示使用者重新開啟活頁簿以取得變更。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新

- 修正因第三方 SfB / Lync SDK 應用程式存在，而導致商務用 Skype 在回應聊天通知時停止回應的問題。
- 修正將特定剪貼簿內容貼到聊天時，應用程式當機的問題。
- 修正由其中一位通話專員接聽的通話佇列通話的「接受者」資訊無法顯示的問題。
- 已修正當 Teams 使用者加入商務用 Skype 會議時，通話圖示隱藏的問題。

### <a name="word-feature-updates"></a>Word：功能更新

- **提高內容的方便使用性：** 想要讓您的文件更易於使用嗎？ 讓協助工具檢查程式來幫助您，您不需要自行處理。 按一下 [校閱] > [檢查協助工具] 試試看這個功能 – 我們會在狀態列上告訴您需要留意的部分。

## <a name="version-1902-march-25"></a>版本 1902：3 月 25 日
*版本 1902 (組建 11328.20222)*

- 不同的錯誤 (bug) 和效能修正。

## <a name="version-1902-march-12"></a>版本 1902：3 月 12 日
*版本 1902 (組建 11328.20158)* 

- 不同的錯誤 (bug) 和效能修正。

## <a name="version-1902-march-4"></a>版本 1902：3 月 4 日
*版本 1902 (組建 11328.20146)* 

### <a name="access-feature-updates"></a>Access：功能更新

- **將索引標籤保留在資料庫物件上：** 能清楚看到使用中的索引標籤、輕鬆拖曳索引標籤來重新排列，只要按一下就能關閉資料庫物件。
- **使用更大的空間來縮放：** 加大 [縮放] 方塊、變更字型、記憶縮放。[深入了解](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel-feature-updates"></a>Excel：功能更新

- **使用 \@ 提及取得他人注意** 在註解中使用 @ 提及功能讓同事知道您需要他們提供建議。[深入了解](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)
- **更深入地探索您的資料：** 新的 [構想] 按鈕可尋找資料的模式，並使用模式建立更有智慧且個人化的建議。[深入了解](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)
- **隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。
- **能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-feature-updates"></a>Outlook：功能更新

- **在連續會議之間置入時間：** 將會議預設為提早 5-10 分鐘結束，讓出席者有時間休息，或在前往下一個地點。[深入了解](https://support.office.com/article/Schedule-a-meeting-with-other-people-5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F#BKMK_endmeetingsearly)
- **使用「大聲朗讀」聆聽您的電子郵件：** Outlook 可以大聲朗讀您的電子郵件，強調所朗讀的文字。若要開啟 [大聲朗讀]，請移至 [輕鬆存取] 設定。[深入了解](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新

- **輕鬆插入內嵌影片：** 想要在您的投影片中放入 Vimeo 或 YouTube 影片嗎？只要有影片頁面連結即可。[深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)
- **您來計算，格式設定交給我們** 我們能將難懂的手寫數學運算式變更為標準字元。只要選擇 [筆跡轉換數學]，然後選取您的手寫筆記，即可開始使用。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。
- **能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **大型檔案現在會以更快速度開啟：** 現在開啟儲存在 OneDrive 或 SharePoint 上的檔案時，會在背景下載影像、影片及其他大型元素。

### <a name="word-feature-updates"></a>Word：功能更新

- **隨時儲存變更：** 將檔案上傳至 OneDrive，確保所有的更新都會自動儲存。
- **了解自動儲存未開啟的原因！** 在自動儲存功能關閉時按一下 [自動儲存] 開關現在會將顯示一個有用的註標，說明自動儲存關閉的可能原因。造成自動儲存無法運作的唯一原因，就是文件不在 OneDrive 或 SharePoint 上，而我們將一鍵按鈕功能來方便移動文件。
- **能在套用篩選時插入 SVG：** Office 使用者現在可以在套用篩選的同時，插入 SVG。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
 
### <a name="office-suite-feature-updates"></a>Office 套件：功能更新

- **安裝 Microsoft Teams：** 在 Office 365 專業增強版的新安裝中，預設會安裝 Microsoft Teams。[深入了解](https://docs.microsoft.com/DeployOffice/teams-install)

## <a name="version-1901-february-12"></a>版本 1901：2 月 12 日
*版本 1901 (組建 11231.20174)* 

安全性更新列於[此處](microsoft365-apps-security-updates.md)

## <a name="version-1901-january-31"></a>版本 1901：1 月 31 日
*版本 1901 (組建 11231.20130)* 

### <a name="excel-feature-updates"></a>Excel：功能更新

- **利用註解共同作業：** 使用內建的回覆方塊，在試算表中進行交談。[深入了解](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)

### <a name="outlook-feature-updates"></a>Outlook：功能更新

- **他們會看到您的 meme：** 如果使用文字或靜態影像還不足以清楚表達您的想法，您可以使用動畫 GIF。[深入了解](https://support.office.com/article/114BB251-861F-41CD-B20F-7E7289630C5B)
 
### <a name="visio-feature-updates"></a>Visio：功能更新

- **資料流程圖上的 Double-Take：** 資料視覺化工具流程圖美觀的新版面配置，既清新、簡潔且更易於了解。 [深入了解](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **內建的 Azure 樣板：** 使用數十種 Azure 樣板來設計雲端應用程式或規劃架構。 [深入了解](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word-feature-updates"></a>Word：功能更新

- **為靜態文件注入動人的生命力：** 將文件轉變為在任何裝置上，均具有完美外觀的可互動、易分享的網頁。[深入了解](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

### <a name="office-suite-feature-updates"></a>Office 套件：功能更新

- **Office 第三方應用程式現在已使用 office.js api 擁有插入 SVG 支援的功能：** 亦稱為 Office 增益集的第三方應用程式現在擁有插入 SVG 的功能。使用者現在可以將個人的 SVG 集合連線至 Office。開發人員現在可以使用 Office.js API 來使用這項功能。


## <a name="version-1812-january-14"></a>版本 1812：1 月 14 日
*版本 1812 (組建 11126.20266)* 

僅含解決效能問題的非安全性更新。

## <a name="version-1812-january-8"></a>版本 1812：1 月 8 日
*版本 1812 (組建 11126.20196)* 

### <a name="project-non-security-updates"></a>Project：非安全性更新
- 已修正以下問題：核取甘特圖的 [要徑]、[落後] 和 [寬限時間] 長條圖樣式後，無法取消核取。

## <a name="version-1812-january-3"></a>版本 1812：1 月 3 日
*版本 1812 (組建 11126.20188)* 

### <a name="excel-feature-updates"></a>Excel：功能更新

- **在您工作的同時，持續執行協助工具檢查程式：** 不用一直開啟協助工具檢查程式，仍然可以追蹤文件內是否有協助工具問題。透過狀態列上的指示器 (與拼字檢查類似)，Excel 可在您工作的同時，標示出找到的協助工具問題。 

### <a name="outlook-feature-updates"></a>Outlook：功能更新

- **集中所有加密選項：** 只要前往 [選項] > [加密]，即可選擇要用來保護電子郵件訊息的方法。[深入了解](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)


### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新

- **運用筆跡製作精彩的投影片：** 將筆跡轉換成標準圖形和文字，然後從 PowerPoint 設計工具吸取智慧的投影片設計概念。[深入了解](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)
- **在您工作的同時，持續執行協助工具檢查程式：** 不用一直開啟協助工具檢查程式，仍然可以追蹤文件內是否有協助工具問題。透過狀態列上的指示器 (與拼字檢查類似)，PowerPoint 可在您工作的同時，標示出找到的協助工具問題。 

### <a name="word-feature-updates"></a>Word：功能更新

- **運用行聚焦，提高理解力：** 毫不費力地逐行瀏覽文件。調整焦點，在檢視畫面中一次放入一行、三行或五行。[深入了解](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)
- **在您工作的同時，持續執行協助工具檢查程式：** 不用一直開啟協助工具檢查程式，仍然可以追蹤文件內是否有協助工具問題。透過狀態列上的指示器 (與拼字檢查類似)，Word 可在您工作的同時，標示出找到的協助工具問題。

### <a name="visio-feature-updates"></a>Visio：功能更新

- **告別錯誤的 Excel 連結：** 找不到與 Data Visualizer 圖表連結的 Excel 活頁簿嗎？重新連結，就可繼續使用了。[深入了解](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

### <a name="office-suite-feature-updates"></a>Office 套件：功能更新

- **新增功能窗格：**[新增功能] 體驗已移至 [說明] 窗格，讓您可以更輕鬆地存取最新更新，並掌握最新消息。

## <a name="version-1811-december-11"></a>版本 1811：12 月 11 日
*版本 1811 (組建 11029.20108)* 

 ### <a name="excel-security-updates"></a>Excel：安全性更新 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8597)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8598)：Microsoft Excel 資訊洩漏弱點 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8627)：Microsoft Excel 資訊洩漏弱點 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8636)：Microsoft Excel 遠端程式碼執行弱點 

### <a name="outlook-security-updates"></a>Outlook：安全性更新 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8587)：Microsoft Outlook 遠端程式碼執行弱點 

### <a name="powerpoint-security-updates"></a>PowerPoint：安全性更新 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8628)：Microsoft PowerPoint 遠端程式碼執行弱點 


## <a name="version-1811-november-27"></a>版本 1811：11 月 27 日
*版本 1811 (組建 11029.20079)* 

### <a name="access-feature-updates"></a>Access：功能更新

- **繪製成黑色、繪製成灰色：** 依照您的喜好變更 Access 的外觀。有四個佈景主題可供選擇：彩色、深灰色、黑色或白色。[深入了解](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)

### <a name="outlook-feature-updates"></a>Outlook：功能更新

- **縮放與搖桿：** 選擇要用於所有郵件的預設值，而不用在每次讀取郵件時調整 [縮放]。[深入了解](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **在移動郵件時繼續作業：** Outlook 現在會在背景中移動郵件，因此，在資料夾之間移動大量郵件時您可以繼續作業。
- **改善焦點收件匣的開啟和關閉體驗：** 對於沒有使用焦點收件匣的客戶，我們已在所有資料夾的郵件清單中恢復 [未讀取] 索引標籤。我們也新增了以旗標為依據的排序功能，讓您能更輕鬆地找到加上旗標的項目。最後，焦點收件匣有更好的互動搜尋模型：焦點收件匣會保留到使用者開始進行搜尋，然後我們在搜尋完成後顯示「結果」文字為止。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新

- **在印出的講義上看到投影片編號：** 將投影片編號新增至講義的列印複本。[深入了解](https://support.office.com/article/91c62c83-9032-497c-ab76-cae8f3e1a402)

### <a name="office-suite-feature-updates"></a>Office 套件：功能更新

- **利用 [資訊位置] 中新公開的按鈕共用及上傳文件：**[共用]、[將路徑複製到剪貼簿] 及 [開啟檔案位置] 按鈕先前只能在文件儲存路徑後面存取。您現在可以在 [資訊位置] 中清楚地看到這些按鈕！瀏覽至 [檔案] > [資訊] 時通常會看到這些新按鈕。


## <a name="version-1810-november-13"></a>版本 1810：11 月 13 日
*版本 1810 (組建 11001.20108)* 

### <a name="excel-security-updates"></a>Excel：安全性更新

-   [CVE-2018-8574](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8574)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8577](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8577)：Microsoft Excel 遠端程式碼執行弱點 

### <a name="outlook-security-updates"></a>Outlook：安全性更新 

-   [CVE-2018-8522](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8522)：Microsoft Outlook 遠端程式碼執行弱點 
-   [CVE-2018-8524](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8524)：Microsoft Outlook 遠端程式碼執行弱點 
-   [CVE-2018-8558](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8558)：Microsoft Outlook 資訊洩漏弱點 
-   [CVE-2018-8576](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8576)：Microsoft Outlook 遠端程式碼執行弱點 
-   [CVE-2018-8579](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8579)：Microsoft Outlook 資訊洩漏弱點 
-   [CVE-2018-8582](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8582)：Microsoft Outlook 遠端程式碼執行弱點 

### <a name="project-security-updates"></a>Project：安全性更新 

-   [CVE-2018-8575](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8575)：Microsoft Project 遠端程式碼執行弱點 

### <a name="word-security-updates"></a>Word：安全性更新  

-   [CVE-2018-8573](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8573)：Microsoft Word 遠端程式碼執行弱點 

### <a name="skype-for-business-security-updates"></a>商務用 Skype：安全性更新 

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8546)：Microsoft 商務用 Skype 阻絕服務弱點 

 ### <a name="project-non-security-updates"></a>Project：非安全性更新

 - 修正此問題：將專案儲存/發佈到 Project Online 時，狀態列不一定會更新至最新狀態。
 - 修正此問題：如果您使用新的新式體驗 SharePoint 文件庫上的 Project 檔案，「需要取出」和「唯讀」動作沒有正確執行。


## <a name="version-1810-october-29"></a>版本 1810：10 月 29 日
*版本 1810 (組建 11001.20074)* 

### <a name="excel-feature-updates"></a>Excel：功能更新 

- **使用註解共同作業：** 使用內建的回覆方塊，在試算表中進行交談。[深入了解](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **股票報價唾手可得：** 擷取最新的股價、價格變化及其他新的股票資料類型。地理位置也有新的資料類型。[深入了解](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)
- **顯示圖片後面的內容：** 將圖片放在工作表中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **在資料編輯列中輕鬆編輯：** 您現在可以使用 CTRL + A 來選取儲存格或資料編輯列中的文字。另外也改善了 Emoji 和其他複雜字元的支援。[深入了解](https://support.office.com/article/402d8c2a-354c-4690-bacf-1c319c4ec2fb)

### <a name="outlook-feature-updates"></a>Outlook：功能更新 

- **排程助理員中的人員建議：** 在您排定會議時查看對要新增之出席者的建議。不再來回切換排程助理員與收件者。[深入了解](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **預留房間更加輕鬆：** 使用多個會議室清單尋找會議室 - 以及切換清單，而不會失去您已選取的會議室。
- **停止看到過去事件的提醒：** 您可以設定行事曆，在事件結束之後自動關閉事件的提醒。[深入了解](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新 

- **顯示圖片後面的內容：** 將圖片放在投影片中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **新的校對工具：** 不必對您的文筆沒信心。PowerPoint 現在提供文法及書寫建議。
- **您素描，我修飾：** 我們可將手繪文字和形狀變為更精緻的圖表。只需選取您的筆跡線條即可開始。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

### <a name="word-feature-updates"></a>Word：功能更新 

- **顯示圖片後面的內容：** 將圖片放在文件中、挑選您的預設，並觀看透明度變更。就這麼簡單！[深入了解](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **生動地觀看您的文件：** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在整個頁面橫衝直撞。[深入了解](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)

### <a name="access-feature-updates"></a>Access：功能更新 
- **功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)

### <a name="publisher-feature-updates"></a>Publisher：功能更新 
- **功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)

### <a name="project-feature-updates"></a>Project：功能更新 
- **功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)

### <a name="visio-feature-updates"></a>Visio：功能更新 
- **功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)


## <a name="version-1809-october-16"></a>版本 1809：10 月 16 日
*版本 1809 (組建 10827.20181)* 

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新 
-  已修正各種效能問題。


## <a name="version-1809-october-9"></a>版本 1809：10 月 9 日
*版本 1809 (組建 10827.20150)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8502](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8502)：Microsoft Excel 遠端程式碼執行弱點 

### <a name="outlook-security-updates"></a>Outlook：安全性更新 
-   [ADV180026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180026)：Microsoft Office 深度防禦更新 

### <a name="powerpoint-security-updates"></a>PowerPoint：安全性更新 
-   [CVE-2018-8501](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8501)：Microsoft PowerPoint 遠端程式碼執行弱點

### <a name="word-security-updates"></a>Word：安全性更新 
-   [CVE-2018-8504](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8504)：Microsoft Word 遠端程式碼執行弱點 
-   [ADV180026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180026)：Microsoft Office 深度防禦更新 

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新 
-   [CVE-2018-8432](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8432)：Microsoft Graphics 元件遠端程式碼執行弱點 


## <a name="version-1809-september-27"></a>版本 1809：9 月 27 日
*版本 1809 (組建 10827.20138)*

### <a name="excel-feature-updates"></a>Excel：功能更新
- **快速查閱** 我們已加速 VLOOKUP、HLOOKUP、MATCH 的計算速度，讓您能更快得到答案。[深入了解](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)
- **呼叫所有取得與轉換粉絲** 如果您經常使用取得與轉換，您會很高興知道我們已改善資料行來源範例功能。此外，也已改善許多連接器。[深入了解](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)

### <a name="outlook-feature-updates"></a>Outlook：功能更新
- **查看即將推出的功能** 在發行新的使用者體驗之前先行試用，讓我們知道您的想法。[深入了解](https://support.office.com/article/d4b7db49-b4e0-4f98-a0dc-156952e551e2)
- **查看安全連結背後的 URL：** 安全連結可保護您防範在電子郵件中收到但隱藏原始 URL 的惡意 URL。 若要查看原始 URL，請將滑鼠游標移到 URL 上。 需要進階威脅防護授權。 [深入了解](https://products.office.com/exchange/advance-threat-protection)
- **取得搜尋拼字建議** 在執行搜尋之後，Outlook 將提供拼字更正的建議搜尋查詢。
- **功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
- **生動地觀看您的投影片** 插入動畫 3D 圖形，來查看心跳、行星軌道，以及暴龍在整個畫面橫衝直撞。[深入了解](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)

### <a name="word-feature-updates"></a>Word：功能更新
- **使用 \@mentions 取得其注意** 在註解中使用 @mentions，讓同事知道您何時需要其輸入。[深入了解](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)
- **功能區圖示有了嶄新的外觀** 別擔心，一切照舊，而且它們在各種尺寸的螢幕上看起來都很棒。[深入了解](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **方程式編輯器轉換程式** 此轉換程式可讓使用者將使用 Microsoft 方程式編輯器建立的方程式轉換為 Office 數學 ML 格式，以啟用編輯。
- **為靜態文件注入動人的生命力** 將文件轉變為在任何裝置上，均具有完美外觀的可互動、易分享的網頁。 [深入了解](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

## <a name="version-1808-september-11"></a>版本 1808：9 月 11 日
*版本 1808 (組建 10730.20102)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8331)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8429)：Microsoft Excel 資訊洩漏弱點

### <a name="word-security-updates"></a>Word：安全性更新
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8430)：Windows PDF 遠端程式碼執行弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8332)：Win32k 圖形遠端程式碼執行弱點


## <a name="version-1808-september-5"></a>版本 1808：9 月 5 日
*版本 1808 (組建 10730.20088)*

### <a name="access-feature-updates"></a>Access：功能更新
 - **重新整理、重新連結或移除連結的資料表** 更新的連結資料表管理員是用於管理所有資料來源與連結資料表的位置。[深入了解](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="outlook-feature-updates"></a>Outlook：功能更新
 - **關閉會議的轉寄** 防止出席者將您的會議轉寄給其他人。只需移至功能區，按一下 [回應選項] 即可。[深入了解](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
 
### <a name="visio-feature-updates"></a>Visio：功能更新
 - **在下一個圖表中享受圖示時刻** 從 26 個圖案中挑選，其中的圖示表示分析、藝術、慶典、臉、運動和其他。 
 - **從 Visio 圖形建立 Word 文件：** 自動將圖表內容 (包括圖形和中繼資料) 新增至 Word 文件。然後自訂文件以建立程序指導方針和操作手冊。[深入了解](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)
 - **Visio 與 Power BI：更好的搭配** 只需按幾下，即可將您的 Visio 圖表轉換成互動式 Power BI 視覺效果。[深入了解](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

 ### <a name="project-feature-updates"></a>Project：功能更新
 - **在工作面板卡片上查看詳細資訊** 當單獨標題不能訴說故事時，請自訂您的工作面板卡片，以顯示所有最重要的詳細資料。[深入了解](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-  已修正 Excel 中的問題，其中標示使用者選取以進行複製之儲存格範圍的虛線，並不會消失，而且甚至在後續的使用者作業 (例如貼上) 之後仍會保留在剪貼簿中。 

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
 - 對於一些已設定多個 Exchange 帳戶的使用者，已解決導致「按一下以檢視其他...」連結從搜尋結果清單中遺失的問題。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
 - 已修正導致更新安裝在特定情況下需要很長時間的問題。
 
### <a name="lync-non-security-updates"></a>Lync：非安全性更新
 - 已修正阻止在 IM 訊息中顯示表情符號的問題。 


## <a name="version-1807-august-14"></a>版本 1807：8 月 14 日
*版本 1807 (組建 10325.20118)*

### <a name="access-security-updates"></a>Access：安全性更新
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8375)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8379)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8382)：Microsoft Excel 資訊洩漏弱點 

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [ADV180021](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180021)：Microsoft Office 深度防禦更新 

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8378)：Microsoft Office 資訊洩漏弱點 

## <a name="version-1807-july-25"></a>版本 1807：7 月 25 日
*版本 1807 (組建 10325.20082)*

### <a name="outlook-feature-updates"></a>Outlook：功能更新
- **Outlook 增益集警告：** 有時 Outlook COM 增益集會發生問題，讓其餘 Outlook 功能變慢。這些問題可能是因為以下的事件延遲：在 Outlook 資料夾之間進行切換、新的電子郵件送達、開啟行事曆項目等等。當這類問題發生時，Outlook 會在通知列中顯示警告。
- **從 Outlook 提醒對話方塊加入小組會議：** 當 Outlook 提醒使用者有即將來臨的會議時，如果即將來臨的會議是小組線上會議，則它會顯示 [線上加入] 按鈕。這個動作與從 Outlook [提醒] 對話方塊加入商務用 Skype 會議的體驗類似。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
 - **超連結色彩：** 超連結不再只是藍色。套用您喜歡的任何字型色彩。[深入了解](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)

### <a name="visio-feature-updates"></a>Visio：功能更新
 - **從 Visio 圖形建置 Word 文件：** 自動將圖表內容 (包括圖形和中繼資料) 新增至 Word 文件。然後自訂文件以建立程序指導方針和操作手冊。[深入了解](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="word-feature-updates"></a>Word：功能更新
 - **使用 IRM 追蹤修訂：** 您現在可於 Word 中，在不需要完全控制使用權限的受 IRM 保護文件中使用「追蹤修訂」功能。

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
 - 修正了防止部分使用者開啟受 IRM 保護的文件和電子郵件 (由其他組織中的人員與他們共用) 的一些問題。

## <a name="version-1806-july-17"></a>版本 1806：7 月 17 日
*版本 1806 (組建 10228.20134)*

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
 - 修正一些效能問題。

## <a name="version-1806-july-10"></a>版本 1806：7 月 10 日
*版本 1806 (組建 10228.20104)*

### <a name="access-security-updates"></a>Access：安全性更新
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 竄改弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 遠端程式碼執行弱點

## <a name="version-1806-june-25"></a>版本 1806：6 月 25 日
*版本 1806 (組建 10228.20080)*

### <a name="excel-feature-updates"></a>Excel：功能更新
- **改善儲存格和資料編輯列編輯：** 您現在可以使用 CTRL + A 來選取儲存格或資料編輯列中的文字。另外也改善了 Emoji 和其他複雜字元的支援。[深入了解](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **改善 SVG 支援：** 您可以將已套用篩選的 SVG 插入。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-feature-updates"></a>Outlook：功能更新
- **定期預設：** 在 [定期約會] 對話方塊中 (「定期範圍」下)，「結束日期」是預設設定 (而非「沒有結束日期」) 及列出的第一個設定，且會設定預設的結束日期。
- **改善協助工具檢查程式︰** 協助工具檢查程式已更新對國際標準與建議的支援，以使您的郵件更易於存取。[深入了解](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)


### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
- **改善 SVG 支援：** 您可以將已套用篩選的 SVG 插入。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **使用手寫筆為投影片撰寫標題：** 使用手寫筆輸入標題，並觀看 PowerPoint 將它轉換成文字。[深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

### <a name="project-feature-updates"></a>Project：功能更新
 - **使用最近的儲存位置保持組織：** 專案會保存您已儲存其他專案位置的持續清單。當您準備好要儲存專案時，只需選擇其中一個您最近的儲存位置，就能繼續進行您一天的工作。
 - **管理短期衝刺的全新方法：** 採取敏捷方式來使用工作面板。隨著專案的發展，請移至 [管理短期衝刺] 來新增或移除短期衝刺。


### <a name="project-non-security-updates"></a>Project：非安全性更新
 - 修正此問題：儲存主專案中的子專案時會發生失敗。

### <a name="visio-feature-updates"></a>Visio：功能更新
 - **更多樣板、更多圖示、更多選項：** 我們新增了 26 個樣板，包括「分析」、「藝術」、「慶祝」、「表情」、「位置」、「醫療」、「自然」、「人物」、「運動」、「天氣與季節」等等。

### <a name="word-feature-updates"></a>Word：功能更新
 - **改善 SVG 支援：** 您可以將已套用篩選的 SVG 插入。[深入了解](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)



## <a name="version-1805-june-13"></a>版本 1805：6 月 13 日
*版本 1805 (組建 9330.2124)*

### <a name="outlook-non-security-updates"></a>Outlook 非安全性更新
 - 修正當應用程式呼叫 MAPI API 時會造成當機的問題。



## <a name="version-1805-june-12"></a>版本 1805：6 月 12 日
*版本 1805 (組建 9330.2118)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 遠端程式碼執行弱點

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 提高權限弱點

### <a name="outlook-non-security-updates"></a>Outlook 非安全性更新

- 修正當應用程式呼叫 MAPI API 時會造成當機的問題。

### <a name="project-non-security-updates"></a>Project 非安全性更新

- 修正此問題：當您透過主要專案使用子專案時，系統阻止您儲存子專案。

## <a name="version-1805-may-24"></a>版本 1805：5 月 24 日
*版本 1805 (組建 9330.2087)*

### <a name="outlook-non-security-updates"></a>Outlook 非安全性更新
 - 修正 Outlook 在使用 iCloud 增益集時會當機的問題。
 


## <a name="version-1805-may-23"></a>版本 1805：5 月 23 日
*版本 1805 (組建 9330.2078)*

### <a name="access-feature-updates"></a>Access：功能更新
 - **使用新圖表以視覺化方式呈現資料：** 從 11 個圖表中選擇，並將其中一個新增至您的表單和報告，更有效地以視覺化方式呈現資料並進行明智的決策。[深入了解](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)

### <a name="excel-feature-updates"></a>Excel：功能更新
 - **在編輯時與共同作者交談：** 藉由與共同作者聊天，即可更有效率地共同作業而不需要離開 Excel。請注意，某些地區不提供這項功能。[深入了解](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)

### <a name="outlook-feature-updates"></a>Outlook：功能更新
 - **免操作輸入：** 使用您的語音直接聽寫以建立電子郵件。不需輸入。[深入了解](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
 - **檢視 3 個時區：** 需要跨時區排程會議嗎？將多個時區新增至您的行事曆，輕鬆查看每個人的時程，並挑選出所有人都可以的時間。[深入了解](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
 - **輕鬆共用行事曆：** 共用行事曆更加簡單，而且從 Outlook Desktop 共用的行事曆現在也可在 Outlook Mobile 中使用。[深入了解](https://support.office.com/article/353ed2c1-3ec5-449d-8c73-6931a0adab88)

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
- 將共用行事曆邀請中的用語從「開啟此行事曆」變更為「接受」。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
 - **在編輯時與共同作者交談：** 藉由與共同作者聊天，即可更有效率地共同作業而不需要離開 PowerPoint。[深入了解](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)
 - **免操作輸入：** 使用您的語音直接聽寫以建立簡報。不需輸入。[深入了解](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
 - **Microsoft 表單：** 在投影片上進行測驗或問卷。Office 會收集並儲存存儲您的回應。[深入了解](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

### <a name="project-non-security-updates"></a>Project：非安全性更新
 - 修正 Project 第一次在 Project Web 應用程式中儲存專案時可能會當機的問題。


### <a name="visio-feature-updates"></a>Visio：功能更新
 - **入門圖表：** 組織圖、腦力激盪和 SDL 範本有新的入門圖表可讓您快速啟動並執行。

### <a name="word-feature-updates"></a>Word：功能更新
 - **在編輯時與共同作者交談：** 藉由與共同作者聊天，即可更有效率地共同作業而不需要離開 Word。[深入了解](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)
 - **免操作輸入：** 使用您的語音直接聽寫以建立文件。不需輸入。[深入了解](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
 - **編輯當然是使用筆跡編輯：** 使用畫筆透過單一筆劃來分割或加入文字、新增新的一行，或插入文字。[深入了解](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)



## <a name="version-1804-may-14"></a>版本 1804：5 月 14 日
*版本 1804 (組建 9226.2156)*

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
- 修正此問題：開啟應用程式時，使用者可能會看到以安全模式啟動的訊息，然後應用程式無法開啟。



## <a name="version-1804-may-8"></a>版本 1804：5 月 8 日
*版本 1804 (組建 9226.2126)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 資訊洩漏弱點

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全性功能略過的弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 遠端程式碼執行弱點


## <a name="version-1804-april-25"></a>版本 1804：4 月 25 日
*版本 1804 (組建 9226.2114)*

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **聽取您的電子郵件：** Outlook 可以大聲念出您的電子郵件，並將所念到的文字醒目提示。[深入了解](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
-   **絕不錯過任何提醒：** 將提醒設定為在您正在工作的視窗上彈出。否則，Outlook 會在工作列中閃爍，以引起您的注意。[深入了解](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
-   **將刪除的郵件標示為已讀取：** 您現在可以將任何已刪除的郵件標示為已讀取。請移至 [檔案] \> [選項] \> [郵件] \> [其他] 來選擇使用。
-   **加密選項：** Office 365 郵件加密使用者可以加密郵件，並將其傳送給組織內外的任何人。建立郵件時，加密選項會出現在 [選項] \> [權限] 底下。 [深入了解](https://aka.ms/omeoverview)

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **轉換筆跡：** 擷取草草寫下的筆記和繪圖，並將其轉換為可供閱讀的文字和簡潔的圖形，以建立精美的簡報。 [深入了解](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="project-feature-updates"></a>Project：功能更新
-   **工作面板篩選：** 篩選重要資源或摘要任務，以簡化您的工作面板。
-   **從工作面板設定完成百分比：** 針對每個資料行選擇完成百分比，然後透過拖放更新工作完成度。
-   **短期衝刺瀏覽：** 從某個短期衝刺檢視切換為另一個檢視，並快速地在短期衝刺之間移動工作。

### <a name="word-feature-updates"></a>Word：功能更新
-   **找出相關的校訂問題並加以修正：**[編輯器] 窗格現在會顯示您的文件中所找到的校訂問題概觀，所以焦點會放在修正與您最相關的問題。


## <a name="version-1803-april-11"></a>版本 1803：4 月 11 日
*版本 1803 (組建 9126.2152)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 遠端程式碼執行弱點

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：多個使用者在相同簡報上共同撰寫會導致投影片母片不正確重複。
-   修正此問題：將儲存在 OneDrive 中的檔案開啟時，結束受保護的檢視時會導致 PowerPoint 當機。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正與 TLS 1.2 支援相關的問題。

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正造成顯示記憶體不足訊息的問題。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 遠端程式碼執行弱點
-   **基於安全原因已封鎖 Flash、Silverlight、Shockwave 控制在 Office 中啟動：** 基於安全原因，Windows 上新組建的 Microsoft Office for Office 365 會封鎖 Flash、Silverlight、Shockwave 控制的啟動。請看 [這裡](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)和 [這裡](https://support.office.com/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1)深入了解。

## <a name="version-1803-march-27"></a>版本 1803：3 月 27 日
*版本 1803 (組建 9126.2116)*

### <a name="excel-feature-updates"></a>Excel：功能更新
-   **Microsoft Translator：** 使用 Microsoft Translator 可將單字、片語或句子翻譯成另一種語言。您可以從功能區中的 [校閱] 索引標籤使用此功能。

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：快速列印附加至 Outlook 電子郵件的 Excel 活頁簿可能會列印不出來。
-   修正此問題：按一下超連結可能會造成 Excel 當機。
-   修正此問題：使用 cube 函式會造成 Excel 當機。

### <a name="onedrive-for-business-non-security-updates"></a>商務用 OneDrive：非安全性更新
-   修正此問題：商務用 OneDrive (Groove.exe) 會在 [工作管理員] 中耗用相當於一個 CPU 核心的 CPU (例如，4 核心 CPU 的 25%) 來延長一段時間。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **密件副本 (Bcc) 警告：** 如果您對先前使用密件副本的郵件選擇 [全部回覆]，將會顯示警告訊息。
-   **更聰明的 [收件者：] 行：** 當您按一下 [收件者：] 來撰寫郵件時，我們會建議您可能要選擇的收件者。此外，還可以看到收件者相片，讓您知道要傳送的對象是正確的。 

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **Microsoft Translator：** 使用 Microsoft Translator 可將單字、片語或句子翻譯成另一種語言。您可以從功能區中的 [校閱] 索引標籤使用此功能。
-   **改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。 [深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正此問題：在會議中以選取 [Skype 通話] 的方式新增使用者會產生錯誤。
-   如果已將 Skype 會議室新增為位置，且會議已包含小組會議座標，請移除要求使用者將 Skype 座標新增至會議的提示。

### <a name="visio-feature-updates"></a>Visio：功能更新
-   **改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。 [深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="word-feature-updates"></a>Word：功能更新
-   **改善了對高解析度顯示器的支援**：現在，如果您使用多部監視器或筆記型電腦基座，Office 應用程式在每個顯示器上都會順暢清晰地呈現，即使顯示器使用不同的縮放設定亦然。 [深入了解](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)


## <a name="version-1802-march-13"></a>版本 1802：3 月 13 日
*版本 1802 (組建 9029.2253)*

### <a name="access-security-updates"></a>Access：安全性更新
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 遠端程式碼執行弱點

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全性功能略過

### <a name="word-security-updates"></a>Word：安全性更新
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 資訊洩漏弱點


## <a name="version-1802-february-26"></a>版本 1802：2 月 26 日
*版本 1802 (組建 9029.2167)*

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **了解要參與會議的人員：** 即使您不是召集人，也可以看到其他人對於會議邀請的回應。
-   **輕鬆地排序您的電子郵件：** 由於您的意見反應，我們已為不使用 [焦點收件匣] 的使用者，重新加入了郵件清單上方的排序功能和 [未讀取] 篩選器。

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正此問題：在工作階段中設定多個基準，會讓 MOD\_DATE 值都設為相同。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正此問題：即使 UseLocationForE911Only 設定為 true，也會填入位置。
-   修正此問題：使用名冊中的「使用會議中心呼叫」選項來邀請使用者時，商務用 Skype 會當機。
-   修正此問題：建立商務用 Skype 會議時，在終端機伺服器上運行的Outlook 會凍結。
-   將 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的預設值變更為 TRUE。

### <a name="visio-feature-updates"></a>Visio：功能更新
-   **內建資料庫模型圖表：** 使用新的資料庫模型圖表範本，將您的資料庫精確地建模為 Visio 圖表。不需要增益集。
-   **更多商用圖表的樣板：** 使用新式圖形，以文氏圖表來比較和對比資料；或繪製循環、矩陣或金字塔圖表來表達您的想法。
-   **讓您的圖表和來源能保持同步：** 當您在 Visio 中編輯 [資料視覺化工具] 圖表時，可以選擇用最新的圖表內容來更新連結的 Excel 來源資料。


## <a name="version-1801-february-13"></a>版本 1801：2 月 13 日
*版本 1801 (組建 9001.2171)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 遠端程式碼執行弱點

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 提高權限弱點
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 記憶體損毀弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 資訊洩漏弱點


## <a name="version-1801-february-7"></a>版本 1801：2 月 7 日
*版本 1801 (組建 9001.2144)*

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正下列問題：如果您的編輯語言是日文、中文或韓文，則當您嘗試在 [首頁] 索引標籤上選取新字型時，或當編輯時，Excel 可能會凍結。


## <a name="version-1801-february-1"></a>版本 1801：2 月 1 日
*版本 1801 (組建 9001.2138)*

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正此問題：將實際工時從 [儲存為共用] 工作階段中移除之後，[實際工時] 仍然顯示在報表中。
-   修正此問題：在德文版中進行排程時，要使用 [週] 日期格式時會傳回錯誤。
-   修正此問題：在編輯 [排程網頁組件] 的完成日期時，工作保持為每天 8 小時，而不是隨著時間分配。
-   修正此問題：在非預期的位置繪製「進度點形狀」。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正此問題：當會議處於全螢幕模式時，[其他選項] 和 [邀請其他人] 按鈕會隱藏。
-   修正此問題：當您想要加入會議時，P2P 音訊撥號視窗或電話會議視窗會變成透明。
-   修正此問題：即將開始的 Skype 會議未顯示在 [會議] 索引標籤。
-   修正此問題：當商務用 Skype 配置為無音訊加入會議，新增音訊至會議時不會將音訊新增至現有的會議，反而是向使用者本身啟動新的 P2P 撥號。
-   修正此問題：當使用者按下 Outlook 會議邀請的 [加入 Skype 會議] 連結時，會收到錯誤訊息 [找不到此 Skype 會議]。


## <a name="version-1712-january-30"></a>版本 1712：1 月 30 日
*版本 1712 (組建 8827.2179)*

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：當 Excel 最小化時，開啟活頁簿時捲軸會遺失。

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：當搜尋範圍限定為 [所有信箱] 時，搜索會失敗並顯示 [找不到相符項目]。


## <a name="version-1712-january-17"></a>版本 1712：1 月 17 日
*版本 1712 (組建 8827.2148)*

### <a name="excel-feature-updates"></a>Excel：功能更新
-   **將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。
-   **取消選取儲存格：** 在工作表中進行選取，並取消選取不小心按到的儲存格而不必重新開始。

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：在 [檔案總管] 中的檔案名稱上按兩下以開啟多個活頁簿時，活頁簿參照會失敗。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。
-   **Office 365 群組的改善︰** 您可以在群組訊息上按兩下，開啟其個別視窗，這讓您更加容易閱讀和回覆群組對話。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **3D 動畫：** 透過輕輕搖晃或跳躍及旋轉等動畫，讓 3D 模型栩栩如生。
-   **將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   在快顯通知 UI 中為撥入的 PSTN 通話新增來電轉接按鈕。
-   當 ChatDefaultClient 和 CallDefaultClient 設定至 Teams 時，通知使用者來電與交談正在傳送至 Teams。
-   當使用者不在會議中並停用商務用 Skype 時，使用者狀態會顯示為 [離線]，且會議加入體驗會設為 [原生有限用戶端]。
-   商務用 Skype 最小化至通知區域時，停用 [開啟] 和 [結束] 以外的所有選項。 
-   與 Aries 電話配對且啟用 RedirectClient 時，隱藏新來電和對話。
-   修正此問題：日期格式非美國格式 (mm/dd/yy) 時，在 PChat 中依日期搜尋訊息會失敗。
-   修正此問題：當 EnableExternalP2PFileTransfer 原則設為 false 時，使用者仍然可以在會議中附加檔案。

### <a name="visio-feature-updates"></a>Visio：功能更新
-   **使用 Excel 範本匯出至 Visio 圖表：** 搶先使用 Visio 流程表。在其中一個程序圖 Excel 範本中輸入資料，並匯出至 Visio 以自動建立圖表。需要 Visio Pro for Office 365。

### <a name="word-feature-updates"></a>Word：功能更新
-   **將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。


## <a name="version-1711-january-9"></a>版本 1711：1 月 9 日
*版本 1711 (組建 8730.2175)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 遠端程式碼執行弱點
-   [Advisory 170021](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點

### <a name="word-security-updates"></a>Word：安全性更新
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0792)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0794)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0798)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0801)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0802)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0804)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0805)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0806)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0807)：Microsoft Word 遠端程式碼執行弱點
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0812)：Microsoft Word 記憶體損毀弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 遠端程式碼執行弱點
-   [Advisory 180003](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180003)：Microsoft Office 深度防禦更新


## <a name="version-1711-january-2"></a>版本 1711：1 月 2 日
*版本 1711 (組建 8730.2165)*

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：以程式設計方式建立樞紐分析表，接著以程式設計方式重新整理，會造成 Excel 當機。
-   修正此問題：以程式設計方式呼叫 Workbook.Open() 可能會造成 Excel 當機。

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：移除文件屬性和個人資訊會造成儲存至 SharePoint 失敗。

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正此問題：VBA 程式碼從專案中遺失。



> [!NOTE]
> 如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。
