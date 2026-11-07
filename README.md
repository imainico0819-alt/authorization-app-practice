# authorization-app-practice

## 概要
COACHTECH 教材 Tutorial 10-3「認可機能 ハンズオン演習」で作成した成果物です。
（認可ロジックをポリシーで定義、コントローラでのポリシー追加、bladeでの@canを使った表示制御）

## 使用技術
- PHP 8.x
- Laravel 10.x
- Policy / Gate（認可）
- Laravel Fortify（認証）

## 学んだこと
- ポリシーの作成、および実装方法
- コントローラーへの$this->authoraze追加
- Bladeへの@canを使った表示制御方法

## 動作確認
http://localhost にアクセスしてログイン

ユーザーA: usera@example.com / password
ユーザーB: userb@example.com / password
それぞれのユーザーでログインし、ログインユーザーの投稿のみが編集・削除できる状態か確認する。
