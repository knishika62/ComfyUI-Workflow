# ComfyUI Workflows

ComfyUI用のワークフロー集です。

## フォルダ構成

```
├── LTX-2/          # LTX-2 動画生成ワークフロー
│   └── LTX-2_S2V.json
├── sora2-like/     # LLMを使ったSora2風動画生成ワークフロー
│   ├── make_scenario_by_LLM.json
│   ├── scenario_t2v.md
│   ├── scenario_i2v.md
│   ├── ltx2_prompt_t2v.md
│   ├── ltx2_prompt_i2v.md
│   ├── japanese_to_romaji.md
│   └── README.md
└── Z-Image/        # 画像生成ワークフロー
    └── ZIT_ZIB_Hybrid.json
```

## 使い方

1. ComfyUIを起動
2. 使用したいワークフロー（`.json`）をドラッグ＆ドロップ、または「Load」から読み込み
3. 必要に応じてパラメータを調整して実行
