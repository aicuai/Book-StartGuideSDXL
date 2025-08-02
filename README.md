# 書籍「画像生成AI　Stable Diffusion スタートガイド」
## サポートリポジトリ 第3刷対応版

![](https://www.sbcr.jp/wp-content/uploads/2024/02/9784815624569-1-424x596.jpg)

- [https://www.sbcr.jp/product/4815624569/](https://www.sbcr.jp/product/4815624569/)
- [Amazon j.aicu.ai/SBXL](https://j.aicu.ai/SBXL)
- [wiki](https://github.com/aicuai/Book-StartGuideSDXL/wiki)
- [Issues](https://github.com/aicuai/Book-StartGuideSDXL/issues)
- [Membership](https://note.com/aicu/membership/boards/61ab0aa9374e/posts/7cab00942b22?from=self)
- [Huggingface](https://huggingface.co/AICU/SDXL-LoRA/blob/main/README.md)

## Updates

- [20250729 AICU A1111 TheLastBen on Colabの不具合修正](https://j.aicu.ai/SBXL1)
- [20250518 LoRA編の不具合を修正、SDXLおよびAnimagine XL4.0に対応しました](https://note.com/aicu/n/n856b81b530e5)
- [20250405 起動不具合を解消する hotfix と Animagine XL4.0 zeroへ対応を実施しました。](https://note.com/aicu/n/ndbf69d4aa154)
- 20241228 第3刷に対応した hotfixを実施しました [https://j.aicu.ai/SBXL1](https://j.aicu.ai/SBXL1)  [https://j.aicu.ai/SBXL2](https://j.aicu.ai/SBXL2)
- 20241118 第3刷 6.3 自分の画風のLoRAを作る [https://j.aicu.ai/SDLoRA2](https://j.aicu.ai/SDLoRA2)
- [20240729 Google Colab での TheLastBen版「Fast Stable Diffusion - AUTOMATIC1111」を 長期間サポート(LTS)化を目指して完全解説](https://note.com/aicu/n/nf5562077c8ad)
- 20240728 AUTOMATIC1111 v1.10.x に対応しました https://j.aicu.ai/SBXL1 https://j.aicu.ai/SBXL2


## 進行中の未解決問題は [Issues](https://github.com/aicuai/Book-StartGuideSDXL/issues) をご確認ください

- https://github.com/aicuai/Book-StartGuideSDXL/issues

## 本書で扱っている Colab ノートブック

- [Foocus日本語版](https://j.aicu.ai/FoooC)  [j.aicu.ai/FoooC](https://j.aicu.ai/FoooC)
- 第2章 [A1111 on Colab](https://j.aicu.ai/SBXL1) [j.aicu.ai/SBXL1](https://j.aicu.ai/SBXL1)
- 第5章:ControlNet編 [TheLastBen](https://j.aicu.ai/SBXL2) [j.aicu.ai/SBXL2](https://j.aicu.ai/SBXL2)
- 第6章 LoRAを作って使ってみよう (第3刷にて大幅改訂)
   - 6.3 自分の画風のLoRAを作る　https://j.aicu.ai/SDLoRA2
   - 旧スクリプト [https://j.aicu.ai/SDLoRA1x](https://j.aicu.ai/SDLoRA1x) 原作のアーカイブ化にともない、今後の対応を[検討](https://note.com/aicu/n/n96c10dd1249b)しておりましたが、代替の推奨スクリプトは「⭐ Lora Trainer by Hollowstrawberry」になります
   - SD1.5系 https://j.aicu.ai/SDLoRA2
   - SDXL系 https://j.aicu.ai/SDLoRA2XL

## 本書に含まれていないおまけコンテンツ

- [AICU media 特集サイト](https://ja.aicu.ai/sbxl/)
- 実写系SD1.5 AICU A1111 TheLastBen on Colab for Photo [j.aicu.ai/SDPH](https://j.aicu.ai/SDPH)
- [出版社：SBクリエイティブ]()
- [Amazon購入ページ]()
- [note.com/aicu メンバーシップ掲示板] (https://note.com/aicu/membership/boards/61ab0aa9374e/posts/b19143b895ce)
- 書籍を購入の方に AICU サポートDiscordもございます

## 関連イベント・ワークショップ

- [2024/06/26(水) 19:00〜20:30- 【生成AIの社会と倫理】「画像生成AI Stable Diffusion スタートガイド」](https://techplay.jp/event/946209)

- [2024/05/15 【Stable Diffusion でデルタもん LoRA を作ろう！】「画像生成AI Stable Diffusion スタートガイド」](https://techplay.jp/event/942272)

- [2024/4/19 19:00- 祝・重版出来！「画像生成AI Stable Diffusion スタートガイド」公式オンラインサイン会](https://techplay.jp/event/941839?utm_source=github)

![image](https://github.com/aicuai/Book-StartGuideSDXL/assets/5110708/39daeeaa-6677-4801-8f25-f5c557e619ac)

[Techplay](https://techplay.jp/community/AICU) および [note.com/aicu メンバーシップ掲示板](https://note.com/aicu/membership/boards/61ab0aa9374e/posts/b19143b895ce)にて最新の開催予定情報を掲示しています

# 書籍：画像生成AI Stable Diffusionスタートガイド

著者：AICU media、白井 暁彦

発売日：2024年3月29日（金）　ISBN：978-4-8156-2456-9

サイズ：B5判　ページ数：224

定価：2,640円（本体2,400円+10%税）


画像生成AIの１つであるStable Diffusionを導入・体験するための入門書です。

プログラミングが分からない、ネットの情報を見てもうまく使えなかった、そんな悩みを抱えている人でもAIを使った画像生成体験ができるようにしっかりサポートします。


本書籍では以下の環境で解説します。

- Google Colab Pro環境
- Windows10/11 NVIDIA GPU環境
- MacOS Apple silicon 環境

本書籍では以下の内容を取り扱います。

- 拡散モデルによる画像生成の原理
- Stable Diffusionを使用するためのWebUI環境構築
- テキスト/画像を元に画像を生成する（txt2img/img2img/ControlNet）
- Google Colab 上で追加学習を行う（LoRAの作成）

本書ではソフトウェアの使い方解説だけではなく、自分で設定できるセッティングやパラメータが画像生成にどのように関わっているのかについても解説しているため、AI技術について知識を深めたい人にとってもおすすめです。
また、既にAIを活用している方にもご満足いただけるように、よりAI画像制作を極めるヒントとなるようなStable Diffusionを含むAI画像生成を利用した作例のメイキング方法やプロンプト構成/生成パラメーターなどの情報を公開・解説しています。ハンズオン形式で最後まで取り組むことで、画像生成AIへの理解をより深めることができる1冊となっています。

## Chapter 1 画像生成AI について知ろう

1-1 AI で画像を生成してみよう

1-2 画像生成AI の誕生と変遷

1-3 2024 年での「AI の定義」を考えてみよう

1-4 ニューラルネットワークについて知っておこう

1-5 拡散モデルによる画像生成の原理を知っておこう

## Chapter 2 環境構築をしてはじめよう

2-1 Stable Diffusion を使う環境を用意しよう

2-2 Google Colab での環境構築

2-3 Stability Matrix をローカル環境で構築する

2-4 簡単な言葉で画像を生成する

2-5 モデルをダウンロードする

2-6 VAE をダウンロードする


## Chapter 3 プロンプトから画像を生成してみよう

3-1 プロンプトで意のままの画像を作り出す

3-2 ネガティブプロンプトを構築する

3-3 思い通りの画像を生成する

3-4 画像の解像度を上げよう

3-5 様々なパラメータを調整しよう

3-6 様々なプロンプトを試してみよう


## Chapter 4 画像を使って画像を生成してみよう

4-1 img2img でできることを知ろう

4-2 Sketch を使って画像を生成しよう

4-3 Inpaint で画像を編集してみよう

4-4 Inpaint を応用して画像を修正する

4-5 Outpainting で画像を拡張する

4-6 img2img で画像の解像度を上げる

4-7 拡張機能でアップスケーリングをしてみよう

## Chapter 5 ControlNet を使ってみよう

5-1 ControlNet について知っておこう

5-2 ControlNet をダウンロード・準備する

5-3 ControlNet を使って画像を生成する

5-4 プリプロセッサの働きを理解しよう


## Chapter 6 LoRA を作って使ってみよう

6-1 追加学習でできることを知ろう

6-2 LoRA を使用して画像を生成しよう

6-3 自分の画風LoRA をつくる

6-4 様々な種類のLoRA をつくってみよう

6-5 学習内容を出力させてみよう


## Chapter 7 画像生成AI をもっと活用しよう

Interview Guest フィナス

Interview Guest らけしで

画像生成AI の活用と注意点

AUTOMATIC1111/WebUI おすすめ拡張機能

関連用語

## 充実したコラム！
ページ番号とともに紹介します

COLUMN 使用するGoogle アカウントに注意しよう 14

COLUMN 変わりゆく社会とAI の関係性 25

COLUMN 利用しているプログラムについて 43

COLUMN Google Colab のエラーに対応しよう 45

COLUMN Google Colab の計算資源を有効に管理しよう 47

COLUMN パッケージ選択ではエスケープしないように注意しよう 57

COLUMN 画像の保存場所を変更しよう 62

COLUMN コミュニティで質問してみる 63

COLUMN StableDiffusion シリーズとは 65

COLUMN CLIP のゼロショット転移性 78

COLUMN embedding とは 82

COLUMN デフォルメキャラ風の画像を生成してみよう 106

COLUMN 色の変化を抑える設定をしておこう 111

COLUMN 下書きから画像を生成してみよう 114

COLUMN Mask blur を調整して自然に見せる 118

COLUMN 拡張機能とは 124

COLUMN オープンソースライセンスの確認 131

COLUMN 複数のControlNet を使用する 141

COLUMN Openpose をもっと使いこなそう 144

COLUMN これからのLoRA の活用方法 149

COLUMN LoRA の学習データで気を付けるべきこと 154

COLUMN 手元に保管しているモデルファイルをLoRA 学習に使う 158

COLUMN 写真や写実的な画像を学習させる場合 161

COLUMN 学習の全体像を把握しよう 167



