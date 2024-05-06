# スキルシート・技術スタック

<!-- textlint-disable -->
名前: 渡邊　泰紀 （わたなべ　たいき）

*a.k.a: yasunori0418*
<!-- textlint-enable -->

## 目次

- 使える言語・ツール
  - できる（実務での使用経験と多少の自身有り）
  - 少しできる（実務経験はあるが、調べながら使える程度）
  - 勉強中（今後伸ばしていきたいスキル・技術）
- 使用しているツール・OSなど
- 個人活動のまとめ
  - OSS活動
  - 登壇経験
  - 技術記事

## 使える言語・ツール

### できる（実務での使用経験と多少の自身有り）

- Linux
  - 日常的に使用中
- Bash & Makefile
  - 上記のLinuxを日常的に使用する中で、さまざまなところで利用
  - チームの開発環境構築ツールの1つとして提供した経験有り
- Git
  - 基本的な操作から、簡単なrebase操作まで可能
  - GitHubを普段利用
  - 現在の職場では自己ホスティングのGitLabを使用
- Docker/docker-compose
  - 開発環境整備の一環で、いくつかのプロジェクトの開発基盤を作成
- TypeScript
  - Denoを使用したVimプラグイン開発
  - 自身のVimの設定にも活用
- Python
  - SQLAlchemy
  - FastAPI
  - Pydantic
    - 上記のライブラリを使用して、リプレイス等の実務開発の経験有り
  - pytest
    - 新規実装やリプレイスしたアプリケーションのテストコード実装経験有り
- Ruby
  - 古い社内システムでRuby on Railsに触れた経験有り
  - 新しい言語仕様やフレームワークについては詳しくはありません
- RDBMS
  - MySQL
    - 1億レコードのテーブル移行作業の経験有り
    - 移行作業に合わせて、Alter文と同等のプロシージャを作成
  - Oracle

### 少しできる（実務経験はあるが、調べながら使える程度）

- AWS
  - VPC EC2
    - 簡単な構成のEC2インスタンス立ち上げであれば、一人称で構築可能
  - Lambda
    - テスト用のAPIをPythonで実装
  - CloudWatch
    - 上記Lambdaのテスト監視に使用
  - CloudFormation
    - 実装途中のLPサイト自動生成機能を完成させました
    - 01での開発経験は無し
- PHP
  - 社内の記事管理CMS開発の経験有り
  - 社内へ向けた自主制作の独自モジューラブルCMSの設計と仮実装
- Perl
  - 古いシステムでPerl/CGIに触れた経験有り
- Apache

### 勉強中（今後伸ばしていきたいスキル・技術）

- Go
  - 小さな修正だが、GitHub-CLIへのPR作成経験有り
- Rust
  - 人気になっているため、今後のスキルセットとして興味有り
- AWS
  - 複雑な設計や提案ができるようなことを目標
- Terraform
  - IaCによる羃等性のあるインフラ構築に興味有り

## 使用しているツール・OSなど

- Git GitHub/GitLab
- Vim/Neovim
  - 2021年7月からメインエディタとして使用
  - 現在はNeovimをメインとして使用
- Linux
  - 個人開発のOSとして2021年からメインで使用
  - 現在はArch Linuxをメインとして使用
- zsh
  - 開発用のOSをLinuxにしたのと同時にメインのシェルとして使用

## 個人活動のまとめ

### OSS活動

普段から使用するVimのプラグインに対して、修正や機能追加のPRを作成した経験があります。
代表的なOSS活動として、GitHub-CLIにPRを作成し[v2.46.0](https://github.com/cli/cli/releases/tag/v2.46.0)でリリースされています。

### 登壇経験

Vimに関するイベント内で何度か登壇した経験があります。

<!-- textlint-disable -->
- [2023年6月30日 ゴリラ.vim](https://gorillavim.connpass.com/event/283937/)
  - [設定をluaに書き直した](https://docs.google.com/presentation/d/1tOa4l5L2hHAYC7tXq0Y9DWvDmvQ9fLxKBPHr5XyBcAI/edit?usp=sharing)
  - 初のイベント登壇
- [VimConf 2023 Tiny 懇親会LT](https://vimconf.org/2023/)
  - [vimを切っ掛けにエンジニアになった話](https://zenn.dev/vim_jp/articles/0002-engineer_with_vim)
  - 当日、懇親会LTに登壇し、その時書き上げた内容を記事化しました
- [2024年2月10日 ゴリラ.vim](https://gorillavim.connpass.com/event/307622/)
  - [設定をすることは自由の象徴](https://docs.google.com/presentation/d/1XHrsRwUkwbXf4nFyhjVxoOEKMuhvmQRBqOoEH3vfgZs/edit?usp=sharing)
  - 当日、登壇者の欠員が出たため、急遽LTに参加しました
<!-- textlint-enable -->

### 技術記事

主にVimに関する記事を中心に、Zennをメインに記事を投稿しています。
過去にはQiitaにも記事を投稿しています。

- [Zenn](https://zenn.dev/yasunori_kirin)
- [Qiita](https://qiita.com/yasunori-kirin0418)
