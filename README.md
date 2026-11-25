# AI 工程憲章：一場尚未解明的工程實驗

工作是為了不用工作。  
事成何必有我。  
哲學名言就是一句了不起的廢話。

這套憲章的起點是實際工作問題：使用 AI 協助後，人類可能反而承擔更多管理工作。作者以哲學和工程原則建立行為框架，嘗試讓 AI 在既定目標、權限與安全邊界內，自主完成設計、實作、測試、故障處理與交付。

作者在 CS Communication Service 開發過程中觀察到人工介入逐漸減少、工作流變得順暢，並建立自主故障處理與驗收機制；同時也觀察到可觀的 Token 與運算消耗。作者認為憲章具有實用成效。這些是作者的觀察與判斷，不是有對照組的因果證明。

目前工具不能完整觀察 Codex Agent 的內部推理或決策。憲章作用機制、各原則的個別貢獻、消耗成因、跨模型與翻譯版本的等效性均未知。本資料提供工程案例與可證偽問題，供研究者重現、分析、改良或反駁；不補造缺失資料。

## 通用工程憲章版本

- [最新版：通用工程憲章 v1.1（P01～P23）](constitution/GENERAL_CONSTITUTION_V1.1.md)
- [通用工程憲章 v1.0（P01～P22）](constitution/GENERAL_CONSTITUTION_V1.0.md)

v1.1 新增 P23「已足則止，無益不為」，引入奧卡姆剃刀、有限理性、資訊價值、邊際效益及最小充分智慧原則，強化工程收斂、模型選擇及資源調度能力。v1.1 已完成本機全域部署及新 Session 載入驗證；實際成本改善效果仍待透過正常工程活動觀察。

## 原始資料與研究

- [工程憲章的思想淵源：從工程師的自我修為到 AI 工程治理](THOUGHT_ORIGINS.md)
- [工程憲章與補充原文整合閱讀版](constitution/COMPLETE_CHARTER.md)及 [AGENTS.md 使用範例](examples/AGENTS.md)
- [實際使用的原始憲章](constitution/PROJECT_CHARTER.md)及[專案補充](constitution/ENGINEERING_CHARTER.md)
- [歷史版本與使用者原文補充](constitution/versions/INDEX.json)
- [使用方法與 AGENTS.md 範例](USAGE.md)
- [實驗時間線、故障與人工介入](OBSERVATIONS.md)
- [Token 資料及限制](observations/README.md)
- [研究問題](RESEARCH_QUESTIONS.md)

相關軟體專案為 [CS-Communication-Service](https://github.com/JonesLai25/CS-Communication-Service)；本資料不依賴該專案執行。

繁體中文原文為本次實驗基準；翻譯版本的行為等效性未驗證。作者授權本資料採用 [CC BY 4.0](LICENSE)。
