# 個人網站改善清單

本文件記錄規劃中的視覺與內容修改項目及實作狀態。內容文字與研究資料需由網站作者確認後再實作。

狀態標記：`待選擇`、`進行中`、`已完成`、`不採用`。

## A. 整體版面

- **A1｜改用現代版面結構** — `已完成`
  - 使用語意化 HTML 與 CSS Grid/Flexbox 取代 table layout。
- **A2｜加寬主要內容區** — `已完成`
  - 將主要內容最大寬度由 800px 調整至約 1000px。
- **A3｜建立一致的頁面留白** — `已完成`
  - 統一區塊、論文項目與頁面左右間距。
- **A4｜加入淡色背景與內容容器** — `待選擇`
- **A5｜加寬 Publications、收窄 Bio 文字區** — `已完成`
  - Publications 使用較寬的展示區；個人介紹與 Research 維持較短、易讀的行長。

## B. 頁首／個人資訊區

- **B1｜重新設計 Hero 區** — `待選擇`
- **B2｜美化個人照片** — `待選擇`
- **B3｜將 Email／CV／Scholar／GitHub 改成按鈕或 icon links** — `待選擇`
- **B4｜加入頂部導覽列** — `待選擇`
- **B5｜Sticky 導覽列** — `待選擇`

## C. 論文列表

- **C1｜論文卡片化** — `待選擇`
- **C2｜統一論文縮圖尺寸** — `已完成`
- **C3｜改善標題與作者層級** — `已完成`
- **C4｜Venue badge** — `待選擇`
- **C5｜美化 Paper／Project／Poster 連結** — `已完成`
- **C6｜作者姓名強調樣式** — `待選擇`
- **C7｜論文 hover 效果** — `待選擇`
- **C8｜交錯式論文版面** — `待選擇`
- **C9｜在 Publications 之間加入分隔線** — `已完成`

## D. 字體與配色

- **D1｜提升基礎字級與行距** — `已完成`
- **D2｜更新字體配置** — `待選擇`
- **D3｜建立一致的主題色** — `已完成`
- **D4｜改善標題系統** — `已完成`
- **D5｜加入深色模式** — `待選擇`

## E. 行動版

- **E1｜完整 responsive layout** — `已完成`
- **E2｜手機版導覽選單** — `待選擇`
- **E3｜調整手機觸控區域** — `已完成`
- **E4｜手機版縮短視覺留白** — `已完成`

## F. 細節與質感

- **F1｜正式 favicon** — `待選擇`
- **F2｜區塊分隔線或小標記** — `待選擇`
- **F3｜平滑錨點捲動** — `已完成`
- **F4｜統一 focus／hover 狀態** — `已完成`
- **F5｜輕量進場動畫** — `待選擇`
- **F6｜頁尾重新設計** — `待選擇`

## G. 圖片與載入體驗

- **G1｜圖片轉成 WebP** — `待選擇`
- **G2｜圖片 lazy loading** — `已完成`
- **G3｜避免圖片載入時版面跳動** — `已完成`

## H. 個人定位與首頁介紹

- **H1｜更新目前身份與所屬單位** — `已完成`
  - 說明目前職稱、任職或研究單位，以及 Ph.D. 畢業年份。
  - 移除容易過期的 `fresh Ph.D. graduate` 表述。
- **H2｜說明目前的機會與合作狀態** — `待選擇`
  - 視實際需求標示是否尋找職缺、研究合作、訪問或其他機會。
- **H3｜重寫一句式研究定位** — `已完成`
  - 聚焦 reinforcement learning、imitation learning、human feedback、imperfect demonstrations 與 generative models 等核心主軸。
- **H4｜串連近期 RL／diffusion 與早期 computer vision 研究** — `已完成`
  - 用第二句或短段落說明研究方向的延續性，避免研究興趣看起來彼此分散。
- **H5｜加入中文姓名或 preferred name 資訊** — `待選擇`
  - 可選擇加入中文姓名、姓名發音或慣用稱呼。

## I. News 與近況

- **I1｜新增 News／Recent Updates 區塊** — `已完成`
  - 首頁顯示最近 4–6 筆重要動態。
- **I2｜加入論文接受與發布消息** — `已完成`
- **I3｜加入畢業、任職或職涯消息** — `已完成`
- **I4｜加入演講、conference、tutorial 或程式碼發布消息** — `待選擇`
- **I5｜建立 News 日期與文字格式** — `已完成`
  - 建議使用 `YYYY.MM` 加一行簡短敘述，並連結相關頁面。

## J. 經歷與教育

- **J1｜新增 Experience 區塊** — `不採用`
  - 以時間軸列出研究與業界經歷。
- **J2｜補充 Chunghwa Telecom Laboratories 合作資訊** — `待選擇`
  - 說明年份、角色、研究主題及相關成果。
- **J3｜補充 Inventec AI Center 實習資訊** — `已完成`
  - 說明年份、職稱、團隊或研究主題。
- **J4｜將經歷連結至相關 publication 或 project** — `待選擇`
- **J5｜新增 Education 區塊** — `不採用`
  - 列出學位、正式系所名稱、學校及年份。
- **J6｜補充 Ph.D. 指導教授與論文題目** — `不採用`
  - 論文題目為可選資訊。
- **J7｜確認 bachelor’s degree 的正式英文系名** — `已完成`
  - 確認應使用 Electronic Engineering、Electrical Engineering 或其他正式名稱。

## K. Research 內容

- **K1｜重寫 Research 簡介** — `已完成`
  - 避免 `utilizing machine learning techniques to solve application problems` 等過於泛用的描述。
- **K2｜整理 2–4 個具體研究主題** — `待選擇`
  - 例如 learning from human feedback、imitation learning from imperfect demonstrations、diffusion models for policy learning、robust visual representation learning。
- **K3｜為每個研究主題補一行研究問題** — `待選擇`
  - 說明想解決的問題，而不只列出演算法名稱。

## L. Publications 內容

- **L1｜解釋作者符號** — `已完成`
  - 加入 `* Equal contribution.`、`† Equal advising.` 等實際適用的說明。
- **L2｜統一並標示 publication status** — `不採用`
  - 區分 conference paper、journal paper、preprint 與 workshop paper。
- **L3｜將 venue 簡化為縮寫與年份** — `不採用`
  - 不只顯示 `ICLR 2025` 等縮寫；保留完整會議名稱、縮寫與年份。
- **L4｜統一 Paper／Project／Code／BibTeX／DOI 連結** — `待選擇`
  - 僅顯示實際存在的資源。
- **L5｜將每篇長摘要縮成 1–2 句** — `待選擇`
  - 聚焦研究問題、核心方法與主要結果。
- **L6｜補充個人在代表作中的貢獻** — `待選擇`
  - 適合求職或希望凸顯研究能力時使用。
- **L7｜區分 Selected Publications 與完整論文列表** — `待選擇`
  - 首頁突出近期或代表性成果，其餘可精簡列出或連至 Google Scholar。

## M. 其他可選內容

- **M1｜Awards and Honors** — `已完成`
  - 獎學金、best paper、競賽成果或其他具體榮譽。
- **M2｜Talks and Tutorials** — `待選擇`
  - Invited talks、conference talks、tutorials 或公開投影片。
- **M3｜Teaching** — `待選擇`
  - 課程、TA 經驗、講義或教學資源。
- **M4｜Academic Service** — `待選擇`
  - Reviewer、workshop organizer 或其他服務。
- **M5｜Open-source Projects** — `待選擇`
  - 不適合放入 publications、但值得展示的程式或工具。
- **M6｜Media and Press** — `待選擇`
  - 研究報導、訪談或外部介紹。
- **M7｜Personal Interests** — `待選擇`
  - 以一至兩句增加個人感，不影響研究資訊主體。
- **M8｜補充 ORCID／LinkedIn 等連結** — `待選擇`
  - 僅加入有持續維護的個人頁面。
- **M9｜標示 CV 與網站最後更新日期** — `已完成`

## 實作紀錄

- 2026-07-21：完成 A1、A2、A3；修改前版本備份於 `backups/2026-07-21-before-layout/`。
- 2026-07-23：完成 D1、D3、D4、E1、E3、E4；建立字級與色彩系統，並完成平板、手機與小型手機版面調整。
- 2026-07-23：新增 H–M 內容改善建議；尚未修改網站內容。
- 2026-07-23：移除原 L4 並重新編號 L 項目；完成 L2、L3，統一現有論文的 publication status、venue 縮寫與年份格式。
- 2026-07-23：依回饋撤回 L2、L3，恢復完整會議名稱與原本年份格式；L2、L3 標記為不採用。
- 2026-07-23：參考 Shao-Hua Sun 網站重整 Publications 格式；完成 C3、C5，採用標題、作者、完整 venue、摘要、資源連結的固定順序。
- 2026-07-23：完成 C9，在相鄰 Publications 之間加入低對比度分隔線，並平衡分隔線上下留白。
- 2026-07-23：完成 A5，參考 Shao-Hua Sun 網站的寬窄比例，加寬 Publications 並限制 Bio／Research 的閱讀行長。
- 2026-08-06：依最新 CV 更新全站內容：改寫 Bio（移除 fresh Ph.D. graduate，補 Spuree／Sony AI 經歷）與 Research 簡介；新增 News、Experience、Education 區塊與 Best Ph.D. Thesis Award；補上 TNNLS 2025 與 ICIP 2019 兩篇論文（TNNLS 縮圖為自製 SVG 示意圖 img/noisy_demo.svg）；Email 改為 sam.sfchen@gmail.com；學士學位改為 Electrical Engineering。完成 C2（縮圖統一 4:3 contain）、F3、F4、G2、G3、L1（* / † 註解）、M9（頁尾更新日期）。
- 2026-08-06：依回饋移除 Experience、Education 區塊與 Github 連結（J1、J5、J6 改為不採用）；Sony AI／Inventec／Spuree 經歷僅保留在 Bio 敘述中。
