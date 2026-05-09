# AtcoderをHaskellでがんばるリポジトリ

## 前提

- nix
- direnv

など

## 環境構築

初回のみ`direnv allow`

## 使い方

```
# コンテストの雛形作成
acc new abc400
cd abc400/a

# サンプルケースをダウンロード
oj download https://atcoder.jp/contests/abc400/tasks/abc400_a

# コードを書く...

# テスト
oj test -c "runghc main.hs"

# 提出→自動提出は使えない
```
