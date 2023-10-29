# 設計

## 概要

### DDD の目的

1. 機能性を高めること
   システムとして使えるものを作るため.

2. 保守性を高めること
   長期運用、開発しても機能拡張が容易であるため。

### モデリングの方法

モデリング手法の一つとして「sudo モデリング」というものがある。DDD 設計する上で大体以下の 4 つの図を最低限書いておいたら良いというもの。

- s
  - システム関連図
- u
  - ユースケース図
- d
  - ドメインモデル図
- o
  - オブジェクト図

## ドメインモデル図の作成手順

### 集約とは