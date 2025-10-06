# Torrent4.0 UIワイヤーフレーム

## 画面一覧とストーリー対応（screen_map.yaml）
- SC1: US-001, US-002, US-007, US-008, US-012, US-019, US-020, US-021
- SC2: US-003, US-004, US-005, US-006, US-009, US-010, US-013, US-014, US-022, US-023, US-024, US-025, US-026, US-027
- SC3: US-015, US-016, US-017, US-018, US-030, US-031, US-032

## スクリーンフロー（MVP/Release）
- MVP/Releaseの画面遷移図は `screen_flow_mermaid.md` を参照（Mermaidコードフェンス付きで出力済み）

## 画面設計仕様
- SC1_design.yaml: ダッシュボード画面の設計仕様
- SC2_design.yaml: 目標設定・進捗管理画面の設計仕様
- SC3_design.yaml: システム管理画面の設計仕様

## ワイヤーフレーム（ASCII Art）
- SC1_wire_aa.md: ダッシュボード画面のワイヤーフレーム
- SC2_wire_aa.md: 目標設定・進捗管理画面のワイヤーフレーム
- SC3_wire_aa.md: システム管理画面のワイヤーフレーム

## Draw.io
- `drawio/SC1.drawio`, `drawio/SC2.drawio`, `drawio/SC3.drawio` は別コマンドで生成可

## 設計方針
- レスポンシブデザイン対応
- アクセシビリティ対応
- Material-UIベースのデザインシステム
- 階層表示による直感的操作
- リアルタイム更新機能

