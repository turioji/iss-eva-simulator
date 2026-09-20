# 🚀 ISS EVA Simulator

**国際宇宙ステーション 船外活動シミュレーター**

Three.js製のブラウザゲームです。インストール不要、ブラウザだけで動きます。

## 🎮 遊ぶ

👉 **[GitHub Pages で遊ぶ](https://turioji.github.io/iss-eva-simulator/)**

## 特徴

- 🛰 本物のISS位置データをリアルタイム表示
- 🔧 修理ミッション（ボルト締め・パネル交換・アンテナ調整）
- 💥 ISS衝突判定・デブリ回避
- 🌙 昼夜サイクル（90秒周期）
- 📡 管制官からの無線メッセージ
- 🏆 スコア・コンボシステム

## 操作方法

| キー | 動作 |
|---|---|
| W / 上矢印 | 前進 |
| S / 下矢印 | 後退 |
| A / 左矢印 | 左移動 |
| D / 右矢印 | 右移動 |
| Q または Z | 上昇 |
| E または C | 下降 |
| マウス | 視点操作 |

## 技術構成

- Three.js r128
- Vanilla JavaScript（フレームワークなし）
- HTML1ファイル完結
- ISS位置API: [wheretheiss.at](https://wheretheiss.at)

## ライセンス

MIT
