---
title: 2020 年每月企業通道版本的版本資訊
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2020 年 Microsoft 365 Apps 每月企業通道版本的版本資訊
ms.openlocfilehash: f76ceaf76f505d9a4301f2bba66c9efcb6278ca4
ms.sourcegitcommit: 9fba85e39543d5fa71669437ad88913c574c4371
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/15/2020
ms.locfileid: "45138679"
---
# <a name="release-notes-for-monthly-enterprise-channel-releases-in-2020"></a>2020 年每月企業通道版本的版本資訊

這些版本資訊提供新功能和非安全性更新的相關資訊，這些功能和非安全性更新包含在 2020 年 Microsoft 365 Apps 企業版、Microsoft 365 Apps 商務版，以及 Project 和 Visio 版的傳統型應用程式訂閱版本的每月企業通道更新。

> [!IMPORTANT]
> 我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。 如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。

[//]: # (DO NOT REMOVE)



## <a name="version-2005-july-14"></a>版本 2005：7 月 14 日
*版本 2005 (組建 12827.20538)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。 [深入了解](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

### <a name="word"></a>Word

- **用其他方式表達：** 當您想要以不同方式表達時，「重寫」功能可以幫助您。 重寫提供其他不同方式來表達您的詞彙。<br />在[部落格文章](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/)中查看詳細資料


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 已修正問題；您應該可以呼叫日期/時間延伸資料類型至您的程式碼，而不會在您的應用程式中遇到任何當機。

- 已修正問題；您現在可以還原為最新的 Access 版本，並使用 DAO/VBA 來管理及編輯十進位資料類型。

### <a name="excel"></a>Excel

- 已修正當 Excel 視窗透過 Teams 共用時，使用 Ctrl + Shift + 方向鍵滑動後，Excel 可能會無法回應的問題。

- 在某些情況下，按一下同一個活頁簿中某個位置的超連結會導致活頁簿被隱藏。

- 已修正當儲存至 SharePoint/OneDrive 時，會導致自訂功能區索引標籤 CustomUI XML 的問題。

- 解決嘗試將樞紐分析表插入圖表時 Excel 可能會當機的問題。

### <a name="outlook"></a>Outlook

- 已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。

- 解決導致在[建議功能]中尋找功能沒有結果並未留給使用者選項以提交新功能點子的問題。

- 解決導致使用者看到 Outlook 持續提示他們執行收件匣修復工具的問題。

- 解決問題：導致 Windows 10 伺服器版本的使用者看到警告 [防毒軟體狀態: 未安裝。 這個版本的 Windows 支援防毒偵測，但找不到任何防毒軟體。]，即使已正確安裝防毒軟體。

- 解決會導致使用者在某些情況下遇到間歇性懸置和當機的問題。

- 解決導致 [共用行事曆] 改善的使用者查看行事曆失敗的問題。

- 解決會導致使用者在 Outlook 中更新其規則時，看到 [此電腦上的規則與 Microsoft Exchange 上的規則不相符] &quot;&quot;訊息的問題。

- 解決會導致使用者看到他們透過拖放附件，以複製到其檔案系統所建立附件的建立日期設為 4501 年 1 月 1 日的問題。&nbsp;

- 解決 Outlook 無法為已支付 M365 Business Plus 方案服務的使用者啟用「資料外洩防護」原則提示的問題。

- 解決有回覆/轉寄標籤的 clp 審查事件的問題。


### <a name="powerpoint"></a>PowerPoint

- 這可修正使用者在同一檔案中同時有新版和舊版批註，因此觸發批註的升級而當機的問題。

- 我們已修正建議窗格的當機問題。


### <a name="project"></a>Project

- 已修正當專案摘要工作-或是專案[開始/工作]欄位有變更時，ProjectBeforeTaskChange 事件不會觸發的問題。

- 已修正當標示為100% 完成之工作錯誤地變更為完成度低於100% 的問題。

### <a name="skype"></a>Skype

- 當使用者收到將他們移至 Teams Only 的原則時，他們仍然可以使用商務版 Skype Outlook 增益集來排程會議。 在此更新之後，當客戶端讀取指示用戶為 Teams Only 的策略並進入僅限會議加入模式後，您將不再能用商務版 Skype 安排會議。 此外，如果商務版 Skype Outlook 增益集發現商務版 Skype 用戶端處於 [僅限會議加入] 模式，就無法自行啟動。

### <a name="word"></a>Word

- 解決會導致從應用程式拖曳部分內容時遇到當機的問題。

### <a name="office-suite"></a>Office 套件

- 此變更會解決載入和播放動畫內容 (例如 Gif 或3D 模型) 時可能會發生的懸置。

- 我們透過設定Bing附加預設安裝驗證設定為true默認，並將MSI返回成功視為安裝成功，而解決了 ValidateInstall 失敗率問題。

- 此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。

- 當您啟用增益集，而登錄金鑰 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 被設為零時，辦公主機視窗會當機。 這變更將修正此問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-july-14"></a>版本 2004：7 月 14 日
*版本 2004 (組建 12730.20602)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2004-june-09"></a>版本 2004: 6 月 09 日
*版本2004（組建12730.20430）*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **按幾下就能新增資料表：** 使用 [新增資料表] 工作窗格，當您工作時，該窗格會保持開啟狀態，以便將資料表新增至關聯和查詢。 [深入了解](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a>Excel

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。<br />在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料

- **Facebook 連接器支援即將結束：** 於 2020 年 4 月起，Excel 就不再支援使用 Facebook 連接器的外部資料連線。

- **讓活頁簿更生動的新影像：** 您可以在活頁簿中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />在[部落格文章](https://blog-insider.office.com/2020/04/06/premium-creative-content/)中查看詳細資料

### <a name="outlook"></a>Outlook

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。<br />在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料

- **將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。 您拖曳的郵件將會與所有群組成員共用。<br />在[部落格文章](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)中查看詳細資料

- **行事曆煥然一新：** 查看視覺更新，讓您的行事曆更容易流覽。 [深入了解](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />在[部落格文章](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)中查看詳細資料

- **讓郵件更生動的新影像：** 您可以在電子郵件中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />在[部落格文章](https://blog-insider.office.com/2020/04/06/premium-creative-content/)中查看詳細資料

### <a name="powerpoint"></a>PowerPoint

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。<br />在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料

- **在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。 [深入了解](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />在[部落格文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看詳細資料

- **讓投影片更生動的新影像：** 您可以在投影片中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />在[部落格文章](https://blog-insider.office.com/2020/04/06/premium-creative-content/)中查看詳細資料

### <a name="word"></a>Word

- **對筆跡使用套索：**[繪圖] 索引標籤上的 [套索] 工具，可協助您選取使用筆跡繪製的物件。 選取個別筆劃或整個字。 [深入了解](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **挑選完美色彩：** 使用十六進位色彩代碼來選擇您想要的字型色彩、文字醒目提示等。<br />在[部落格文章](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)中查看詳細資料

- **讓文件更生動的新影像：** 您可以在文件中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />在[部落格文章](https://blog-insider.office.com/2020/04/06/premium-creative-content/)中查看詳細資料

### <a name="office-suite"></a>Office 套件

- **敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正當檔案路徑太長時，在檔案重新開啟之後外部連結會停止運作的問題。

- 在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。

- 在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。

- 已修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。

### <a name="outlook"></a>Outlook

- 已解決在從系統管理人通知中提交意見反應時，使用者遇到當機的問題。

- 已解決導致使用者在退出 Outlook 時遇到掛斷的問題。

- 解決在顯示快顯通知時，使用者遇到當機的問題。

- 已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。

- 已解決導致 Outlook 在某些 Windows 組建上當機的問題。

- 已解決導致資料夾窗格寬度意外變更的問題。

### <a name="project"></a>Project

- 在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。

- 已修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。

### <a name="office-suite"></a>Office 套件

- 修正了當嘗試硬連結符號連結時，導致更新失敗的 [點擊運作] 問題。

- 當您啟用增益集，而登錄金鑰 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 被設為零時，辦公主機視窗會當機。 這變更將修正此問題。

- 此修正可解決同時防止限制存取和保護設有密碼之檔案的錯誤。

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。

- 此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-june-09"></a>版本 2003: 6 月 09日
*版本2003（組建12624.20708）*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="office-suite"></a>Office 套件

- 此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-may-12"></a>版本 2003：5 月 12 日
*版本 2003 (組建 12624.20588)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。 在 SQL 檢視中搜尋及取代文字。 在 [關聯圖] 視窗中選取多個資料表。

### <a name="excel"></a>Excel

- **輸入會傳回多個值的公式**：現在您可以快速輸入公式來傳回多個值，並且值會自動溢出至相鄰的儲存格。 [深入了解](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br />在[部落格文章](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)中查看詳細資料

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。

- **六個功能強大的函數：** 我們新增了六個新的函數，讓您的試算表功能更強大：FILTER、SORT、SORTBY、UNIQUE、SEQUENCE 和 RANDARRAY。 [深入了解](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- **向左看，向右看... XLOOKUP 在這裡！：** 一列接著一列，在含有 XLOOKUP 的表格或範圍中尋找您需要的項目。 [深入了解](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br />在[部落格文章](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)中查看詳細資料

- **即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。

### <a name="outlook"></a>Outlook

- **搜尋人員時取得電子郵件建議：** 當您在 [搜尋] 方塊中輸入人員的名稱時，最相關的電子郵件訊息會包括在您的搜尋建議中。 [深入了解](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- **群組命名原則：** 群組命名原則可讓 IT 系統管理員將組織中使用者所建立群組的名稱標準化及管理。 系統管理員可以要求在建立群組時，將特定首碼和尾碼新增至群組的名稱，而且可以封鎖使用特定字詞。 這有助於將群組名稱中使用不當字詞的情況最小化，以及 IT 管理其目錄中群組的表示方式。 命名原則也可協助部署小組網站的組織根據部門來分類。

- **加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。 將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。

- **受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？ Outlook 現在會偵測這項要求並協助您取得連結。

### <a name="powerpoint"></a>PowerPoint

- **在 PowerPoint 中快速即時共同作業：** 在 PowerPoint 中快速即時共同作業

- **線上影片有新的首頁：** 將影片儲存至 Microsoft Stream，讓組織中的任何人都看得到。 插入影片連結，享受檔案大小只有原來一小部分的多媒體簡報。 [深入了解](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。

- **jiffy 中的 Gif：** 一個投影片、一個圖文框。 在 PowerPoint 中輕鬆建立迴圈 Gif。 [深入了解](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br />在[部落格文章](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)中查看詳細資料

- **更好的圖表：** 使用更完善的連接線和更平滑的筆跡轉換程式，您可以自信地用筆跡繪製您的想法。 [深入了解](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。<br />在[部落格文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看詳細資料

### <a name="word"></a>Word

- **不必再來回往返瀏覽器：** 您決定開啟 Office 文件連結的方式：在瀏覽器或應用程式中開啟。

- **其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。

### <a name="office-suite"></a>Office 套件

- **以漸進方式開啟大型檔案：** 即使大型 PowerPoint 簡報的某些部分 (例如大型視訊或影像) 還沒有下載完成，還是能夠下載、開啟並與之互動。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel

- 在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。

- 解決當來源活頁簿關閉時，外部連結無法在填入時更新的問題。


### <a name="onenote"></a>OneNote

- 透過暫時變更建立頁面版本歷程記錄的頻率，可改善同步處理與服務的穩定性。


- 透過暫時停用將頁面移動至資源回收桶，來改善同步處理與服務的穩定性。 若使用者想要刪除頁面，則會改為顯示詢問是否要永久刪除頁面的對話方塊。


- 透過暫時將 OneNote 2016 中新嵌入附件的最大允許大小減少為 50MB，來改善同步處理與服務的穩定性。 對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。


- 透過暫時停用 OneNote 2016 中的應用程式內視訊錄製，來改善同步處理與服務的穩定性。 本機筆記本不受這個值的影響。


- 透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。


- 透過在資訊列中通知使用者有關 Microsoft OneNote 中的暫時調整之資訊，可協助改善在高全球使用狀況時的同步處理與服務可用性。


### <a name="outlook"></a>Outlook

- 已解決導致使用者在工作管理員中看到 Outlook 處理序延遲的問題。


- 解決使用滑鼠上的按鈕時，導致使用者偶爾發生當機的問題。


- 解決使用者在第三方 MAPI 應用程式中遇到當機的問題。


- 已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。


- 已解決導致 Outlook 在某些 Windows 組建上當機的問題。


- 已解決導致資料夾窗格寬度意外變更的問題。


### <a name="project"></a>Project

- 修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。


- 修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。


- 修正無法正確計算摘要工作日期的問題。


- 修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。


- 修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。


- 修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。


- 修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。


- 在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。


### <a name="word"></a>Word

- 解決使用滑鼠上的「X」按鈕時，導致使用者偶爾遇到當機的問題。

### <a name="office-suite"></a>Office 套件

- 此修正可解決同時防止限制存取和保護設有密碼之檔案的錯誤。

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE END)

> [!NOTE]
> 如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|MEC|生產|功能|16.0.12827.20538|版本-2005-14|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
