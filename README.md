# 江戸時代検定 LINE Bot

## 概要
戦国時代に関する知識を試す検定を実施するLINE Botです。全10問の質問に答えることで、戦国時代に関する知識をテストすることができます。

## システム構成
- フロントエンド: LINE Messaging API
- バックエンド: GAS
- データベース: LINE Platform
- ![image](https://github.com/user-attachments/assets/efcff4c9-d210-496b-afe0-406cad4ce20b)


## 主な機能
- 江戸、明治、安土桃山時代に関する10問の検定実施
- 各問題に対する選択式回答
- 回答後の正誤判定
- 最終スコアの表示


https://github.com/user-attachments/assets/3d743e1e-ef53-4a03-bae3-57d1d3dd28a0




以下のリンクを参考にAPIをつなげた
https://developers.line.biz/ja/docs/messaging-api/overview/
### 環境変数やコマンド一覧
CHANNEL_ACCESS_TOKEN　　各チャネル（公式ライン）ごとに与えられるトークン
