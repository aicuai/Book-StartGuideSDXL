# 書籍サポートリポジトリ

AICU media / 白井 暁彦 著作物の Colab ノートブック・サポートリソース集です。

---

## 📗 画像生成AI Stable Diffusion スタートガイド（SD黄色本）

- 発売日: 2024年3月29日 / ISBN: 978-4-8156-2456-9
- [SBクリエイティブ](https://www.sbcr.jp/product/4815624569/) / [Amazon](https://j.aicu.ai/SBXL)
- [Issues（質問・不具合報告）](https://github.com/aicuai/Book-StartGuideSDXL/issues)
- [wiki](https://github.com/aicuai/Book-StartGuideSDXL/wiki)
- [AICU メンバーシップ](https://note.com/aicu/membership/boards/61ab0aa9374e/posts/7cab00942b22)
- [HuggingFace (LoRA配布)](https://huggingface.co/AICU/SDXL-LoRA/blob/main/README.md)

### Colab ノートブック（SD黄色本対応）

| 章 | ノートブック | リンク |
|----|-------------|--------|
| 第2章 | A1111 on Colab | [j.aicu.ai/SBXL1](https://j.aicu.ai/SBXL1) |
| 第5章 ControlNet | TheLastBen版 | [j.aicu.ai/SBXL2](https://j.aicu.ai/SBXL2) |
| 第6章 LoRA | SDLoRA2 (Hollowstrawberry) | [j.aicu.ai/SDLoRA2](https://j.aicu.ai/SDLoRA2) |
| 第6章 LoRA SDXL | SDLoRA2 XL | [j.aicu.ai/SDLoRA2XL](https://j.aicu.ai/SDLoRA2XL) |
| おまけ | A1111 実写系 | [j.aicu.ai/SDPH](https://j.aicu.ai/SDPH) |
| おまけ | Fooocus日本語版 | [j.aicu.ai/FoooC](https://j.aicu.ai/FoooC) |

---

## 📘 画像・動画生成AI スタートガイド（SG26）

> **AIキャラ開発スタートガイド** — 2026年7月10日発売予定
> ISBN: 978-4-8156-3767-5 / SBクリエイティブ / B5判160ページ / 2,860円
> [note連載（先行版）](https://j.aicu.jp/CSG)

### 第3-11節対応: オリジナルLoRAを作ろう

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aicuai/Book-StartGuideSDXL/blob/main/AICU_Civitai_LoRA_Trainer.ipynb)

**`AICU_Civitai_LoRA_Trainer.ipynb`** — Civitai モデルに対応した SDXL / Illustrious 系 LoRA トレーナー

| 項目 | 内容 |
|------|------|
| ベースモデル（デフォルト） | Sierunami v1（Illustrious License） |
| モデル取得元 | https://j.aicu.ai/sierunami |
| 認証方式 | Colab Secrets `CIVITAI_KEY` |
| Kohya バージョン | `sd-scripts` v0.10.5（固定） |
| PyTorch | 2.6.0 + CUDA 12.4 wheel |
| デフォルトキャラ | 響姫メイ（HibikiMei）/ 25枚データセット |
| データセット | [HibikiMei.zip](https://huggingface.co/AICU/SDXL-LoRA/resolve/main/HibikiMei.zip) |

**Civitai API Key の設定方法:**
1. https://civitai.com/user/account で API Key を発行
2. Colab 左側の 🔑 アイコン → シークレット → `CIVITAI_KEY` に貼り付け
3. ノートブックのアクセスを許可

---

## Updates

- **2026-06** `AICU_Civitai_LoRA_Trainer.ipynb` 追加: Civitai対応・HibikiMeiデフォルト・Kohya LTS固定
- 2025-07-29 A1111 TheLastBen on Colab 不具合修正 ([詳細](https://j.aicu.ai/SBXL1))
- 2025-05-18 LoRA編不具合修正・Animagine XL4.0対応 ([note](https://note.com/aicu/n/n856b81b530e5))
- 2025-04-05 hotfix: 起動不具合解消・Animagine XL4.0 zero対応 ([note](https://note.com/aicu/n/ndbf69d4aa154))
- 2024-12-28 第3刷対応 hotfix ([SBXL1](https://j.aicu.ai/SBXL1) / [SBXL2](https://j.aicu.ai/SBXL2))
- 2024-11-18 第3刷 6.3 LoRA章追加 ([SDLoRA2](https://j.aicu.ai/SDLoRA2))

---

## Issues・質問

- [Issues](https://github.com/aicuai/Book-StartGuideSDXL/issues)（バグ報告・質問はこちら）
- [AICU media 特集](https://ja.aicu.ai/sbxl/)
- [AICU メンバーシップ サポートDiscord](https://note.com/aicu/membership/boards/61ab0aa9374e/posts/b19143b895ce)
