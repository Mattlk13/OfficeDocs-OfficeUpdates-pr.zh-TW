---
title: Microsoft AutoUpdate (MAU) 的版本歷程記錄
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_Mac
description: 為 IT 專業人員提供 Microsoft AutoUpdate (MAU) 的版本歷程記錄
ms.openlocfilehash: 729073178740f67134e7bcac1c3b4e07a4012ac9
ms.sourcegitcommit: 88a3e983436c7d90f1727d4bf3f20470cb6dafa7
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/12/2022
ms.locfileid: "68525730"
---
# <a name="release-history-for-microsoft-autoupdate-mau"></a>Microsoft AutoUpdate (MAU) 的版本歷程記錄
 
建議您一律更新至最新版本的 Microsoft AutoUpdate (MAU)。

The following table provides release history information for Microsoft AutoUpdate. The table is ordered by release date, with the most recent release date listed first. All update packages are 64-bit.


> [!NOTE]
> 
> - 僅提供最新版的 Microsoft AutoUpdate 下載連結
> - Microsoft AutoUpdate provides updates to various Mac products from Microsoft. Therefore, you might receive a notification to update Microsoft AutoUpdate even if you're not running Office for Mac.

若要檢視版本資訊，請參閱[版本資訊。](release-notes-office-for-mac.md)<br/><br/>

## <a name="october-2022-release"></a>2022 年 10 月版本

**發行日期：** 2022 年 10 月 11 日

*Microsoft AutoUpdate 4.52*

**重大變更：**
- Microsoft AutoUpdate 4.52 和更新版本至少需要 macOS 10.13 High Sierra

**增強功能：**
- 在系統重新開機期間從失敗的更新向前復原或復原的新邏輯
- 重新組織程式碼以減少 Microsoft AutoUpdate 套件的大小
- 改善程式碼健全性，以防止非預期的錯誤

[下載 Microsoft AutoUpdate 4.52 套件](https://officecdnmac.microsoft.com/pr/C1297A47-86C4-4C1F-97FA-950631F94777/MacAutoupdate/Microsoft_AutoUpdate_4.52.22100900_Updater.pkg)<br/>
<br/>
**SHA-256 雜湊：**

C55D8421F3BF30962109AD3569C2EC4EC2BF8DB28C91C74350E030065B136EE0
<br><br>

## <a name="september-2022-release"></a>2022 年 9 月版本

**發行日期：** 2022 年 9 月 13 日

*Microsoft AutoUpdate 4.51*

**增強功能：**
-   如果在 macOS Ventura 上停用在背景中執行，AutoUpdate 現在會顯示警告
- 改善圖形使用者介面中的協助工具
- 期限功能的增強可靠性

**錯誤修正：**
-   修正在設定 GuardAgainstAppModification 時，複製的應用程式在啟動時不正確移除的問題
- 已修正當複製資料夾遺失時，更新小幫手意外關閉的問題


**SHA-256 雜湊：**

EA9E59EB60604AD9785CB0C81BD490DE5C7D32527F1DA7064D4F77226E2DC907
<br><br>

## <a name="august-2022-release"></a>2022 年 8 月版本

**發行日期：** 2022 年 8 月 16 日

*Microsoft AutoUpdate 4.50*

**增強功能：**
- 期限功能的增強功能，以便在使用者看到最終倒數計時之前更新並驗證複製。 這可大幅減少應用程式更新的停機時間量
- 預設檢查間隔已從 12 小時變更為 13 小時，因此更新時間會錯開
- .noindex 的尾碼已新增至 Clones 預備資料夾，以防止焦點編制暫存應用程式套件組合的索引
- IT 系統管理員現在可以設定名為 GuardAgainstAppModification 的新布林值式喜好設定，以便在協力廠商應用程式修改應用程式套件組合時套用二進位差異更新

**錯誤修正：**
- 已修正複製作業失敗時，差異更新未正確套用的問題
- 已修正取消更新無法運作的問題
- 已修正倒數計時器無法顯示超過 99 分鐘的問題
- 已修正 [在尋找程式中顯示] 選項會失敗的問題
- 已修正如果已設定不正確日期/時間，Microsoft AutoUpdate 可能會當機的問題
- 修正了建構下載 URL 時，Microsoft AutoUpdate 可能會當機的問題



**SHA-256 雜湊：**

28F675FA2D1B21CB01DE005DAD1EE6182536DD05489C98AEAADF8BC7550AACD9
<br><br>


## <a name="july-2022-release"></a>2022 年 7 月發行版本

**發行日期：** 2022 年 7 月 12 日

*Microsoft AutoUpdate 4.49*

**增強功能：**
- 已改善透過 Microsoft AutoUpdate 使用者介面更新應用程式的工作流程

**錯誤修正：**
- 已修正當 GUI 上未顯示任何應用程式更新時，Microsoft AutoUpdate 使用者介面會啟動的問題
- 已修正 Microsoft AutoUpdate 可能會在記憶體不足的情況下當機的問題
- 已修正 Microsoft AutoUpdate 在啟動時可能沒有回應的問題

**SHA-256 雜湊：**

2749A0163267E8E24D212BE09012FCB2C09E840EBC2047507D5088DA9629EC04
<br><br>


## <a name="june-2022-release"></a>2022 年 6 月版本

**發行日期:** 2022 年 6 月 14 日

*Microsoft AutoUpdate 4.48*

**增強功能：**
- IT 系統管理員現在可以透過 UpdateDeadline.FinalCountDown 喜好設定來覆蓋 60 分鐘的預設期限時間
- 在不同網路連接間切換時，Microsoft AutoUpdate 現在擁有更好的重試邏輯
- 如果資料夾許可權不正確或缺少協助程式工具，Microsoft AutoUpdate 現在會顯示說明連結
- Microsoft AutoUpdate 使用者介面將不再停止，並要求使用者關閉應用程式 (如果應用程式目前開啟)
- 使用 Microsoft AutoUpdate 使用者介面時 VoiceOver 的增強功能


**錯誤修正：**
- 安裝程式套件現在正確地指定 macOS 10.12 做為安裝的最低作業系統
- 已修正下載和安裝應用程式更新期間可能發生的各種當機問題
- 已修正法文使用者按鈕文字被截斷的問題


**SHA-256 雜湊：**

52823A753D1E221D3ADFB4023A8FE284005D1B1C37EE104EAFB526C8C809E03C
<br><br>

## <a name="may-2022-release"></a>2022 年 5 月發行版本

**發行日期：** 2022 年 5 月 10 日

*Microsoft AutoUpdate 4.47*



**錯誤修正：**
- 已修正在還原複製時，Microsoft AutoUpdate 可能會當機的問題
- 已修正在叫用 msupdate 命令列公用程式時，圖示會在擴充座中顯示的問題


**SHA-256 雜湊：**

82873FEA5AC7D5FDC86A1CA66F6064858BD635CFED00072A013A6949DDDAAA24
<br><br>


## <a name="april-2022-release"></a>2022 年 4 月版本

**發行日期:** 2022 年 4 月 21 日

*Microsoft AutoUpdate 4.46*


**錯誤修正：**
- 已修正應用程式在重新開機 macOS 之後不會更新的問題


**SHA-256 雜湊：**

C55FB506525B625D5539385F9AF267B1ECC0B6534BF9461A7CF04FAECAF82FFB


**發行日期:** 2022 年 4 月 12 日

*Microsoft AutoUpdate 4.46*

**增強功能：**
- Microsoft AutoUpdate 現在將在系統重新啟動時完成應用程式更新
- Microsoft AutoUpdate 現在會更新應用程式，即使應用程式已重新命名
- Microsoft AutoUpdate 會自動修正使用者喜好設定檔案的權限問題

**錯誤修正：**
- 已修正 msupdate 命令列工具在流程關閉時當機的問題
- Microsoft AutoUpdate GUI 會在處理程序關閉時當機的問題已修正
- 已修正如果已鎖定快取套件，更新會失敗的問題

**SHA-256 雜湊：**

2AF0B460A3B4FBBCB24A50608EE1D43737093907F2C58A901E406B1A34A97E66
<br><br>


## <a name="march-2022-release"></a>2022 年 3 月發行版本

**發行日期：** 2022 年 3 月 15 日

*Microsoft AutoUpdate 4.45*

**增強功能：**
- Microsoft AutoUpdate 現在會偵測、下載並套用更新至 Microsoft Teams
- Microsoft AutoUpdate 現在有額外的快取，以避免重複套件下載
- [期限] 對話方塊只會在已分段更新，且準備好安裝時顯示

**錯誤修正：**
- Microsoft AutoUpdate 因憑證到期而無法套用更新的問題已修正
- 使 macOS 無法正常關機及重新開機的問題已修正
- Microsoft AutoUpdate 未在 72 小時後關閉並重新啟動的問題已修正
- UpdateCheckFrequency 偏好設定未生效的問題已修正
- Microsoft AutoUpdate 會在處理程序關閉時當機的問題已修正


**SHA-256 雜湊：**

6FCECBDF0348B67D925CE55D85E7CB223178DF2B157D72FD14F76C30FD3FC324
<br><br>


## <a name="february-2022-release"></a>2022 年 2 月發行版本

**發行日期：** 2022 年 2 月 16 日

*Microsoft AutoUpdate 4.44*

**錯誤修正：**
- 已修正如果發出多個 '檢查更新' 要求，會導致 Microsoft AutoUpdate 意外關閉的問題
- 已修正會導致 Microsoft AutoUpdate 在啟動時無限期停止回應的問題
- 已修正在套用更新之後，會導致 Office 應用程式以隱藏狀態開啟的問題


**SHA-256 雜湊：**

0839300CECF910E03FE224B506DCE8F6E732F0C8FC474A8E26D6981C80E32E2B
<br><br>

## <a name="january-2022-release"></a>2022 年 1 月發行版本

**發行日期:** 2022 年 1 月 13 日

*Microsoft AutoUpdate 4.43*

**錯誤修正：**
- 已修正可能會導致 Microsoft AutoUpdate 提前終止的問題


**SHA-256 雜湊：**

E3F1EE36F7977F3AA52D31BAE9F7EC084606FDC059514F31A7B1856914C0B507


## <a name="december-2021-release"></a>2021 年 12 月發行

**發行日期：** 2021 年 12 月 14 日

*Microsoft AutoUpdate 4.42*

**增強功能：**
- 改進對 VoiceOver 的支援
- 使用 GUI 時，MAU 將會立即關閉並重新啟動應用程式
- 如果使用者先前已選擇延遲更新，則稍後會顯示 [提醒] 對話方塊。

**錯誤修正：**
- 已修正 GUI 中遺漏「新增功能」內容的問題
- 已修正在某些情況下，更新通知對話方塊未顯示的問題
- 已修正在慢速裝置上 MAU 會提前終止的問題
- 已修正如果已發出多個更新要求，導致 MAU 終止的問題


**SHA-256 雜湊：**

299DDCBFB071C287603B9602C94EFE8977EF82CF1C65C98F36B1BC9428CBC02B
<br><br>

## <a name="november-2021-release"></a>2021 年 11 月發行版本

**發行日期：** 2021 年 11 月 16 日

*Microsoft AutoUpdate 4.41*

**錯誤修正及增強功能：**
- 準備好安裝更新時，MAU 現在會顯示應用程式內訊息列 (Word、Excel、PowerPoint)
- 如果沒有未儲存的文件變更，Word、Excel 和 PowerPoint 將自動更新並重新啟動
- 如果應用程式在分配的時間內無法更新，MAU 將在不需要重新下載更新套件的情況下重試更新
- 新增更新 Office 授權協助程式的支援。 如需詳細資訊，請參閱 https://go.microsoft.com/fwlink/?linkid=2181277




**SHA-256 雜湊：**

C634C99867D70524C090B1FA26DD9BCE747A04611DB88B68F6E35C58B7752516
<br><br>
## <a name="october-2021-release"></a>2021 年 10 月發行

**發行日期：** 2021 年 10 月 12 日

*Microsoft AutoUpdate 4.40*

**錯誤修正及增強功能：**
- MAU 現在使用增強的內容傳遞網路 (CDN) 進行更新 (officecdnmac.microsoft.com)
- 對期限功能進行使用者體驗精簡
- 修正某些更新案例可能會發生應用程式損壞的問題



**SHA-256 雜湊：**

F638F7E0DA9EE659C323F2EDE0F176804BFE9A615A8F8B6320BD2E69D91EF2B2

## <a name="september-2021-release"></a>2021 年 9 月發行

**發行日期：** 2021 年 9 月 14 日

*Microsoft AutoUpdate 4.39*

**錯誤修正及增強功能：**
- 錯誤修正：如果未使用 MAU 命令提示字元終止應用程式，則在更新應用程式之後將無法重新啟動


**SHA-256 雜湊：**

E6D45F0F0010F67638F199CE8757739F26E703F3D472EF482BEC2175AB7D85B7
<br><br>

## <a name="august-2021-release"></a>2021 年 8 月發行

**發行日期：** 2021 年 8 月 10 日

*Microsoft AutoUpdate 4.38*

**錯誤修正及增強功能：**
- 在更新套件以下載完成且準備就緒進行安裝之後，MAU 的 CLI 會立即顯示通知。 


**SHA-256 雜湊：**

FA603BA191C87A6E261475F7BCEA98176533C3C8760EB0F4B31118A845EC6DBB
<br><br>

## <a name="july-2021-release"></a>2021 年 7 月發行

**發行日期：** 2021 年 7 月 13 日

*Microsoft AutoUpdate 4.37*

**錯誤修正及增強功能：**
- msupdate 通知的變更 - MAU 現在會先下載更新並暫存，然後再顯示 IT 系統管理員的通知。
- 修正 MAU 在套用更新後顯示舊應用程式版本的問題。
- 修正啟動更新時未關閉 MAU 期限通知的問題。


**SHA-256 雜湊：**

2352BA7722ABCC92E9C05E2D50B1B6F71FEF7D91306D6E4EF765F042688F2BC4
<br><br>
## <a name="june-2021-release"></a>2021 年 6 月版本

**發行日期：** 2021 年 6 月 15 日

*Microsoft AutoUpdate 4.36*

**錯誤修正及增強功能：**
- Docktile 進度指示器 - MAU 現在會在 Dock 中所顯示的圖示上展現進度指示。
- 隨機更新完成 - MAU 會嘗試在裝置關機/重新開機期間套用延遲的更新。


**SHA-256 雜湊：**

0680414EA9553FEF6198B8414CFABABB6ED5B22A571138B98F6F3E4190630DB3
<br><br>

## <a name="may-2021-release"></a>2021 年 5 月發行

**發行日期：** 2021 年 5 月 13 日

*Microsoft AutoUpdate 4.35*

**錯誤修正及增強功能：**
- 解決導致顯示「更新已在進行中」提示的並行更新的潛在問題。
- [略過] 對話方塊顯示兩次的錯誤修正。
- 相同更新顯示多個通知的錯誤修正。
- Microsoft AutoUpdate 安裝程式/更新程式套件上的大小縮減。
- 命令列介面 (CLI) 現在使用原生 xpc 與 Microsoft Update Assistant 通訊，而不是 Apple 事件。


**SHA-256 雜湊：**

1F6CAB8CCAF52743EFEEA908D0F26E2AE1A1F171C877F7B8057D00CDA7727733
<br><br>
## <a name="april-2021-release"></a>2021 年 4 月發行

**發行日期：** 2021 年 4 月 13 日

*Microsoft AutoUpdate 4.34*

**錯誤修正及增強功能：**
- 對於使用手動更新模式的使用者，微小的 'Badging Notifications' 現在會指出更新的可用性，而不是傳統的作業系統通知提示。


**SHA-256 雜湊：**

98C6821D939A3FA78BE21B11919625A48EAE2A3CC87CB104BF06637D9B850D9C
<br><br>


## <a name="march-2021-release"></a>2021 年 3 月版本

**發行日期：** 2021 年 3 月 17 日

*Microsoft AutoUpdate 4.33*

**錯誤修正及增強功能：**
- MAU 檢查更新時，現在會停用 MAU GUI 上的 [檢查中...] 按鈕。
- 「更新已在進行中」提示現在會提供其他資訊。
- MAU UI 會在下載更新時顯示正確的更新大小。
- MAU 現在可在不含 Rosetta 的 M1 macOS 裝置上安裝。


**SHA-256 雜湊：**

 8B851FD35B8172AB3220592E68ABCD6C302A55336FD7E9F8B5511683B372E7E1
<br/><br/>

## <a name="february-2021-release"></a>2021 年 2 月版本

**發行日期：** 2021 年 2 月 17 日

*Microsoft AutoUpdate 4.32*

**錯誤修正及增強功能：**
- 文件更新：遺失的 -t、-m 及更新旗標的旗標描述現在可在 MAU 的命令列介面中提供。
- 協助工具更新：Voice Over 宣告現已可在在 MAU UI 下載/安裝進度列，以及 MAU 使用者喜好設定 UI 上的更新通道標籤上使用。
- 功能更新：MAU 的主功能表列現在有一個 [編輯] 選項，可允許鍵盤快速鍵。
- 其他更新：MAU 的著作權年度已更新至 2021 年。


**SHA-256 雜湊：**

CCB758531B295848620C703957FD8CF3C7F1555C334FB320C4BB682ABA0261D6
<br/><br/>

## <a name="january-2021-release"></a>2021 年 1 月版本

**發行日期：** 2020 年 1 月 13 日

*Microsoft AutoUpdate 4.31*

**錯誤修正及增強功能：**
- 針對未採用自動更新的裝置，Microsoft AutoUpdate 現在將透過通知 (而不是開啟 MAU UI) 來通知相關的新更新。


**SHA-256 雜湊：**

209B444D2831B879BB73C92041A1C7318C1D5BA58B4689F6C4FC842B0930B532
<br/><br/>

## <a name="december-2020-release"></a>2020 年 12 月版本

**發行日期：** 2020 年 12 月 15 日

*Microsoft AutoUpdate 4.30*

**錯誤修正及增強功能：**
- 為使用 M1 的 Mac 新增通用應用程式支援。

**MAU 更新連結：**


**SHA-256 Hash:** 9F4C49BE4FCC82DED7BD394F4F2057912B40D0083F754D15495B7BDE9E58EAC4

<br/><br/>


## <a name="november-2020-release"></a>2020 年 11 月版本

**發行日期：** 2020 年 11 月 10 日

*Microsoft AutoUpdate 4.29*

**錯誤修正及增強功能：**
-   已更新 Microsoft 365 的通道名稱。
-   修正會導致某些 OneDrive 安裝無法取得更新的問題。

**MAU 更新連結：**


**SHA-256 雜湊；** 7EDE97D524CE7E7869A4033D25270057E670588886F7A0E02628CC7FCB4F7851

<br/><br/>

## <a name="october-2020-release"></a>2020 年 10 月版本

**發行日期：** 2020 年 10 月 13 日

*Microsoft AutoUpdate 4.28*

**錯誤修正及增強功能：**
-   MAU UI：[摘要視圖] 現在會顯示使用者需要注意的錯誤
-   MAU UI 和更新小幫手現在會於 72 小時內未不執行任何動作的時候自行終止。
-   MAU UI：現在隨附 Windows 功能表

**MAU 更新連結：**


**SHA-256 雜湊：**

80171D842C59BA3B26A085DD3AB6E63E32102088078848C95AEBECF4C91B0438

<br/><br/>

## <a name="september-2020-release"></a>2020 年 9 月版本

**發行日期：** 2020 年 9 月 16 日

*Microsoft AutoUpdate 4.27*

**錯誤修正及增強功能：**
-   即使未達到一般檢查週期，MAU 更新小幫手現在會在鎖定螢幕背後開始更新。

**MAU 更新連結：**


**SHA-256 雜湊：**

7AF6ACDC5E1278CF4D227F305A127A6FE5A275094D945C1504DC108C2090F2CB

<br/><br/>

## <a name="august-2020-release"></a>2020 年 8 月發行

**發行日期：** 2020 年 8 月 11 日

*Microsoft AutoUpdate 4.26*

**錯誤修正及增強功能：**
-   擴充座中的 MAU 圖示現在會顯示可用的更新數目。 
-   MAU 將在偵測到更新時，啟動最小化狀態。
-   新增了新的「IgnoreUIOpenAfterInstall」偏好，可用于防止 MAU UI 在安装之后啟動。
-   解决了導致顯示「無法正確安裝」訊息的權限問題 
-   將 MAU 「更新期限」通知訊息的持續時間從60秒延伸為1小時。


**MAU 更新連結：**


**SHA-256 雜湊：**

E81CEADF900A0C7E7D593720D08146DBC1C55868D5B21C7E7A175AA36DFE0178

<br/><br/>

## <a name="july-2020-release"></a>2020 年 7 月版本

**發行日期：** 2020 年 7 月 14 日

*Microsoft AutoUpdate 4.25*

**錯誤修正及增強功能：**
- 偵測應用程式終止，並自動移除與「開啟的應用程式」相關的顯示對話方塊。
- 還原 4 月版本中所推出，關閉了自動更新的使用者，只會每週看到 Microsoft AutoUpdate UI 一次的功能。
- 已修正更新小幫手於下載更新之後、安裝開始前未預期關閉的問題。
- 已修正更新小幫手在拖延的擱置中使用者通知期間後未關閉的問題。
- Fixed an issue where the MAU UI reopened (or didn't reopen) after install. The UI should open after install if the update is started from the MAU UI itself, or if an update is explicitly started by the user (via Finder, Terminal, and so on.).

**SHA-256 雜湊：**

B8E3D4391E48732F42217589784D8B3417F6F14489D9DE04395198A01BFDFA46

<br/><br/>

## <a name="june-2020-release"></a>2020 年 6 月版本

**發行日期：** 2020 年 6 月 18 日

*Microsoft AutoUpdate 4.24*

**錯誤修正及增強功能：**
- 客戶訊息活動：Mac 版 Office 2016 將於 2020 年 10 月終止支援。 
- MAU 的 Helper 工具 XPC 連線的安全性修正程式。

**SHA-256 雜湊：**

EEA059A348F7807DE4C0FD18D480F410B28FB729CB2604D9AD8C63484B0EA1E0

<br/><br/>

## <a name="may-2020-release"></a>2020 年 5 月發行

**發行日期：** 2020 年 5 月 12 日

*Microsoft AutoUpdate 4.23*

**錯誤修正及增強功能：**
- 針對使用 macOS 10.13 或更新版本的裝置與 Office 2016 版本，使用者將會看到 Office 2016 即將終止支援的通知。 
- 如果 Word、Excel 和 PowerPoint 應用程式沒有開啟中的視窗，且裝置處於 Microsoft AutoUpdate 的自動更新模式，使用者不需要關閉這些應用程式就可以套用更新。 Microsoft AutoUpdate 現在將使用 CDN 上的最新版本自動重新整理 [更新儀表板]，使用者不需要重新整理或啟動新的 AutoUpdate 工作階段。 

**SHA-256 雜湊：**

7DAB76D11427BACF30D3DBD87374CE755C618262E68FC3CA85B3FB8F3F3750AD

<br/><br/>

## <a name="april-2020-release"></a>2020 年 4 月版本

**發行日期：** 2020 年 4 月 21 日

*Microsoft AutoUpdate 4.22*

**錯誤修正及增強功能：**
- Microsoft AutoUpdate UI 不會在透過 Microsoft AutoUpdate 的 [自動] 模式更新其 Office 應用程式的裝置上顯示，也不會在沒有新的更新可用時，在使用非自動模式取得更新的裝置中顯示。

**SHA-256 雜湊：**

2D672B377C6A1115FDC509E45E6AFF663D8F15412D4EB77E033085700DC1B72B

<br/><br/>

**發行日期：** 2020 年 4 月 14 日

*Microsoft AutoUpdate 4.22*

 **功能更新：**

- 安全性問題修正：Microsoft AutoUpdate 將禁止來自舊版的任何不安全連線。
- 將 [自動更新] 設為 [關閉] 的使用者每週只會看到一次 Microsoft AutoUpdate UI。
- 使用 SSD 的 macOS 機器會體驗到更快速的更新，且因為更新而導致應用程式停機的時間變得微不足道。


請參閱 [CVE-2020-0984](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-0984)

**SHA-256 雜湊：**

2E202B0B65AC093BDBFDA47F2A62758E44E0FBC09383B121EAA76206CF2B3EAB
<br/><br/>

## <a name="march-2020-release"></a>2020 年 3 月發行

**發行日期：** 2020 年 3 月 10 日

*Microsoft AutoUpdate 4.21*

 **功能更新：**

- 為 Word、Excel 和 PowerPoint 啟用「狀態還原」，執行時不開啟任何視窗，或是在 Microsoft AutoUpdate 的自動更新模式中執行 Docstage 狀態。 現在更新將會對使用 [自動更新] 模式的使用者更為安靜，因為他們不需要結束其符合「透過狀態還原更新」資格的應用程式。

**SHA-256 雜湊：**

9AF2FAF4854BF06F33322A8530275F8D32965C91D446C45A0CD8BC4C5DF04F44
<br/><br/>

## <a name="february-2020-release"></a>2020 年 2 月版本

**發行日期：** 2020 年 2 月 11 日

*Microsoft AutoUpdate 4.20*

 **功能更新：**

- 只有在裝置上至少有 1 個應用程式使用 MAU 註冊時，才會啟動 Microsoft AutoUpdate UI
- 錯誤修正及增強功能

**SHA-256 雜湊：**

80DD0637AA60007310FB7B68C01926F6CA0F2771DBB42166C191626607D89B56<br/><br/>

## <a name="january-2020-release"></a>2020 年 1 月發行

**發行日期：** 2020 年 1 月 14 日

*Microsoft AutoUpdate 4.19*

 **功能更新：**

- 錯誤修正及增強功能

**SHA-256 雜湊：**

D480D4FD23BDC07852DEFBADCE4CCBEF00265500E6595FE8B299444EB8F90C3F<br/><br/>

## <a name="december-2019-release"></a>2019 年 12 月版本

**發行日期：** 2019 年 12 月 10 日

*Microsoft AutoUpdate 4.18*

 **功能更新：**

- 每個應用程式的頻道：Mac 系統管理員現在可以訂閱不同頻道或每個應用程式的驗證頻道。 

**SHA-256 雜湊：**

11D051503067DB9819C84C8D1EBE29435A781D29C6B1FE3173DB03DC88F1B4C3<br/><br/>

## <a name="november-2019-release"></a>2019 年 11 月發行

**發行日期：** 2019 年 11 月 12 日

*Microsoft AutoUpdate 4.17*

 **功能更新：**

- 您現在可以在 Microsoft AutoUpdate 儀表板上檢視每個主要更新中的新功能。
- Minimum OS requirements for Office 2019 updates have changed to macOS 10.13 with the release of Catalina. Users will be notified to get upgrade to latest Office Updates.

**SHA-256 雜湊：**

0F8BECB34385711F3D5E54B2944D9C30567B37352C5E59E0A7BC74B83371AB0A<br/><br/>

## <a name="october-2019-release"></a>2019 年 10 月發行

**發行日期：** 2019 年 10 月 15 日

*Microsoft AutoUpdate 4.16*

 **功能更新：**

- 從 Microsoft AutoUpdate 4.16 之後，所有客戶都能享用全新改善的使用者體驗。

**SHA-256 雜湊：**

5BEA94F8AA2BD4F4398B3E5EDE0EA2F406440B8ACAD46B3DACE904824B41052C<br/><br/>
## <a name="september-2019-release"></a>2019 年 9 月發行

**發行日期：** 2019 年 9 月 10 日

*Microsoft AutoUpdate 4.15*

 **功能更新：**

- MAU 更新期限通知現在會以本機裝置的時間格式向使用者顯示截止時間。
- MAU AU 精靈現在稱為「Microsoft Update 小幫手」。
- 修正執行 'msupdate' 命令時，前景應用程式中失去焦點的問題。

**SHA-256 雜湊：**

E5D4EADF632745115CD4819DAB3B1A1838FA8263ECDDC6E621AEA19A3C84F6F7<br/><br/>
## <a name="august-2019-release"></a>2019 年 8 月發行

**發行日期：** 2019 年 8 月 13 日

*Microsoft AutoUpdate 4.14*

 **功能更新：**

- 修正用於改善語音翻譯的各種問題，更新效能和 UI。
- 新增用於疑難排解的遙測和修正程式。

**SHA-256 雜湊：**

76FA706E9E5B717D333B7EFB5AB95FCF9EE3E571A7FF171CA25E77CA6E9EBD97<br/><br/>
## <a name="july-2019-release"></a>2019 年 7 月發行

**發行日期：** 2019 年 7 月 18 日

*Microsoft AutoUpdate 4.13*

 **功能更新：**

- MAU 的隱私權變更：將向使用者顯示必要的資料集合通知，做為規範的一部分。
- MAU Update Deadline: Mac Admins can now set a deadline within MAU to enforce updates across their Mac users. [Learn more](/deployoffice/mac/mau-deadline)
- 各種錯誤和效能修正。

**SHA-256 雜湊：**

9FDCEAFA05AB070531ECEE50E1E977839C1E2DE2312569F816C59F35DE162B08
<br/><br/>
## <a name="june-2019-release"></a>2019 年 6 月發行

**發行日期：** 2019 年 6 月 27 日

*Microsoft AutoUpdate 4.12*

 **功能更新：**

- 修正 Apple OS 測試版會導致 MAU 更新取得完整更新程式失敗的問題。 

**SHA-256 雜湊：**

85ce26ece89a256711f082e61b313c1ed6a22bfc402d4789a78a08022a96f6fa
<br/><br/>

**發行日期：** 2019 年 6 月 9 日

*Microsoft AutoUpdate 4.12*

 **功能更新：**

- 二進位差異更新：針對 SSD 裝置推出較少量的更新，這麼做可減少由於更新造成的頻寬使用量。
- 支援附屬應用程式：MAU 現在支援附屬應用程式，例如 Microsoft OneDrive。
- 「複製時安裝」增強功能：更新複製現在更為穩健。

**SHA-256 雜湊：**

ABCC7D58DA7DB1B8B24B9B1BE6B1DB93BDC97AE487EFB615EC5695B9E1CC0FC9
<br/><br/>


## <a name="may-2019-release"></a>2019 年 5 月發行

**發行日期：** 2019 年 5 月 14 日

*Microsoft AutoUpdate 4.11*

 **功能更新：**

- MAU 的隱私權變更：將向使用者顯示必要的資料集合通知，做為規範的一部分。
- MAU Update Deadline: Mac Admins can now set a deadline within MAU to enforce updates across their Mac users. [Learn more](/deployoffice/mac/mau-deadline)
- 各種錯誤和效能修正。

**SHA-256 雜湊：**

EE3403B79E536191E545E70708A99D3A33B384372F65C028490AFFB551CD1EE2
<br/><br/>

## <a name="april-2019-release"></a>2019 年 4 月發行

**發行日期：** 2019 年 4 月 16 日

*Microsoft AutoUpdate 4.10*

 **功能更新：**

- 「複製時安裝」增強功能：針對 SSD 裝置，對使用中的應用程式推出複製時更新，這麼做可減少由於更新造成的應用程式停機時間。
- 安裝最佳化：由於更新程序會使用平行化複製，將可減少應用程式停機時間。

**SHA-256 雜湊：**

FF676870D5B3521202095810B85DEF36538B59E00AEA44A2ED0D7EA8B3B99D6C
<br/><br/>

## <a name="release-history"></a>版本歷程記錄

|發行日期|版本|其他相關資訊|
|:-----|:-----|:-----|
|2019 年 9 月 10 日 <br/>|4.15 <br/> |  <br/> ||
|2019 年 8 月 13 日 <br/>|4.14 <br/> |  <br/> ||
|2019 年 7 月 18 日 <br/>|4.13 <br/> |  <br/> ||
|2019 年 6 月 27 日 <br/>2019 年 6 月 9 日|4.12 <br/> | <br/> ||
|2019 年 5 月 14 日 <br/>|4.11 <br/> |  <br/> | <br/> |
|2019 年 4 月 16 日 <br/>|4.10 <br/> |  <br/> |<br/> |
|2019 年 3 月 14 日 <br/>|4.9.0 <br/> | [版本資訊](release-notes-office-for-mac.md#march-2019-release) <br/> | <br/> |
|2019 年 2 月 26 日 <br/>|4.8.0 <br/> | [版本資訊](release-notes-office-for-mac.md#february-2019-release) <br/> |<br/> |
|2019 年 1 月 16 日 <br/>|4.7.0 <br/> | [版本資訊](release-notes-office-for-mac.md#january-2019-release) <br/> | |
|2018 年 12 月 11 日 <br/>|4.6.0 <br/> | [版本資訊](release-notes-office-for-mac.md#december-2018-release) <br/> ||
|2018 年 11 月 14 日 <br/> |4.5.0 <br/> |[版本資訊](release-notes-office-for-mac.md#november-2018-release) <br/> | |
|2018 年 10 月 16 日 <br/> |4.4.0 <br/> |[版本資訊](release-notes-office-for-mac.md#october-2018-release) <br/> | |
|2018 年 9 月 11 日  <br/> |4.3.0  <br/> |[版本資訊](release-notes-office-for-mac.md#september-2018-release) <br/> | |
|2018 年 8 月 14 日  <br/> |4.2.0  <br/> |[版本資訊](release-notes-office-for-mac.md#august-2018-release) <br/> | |
|2018 年 7 月 10 日  <br/> |4.1.0  <br/> |[版本資訊](release-notes-office-for-mac.md#july-2018-release) <br/> | |
|2018 年 6 月 12 日  <br/> |4.0.0  <br/> |||
|2018 年 5 月 15 日  <br/> |4.0.0  <br/> |||
|2018 年 4 月 10 日  <br/> |3.18  <br/> |[版本資訊](release-notes-office-for-mac.md#april-2018-release) <br/> ||
|2018 年 3 月 13 日  <br/> |3.17  <br/> |||
|2018 年 2 月 13 日  <br/> |3.16.0  <br/> |[版本資訊](release-notes-office-for-mac.md#february-2018-release) <br/> | <br/> |
|2018 年 1 月 18 日  <br/> |3.15.0  <br/> |<br/> |
|2017 年 12 月 17 日  <br/> |3.14.1  <br/> |[版本資訊](release-notes-office-for-mac.md#december-2017-release) <br/> | <br/> |
|2017 年 12 月 12 日  <br/> |3.14  <br/> ||  <br/> |
|2017 年 10 月 10 日  <br/> |3.11  <br/> ||<br/> |
|2017 年 9 月 12 日  <br/> |3.9.3  <br/> |[版本資訊](release-notes-office-for-mac.md#september-2017-release) <br/> |<br/> |
|2017 年 8 月 15 日  <br/> |3.9.2  <br/> || <br/> |
|2017 年 7 月 11 日  <br/> |3.9.1  <br/> || <br/> |
|2017 年 6 月 13 日  <br/> |3.9.1  <br/> || <br/> |
|2017 年 5 月 9 日  <br/> |3.9.1  <br/> |[版本資訊](release-notes-office-for-mac.md#may-2017-release) <br/> | <br/> |
|2017 年 4 月 11 日  <br/> |3.9  <br/> |[版本資訊](release-notes-office-for-mac.md#april-2017-release) <br/> |  <br/> |
|2017 年 2 月 16 日  <br/> |3.8.4  <br/> |[版本資訊](release-notes-office-for-mac.md#february-2017-release) <br/> | <br/> |
|2017 年 1 月 11 日  <br/> |3.8.3  <br/> |[版本資訊](release-notes-office-for-mac.md#january-2017-release) <br/> | <br/> |
|2016 年 12 月 13 日  <br/> |3.8.2  <br/> | <br/> | <br/> |
|2016 年 11 月 15 日  <br/> |3.8.1  <br/> | <br/> | <br/> |
|2016 年 10 月 11 日  <br/> |3.8.0  <br/> |[KB 3193438](https://support.microsoft.com/kb/3193438) <br/> | <br/> |
|2016 年 8 月 22 日  <br/> |3.6.0  <br/> |[KB 3179163](https://support.microsoft.com/kb/3179163) <br/> | <br/> |
|2016 年 5 月 10 日  <br/> |3.5.0  <br/> |[KB 3155777](https://support.microsoft.com/kb/3155777) <br/> | <br/> |
|2016 年 4 月 12 日  <br/> |3.4.0  <br/> |[KB 3142577](https://support.microsoft.com/kb/3142577) <br/> | <br/> |
|2016 年 1 月 5日  <br/> |3.4.0  <br/> |[KB 3133674](https://support.microsoft.com/kb/3133674) <br/> | <br/> |


## <a name="related-articles"></a>相關文章

- [Mac 版 Office 的更新歷程記錄](update-history-office-for-mac.md)
- [Mac 版 Office 的版本資訊](release-notes-office-for-mac.md)