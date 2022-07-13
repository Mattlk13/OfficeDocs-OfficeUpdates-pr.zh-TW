---
title: Office 部署工具 (ODT) 的發行記錄
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: 為 IT 專業人員提供 Office 部署工具 (ODT) 的發行記錄
ms.openlocfilehash: 1f0e808979e52e48563be0dc7bb907ecc81cf8de
ms.sourcegitcommit: 9de6a870701ddab17b3ca9f9c33302edf3220dec
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/13/2022
ms.locfileid: "66767359"
---
# <a name="release-history-for-office-deployment-tool"></a>Office 部署工具的發行記錄

Office 部署工具 (ODT) 是一種命令列工具，可用來將像 Microsoft 365 應用程式這類的 Office 隨選即用版本下載並部署到用戶端電腦。 


ODT 讓您對 Office 安裝作業有更多的控制權。您可以定義要安裝哪些產品及語言、這些產品的更新方式，以及是否要讓使用者看到安裝過程。若要了解如何使用 ODT 的詳細資訊，請參閱 [Office 部署工具概觀](/deployoffice/overview-of-the-office-2016-deployment-tool)。

 **支援作業系統**：Windows 10、Windows 8.1、Windows Server 2019、Windows Server 2016 
 
 **安裝指示**：下載檔案然後執行自我解壓縮可執行檔，其中會包含 Office 部署工具可執行檔 (setup.exe) 及範例組態檔 (configuration.xml)。 

[下載 Office 部署工具](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="july-12-2022"></a>2022 年 7 月 12 日
版本 16.0.15330.20230 (setup.exe 版本 16.0.15330.20218) ：
- 可靠性改善。


## <a name="june-14-2022"></a>2022 年 6 月 14 日
版本 16.0.15225.20204 (setup.exe 版本 16.0.15225.20172)：
- 可靠性改善。


## <a name="may-10-2022"></a>2022 年 5 月 10 日
版本 16.0.15128.20224 (setup.exe 版本 16.0.15128.20220)：
- 可靠性改善。


## <a name="april-29-2022"></a>2022 年 4 月 29 日
版本 16.0.15028.20242 (setup.exe 版本 16.0.15028.20242):
- 可靠性改善。


## <a name="april-12-2022"></a>2022 年 4 月 12 日
版本 16.0.15028.20160 (setup.exe 版本 16.0.15028.20152):
- 安全修補程式。


## <a name="march-8-2022"></a>2022 年 3 月 8 日
版本 16.0.14931.20120 (setup.exe 版本 16.0.14931.20118):
- 安全修補程式。
- 可靠性改善。


## <a name="january-13-2022"></a>2022 年 1 月 13 日
版本 16.0.14729.20228 (setup.exe 版本 16.0.14729.20228):
- 已修正在特定網路 Proxy 設定下下載或安裝會失敗的問題。
- 已修正從每月企業通道從未連結內容下載失敗的問題。


## <a name="october-26-2021"></a>2021 年 10 月 26 日
版本 16.0.14527.20178 (setup.exe 版本 16.0.14527.20144):
- 一般可靠性改善。


## <a name="sept-16-2021"></a>2021 年 9 月 16 日
版本 16.0.14326.20404 (setup.exe 版本 16.0.14326.20384):
- Office LTSC 2021 產品的支援。
- 可靠性改善。


## <a name="july-12-2021"></a>2021 年 7 月 12 日
版本 16.0.14131.20278 (setup.exe 版本 16.0.14131.20278):
- 已修正 RemoveMSI 在某些情況下會失敗的問題。
- 修正偵測 setup.exe 並存執行的問題。
- ARM 平台的可靠性修正。


## <a name="june-17-2021"></a>2021 年 6 月 17 日
版本 16.0.14026.20306 (setup.exe 版本 16.0.14026.20306):
- 修正使用 MatchOS 語言選項的作業，在某些作業系統設定上失敗的問題。


## <a name="june-7-2021"></a>2021 年 6 月 7 日
版本 16.0.14026.20254 (setup.exe 版本 16.0.14026.20252):
- ARM 平台的可靠性修正。


## <a name="may-10-2021"></a>2021 年 5 月 10 日
版本 16.0.13929.20296 (setup.exe 版本 16.0.13929.20238):
- 已修正如果設定檔同時包含 MigrateArch 和 RemoveMSI，/configure 模式可能會失敗的問題
- 其他可靠性改善。

## <a name="april-13-2021"></a>2021 年 4 月 13 日
版本 16.0.13901.20336 (setup.exe 版本 16.0.13901.20328):
- 設定已在已安裝 Office 的裝置上執行作業的可靠性修正。
- 修正以在某些情況下避免顯示重複的進度 UI。
- 改善 UI 中顯示的錯誤碼正確性。
- ARM 平台的可靠性修正。

## <a name="march-23-2021"></a>2021 年 3 月 23 日
版本 16.0.13801.20360 (setup.exe 版本 16.0.13801.20340):
- 支援即將推出的 Office 產品版本資訊的變更。
- ARM 平台的可靠性修正。


## <a name="february-25-2021"></a>2021 年 2 月 25 日
版本 16.0.13628.20476 (setup.exe 版本 16.0.13628.20462):
- 修正 configuration.xml 檔案指定數十種無法驗證的語言的問題。
- 修正 MigrateArch 案例未遵守 FORCEAPPSHUTDOWN 屬性的問題。
- 修正在 configuration.xml 中指定 2 個或多個 PIDKEY 屬性而無法安裝 PIDKey 的問題。



## <a name="february-9-2021"></a>2021 年 2 月 9 日
版本 16.0.13628.20274 (setup.exe 版本 16.0.13628.20246):
- 新增驗證，以警告並防止 Windows 8.0 的安裝不受支援。
- ARM64 裝置的可靠性修正。


## <a name="january-12-2021"></a>2021 年 1 月 12 日
版本 16.0.13530.20376 (setup.exe 版本 16.0.13530.20334):
- 修正已損毀或非標準產品註冊可能會導致 RemoveMSI 作業失敗的問題。

## <a name="december-21-2020"></a>2020 年 12 月 21 日
版本 16.0.13426.20370 (setup.exe 版本 16.0.13426.20352):
- 已修正從 PerpetualVL2019 通道 ProofingTools 的本機來源安裝失敗的問題。
- 已修正當您在現有安裝中新增其他非完整 Office 語言中的產品時，確保隨選即用用戶端嘗試自我更新的問題。


## <a name="december-8-2020"></a>2020 年 12 月 8 日
版本 16.0.13426.20308 (setup.exe 版本 16.0.13426.20308):
- 已修正如果裝置的 Office 產品是從非Perpetual 2019 的通道進行安裝，則 [下載] 模式會封鎖 Perpetual 2019 的通道下載之問題。
- 已修正針對透過 [下載] 模式所建立的本機來源，在設定 XML 中指定明確的 [版本]，將會導致 [結構移轉] 失敗的問題。


## <a name="november-23-2020"></a>2020 年 11 月 23 日
版本 16.0.13328.20420 (setup.exe 版本 16.0.13328.20420):
- 已修正 /download 模式未下載校訂工具的問題。
- 已修正在停權使用者內容中執行時，/download 模式失敗的問題。
- 已修正在組態 XML 中指定 Version 屬性時，導致 /download 模式中下載不完全的問題。
- 已修正在解壓縮時，Office 部署工具未命名為 “setup.exe” 的問題。
- 已修正在組態 XML 中提供 Channel 屬性時，安裝來源優先順序的問題。

## <a name="november-10-2020"></a>2020 年 11 月 10 日
版本 16.0.13328.20356 (setupODT.exe 版本 16.0.13328.20336):
- 可靠性和復原改善
- 為了防止混淆及更輕鬆地診斷安裝程式錯誤，ODT 現在預設稱為 setupODT。

## <a name="october-29-2020"></a>2020 年 10 月 29 日
版本 16.0.13328.20292 (setup.exe 版本 16.0.13328.20290):
- 解決使用 RemoveMSI 時，某些 Office 2007 產品可能會意外封鎖安裝的問題。

## <a name="october-14-2020"></a>2020 年 10 月14 日
版本 16.0.13231.20368 (setup.exe 版本 16.0.13231.20350):
- 當沒有指定頻道時，預設情况下所有產品都將使用每月通道。
- 改善從含有其他 DLL 的目錄執行 ODT 時的安全性。
- 可靠性和恢復改善。

## <a name="june-9-2020"></a>2020 年 6 月 9 日

版本 16.0.12827.20268 (setup.exe 版本 16.0.12827.20258):
- 在未指定頻道時，目前的通道即為預設的頻道。
- 新增每月企業通道的支援。
- 新增新頻道名稱的支援。
- 即使在無法使用某些語言資源時，如可能，可持續安裝其他復原功能。
- MSIRemove 的功能已展開，可移除 Office 2007 產品。
- MSIRemove 的功能已展開，可移除 Access 資料庫引擎。

## <a name="april-15-2020"></a>2020 年 4 月 15 日

版本 16.0.12624.20320 (setup.exe 版本 16.0.12624.20290):
- 新增對於 Windows 7 特定生命週期結束 Office 版本的支援。
- 已修正可能無法如預期方式套用自訂設定的問題。
- 已修正可能會意外下載無關 .cat 檔案的問題。

## <a name="january-16-2020"></a>2020 年 1 月 16 日

版本 16.0.12325.20288:
- 修正在安裝多個語言時，Office 安裝 UI 可能會以不正確的語言顯示的問題。
- 修正在安裝某些校訂工具套件之後，Office 安裝可能會非預期地失敗的問題。
- 新增支援以選擇性地控制 [Bing 中的 Microsoft 搜尋](/deployoffice/microsoft-search-bing)的初始部署。


## <a name="october-31-2019"></a>2019 年 10 月 31 日

版本 16.0.12130.20272:
- 修正了允許商務用 Skype 基本版 2019 安裝 2019 永久企業版大量授權產品的問題。
- 修正了使用 Proxy 時，在某些情況下，可能會導致 ODT 下載模式意外失敗的問題。
- 新功能可讓 ODT 下載模式透過 HTTP 連接埠 80 以外的連接埠來下載。


## <a name="july-10-2019"></a>2019 年 7 月 10 日

版本 16.0.11901.20022:
- 隨 Office 2019 一起安裝時，新增了對其他產品的支援：Access Runtime，商務用 Skype 基本版。
- 從 MSI 升級時，新增對獨立產品之條件式件安裝的支援。

## <a name="april-23-2019"></a>2019 年 4 月 23 日

版本 16.0.11617.33601:
- 已修正 RemoveMSI = True 清除相關登錄設定的錯誤。
- 更新錯誤碼，以提供非預期失敗 (E_UNEXPECTED) 的其他詳細資料。

## <a name="april-16-2019"></a>2019 年 4 月 16 日

版本 16.0.11615.33602:
- 支援使用新的 MigrateArch 屬性將 32 位元 C2R 升級到 64 位元 C2R。
- 更新了 /configure 的邏輯，允許存取儲存在 Web 位置 (http 和 https) 中的設定 XML 文件。
- 已新增 MatchInstalled 為新屬性，允許 ODT 在新增其他產品或語言時比對現有版本。

## <a name="march-13-2019"></a>2019 年 3 月 13 日

版本 16.0.11509.33604:
- 升級與移轉案例的增強功能。

## <a name="january-14-2019"></a>2019 年 1 月 14 日

版本 16.0.11306.33602:
- 部署設定的記錄及遙測改良功能。


## <a name="related-links"></a>相關連結

[ODT 下載中心](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
