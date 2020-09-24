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
ms.openlocfilehash: c01fbe403dacb0b474c37b7439eba5b616f8a08f
ms.sourcegitcommit: 591f5da255de896ef3156108349c6d2eaf34ed54
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/22/2020
ms.locfileid: "48174642"
---
# <a name="release-history-for-office-deployment-tool"></a>Office 部署工具的發行記錄

Office 部署工具 (ODT) 是一種命令列工具，可用來將像 Microsoft 365 應用程式這類的 Office 隨選即用版本下載並部署到用戶端電腦。 


ODT 能讓您進一步控制 Office 安裝。 您可以定義要安裝哪些產品及語言、這些產品的更新方式，以及是否要讓使用者看到安裝過程。 如需有關如何使用 ODT 的詳細資訊，請參閱 [Office 部署工具概觀](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)。

 **支援作業系統**：Windows 10、Windows 8.1、Windows Server 2019、Windows Server 2016 
 
 **安裝指示**：下載檔案然後執行自我解壓縮可執行檔，其中會包含 Office 部署工具可執行檔 (setup.exe) 及範例組態檔 (configuration.xml)。 

[下載 Office 部署工具](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


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