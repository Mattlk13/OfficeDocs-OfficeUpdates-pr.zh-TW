---
title: 2020中目前通道版本的發行附注
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為 IT 專業人員提供 2020 年 Microsoft 365 Apps 每月通道版本的版本資訊
ms.openlocfilehash: 13bb14c00a9066c7437cde9a00f94a078788d5c5
ms.sourcegitcommit: 1f8cb906d8d0af5eb26eaedf008180375d2fd55d
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/09/2020
ms.locfileid: "44668008"
---
# <a name="release-notes-for-current-channel-releases-in-2020"></a>2020中目前通道版本的發行附注

這些版本資訊中提供的新功能和非安全性更新的相關資訊，在2020中的 Microsoft 365 應用程式適用于企業、Microsoft 365 商務用應用程式，以及適用于 Project 和 Visio 的桌面應用程式訂閱版本。

> [!IMPORTANT]
> 我們會變更 Microsoft 365 應用程式的更新通道，包括新增新的更新通道 (每月企業通道)，並變更現有的更新通道名稱。 如需深入了解，[請閱讀本文](https://go.microsoft.com/fwlink/p/?linkid=2127441)。

 > [!NOTE]
>
>- 我們通常會在一段時間內，將功能（甚至也是修正）推廣到目前。  如果您現在沒有看到如下所述的項目，您可以預期它近期會推出。 [深入了解](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-09"></a>版本2005：6月9日
*版本2005（組建12827.20336）*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 解決在嘗試將 PivotTables 插入圖表工作表時，Excel 可能會損毀的問題。

### <a name="powerpoint"></a>PowerPoint

- 這會修正使用者在檔案中同時有新式和舊版批註時的損毀，因此會觸發對批註的升級。

### <a name="project"></a>Project

- 已修正此問題：當專案摘要任務（專案開始/任務欄位）變更時，不會觸發 ProjectBeforeTaskChange 事件。

### <a name="office-suite"></a>Office 套件

- 我們已解決 ValidateInstall 失敗率問題，方法是將 Bing 載入項預設安裝驗證設定為 true，並考慮 MSI 傳回成功為安裝成功。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-02"></a>版本2005：02年6月
*版本2005（組建12827.20268）*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **自動使用新的資料類型：** 當您輸入類似股票或地理位置的資料值時，Excel 會將其轉換為正確連接的資料類型-股票或地理位置。 [深入了解](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **使用動畫 Gif 告訴您故事：** 動態 Gif 現在可在 Office 編輯器中支援-您的檔只是 snazzier

### <a name="outlook"></a>Outlook

- **協助保護群組中的資料：** 建立群組時所選擇的「敏感度」標籤會套用到群組電子郵件、文件及小組網站

- **更好的結果—瞬間：** 我們更新了搜尋體驗，讓這個版本比以往更聰明、更快速，且更可靠。 [深入了解](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **使用動畫 Gif 告訴您故事：** 動態 Gif 現在可在 Office 編輯器中支援-您的檔只是 snazzier

- 行事**曆取得 makeover：** 請參閱視覺更新，讓您的行事曆更容易掃描。 [深入了解](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />在[部落格文章](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)中查看詳細資料

### <a name="powerpoint"></a>PowerPoint

- **使用動畫 Gif 告訴您故事：** 動態 Gif 現在可在 Office 編輯器中支援-您的檔已經 snazzier[深入瞭解](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

- **在簡報時同步處理變更：** 即使簡報處於投影片放映模式，仍可即時同步處理所做的變更。 [深入了解](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />在[部落格文章](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)中查看詳細資料

- **不需要簡報導覽裝置：您的 earbuds 包括：** 使用表面 Earbuds 來控制您的 PowerPoint 簡報。 其運作方式：配對後，您必須在 PowerPoint 啟用該功能。 按 F5 或選取 [投影片放映 > 從頭開始播放簡報。  在 [投影片放映] 中，以滑鼠右鍵按一下投影片，並在 [表面 Earbuds 設定] 下方，選擇 [使用勢來控制簡報]  所有未來的簡報都會記住此設定。 您現在可以向前及向後滑動左側 earbud，以在投影片放映模式中流覽您的簡報。  按兩下以播放或暫停內嵌影片。  重要：您必須在適用于 Windows 10 的「表面音訊」應用程式中搭配您的 Surface Earbuds，以便使用筆勢控制簡報。 在 Windows 10 上開始使用表面音訊應用程式的指示可于這裡取得。 [深入了解](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a>Teams

- **對小組會議中的影片版面配置所做的變更：** 不久，小組會議期間可同時查看的參與者人數會從4增加至9。

- **在 live 事件中包含系統音訊：** 在即時事件期間共用桌面或視窗畫面時，live 事件中的簡報者和發生器現在可以包含系統音訊。 這可讓您的使用者聽到您共用內容的任何音訊部分。

- **讓召集人可以變更撥入參與者的前廳流覽設定：** 此設定會控制以電話撥號的使用者是否直接加入會議，或不論 [自動承認人員] 設定，是否等候會議廳。

- **在會議中舉手：** 現在使用者可以在會議中提升虛擬手！ 其他參與者會在會議階段和您的名單中的名字旁，看到您的名字旁邊的凸起。

- **自訂會議影片背景：** 當您使用影片會議時，您現在可以選擇要使用的不同靜態背景圖像。 這可讓您顯示此影像，而不是您坐在何處的實際背景。

- **新增更多人員進行聊天：** 我們現在可以將最多350人員新增至單一聊天線程。

- **設定會齒輪您的活動摘要：** 使用者現在可以透過設定齒輪的方式，直接從摘要左軌存取活動摘要和通知設定。

- 在**進行中的團隊會議中輕鬆存取會議選項：** 當小組會議開始時，可直接在參與者窗格中提供輕鬆存取的連結，讓會議召集人快速且輕鬆地變更其簡報者和前廳設定。 這項新功能將會出現在排程和「立即開會」會議上。

- **小組和通道分析：** 除了小組分析之外，現在您還可以查看通道層級的計量與深入瞭解。 我們也將時間週期提升為90天，讓您可分析較長時間的資料。 除此之外，此版本也包含有關小組或管道的文章總數、回復和會議的新度量和圖表。

- **進入/出口宣告：** 我們新增這項功能，讓會議召集人能夠開啟或關閉會議的進入及關閉宣告。

### <a name="word"></a>Word

- 在**不留下文字的情況下解碼縮寫：** 當您遇到縮寫時，Word 會嘗試根據其他人的使用方式來定義它。

- **使用動畫 Gif 告訴您故事：** 動態 Gif 現在可在 Office 編輯器中支援-您的檔只是 snazzier


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題

### <a name="excel"></a>Excel

- 已修正此問題：使用 Ctrl + Shift + 箭號鍵，在 Excel 視窗透過團隊共用時，Excel 可能會停止回應。

- 在某些情況下，按一下相同活頁簿中某個位置的超連結，就會隱藏該活頁簿。

### <a name="outlook"></a>Outlook

- 解決 [回復/轉寄] 標籤的 clp 審核事件問題。

- 解決導致 Windows 10 伺服器版本使用者無法看到警告「防毒程式狀態：無效」的問題。 此版本的 Windows 支援防病毒偵測，但即使已正確安裝防毒軟體，仍未找到防毒軟體。

- 解決了使用者從系統管理員通知提交意見反應時遇到損毀的問題。

### <a name="skype"></a>Skype

- 當使用者獲得只將其移至小組的原則時，他們仍然可以使用商務用 Skype Outlook 增益集來排程會議。 在此更新之後，用戶端將無法再排程商務用 Skype 會議。用戶端讀取指出使用者只有小組的原則，並進入僅限會議加入模式。 此外，商務用 Skype Outlook 增益集會在啟動時不會自行啟用（如果它看到商務用 Skype 用戶端為會議僅限加入模式）。

### <a name="office-suite"></a>Office 套件

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。

- 此更新解決了 Microsoft Office 中的一個問題：可能無法在執行時期正確找到 Visual Basic for Applications 專案，這些專案的參照預期透搜尋 PATH 環境變數指定的位置來找到，進而導致VBA 執行時期錯誤。

- Office 主應用程式在 windows 中已崩潰，當登錄機碼 HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth 設定為0時，便會啟用增益集。 這種變更可修正此問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-21"></a>版本2004：5月21日
*版本2004（組建12730.20352）*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 已修正此問題：如果檔路徑過長，外部連結會在重新開啟檔案後停止運作。


### <a name="outlook"></a>Outlook

- 解決了使用者從系統管理員通知提交意見反應時遇到損毀的問題。


### <a name="office-suite"></a>Office 套件

- 已修正 Click-to-Run 問題，導致最新的組建偶然更新失敗。

- 修正此問題：在 Microsoft Office 中，您可能無法在執行時間找到透過搜尋路徑環境變數中所指定的位置來找到的 Visual Basic for Applications 專案，進而導致 VBA runtime 錯誤。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-12"></a>版本 2004：5 月 12 日
*版本 2004 (組建 12730.20270)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決在顯示快顯通知時，使用者遇到當機的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-04"></a>版本 2004：5 月 4 日
*版本 2004 (組建 12730.20250)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="office-suite"></a>Office 套件

- 此更新修正了 Microsoft Office 中 Visual Basic for Applications 中的問題，其中特定 VBA 專案參考了程式庫名稱或程式庫路徑中有 DBCS 字元的程式碼程式庫，因而在載入時被 Office 應用程式視為損毀。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a>版本 2004：4 月 29 日
*版本 2004 (組建 12730.20236)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="access"></a>Access

- **在查詢設計工具、SQL 檢視和關聯視窗中工作時更具生產力：** 在資料表上按一下滑鼠右鍵即可開啟、設計、調整大小及隱藏它。 在 SQL 檢視中搜尋及取代文字。 在 [關聯圖] 視窗中選取多個資料表。

- **按幾下就能新增資料表：** 使用 [新增資料表] 工作窗格，當您工作時，該窗格會保持開啟狀態，以便將資料表新增至關聯和查詢。 [深入了解](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a>Excel

- **Facebook 連接器支援即將結束：** 於 2020 年 4 月起，Excel 就不再支援使用 Facebook 連接器的外部資料連線。

- **有問題嗎？請詢問 Excel：** 現在 Excel 創意可讓您提問有關資料的問題-不需要花時間寫入公式（僅提供英文版）。 [深入了解](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **讓活頁簿更生動的新影像：** 您可以在活頁簿中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a>Outlook

- **加入會議而不需離開您的收件匣：** 不需切換至您的行事曆即可加入線上會議。 將行事曆釘選到 [待辦事項] 窗格之後，只要按一下就能加入任何會議。

- **讓郵件更生動的新影像：** 您可以在電子郵件中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- **週期性會議的位置建議支援：** 搜尋會議室，並排定週期性會議。

### <a name="powerpoint"></a>PowerPoint

- **在投影片放映期間更新投影片：** 在簡報期間，更新由其他作者變更的投影片。

- **讓投影片更生動的新影像：** 您可以在投影片中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a>Teams

- **增強 Teams 行事曆功能：** 以滑鼠右鍵按一下行事曆中的項目，以展開 RSVP 選項，開始與會議參與者交談，或在會議開始時快速加入會議。 我們也改善了活動排程表單。

- **抓到你了！：** 建立標籤並將人員指派至標籤，您就可以 @mention 群組、角色、部門等。小組擁有者可以自行嘗試。 移至某個小組，選取 [其他選項]、[管理標籤]。

### <a name="word"></a>Word

- **讓您的工具方便使用：** 在您的繪圖工具箱中，尋找智慧筆，以便在文字中加入筆跡筆勢。 [深入了解](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **讓文件更生動的新影像：** 您可以在文件中使用的數千個免版稅圖庫影像、圖示和貼紙。 移至 [插入] > [圖片] > [圖庫影像] 以開始使用。 [深入了解](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 在 Excel 2016 中使用數位簽章所儲存的活頁簿，會在於目前版本的 Excel 中開啟時導致簽章失效。

- 已修正在複製含有樞紐分析表的工作表後，會於某些情況下導致 Excel 當機的問題。

- 在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函式中運作。

### <a name="outlook"></a>Outlook

- 已解決導致資料夾窗格寬度意外變更的問題。


- 已解決導致 Outlook 在某些 Windows 組建上當機的問題。


- 已解決在 Windows 更新後，開啟儲存在本機的 msg 或 .oft 檔案會導致 Outlook 當機的問題。


- 已解決導致 Outlook 在某些 Windows 組建上當機的問題。


- 已解決導致使用者在退出 Outlook 時遇到掛斷的問題。


### <a name="project"></a>Project

- 在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。


- 已修正如果您使用的是連線至 Project Web App 的 Project，且小數分隔符號是逗號，當您嘗試將延遲新增至相依性時，TaskDependencies Add 方法會失敗的問題。

### <a name="office-suite"></a>Office 套件

- 已解決同時防止限制存取和保護設有密碼之檔案的錯誤。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-15"></a>版本 2003：4 月 15 日
*版本 2003 (組建 12624.20466)*
* 各種錯誤和效能修正。

## <a name="version-2003-april-14"></a>版本 2003：4 月 14 日
*版本 2003 (組建 12624.20442)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 在某些情況下，Application.Evaluate (VBA) 無法在使用者定義的函數中運作。

### <a name="outlook"></a>Outlook

- 解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。

### <a name="project"></a>Project

- 在表單檢視中編輯前置/後續任務資料時，會觸發額外的 ProjectBeforeTaskChange 事件。

### <a name="word"></a>Word

- 解決使用滑鼠上的「X」按鈕時，導致使用者偶爾發生當機的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a>版本 2003：3 月 31 日
*版本 2003 (組建 12624.20382)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="onenote"></a>OneNote

- 透過暫時停用將頁面移動至資源回收桶，來改善同步處理與伺服器的穩定性。 若使用者想要刪除頁面，則會改為顯示詢問是否要永久刪除頁面的對話方塊。

- 透過在資訊列中通知使用者有關 Microsoft OneNote 中的暫時調整之資訊，可協助改善在高全球使用狀況時的同步處理與服務可用性。

- 透過暫時變更建立頁面版本歷程記錄的頻率，可改善同步處理與服務的穩定性。

### <a name="project"></a>專案

- 修正了當開啟保護實際工作的設定時，使用者無法輸入分時期基準工時的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-25"></a>版本 2003：3 月 25 日
*版本 2003 (組建 12624.20320)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="outlook"></a>Outlook

- **將電子郵件拖曳到您擁有的群組：** 從您的 [收件匣] 拖曳郵件和交談以將它們移動和複製。 您拖曳的郵件將會與所有群組成員共用。

- **受限 WiFi 網路的新體驗：** 是否曾經加入需要登入網頁的 WiFi 網路呢？ Outlook 現在會偵測這項要求並協助您取得連結。

### <a name="word"></a>Word

- **其他人更快速看到您的變更：** 共同撰寫增強功能表示，共同作業者可較以往更快速看到您的變更。

### <a name="office-suite"></a>Office 套件

- **敏感度標籤**：您現在可以套用組織設定、用來提示您輸入自訂權限的敏感度標籤。


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 重複開啟內嵌在 Word 或 PowerPoint 中的活頁簿時，在某些情況下，Excel 會當機。

- 解決當來源活頁簿關閉時，外部連結無法在填入時更新的問題。

- 解決從範本建立圖表時的效能問題。

### <a name="onenote"></a>OneNote

- 透過暫時減少新嵌入附件的最大允許尺寸至 50MB，來改善同步處理與服務的穩定性。 對於超過此限制的檔案，使用者可以選擇將檔案上傳到 OneDrive，並將連結插入 OneNote。

- 透過暫時停用 OneNote 2016 中的應用程式內視訊錄製，來改善同步處理與服務的穩定性。 本機筆記本不受這個值的影響。

- 透過暫時調整 OneNote 2016 中的同步處理頻率，來改善同步處理與服務的穩定性。

### <a name="outlook"></a>Outlook

- 已解決導致使用者在工作管理員中看到 Outlook 處理序延遲的問題。

### <a name="powerpoint"></a>PowerPoint

- 已改善複製貼上的案例：將 PowerPoint 投影片中的圖形複製並貼到迴圈中的其他投影片，可能會出現例外狀況而失敗。


### <a name="project"></a>Project

- 修正透過 [已停用] 按鈕停用/啟動工作時，ProjectBeforeTaskChange 事件無法偵測的問題。

- 修正儲存使用舊版 Project 建立的專案時，Project 可能當機的問題。

- 修正在將任務標示為完成之後，不正確地將任務完成百分比變更為低於 100% 的值的問題。

- 修正無法正確計算摘要任務日期的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-10"></a>版本 2002：3 月 10 日
*版本 2002 (組建 12527.20278)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="project"></a>Project

- 修正不先執行 OpenUndoTransaction 方法就不能觸發 OnUndoOrRedo 事件的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-01"></a>版本 2002：3 月 1 日
*版本 2002 (組建 12527.20242)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="outlook"></a>Outlook

- 解決導致協力廠商應用程式無法傳送電子郵件的問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-25"></a>版本 2002：2 月 25 日
*版本 2002 (組建 12527.20194)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **使用者現在可以在 Word 和 Excel 中將物件儲存為 SVG：** 使用者可以將圖表、圖案、筆跡、圖示、圖片等物件儲存為 SVG。 [深入了解](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **活頁簿統計資料：** 我們會計算儲存格、公式、圖表、表格，這樣您就不需要計算。

- **查詢編輯器中的資料分析：** 取得欄位資料的總覽分析、識別錯誤和空白值，查看分佈長條圖等。

### <a name="word"></a>Word

- **使用者現在可以在 Word 和 Excel 中將物件儲存為 SVG：** 使用者可以將圖表、圖案、筆跡、圖示、圖片等物件儲存為 SVG。 [深入了解](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 修正 CUBEVALUE 函數有時會傳回不正確結果的問題。

### <a name="outlook"></a>Outlook

- 解決導致會議的位置欄位中的逗號變成分號的問題。

- 解決在多個視窗中檢視相同項目時可能會導致當機的問題。

- 已解決導致在某些情況下無法使用相關選項來停用標幟項目醒目提示的問題。

- 解決即使將同步處理滑桿設定為較小的設定，也會導致 Outlook 非預期地同步處理所有郵件的問題。


- 解決的問題導致使用黑色主題的使用者看到白色背景上的「寄件者」下拉式顯示白色文字。


- 此變更會還原在郵件標頭中檢視多行主旨的功能。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-february-19"></a>版本 2001：2 月 19 日
*版本 2001 (組建 12430.20288)*
* 各種錯誤和效能修正。

## <a name="version-2001-february-11"></a>版本 2001：2 月 11 日
*版本 2001 (組建 12430.20264)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- Access 範本應不再導致資料庫中的附件欄出現故障。 個體化範本後，您現在應該可以將附件欄新增至資料庫。

### <a name="excel"></a>Excel

- 已修正未顯示操作功能表中的註解命令的問題。

- 已修正以下問題：將文字轉換成具有溢出陣列之儲存格的欄時，某些使用者發生當機。


### <a name="outlook"></a>Outlook

- 解決導致使用者在指定無效寄件者地址時發生當機的問題。


- 解決導致使用者在取消帳戶設定時發生當機的問題。


### <a name="project"></a>Project

- 已修正以下問題：固定工期類型的 100% 工作可能會誤將其完成百分比計算為小於 100% 完成。


### <a name="office-suite"></a>Office 套件

- 此變更解決使用 Intel Integrated GPU 的圖形配接卡報告問題。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-january-30"></a>版本 2001：1 月 30 日
*版本 2001 (組建 12430.20184)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新
### <a name="excel"></a>Excel

- **即時讀取與回覆：** 直接從電子郵件回覆註解和提及，而不需開啟活頁簿。

- **向左看，向右看... XLOOKUP 在這裡！：** 一列接著一列，在含有 XLOOKUP 的表格或範圍中尋找您需要的項目。 [深入了解](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a>Outlook

- **進階群組電子郵件設定：** 此功能可協助使用者自訂要在收件匣中接收/追蹤哪些電子郵件或活動。

- **群組命名原則：** 群組命名原則可讓 IT 系統管理員將組織中使用者所建立群組的名稱標準化及管理。 系統管理員可以要求在建立群組時，將特定首碼和尾碼新增至群組的名稱，而且可以封鎖使用特定字詞。 這有助於將群組名稱中使用不當字詞的情況最小化，以及 IT 管理其目錄中群組的表示方式。 命名原則也可協助部署小組網站的組織根據部門來分類。

### <a name="word"></a>Word

- **更安全的影片體驗：** 安全性增強功能可讓您擁有更安全的線上影片體驗。 [深入了解](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- **對筆跡使用套索：**[繪圖] 索引標籤上的 [套索] 工具，可協助您選取使用筆跡繪製的物件。 選取個別筆劃或整個字。 [深入了解](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **將圖形另存為圖片：** 只要按幾下，即可將圖形、圖示或其他物件另存成圖片，便於您於任何其他地方使用。 [深入了解](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此更新會修正使用 ADODB 的問題。 VB 程式碼中的記錄器物件可能會不正確地報告錯誤。


- 此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。


### <a name="excel"></a>Excel

- 解決重新命名簽名時，使用者遇到當機的問題。


### <a name="outlook"></a>Outlook

- 解決重新命名簽名時，使用者遇到當機的問題。


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-january-22"></a>版本 1912：1 月 22 日
*版本 1912 (組建 12325.20344)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="access"></a>Access

- 此更新修正可能會導致 Microsoft Access 無法識別連結的 SQL Server 資料表中的識別資料行的問題，這可能會導致不正確地將資料列報告為已刪除。



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-january-14"></a>版本 1912：1 月 14 日
*版本 1912 (組建 12325.20298)*

安全性更新列於[此處](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-1912-january-08"></a>版本 1912：1 月 8 日
*版本 1912 (組建 12325.20288)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>功能更新

### <a name="outlook"></a>Outlook

- **傳送可存取的郵件給最需要它的人員：** Outlook 會顯示郵件提示，協助確保將您的內容傳送給偏好可存取內容的使用者時可供其存取

### <a name="powerpoint"></a>PowerPoint

- **最佳化您的簡報：** 協助工具檢查程式可協助您以螢幕閱讀器為中心，在投影片上排列物件。

- **jiffy 中的 Gif：** 一個投影片、一個圖文框。 在 PowerPoint 中輕鬆建立迴圈 Gif。 [深入了解](https://support.office.com/en-us/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>解決的問題
### <a name="excel"></a>Excel

- 這項變更透過利用軟體轉譯避免特定 Intel 圖形驅動程式發生問題。

### <a name="outlook"></a>Outlook

- 解決了導致會議位置在清除之後，又會不預期地重新加回會議的問題。

- 解決當使用者透過鍵盤快速鍵與信箱資料夾互動時會造成明顯延遲的問題。

- 解決在某些情況下，導致使用者看到電子郵件傳送到與顯示的 SMTP 位址不相符之地址的問題。

- 解決在擷取雲端設定時，導致使用者在 Outlook 中遇到當機的問題。

### <a name="word"></a>Word

- 組建區塊召集人可能會顯示不正確警示：「您已修改樣式、組建區塊」。

### <a name="office-suite"></a>Office 套件

- 解決 Office 更新可能會非預期地從 Office CDN 而不是預期使用的來源 (例如本機或網路共用或 Configuration Manager 提供的位置) 下載檔案的問題。

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> 如果您需要關於使用 Office 的問題協助，建議您將問題張貼在 [Microsoft Answers 論壇](https://answers.microsoft.com/)或[技術社群](https://techcommunity.microsoft.com/)，或連絡[支援](https://support.microsoft.com/contactus)。
