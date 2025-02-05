

## Docker とは？

Dockerは、アプリケーションを開発、デプロイ、実行するためのオープンソースのプラットフォームです。Dockerは、アプリケーションをインフラストラクチャから分離することで、ソフトウェアを迅速に提供することを可能にします。コードを迅速にリリース、テスト、デプロイするためのDockerの方法論を利用することで、コードを書いてから本番で実行するまでの時間を大幅に短縮することができます。

Dockerは、開発者やシステム管理者がコンテナを使ってアプリケーションを構築、実行、共有するためのプラットフォームです。コンテナを使ってアプリケーションを展開することをコンテナ化といいます。コンテナは新しいものではありませんが、アプリケーションを簡単にデプロイするために使用されています。

## インストール

### MacOS

1. 次のページからダウンロードとインストールを行います。 [https://hub.docker.com/editions/community/docker-ce-desktop-mac/](https://hub.docker.com/editions/community/docker-ce-desktop-mac/)
2. Docker.dmgをダブルクリックしてインストーラーを開き、Dockerアイコンを「アプリケーション」フォルダにドラッグします。
3. アプリケーションフォルダー内のDocker.appをダブルクリックして、Dockerを起動します。

詳細は https://docs.docker.com/docker-for-mac/install/ をご覧ください。

### Windows

1. 次のページからダウンロードとインストールを行います。 [https://hub.docker.com/editions/community/docker-ce-desktop-windows/](https://hub.docker.com/editions/community/docker-ce-desktop-windows/)
2. Docker Desktop Installer.exe をダブルクリックして、インストーラーを実行します。
3. インストールウィザードの指示に従って、ライセンスの承認、インストーラーの認証を行い、インストールを進めてください。
4. プロンプトが表示されたら、インストールプロセス中にシステムパスワードで Docker Desktop Installer を認証してください。ネットワークコンポーネントのインストール、Docker アプリへのリンク、Hyper-V VMの管理には特権的なアクセスが必要です。
5. セットアップ完了ダイアログで「完了」をクリックし、Docker Desktop アプリケーションを起動します。

Visit [https://docs.docker.com/docker-for-windows/install/](https://docs.docker.com/docker-for-windows/install/) for more information.

### Linux

Dockerは、Ubuntu、Debian、CentOSなどの最も一般的なLinuxディストロ用の.debおよび.rpmパッケージを提供しています。Linuxへのインストールは単純な手順ではなく、パッケージ管理に関する知識が必要です。

詳細は https://docs.docker.com/engine/install/#server をご覧ください。

## Dockerを利用したWordPressへのコントリビュート

多くのWordPressプロジェクトは、Vagrantや他の類似したセットアップよりも簡単で軽量であるため、Dockerの使用に切り替えています。現時点では、WordPress CoreやWordCamp.orgの環境に貢献するためにDockerを使うことができます。

WordPress Core開発用のDockerコンテナのセットアップと使用方法については、https://github.com/WordPress/wordpress-develop をご覧ください。

WordCamp.orgの環境構築のためのDockerコンテナのセットアップと使用方法については、https://github.com/WordPress/wordcamp.org/blob/production/.docker/readme.md をご覧ください。
