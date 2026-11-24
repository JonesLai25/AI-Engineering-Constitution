# Token 與工作流資料

`token_usage.csv` 由本次 CS 對話的私人 Session 時間點快照中，僅擷取結構化 `token_usage_record` 的非負整數欄位，依原出現順序編號；turn ID 轉為本資料集內的順序號。移除了原始訊息、工具參數與輸出、Session／回應識別碼、絕對時間、路徑與其他內容。原始 `TokenCountEvent` 與 usage 紀錄可能重複，沒有一併匯出或相加。

快照包含 2183 筆使用量事件與 17 個有記錄的 turn；仍在進行中的對話在快照後的資料不包含在內。此數據的累計／計費語義及其與實際扣費的對應 **UNKNOWN**；不能將欄位直接相加宣稱為成本或完整任務消耗。cached input、reasoning output 只屬數值欄位，不包含模型內部推理。詳見 `metadata.json`。

為保護私人資料，未公開完整 Session、完整工具呼叫、原始 Git 歷史或私人封存。選擇與去識別化會限制時間分析、人工介入計數及他人重現能力。
