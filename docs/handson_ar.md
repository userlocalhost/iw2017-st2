# 目的
監視システムからの通知を検知し、NW 機器に対する復旧処理を実施する

![](https://raw.githubusercontent.com/userlocalhost/iw2017-st2/master/docs/images/hanson_ar_01.png)

# 実施内容

## 1. Sensu pack のセットアップ
### 概要
監視システム (Sensu) からの通知を StackStorm が検知するための環境構築を行う

### 実施手順
* sensu pack のインストール
  ```
  $ st2 pack install sensu
  ```
* sensu pack の設定
  ```
  (Note: 具体的な作業手順を記載)
  ```

* sensu handler の登録
  ```
  (Note: 具体的な作業手順を記載)
  ```

* sensu checks の登録
  ```
  (Note: 具体的な作業手順を記載)
  ```

* 動作確認
  ```
  (Note: 具体的な作業手順を記載)
  ```

## 2. Sensu イベントを処理する Rule の作成
### 概要
検知したイベントを検知し、テストコマンドを実行する Rule を作成
(Note: 要図解)

### 実施手順

## 3. napalm pack のセットアップ
### 概要
### 実施手順

## 4. エラー検知から vSRX の AR　
### 概要
(Note: エラーの種類と具体的な AR の内容を考える)

### 実施手順
