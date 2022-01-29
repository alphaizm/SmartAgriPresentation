---
marp: true
theme: gaia
# theme: uncover
paginate: true
backgroundColor: black
color: white
header: "Challenge Smart-agriculture 2022"
footer: "Created by Atsushi Nakada"
# headingDivider: 3
---

<!--
_paginate: false
-->

# 1. スマート農業を試してみませんか

～ 2021年チャレンジしてみたこと ～

---

# 2. 目次

- [1. スマート農業を試してみませんか](#1-スマート農業を試してみませんか)
- [2. 目次](#2-目次)
- [3. 導入](#3-導入)
  - [3.1. スマート農業の12カテゴリー(1)](#31-スマート農業の12カテゴリー1)
  - [3.2. スマート農業の12カテゴリー(2)](#32-スマート農業の12カテゴリー2)
  - [スマート農業のコスト感](#スマート農業のコスト感)
- [4. 背景と目的](#4-背景と目的)
- [5. ドローン](#5-ドローン)
  - [5.1. 雑草診断](#51-雑草診断)
    - [5.1.1. 期待](#511-期待)
  - [5.2. 葉色診断](#52-葉色診断)
    - [5.2.1. 期待](#521-期待)
  - [6.7. 導入する上での構成物](#67-導入する上での構成物)
- [6. トラクターナビ](#6-トラクターナビ)
  - [6.1. 使用中イメージ](#61-使用中イメージ)
  - [6.2. 使用中の期待](#62-使用中の期待)
  - [6.3. 使用後イメージ1](#63-使用後イメージ1)
  - [6.4. 使用後イメージ2](#64-使用後イメージ2)
  - [6.5. 使用後の期待](#65-使用後の期待)
  - [6.6. 2021スマート農業_福井の例を表示](#66-2021スマート農業_福井の例を表示)
  - [6.7. 導入する上での構成物](#67-導入する上での構成物-1)
  - [6.8. 導入する上での注意点](#68-導入する上での注意点)
- [7. 土壌調査](#7-土壌調査)
- [8. 質問](#8-質問)
- [9. 『提案書構成のコツ』](#9-提案書構成のコツ)

---

# 3. 導入

農林水産省発表におけるスマート農業について
- [「農業新技術 製品・サービス集」](https://www.maff.go.jp/j/kanbo/smart/products.html)には12カテゴリーが分類
- [「スマート農業技術カタログ」](https://www.maff.go.jp/j/kanbo/smart/smart_agri_technology/smartagri_catalog.html)には286サービス※
※2022/1/29現在

---

## 3.1. スマート農業の12カテゴリー(1)

| No.                               | 内容                                               |
| --------------------------------- | -------------------------------------------------- |
| 1                                 | 経営管理システム                                   |
| 2                                 | ロボットトラクター                                 |
| <span style="color: red">3</span> | <span style="color: red">自動操舵システム</span>   |
| 4                                 | トラクター（自動操舵機能付き）                     |
| 5                                 | 高性能田植機（直線アシスト機能・可変施肥機能付き） |
| 6                                 | リモコン草刈機                                     |

---

## 3.2. スマート農業の12カテゴリー(2)

| No.                                | 内容                                                                                 |
| ---------------------------------- | ------------------------------------------------------------------------------------ |
| 7                                  | 高性能コンバイン（収量等センサ・直線アシスト機能付き）                               |
| 8                                  | アシストスーツ                                                                       |
| 9                                  | 農業用ドローン・人工衛星（サービスを含む）                                           |
| 10                                 | 水管理システム                                                                       |
| <span style="color: red">11</span> | <span style="color: red">ほ場・施設環境モニタリング（環境制御システムを含む）</span> |
| 12                                 | その他農産関係                                                                       |

---

## スマート農業のコスト感

![height:450](images/smart_cost.png)
<span style="font-size:20px">　　　　　　　　　　　　　　　　　　　　　出展：スマート農業新技術 製品サービス集(農林水産省)</span>
<span style="font-size:20px">　　　　　　　　　　　　　　　　　　　　　引用：FOODBOX株式会社 ウェビナー内資料</span>

---

# 4. 背景と目的

1. スマート農業を取り入れて楽を模索したい
2. 今後のためにデータを残していきたい
→ 結果の可視化

---


# 5. ドローン

ドローンにより圃場を撮影し、
撮影できた画像を活用したい

Q：オルソ画像を乗せる

---

## 5.1. 雑草診断

移植後５～７週
　　　～～～Ｑ要確認

Q：画像を載せる

---

### 5.1.1. 期待

* 雑草の分布を知ることで、除草剤散布が可変にできる
  * 使用量を減らせる
    * 経費を減らせる

---

## 5.2. 葉色診断

穂肥判断用

---

### 5.2.1. 期待

* 生育状況を分布を知ることで、穂肥散布が可変にできる
  * 使用量を減らせる
    * 経費を減らせる

---

## 6.7. 導入する上での構成物

![bg fit brightness:0.4](images/DJI_mavic_3.jpeg)

* ドローンセット【自前／レンタル／購入】
  * 本体
  * プロポ
  * バッテリー
  * マイクロSDカード
* ドローン設定、確認用タブレット【自前／レンタル／購入】
※:warning: DJI製の場合、iPad(iPadOS)が必要
* 画像解析用のサービス【購入】
  * 今回使用したアプリ：葉色解析サービス IROHA ※ [参照](https://smx-iroha.com/)

---

# 6. トラクターナビ

以下を使用することで以降のような期待する
- 約1cm精度のGPS
- トラクター向けナビアプリ
- *(いずれは直進アシストハンドルを導入したいなぁ・・・)*


今回使用したアプリ：AgriBus-NAVI ※ [参照](https://agri-info-design.com/agribus-navi/)

![bg fit brightness:0.4 ](images/AgriBus_All.png)

---

## 6.1. 使用中イメージ

![bg 80%](./images/AgriBus_app_using.png)

---

## 6.2. 使用中の期待

* トラクターを運転するときの直進の目安にできる
* 作業した場所が分かる
  * 代掻き等の作業
  * 肥料等の散布

---

## 6.3. 使用後イメージ1

以下のような情報が分かる
1. 作業開始～終了時間
1. 圃場毎の作業面積
1. 圃場毎の作業距離
1. 作業箇所の塗りつぶし状況

![bg right:49% 100%](images/AgriBus_app_task_history1.png)

---

## 6.4. 使用後イメージ2

以下のような情報が分かる
→日／週／月毎
1. 作業圃場数
1. 走行距離
1. 作業面積
1. 作業時間
1. 平均速度
1. 作業軌跡

![bg right:49% 80%](images/AgriBus_app_task_history2.png)

---

## 6.5. 使用後の期待

* 複数人で作業している場合、
  * 作業詳細を共有できる
  * 作業内容の妥当性を検証できる
* 作業内容を蓄積した結果、今までの結果を比較できる

---

## 6.6. 2021スマート農業_福井の例を表示

https://www.maff.go.jp/hokuriku/seisan/smart/forum.html

---

## 6.7. 導入する上での構成物

![bg fit brightness:0.4](images/AgriBus_All.png)

* トラクターに取り付けるアンテナ【レンタル／購入】
* トラクターに取り付けるタブレット／スマホ【自前／レンタル】
※:warning: Android5.0以上 (iPhone不可)
* トラクター位置補正用の基準局【レンタル／購入】
* トラクター位置補正用のデータ転送【無料サービス可】

---

## 6.8. 導入する上での注意点

:warning: AgriBus-NAVIには無料版／有料版がある ※[参照](https://agri-info-design.com/agribus-navi/)
　→無料版の場合、作業履歴が残るのは2日間
:warning: アプリの設定はトラクター毎に必要
:warning: 機材を導入すれば直進アシストも可能 ※[参照](https://agri-info-design.com/agribus-autosteer-lp/)


<strong><span style="font-size: 120%; color: red;">今現在、模索している内容</span></strong>
:warning: トラクター開始位置の目安となる2周内側の場所を知る方法
:warning: 田植え機の場合、田植え開始位置を知る方法

---

# 7. 土壌調査

土壌の傾向を知ることで、今後の肥料散布の参考にする

---

# 8. 質問

- ハウス内の情報を遠隔から知りたいか？

---

# 9. 『提案書構成のコツ』
① 背景と目的
② 潜在課題の仮説
③ 解決策の方向性提示
④ プロダクトの詳細説明
⑤ 期待効果(⇒定量的に記載)
⑥ なぜ自社か(⇒競合優位性)
⑦ 概要スケジュールと予算感
⑧ 全体まとめ(＋留意&前提事項)

---

<table>
<tr><td>№</td><td>色</td><td>値</td>
<tr><td>1<td bgcolor="white">white</td><td>#ffffff</td>
<tr><td>2<td bgcolor="black"><font color=white>black</td><td>#000000</td>
<tr><td>3<td bgcolor="red"><font color=white>red<td>#ff0000
<tr><td>4<td bgcolor="blue"><font color=white>blue</td><td>#0000ff</td>
<tr><td>5<td bgcolor="yellow">yellow<td>#ffff00
<tr><td>6<td bgcolor="green"><font color=white>green<td>#008000
<tr><td>7<td bgcolor="orange">orange<td>#ffa500
<tr><td>8<td bgcolor="pink">pink<td>#ffc0cb
</table>

---

|                        №                        |   色    |  値   |
| :---------------------------------------------: | :-----: | :---: |
|          1<td bgcolor=white>white</td>          | #ffffff |
| 2<td bgcolor=black><font color=white>black</td> | #000000 |
|   3<td bgcolor=red><font color=white>red</td>   | #0000ff |
|  4<td bgcolor=blue><font color=white>blue</td>  | #ffff00 |
|         5<td bgcolor=yellow>yellow</td>         | #ffff00 |
|         5<td bgcolor=yellow>yellow</td>         | #ffff00 |
| 6<td bgcolor=green><font color=white>green</td> | #ffff00 |
| 6<td bgcolor=green><font color=white>green</td> | #ffff00 |
|         7<td bgcolor=orange>orange</td>         | #ffff00 |
|           8<td bgcolor=pink>pink</td>           | #ffff00 |
