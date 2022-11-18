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
ms.openlocfilehash: 6b6c462a55fb3610bad56bcc83f07939eca2eb4e
ms.sourcegitcommit: 47fab86878737721addf940bccdc3ced4ea5e64e
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/12/2022
ms.locfileid: "68542134"
---
# <a name="release-history-for-office-deployment-tool"></a>Office 部署工具的發行記錄

Office 部署工具 (ODT) 是一種命令列工具，可用來下載並部署隨選即用版本的 Office，例如Microsoft 365 Apps，部署到您的用戶端電腦。 

The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](/deployoffice/overview-of-the-office-2016-deployment-tool).

 **支援的作業系統**：Windows 10、Windows 8.1、Windows Server 2019 和 Windows Server 2016。 
 
 **安裝指示**：下載檔案然後執行自我解壓縮可執行檔，其中會包含 Office 部署工具可執行檔 (setup.exe) 及範例組態檔 (configuration.xml)。 

[下載 Office 部署工具](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="october-11-2022"></a>2022 年 10 月 11 日
版本 16.0.15629.20208 (**setup.exe** 16.0.15629.20196 版) 
- 可靠性改善

## <a name="september-13-2022"></a>2022 年 9 月 13 日
版本 16.0.15601.20148 (**setup.exe** 16.0.15601.20148 版) 
- 可靠性和復原能力改善

## <a name="august-16-2022"></a>2022 年 8 月 16 日
版本 16.0.15427.20220 **(setup.exe** 16.0.15427.20220 版) 
- 可靠性和復原能力改善

## <a name="july-12-2022"></a>2022 年 7 月 12 日
版本 16.0.15330.20230 (**setup.exe** 16.0.15330.20218 版) 
- 可靠性改善


## <a name="june-14-2022"></a>2022 年 6 月 14 日
版本 16.0.15225.20204 (**setup.exe** 16.0.15225.20172 版) 
- 可靠性改善。


## <a name="may-10-2022"></a>2022 年 5 月 10 日
版本 16.0.15128.20224 (**setup.exe** 16.0.15128.20220 版) 
- 可靠性改善。


## <a name="april-29-2022"></a>2022 年 4 月 29 日
版本 16.0.15028.20242 **(setup.exe** 16.0.15028.20242 版) 
- 可靠性改善。


## <a name="april-12-2022"></a>2022 年 4 月 12 日
版本 16.0.15028.20160 (**setup.exe** 16.0.15028.20152 版) 
- 安全修補程式。


## <a name="march-8-2022"></a>2022 年 3 月 8 日
版本 16.0.14931.20120 (**setup.exe** 16.0.14931.20118 版) 
- 安全修補程式。
- 可靠性改善。


## <a name="january-13-2022"></a>2022 年 1 月 13 日
版本 16.0.14729.20228 (**setup.exe** 16.0.14729.20228 版) 
- 已修正在特定網路 Proxy 設定下下載或安裝會失敗的問題。
- 已修正從每月企業通道從未連結內容下載失敗的問題。


## <a name="october-26-2021"></a>2021 年 10 月 26 日
版本 16.0.14527.20178 **(setup.exe** 16.0.14527.20144 版) 
- 一般可靠性改善。


## <a name="sept-16-2021"></a>2021 年 9 月 16 日
版本 16.0.14326.20404 (**setup.exe** 16.0.14326.20384 版) 
- Office LTSC 2021 產品的支援。
- 可靠性改善。


## <a name="july-12-2021"></a>2021 年 7 月 12 日
版本 16.0.14131.20278 (**setup.exe** 16.0.14131.20278 版) 
- 已修正 RemoveMSI 在某些情況下會失敗的問題。
- 修正偵測 setup.exe 並存執行的問題。
- ARM 平台的可靠性修正。


## <a name="june-17-2021"></a>2021 年 6 月 17 日
版本 16.0.14026.20306 **(setup.exe** 16.0.14026.20306 版) 
- 修正使用 MatchOS 語言選項的作業，在某些作業系統設定上失敗的問題。


## <a name="june-7-2021"></a>2021 年 6 月 7 日
版本 16.0.14026.20254 **(setup.exe** 16.0.14026.20252 版) 
- ARM 平台的可靠性修正。


## <a name="may-10-2021"></a>2021 年 5 月 10 日
版本 16.0.13929.20296 (**setup.exe** 16.0.13929.20238 版) 
- 已修正如果設定檔同時包含 MigrateArch 和 RemoveMSI，/configure 模式可能會失敗的問題
- 其他可靠性改善。

## <a name="april-13-2021"></a>2021 年 4 月 13 日
版本 16.0.13901.20336 (**setup.exe** 16.0.13901.20328 版) 
- 設定已在已安裝 Office 的裝置上執行作業的可靠性修正。
- 修正以在某些情況下避免顯示重複的進度 UI。
- 改善 UI 中顯示的錯誤碼正確性。
- ARM 平台的可靠性修正。

## <a name="march-23-2021"></a>2021 年 3 月 23 日
版本 16.0.13801.20360 (**setup.exe** 16.0.13801.20340 版) 
- 支援即將推出的 Office 產品版本資訊的變更。
- ARM 平台的可靠性修正。


## <a name="february-25-2021"></a>2021 年 2 月 25 日
版本 16.0.13628.20476 **(setup.exe** 16.0.13628.20462 版) 
- 修正 configuration.xml 檔案指定數十種無法驗證的語言的問題。
- 修正 MigrateArch 案例未遵守 FORCEAPPSHUTDOWN 屬性的問題。
- 修正在 configuration.xml 中指定 2 個或多個 PIDKEY 屬性而無法安裝 PIDKey 的問題。



## <a name="february-9-2021"></a>2021 年 2 月 9 日
版本 16.0.13628.20274 **(setup.exe** 16.0.13628.20246 版) 
- 我們已新增驗證來警告和防止在 Windows 8.0 上安裝不受支援。
- 已完成 ARM64 裝置的可靠性修正。


## <a name="january-12-2021"></a>2021 年 1 月 12 日
版本 16.0.13530.20376 (**setup.exe** 16.0.13530.20334 版) 
- 已修正損毀或非標準產品註冊可能會導致 RemoveMSI 作業停止運作的問題。

## <a name="december-21-2020"></a>2020 年 12 月 21 日
版本 16.0.13426.20370 **(setup.exe** 16.0.13426.20352 版) 
- 已修正從 PerpetualVL2019 通道安裝 ProofingTools 的本機來源無法運作的問題。
- 已修正當您在現有安裝中新增其他非完整 Office 語言中的產品時，確保隨選即用用戶端嘗試自我更新的問題。


## <a name="december-8-2020"></a>2020 年 12 月 8 日
版本 16.0.13426.20308 (**setup.exe** 16.0.13426.20308 版) 
- 已修正如果裝置的 Office 產品是從非Perpetual 2019 的通道進行安裝，則 [下載] 模式會封鎖 Perpetual 2019 的通道下載之問題。
- 已修正下列問題：架構移轉會針對透過下載模式建立的本機來源停止運作，該下載模式已在組態 XML 中指定明確的版本。


## <a name="november-23-2020"></a>2020 年 11 月 23 日
版本 16.0.13328.20420 (**setup.exe** 16.0.13328.20420 版) 
- 已修正下載模式未下載校訂工具的問題。
- 已修正在不相關的使用者內容中執行時，下載模式無法運作的問題。
- 已修正在組態 XML 中指定版本屬性會導致下載模式中下載不完整的問題。
- 已修正在解壓縮時，Office 部署工具未命名為 “setup.exe” 的問題。
- 已修正在組態 XML 中提供 Channel 屬性時，安裝來源優先順序的問題。

## <a name="november-10-2020"></a>2020 年 11 月 10 日
版本 16.0.13328.20356 (**setupODT.exe** 16.0.13328.20336 版) 
- 已新增可靠性和復原功能改善。
- 為了防止混淆及更輕鬆地診斷安裝程式錯誤，ODT 現在預設稱為 setupODT。

## <a name="october-29-2020"></a>2020 年 10 月 29 日
版本 16.0.13328.20292 **(setup.exe**  16.0.13328.20290 版) 
- 此版本可解決使用 RemoveMSI 時，某些 Office 2007 產品可能會意外封鎖安裝的問題。

## <a name="october-14-2020"></a>2020 年 10 月14 日
版本 16.0.13231.20368 (**setup.exe**  16.0.13231.20350 版) 
- 當沒有指定頻道時，預設情况下所有產品都將使用每月通道。
- 我們已改善從包含其他 DLL 的目錄執行 ODT 時的安全性。
- 已新增可靠性和復原功能改善。

## <a name="june-9-2020"></a>2020 年 6 月 9 日

版本 16.0.12827.20268 **(setup.exe**  16.0.12827.20258 版) 
- 在未指定頻道時，目前的通道即為預設的頻道。
- 我們新增了每月企業通道的支援。
- 我們新增了新通道名稱的支援。
- 如果可能，即使某些語言資源無法使用，仍可繼續安裝更多復原功能。
- 已完成擴充以移除 Office 2007 產品的 MSIRemove 功能。
- 已完成擴充以移除 Access 資料庫引擎的 MSIRemove 功能。

## <a name="april-15-2020"></a>2020 年 4 月 15 日

版本 16.0.12624.20320 (**setup.exe**  16.0.12624.20290 版) 
- 此版本新增 Windows 7 特定生命週期結束 Office 版本的支援。
- 我們已修正自訂設定可能不會如預期般套用的問題。
- 我們已修正意外下載無關的 .cat 檔案的問題。

## <a name="january-16-2020"></a>2020 年 1 月 16 日

版本 16.0.12325.20288
- 我們已修正安裝多種語言時，Office 安裝 UI 可能會以不正確的語言顯示的問題。
- 我們已修正安裝特定校訂工具套件時，Office 安裝可能會意外停止運作的問題。
- 此版本新增支援，可選擇性地控制 [Bing 功能中 Microsoft Search](/deployoffice/microsoft-search-bing)的初始部署。


## <a name="october-31-2019"></a>2019 年 10 月 31 日

版本 16.0.12130.20272
- 我們已修正允許 商務用 Skype Basic 2019 與 2019 永久企業大量授權產品一起安裝的問題。
- 我們已修正在使用 Proxy 時，可能會導致 ODT 下載模式在某些情況下意外停止運作的問題。
- 已完成允許 ODT 下載模式使用埠 80 以外的埠透過 HTTP 下載的新功能。


## <a name="july-10-2019"></a>2019 年 7 月 10 日

版本 16.0.11901.20022
- 我們已在 Office 2019 安裝時新增更多產品的支援：Access Runtime、商務用 Skype Basic。
- 我們新增了從 MSI 升級時，獨立產品的條件式安裝支援。

## <a name="april-23-2019"></a>2019 年 4 月 23 日

版本 16.0.11617.33601
- 我們已修正 RemoveMSI=True 的問題，以清除相關的登錄設定。
- 已更新錯誤碼，以針對已新增的非預期失敗 (E_UNEXPECTED) 提供更多詳細資料。

## <a name="april-16-2019"></a>2019 年 4 月 16 日

版本 16.0.11615.33602
- 已新增使用新 MigrateArch 屬性將 32 位 C2R 升級至 64 位 C2R 的支援。
- 已更新 和 設定的邏輯，允許存取儲存在 Web 位置 (HTTP 和 HTTPs) 的組態 XML 檔案。
- 已新增 MatchInstalled 為新屬性，允許 ODT 在新增其他產品或語言時比對現有版本。

## <a name="march-13-2019"></a>2019 年 3 月 13 日

版本 16.0.11509.33604
- 已新增升級和移轉案例的改善。

## <a name="january-14-2019"></a>2019 年 1 月 14 日

版本 16.0.11306.33602
- 已新增部署設定的記錄和遙測改善。


## <a name="related-links"></a>相關連結

[ODT 下載中心](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
