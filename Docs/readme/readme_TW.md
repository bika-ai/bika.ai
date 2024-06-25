<p align="center">
    <a href="https://bika.ai" target="_blank">
        <img src="/home/coder/_work/bika.ai/Docs/static/bika-cover.png" alt="bika封面图像" />
    </a>
</p>

<p align="center">
  <a href="README.md">English</a>
  | 
<a href="Docs/readme/readme_ZH.md">简体中文</a>
  | 
 繁體中文
  | 
   <a href="Docs/readme/readme_ja.md">日本語</a>
</p>

# 什麼是Bika.ai？ - 自驅協作型AI自動化平台入門指南 

> 本文是自驅協作型AI自動化平台[Bika.ai](https://bika.ai) 的入門指南
>
> [Bika.ai](https://bika.ai) 是一個AI自動化應用搭建工具，每日定時主動幫助每個人完成工作、流程匯報、數據收集。
>
> 釋放您的工作時間，擺脫繁瑣的工作，真正讓您有更多的時間享受生活。

## Bika.ai是什麼？

傳統的AI工具中，你需要主動跟AI對話，讓AI幫助你完成工作。

而Bika.ai是一個AI主動進行提醒和向人們發起任務的協作式AI自動化平台，你不需要跟AI對話，而是AI定時自動化幫助你或你的團隊，完成一些工作。

<p align="center">
    <a href="https://bika.ai/auth?redirect=%2Fspace" target="_blank">
        <img src="/home/coder/_work/bika.ai/Docs/static/blog-cta.zh-TW.png" alt="bika-cta" />
    </a>
</p>

<br />

BBika.ai提供了:

- **智能任務**: AI主動地自動創建任務、自動分配、自動判斷完成，無需人工催促，如每日記帳、每日日記、團隊任務、晨會填寫、季度OKR復盤

- **AI報告**: AI根據您的活動或任務生成報告，如每週日記總結、收支分析、銷售週報、出勤統計等；

- **數據可視化**: AI自動化生成任務，委派人們收集數據，生成的多維表格支持億級數據行，並能根據您的數據生成圖表，如銷售額、客戶增長、團隊績效、人口普查等；

- **智能提醒**: 貼心提醒您記得每一個紀念日和重要事件，如朋友生日、客戶送禮、銷售拜訪、績效追蹤

- **語音錄入**: 與 Bika 對話，能將您的語音轉換為結構化的數據，如靈感速記、客戶拜訪錄入、生活日記、團隊CRM

<p align="center">
 <img src="/home/coder/_work/bika.ai/Docs/static/template.zh-TW.gif" alt="template.zh-TW" />
</p>

> Bika.ai模板中心預設了大量的自驅協作型AI自動化模板 

<br />

## 快速入門Bika.ai，開始AI自動化

<p align="center">

[![YouTube Video](http://img.youtube.com/vi/CxJFssdj6hs/0.jpg)](http://www.youtube.com/watch?v=CxJFssdj6hs)

</p>

<br />

讓我們快速入門一下Bika.ai，看看短短4分鐘內，習得AI自動化新技能，在今後釋放您的時間。

1. 右上角註冊Bika.ai帳號，[點擊這裡](https://bika.ai/signup)註冊;
2. 在空間站界面左側，點擊進入模板中心，看到大量預設好的AI自動化模板；
3. 選擇模板“Slack頻道定時提醒”，進行安裝；
4. 根據模板內的Slack Incoming Webhooks指引，創建Slack應用，並獲取對應Channel Webhook URL；
5. 複製對應Channel Webhook URL，粘貼到模板的URL處；
6. 點擊手動觸發，看到Slack中收到消息，配置成功；
7. 根據需求，調整自動發送文案和發送時間；
8. 手動觸發，確認Slack中的提醒更新正確；
9. 打開自動化“啟動”開關，你的AI自動化就已配置完畢了。

下面簡單介紹原理。

<br />

## 深入Bika.ai: 是如何讓AI自動完成任務的？

在看完快速入門之後，相信你會發現，使用Bika.ai非常簡單，選擇對應的AI模板，你就可以非常簡單完成各種任務，並微調做更多的事情。

我們打開主界面UI，深入一下Bika.ai，理解一下它的基礎組件，及它是如何做到的？

<p align="center">
 <img src="/home/coder/_work/bika.ai/Docs/static/space2.zh-TW.png" alt="space2.zh-TW" />
</p>

### 空間站 Space

空間站是你第一次進入Bika.ai看到的界面，涵蓋了你所有工作內容，由個人區域、資源區域、探索區域、展示區域、個人設置、以及空間站管理構成。


<p align="center">
 <img src="/home/coder/_work/bika.ai/Docs/static/space-structure2.zh-TW.png" alt="space-structure2.zh-TW" />
</p>


一個空間站可以有多個成員，每個成員可以有專屬的個人專區，建立多個資源。

### 個人區域 Personal Area

在個人區域中，你可以看到專屬於你的主頁、任務、和報告。主頁很好理解，是你個人相關工作的一個總覽，讓我們來看看「我的待辦」和「報告」。

#### 我的待辦

Bika.ai中，AI會自動化生成一些任務，比如說收集數據、閱讀報告、填寫數據、審批AI生成的稿件等等等等。

<p align="center">
 <img src="/home/coder/_work/bika.ai/Docs/static/mission1.zh-TW.png" alt="mission1.zh-TW" />
</p>

注意，Bika.ai說的“任務”， 與你一般理解的to-do軟件中的任務不同，

通常的待辦事項軟件中，用戶需要手動創建和完成任務，並手動標記完成。

而在Bika.ai中，任務由AI自動生成，並且AI也會自動判斷任務是否完成。

比如說，像在「每日晨會模板」(鏈接)中，AI會為每位成員自動生成任務，從而實現任務管理的全自動化。這種方式減少了人工操作，提高了效率。

#### 報告

報告，基於設定的規則或數據，由AI或自動化進行匯總生成，有點像一篇郵件、文章。

<p align="center">
 <img src="/home/coder/_work/bika.ai/Docs/static/report2.zh-TW.png" alt="report2.zh-TW" />
</p>


### 資源區域 Resource Area

在安裝模板的時候你就發現看到，一個模板是有多個資源組成的 ， 以下面的這個“Slack頻道定時提醒”模板為例，它由一個資源構成：

- 自動流程: 定時做某件事

<p align="center">
 <img src="/home/coder/_work/bika.ai/Docs/static/template-detail1.zh-TW.png" alt="template-detail1.zh-TW" />
</p>

此外，資源還可以包括數據庫（多維表格），可以利用AI自動化能力進行強大的數據可視化。

### 探索區域 Explore Area

探索區域方便你拓展Bika的各種可能性，包括模板中心、邀請成員、升級、聯繫客服、幫助與支持。其中模板中心為你提供了豐富的AI自動化模板，讓你可以快速解決工作難題。

<p align="center">
 <img src="/home/coder/_work/bika.ai/Docs/static/explore-area.zh-TW.png" alt="explore-area.zh-TW" />
</p>

### 展示區域 Display Area

在這裡，你將可以對你的任務、報告、資源節點進行展示與編輯，方便你了解並管理你的工作內容。

<p align="center">
 <img src="/home/coder/_work/bika.ai/Docs/static/display-area.zh-TW.png" alt="display-area.zh-TW" />
</p>


### 個人設置 Personal Settings

點擊左下角頭像 -> 個人設置，你可以看到你的個人信息、帳號綁定與安全、通知設置、登錄記錄、開發者 API、以及推薦獎積分。

<p align="center">
 <img src="/home/coder/_work/bika.ai/Docs/static/personal-setting.zh-TW.png" alt="personal-setting.zh-TW" />
</p>

### 空間站管理 Space Management

點擊左上角空間站 -> 齒輪圖標，你可以進行空間站管理和設置，包括：空間站設置、邀請成員、成員管理、角色管理、第三方集成、付費升級、用量&帳單、空間站審計。

<p align="center">
 <img src="/home/coder/_work/bika.ai/Docs/static/space-setting.zh-TW.png" alt="space-setting.zh-TW" />
</p>

<p align="center">
    <a href="https://bika.ai/auth?redirect=%2Fspace" target="_blank">
        <img src="/home/coder/_work/bika.ai/Docs/static/blog-cta.zh-TW.png" alt="bika-cta" />
    </a>
</p>

<br />

## Bika.ai有什麼應用場景？

Bika.ai是一款主動協作型AI工具，結合AI推理、自動化、數據表、任務等技術，在以人決策為本的情況，幫助人們自動化完成很多工作，歸納來說，它尤其比較適合於以下幾大場景：

### 定時發送通知、消息、郵件

設定指定時間或觸發事件，自動發送消息、郵件、通知、AI匯總、AI任務等，比如通知人們進行每日晨會、每日提醒、每日报告、每月數據收集等。

參考模板:

- [Email Reminder](https://bika.ai/zh-TW/template/email-reminder) 
- [Slack Channel Scheduled Notifications](https://bika.ai/zh-TW/template/slack-ai-automated-remind) 
- [Invoice collation reminders](https://bika.ai/zh-TW/template/invoice-org-ai-automated-remind) 
- [Rotating Duty Reminder(Slack)](https://bika.ai/zh-TW/template/rotating-duty-reminder-slack) 

<br />

### AI自動化定時抓取網頁並生成內容、文章、報告

根據設定的規則或數據，由AI或自動化對某些第三方的網頁、數據進行抓取，再經過AI大模型進行匯總生成，生成一篇郵件、文章、內容、視頻、圖片。

你可以想像一個公司內部的自媒體內容專員、數據采集專員、競品分析專員，24小時365天每天幫你采集市場信息和動態，風雨不休，每日遞交給你一份報告。

參考模板:

- [Automated Stock Data Retrieval (Python)](https://bika.ai/zh-TW/template/automated-get-stock-info-py) 
- [Automated Currency Data Retrieval (Python)](https://bika.ai/zh-TW/template/automated-get-currency-info-py) 
- [Automated Currency Data Retrieval (JavaScript)](https://bika.ai/zh-TW/template/automated-get-currency-info-js) 
- [Automated Stock Data Retrieval (JavaScript)](https://bika.ai/zh-TW/template/automated-get-stock-info-js) 

<br />


### AI自動化生成任務、數據收集

通過AI自動化生成一些任務，委派人們收集數據，生成的多維表格支持億級數據行，並能根據您的數據生成圖表，如銷售額、客戶增長、團隊績效、人口普查等。

比如，Bika.ai在AI自動化的加持下，搖身一變變成一個AI驅動的CRM客戶管理系統。

參考模板：

- [Vika CRM模板](https://bika.ai/zh-TW/template/@vika/crm) 
- [Daily Standup](https://bika.ai/zh-TW/template/@vika/scrum-standup) 
- [Vika OKR](https://bika.ai/zh-TW/template/@vika/okr) 

<br />

## 誰適合用Bika.ai？

尤其適合以下人士使用：

### 個人生活助理 & 個人工作助理

每個人的生活中，總有很多的定期的繁雜事務需要處理，如果有一個AI助理主動幫你分擔或提醒，那該多好。使用Bika.ai，AI可以自動化每日提醒你進行每日記帳、每日日記、水電費繳納等等個人生活和工作場景。

### CEO & 企業主

CEO或企業主，日常帶領團隊，會有大量的瑣碎事，要雇員、要管理，可不容易。

企業主使用Bika.ai可以理解為請了一個「AI團隊」，每年365天24小時不眠不休地為您工作的「助理」，幫您完成各種工作，比如每日任務追蹤、每日晨報追蹤、每日數據收集、數據匯總、文案寫作、報告生成、銷售數據收集、銷售任務分配、銷售績效追蹤、客戶拜訪、銷售報告、銷售數據收集、銷售任務分配、銷售績效追蹤、市場動態熱點抓取等等。

參考模板：

- [Daily Standup](https://bika.ai/zh-TW/template/@vika/scrum-standup) 
- [Vika OKR](https://bika.ai/zh-TW/template/@vika/okr) 

<br />

### 銷售管理者 & 項目管理

銷售管理者每天都會面對很多的管理難題，如何催促銷售員工做客戶拜訪、銷售任務分配、銷售績效追蹤，如何有效記住客戶的交往歷史、訂單詳情，如何高效地進行銷售數據收集、銷售報告生成？

銷售管理者和項目管理者，使用Bika.ai，就像為自己聘請了一個「AI助理」，每年365天24小時不眠不休地為你催促拜訪記錄填寫、客戶動態更新，銷售任務分配、銷售績效追蹤、銷售報告生成、銷售數據收集、銷售任務分配、銷售績效追蹤、市場動態熱點抓取等等。

參考模板：

- [Vika CRM模板](https://bika.ai/zh-TW/template/@vika/crm) 

- [Email Reminder](https://bika.ai/zh-TW/template/email-reminder) 

<br />

### 市場人 & 內容運營

內容創作者，真正用於內容創作的時間，其實遠不如你想像的那麼多，大部分時間都在琢磨、選題、打草稿、策劃、排版、發布、推廣等等瑣碎事務上。使用Bika.ai，AI每日自動抓取新聞熱點或市場動態，為你提供創作靈感和素材，甚至定期自動發布，自動化生成一些內容、文章、報告，你只需要微調、審批、發布即可。

參考模板:

- [Automated Stock Data Retrieval (Python)](https://bika.ai/zh-TW/template/automated-get-stock-info-py) 
- [Automated Currency Data Retrieval (Python)](https://bika.ai/zh-TW/template/automated-get-currency-info-py) 
- [Automated Currency Data Retrieval (JavaScript)](https://bika.ai/zh-TW/template/automated-get-currency-info-js) 
- [Automated Stock Data Retrieval (JavaScript)](https://bika.ai/zh-TW/template/automated-get-stock-info-js) 

<br />

## 更多高級功能

總的來說，Bika.ai提供一系列讓AI主動、自動化的新奇的功能，從個人到企業都適用。

- 空間站：空間站是你個人或團隊的工作空間，一個空間站可以有多個成員，每個成員可以有多個任務、報告、資源、AI Agent等；
- 資源：資源是一種可以被AI自動化操作的對象，包括：
  - 自動化流程：設置定時、觸發事件，自動化完成某些事情
  - 數據表：與多維表格、數據庫表格類似的，結構化的表格，支持億級數據行
  - 視圖: 將數據表中的一種視圖，如網格視圖、圖庫視圖、腦圖視圖、看板視圖、全功能網格視圖、日曆視圖等，獨立在資源中；
- 任務： 與你理解的“個人任務”不同，是AI自動化生成的任務，由AI自動化去判斷有沒有完成；
- 報告：有自動化或AI進行匯總，生成的文案報告；
- 數據表：
  - `大數據量`: 億級數據行的多維表格，支持大數據量圖表生成、AI數據訓練；
  - `豐富的API`: 從 `數據(Data)` 到 `元數據(Metadata)` 的全棧式OpenAPI訪問，將Bika.ai當成PostgresSQL、MySQL等業務數據庫使用；
  - `關聯`: 單向/雙向表鏈接和 `無限交叉鏈接`
  - `AI 搜尋`：對整個資料表、檢視、知識庫進行 AI 搜尋和問答，化為生產力知識庫；
  - `增刪改查`: 創建、瀏覽、更新、刪除表、列和行
  - `個性化工具欄`: 每位用戶使用數據表工具欄作出的篩選、分組等操作都是獨立的，不會影響其他用戶
  - `字段操作`: 排序、過濾、分組、隱藏/取消隱藏、高度設置。
  - `基於空間(Space)`：使用分離的工作空間來代替基於 App/Base 的結構，使無限的表格連接成為可能。
  - `暗色模式` 和主題定制。
  - `7 種視圖類型`: 網格視圖(Datasheet) / 圖庫視圖 / 腦圖視圖/ 看板視圖 / 全功能網格視圖 / 日曆視圖
- 模板： 真正的一站式模板，將自動化、第三方集成、數據表、組織角色打包在一起，一鍵安裝，一鍵使用；
  - 升級模板: 安裝後的模板，可以跟隨官方升級，也可以自己進行輕量級微調
  - 發布模板: 一站式、全棧式的模板，可以對外發布，甚至對外售賣模板，保護的知識產權，模板不會安裝後就失去控制權；
- 個人與團隊、企業級結構管理：
- 多語言：默認支持英文、簡體中文、繁體中文、日語，無縫支持跨國團隊協作，更多語言等你來提；
- 企業級權限
  - 權限：支持個人、團隊、企業級權限，支持個人局部權限、行權限、列權限、文件夾權限等；
  - 獨立資源`視圖`, 將視圖變成鏡像以實現更高級的權限隔離；
  - 通過非常簡單的操作激活 `列權限`
  - 文件夾/子文件夾/文件權限
  - 樹結構文件夾和可自定義的資源（節點文件）
  - 團隊管理 & 組織架構
  - 支持OEM貼牌和私有化部署
- 未來更多功能
  - AI語音：全智能
  - AI創建：
  - Terraform資源控制
  - 集成 n8n.io / Zapier / make.com / Appsmith等更多
  - 單點登錄（SSO）/SAML等身份驗證
  - 定制擴展和插件
  - 審計
  - 數據庫自動備份/導出
  - 安全水印
  - Slack/WhatsApp/Teams/Telegram/釘釘/企業微信/飛書集成
- ....

## 完全免費試用

<p align="center">
    <a href="https://bika.ai/auth?redirect=%2Fspace" target="_blank">
        <img src="/home/coder/_work/bika.ai/Docs/static/blog-cta.zh-TW.png" alt="bika-cta" />
    </a>
</p>

<br />

目前Bika.ai完全免費使用，而且用量非常慷慨，你可以參考免費規格，你可以詳情查看[價目表](https://bika.ai/pricing)。

如果你有想法，想提出一些功能，請加入我們社區，用力吐槽和給建議哈：https://bika.ai/contact。

如果你有進一步的功能需要，如私有化部署、功能定時等，請聯繫我們的[高級管理人員](?contact=1)。

<br />

## 常見問題解答: 什麼是Bika.ai?

### 1. Bika.AI是免費使用的嗎？
是的，目前Bika.AI是完全免費使用，而且用量非常慷慨，你可以參考免費規格。 如果您超出了免費規格，或者，你想享受定制功能、私有化部署等更多服務，可以[聯繫銷售](https://bika.ai/zh-TW/blog/what-is-bika-ai?contact=1)

<br />

### 2. 一句話快速介紹：什麼是Bika.ai?
Bika.ai 是一個AI自動化工具，透過結合表格型數據庫和AI技術，自動化地優化數據管理和任務處理，幫助您更高效地執行工作流程。

<br />

### 3. Bika.ai是怎麼做到AI自動化做事的？
Bika.ai的起點不是“聊天框”，而是“自動化”，透過設置自動化和一些觸發條件，如定時、新數據新增等，來觸發AI自動化做事。 實際上，Bika.ai是一個“AI自動化工具”，而不是一個“AI助手”，它使用自動化功能而不依賴於大型AI模型，這意味著不需要消耗AI推理成本。透過Bika.ai的任務、匯總、資源等核心組件，可以有效地完成許多工作，節省您的時間，讓您有更多時間享受生活。 直接前往[模板中心](https://bika.ai/template)來獲取適合你的解決方案。

<br />

### 4. Bika.ai與ChatGPT、Gemini等AI助手有什麼區別？
ChatGPT、Gemini、Claude等AI助手，是基於大模型的AI聊天助手，需要消耗大量的AI推理成本， 而Bika.ai是一個AI自動化、數據庫工具，自動化地完成任務。 兩者是完全不一樣的產品，你可以瀏覽一下AI自動化模板中心，看看有沒有滿足你日常需求的[模板](https://bika.ai/template)？

<br />

### 5. Bika.ai與多維表格有什麼區別？
市面上有很多優秀的多維表格工具，如[AITable.ai](https://aitable.ai/)、[Airtable](https://airtable.com/) 等。 確實Bika.ai與多維表格的核心是類似的：表格型數據庫、自動化等。 多維表格更擅長協作，但Bika.ai是以“任務”、“彙報”、“AI自動化”為主，並不以表格為主，Bika.ai旨在利用AI充分把數據用起來的AI自動化工具。

<br />

### 6. Bika.ai 在單表數據量、關聯引用變多後，如幾萬行、幾十萬行，會卡住嗎？
不會。Bika.ai 的資料表在架構設計時就已考慮到海量數據的需求，底層綜合運用了 OLTP 業務資料庫、OLAP 分析資料庫、NoSQL 資料庫、時間序列資料庫、索引資料庫以及向量資料庫等技術，確保即使達到千萬級、億級的數據量,系統仍能保持流暢高效的效能表現。

<br />

### 7. Bika.AI中的"空間站"是什麼?
"空間站"是您的組織或團隊所有成員的協作平台。通過單擊Bika.ai工作台左上角的空間圖標,可以訪問您的個性化管理和受邀空間。

<br />

### 8. 什麼是"資源"?
"資源"一詞指的是您空間資源部分左側目錄樹文件中的文件節點，如自動化、數據庫、表單、儀表板等。 被刪除的資源不會被計算在內。創建一個新的數據庫和一個新的表單會增加兩個文件節點到您的計數中。刪除其中一個項目會使計數減少一個。

<br />

### 9. Bika.ai 的團隊是如何「吃自己的狗糧」的？
好問題,我們自己內部非常熱愛使用 Bika.ai。 在內部,我們應用 Bika.ai 於:每日晨會通知/收集/彙整、每週 scrum 工作迭代通知/收集/彙整、定時給運營經理審批並發送 twitter 公眾號文章、每日銷售數據分析報告生成、功能需求和 BUG AI 自動化管理、定期行銷電郵發送等等等,盡量將重複性、日常化的工作交給 AI 自動化。 Bika.ai 團隊運營著 3 個 SaaS 平台產品、30+ 個部署、百萬的用戶、數萬個團隊客戶,我們也急需一個更 AI 自動化的工具,來減少我們的重複工作,這是我們開發 Bika.ai 的初衷。 我們希望我們的用戶,使用 Bika.ai 是「用完就走」的 —— 只要進去軟體,初始化和設置後,之後大部分的工作,都交給 AI 自動化。

<br />

### 10. Bika.ai如何幫助提高工作效率？
Bika.ai 通過其強大的自動化功能幫助用戶自動執行常規任務。用戶可以根據自己的需求設置自動化任務，比如數據更新通知、任務調度和自動報告生成等，從而減少人工操作，提高工作效率。你可以直接前往[模板中心](https://bika.ai/template)來獲取適合你的解決方案。

<br />

### 11. Bika.ai 的AI自動化功能有哪些特點？
Bika.ai 的AI自動化功能允許用戶創建基於條件的任務，這些任務可以在滿足特定條件時自動觸發。例如，當一個數據表接收到新數據時，Bika.ai 可以自動進行數據處理和分析，甚至發送通知給相關人員。直接前往[模板中心](https://bika.ai/template)來感受吧。

### 12. Bika.ai 中的自動化模板是什麼？
自動化模板是預先設定的任務流程，用戶可以直接應用這些模板，3分鐘來自動化特定的工作流程。這些模板涵蓋了從數據錄入到複雑數據處理的各種常見場景，使用戶能夠快速部署和利用AI技術。建議你可以直接前往[模板中心](https://bika.ai/template)進行使用。

<br />

### 13. Bika.ai 是否支持团队协作及权限功能？
是的，Bika.ai 提供了“空间站”功能，这是一个团队协作平台，，不仅允许团队内部成员共享资源、管理数据和协同工作，还能良好地支持与外部团队或个人的协作。空间站支持个性化设置和权限管理，确保团队成员可以高效地协作。

<br />

<p align="center">
    <a href="https://bika.ai/auth?redirect=%2Fspace" target="_blank">
        <img src="/home/coder/_work/bika.ai/Docs/static/blog-cta.zh-TW.png" alt="bika-cta" />
    </a>
</p>