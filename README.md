# Cloud Computing and FinTech(109-2)
## Course Description
課程內容包括財金專業知識、文字探勘與機器學習，以及使用程式語言（如 Python）來實作專題。

學習 AWS 所提供的雲端運算服務，其中包含：
1. 架設虛擬機與伺服器
2. 網頁部署與版本控制
3. API 串接 Chatbot
4. RDS 與 DynamoDB 資料庫服務
5. Docker 技術應用

除此之外，將會跨校組隊，共同解決金融業者（如：南山人壽、永豐金控等公司）實務上所面臨的問題。

授課老師：
* 蔡芸琤 老師

課程助教：
* 司福民 助教
* 陳偉傑 助教
* 蔡雨臻 助教


---
## Self Introduction
**Name** : 黃柏森 *Bosen Huang*

**Major** : Soochow University Big Data

**Better programming language** : Python


---
## Homework
### HW1
* [HW1](HW/HW1.md)

### HW2

### HW3

### HW4

### HW5

### HW6

---
## Project
### 南山人壽題目一：文本分析--市場焦點機器人
在人力不足與資料爆炸的背景下，希望透過自動化的方式去採集資料並萃取重點生成報告書。

### 目前市場上的做法(WHY)
像新聞等文字資訊（尤其是中文），大多是透過人力去瀏覽、蒐集並彙整成報告書。

### 預備解決的痛點(WHAT)
1. 解決隨新聞量劇增所造成之人力成本增加以及分析品質不佳等問題。
2. 自動化生成焦點報告書，提高同仁工作效率。
3. 對每日市場新聞進行焦點萃取和動向變化分析，以擴展投資之資訊觸手。
4. 挑戰中文分析利用斷詞方式所產生的瓶頸。建構通用之中文語意分析框架，以作為其他應用之分析引擎。

### 可能的解決方法(HOW)
1. 利用 Google News 作為蒐集每日新聞之源頭。
2. 使用 Google Translation 進行中文與英文之對照翻譯。
3. 以 NLTK 等英文模型進行文字解析。
4. 使用 JIEBA 或 CKIP 等中文模型進行文字解析。
5. 透過 PPTX 及 XlsxWriter 生成報告書。
