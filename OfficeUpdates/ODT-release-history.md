---
title: Office 部署工具 (ODT) 的發行記錄
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: 為 IT 專業人員提供 Office 部署工具 (ODT) 的發行記錄
ms.openlocfilehash: fb59993362c4c186518f8472cb0330fa1b1e8d58
ms.sourcegitcommit: f042b25b15960fc4911a7e7d8500dcfd992ee95c
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 01/17/2020
ms.locfileid: "41230061"
---
# <a name="release-history-for-office-deployment-tool"></a>Office 部署工具的發行記錄

Office 部署工具 (ODT) 是一種命令列工具，可用來將像 Office 365 專業增強版這類的 Office 隨選即用版本下載並部署到用戶端電腦。 


ODT 能讓您進一步控制 Office 安裝。 您可以定義要安裝哪些產品及語言、這些產品的更新方式，以及是否要讓使用者看到安裝過程。 如需有關如何使用 ODT 的詳細資訊，請參閱 [Office 部署工具概觀](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)。

 **支援的作業系統**：Windows 10、Windows 7、Windows 8、Windows 8.1、Windows Server 2008 R2、Windows Server 2012 和 Windows Server 2012 R2 
 
 **安裝指示**：下載檔案然後執行自我解壓縮可執行檔，其中會包含 Office 部署工具可執行檔 (setup.exe) 及範例組態檔 (configuration.xml)。 

[下載 Office 部署工具](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


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