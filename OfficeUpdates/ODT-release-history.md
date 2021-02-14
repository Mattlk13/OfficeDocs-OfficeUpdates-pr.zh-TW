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
ms.openlocfilehash: 1046a62a8440402e64bb25cb5ccf3dfbd84c894d
ms.sourcegitcommit: b015407aa6693d879f11025b40a7b45424753f99
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/10/2021
ms.locfileid: "50177948"
---
# <a name="release-history-for-office-deployment-tool"></a>Office 部署工具的發行記錄

Office 部署工具 (ODT) 是一種命令列工具，可用來將像 Microsoft 365 應用程式這類的 Office 隨選即用版本下載並部署到用戶端電腦。 


ODT 能讓您進一步控制 Office 安裝。 您可以定義要安裝哪些產品及語言、這些產品的更新方式，以及是否要讓使用者看到安裝過程。 如需有關如何使用 ODT 的詳細資訊，請參閱 [Office 部署工具概觀](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)。

 **支援作業系統**：Windows 10、Windows 8.1、Windows Server 2019、Windows Server 2016 
 
 **安裝指示**：下載檔案然後執行自我解壓縮可執行檔，其中會包含 Office 部署工具可執行檔 (setup.exe) 及範例組態檔 (configuration.xml)。 

[下載 Office 部署工具](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="february-9-2021"></a>2021 年 2 月 9 日
版本 16.0.13628.20274 (setup.exe 版本 16.0.13628.20246)
- 新增驗證，以警告並防止 Windows 8.0 的安裝不受支援
- ARM64 裝置的可靠性修正


## <a name="january-12-2021"></a>2021 年 1 月 12 日
版本 16.0.13530.20376 (setup.exe 版本 16.0.13530.20334)
- 修正已損毀或非標準產品註冊可能會導致 RemoveMSI 作業失敗的問題

## <a name="december-21-2020"></a>2020 年 12 月 21 日
版本 16.0.13426.20370 (setup.exe 版本 16.0.13426.20352)
- 已修正從 PerpetualVL2019 通道 ProofingTools 的本機來源安裝失敗的問題
- 已修正當您在現有安裝中新增非完整 Office 語言中的其他產品時，隨選即用用戶端嘗試自我更新的問題


## <a name="december-8-2020"></a>2020 年 12 月 8 日
版本 16.0.13426.20308 (setup.exe 版本 16.0.13426.20308) 
- 已修正如果裝置的 Office 產品是從非Perpetual 2019 的通道進行安裝，則 [下載] 模式會封鎖 Perpetual 2019 的通道下載之問題。
- 已修正針對透過 [下載] 模式所建立的本機來源，在設定 XML 中指定明確的 [版本]，將會導致 [結構移轉] 失敗的問題。


## <a name="november-23-2020"></a>2020 年 11 月 23 日
版本 16.0.13328.20420 (setup.exe 版本 16.0.13328.20420)
- 已修正 /download 模式未下載校訂工具的問題
- 已修正在停權使用者內容中執行時，/download 模式失敗的問題
- 已修正在組態 XML 中指定 Version 屬性時，導致 /download 模式中下載不完全的問題
- 已修正在解壓縮時，Office 部署工具未命名為 “setup.exe” 的問題
- 已修正在組態 XML 中提供 Channel 屬性時，安裝來源優先順序的問題

## <a name="november-10-2020"></a>2020 年 11 月 10 日
版本 16.0.13328.20356 (setupODT.exe 版本 16.0.13328.20336)
- 可靠性和復原改善
- 為了防止混淆及更輕鬆地診斷安裝程式錯誤，ODT 現在預設稱為 setupODT。

## <a name="october-29-2020"></a>2020 年 10 月 29 日
版本 16.0.13328.20292 (setup.exe 版本 16.0.13328.20290)
- 解決使用 RemoveMSI 時，某些 Office 2007 產品可能會意外封鎖安裝的問題

## <a name="october-14-2020"></a>2020 年 10 月14 日
版本 16.0.13231.20368 (setup.exe 版本 16.0.13231.20350)
- 當沒有指定頻道時，預設情况下所有產品都將使用每月通道
- 改善從含有其他 DLL 的目錄執行 ODT 時的安全性
- 可靠性和恢復改善

## <a name="june-9-2020"></a>2020 年 6 月 9 日

版本 16.0.12827.20268 (setup.exe 版本 16.0.12827.20258)
- 在未指定頻道時，目前的通道即為預設的頻道。
- 新增每月企業通道的支援
- 新增新頻道名稱的支援
- 即使在無法使用部分語言資源時，如可能，可持續安裝其他復原功能
- MSIRemove 的功能已展開，可移除 Office 2007 產品
- MSIRemove 的功能已展開，可移除 Access 資料庫引擎 

## <a name="april-15-2020"></a>2020 年 4 月 15 日

版本 16.0.12624.20320 (setup.exe 版本 16.0.12624.20290)
- 新增對於 Windows 7 特定生命週期結束 Office 版本的支援
- 已修正可能無法如預期方式套用自訂設定的問題
- 已修正可能會意外下載無關 .cat 檔案的問題

## <a name="january-16-2020"></a>2020 年 1 月 16 日

版本 16.0.12325.20288
- 修正在安裝多個語言時，Office 安裝 UI 可能會以不正確的語言顯示的問題
- 修正在安裝某些校訂工具套件之後，Office 安裝可能會非預期地失敗的問題
- 新增支援以選擇性地控制 [Bing 中的 Microsoft Search](https://go.microsoft.com/fwlink/p/?linkid=2109345) 的初始部署


## <a name="october-31-2019"></a>2019 年 10 月 31 日

版本 16.0.12130.20272
- 修正了允許商務用 Skype 基本版 2019 安裝 2019 永久企業版大量授權產品的問題
- 修正了使用 Proxy 時，在某些情況下，可能會導致 ODT 下載模式意外失敗的問題
- 新功能可讓 ODT 下載模式透過 HTTP 連接埠 80 以外的埠來下載


## <a name="july-10-2019"></a>2019 年 7 月 10 日

版本 16.0.11901.20022
- 隨 Office 2019 一起安裝時，新增了對其他產品的支援：Access Runtime，商務用 Skype 基本版。
- 從 MSI 升級時，新增對獨立產品之條件式件安裝的支援。

## <a name="april-23-2019"></a>2019 年 4 月 23 日

版本 16.0.11617.33601
- 已修正 RemoveMSI = True 清除相關登錄設定的錯誤。
- 更新錯誤碼，為非預期的失敗 (E_UNEXPECTED) 提供其他詳細資料。

## <a name="april-16-2019"></a>2019 年 4 月 16 日

版本 16.0.11615.33602
- 支援使用新的 MigrateArch 屬性將 32 位元 C2R 升級到 64 位元 C2R。
- 更新了 /configure 的邏輯，允許存取儲存在 Web 位置 (http 和 https) 中的設定 XML 文件。
- 已新增 MatchInstalled 為新屬性，允許 ODT 在新增其他產品或語言時比對現有版本。

## <a name="march-13-2019"></a>2019 年 3 月 13 日

版本 16.0.11509.33604
- 升級與移轉案例的增強功能。

## <a name="january-14-2019"></a>2019 年 1 月 14 日

版本 16.0.11306.33602
- 部署設定的記錄及遙測改良功能。


## <a name="related-links"></a>相關連結

[ODT 下載中心](https://www.microsoft.com/en-us/download/details.aspx?id=49117)