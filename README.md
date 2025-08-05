# Redmine on Render

このテンプレートをGitHubに公開してRenderに連携するだけで、Redmineが自動デプロイされます。

## 手順

1. GitHubで新規リポジトリを作成（このテンプレートを貼り付け）
2. Render にログインし「Create Web Service」からリポジトリを選択
3. Database→New→PostgreSQL（またはMySQL）を作成（名前を `redmine-db` にするのが推奨）
4. deploy すると自動で起動
5. 提供された URL にアクセス → 初期 `admin/admin` でログイン可能
