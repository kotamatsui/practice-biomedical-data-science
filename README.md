# 医療データ科学実習（Practice of Biomedical Data Science）

| 講師  | 松井茂之，松井孝太，江本遼 |
| --- | -------- |
| 日程  | 火曜日3，4限|

## 概要 
この演習では，医療データ科学（コア）の講義で学んだ医療データ科学の考え方を実際に実践することでその理解の定着を図ることを目的とします．フリーのデータ解析のソフトウエアとして今日幅広く使用されている「R」を用いた実習を中心に行います．後半は様々な実データを解析し，結果を整理してプレゼンテーションするグループ実習を行います．本実習の受講にあたり，各自のノートパソコン（Windows，Mac）を持参してください．

## 到達目標
- 医療データ科学の考え方，基本的なデータ解析法についての理解を深める．
- データ解析ソフトを用いて，データ読み込みからデータ解析までを適切に行い，解析結果を適切に解釈できるようになる．

## 成績評価
- 数回の個人レポートとグループによるプレゼンテーションと質疑応答を評価します．
- 配分はレポート70％，グループ実習でのプレゼンテーションと質疑応答30%相当とします．

## 準備
- [R](https://www.r-project.org)および[RStudio](https://posit.co/download/rstudio-desktop/)を各自のパソコンにインストールします（インストールについては初回の講義時に説明します）．
  - Rは統計を含むデータ解析に特化したオープンソースのプログラミング言語であり，医学・生物学研究をはじめ多くの領域で広く用いられています．
  - RStudioはR用の主要な統合開発環境 (Integrated Development Environment, IDE) です．多くの人がRStudioを使ってRのコーディング，実験管理を行います．
- 講義中のRコードの共有には[Google Colab](https://colab.research.google.com)を利用します．利用にはGoogleアカウントが必要となりますので，持っていない場合は作成をしてください（アカウントの作成は無料でできます）．

## 講義スケジュールとコンテンツ
凡例：📖 スライド資料，💻 Google Colab，💡 slido (質疑応答フォーラム)
### 第1回: データ解析ソフト「R」事始め, インストール, 環境設定
- Rのインストール方法 [📖](Session1/r-install.pdf)
- RStudioのインストール方法 [📖](Session1/rstudio-install.pdf)
- R言語で何ができるか？[📖](Session1/R_demo_logistic.pdf)
- R言語事始め [📖](Session1/R言語事始め.pdf)
  - Rの変数とデータ型 [💻](https://colab.research.google.com/drive/1xxZ20hLT_deXhGRLtRpkht2t9KJ6G4cw?usp=sharing)
  - ベクトル演算 [💻](https://colab.research.google.com/drive/1C_NLAvUe4bMCiv9lQGOqH6wAvTTFd_9P?usp=sharing)
  <!-- - Rによる擬似乱数生成 [💻](https://colab.research.google.com/drive/1A6nBKT40T_vSZuXONgFgAgMF8QVzqG7w?usp=sharing) -->

### 第2回: データセットの作成　[💡](https://app.sli.do/event/ntA1oiNfNnSgbddJ8sUhiQ)
- R言語事始め（続き）[📖](Session2/250415_pbds_session2.pdf)
  - Rにおけるデータテーブルの作成
  - R上のデータテーブルの外部ファイルへの書き出しと外部データのRへの読み込み
  - Rの組み込み関数
  - 外部パッケージのインストールとインポート
    - Rによる擬似乱数生成 [💻](https://colab.research.google.com/drive/1A6nBKT40T_vSZuXONgFgAgMF8QVzqG7w?usp=sharing)
    - ベクトル演算 [💻](https://colab.research.google.com/drive/1C_NLAvUe4bMCiv9lQGOqH6wAvTTFd_9P?usp=sharing)
    - 乱数生成とプロット [💻]
- Microsoft Excelで作られたデータの取り扱い [📖](Session2/R_Excel_Data.pdf)  [データセット](https://www.dropbox.com/scl/fo/bx4rkyx48eo1o209w69nl/ACSn0dwcNiWNhFl9g0LnLnI?rlkey=5iujgakjr7bqeepum3xqar7tk&st=bk8w0bfo&dl=0)
  - Rに正しくデータを読み込むための前処理
    - Excel上でのデータ作成，データテーブルの修正とCSVファイルへの変換
    - よくあるExcelやCSVの問題点と対処法
    - 適切なデータセットとは
  - Rへの読み込みとR上でのデータチェック
 
### 第3回: データの集計
- ベース機能を使っての表作成
  - 一変数：離散変数の頻度集計，連続変数の頻度集計
  - 二変数：離散変数のクロス集計
  - 要約統計量算出（連続変数の平均，中央値，分散，標準偏差など）
  - 層別の集計，要約統計量の計算
- 外部パッケージを使ってのデータ集計
  - dplyrとjanitorを使ったデータ操作・集計，クロス集計や頻度表の作成
  - 組み込み関数を用いた集計と外部パッケージを用いた集計の違い

### 第4回: グラフの作成1
### 第5回: グラフの作成2
### 第6回: 記述統計
### 第7回: シミュレーション, 統計的推測の基本概念
### 第8回: サンプルサイズ設計
### 第9回: グループ実習1: データ選択・収集, 解析計画書
### 第10回: グループ実習2: データ解析
### 第11回: グループ実習3: データ解析
### 第12回: グループ実習4: 報告資料の作成
### 第13回: 診断・予後解析研究におけるデータ解析
### 第14回: グループ実習5: プレゼンテーション

<!--
## 講義資料
- [スライド資料 (PDF)](slides/lecture1.pdf)
- [Python コード](notebooks/lecture1.ipynb)
-->

---
© 2025 Kota Matsui
