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
ms.openlocfilehash: 1622ddf9a89767c2d0e456737362eecf4123b3fd
ms.sourcegitcommit: a5da36df390868d76bddfc78e9481ed8e9c5b673
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/26/2019
ms.locfileid: "37275484"
---
# <a name="release-history-for-office-deployment-tool"></a>Office 部署工具的發行記錄

Office 部署工具 (ODT) 是一種命令列工具，可用來將像 Office 365 專業增強版這類的 Office 隨選即用版本下載並部署到用戶端電腦。 


ODT 能讓您進一步控制 Office 安裝。 您可以定義要安裝哪些產品及語言、這些產品的更新方式，以及是否要讓使用者看到安裝過程。 如需有關如何使用 ODT 的詳細資訊，請參閱 [Office 部署工具概觀](https://docs.microsoft.com/zh-TW/deployoffice/overview-of-the-office-2016-deployment-tool)。

 **支援的作業系統**：Windows 10、Windows 7、Windows 8、Windows 8.1、Windows Server 2008 R2、Windows Server 2012 和 Windows Server 2012 R2 
 
 **安裝指示**：下載檔案然後執行自我解壓縮可執行檔，其中會包含 Office 部署工具可執行檔 (setup.exe) 及範例組態檔 (configuration.xml)。 

[下載 Office 部署工具](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


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