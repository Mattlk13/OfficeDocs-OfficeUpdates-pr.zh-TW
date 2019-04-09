---
title: Office 測試人員的版本資訊
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 4/5/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 快」對象提供關鍵新功能、修正或已知問題的最新清單
ms.openlocfilehash: a829ee5b17b51382cbb85dd7a135b271b62235fc
ms.sourcegitcommit: d4f64674c19638db73a9706b105299dc0559ea64
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/08/2019
ms.locfileid: "31516068"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="afdca-103">Office 測試人員的版本資訊</span><span class="sxs-lookup"><span data-stu-id="afdca-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="afdca-104">本文包含 Windows 電腦版 Word、Excel、PowerPoint、Outlook、Access 和 Project 測試人員組建的版本資訊。</span><span class="sxs-lookup"><span data-stu-id="afdca-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="afdca-105">我們每週都強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。</span><span class="sxs-lookup"><span data-stu-id="afdca-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="afdca-106">請注意，我們在一段時間內會經常推出新功能 (某些時候還有修正) 給測試人員。</span><span class="sxs-lookup"><span data-stu-id="afdca-106">We often roll out features (and sometimes even fixes) to Monthly over a period of time.</span></span> <span data-ttu-id="afdca-107">這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。</span><span class="sxs-lookup"><span data-stu-id="afdca-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="afdca-108">所以，如果你沒有看到下面描述的項目，不要擔心你最終會得到它。</span><span class="sxs-lookup"><span data-stu-id="afdca-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="afdca-109">版本資訊會每週發佈，可能是多個組建的編譯</span><span class="sxs-lookup"><span data-stu-id="afdca-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="afdca-110">版本資訊發佈日期可能與實際組建發行日期不相符</span><span class="sxs-lookup"><span data-stu-id="afdca-110">The release notes publication date may not match the actual build release date</span></span>

## <a name="april-5th-2019"></a><span data-ttu-id="afdca-111">2019 年 4 月 5 日</span><span class="sxs-lookup"><span data-stu-id="afdca-111">April 5th, 2019</span></span>
<span data-ttu-id="afdca-112">版本 1904 (組建 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="afdca-112">Version 1904 (build 11527.20014)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="afdca-113">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="afdca-113">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="afdca-114">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="afdca-114">All Applications</span></span>
 - <span data-ttu-id="afdca-115">我們已修正 Excel 的內容功能表中會出現錯誤應用程式圖示的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-115">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="afdca-116">我們已修正在安裝更新之後 [檔案功能表] 按鈕會消失的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-116">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="afdca-117">我們已修正會變更您的使用者授權的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-117">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="afdca-118">Word</span><span class="sxs-lookup"><span data-stu-id="afdca-118">Word</span></span> 
- <span data-ttu-id="afdca-119">我們已修正文字在特定縮放比例中無法正常顯示的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-119">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="afdca-120">Excel</span><span class="sxs-lookup"><span data-stu-id="afdca-120">Excel</span></span>
- <span data-ttu-id="afdca-121">我們已修正使用者在進行編輯之後未收到儲存活頁簿提示的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-121">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="afdca-122">我們已修正當使用者共用活頁簿時未觸發 BeforeSave 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="afdca-122">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="afdca-123">我們已修正將欄的大小重新調整為小於 6 像素會擲回不正確錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="afdca-123">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="afdca-124">我們已修正 Excel 忽略 Application.Visible 旗標的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-124">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="afdca-125">我們已修正追蹤箭號保留在非作用中凍結窗格的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-125">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="afdca-126">我們已修正在開啟活頁簿時日期和貨幣儲存格格式會變更的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-126">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="afdca-127">我們已修正工具提示會意外移動的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-127">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="afdca-128">我們已修正 Power Query 編輯器的當地語系化問題</span><span class="sxs-lookup"><span data-stu-id="afdca-128">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="afdca-129">我們已修正在透過電子郵件傳送時活頁簿附件會遭到移除的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-129">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="afdca-130">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="afdca-130">PowerPoint</span></span>
- <span data-ttu-id="afdca-131">我們已修正複製圖形會比預期還要久的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-131">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="afdca-132">Outlook</span><span class="sxs-lookup"><span data-stu-id="afdca-132">Outlook</span></span>
- <span data-ttu-id="afdca-133">我們已修正在使用繪圖工具時 Outlook 可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-133">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="afdca-134">我們已修正當撰寫 html 電子郵件時的當地語系化問題</span><span class="sxs-lookup"><span data-stu-id="afdca-134">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="afdca-135">我們已修正使用者在選取下面窗格時會遇到困難的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-135">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="afdca-136">Access</span><span class="sxs-lookup"><span data-stu-id="afdca-136">Access</span></span>
- <span data-ttu-id="afdca-137">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-137">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="afdca-138">Project</span><span class="sxs-lookup"><span data-stu-id="afdca-138">Project</span></span>
- <span data-ttu-id="afdca-139">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-139">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="afdca-140">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="afdca-140">March 22, 2019</span></span>
<span data-ttu-id="afdca-141">版本 1904 (組建 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="afdca-141">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="afdca-142">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="afdca-142">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="afdca-143">Word</span><span class="sxs-lookup"><span data-stu-id="afdca-143">Word</span></span> 
- <span data-ttu-id="afdca-144">我們已修正 UI 經常會顯示「正在檢查變更」的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-144">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="afdca-145">Excel</span><span class="sxs-lookup"><span data-stu-id="afdca-145">Excel</span></span>
- <span data-ttu-id="afdca-146">我們已修正應用程式可能在移動工作表之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-146">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="afdca-147">我們已修正應用程式可能在儲存為 PDF 之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-147">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="afdca-148">我們已修正儲存對話方塊不會接受某些韓文字元的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-148">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="afdca-149">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="afdca-149">PowerPoint</span></span>
- <span data-ttu-id="afdca-150">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-150">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="afdca-151">Outlook</span><span class="sxs-lookup"><span data-stu-id="afdca-151">Outlook</span></span>
- <span data-ttu-id="afdca-152">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-152">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="afdca-153">Access</span><span class="sxs-lookup"><span data-stu-id="afdca-153">Access</span></span>
- <span data-ttu-id="afdca-154">我們已修正 Access 中對 Access 建立額外捷徑的錯誤訊息</span><span class="sxs-lookup"><span data-stu-id="afdca-154">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="afdca-155">我們已修正來自連結 SharePoint 的資料無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-155">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="afdca-156">Project</span><span class="sxs-lookup"><span data-stu-id="afdca-156">Project</span></span>
- <span data-ttu-id="afdca-157">我們已修正語言設定會從中文切換為英文的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-157">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="afdca-158">我們已修正應用程式可能在同步處理到 SharePoint 時當機的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-158">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="afdca-159">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="afdca-159">March 15, 2019</span></span>
<span data-ttu-id="afdca-160">版本 1904 (組建 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="afdca-160">Version 1904 (Build 11504.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="afdca-161">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="afdca-161">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="afdca-162">Word</span><span class="sxs-lookup"><span data-stu-id="afdca-162">Word</span></span> 
- <span data-ttu-id="afdca-163">我們已修正以 PDF 格式儲存文件時，文件中影像的 DPI 會不正確的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-163">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="afdca-164">Excel</span><span class="sxs-lookup"><span data-stu-id="afdca-164">Excel</span></span>
- <span data-ttu-id="afdca-165">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-165">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="afdca-166">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="afdca-166">PowerPoint</span></span>
- <span data-ttu-id="afdca-167">我們已修正註解窗格無法正確開啟或關閉的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-167">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="afdca-168">我們已修正應用程式會在刪除影片時當機的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-168">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="afdca-169">我們已修正於某些情況下應用程式會無法啟動的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-169">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="afdca-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="afdca-170">Outlook</span></span>
- <span data-ttu-id="afdca-171">我們已修正以日文檢視時讀信回條不正確的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-171">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="afdca-172">Access</span><span class="sxs-lookup"><span data-stu-id="afdca-172">Access</span></span>
- <span data-ttu-id="afdca-173">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-173">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="afdca-174">Project</span><span class="sxs-lookup"><span data-stu-id="afdca-174">Project</span></span>
- <span data-ttu-id="afdca-175">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-175">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="afdca-176">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="afdca-176">March 8, 2019</span></span> 
<span data-ttu-id="afdca-177">版本 1903 (組建 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="afdca-177">Version 1903 (Build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="afdca-178">新功能：</span><span class="sxs-lookup"><span data-stu-id="afdca-178">What's new</span></span>

### <a name="word"></a><span data-ttu-id="afdca-179">Word</span><span class="sxs-lookup"><span data-stu-id="afdca-179">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="afdca-180">使用 Microsoft Search 尋找您要的內容</span><span class="sxs-lookup"><span data-stu-id="afdca-180">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="afdca-181">您可以使用 Microsoft Search 找到所有檔案、動作、人員，協助您完成工作所需。</span><span class="sxs-lookup"><span data-stu-id="afdca-181">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="afdca-182">開始使用：</span><span class="sxs-lookup"><span data-stu-id="afdca-182">Getting started</span></span>

- <span data-ttu-id="afdca-183">這個功能在標題中的 UI 上方強調顯示。</span><span class="sxs-lookup"><span data-stu-id="afdca-183">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="afdca-184">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="afdca-184">Scenarios to Try:</span></span>

- <span data-ttu-id="afdca-185">搜尋某間大學、最近使用過的文件或搜尋最常用的功能區命令</span><span class="sxs-lookup"><span data-stu-id="afdca-185">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="afdca-186">尋找某個主題或主旨並取得更多相關資訊</span><span class="sxs-lookup"><span data-stu-id="afdca-186">Look up a topic or subject to get more information on it</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="afdca-187">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="afdca-187">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="afdca-188">Word</span><span class="sxs-lookup"><span data-stu-id="afdca-188">Word</span></span> 
- <span data-ttu-id="afdca-189">我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="afdca-189">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="afdca-190">我們已修正回覆註解時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="afdca-190">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="afdca-191">我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題</span><span class="sxs-lookup"><span data-stu-id="afdca-191">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="afdca-192">Excel</span><span class="sxs-lookup"><span data-stu-id="afdca-192">Excel</span></span>
- <span data-ttu-id="afdca-193">我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-193">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="afdca-194">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="afdca-194">PowerPoint</span></span>
- <span data-ttu-id="afdca-195">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-195">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="afdca-196">Outlook</span><span class="sxs-lookup"><span data-stu-id="afdca-196">Outlook</span></span>
- <span data-ttu-id="afdca-197">我們已修正 Outlook 搜尋未依所選時間順序排序的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-197">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="afdca-198">我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-198">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="afdca-199">我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-199">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="afdca-200">Access</span><span class="sxs-lookup"><span data-stu-id="afdca-200">Access</span></span>
- <span data-ttu-id="afdca-201">我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-201">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="afdca-202">我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 DisplayControl 屬性的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-202">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="afdca-203">Project</span><span class="sxs-lookup"><span data-stu-id="afdca-203">Project</span></span>
- <span data-ttu-id="afdca-204">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-204">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="afdca-205">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="afdca-205">March 1, 2019</span></span> 
<span data-ttu-id="afdca-206">版本 1903 (組建 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="afdca-206">Version 1903 (Build 11414.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="afdca-207">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="afdca-207">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="afdca-208">Word</span><span class="sxs-lookup"><span data-stu-id="afdca-208">Word</span></span> 
- <span data-ttu-id="afdca-209">我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="afdca-209">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="afdca-210">我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題</span><span class="sxs-lookup"><span data-stu-id="afdca-210">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="afdca-211">Excel</span><span class="sxs-lookup"><span data-stu-id="afdca-211">Excel</span></span>
- <span data-ttu-id="afdca-212">我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-212">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="afdca-213">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="afdca-213">PowerPoint</span></span>
- <span data-ttu-id="afdca-214">我們已修正在 PowerPoint 中使用 @Mentions 的投影片圖像大小問題</span><span class="sxs-lookup"><span data-stu-id="afdca-214">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="afdca-215">Outlook</span><span class="sxs-lookup"><span data-stu-id="afdca-215">Outlook</span></span>
- <span data-ttu-id="afdca-216">我們已修正 Outlook 搜尋未依所選時間順序排序的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-216">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="afdca-217">我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-217">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="afdca-218">我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-218">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="afdca-219">Access</span><span class="sxs-lookup"><span data-stu-id="afdca-219">Access</span></span>
- <span data-ttu-id="afdca-220">我們已更新確認使用資料來源重新連結資料表時顯示的提示文字</span><span class="sxs-lookup"><span data-stu-id="afdca-220">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="afdca-221">我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-221">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="afdca-222">我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 [顯示控制項] 屬性的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-222">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="afdca-223">Project</span><span class="sxs-lookup"><span data-stu-id="afdca-223">Project</span></span>
- <span data-ttu-id="afdca-224">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-224">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="afdca-225">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="afdca-225">February 15, 2019</span></span> 
<span data-ttu-id="afdca-226">版本 1903 (組建 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="afdca-226">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="afdca-227">新功能：</span><span class="sxs-lookup"><span data-stu-id="afdca-227">What's new</span></span>

### <a name="powerpoint"></a><span data-ttu-id="afdca-228">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="afdca-228">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="afdca-229">轉化轉場增強效果 - 依名稱轉化</span><span class="sxs-lookup"><span data-stu-id="afdca-229">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="afdca-230">選取要轉化的圖形</span><span class="sxs-lookup"><span data-stu-id="afdca-230">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="afdca-231">開始使用：</span><span class="sxs-lookup"><span data-stu-id="afdca-231">Getting started</span></span>

- <span data-ttu-id="afdca-232">若要使轉化將兩個物件視為同一個物件，使用者可以使用 [選取窗格] 重新命名圖形。</span><span class="sxs-lookup"><span data-stu-id="afdca-232">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="afdca-233">名稱前面必須加上「!!」</span><span class="sxs-lookup"><span data-stu-id="afdca-233">The name must be prefaced with “!!”</span></span> <span data-ttu-id="afdca-234">(兩個半形驚嘆號)，例如「!!名稱」，轉化才能用來覆寫預設比對行為</span><span class="sxs-lookup"><span data-stu-id="afdca-234">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="afdca-235">使用者可以繼續將圖形重新命名為不是以「!!」為開頭的任何名稱</span><span class="sxs-lookup"><span data-stu-id="afdca-235">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="afdca-236">不必擔心會變更轉化的運作方式</span><span class="sxs-lookup"><span data-stu-id="afdca-236">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="afdca-237">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="afdca-237">Scenarios to Try:</span></span>

- <span data-ttu-id="afdca-238">在投影片中插入圖形，讓我們假設是矩形</span><span class="sxs-lookup"><span data-stu-id="afdca-238">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="afdca-239">建立新投影片</span><span class="sxs-lookup"><span data-stu-id="afdca-239">Create a new slide</span></span>
- <span data-ttu-id="afdca-240">在第 2 張投影片中插入不同的圖形，讓我們假設是三角形</span><span class="sxs-lookup"><span data-stu-id="afdca-240">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="afdca-241">開啟 [選取窗格]，將投影片 1 中的矩形重新命名為「!!圖形」，將投影片 2 中的三角形重新命名為「!!圖形」</span><span class="sxs-lookup"><span data-stu-id="afdca-241">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="afdca-242">將 [轉化] 套用至第 2 張投影片</span><span class="sxs-lookup"><span data-stu-id="afdca-242">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="afdca-243">轉化轉場增強效果 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="afdca-243">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="afdca-244">轉場更順暢的 SmartArt 轉化</span><span class="sxs-lookup"><span data-stu-id="afdca-244">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="afdca-245">開始使用：</span><span class="sxs-lookup"><span data-stu-id="afdca-245">Getting started</span></span>

<span data-ttu-id="afdca-246">您使用 SmartArt 的方式與轉化相同</span><span class="sxs-lookup"><span data-stu-id="afdca-246">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="afdca-247">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="afdca-247">Scenarios to Try:</span></span>

- <span data-ttu-id="afdca-248">在投影片中插入 SmartArt</span><span class="sxs-lookup"><span data-stu-id="afdca-248">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="afdca-249">複製投影片</span><span class="sxs-lookup"><span data-stu-id="afdca-249">Duplicate the Slide</span></span>
- <span data-ttu-id="afdca-250">在複製的投影片上調整大小/變更/移動 SmartArt</span><span class="sxs-lookup"><span data-stu-id="afdca-250">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="afdca-251">在複製的投影片上套用 [轉化]</span><span class="sxs-lookup"><span data-stu-id="afdca-251">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="afdca-252">轉化轉場增強效果 - 表格​​</span><span class="sxs-lookup"><span data-stu-id="afdca-252">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="afdca-253">轉場更順暢的表格轉化</span><span class="sxs-lookup"><span data-stu-id="afdca-253">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="afdca-254">開始使用：</span><span class="sxs-lookup"><span data-stu-id="afdca-254">Getting started</span></span>
<span data-ttu-id="afdca-255">您使用表格的方式與轉化相同</span><span class="sxs-lookup"><span data-stu-id="afdca-255">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="afdca-256">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="afdca-256">Scenarios to Try:</span></span>

- <span data-ttu-id="afdca-257">在投影片中插入表格</span><span class="sxs-lookup"><span data-stu-id="afdca-257">Insert a Table in a slide</span></span>
- <span data-ttu-id="afdca-258">複製投影片</span><span class="sxs-lookup"><span data-stu-id="afdca-258">Duplicate the slide</span></span>
- <span data-ttu-id="afdca-259">在複製的投影片上調整大小/變更/移動表格</span><span class="sxs-lookup"><span data-stu-id="afdca-259">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="afdca-260">在複製的投影片上套用 [轉化]</span><span class="sxs-lookup"><span data-stu-id="afdca-260">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="afdca-261">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher 和 Visio</span><span class="sxs-lookup"><span data-stu-id="afdca-261">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="afdca-262">在不同帳戶之間順暢切換</span><span class="sxs-lookup"><span data-stu-id="afdca-262">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="afdca-263">全新的帳戶管理員會在同一個地方顯示您所有的工作和個人帳戶，讓您能控制在其間切換。</span><span class="sxs-lookup"><span data-stu-id="afdca-263">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="afdca-264">這項更新的經驗能清楚知道您的登入方法，因此您現在不需要先登出或處理複雜的對話方塊就可以切換工作和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="afdca-264">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="afdca-266">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="afdca-266">Scenarios to Try:</span></span>
- <span data-ttu-id="afdca-267">在不同的帳戶之間切換</span><span class="sxs-lookup"><span data-stu-id="afdca-267">Switch between accounts</span></span>
- <span data-ttu-id="afdca-268">新增帳戶 [附註：您可能想要先移至 [檔案] | [帳戶] | [已連線服務]，移除任何已連線至工作帳戶的個人服務或是反向服務]</span><span class="sxs-lookup"><span data-stu-id="afdca-268">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="afdca-269">登出帳戶</span><span class="sxs-lookup"><span data-stu-id="afdca-269">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="afdca-270">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="afdca-270">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="afdca-271">Word</span><span class="sxs-lookup"><span data-stu-id="afdca-271">Word</span></span> 
- <span data-ttu-id="afdca-272">我們已修正表格和影像的內容預覽問題</span><span class="sxs-lookup"><span data-stu-id="afdca-272">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="afdca-273">Excel</span><span class="sxs-lookup"><span data-stu-id="afdca-273">Excel</span></span>
- <span data-ttu-id="afdca-274">我們已修正在黑色佈景主題中，自動篩選的搜尋欄位中文字是白色的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-274">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="afdca-275">我們已修正新 Office 增益集的同意 UI 問題</span><span class="sxs-lookup"><span data-stu-id="afdca-275">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="afdca-276">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="afdca-276">PowerPoint</span></span>
- <span data-ttu-id="afdca-277">我們已修正在膝上型電腦或平板電腦上進行投影片簡報時自動延伸顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="afdca-277">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="afdca-278">Outlook</span><span class="sxs-lookup"><span data-stu-id="afdca-278">Outlook</span></span>
- <span data-ttu-id="afdca-279">我們已修正 [傳送至 OneNote] 按鈕的顯示問題</span><span class="sxs-lookup"><span data-stu-id="afdca-279">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="afdca-280">Access</span><span class="sxs-lookup"><span data-stu-id="afdca-280">Access</span></span>
- <span data-ttu-id="afdca-281">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-281">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="afdca-282">Project</span><span class="sxs-lookup"><span data-stu-id="afdca-282">Project</span></span>
- <span data-ttu-id="afdca-283">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-283">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="afdca-284">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="afdca-284">Week of February 11, 2019</span></span>
<span data-ttu-id="afdca-285">版本 1903 (組建 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="afdca-285">Version 1903 (Build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="afdca-286">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="afdca-286">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="afdca-287">Word</span><span class="sxs-lookup"><span data-stu-id="afdca-287">Word</span></span> 
- <span data-ttu-id="afdca-288">我們已修正某些自訂樣式無法套用至線上 Word 的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-288">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="afdca-289">我們已修正 Word 中豐富物件的內容預覽問題</span><span class="sxs-lookup"><span data-stu-id="afdca-289">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="afdca-290">我們已修正貼上清單會導致 Word 當機的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-290">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="afdca-291">Excel</span><span class="sxs-lookup"><span data-stu-id="afdca-291">Excel</span></span>
- <span data-ttu-id="afdca-292">我們已修正無貨幣符號時，數字格式後的附加空白不再顯示的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-292">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="afdca-293">我們已修正自動偵測股票的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-293">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="afdca-294">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="afdca-294">PowerPoint</span></span>
- <span data-ttu-id="afdca-295">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-295">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="afdca-296">Outlook</span><span class="sxs-lookup"><span data-stu-id="afdca-296">Outlook</span></span>
- <span data-ttu-id="afdca-297">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-297">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="afdca-298">Access</span><span class="sxs-lookup"><span data-stu-id="afdca-298">Access</span></span>
- <span data-ttu-id="afdca-299">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-299">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="afdca-300">Project</span><span class="sxs-lookup"><span data-stu-id="afdca-300">Project</span></span>
- <span data-ttu-id="afdca-301">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-301">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="afdca-302">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="afdca-302">February 1, 2019</span></span> 
<span data-ttu-id="afdca-303">版本 1902 (組建 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="afdca-303">Version 1902 (Build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="afdca-304">值得注意的修正</span><span class="sxs-lookup"><span data-stu-id="afdca-304">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="afdca-305">Word</span><span class="sxs-lookup"><span data-stu-id="afdca-305">Word</span></span> 
- <span data-ttu-id="afdca-306">我們已修正內嵌 Excel 表格中調整儲存格大小的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-306">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="afdca-307">我們已修正繪圖畫布中複製/貼上圖形的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-307">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="afdca-308">Excel</span><span class="sxs-lookup"><span data-stu-id="afdca-308">Excel</span></span>
- <span data-ttu-id="afdca-309">我們已修正從 Excel Web App 開啟檔案的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-309">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="afdca-310">我們已修正因為檔名大小造成 CSV 檔案儲存為 XLSX 失敗的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-310">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="afdca-311">我們已修正快顯功能表顯示快顯功能表選項的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-311">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="afdca-312">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="afdca-312">PowerPoint</span></span>
- <span data-ttu-id="afdca-313">我們已修正使用者無法使用鍵盤快速鍵 ctrl+alt+7/ctrl+alt+8 輸入方括號的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-313">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="afdca-314">我們已修正將本機影片插入至 PPT 會減少 C 磁碟機磁碟空間的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-314">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="afdca-315">我們已修正 [發佈至 Microsoft Stream] 按鈕無法向某些使用者顯示的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-315">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="afdca-316">Outlook</span><span class="sxs-lookup"><span data-stu-id="afdca-316">Outlook</span></span>
- <span data-ttu-id="afdca-317">我們已修正行事曆中工作檢視無法正確顯示工作主旨的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-317">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="afdca-318">Access</span><span class="sxs-lookup"><span data-stu-id="afdca-318">Access</span></span>
- <span data-ttu-id="afdca-319">我們已修正圖表的縮放比例的問題</span><span class="sxs-lookup"><span data-stu-id="afdca-319">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="afdca-320">Project</span><span class="sxs-lookup"><span data-stu-id="afdca-320">Project</span></span>
- <span data-ttu-id="afdca-321">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="afdca-321">Various performance and stability fixes</span></span>
