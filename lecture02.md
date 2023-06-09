# 2023年5月度第2回課題
## 講座での学び

**SVN(SubVersioN)について：**
- バージョン管理システムであり、最近はあまり使われていない。
- 集中型リポジトリのため有事の際、バージョン履歴は吹き飛ぶがスナップショット機能により復元は容易。
- Gitのような柔軟性はない分、操作が容易で学習コストが低い。
- 日本では昔から使われているため、現場によってはSVNしか利用していないケースもある。

**Gitについて：**
- 現在主流となっているバージョン管理システムで、分散型リポジトリである。
- リモートリポジトリからデータを複製し編集(clone)することで、T&Eが気軽い。
- 定期的にリモート側に反映(push)する必要がある。
- チェンジセットを保存する形式によりスピーディな開発が可能。
- 特定の変更点から分岐(ブランチ)したり統合(マージ)することができる。
- マージの前にレビュー依頼(プルリクエスト)を出す。

**GitHubについて：**
- Gitホスティングプラットフォームで、多数のリポジトリサービスが存在し世界的に利用されている。
- 基本的にはGitと同じ開発手順である。
- イシュートラッキングシステムを提供し、バグや機能リクエストなどの問題が管理しやすい。
- 複数人がわかりやすいようなリポジトリ名の作成やファイル変更数が少なくなるようにブランチを切ること求められ$
- チームでの作業をサポートし、複数の開発者が同時にリポジトリにアクセスすることができる。
