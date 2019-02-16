---
<span data-ttu-id="f2958-101">標題："Release Notes for Office 的內部"ms.author: andrewmo 作者： mikho manager: andrewmo ms.date: 2/15/2019 ms.audience： Win32 Fast ms.topic： 參照 ms.service: o365 proplus localization_priority： 重要 ms.collection: RelNotes_ProPlus描述："提供內部人員 Fast 對象的主要新功能、 修正或已知的問題的最新清單</span><span class="sxs-lookup"><span data-stu-id="f2958-101">title: "Release Notes for Office Insiders" ms.author: andrewmo author: mikho manager: andrewmo ms.date: 2/15/2019 ms.audience: Win32 Fast ms.topic: reference ms.service: o365-proplus- localization_priority: Critical ms.collection: RelNotes_ProPlus description: "Provides Insiders Fast audience with the latest list of key new features, fixes or known issues</span></span>
---

# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="f2958-102">Office 的內部的版本資訊</span><span class="sxs-lookup"><span data-stu-id="f2958-102">Release Notes for Office Insiders</span></span>

<span data-ttu-id="f2958-p101">本文包含 Word、 Excel、 PowerPoint、 Outlook、 存取及 Project 的 Windows 桌面的內部組建版本的資訊。每週，我們將反白顯示有趣的新功能、 重要的修正程式與我們想了解您的所有重大問題。請注意我們通常導入功能 （和有時偶數修正） 內部人員在一段時間。這可讓我們以確保事項順暢運作之前釋放較多對象功能。因此，如果您沒有看到如下所述的某個項目，請不要擔心您將取得其最後。</span><span class="sxs-lookup"><span data-stu-id="f2958-p101">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

## <a name="february-12-2019-version-1902-build-1133020014"></a><span data-ttu-id="f2958-108">2 月 12 2019年版本 1902 （組建 11330.20014）</span><span class="sxs-lookup"><span data-stu-id="f2958-108">February 12 2019 Version 1902 (build 11330.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2958-109">新功能：</span><span class="sxs-lookup"><span data-stu-id="f2958-109">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2958-110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2958-110">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="f2958-111">形狀變形轉換增強功能-Morph 依名稱</span><span class="sxs-lookup"><span data-stu-id="f2958-111">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="f2958-112">指定您想要形狀變形的圖形</span><span class="sxs-lookup"><span data-stu-id="f2958-112">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2958-113">快速入門]：</span><span class="sxs-lookup"><span data-stu-id="f2958-113">Getting Started:</span></span>

- <span data-ttu-id="f2958-114">若要取得 Morph 至兩個物件視為相同的物件，使用者可以重新命名使用 [選取項目] 窗格中的圖形。</span><span class="sxs-lookup"><span data-stu-id="f2958-114">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="f2958-p102">名稱與的開頭必須是"！"（兩個驚嘆號） Morph 加以運用以覆寫比對行為，例如我們預設值為"！名稱"</span><span class="sxs-lookup"><span data-stu-id="f2958-p102">The name must be prefaced with “!!” (two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="f2958-p103">使用者仍可繼續重新命名圖形不會開始使用任何名稱"！"而不用它會變更 Morph 運作的方式</span><span class="sxs-lookup"><span data-stu-id="f2958-p103">Users can continue to rename shapes with any name that doesn’t start with “!!” without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2958-119">若要嘗試案例：</span><span class="sxs-lookup"><span data-stu-id="f2958-119">Scenarios to Try:</span></span>

- <span data-ttu-id="f2958-120">將圖形插入一張投影片、 假設矩形</span><span class="sxs-lookup"><span data-stu-id="f2958-120">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="f2958-121">建立新的投影片</span><span class="sxs-lookup"><span data-stu-id="f2958-121">Create a new slide</span></span>
- <span data-ttu-id="f2958-122">將不同的圖案插入 2nd 投影片、 假設三角形</span><span class="sxs-lookup"><span data-stu-id="f2958-122">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="f2958-123">開啟 SelectionPane、 重新命名之矩形中投影片 1 至"！圖案"，並重新命名張投影片 2 至三角形"！圖形"</span><span class="sxs-lookup"><span data-stu-id="f2958-123">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="f2958-124">套用 Morph 2nd 投影片上</span><span class="sxs-lookup"><span data-stu-id="f2958-124">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="f2958-125">形狀變形轉換增強功能-SmartArt</span><span class="sxs-lookup"><span data-stu-id="f2958-125">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="f2958-126">SmartArt morph 搭配平順切換效果</span><span class="sxs-lookup"><span data-stu-id="f2958-126">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2958-127">快速入門]：</span><span class="sxs-lookup"><span data-stu-id="f2958-127">Getting Started:</span></span>

<span data-ttu-id="f2958-128">使用 Morph SmartArt 具有相同的方式</span><span class="sxs-lookup"><span data-stu-id="f2958-128">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2958-129">若要嘗試案例：</span><span class="sxs-lookup"><span data-stu-id="f2958-129">Scenarios to Try:</span></span>

- <span data-ttu-id="f2958-130">將 SmartArt 插入一張投影片</span><span class="sxs-lookup"><span data-stu-id="f2958-130">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="f2958-131">重複的投影片</span><span class="sxs-lookup"><span data-stu-id="f2958-131">Duplicate the Slide</span></span>
- <span data-ttu-id="f2958-132">調整大小/變更/移動重複的投影片上 SmartArt</span><span class="sxs-lookup"><span data-stu-id="f2958-132">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="f2958-133">重複的投影片上套用 Morph</span><span class="sxs-lookup"><span data-stu-id="f2958-133">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="f2958-134">形狀變形轉換增強功能-表格</span><span class="sxs-lookup"><span data-stu-id="f2958-134">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="f2958-135">搭配平順切換的資料表 morph</span><span class="sxs-lookup"><span data-stu-id="f2958-135">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2958-136">快速入門]：</span><span class="sxs-lookup"><span data-stu-id="f2958-136">Getting Started:</span></span>
<span data-ttu-id="f2958-137">使用 Morph 與資料表相同的方式</span><span class="sxs-lookup"><span data-stu-id="f2958-137">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2958-138">若要嘗試案例：</span><span class="sxs-lookup"><span data-stu-id="f2958-138">Scenarios to Try:</span></span>

- <span data-ttu-id="f2958-139">一張投影片插入表格</span><span class="sxs-lookup"><span data-stu-id="f2958-139">Insert a Table in a slide</span></span>
- <span data-ttu-id="f2958-140">重複的投影片</span><span class="sxs-lookup"><span data-stu-id="f2958-140">Duplicate the slide</span></span>
- <span data-ttu-id="f2958-141">調整大小/變更/移動重複的投影片上的表格</span><span class="sxs-lookup"><span data-stu-id="f2958-141">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="f2958-142">重複的投影片上套用 Morph</span><span class="sxs-lookup"><span data-stu-id="f2958-142">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="f2958-143">Word、 Excel、 PowerPoint、 OneNote、 存取、 Project、 Publisher & Visio</span><span class="sxs-lookup"><span data-stu-id="f2958-143">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="f2958-144">順暢地帳戶之間的切換參數</span><span class="sxs-lookup"><span data-stu-id="f2958-144">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="f2958-p104">新帳號管理員集中一處會顯示所有的工作以及個人帳戶與您處於兩者之間切換的控制項。此更新的經驗建立清楚指定如何您的登入，並且現在您可以切換工時和個人帳戶不必先登出或處理複雜的對話方塊。</span><span class="sxs-lookup"><span data-stu-id="f2958-p104">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them. This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>



#### <a name="scenarios-to-try"></a><span data-ttu-id="f2958-147">若要嘗試案例：</span><span class="sxs-lookup"><span data-stu-id="f2958-147">Scenarios to Try:</span></span>
- <span data-ttu-id="f2958-148">在帳戶之間切換</span><span class="sxs-lookup"><span data-stu-id="f2958-148">Switch between accounts</span></span>
- <span data-ttu-id="f2958-149">新增帳戶 [附註： 您可能會想要先移至 [檔案 |帳戶 |連線服務並移除任何個人服務連線至搭配使用的帳戶或相反方向]</span><span class="sxs-lookup"><span data-stu-id="f2958-149">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="f2958-150">登出帳戶</span><span class="sxs-lookup"><span data-stu-id="f2958-150">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="f2958-151">值得注意的修正程式：</span><span class="sxs-lookup"><span data-stu-id="f2958-151">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2958-152">Word</span><span class="sxs-lookup"><span data-stu-id="f2958-152">Word</span></span> 
- <span data-ttu-id="f2958-153">我們使用表格 & 影像的快顯 preview 修正問題</span><span class="sxs-lookup"><span data-stu-id="f2958-153">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="f2958-154">Excel</span><span class="sxs-lookup"><span data-stu-id="f2958-154">Excel</span></span>
- <span data-ttu-id="f2958-155">我們修正問題其中 autofilter 搜尋欄位中的文字是白色在黑色的佈景主題</span><span class="sxs-lookup"><span data-stu-id="f2958-155">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="f2958-156">我們固定同意 UI 問題與新版 Office 增益集</span><span class="sxs-lookup"><span data-stu-id="f2958-156">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2958-157">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2958-157">PowerPoint</span></span>
- <span data-ttu-id="f2958-158">我們使用簡報投影片上的筆記型電腦或平板電腦時自動擴充顯示修正問題。</span><span class="sxs-lookup"><span data-stu-id="f2958-158">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="f2958-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2958-159">Outlook</span></span>
- <span data-ttu-id="f2958-160">我們使用 [傳送至 OneNote 按鈕顯示修正問題</span><span class="sxs-lookup"><span data-stu-id="f2958-160">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="f2958-161">存取</span><span class="sxs-lookup"><span data-stu-id="f2958-161">Access</span></span>
- <span data-ttu-id="f2958-162">各種效能和穩定性修正項目</span><span class="sxs-lookup"><span data-stu-id="f2958-162">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2958-163">Project</span><span class="sxs-lookup"><span data-stu-id="f2958-163">Project</span></span>
- <span data-ttu-id="f2958-164">各種效能和穩定性修正項目</span><span class="sxs-lookup"><span data-stu-id="f2958-164">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-9-2019-version-1902-build-1133020014"></a><span data-ttu-id="f2958-165">2 月 9 2019年版本 1902 （組建 11330.20014）</span><span class="sxs-lookup"><span data-stu-id="f2958-165">February 9 2019 Version 1902 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="f2958-166">值得注意的修正程式：</span><span class="sxs-lookup"><span data-stu-id="f2958-166">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2958-167">Word</span><span class="sxs-lookup"><span data-stu-id="f2958-167">Word</span></span> 
- <span data-ttu-id="f2958-168">我們修正問題其中一些自訂的樣式無法套用到 word online</span><span class="sxs-lookup"><span data-stu-id="f2958-168">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="f2958-169">我們在 Word 中的豐富型物件固定快顯預覽問題</span><span class="sxs-lookup"><span data-stu-id="f2958-169">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="f2958-170">我們修正問題其中貼上清單會導致 Word 損毀</span><span class="sxs-lookup"><span data-stu-id="f2958-170">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="f2958-171">Excel</span><span class="sxs-lookup"><span data-stu-id="f2958-171">Excel</span></span>
- <span data-ttu-id="f2958-172">我們修正問題其中附加的空格之後數字格式不再顯示時有無貨幣符號</span><span class="sxs-lookup"><span data-stu-id="f2958-172">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="f2958-173">我們使用自動修正問題的股票偵測</span><span class="sxs-lookup"><span data-stu-id="f2958-173">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2958-174">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2958-174">PowerPoint</span></span>
- <span data-ttu-id="f2958-175">各種效能和穩定性修正項目</span><span class="sxs-lookup"><span data-stu-id="f2958-175">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="f2958-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2958-176">Outlook</span></span>
- <span data-ttu-id="f2958-177">各種效能和穩定性修正項目</span><span class="sxs-lookup"><span data-stu-id="f2958-177">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="f2958-178">存取</span><span class="sxs-lookup"><span data-stu-id="f2958-178">Access</span></span>
- <span data-ttu-id="f2958-179">各種效能和穩定性修正項目</span><span class="sxs-lookup"><span data-stu-id="f2958-179">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2958-180">Project</span><span class="sxs-lookup"><span data-stu-id="f2958-180">Project</span></span>
- <span data-ttu-id="f2958-181">各種效能和穩定性修正項目</span><span class="sxs-lookup"><span data-stu-id="f2958-181">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="january-30-2019-version-1902-build-1132620000"></a><span data-ttu-id="f2958-182">2019 年 1 月 30，版本 1902 （組建 11326.20000）</span><span class="sxs-lookup"><span data-stu-id="f2958-182">January 30, 2019 Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="f2958-183">值得注意的修正程式</span><span class="sxs-lookup"><span data-stu-id="f2958-183">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="f2958-184">Word</span><span class="sxs-lookup"><span data-stu-id="f2958-184">Word</span></span> 
- <span data-ttu-id="f2958-185">我們以調整大小的儲存格內嵌 Excel 表格中修正的問題</span><span class="sxs-lookup"><span data-stu-id="f2958-185">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="f2958-186">我們使用繪圖畫布中之圖案的複製/貼上修正問題</span><span class="sxs-lookup"><span data-stu-id="f2958-186">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="f2958-187">Excel</span><span class="sxs-lookup"><span data-stu-id="f2958-187">Excel</span></span>
- <span data-ttu-id="f2958-188">我們使用從 Excel Web app 開啟檔案修正問題</span><span class="sxs-lookup"><span data-stu-id="f2958-188">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="f2958-189">我們修正問題其中儲存為 CSV 檔案。由於檔案名稱大小已失敗的 XLSX</span><span class="sxs-lookup"><span data-stu-id="f2958-189">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="f2958-190">我們固定顯示快顯功能表選項的快顯功能表</span><span class="sxs-lookup"><span data-stu-id="f2958-190">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2958-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2958-191">PowerPoint</span></span>
- <span data-ttu-id="f2958-192">我們固定發出其中使用者已無法使用鍵盤快速鍵 ctrl + alt + 7/ctrl + alt + 8 輸入方括弧</span><span class="sxs-lookup"><span data-stu-id="f2958-192">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="f2958-193">我們修正問題本機視訊插入 PPT 嗎其中減少 'C' 磁碟磁碟空間</span><span class="sxs-lookup"><span data-stu-id="f2958-193">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="f2958-194">我們固定 [發佈到這不會顯示一些使用者至 Microsoft 資料流] 按鈕</span><span class="sxs-lookup"><span data-stu-id="f2958-194">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="f2958-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2958-195">Outlook</span></span>
- <span data-ttu-id="f2958-196">我們修正問題其中行事曆中任務檢視已無法正確顯示任務之主旨</span><span class="sxs-lookup"><span data-stu-id="f2958-196">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="f2958-197">存取</span><span class="sxs-lookup"><span data-stu-id="f2958-197">Access</span></span>
- <span data-ttu-id="f2958-198">我們固定的縮放比例問題的圖表</span><span class="sxs-lookup"><span data-stu-id="f2958-198">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="f2958-199">Project</span><span class="sxs-lookup"><span data-stu-id="f2958-199">Project</span></span>
- <span data-ttu-id="f2958-200">各種效能和穩定性修正項目</span><span class="sxs-lookup"><span data-stu-id="f2958-200">Various performance and stability fixes</span></span>
