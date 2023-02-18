---
description: flshack = slash hack ( Social Hacking , No Code, Web2.5 )
---

# 👋 Welcome to Flashack

## Overview

## Astar×Slash Bounty Bootcamp Hackathon

### Integrate Slash Web3 payments into Web2 services

> ### **Description**
>
> ・Development of a web service that integrates Slash's API that allows crypto payment to be introduced without any knowledge of Web3, library installation, etc.&#x20;
>
> ・Web3 の知識ゼロ、ライブラリインストール等も一切不要でクリプト決済を導入可能なSlashのAPIをインテグレーションしたウェブサービスの開発。
>
> ー From [AKINDO Hackathons listings](https://app.akindo.io/hackathons/4egraox98uVRBXar)&#x20;
>
> ー Resouces from [slash-fi docs](https://slash-fi.gitbook.io/docs/integration-guide/integration-guide/standard-integration)

> ### Hackathonで評価するポイント
>
> #### 内容
>
> * Slash Web3 Payments の 決済API を インテグレーションしたウェブサービスの開発。
>
> #### 評価ポイント : いずれかを満たせば問題ありません
>
> * サービス内容とクリプト決済の親和性
> * サービスの実用性
>
> ー From [事前オンライン勉強会・資料](https://slash.notion.site/slash/Astar-Slash-Bounty-Bootcamp-Hackathon-6eb234f0260a4052b81c8fd493d320db#36d66c37a7ac4a3080b5eba15c0ce554)

Appendices ：Slash でできないこと（現状）-> Hackason で検討すべきポイント

| 検討項目                                      | 対応要否 | 備考                |
| ----------------------------------------- | ---- | ----------------- |
| クロスチェーンスワップ                               | 不要   | プラットフォームを使えばよい    |
| Gasless 決済                                | 不要   | Fee の安い chain を使用 |
| 決済金額の一時的な預かり（決済したら即加盟店に入金される）             | 不要   |                   |
| 複数トークンをまとめて決済に使う                          | 不要   |                   |
| Slash.extension を WASM で書く                | 不要   |                   |
| ERC20 規格のトークン以外での支払い（BTC, SPL規格などでは支払えない） | 必要   | 将来的には、非常に重要　      |
| 返金をサポートする機能はない                            | 不要   |                   |
| 加盟店受取ウォレットアドレスの自動ローテーション                  | 不要   | Safe Wallet 等にて対応 |
| Reorg等の対応のための複数回にわたるブロック生成確認              | 不明   | 対応保留              |

基本的に、システム外で対応可能なもの、重要度の低いものは、不要と判断。



## 現状分析と方向性

{% content-ref url="overview/analysis/" %}
[analysis](overview/analysis/)
{% endcontent-ref %}

{% content-ref url="overview/our-features.md" %}
[our-features.md](overview/our-features.md)
{% endcontent-ref %}

## Get Started

We've put together some helpful guides for you to get setup with our product quickly and easily.

{% content-ref url="fundamentals/getting-set-up/" %}
[getting-set-up](fundamentals/getting-set-up/)
{% endcontent-ref %}

{% content-ref url="fundamentals/getting-set-up/setting-permissions.md" %}
[setting-permissions.md](fundamentals/getting-set-up/setting-permissions.md)
{% endcontent-ref %}

{% content-ref url="fundamentals/getting-set-up/inviting-members.md" %}
[inviting-members.md](fundamentals/getting-set-up/inviting-members.md)
{% endcontent-ref %}
