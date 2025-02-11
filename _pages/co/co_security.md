---
title: ec-cube.co セキュリティ対策について
keywords: co ec-cube.co クラウド版 セキュリティ対策
tags: [co, ec-cube.co]
permalink: co/co_security
folder: co
---


---

ec-cube.coのセキュリティ対策については、[情報セキュリティ方針](https://www.ec-cube.net/policy/securitypolicy.php){:target="_blank"} を元に、以下を実施しております。  
利用規約に関しましては、[ec-cube.co 利用規約](https://www.ec-cube.co/pdf/term.pdf){:target="_blank"} を参照してください。

## アプリケーションセキュリティ対策

### 監視・モニタリング

以下の監視・モニタリングを行っております。

- 外形監視 (サイトが動作しているか)
- エラー監視 (アプリケーションが正常に動作しているか)
- リソースのモニタリング(メモリ、CPUなど)

### 障害発生時

サイト閲覧が出来ない等の緊急度の高い障害検知時はシステム管理者に通知、対応にあたります。

### バックアップ

アプリケーションファイル、DBダンプのバックアップを定期的に実施しています。

### 定期メンテナンス

- 週次メンテナンスでは、サービスは停止せずにEC-CUBE本体の最新ソースコードなどを反映します。
- 月次メンテナンスでは、サービスを停止しインフラ・ミドルウェアなどの更新を行います。
- 緊急メンテナンスは、緊急事態発生時やイーシーキューブ社が必要と判断した場合に実施します。

## ネットワークセキュリティ対策

### 不正アクセスや攻撃・改ざん対策

WAFによりWebアプリケーションへの攻撃を検知し、攻撃者からのサイトアクセスを遮断し保護しています。

## 開発としての対策

### 個人情報の取り扱い

[個人情報の取扱いについて](https://www.ec-cube.co/pdf/privacy_policy.pdf){:target="_blank"} を参照してください。

### 開発・運用端末

開発・運用端末へのウィルスソフトを導入しており、常に最新化、定期的にウィルススキャンを実施しております。

## 安全にご利用いただく為の対策

### データ通信の暗号化

SSLにより通信を暗号化し、データの盗聴や改ざんを防いでいます。

### アクセス制御

管理画面に対するIP制限機能で実現可能です。

### 決済情報

[オーナーズストア](https://www.ec-cube.net/owners/){:target="_blank"} で提供されている決済プラグインは、クレジットカード情報の非保持化対応済です。
