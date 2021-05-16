# 更新日誌

> 此更新日誌由 [本翻譯專案](https://github.com/goodjack/developer-roadmap-chinese) 提供

此專案的所有顯著更改都將記錄在此文件中。以下版本號皆依 [原著 Commit hash](https://github.com/kamranahmedse/developer-roadmap/commits/master) 為主。

## [`a42d241`](https://github.com/kamranahmedse/developer-roadmap/tree/a42d24142098760b4eba657be8954b0ab0cc31c9) - 2021-01-09

- 更新至 2021 年版本
- 授權條款：此專案改由 CC BY-NC-SA 4.0 釋出
- 介紹
  - 移除「SOLID、KISS、YAGNI」
- 前端
  - 新增全新段落
    - 網際網路
    - VCS
    - 網路安全知識
    - Web 元件
    - GraphQL
  - HTML：新增「表單和驗證」、「慣例和最佳做法」
  - CSS：新增「回應式設計」
  - CSS 架構：已不推薦 OOCSS 和 SMACSS
  - 任務執行器：已不推薦 Gulp
  - 格式化工具：已不推薦 StandardJS，並移除 JSHint 與 JSLint
  - 模組打包工具：更改推薦順序為 Webpack > Rollup > Parcel
  - React.js：優先推薦使用 Redux
  - 現代 CSS：從 CSS in JS 段落更名而來，新增 Styled JSX 作為替代選項，已不推薦 Radium 和 Glamorous
  - CSS 框架：新增一些以 JS component 為基礎的框架，移除 Semantic UI
  - 測試工具：新增 react-testing-library，已不推薦 Mocha、Chai、Ava、Jasmine，移除 Karma 和 Protractor
  - 類型檢查工具：已不推薦 Flow
  - SSR：已不推薦 After.js
  - SSG：新增多個工具，並新增推薦 Next.js
  - 手機應用程式：新增 Flutter 和 Ionic
  - 桌面應用程式：已不推薦 Carlo 和 Proton Native
  - WASM：更新敘述
- 後端
  - 舊有的文字敘述方式已經替換成全新的樹狀地圖
  - 新增段落
    - 網際網路
    - 基礎的前端知識
    - 網路安全知識
    - 作業系統和基本知識，包含 POSIX 的基礎知識、基礎的終端機指令等內容
    - 版本控制系統
    - 倉儲代管服務
    - 更多關於資料庫，如 ORM、ACID、交易、N+1、正規化、索引
    - CI/CD
    - 設計和開發原則
    - 架構模式
    - GraphQL 改為段落
    - 圖形資料庫改為段落
    - 規模化建設
  - 程式語言段落：推薦 JavaScript，其他語言為替代選項，移除函數程式語言
  - 關聯式資料庫：原本優先推薦 MySQL，現在推薦 PostgreSQL，MySQL 與 MariaDB 改為替代選項
  - NoSQL 資料庫：增加分類，並更新推薦與替代選項
  - 擴充 API 段落：REST、JSON、SOAP、gRPC、HATEOAS、OpenAPI 規範
  - API 認證段落：OpenID 改為替代選想，加入 Cookie Based 和 SAML 兩個替代選項
  - 搜尋引擎：Solr 改為替代選項，移除 Sphinx
  - 網頁伺服器：Apache 改為替代選項
- DevOps
  - 新增段落
    - Linux 改為段落
    - Unix 改為段落
    - 終端機多工器
    - 服務網格
    - 雲端設計模式
  - 學習程式語言：將 C 與 C++ 分開條列
  - 瞭解不同的作業系統概念：新增 POSIX 的基礎知識、網路概念、init.d、systemd
  - 終端機：網路工具新增 netstat
  - 網路與安全：擴充為「網路、安全與協定」，新增 SSH、Port Forwarding，以及新增 email 子段落
  - 網頁伺服器：Apache 改為替代選項
  - 容器：移除 rkt
  - 基礎建設佈建：新增 Pulumi 為替代選項
  - 學習一些 CI/CD 工具：TeamCity 改為替代選項，移除 Drone，推薦 Gitlab CI、GitHub Actions，新增替代選項 Bamboo、Azure DevOps Services
  - 基礎建設監控：新增推薦 Prometheus、Grafana，移除 Icinga
  - 應用程式監控：新增推薦 Jaeger，New Relic 改為推薦，新增 Instana、OpenTracing 為替代選項
  - 日誌管理：ELK Stack 更新為 Elastic Stack，並推薦使用
  - 雲端供應商：新增 Linode、Vultr 為替代選項，不推薦阿里雲

## [`347831f`](https://github.com/kamranahmedse/developer-roadmap/tree/347831feaed227f42525e829ccc8d84a22386952) - 2020-01-04

- 更新官網徽章按鈕

## [`dacbf09`](https://github.com/kamranahmedse/developer-roadmap/tree/dacbf09f5529ef46ef652b88b5076dcc15067672) - 2019-07-10

- 前端：移除已整併至 ESLint 的 JSCS，並新增 StandardJS
- 後端：Go 語言正名
- 修正 GitHub 贊助
- （中文翻譯）將原著 JSON 檔格式化，以方便追蹤變更

## [`796bde7`](https://github.com/kamranahmedse/developer-roadmap/tree/796bde76c96759b9d23892d30d2dbd8b55892aac) - 2019-07-01

- 新增 GitHub 贊助功能
- Readme 更新總結段落，移除贊助段落

## [`2312fdd`](https://github.com/kamranahmedse/developer-roadmap/tree/2312fdd608feb5c660645d02058200ccbfbbf4c6) - 2019-05-17

- Readme 更新：更換封面圖片、新增 roadmap.sh 網站
- 前端修正：Hoisting 拼寫
- DevOps 修正：TeamCity 拼寫
- 更新 Sponsored By 段落
- 更換授權條款
- （中文翻譯）CSS in JS 改用原文

## [`3fd5b9e`](https://github.com/kamranahmedse/developer-roadmap/tree/3fd5b9e7448d5a1eafffd380141e5dc2fedb2e50) - 2019-02-06

- 更新 Sponsored By 段落

## [`edff915`](https://github.com/kamranahmedse/developer-roadmap/tree/edff9156ff6820bdf29db11381cab590429122a5) - 2019-02-05

- 更新 Sponsored By 段落

## [`abaa839`](https://github.com/kamranahmedse/developer-roadmap/tree/abaa839b26d6bfb02208ad63e25186b558c1bdc4) - 2019-01-26

- 取消後端路線圖的透明背景

## [`08303c0`](https://github.com/kamranahmedse/developer-roadmap/tree/08303c062316bd3c903dcbd4d38cf31ca1b705bc) - 2019-01-01

- 2019 年新版路線圖
- 介紹改版：
  - 新增 SOLID、KISS、YAGNI
  - 新增授權條款
  - 新增語意化版本
- 前端改版：
  - 伺服器端渲染推薦 React.js
  - 擴充測試段落並推薦 Jest、Enzyme、Cypress
  - 新增 Web API、JS 中的 CSS、靜態網站產生器、桌面及手機應用程式、Web Assembly 等段落。

## [`67a72aa`](https://github.com/kamranahmedse/developer-roadmap/commit/67a72aab113e79c11e292ada394606f079f6a263) - 2018-11-29

- 新增 DevOps 容器協作，並推薦 Kubernetes。
