# 認定試験 学習教材（CCA-F ほか）

Claude 認定（CCAR-F / CCDV-F / CCAO-F / CCAR-P）および AWS 認定（AIB-C01）試験対策の自作学習教材です。

🌐 **GitHub Pages**: https://satoshif1977.github.io/CCA-F/

## 収録コンテンツ

| 種類 | 内容 | 問数/語数 |
|------|------|----------|
| 🇯🇵 日本語版問題集 | JP Vol.1–6 | 180問 |
| 📖 バイリンガル版問題集 | BILI Vol.1–9 | 180問 |
| 📚 語彙帳（チェック版） | 全19カテゴリ | 345語 |
| ☁️ AWS AIB-C01 問題集 | 要点問題集（読む版）＋ 演習ドリル（解く版） | 100問 |

## 語彙帳の機能

- チェックボックス＋localStorage 自動保存
- 自動読み上げ（Web Speech API）
- 英語のみ / 英語→日本語→英語 モード切替
- グループ再生（全体 / 100語ずつ）・リピート・速度調整
- 未記憶語のみ新単語帳を生成

## AWS AIB-C01 問題集

AWS Certified AI Business Strategist（ベータ）の試験ガイドに基づく自作問題集。

| ファイル | 用途 |
|---|---|
| `AIB-C01/AIB-C01_review.html` | 読む版。問題 → 答え → 解説 → 暗記ポイント の順に読み進める構成。巻末に暗記ノート8枚 |
| `AIB-C01/AIB-C01_drill.html` | 解く版。4択・複数選択のドリル。演習/試験モード、選択肢シャッフル、採点、誤答復習 |

### 特徴

- **公式スキル項目 58 個を 100% 網羅**（1.1.1〜4.4.6）
- ドメイン配分は公式ウェイトに一致（D1 24% / D2 28% / D3 24% / D4 24%）
- 設問形式も公式仕様どおり（択一＝1正解＋3誤答の4択、複数選択＝5択以上）
- 正解位置は各約25%（A/B/C/D = 21/21/20/20問）に平準化し、ドリル側は実行時シャッフルにも対応
- 公式の In-scope AWS services（Amazon Bedrock / Amazon SageMaker AI / Amazon Quick / AWS CAF /
  AWS 責任共有モデル / AI 料金体系 / Cost Explorer / Pricing Calculator / AWS Marketplace）に対応する問題を収録
- 各サービスは**必ず1問以上で正解側に登場**させ、「常に誤答」となるサービスを作らない
- ダミー選択肢は「知識がなくても消去できる」ものを排し、もっともらしいが観点がずれた選択肢で構成

### AIB-C01 試験概要

- 試験名：AWS Certified AI Business Strategist（AIB-C01）
- 問題数：85問 / 制限時間：170分（ベータ）
  - 試験ガイド PDF は「130 minutes」と記載しているが、これは一般提供版の想定。
    製品ページおよび Pearson VUE の予約枠（180分＝試験170分＋チュートリアル約10分）から、
    ベータは 85問／170分（＝約2分/問）で確定。本問題集の試験モードも 2分/問 で設定している
- 合格点：700 / 1000（スケールドスコア・compensatory 方式）
- ドメイン：AI Fundamentals and Literacy / AI Strategy and Business Value Creation /
  AI Governance and Responsible AI Leadership / Business Readiness, Leadership, and AI Transformation

## CCA-F 試験概要

- 試験名：Anthropic Claude Certified Architect Foundations (CCA-F)
- 問題数：60問 / 制限時間：120分
- 合格点：720 / 1000（72%）
- 主要ドメイン：Agent Architecture / Claude Code / Prompt Engineering / MCP / Context Management
