---
title: Office 測試人員的版本資訊
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 4/11/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 為「測試人員 - 快」對象提供關鍵新功能、修正或已知問題的最新清單
ms.openlocfilehash: cecd509883c6738c9640dabe15ec6f31ad5baf64
ms.sourcegitcommit: 2e379740ddeb6f2e8f51da1d06002ffb2ddad02d
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/11/2019
ms.locfileid: "31818510"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="a82f4-103">Office 測試人員的版本資訊</span><span class="sxs-lookup"><span data-stu-id="a82f4-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="a82f4-104">本文包含 Windows 電腦版 Word、Excel、PowerPoint、Outlook、Access 和 Project 測試人員組建的版本資訊。</span><span class="sxs-lookup"><span data-stu-id="a82f4-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="a82f4-105">我們每週都強調有趣的新功能、重要修正，以及我們想讓您知道的重大問題。</span><span class="sxs-lookup"><span data-stu-id="a82f4-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="a82f4-106">請注意，我們在一段時間內會經常推出新功能 (某些時候還有修正) 給測試人員。</span><span class="sxs-lookup"><span data-stu-id="a82f4-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="a82f4-107">這樣可讓我們確保功能都運作順利，然後才推出給更廣泛的對象。</span><span class="sxs-lookup"><span data-stu-id="a82f4-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="a82f4-108">所以，如果你沒有看到下面描述的項目，不要擔心你最終會得到它。</span><span class="sxs-lookup"><span data-stu-id="a82f4-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="a82f4-109">版本資訊會每週發佈，可能是多個組建的編譯</span><span class="sxs-lookup"><span data-stu-id="a82f4-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="a82f4-110">版本資訊發佈日期可能與實際組建發行日期不相符</span><span class="sxs-lookup"><span data-stu-id="a82f4-110">The release notes publication date may not match the actual build release date</span></span>

## <a name="april-11-2019"></a><span data-ttu-id="a82f4-111">2019 年 4 月 11 日</span><span class="sxs-lookup"><span data-stu-id="a82f4-111">April 11, 2019</span></span>
<span data-ttu-id="a82f4-112">版本 1905 (組建 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="a82f4-112">Version 1905 (build 11601.20042)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a82f4-113">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="a82f4-113">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="a82f4-114">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="a82f4-114">All Applications</span></span>
 - <span data-ttu-id="a82f4-115">我們已修正會防止使用者將檔案儲存到雲端位置的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-115">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="a82f4-116">我們已修正可能從功能區開啟錯誤窗格的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-116">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="a82f4-117">Word</span><span class="sxs-lookup"><span data-stu-id="a82f4-117">Word</span></span> 
- <span data-ttu-id="a82f4-118">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-118">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a82f4-119">Excel</span><span class="sxs-lookup"><span data-stu-id="a82f4-119">Excel</span></span>
- <span data-ttu-id="a82f4-120">我們已修正當活頁簿不包含連結資料類型時，使用者會看到連結資料類型之錯誤訊息的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-120">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="a82f4-121">我們已修正在本機與線上檢視 Word 文件時，文件中的 URL 連結可能變更的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-121">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a82f4-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a82f4-122">PowerPoint</span></span>
- <span data-ttu-id="a82f4-123">我們已修正應用程式可能會在從 [動畫] 索引標籤復原變更之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-123">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="a82f4-124">Outlook</span><span class="sxs-lookup"><span data-stu-id="a82f4-124">Outlook</span></span>
- <span data-ttu-id="a82f4-125">我們已修正會防止一些使用者修改公用資料夾中連絡人 [備註] 欄位的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-125">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="a82f4-126">我們已修正到期日與刪除日期之間可能發生衝突的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-126">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="a82f4-127">Access</span><span class="sxs-lookup"><span data-stu-id="a82f4-127">Access</span></span>
- <span data-ttu-id="a82f4-128">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-128">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a82f4-129">Project</span><span class="sxs-lookup"><span data-stu-id="a82f4-129">Project</span></span>
- <span data-ttu-id="a82f4-130">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-130">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="a82f4-131">2019 年 4 月 5 日</span><span class="sxs-lookup"><span data-stu-id="a82f4-131">April 5, 2019</span></span>
<span data-ttu-id="a82f4-132">版本 1904 (組建 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="a82f4-132">Version 1904 (build 11527.20014)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a82f4-133">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="a82f4-133">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="a82f4-134">所有應用程式</span><span class="sxs-lookup"><span data-stu-id="a82f4-134">All Applications</span></span>
 - <span data-ttu-id="a82f4-135">我們已修正 Excel 的內容功能表中會出現錯誤應用程式圖示的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-135">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="a82f4-136">我們已修正在安裝更新之後 [檔案功能表] 按鈕會消失的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-136">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="a82f4-137">我們已修正會變更您的使用者授權的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-137">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="a82f4-138">Word</span><span class="sxs-lookup"><span data-stu-id="a82f4-138">Word</span></span> 
- <span data-ttu-id="a82f4-139">我們已修正文字在特定縮放比例中無法正常顯示的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-139">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="a82f4-140">Excel</span><span class="sxs-lookup"><span data-stu-id="a82f4-140">Excel</span></span>
- <span data-ttu-id="a82f4-141">我們已修正使用者在進行編輯之後未收到儲存活頁簿提示的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-141">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="a82f4-142">我們已修正當使用者共用活頁簿時未觸發 BeforeSave 事件的問題。</span><span class="sxs-lookup"><span data-stu-id="a82f4-142">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="a82f4-143">我們已修正將欄的大小重新調整為小於 6 像素會擲回不正確錯誤訊息的問題。</span><span class="sxs-lookup"><span data-stu-id="a82f4-143">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="a82f4-144">我們已修正 Excel 忽略 Application.Visible 旗標的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-144">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="a82f4-145">我們已修正追蹤箭號保留在非作用中凍結窗格的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-145">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="a82f4-146">我們已修正在開啟活頁簿時日期和貨幣儲存格格式會變更的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-146">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="a82f4-147">我們已修正工具提示會意外移動的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-147">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="a82f4-148">我們已修正 Power Query 編輯器的當地語系化問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-148">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="a82f4-149">我們已修正在透過電子郵件傳送時活頁簿附件會遭到移除的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-149">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a82f4-150">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a82f4-150">PowerPoint</span></span>
- <span data-ttu-id="a82f4-151">我們已修正複製圖形會比預期還要久的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-151">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="a82f4-152">Outlook</span><span class="sxs-lookup"><span data-stu-id="a82f4-152">Outlook</span></span>
- <span data-ttu-id="a82f4-153">我們已修正在使用繪圖工具時 Outlook 可能會當機的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-153">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="a82f4-154">我們已修正當撰寫 html 電子郵件時的當地語系化問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-154">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="a82f4-155">我們已修正使用者在選取下面窗格時會遇到困難的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-155">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="a82f4-156">Access</span><span class="sxs-lookup"><span data-stu-id="a82f4-156">Access</span></span>
- <span data-ttu-id="a82f4-157">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-157">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a82f4-158">Project</span><span class="sxs-lookup"><span data-stu-id="a82f4-158">Project</span></span>
- <span data-ttu-id="a82f4-159">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-159">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="a82f4-160">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="a82f4-160">March 22, 2019</span></span>
<span data-ttu-id="a82f4-161">版本 1904 (組建 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="a82f4-161">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a82f4-162">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="a82f4-162">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a82f4-163">Word</span><span class="sxs-lookup"><span data-stu-id="a82f4-163">Word</span></span> 
- <span data-ttu-id="a82f4-164">我們已修正 UI 經常會顯示「正在檢查變更」的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-164">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="a82f4-165">Excel</span><span class="sxs-lookup"><span data-stu-id="a82f4-165">Excel</span></span>
- <span data-ttu-id="a82f4-166">我們已修正應用程式可能在移動工作表之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-166">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="a82f4-167">我們已修正應用程式可能在儲存為 PDF 之後當機的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-167">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="a82f4-168">我們已修正儲存對話方塊不會接受某些韓文字元的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-168">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a82f4-169">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a82f4-169">PowerPoint</span></span>
- <span data-ttu-id="a82f4-170">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-170">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a82f4-171">Outlook</span><span class="sxs-lookup"><span data-stu-id="a82f4-171">Outlook</span></span>
- <span data-ttu-id="a82f4-172">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-172">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a82f4-173">Access</span><span class="sxs-lookup"><span data-stu-id="a82f4-173">Access</span></span>
- <span data-ttu-id="a82f4-174">我們已修正 Access 中對 Access 建立額外捷徑的錯誤訊息</span><span class="sxs-lookup"><span data-stu-id="a82f4-174">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="a82f4-175">我們已修正來自連結 SharePoint 的資料無法正確顯示的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-175">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="a82f4-176">Project</span><span class="sxs-lookup"><span data-stu-id="a82f4-176">Project</span></span>
- <span data-ttu-id="a82f4-177">我們已修正語言設定會從中文切換為英文的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-177">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="a82f4-178">我們已修正應用程式可能在同步處理到 SharePoint 時當機的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-178">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="a82f4-179">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="a82f4-179">March 15, 2019</span></span>
<span data-ttu-id="a82f4-180">版本 1904 (組建 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="a82f4-180">Version 1904 (build 11504.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a82f4-181">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="a82f4-181">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a82f4-182">Word</span><span class="sxs-lookup"><span data-stu-id="a82f4-182">Word</span></span> 
- <span data-ttu-id="a82f4-183">我們已修正以 PDF 格式儲存文件時，文件中影像的 DPI 會不正確的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-183">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="a82f4-184">Excel</span><span class="sxs-lookup"><span data-stu-id="a82f4-184">Excel</span></span>
- <span data-ttu-id="a82f4-185">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-185">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a82f4-186">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a82f4-186">PowerPoint</span></span>
- <span data-ttu-id="a82f4-187">我們已修正註解窗格無法正確開啟或關閉的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-187">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="a82f4-188">我們已修正應用程式會在刪除影片時當機的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-188">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="a82f4-189">我們已修正於某些情況下應用程式會無法啟動的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-189">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="a82f4-190">Outlook</span><span class="sxs-lookup"><span data-stu-id="a82f4-190">Outlook</span></span>
- <span data-ttu-id="a82f4-191">我們已修正以日文檢視時讀信回條不正確的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-191">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="a82f4-192">Access</span><span class="sxs-lookup"><span data-stu-id="a82f4-192">Access</span></span>
- <span data-ttu-id="a82f4-193">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-193">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a82f4-194">Project</span><span class="sxs-lookup"><span data-stu-id="a82f4-194">Project</span></span>
- <span data-ttu-id="a82f4-195">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-195">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="a82f4-196">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="a82f4-196">March 8, 2019</span></span> 
<span data-ttu-id="a82f4-197">版本 1903 (組建 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="a82f4-197">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a82f4-198">新功能：</span><span class="sxs-lookup"><span data-stu-id="a82f4-198">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="a82f4-199">Word</span><span class="sxs-lookup"><span data-stu-id="a82f4-199">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="a82f4-200">使用 Microsoft Search 尋找您要的內容</span><span class="sxs-lookup"><span data-stu-id="a82f4-200">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="a82f4-201">您可以使用 Microsoft Search 找到所有檔案、動作、人員，協助您完成工作所需。</span><span class="sxs-lookup"><span data-stu-id="a82f4-201">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a82f4-202">開始使用：</span><span class="sxs-lookup"><span data-stu-id="a82f4-202">Getting Started:</span></span>

- <span data-ttu-id="a82f4-203">這個功能在標題中的 UI 上方強調顯示。</span><span class="sxs-lookup"><span data-stu-id="a82f4-203">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a82f4-204">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="a82f4-204">Scenarios to Try:</span></span>

- <span data-ttu-id="a82f4-205">搜尋某間大學、最近使用過的文件或搜尋最常用的功能區命令</span><span class="sxs-lookup"><span data-stu-id="a82f4-205">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="a82f4-206">尋找某個主題或主旨並取得更多相關資訊</span><span class="sxs-lookup"><span data-stu-id="a82f4-206">Look up a topic or subject to get more information on it</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="a82f4-207">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="a82f4-207">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a82f4-208">Word</span><span class="sxs-lookup"><span data-stu-id="a82f4-208">Word</span></span> 
- <span data-ttu-id="a82f4-209">我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-209">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="a82f4-210">我們已修正回覆註解時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-210">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="a82f4-211">我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-211">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="a82f4-212">Excel</span><span class="sxs-lookup"><span data-stu-id="a82f4-212">Excel</span></span>
- <span data-ttu-id="a82f4-213">我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-213">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a82f4-214">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a82f4-214">PowerPoint</span></span>
- <span data-ttu-id="a82f4-215">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-215">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a82f4-216">Outlook</span><span class="sxs-lookup"><span data-stu-id="a82f4-216">Outlook</span></span>
- <span data-ttu-id="a82f4-217">我們已修正 Outlook 搜尋未依所選時間順序排序的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-217">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="a82f4-218">我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-218">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="a82f4-219">我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-219">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="a82f4-220">Access</span><span class="sxs-lookup"><span data-stu-id="a82f4-220">Access</span></span>
- <span data-ttu-id="a82f4-221">我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-221">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="a82f4-222">我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 DisplayControl 屬性的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-222">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="a82f4-223">Project</span><span class="sxs-lookup"><span data-stu-id="a82f4-223">Project</span></span>
- <span data-ttu-id="a82f4-224">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-224">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="a82f4-225">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a82f4-225">March 1, 2019</span></span> 
<span data-ttu-id="a82f4-226">版本 1903 (組建 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="a82f4-226">Version 1903 (build 11414.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="a82f4-227">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="a82f4-227">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a82f4-228">Word</span><span class="sxs-lookup"><span data-stu-id="a82f4-228">Word</span></span> 
- <span data-ttu-id="a82f4-229">我們已修正在 [選項] 中按下 ESC 鍵時發生的當機問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-229">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="a82f4-230">我們已修正從 Word 到 PowerPoint Online 的複製與貼上問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-230">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="a82f4-231">Excel</span><span class="sxs-lookup"><span data-stu-id="a82f4-231">Excel</span></span>
- <span data-ttu-id="a82f4-232">我們已修正當受保護的文件和可編輯的文件在開啟時複製 Excel 儲存格導致高 CPU 使用率的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-232">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a82f4-233">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a82f4-233">PowerPoint</span></span>
- <span data-ttu-id="a82f4-234">我們已修正在 PowerPoint 中使用 @Mentions 的投影片圖像大小問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-234">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="a82f4-235">Outlook</span><span class="sxs-lookup"><span data-stu-id="a82f4-235">Outlook</span></span>
- <span data-ttu-id="a82f4-236">我們已修正 Outlook 搜尋未依所選時間順序排序的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-236">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="a82f4-237">我們已修正 [開啟此工作] 工作流程功能區按鈕無法回應特定電子郵件的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-237">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="a82f4-238">我們已修正使用者在 [會議室尋找工具] 中選取可用的會議室後，Outlook 無法清除內部部署會議室的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-238">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="a82f4-239">Access</span><span class="sxs-lookup"><span data-stu-id="a82f4-239">Access</span></span>
- <span data-ttu-id="a82f4-240">我們已更新確認使用資料來源重新連結資料表時顯示的提示文字</span><span class="sxs-lookup"><span data-stu-id="a82f4-240">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="a82f4-241">我們已修正已儲存的匯入/匯出對話方塊在深色佈景主題中有白色文字在白色背景的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-241">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="a82f4-242">我們已修正使用者在表格設計中無法針對 [文字方塊] 的 [是/否] 欄位設定 [顯示控制項] 屬性的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-242">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="a82f4-243">Project</span><span class="sxs-lookup"><span data-stu-id="a82f4-243">Project</span></span>
- <span data-ttu-id="a82f4-244">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-244">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="a82f4-245">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="a82f4-245">February 15, 2019</span></span> 
<span data-ttu-id="a82f4-246">版本 1903 (組建 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="a82f4-246">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a82f4-247">新功能：</span><span class="sxs-lookup"><span data-stu-id="a82f4-247">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a82f4-248">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a82f4-248">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="a82f4-249">轉化轉場增強效果 - 依名稱轉化</span><span class="sxs-lookup"><span data-stu-id="a82f4-249">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="a82f4-250">選取要轉化的圖形</span><span class="sxs-lookup"><span data-stu-id="a82f4-250">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a82f4-251">開始使用：</span><span class="sxs-lookup"><span data-stu-id="a82f4-251">Getting Started:</span></span>

- <span data-ttu-id="a82f4-252">若要使轉化將兩個物件視為同一個物件，使用者可以使用 [選取窗格] 重新命名圖形。</span><span class="sxs-lookup"><span data-stu-id="a82f4-252">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="a82f4-253">名稱前面必須加上「!!」</span><span class="sxs-lookup"><span data-stu-id="a82f4-253">The name must be prefaced with “!!”</span></span> <span data-ttu-id="a82f4-254">(兩個半形驚嘆號)，例如「!!名稱」，轉化才能用來覆寫預設比對行為</span><span class="sxs-lookup"><span data-stu-id="a82f4-254">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="a82f4-255">使用者可以繼續將圖形重新命名為不是以「!!」為開頭的任何名稱</span><span class="sxs-lookup"><span data-stu-id="a82f4-255">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="a82f4-256">不必擔心會變更轉化的運作方式</span><span class="sxs-lookup"><span data-stu-id="a82f4-256">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a82f4-257">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="a82f4-257">Scenarios to Try:</span></span>

- <span data-ttu-id="a82f4-258">在投影片中插入圖形，讓我們假設是矩形</span><span class="sxs-lookup"><span data-stu-id="a82f4-258">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="a82f4-259">建立新投影片</span><span class="sxs-lookup"><span data-stu-id="a82f4-259">Create a new slide</span></span>
- <span data-ttu-id="a82f4-260">在第 2 張投影片中插入不同的圖形，讓我們假設是三角形</span><span class="sxs-lookup"><span data-stu-id="a82f4-260">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="a82f4-261">開啟 [選取窗格]，將投影片 1 中的矩形重新命名為「!!圖形」，將投影片 2 中的三角形重新命名為「!!圖形」</span><span class="sxs-lookup"><span data-stu-id="a82f4-261">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="a82f4-262">將 [轉化] 套用至第 2 張投影片</span><span class="sxs-lookup"><span data-stu-id="a82f4-262">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="a82f4-263">轉化轉場增強效果 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="a82f4-263">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="a82f4-264">轉場更順暢的 SmartArt 轉化</span><span class="sxs-lookup"><span data-stu-id="a82f4-264">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a82f4-265">開始使用：</span><span class="sxs-lookup"><span data-stu-id="a82f4-265">Getting Started:</span></span>

<span data-ttu-id="a82f4-266">您使用 SmartArt 的方式與轉化相同</span><span class="sxs-lookup"><span data-stu-id="a82f4-266">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a82f4-267">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="a82f4-267">Scenarios to Try:</span></span>

- <span data-ttu-id="a82f4-268">在投影片中插入 SmartArt</span><span class="sxs-lookup"><span data-stu-id="a82f4-268">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="a82f4-269">複製投影片</span><span class="sxs-lookup"><span data-stu-id="a82f4-269">Duplicate the Slide</span></span>
- <span data-ttu-id="a82f4-270">在複製的投影片上調整大小/變更/移動 SmartArt</span><span class="sxs-lookup"><span data-stu-id="a82f4-270">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="a82f4-271">在複製的投影片上套用 [轉化]</span><span class="sxs-lookup"><span data-stu-id="a82f4-271">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="a82f4-272">轉化轉場增強效果 - 表格​​</span><span class="sxs-lookup"><span data-stu-id="a82f4-272">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="a82f4-273">轉場更順暢的表格轉化</span><span class="sxs-lookup"><span data-stu-id="a82f4-273">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a82f4-274">開始使用：</span><span class="sxs-lookup"><span data-stu-id="a82f4-274">Getting Started:</span></span>
<span data-ttu-id="a82f4-275">您使用表格的方式與轉化相同</span><span class="sxs-lookup"><span data-stu-id="a82f4-275">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a82f4-276">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="a82f4-276">Scenarios to Try:</span></span>

- <span data-ttu-id="a82f4-277">在投影片中插入表格</span><span class="sxs-lookup"><span data-stu-id="a82f4-277">Insert a Table in a slide</span></span>
- <span data-ttu-id="a82f4-278">複製投影片</span><span class="sxs-lookup"><span data-stu-id="a82f4-278">Duplicate the slide</span></span>
- <span data-ttu-id="a82f4-279">在複製的投影片上調整大小/變更/移動表格</span><span class="sxs-lookup"><span data-stu-id="a82f4-279">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="a82f4-280">在複製的投影片上套用 [轉化]</span><span class="sxs-lookup"><span data-stu-id="a82f4-280">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="a82f4-281">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher 和 Visio</span><span class="sxs-lookup"><span data-stu-id="a82f4-281">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="a82f4-282">在不同帳戶之間順暢切換</span><span class="sxs-lookup"><span data-stu-id="a82f4-282">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="a82f4-283">全新的帳戶管理員會在同一個地方顯示您所有的工作和個人帳戶，讓您能控制在其間切換。</span><span class="sxs-lookup"><span data-stu-id="a82f4-283">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="a82f4-284">這項更新的經驗能清楚知道您的登入方法，因此您現在不需要先登出或處理複雜的對話方塊就可以切換工作和個人帳戶。</span><span class="sxs-lookup"><span data-stu-id="a82f4-284">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="a82f4-286">可嘗試使用的範例：</span><span class="sxs-lookup"><span data-stu-id="a82f4-286">Scenarios to Try:</span></span>
- <span data-ttu-id="a82f4-287">在不同的帳戶之間切換</span><span class="sxs-lookup"><span data-stu-id="a82f4-287">Switch between accounts</span></span>
- <span data-ttu-id="a82f4-288">新增帳戶 [附註：您可能想要先移至 [檔案] | [帳戶] | [已連線服務]，移除任何已連線至工作帳戶的個人服務或是反向服務]</span><span class="sxs-lookup"><span data-stu-id="a82f4-288">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="a82f4-289">登出帳戶</span><span class="sxs-lookup"><span data-stu-id="a82f4-289">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="a82f4-290">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="a82f4-290">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a82f4-291">Word</span><span class="sxs-lookup"><span data-stu-id="a82f4-291">Word</span></span> 
- <span data-ttu-id="a82f4-292">我們已修正表格和影像的內容預覽問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-292">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="a82f4-293">Excel</span><span class="sxs-lookup"><span data-stu-id="a82f4-293">Excel</span></span>
- <span data-ttu-id="a82f4-294">我們已修正在黑色佈景主題中，自動篩選的搜尋欄位中文字是白色的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-294">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="a82f4-295">我們已修正新 Office 增益集的同意 UI 問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-295">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a82f4-296">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a82f4-296">PowerPoint</span></span>
- <span data-ttu-id="a82f4-297">我們已修正在膝上型電腦或平板電腦上進行投影片簡報時自動延伸顯示的問題。</span><span class="sxs-lookup"><span data-stu-id="a82f4-297">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="a82f4-298">Outlook</span><span class="sxs-lookup"><span data-stu-id="a82f4-298">Outlook</span></span>
- <span data-ttu-id="a82f4-299">我們已修正 [傳送至 OneNote] 按鈕的顯示問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-299">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="a82f4-300">Access</span><span class="sxs-lookup"><span data-stu-id="a82f4-300">Access</span></span>
- <span data-ttu-id="a82f4-301">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-301">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a82f4-302">Project</span><span class="sxs-lookup"><span data-stu-id="a82f4-302">Project</span></span>
- <span data-ttu-id="a82f4-303">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-303">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="a82f4-304">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="a82f4-304">February 11, 2019</span></span>
<span data-ttu-id="a82f4-305">版本 1903 (組建 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="a82f4-305">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="a82f4-306">值得注意的修正：</span><span class="sxs-lookup"><span data-stu-id="a82f4-306">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a82f4-307">Word</span><span class="sxs-lookup"><span data-stu-id="a82f4-307">Word</span></span> 
- <span data-ttu-id="a82f4-308">我們已修正某些自訂樣式無法套用至線上 Word 的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-308">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="a82f4-309">我們已修正 Word 中豐富物件的內容預覽問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-309">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="a82f4-310">我們已修正貼上清單會導致 Word 當機的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-310">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="a82f4-311">Excel</span><span class="sxs-lookup"><span data-stu-id="a82f4-311">Excel</span></span>
- <span data-ttu-id="a82f4-312">我們已修正無貨幣符號時，數字格式後的附加空白不再顯示的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-312">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="a82f4-313">我們已修正自動偵測股票的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-313">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a82f4-314">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a82f4-314">PowerPoint</span></span>
- <span data-ttu-id="a82f4-315">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-315">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a82f4-316">Outlook</span><span class="sxs-lookup"><span data-stu-id="a82f4-316">Outlook</span></span>
- <span data-ttu-id="a82f4-317">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-317">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a82f4-318">Access</span><span class="sxs-lookup"><span data-stu-id="a82f4-318">Access</span></span>
- <span data-ttu-id="a82f4-319">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-319">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a82f4-320">Project</span><span class="sxs-lookup"><span data-stu-id="a82f4-320">Project</span></span>
- <span data-ttu-id="a82f4-321">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-321">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="a82f4-322">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a82f4-322">February 1, 2019</span></span> 
<span data-ttu-id="a82f4-323">版本 1902 (組建 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="a82f4-323">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="a82f4-324">值得注意的修正</span><span class="sxs-lookup"><span data-stu-id="a82f4-324">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="a82f4-325">Word</span><span class="sxs-lookup"><span data-stu-id="a82f4-325">Word</span></span> 
- <span data-ttu-id="a82f4-326">我們已修正內嵌 Excel 表格中調整儲存格大小的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-326">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="a82f4-327">我們已修正繪圖畫布中複製/貼上圖形的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-327">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="a82f4-328">Excel</span><span class="sxs-lookup"><span data-stu-id="a82f4-328">Excel</span></span>
- <span data-ttu-id="a82f4-329">我們已修正從 Excel Web App 開啟檔案的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-329">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="a82f4-330">我們已修正因為檔名大小造成 CSV 檔案儲存為 XLSX 失敗的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-330">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="a82f4-331">我們已修正快顯功能表顯示快顯功能表選項的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-331">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a82f4-332">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a82f4-332">PowerPoint</span></span>
- <span data-ttu-id="a82f4-333">我們已修正使用者無法使用鍵盤快速鍵 ctrl+alt+7/ctrl+alt+8 輸入方括號的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-333">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="a82f4-334">我們已修正將本機影片插入至 PPT 會減少 C 磁碟機磁碟空間的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-334">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="a82f4-335">我們已修正 [發佈至 Microsoft Stream] 按鈕無法向某些使用者顯示的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-335">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="a82f4-336">Outlook</span><span class="sxs-lookup"><span data-stu-id="a82f4-336">Outlook</span></span>
- <span data-ttu-id="a82f4-337">我們已修正行事曆中工作檢視無法正確顯示工作主旨的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-337">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="a82f4-338">Access</span><span class="sxs-lookup"><span data-stu-id="a82f4-338">Access</span></span>
- <span data-ttu-id="a82f4-339">我們已修正圖表的縮放比例的問題</span><span class="sxs-lookup"><span data-stu-id="a82f4-339">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="a82f4-340">Project</span><span class="sxs-lookup"><span data-stu-id="a82f4-340">Project</span></span>
- <span data-ttu-id="a82f4-341">修正多項效能和穩定性</span><span class="sxs-lookup"><span data-stu-id="a82f4-341">Various performance and stability fixes</span></span>
