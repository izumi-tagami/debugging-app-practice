# debugging-app-practice

## 概要
COACHTECH 教材 Tutorial 10-4「デバッグ ハンズオン演習」で作成した成果物です。
バグが含まれたユーザー登録機能をデバックし、正しく動くように修正しました。

## 使用技術
- PHP 8.x
- Laravel 10.x
- デバッグツール（`dd()`, `dump()`, `Log` ファサード）
（**他に使ったものがあれば追記してください**）

## 学んだこと
- dd()とLog::info()の違い。
- エラーメッセージの読み方。
- Mass Assignment エラーの際の対処方法。

## 動作確認
http://localhost/users/create　にアクセスし、ユーザー登録した際にエラーが発生せずに登録が完了する。
http://localhost/users　に自分で登録したユーザーが表示される。
