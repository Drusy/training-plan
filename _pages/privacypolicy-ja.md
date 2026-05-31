---
layout: post
title: プライバシーポリシー
permalink: /ja/privacy/
lang: ja
---

# {{ site.app_name }}
# プライバシーポリシー

## 概要

{{ site.app_name }} は、アスリートが大会を管理し、AIを活用して個別のトレーニングプランを生成できるiOSアプリです。ランニング、サイクリング、水泳、トライアスロンに対応しています。

## 利用するデータ

{{ site.app_name }} は主要機能の提供のため、以下のデータにアクセスする場合があります。

- アスリートのプロフィールデータ（スポーツ種目、経験レベル、任意の体重）
- 大会・競技データ（日程、距離、目標）
- トレーニングプランおよびセッションデータ（プログラム、完了状況）
- 任意のStrava アカウント連携（ユーザーが有効化した場合のみ）
- 任意のローカル通知（ユーザーが許可した場合のみ）

## データの保存方法

すべての大会、プラン、プロフィールデータは端末内にローカル保存されます。  
当社はサーバーを運営せず、個人データを収集・保存しません。

Claude（Anthropic）またはGPT-4o（OpenAI）を選択してプランを生成する場合、プロフィールと目標データが該当プロバイダーのAPIに送信されます。これは各プロバイダーのプライバシーポリシーに準拠します：

- [Anthropic プライバシーポリシー](https://www.anthropic.com/privacy)
- [OpenAI プライバシーポリシー](https://openai.com/privacy)

当社は個人データを販売しません。

## 権限

有効化された機能に応じて、アプリは以下の権限を要求する場合があります。

- 通知権限（毎日のトレーニングリマインダーとセッション通知）
- インターネットアクセス（AIプラン生成および任意のStrava同期）

## サードパーティサービス

**Strava API**（任意。ユーザーが連携した場合のみ）：  
[https://developers.strava.com](https://developers.strava.com)

**Anthropic Claude API**（任意。ユーザーが選択した場合のみ）：  
[https://www.anthropic.com](https://www.anthropic.com)

**OpenAI API**（任意。ユーザーが選択した場合のみ）：  
[https://openai.com](https://openai.com)

**Firebase Crashlytics**（アプリ安定性とクラッシュ診断）

## リソース

本アプリは Apple のシステム UI アセット（SF Symbols）を使用します。  
サードパーティブランドのアセット（例: Strava ボタン）は各ブランドガイドラインに従って使用されます。
