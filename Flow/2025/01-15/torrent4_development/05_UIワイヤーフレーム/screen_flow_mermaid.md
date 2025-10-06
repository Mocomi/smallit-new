```mermaid
flowchart LR
  %% MVP
  SC1[SC1 ダッシュボード] -->|目標設定| SC2[SC2 目標設定・進捗管理]
  SC2 -->|進捗更新| SC1
  SC1 -->|システム管理| SC3[SC3 システム管理]
  SC3 -->|戻る| SC1
  
  %% Release1
  SC1 -->|詳細表示| SC2
  SC2 -->|設定変更| SC3
```

