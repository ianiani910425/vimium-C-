# vimium-C-

```
unmapAll

" 滾動視窗
map h scrollLeft        " 向左滾動
map j scrollDown        " 向下滾動
map k scrollUp          " 向上滾動
map l scrollRight       " 向右滾動
map gg scrollToTop      " 滾動到頂部
map G scrollToBottom    " 滾動到底部

map u scrollPageDown    " 向下滾動一頁
map r scrollPageUp      " 向上滾動一頁

" 瀏覽歷史
map H goBack            " 返回上一頁
map L goForward         " 前進到下一頁

" 開啟新的頁籤
map gu goToRoot         " 返回網站根目錄
map f LinkHints.activate " 激活連結提示
map x removeTab         " 關閉當前頁籤
map X restoreTab        " 恢復最近關閉的頁籤

" 頁籤操作
map q previousTab       " 切換到前一個頁籤
map e nextTab           " 切換到下一個頁籤

map t createTab         " 創建新頁籤
map yy copyCurrentUrl   " 複製當前頁面的 URL
map p openCopiedUrlInCurrentTab " 在當前頁籤中開啟已複製的 URL
map P openCopiedUrlInNewTab     " 在新頁籤中開啟已複製的 URL
map yf LinkHints.activateCopyLinkUrl " 激活連結提示並複製 URL

" 各種面板
map o Vomnibar.activateInNewTab " 在新頁籤中激活 Vomnibar
map O Vomnibar.activate         " 激活 Vomnibar

" 可視模式
map v enterVisualMode     " 進入可視模式
map V enterVisualLineMode " 進入行可視模式

map ? showHelp " 顯示幫助

```