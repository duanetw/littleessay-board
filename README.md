# 小論文經典追蹤板

均線斜率 × 穿越追蹤看板，資料同步自本機的 `小論文經典.xlsx`。

網頁上的資料是 AES-256-GCM 密文（金鑰由 PBKDF2-SHA256 從密碼導出），
需要密碼才能解開。這個 repo 不含任何明文個股資料。

產生方式：在 tradingview 資料夾執行 `python sync_littleessay_web.py`。
