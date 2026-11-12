# 教學，與 AI 同行：教師指引導讀網站

本下載包包含最新版完整靜態網站：師生 AI 素養框架、原書圖表、教學六步驟、課堂示例、測驗、行動筆記與文字大小調整功能。

不需要安裝套件、不需要建置，也不需要 API 金鑰。

## 放到 GitHub Pages

1. 登入 GitHub，建立一個 repository，例如 `teacher-ai-guide`。若要使用一般免費帳號的 GitHub Pages，請選 Public。
2. 將 ZIP 解壓縮。
3. 在 repository 頁面選 **Add file → Upload files**，上傳解壓縮後的所有檔案與 `assets` 資料夾。也可使用 GitHub Desktop 或 Git。
4. 確認 `index.html` 位於 repository 最外層；不要只上傳 ZIP，也不要再多包一層資料夾。按 **Commit changes**。
5. 開啟 **Settings → Pages**。
6. 在 **Build and deployment → Source** 選 **Deploy from a branch**。
7. Branch 選 `main`（若你的預設分支不同，請選實際分支），資料夾選 **/ (root)**，按 **Save**。
8. 等待 GitHub 部署完成。回到 Pages 頁面按 **Visit site**，即可取得網站網址。

網址通常為 `https://你的帳號.github.io/teacher-ai-guide/`，請以 GitHub Pages 顯示的實際網址為準。

## 檔案位置

- `index.html`：主要網頁與靜態教學內容。
- `style.css`：桌面、手機、列印版面與預設大字體。
- `app.js`：框架切換、圖片放大、測驗、筆記下載與 A−／A＋／重設按鈕。
- `framework-data.js`：教師與學生框架目標、內涵與補充例子。
- `assets/`：原書 PDF 與網頁使用的圖像；請整個資料夾保留。
- `.nojekyll`：讓 GitHub Pages 直接提供靜態檔案。

所有網站資源使用相對路徑，支援 GitHub Pages 的 repository 子路徑。

## 閱讀功能

- 正文預設約 20px，文字大小可調整為預設的 80%～150%。
- 同一瀏覽器會在本機記住文字大小。行動筆記不會自動保存，請按下載備份。
- PDF 與原書圖像的文字屬於原檔內容，請使用圖表放大或 PDF 閱讀器的縮放功能。
- 若瀏覽器不允許複製，網站會選取文字，讓使用者自行複製。

## 後續修改

修改對應檔案後，再上傳到同一個 repository。GitHub Pages 會自動重新部署。若仍看到舊版，請重新整理或清除瀏覽器快取。

## 內容與來源

依使用者提供的兩份文件製作：

1. 《115年中小學教師數位與AI教學指引》（文件標示2026年9月）。
2. 《臺灣中小學教師與學生AI素養框架》（文件標示2026年3月）。

本網站為導讀整理，非教育部官方網站。框架原文、原書圖像與補充案例在頁面中分別標示。原文件與圖像的權利仍依原著作權人及其授權規範；本下載包未另行賦予其授權。

本包不含 Sites 託管設定、存取金鑰、Git 歷史或開發環境檔案。原網站的私人存取設定不會隨檔案移轉；GitHub Pages 的瀏覽權限依 GitHub 方案及設定而定。
