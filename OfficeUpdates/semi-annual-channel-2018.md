---
title: 2018 年半年通道版本的版本資訊
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 7/17/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2018 年 Office 365 專業增強版半年通道版本的版本資訊
ms.openlocfilehash: c986913ae1c92e6f8e5e8992c71484ef141fc976
ms.sourcegitcommit: 8abc8240e5b4b922070ac9498ed5ac311732e4b2
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/17/2018
ms.locfileid: "20435672"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2018"></a>2018 年半年通道版本的版本資訊

這些版本資訊會提供 2018 年 Office 365 專業增強版的半年通道更新所含新功能、安全性更新和非安全性更新的相關資訊。 

> [!NOTE]
> - 下面也會提供 Visio Pro for Office 365 和 Project Online 桌面用戶端新功能、安全性更新和非安全性更新的相關資訊。
> - 此資訊也適用於 Office 365 商務版，這是隨附一些 Office 365 方案 (例如，商務進階版) 的 Office 版本。
> - 在 2018 年 1 月以前，半年通道的舊名為順延通道。

## <a name="version-1803-july-10"></a>版本 1803：7 月 10 日
*版本 1803 (組建 9126.2259)*

### <a name="access-security-updates"></a>Access：安全性更新
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 遠端程式碼執行弱點
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點 

### <a name="access-non-security-updates"></a>Access：非安全性更新
-   修正此問題：開啟 Access 執行階段應用程式 (.accde 檔案) 會導致「無法辨認此資料庫格式」錯誤訊息，且應用程式不會開啟。
-   修正此問題：嘗試在文字方塊或下拉式方塊中選取文字似乎會選取所有文字，而不是表示選取範圍。

### <a name="excel-feature-updates"></a>Excel：功能更新
-   **Microsoft Translator：** 使用 Microsoft Translator 可將單字、片語或句子翻譯成另一種語言。您可以從功能區中的 [校閱] 索引標籤使用此功能。
-   **將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。
-   **取消選取儲存格：** 在工作表中進行選取，並取消選取不小心按到的儲存格而不必重新開始。
-   **快速存取您的網站和群組︰** 您可以使用 [檔案] 功能表，使用儲存在您常用的網站和群組中的文件。
-   **數位鉛筆：** 使用新的鉛筆紋理手寫或繪製出您的創意。只需傾斜即可使用支援的數位鉛筆進行陰影處理。
-   **LinkedIn 功能設定：** 移至 [檔案] \> [選項] \> [一般]，以控制 LinkedIn 功能是否要顯示在您的 Office 應用程式中。[深入了解](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **3D 模型：** 使用 3D 來增加活頁簿的視覺效果和創意影響。輕鬆插入 3D 模型，然後將其旋轉 360 度。 [深入了解](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **新的筆跡效果：** 使用金屬畫筆和筆跡效果 (如彩虹、星空、熔岩、海洋、黃金、銀等) 來展現您的想法。
-   **共用檔案 UI：** 對於商務用 OneDrive 或 SharePoint 檔案，按一下功能區右上角的 [共用] 按鈕，或移至 [檔案] \> [共用] 可啟動經簡化並改良過的 [共用] 對話方塊。對於新的或儲存在本機的檔案，該 UI 可讓使用者輕鬆地將檔案上傳至 OneDrive 以啟動共同作業。
-   **封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **有用的聲音可改善協助工具：** 開啟音訊提示可在作業時一面引導您。可在 [檔案] \> [選項] \> [輕鬆存取] 中找到此功能。無需增益集。 [深入了解](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **依帳戶的檔案位置：** 開啟或儲存檔案時，位置清單會依照與其相關聯的帳戶整理。
-   **畫筆自訂：** 針對筆跡選擇畫筆和螢光筆的個人集合。您的自訂集可在您所有的 Windows 電腦上使用。

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11877)：Microsoft Excel 安全性功能略過的弱點
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11878)：Microsoft Excel 記憶體損毀弱點
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11884)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全性功能略過
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8147)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8148)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8162)：Microsoft Excel 遠端程式碼執行弱點 
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8163)：Microsoft Excel 資訊洩漏弱點 
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0907)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全性功能略過
-   [Advisory 170021](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新

### <a name="excel-non-security-updates"></a>Excel：非安全性更新

-   修正此問題：在日期儲存格格式使用日本紀元日曆時顯示錯誤年份。
-   當資料匯入 Excel 資料模型中，負值或零的輸入值會造成錯誤。此修正會將此類的值匯入為零。
-   修正 Excel 樞紐分析表中的群組 (或取消群組) 作業有時候會觸發當機的問題。
-   修正此問題：在圖表上動作可能會造成 Excel 當機。
-   修正此問題：部分使用者不小心停用 Power View 增益集。
-   修正此問題：在文件復原期間建立的暫時自動復原檔案永遠不會清除。
-   修正此問題：Excel 在從 SharePoint Online 開啟檔案時損毀。
-   修正此問題：快速列印附加至 Outlook 電子郵件的 Excel 活頁簿可能會列印不出來。
-   修正此問題：按一下超連結可能會造成 Excel 當機。
-   修正此問題：使用 cube 函數會造成 Excel 當機。
-   修正此問題，列印或預覽列印時，只列印或顯示了工作表中的一部分，內容被截斷為工作表上的交叉分析篩選器。
-   修正此問題：在嘗試與受保護活頁簿中的文字檔建立新連線時，收到「活頁簿受到保護，且無法變更」錯誤訊息。修正此問題：如果您的編輯語言是日文、中文或韓文，則當您嘗試在 [首頁] 索引標籤上選取新字型時，或當編輯時，Excel 可能會凍結。
-   修正此問題：當 Excel 最小化時，開啟活頁簿時捲軸會遺失。
-   修正此問題：在 [檔案總管] 中的檔案名稱上按兩下以開啟多個活頁簿時，活頁簿參照會失敗。
-   修正此問題：以程式設計方式建立樞紐分析表，接著以程式設計方式重新整理，會造成 Excel 當機。
-   修正此問題：以程式設計方式呼叫 Workbook.Open() 可能會造成 Excel 當機。
-   修正此問題：使用者使用巨集開啟 Office 2007 或較舊的活頁簿 (.xls 或 .xla) 時，會看到不正確的「重大失敗」錯誤訊息。
-   修正此問題：使用者開啟內容功能表時，Excel 可能會當機。
-   修正此問題：當使用者嘗試在現有的活頁簿中插入物件時，Excel 會在使用者按一下 [瀏覽] 時損毀。
-   修正此問題：使用密碼保護一個範圍時，看不到要輸入密碼以解鎖範圍的對話方塊。
-   修正此問題：在檔案名稱包含方括弧時，使用者無法在受保護的檢視中關閉活頁簿。
-   修正此問題：在拖曳或拖曳填滿時，工具提示的放置位置沒有對齊。
-   修正此問題：使用 [檔案] \> [另存新檔] 來儲存活頁簿時，包含句點的檔案名稱在檔案儲存對話方塊中會出現空白或截斷。
-   修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **輕鬆地排序您的電子郵件：** 由於您的意見反應，我們已為不使用 [焦點收件匣] 的使用者，重新加入了郵件清單上方的排序功能和 [未讀取] 篩選器。
-   **將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。
-   **Office 365 群組的改善︰** 您可以在群組訊息上按兩下，開啟其個別視窗，這讓您更加容易閱讀和回覆群組對話。
-   **LinkedIn 功能設定：** 移至 [檔案] \> [選項] \> [一般]，以控制 LinkedIn 功能是否要顯示在您的 Office 應用程式中。[深入了解](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **3D 模型：** 使用 3D 來增加電子郵件的視覺效果和創意影響。輕鬆插入 3D 模型，然後將其旋轉 360 度。 [深入了解](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **個人檔案卡片：** 無論您是使用桌面應用程式、Web 應用程式或行動應用程式，都能顯示有關人員和群組的最相關詳細資料。
-   **在群組行事曆中新增約會：** 現在，您可以讓群組中的每個人都知道您何時會離開，而不需要以電子郵件傳送會議。
-   **下載雲端附件：** 當您將 OneDrive 附件儲存或拖放到電腦時，我們會為您下載檔案。
-   **有用的聲音可改善協助工具：** 開啟音訊提示可在作業時一面引導您。可在 [檔案] \> [選項] \> [輕鬆存取] 中找到此功能。無需增益集。 [深入了解](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **焦點收件匣：** 收件匣分成兩個索引標籤 – 焦點及其他。訊息會依照訊息內容和您最常互動的寄信者進行分類。 [深入了解](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)
-   **快速存取您最常使用的群組︰** 您最有可能互動的群組，會出現在 [群組] 下方清單頂端的 [資料夾] 窗格中。

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11939)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 提高權限弱點
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 記憶體損毀弱點
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8150)：Microsoft Outlook 安全性功能略過的弱點
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 提高權限弱點
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 竄改弱點

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：切換到 [寄件匣] 或 [寄件備份] 資料夾造成 Outlook 損毀。
-   修正此問題：會議內文或附件變更時所有出席者收到會議更新，而非傳送會議更新給選擇性的出席者。
-   修正此問題：因為使用者代理程式字串中的變更，造成使用者無法連線到 EWS 及 REST 端點。
-   修正此問題：出席者的會議位置更新是顯示舊的位置而不是新的位置。
-   修正此問題：使用者在預覽讀取窗格中的附件時，會看到錯誤。
-   修正此問題：當使用者在撰寫電子郵件時，解決電子郵件地址的顯示名稱會使 Outlook 當機。
-   修正此問題：有些使用者未收到其租用戶系統管理員已啟用的支援功能
-   修正此問題：當搜尋範圍限定為 [所有信箱] 時，搜索會失敗並顯示 [找不到相符項目]。
-   修正此問題：使用 Accessible Event Watcher (AccEvent.exe) 來監視時，切換資料夾會導致 Outlook 當機。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **Microsoft Translator：** 使用 Microsoft Translator 可將單字、片語或句子翻譯成另一種語言。您可以從功能區中的 [校閱] 索引標籤使用此功能。
-   **3D 動畫：** 透過輕輕搖晃或跳躍及旋轉等動畫，讓 3D 模型栩栩如生。
-   **將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。
-   **修訂追蹤資訊漫遊：** 醒目提示共用投影片 (已經過他人修改) 的已讀取/未讀取狀態，現在會儲存在漫遊服務中 (而不是在使用者的本機電腦上)，讓這項資訊可以跨越多個裝置或平台上進行同步處理。
-   **快速存取您的網站和群組︰** 您可以使用 [檔案] 功能表，使用儲存在您常用的網站和群組中的文件。
-   **數位鉛筆：** 使用新的鉛筆紋理手寫或繪製出您的創意。只需傾斜即可使用支援的數位鉛筆進行陰影處理。
-   **LinkedIn 功能設定：** 移至 [檔案] \> [選項] \> [一般]，以控制 LinkedIn 功能是否要顯示在您的 Office 應用程式中。[深入了解](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **使用數位筆執行投影片放映：** 使用 Surface 手寫筆或其他有藍牙按鈕的手寫筆，推進您的投影片。必須有 Windows 10 Fall Creators Update。 [深入了解](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)
-   **3D 模型：** 使用 3D 來增加簡報的視覺效果和創意影響。透過「轉化」轉場在投影片之間建立電影動畫，讓 3D 模型讓您的簡報更生動。 [深入了解](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **新的筆跡效果：** 使用金屬畫筆和筆跡效果 (如彩虹、星空、熔岩、海洋、黃金、銀等) 來展現您的想法。
-   **共用檔案 UI：** 對於商務用 OneDrive 或 SharePoint 檔案，按一下功能區右上角的 [共用] 按鈕，或移至 [檔案] \> [共用] 可啟動經簡化並改良過的 [共用] 對話方塊。對於新的或儲存在本機的檔案，該 UI 可讓使用者輕鬆地將檔案上傳至 OneDrive 以啟動共同作業。
-   **封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **修訂醒目提示：** 會醒目提示已由其他使用者修改的投影片。
-   **當您離開時：** PowerPoint 會顯示自您上次查閱以來誰編輯了共用的簡報。
-   **設計工具的改進：** 設計工具現在會針對項目符號清單中的時間軸建議設計概念。
-   **有用的聲音可改善協助工具：** 開啟音訊提示可在作業時一面引導您。可在 [檔案] \> [選項] \> [輕鬆存取] 中找到此功能。無需增益集。 [深入了解](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **依帳戶的檔案位置：** 開啟或儲存檔案時，位置清單會依照與其相關聯的帳戶整理。
-   **畫筆自訂：** 針對筆跡選擇畫筆和螢光筆的個人集合。您的自訂集可在您所有的 Windows 電腦上使用。
-   **設計工具的改進：** 設計工具現在會針對新增至投影片的圖表建議設計概念。
-   **快速啟動工具：** 自動建置大綱，協助使用者開始研究他們所選擇的主題。[深入了解](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)
-   **數位尺規：** 在有觸控式螢幕的裝置上，請移至「繪圖 \> 尺規」，然後使用您的手寫筆或手指來繪製直線，或對齊一組物件。[深入了解](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)

### <a name="powerpoint-security-updates"></a>PowerPoint：安全性更新
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11934)：Microsoft PowerPoint 資訊洩漏弱點

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：表格以粗框線錯誤編譯。
-   修正當變更 Shape.Visibile 屬性時可能會造成當機的問題。
-   修正共同撰寫文件中的變更無法合併的問題。
-   修正包含 ActiveX 控制項的文件會造成共同撰寫失敗的問題。
-   修正此問題：在圖形中使用拼字校正時會造成 PowerPoint 當機。
-   修正此問題：PowerPoint 在從 SharePoint Online 開啟檔案時損毀。
-   修正此問題：開啟 [自動儲存] 時，[復原] 窗格不正確地顯示。
-   修正此問題：未顯示登入，使得使用者無法存取檔案。
-   修正此問題：多個使用者在相同簡報上共同撰寫會導致投影片母片不正確重複。
-   修正此問題：將儲存在 OneDrive 中的檔案開啟時，結束受保護的檢視時會導致 PowerPoint 當機。修正此問題：移除文件屬性和個人資訊會造成儲存至 SharePoint 失敗。
-   修正此問題：以 Flash Player 為基礎之 YouTube 內嵌程式碼的參考，導致開啟新視窗來播放影片。舊的內嵌程式碼現已升級為參考以 HTML5 為基礎的 YouTube 影片，以便正確地就地播放。
-   修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。

### <a name="project-feature-updates"></a>Project：功能更新
-   **工作面板檢視：** 在 [工作面板] 檢視中的卡片上排序工作。在面板上的資料行之間重新排序和移動卡片，就像在敏捷式專案中一樣。
-   **敏捷式專案：** 使用待辦項目、工作面板、衝刺及其他項目管理您的敏捷式專案。同時支援 Scrum 或 Kanban 方法。[深入了解](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)  
-   **在 Planner 中管理工作：** 將專案工作連結至 Planner，並為其建立計劃。將工作分成子工作、新增小組、指派任務，以及管理工作面板上的工作。

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正此問題：如果工作以成本資源分割，成本資源未正確更新，且成本遺失。
-   修正時間表檢視的問題：在 [將現有工作新增至時間表] 對話方塊中，只會出現來自第一個摘要工作中的工作。
-   修正此問題：從 Project Online 或 Project Server 將主要專案儲存為 XML 時失敗。
-   修正時間表檢視的問題：在 [將現有工作新增至時間表] 對話方塊中，只會出現來自第一個摘要工作中的工作。
-   修正此問題：在日期資料行上使用 [自動篩選] 下拉式清單造成專案中的所有工作隱藏。
-   修正此問題：將現有的工作新增至時間表檢視中的時間表時，對話方塊中只會出現來自第一個摘要工作的工作。
-   修正此問題：在工作階段中設定多個基準，會讓 MOD\_DATE 值都設為相同。
-   修正此問題：將實際工時從 [儲存為共用] 工作階段中移除之後，[實際工時] 仍然顯示在報表中。
-   修正此問題：在德文版中進行排程時，要使用 [週] 日期格式時會傳回錯誤。
-   修正此問題：在編輯 [排程網頁組件] 的完成日期時，工作保持為每天 8 小時，而不是隨著時間分配。
-   修正此問題：在非預期的位置繪製「進度點形狀」。
-   修正此問題：VBA 程式碼從專案中遺失。
-   修正此問題：即使有剩餘工時，工作卻顯示為完成。
-   修正此問題：使用「任務路徑」功能時，專案停止回應。
-   修正此問題：時幅沒有顯示時幅標籤。
-   修正此問題：視覺效果報表顯示不完整的資訊或完全失敗。
-   修正此問題：儲存失敗會導致檔案損毀，並造成專案在開啟時當機。
-   修正此問題：您無法在時間軸和團隊規劃檢視中拖曳工作。
-   修正此問題：「小組建立器」中沒有顯示資源可用性。
-   修正此問題：圖形指標並未正確顯示。
-   修正此問題：專案以每小時或每一天為基礎進行調整時沒有反應。
-   修正此問題：搭配使用 SharePoint 文件庫的主/子專案。
-   修正此問題：當您將工作分派新增到固定工期的排程時，可能會導致沒有名稱的資源。
-   修正此問題：變更受保護的工作時，會產生不正確的錯誤訊息。
-   修正此問題：當報表包含數個影像時，Project 可能會損毀。

### <a name="publisher-feature-updates"></a>Publisher：功能更新
-   **封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="publisher-non-security-updates"></a>Publisher：非安全性更新
-   修正此問題：執行合併列印精靈時，篩選包含 null (空白) 值的資料來源欄位失敗。

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正與 TLS 1.2 支援相關的問題。
-   修正此問題：在會議中以選取 [Skype 通話] 的方式新增使用者會產生錯誤
-   修正此問題：在會議中以選取 [Skype 通話] 的方式新增使用者會產生錯誤。
-   如果已將 Skype 會議室新增為位置，且會議已包含小組會議座標，請移除要求使用者將 Skype 座標新增至會議的提示。
-   修正此問題：即使 UseLocationForE911Only 設定為 true，也會填入位置。
-   修正此問題：使用名冊中的「使用會議中心呼叫」選項來邀請使用者時，商務用 Skype 會當機。
-   修正此問題：建立商務用 Skype 會議時，在終端機伺服器上運行的Outlook 會凍結。
-   將 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 的預設值變更為 TRUE。
-   修正此問題：當會議處於全螢幕模式時，[其他選項] 和 [邀請其他人] 按鈕會隱藏。
-   修正此問題：當您想要加入會議時，P2P 音訊撥號視窗或電話會議視窗會變成透明。
-   修正此問題：即將開始的 Skype 會議未顯示在 [會議] 索引標籤。
-   修正此問題：當商務用 Skype 配置為無音訊加入會議，新增音訊至會議時不會將音訊新增至現有的會議，反而是向使用者本身啟動新的 P2P 撥號。
-   修正此問題：當使用者按下 Outlook 會議邀請的 [加入 Skype 會議] 連結時，會收到錯誤訊息 [找不到此 Skype 會議]。
-   在快顯通知 UI 中為撥入的 PSTN 通話新增來電轉接按鈕。
-   當 ChatDefaultClient 和 CallDefaultClient 設定至 Teams 時，通知使用者來電與交談正在傳送至 Teams。
-   當使用者不在會議中並停用商務用 Skype 時，使用者狀態會顯示為 [離線]，且會議加入體驗會設為 [原生有限用戶端]。
-   商務用 Skype 最小化至通知區域時，停用 [開啟] 和 [結束] 以外的所有選項。
-   與 Aries 電話配對且啟用 RedirectClient 時，隱藏新來電和對話。
-   修正此問題：日期格式非美國格式 (mm/dd/yy) 時，在 PChat 中依日期搜尋訊息會失敗。
-   修正此問題：當 EnableExternalP2PFileTransfer 原則設為 false 時，使用者仍然可以在會議中附加檔案。
-   修正此問題：在 [交談歷程記錄] 中，顯示了來電者而非受話者。使用 Active Directory 修改受話者的公司電話時會發生這種情況。
-   修正此問題：對於撥出 PSTN 通話到行動號碼，交談歷程記錄的通話記錄中遺失受話方資訊。
-   修正此問題：從 Outlook 中的電子郵件起始 IM 時，電子郵件的主旨列並不包含在 IM 的主旨中。
-   修正此問題：當 [IM 交談] 視窗貼齊到一側時，交談會出現雙重堆疊。
-   修正此問題：在 VDIv2 環境中，VbSS 螢幕畫面分享要求會顯示為 RDP 要求。
-   修正此問題：來電轉接失敗時，來電者會列在失敗通知中而非列在未接受話方。
-   修正此問題：「開始使用 Teams」按鈕隱藏在用戶端升級重新導向橫幅內。
-   修正即時通訊視窗中的 DPI 縮放比例問題。
-   修正此問題：商務用 Skype 連絡人卡片中未顯示 LinkedIn 資料。
-   新增可讓使用者代表群組搜尋停止接受呼叫的功能。
-   新增功能，正在商務用 Skype 或 Teams 進行通話時，若接收或起動新的通話時，會自動保留通話。
-   修正此問題：使用者使用全螢幕共用之後無法傳送 IM。
-   修正此問題：在大廳中的使用者進入會議室遭到拒絕時，不會收到通知。
-   修正此問題：自動增益控制在通話期間無法控制的增加。
-   修正此問題：將會議室資源信箱加入會議邀請時，使用者無法選取「會議選項」中的簡報者。
-   修正此問題：如果 AllowlPVideo 設定為 False，桌面共用按鈕在端對端視訊通話期間無法使用。
-   修正此問題：將現有會議 (建立時為「停用 IM」) 的「會議選項」設定變更為「啟用 IM」之後，IM 仍保持停用。
-   修正此問題：當滑鼠停留在聊天視窗的 [插入連結] 按鈕上時，工具提示不會顯示，並且在選取按鈕時沒有協助工具名稱。

### <a name="visio-feature-updates"></a>Visio：功能更新
-   **內建資料庫模型圖表：** 使用新的資料庫模型圖表範本，將您的資料庫精確地建模為 Visio 圖表。不需要增益集。
-   **更多商用圖表的樣板：** 使用新式圖形，以文氏圖表來比較和對比資料；或繪製循環、矩陣或金字塔圖表來表達您的想法。
-   **建立網站的線框圖：** 快速地建立網站的線框圖，包括介面、瀏覽，以及如何共同作業。 [深入了解](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **建立行動應用程式的框線：** 使用範本來建立行動應用程式的框線。[深入了解](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **將資料圖形套用至 [資料視覺化工具] 圖表：** 藉由自動套用圖形資料作為資料圖形，以節省建立資料視覺化工具圖表的時間。[深入了解](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)
-   **繪圖共同作業：** 透過在商務用 OneDrive 或 SharePoint Online 上共用繪圖來與其他人合作。您可以看到誰在使用繪圖、新增註解以及查看檔案活動。 [深入了解](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)
-   **封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="word-feature-updates"></a>Word：功能更新
-   **將 SVG 圖示轉換成圖形：** 將所有 SVG 圖片和圖示轉換成 Office 圖形，讓您可以變更其色彩、大小或材質。
-   **字元數：** 當您輸入時，可在狀態列上顯示字元數。您可以從 [自訂狀態列] 功能表啟用此項目。
-   **快速存取您的網站和群組︰** 您可以使用 [檔案] 功能表，使用儲存在您常用的網站和群組中的文件。
-   **Microsoft Translator：** 在 Word 中使用 Microsoft Translator 將文字、片語或整個文件翻譯成另一種語言。[深入了解](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)
-   **數位鉛筆：** 使用新的鉛筆紋理手寫或繪製出您的創意。只需傾斜即可使用支援的數位鉛筆進行陰影處理。
-   **LinkedIn 功能設定：** 移至 [檔案] \> [選項] \> [一般]，以控制 LinkedIn 功能是否要顯示在您的 Office 應用程式中。[深入了解](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **SharePoint 屬性面板：** 在文件中顯示和編輯 SharePoint 文件庫欄值。[檢視] 索引標籤上的功能區按鈕可讓您輕鬆存取面板，且 SharePoint 系統管理員可以使用文件庫設定來自動開啟 [屬性] 面板。
-   **3D 模型：** 使用 3D 來增加文件的視覺效果和創意影響。輕鬆插入 3D 模型，然後將其旋轉 360 度。 [深入了解](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **新的筆跡效果：** 使用金屬畫筆和筆跡效果 (如彩虹、星空、熔岩、海洋、黃金、銀等) 來展現您的想法。
-   **共用檔案 UI：** 對於商務用 OneDrive 或 SharePoint 檔案，按一下功能區右上角的 [共用] 按鈕，或移至 [檔案] \> [共用] 可啟動經簡化並改良過的 [共用] 對話方塊。對於新的或儲存在本機的檔案，該 UI 可讓使用者輕鬆地將檔案上傳至 OneDrive 以啟動共同作業。
-   **封鎖危險的副檔名：** 依預設，視為具有高風險以及內嵌為 OLE 封裝物件的副檔名 (例如.exe、.vbs 和 .js)，會遭到封鎖而無法啟動。[深入了解](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **使用學習工具進行編輯：** 在 Word 的 Web 版面配置中現已提供學習工具。在您編輯時可調整文字間距和顯示音節。在任何檢視中，都可看見每個字會隨著大聲朗讀文件而以反白顯示。 [深入了解](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)
-   **LaTeX 語法：** 使用 LaTeX 語法建立並編輯數學方程式。
-   **有用的聲音可改善協助工具：** 開啟音訊提示可在作業時一面引導您。可在 [檔案] \> [選項] \> [輕鬆存取] 中找到此功能。無需增益集。 [深入了解](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **依帳戶的檔案位置：** 開啟或儲存檔案時，位置清單會依照與其相關聯的帳戶整理。
-   **畫筆自訂：** 針對筆跡選擇畫筆和螢光筆的個人集合。您的自訂集可在您所有的 Windows 電腦上使用。
-   **以 [編輯器] 窗格增強了撰寫協助：** 使用 [編輯器] 窗格可得到進階拼字檢查、文法和書寫樣式的建議。它內建無障礙功能，並已改善對輔助技術的支援。

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
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 資訊洩漏弱點
-   [Advisory 170020](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV170020)：Microsoft Office 深度防禦更新

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：Word 在從 SharePoint Online 開啟檔案時損毀。
-   修正此問題：小寫羅馬數字頁碼不正確地變更為大寫。
-   修正造成顯示記憶體不足訊息的問題。
-   修正此問題：Word 在執行 Windows 7 的電腦上無法開啟，且該電腦上未安裝 客戶體驗和診斷遙測的更新。
-   修正此問題：清單中的項目符號無法列印。
-   修正此問題：當使用者嘗試對商務用 OneDrive 上的現有文件執行 [另存新檔] 時，Word 會當機，並取消儲存作業或嘗試合併現有變更。
-   修正此問題：執行合併列印精靈時，篩選包含 null (空白) 值的資料來源欄位失敗。
-   修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。
-   修正此問題：要移除文件中的 IRM 保護時並沒有移除保護。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11882)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8157)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8158)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 遠端程式碼執行弱點
-   [Advisory 180003](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180003)：Microsoft Office 深度防禦更新

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   修正問題，問題是當使用 System Center Configuration Manager 將更新部署至執行 Office 應用程式的用戶端時，更新未在 Office 應用程式執行中且重新啟動裝置之後套用。
-   修正此問題：開啟應用程式時，使用者可能會看到以安全模式啟動的訊息，然後應用程式無法開啟。
-   當啟用 Office COM 物件，讓 Office 365 用戶端更新由 System Center Configuration Manager 管理，[立即更新] 選項會在 [檔案] \> [帳戶] \> [更新選項] 中隱藏。
-   修正此問題：當使用者嘗試使用 [啟動 Office] 對話方塊來啟動 Office 時，Office 應用程式會當機。
-   修正在動態 DPI 環境下的 Office 增益集中縮放與調整大小的問題。
-   修正此問題：即使目前已安裝 Office 365 ProPlus，Office 設定服務提供者 (CSP) 的 CurrentStatus 節點仍會傳回空字串。
-   修正此問題：因為同一部電腦上所有的 Office 應用程式版本會共用 .box 檔案，而導致 .box 檔案格式變更；該問題會影響同一部電腦上所安裝舊版 Office 的功能。
-   修正會導致更新安裝在特定案例中耗費長時間的錯誤。 
-   修正此問題：SVG 測試失敗
-   修正問題，問題是當使用 System Center Configuration Manager 將更新部署至執行 Office 應用程式的用戶端時，更新未在 Office 應用程式執行中且重新啟動裝置之後套用。


## <a name="version-1708-july-10"></a>版本 1708：7 月 10 日
*版本 1708 (組建 8431.2280)*

*這是自從 2018 年 1 月以來提供的半年通道版本。它會繼續受到支援並接收安全性更新，直到 2019 年 3 月為止。不過，目前已提供新的半年通道版本 — 版本 1803 (組建 16.0.9126.2259) — 其中包含了新功能、安全性更新和非安全性更新。*

### <a name="access-security-updates"></a>Access：安全性更新
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8312)：Microsoft Access 遠端程式碼執行 Use After Free 弱點

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8310)：Microsoft Office 竄改弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8281)：Microsoft Office 遠端程式碼執行弱點


## <a name="version-1708-june-12"></a>版本 1708：6 月 12 日
*版本 1708 (組建 8431.2270)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 遠端程式碼執行弱點

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 提高權限弱點

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正造成 Windows 7 SP1 使用者無法將成員新增至「新式群組」的問題。



## <a name="version-1705-june-12"></a>版本 1705：6 月 12 日
*版本 1705 (組建 8201.2294)*

*這是自從 2017 年 9 月以來提供的順延通道版本。它會繼續受到支援並接收安全性更新，直到 2018 年 7 月為止。不過，目前已提供新的半年通道版本 — 版本 1708 (組建 8431.2270) — 其中包含了新功能、安全性更新和非安全性更新。*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8246)：Microsoft Excel 資訊洩漏弱點
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8248)：Microsoft Excel 遠端程式碼執行弱點

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-8244)：Microsoft Outlook 提高權限弱點



## <a name="version-1708-may-8"></a>版本 1708：5 月 8 日
*版本 1708 (組建 8431.2250)*

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



## <a name="version-1705-may-8"></a>版本 1705：5 月 8 日
*版本 1705 (組建 8201.2278)*

*這是自從 2017 年 9 月以來提供的順延通道版本。它會繼續受到支援並接收安全性更新，直到 2018 年 7 月為止。不過，目前已提供新的半年通道版本 — 1708 版 (組建 8431.2250) — 其中包含了新功能、安全性更新和非安全性更新。*

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



## <a name="version-1708-april-10"></a>版本 1708：4 月 10 日
*版本 1708 (組建 8431.2242)*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 遠端程式碼執行弱點

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   修正與 TLS 1.2 支援相關的問題。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 遠端程式碼執行弱點



## <a name="version-1705-april-10"></a>版本 1705：4 月 10 日
*版本 1705 (組建 8201.2272)*

*這是自從 2017 年 9 月以來提供的順延通道版本。它會繼續受到支援並接收安全性更新，直到 2018 年 7 月為止。不過，目前已提供新的半年通道版本 — 1708 版 (組建 8431.2242) — 其中包含了新功能、安全性更新和非安全性更新。*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1029)：Microsoft Excel 遠端程式碼執行弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0950)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1026)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-1030)：Microsoft Office 遠端程式碼執行弱點



## <a name="version-1708-march-13"></a>版本 1708：3 月 13 日
*版本 1708 (組建 8431.2236)*

### <a name="access-security-updates"></a>Access：安全性更新
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 遠端程式碼執行弱點

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全性功能略過

### <a name="word-security-updates"></a>Word：安全性更新
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 資訊洩漏弱點



## <a name="version-1705-march-13"></a>版本 1705：3 月 13 日
*版本 1705 (組建 8201.2265)*

*這是自從 2017 年 9 月以來提供的順延通道版本。它會繼續受到支援並接收安全性更新，直到 2018 年 7 月為止。不過，目前已提供新的半年通道版本 — 1708 版 (組建 8431.2236) — 其中包含了新功能、安全性更新和非安全性更新。*

### <a name="access-security-updates"></a>Access：安全性更新
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0903)：Microsoft Access 遠端程式碼執行弱點

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0907)：Microsoft Office Excel 安全性功能略過

### <a name="word-security-updates"></a>Word：安全性更新
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0919)：Microsoft Office 資訊洩漏弱點



## <a name="version-1708-february-13"></a>版本 1708：2 月 13 日
*版本 1708 (組建 8431.2215)*

### <a name="access-non-security-updates"></a>Access：非安全性更新
-   修正下列問題：當使用多個項目表單時，調整滑鼠滾輪或捲軸捲動方塊並不會變更表單中顯示的項目。

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 遠端程式碼執行弱點

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 提高權限弱點
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 記憶體損毀弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 資訊洩漏弱點



## <a name="version-1705-february-13"></a>版本 1705：2 月 13 日
*版本 1705 (組建 8201.2258)*

*這是自從 2017 年 9 月以來提供的順延通道版本。它會繼續受到支援並接收安全性更新，直到 2018 年 7 月為止。不過，目前已提供新的半年通道版本 — 1708 版 (組建 8431.2215) — 其中包含了新功能、安全性更新和非安全性更新。*

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0841)：Microsoft Excel 遠端程式碼執行弱點

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0850)：Microsoft Outlook 提高權限弱點
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0852)：Microsoft Outlook 記憶體損毀弱點

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0851)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0853)：Microsoft Office 資訊洩漏弱點



## <a name="version-1708-january-9"></a>版本 1708：1 月 9 日
*版本 1708 (組建 8431.2153)*

### <a name="access-feature-updates"></a>Access：功能更新
-   **標籤名稱屬性：** 藉由使標籤與表單上的控制項相關聯來增強協助工具。
-   **編輯新項目變得更無障礙：** 您可以使用快速鍵盤快速鍵 (Ctrl + E) 從下拉式方塊或清單方塊編輯新項目。
-   **動態連接器：** 從 Microsoft Dynamics 匯入資料或連結到儲存在其中的資料。[詳細資訊](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Salesforce 連接器：** 匯入資料或連結到儲存在 Salesforce 的資料。[詳細資訊](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="access-non-security-updates"></a>Access：非安全性更新
-   修正此問題：嘗試在文字方塊或下拉式方塊中選取文字似乎會選取所有文字，而不是表示選取範圍。
-   修正此問題：如果查詢與 Microsoft Dynamics 連結的資料表中的主索引鍵有聯接，則查詢不會執行。
-   修正此問題：Microsoft Dynamics 資料表中的貨幣值未顯示小數位數。

### <a name="excel-feature-updates"></a>Excel：功能更新
-   **「從範例新增資料行」增強功能：** 支援多個日期/時間、數學、和索引資料行轉換。
-   **效能改善：** Excel 能更快速地開啟具有多個工作表的複雜活頁簿，讓您可以使用大範圍的公式、篩選大量資料列，或更快地複製和貼上。
-   **插入線上圖片：** 用以選取影像和屬性資訊的新登陸頁面會隨著影像自動插入。
-   **Azure Data Lake Store 連接器：** 使用者現在可以從 Azure Data Lake Store 匯入資料。
-   **「從範例新增資料行」增強功能：** 支援建議、更多日期/時間作業及其他轉換。
-   **[資料] 索引標籤**：在 [資料] 索引標籤上的功能區按鈕，已重新排列成兩個新的群組：「取得與轉換資料」及「查詢與連線」。
-   **共用查詢**：將任何查詢定義匯出至 Office 資料庫連線 (ODC) 檔，然後在活頁簿之間共用或與其他人共用。
-   **載入資料：** 從查詢直接將資料載入到樞紐分析表或樞紐分析圖中，而不必將資料儲存到資料模型內。
-   **共用的檔案活動︰** 選擇檔案右上角的 [活動] 按鈕，以查看在商務用 OneDrive 或 SharePoint 中共用檔案的共用、編輯、重新命名或還原。
-   **安全連結：** 當使用者按一下連結時，Office 365 進階威脅防護 (ATP) 會檢查是否為惡意的連結。如果連結被視為惡意，系統就會將使用者重新導向至警告頁面而非原始的目標 URL。 [詳細資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **增強的資料匯入功能︰** 輕鬆地從各種來源匯入圖形資料。使用 [查詢和連線] 側邊窗格來管理活頁簿查詢和連線，並透過 ODC 檔與他人共用查詢。 [詳細資訊](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **共用檔案中的變更**：檢視誰在共用活頁簿中進行了變更，以及將活頁簿還原到舊版。[詳細資訊](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **具有畫筆按鈕的套索工具：** 使用套索工具筆跡支援的數位畫筆按鈕，而不造訪功能區。

### <a name="excel-security-updates"></a>Excel：安全性更新
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8501)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8502)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8631)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8632)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11877)：Microsoft Excel 安全性功能略過的弱點
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11878)：Microsoft Excel 記憶體損毀弱點
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11884)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11935)：Microsoft Excel 遠端程式碼執行弱點
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0796)：Microsoft Excel 遠端程式碼執行弱點
-   [Advisory 170021](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新

### <a name="excel-non-security-updates"></a>Excel：非安全性更新
-   修正此問題：以程式設計方式建立樞紐分析表，接著以程式設計方式重新整理，會造成 Excel 當機。
-   修正此問題：使用者使用巨集開啟 Office 2007 或較舊的活頁簿 (.xls 或 .xla) 時，會看到不正確的「重大失敗」錯誤訊息。
-   修正此問題：從命令列開啟活頁簿可能會導致儲存格中的 RTF 格式遺失。
-   修正此問題：在檔案名稱包含方括弧時，使用者無法在受保護的檢視中關閉活頁簿。
-   修正此問題：當使用者嘗試在現有的活頁簿中插入物件時，Excel 會在使用者按一下 [瀏覽] 時損毀。
-   修正此問題：選取 [調整圖形大小以修正文字] (在 [圖形格式] 窗格的 [文字選項]/[文字方塊] 部分中)，結果圖形不變。
-   修正此問題：在活頁簿上按兩下以開啟活頁簿時，不會載入儲存格的文字字型和格式，或兩個完全相同的活頁簿會針對一個範本開啟。
-   修正此問題：開啟或建立新的活頁簿時，在 Excel 啟動時所建立的第一個活頁簿不會關閉。
-   修正此問題：在拖曳或拖曳填滿時，工具提示的放置位置沒有對齊。
-   修正此問題：使用 [檔案] \> [另存新檔] 來儲存活頁簿時，包含句點的檔案名稱在檔案儲存對話方塊中會出現空白或截斷。
-   修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。
-   修正轉譯問題：由於錯誤的圖形驅動程式而出現黑色線條和標頭。
-   修正此問題：在插入圖表後，Excel 毀損或無法儲存活頁簿。
-   修正此問題：分頁預覽中的分頁線位置不正確。
-   修正此問題：Excel 在開啟 XLL 檔案時損毀。
-   修正此問題：在頁面配置檢視中新增頁首或頁尾後，其儲存格的圖樣樣式無法正確呈現。
-   修正此問題：將樞紐分析表的副本貼上到另一個活頁簿可能會導致當機。
-   修正此問題：當選擇 [取代] 命令時，[尋找] 及 [取代] 對話方塊隨即開啟，但對話方塊的焦點位於 [尋找] 索引標籤，而不是 [取代] 索引標籤。
-   修正此問題：從比 SharePoint Server 2016 更早版本的 SharePoint Server 開啟活頁簿的 [活動] 窗格時，Excel 會當機。
-   修正此問題：當啟用一或多個 XLL 增益集時，Excel 會開啟並顯示一個空白視窗。
-   修正此問題：在已關閉的活頁簿中使用 [表單] 按鈕之後，Excel 會當機。
-   修正此問題：使用 SheetBeforeRightClick 事件時，插入與合併儲存格相交的資料行不會展開合併的儲存格。
-   修正此問題：展開或摺疊樞紐分析表時，Excel 暫時停止回應且樞紐分析表標頭移出螢幕。
-   修正此問題：從 Word 複製和貼上 Tab 分隔的文字時，會忽略索引標籤，導致文字無法被剖析成多個欄位。
-   修正此問題：開啟 [發佈為網頁] 對話方塊時，Excel 會當機。
-   修正此問題：使用來自 SQL Server Analysis Services 伺服器的資料，且 Excel 的地區設定和 SQL Server Analysis Services 伺服器的地區設定不同時，資料重新整理不成功或 Excel 當機。
-   修正此問題：當嘗試儲存與 OneDrive 用戶端同步的文件變更時出現錯誤。
-   修正此問題：當「篩選」區域中有 PivotTable，其他地方並沒有任何欄位時，無法在工作表中進行任何變更。

### <a name="outlook-feature-updates"></a>Outlook：功能更新
-   **協助工具的改善：** 我們讓您在使用螢幕助讀程式時，能夠容易地閱讀及編輯電子郵件中的文字、表格、清單和圖像。
-   **新帳戶設定：** 使用新的精靈設定新帳戶，所需的手動步驟更少。
-   **附加連結的對話方塊：** 在功能區使用「附加檔案」附加連結時，您可以選擇要將其新增為連結或作為附件傳送。如果您不希望每次都看到此對話方塊，請移至 [檔案] \> [選項] \> [一般]，並指定想要在 [附件選項] 下附加連結的方式。
-   **內部部署附件的支援：** 內部部署 SharePoint 伺服器上的檔案會在 [訊息] \> [附加檔案] 下顯示為最近使用的檔案，而內部部署商務用 OneDrive 和 SharePoint 團隊網站會顯示在 [附加檔案] \> [瀏覽網頁位置]，此外本機檔案可以上傳至內部部署商務用 OneDrive 網站。
-   **群組的業務分類︰**  租用戶系統管理員定義的業務分類層級 (如機密)，可在建立或編輯群組時指派，且該分類會顯示在群組標題中。
-   **來賓存取 Office 365 群組︰** 透過授予存取組織對話、檔案、行事曆邀請和群組筆記本的存取權限，與組織外部的人員協同合作。 [詳細資訊](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **可採取動作的訊息︰** 開發人員可以建立訊息，讓使用者可以從 Outlook 輕鬆採取簡單或快速的動作，而不需要切換至外部網站或個別的應用程式。[詳細資訊](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook：安全性更新
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8571)：Microsoft Office Outlook 安全性功能略過的弱點
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8572)：Microsoft Office Outlook 資訊洩漏弱點
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8663)：Microsoft Office Outlook 記憶體損毀弱點
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11774)：Microsoft Outlook 安全性功能略過的弱點
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11776)：Microsoft Outlook 資訊洩漏弱點
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11939)：Microsoft Office 資訊洩漏弱點
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0791)：Microsoft Outlook 遠端程式碼執行弱點
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0793)：Microsoft Outlook 遠端程式碼執行弱點

### <a name="outlook-non-security-updates"></a>Outlook：非安全性更新
-   修正此問題：使用者看到郵件清單中的焦點會在刪除郵件時意外跳轉。
-   修正導致使用者在與附件互動時看到驗證提示的問題
-   修正此問題：使用深灰色佈景主題時，「原則提示」中的「深入了解」連結無法顯示。
-   修正此問題：當使用者嘗試設定新帳戶，並且在未完成帳戶設定之前即關閉該視窗時，Outlook 會當機。
-   修正此問題：「標記為已讀取」時，「標記為未讀取」為群組的共用收件匣中的郵件選項。
-   修正此問題：無法在 Outlook 中設定 IMAP 帳戶。
-   修正此問題：開啟 Outlook 時會間歇性當機。

### <a name="powerpoint-feature-updates"></a>PowerPoint：功能更新
-   **插入線上圖片：** 用以選取影像和屬性資訊的新登陸頁面會隨著影像自動插入。
-   **影片的隱藏式輔助字幕：** 可將隱藏式輔助字幕新增至影片，使其變得更無障礙。[詳細資訊](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **製作錄製的旁白︰** 當您錄製簡報時，可加入自己旁白的視訊。錄製可以包含動畫、筆跡、音訊和視訊。
-   **共用的檔案活動︰** 選擇檔案右上角的 [活動] 按鈕，以查看在商務用 OneDrive 或 SharePoint 中共用檔案的共用、編輯、重新命名或還原。
-   **Alt 文字建立︰** 雲端式服務會自動為簡報中的圖片產生替代文字。
-   **安全連結：** 當使用者按一下連結時，Office 365 進階威脅防護 (ATP) 會檢查是否為惡意的連結。如果連結被視為惡意，系統就會將使用者重新導向至警告頁面而非原始的目標 URL。 [詳細資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **設計工具改進功能：** 針對動作取向的清單提供專業的設計構想建議。
-   **共用檔案中的變更**：檢視誰在共用簡報中進行了變更，以及將簡報還原到舊版。[詳細資訊](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint：安全性更新
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8742)：PowerPoint 遠端程式碼執行弱點
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8743)：PowerPoint 遠端程式碼執行弱點
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11934)：Microsoft PowerPoint 資訊洩漏弱點

### <a name="powerpoint-non-security-updates"></a>PowerPoint：非安全性更新
-   修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。
-   修正此問題：在表格中復原後編輯和格式化文字會導致 PowerPoint 毀損。
-   修正此問題：以 Flash Player 為基礎之 YouTube 內嵌程式碼的參考，導致開啟新視窗來播放影片。舊的內嵌程式碼現已升級為參考以 HTML5 為基礎的 YouTube 影片，以便正確地就地播放。
-   修正此問題：從比 SharePoint Server 2016 更早版本的 SharePoint Server 開啟簡報時，PowerPoint 會當機。
-   修正此問題：已連結字型的使用者定義字元 (EUDC) 無法顯示。

### <a name="project-non-security-updates"></a>Project：非安全性更新
-   修正此問題：專案層級自訂欄位的資料可能在儲存時遺失。
-   修正此問題：儲存失敗會導致檔案損毀，並造成專案在開啟時當機。
-   修正此問題：開啟專案計劃可能會導致當機。
-   修正此問題：從 Project Online 開啟某些檔案會造成 Project Online 當機。
-   修正此問題：設定剩餘工時時，可能會錯誤清除「實際開始時間」。
-   修正此問題：「指派實際開始時間」顯示的資料，可能會與透過 Project Web App 中狀態的資源所回報的資料不同。
-   修正此問題：若變更工作的完成日期，則實際工時可能會重新排程。
-   修正此問題：如果您複製並貼上成本欄位，由於進位的問題，貼上的值可能與複製的值不完全符合。
-   修正此問題：從一個比較基準儲存到另一個基準時，不會複製預算資源的時段資料。
-   修正此問題：[狀態] 欄位對摘要任務的計算不一定正確。
-   修正此問題：當實際工時取代本機資源並啟用受保護的工時，實際工時會錯誤地轉移到企業資源。
-   修正此問題：如果您有一個資料表，其中第一欄是 [工作名稱]，該欄已被鎖定，而按一下工作會導致專案損毀。
-   修正此問題：您可以透過 [任務分派狀況] 檢視，將相同的資源多次指定至相同的工作。
-   修正此問題：開啟 XML 檔案時，數字自訂欄位的值可能會遺失。
-   修正此問題：最高層級任務縮排無法從 Project 正確同步到 SharePoint 工作清單。
-   修正此問題：如果您從 Excel 活頁簿匯入任務、資源或工作分派資訊，[工時] 欄位中的值可能會被忽略。
-   修正此問題：分時段的基準值不符合 (您將專案儲存為 XML 檔案格式時的) 初始值。
-   修正此問題：由於 Project 用戶端認為專案已簽出，因此不會開啟專案，但實際上並未簽出。
-   修正此問題：從高延遲的檔案伺服器開啟 Project 檔案，現在速度已加快。

### <a name="skype-for-business-security-updates"></a>商務用 Skype：安全性更新
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8676)：Windows GDI + 資訊洩漏弱點
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8695)：圖形元件資訊洩漏弱點
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8696)：Microsoft 圖形元件遠端程式碼執行

### <a name="skype-for-business-non-security-updates"></a>商務用 Skype：非安全性更新
-   新增對話方塊，說明特定連接埠被封鎖或 IP 未列入白名單時，使用者為何無法加入會議。
-   修正此問題：當您按一下 IM 交談分頁時，常設聊天室中的未讀訊息會標示成已讀。
-   修正此問題：傳入的 IM 快顯通知會發生幾秒延遲。
-   修正此問題：停用 Exchange 同步處理時，AD 連絡人會顯示為電話號碼，而不是連絡人名稱。
-   修正此問題：停用同盟且會議召集人未明確封鎖匿名加入時，匿名加入使用者會被封鎖而無法加入。
-   修正此問題：超過人數限制的會議中，對會議召集人顯示的受邀者數目不正確。
-   修正此問題：內送 PSTN 通話的快顯通知中不顯示電話號碼。
-   修正此問題：重新命名連絡人清單群組時，使用 Delete 鍵會刪除整個群組。
-   修正此問題：共用停止之前，會關閉 IM 交談中的共用通知。
-   修正此問題：某些非英文語言的登入畫面是空白的。
-   修正此問題：在聊天和聊天歷程記錄中的非英文字元是亂碼。
-   若使用者的名稱未知，則會顯示由組織的自動語音應答所處理的來電者電話號碼。
-   新增 Inband 設定，可選擇性地限制「這些人不需要在大廳中等候」中的「任何人 (沒有限制)」。
-   新增在 VDIv2 中 P2P 視訊呼叫己方視訊的開/關功能。
-   修正此問題：呼叫下拉功能表中連絡人會顯示重複的號碼。
-   修正此問題：在商務用 Skype 和商務用 Skype 基本版之間移動的使用者委派會遭到移除。
-   修正此問題：使用「啟用顯示為離線」和「自訂狀態 URL」用戶端原則時，會看不到 [顯示為離線]。
-   加寬 [加入會議] 按鈕，以修正某些當地語系化語言的截斷問題。
-   更加凸顯高重要性的訊息在聊天中的重要性。
-   在允許的檔案傳輸封鎖清單中新增 Office 和商務用 Skype 副檔名類型。
-   在設為非英文的 Outlook 會議邀請中，修正會議頁尾文字的當地語系化。
-   修正此問題：在多個使用者的情況下，對話中的傳送者名稱可能會切換。
-   修正此問題：在成功加入會議前，空白的對話視窗都不會出現。
-   修正此問題：若職稱欄位空白，則搜尋結果中連絡人卡片上的部門欄位資訊也會空白。
-   修正此問題：從內部部署移轉到線上的使用者，會因為防火牆規則而造成登入失敗。
-   新增新的 DWORD 登錄機碼來修正此問題：當使用者從執行 LyncAutoD 的外部網路登入用戶端，用戶端會將 OAuthUsed 登錄機碼重設為 False。若要修正此問題，請將 HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\> 下的 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket 值設定為 1。

### <a name="visio-feature-updates"></a>Visio：功能更新
-   **從 Excel 資料製作圖表︰** 使用新的「資料視覺化工具」範本，從 Excel 資料自動建立「基本流程圖」或「交互功能流程圖」。 [詳細資訊](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **安全連結：** 當使用者按一下連結時，Office 365 進階威脅防護 (ATP) 會檢查是否為惡意的連結。如果連結被視為惡意，系統就會將使用者重新導向至警告頁面而非原始的目標 URL。 [詳細資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio：非安全性更新
-   修正此問題：在檔案圖示或檔案名稱上按兩下以開啟 Visio 檔時，COM 增益集沒有收到文件開啟的事件。

### <a name="word-feature-updates"></a>Word：功能更新
-   **插入線上圖片：** 用以選取影像和屬性資訊的新登陸頁面會隨著影像自動插入。
-   **Alt 文字建立︰** 雲端式服務會自動為文件中的圖片產生替代文字 (Alt 文字)。
-   **共用的檔案活動︰** 選擇檔案右上角的 [活動] 按鈕，以查看在商務用 OneDrive 或 SharePoint 中共用檔案的共用、編輯、重新命名或還原。
-   **安全連結：** 當使用者按一下連結時，Office 365 進階威脅防護 (ATP) 會檢查是否為惡意的連結。如果連結被視為惡意，系統就會將使用者重新導向至警告頁面而非原始的目標 URL。 [詳細資訊](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **共用檔案中的變更**：檢視誰在共用文件中進行了變更，以及將文件還原到舊版。[詳細資訊](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-security-updates"></a>Word：安全性更新
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11826)：Microsoft Office 記憶體損毀弱點
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
-   [Advisory 170020](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV170020)：Microsoft Office 深度防禦更新
-   [Advisory 170021](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV170021)：Microsoft Office 深度防禦更新

### <a name="word-non-security-updates"></a>Word：非安全性更新
-   修正此問題：當使用者嘗試對商務用 OneDrive 上的現有文件執行 [另存新檔] 時，Word 會當機，並取消儲存作業或嘗試合併現有變更。
-   修正此問題：正在儲存同步備份檔案時，Office 無法寫入磁碟，但 Office 會不斷上傳檔案到 OneDrive。有了此修正程式之後，使用者現在會看到一則錯誤訊息，且 Office 不會繼續上傳。
-   修正此問題：如果使用者在開啟 Word 後立刻瀏覽至 [插入] 索引標籤，Word 可能會停止回應。
-   修正此問題：按一下邊界之後，輸入字元時，字元會顯示在畫面左上角。
-   修正此問題：從比 SharePoint Server 2016 更早版本的 SharePoint Server 開啟文件的 [活動] 窗格時，Word 會當機。
-   修正此問題：載入 Grammarly 增益集時 Word 會意外關閉。
-   修正此問題：在某些情況下，嘗試復原雲端型檔案時 Word 會損毀。
-   修正此問題：無法旋轉繪圖畫布中圖形。
-   修正此問題：當輸入韓文時，母音和元音會不正確地分開。
-   將文件儲存為 PDF 格式 (儲存文件為版本 1.7 PDF)。

### <a name="office-suite-security-updates"></a>Office 套件：安全性更新
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8570)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8630)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-8744)：Microsoft Office 記憶體損毀弱點
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11825)：Microsoft Office 遠端程式碼執行弱點
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2017-11882)：Microsoft Office 記憶體損毀弱點
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/CVE-2018-0795)：Microsoft Office 遠端程式碼執行弱點
-   [Advisory 180003](https://portal.msrc.microsoft.com/zh-TW/security-guidance/advisory/ADV180003)：Microsoft Office 深度防禦更新

### <a name="office-suite-non-security-updates"></a>Office 套件：非安全性更新
-   為 Office 365 德國方案的網域使用者新增單一登入 (SSO) 的支援，該方案的身分識別與內部部署的 Active Directory 同盟。
-   新增功能以避免未成年人獲取和啟動來自 Office 市集的 Office 增益集。
-   修正在動態 DPI 環境下的 Office 增益集中縮放與調整大小的問題。
-   修正此問題：即使目前已安裝 Office 365 ProPlus，Office 設定服務提供者 (CSP) 的 CurrentStatus 節點仍會傳回空字串。
-   修正此問題：因為同一部電腦上所有的 Office 應用程式版本會共用 .box 檔案，而導致 .box 檔案格式變更；該問題會影響同一部電腦上所安裝舊版 Office 的功能。
-   修正此問題：在使用共用電腦啟用的某些情況下，出現一則錯誤訊息，表示應用程式發生錯誤，以致無法正常運作並詢問使用者是否要執行修復。
-   修正此問題：線上修復進度不會向使用者顯示。
-   修正此問題：Office 檔案屬性未顯示在 [檔案總管] 中。
-   修正此問題：開啟第二份文件時，Office 增益集按鈕會從功能區消失。
-   修正此問題：無法開啟某些名稱具有雙位元組字元的 VBA 模組。
-   修正此問題：「新增功能」對話方塊無法顯示。
-   修正此問題：按一下 [繪圖] 索引標籤會造成部分使用者的應用程式損毀。
-   修正此問題：在其上有工具提示的「通用控制項」停留時，會造成應用程式損毀。
-   修正此問題：使用「通用控制項」時，出現授權錯誤訊息。
-   修正此問題：某些程式檔案簽章的方式發生問題，導致防毒程式標幟這些檔案，以及在 Windows 資訊保護 (WIP) 底下保護或存取資料的問題。
-   新增 support.to 可允許使用者在 64 位元版本的 Office 開啟含有 mscomctl.ocx 控制項的巨集檔案。
-   改善在 mscomctl.ocx 中使用之控制項的協助工具。
-   修正此問題：Ribbon 或快速存取工具列自訂對話方塊中缺少指令。



## <a name="version-1705-january-9"></a>版本 1705：1 月 9 日
*版本 1705 (組建 8201.2217)*

*這是自從 2017 年 9 月以來提供的順延通道版本。它會繼續受到支援並接收安全性更新，直到 2018 年 7 月為止。不過，目前已提供新的半年通道版本 — 1708 版 (組建 8431.2153) — 其中包含了新功能、安全性更新和非安全性更新。*

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