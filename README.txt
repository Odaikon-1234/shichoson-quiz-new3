市町村クイズ 全国版・読み込み不要版

この版は、iPhoneで全国自治体データを外部から読み込む方式ではありません。
GitHub Actionsがlocalgovjpの全国データを取得して data.js を自動生成し、GitHub Pages上で同じサイト内のデータとして利用します。

初回だけ必要な作業：
1. このZIPを展開
2. 中身をGitHubリポジトリのルートへアップロード（.githubフォルダも含む）
3. GitHubのActionsで「Build nationwide municipality data」が成功するのを待つ
4. リポジトリに data.js が自動追加されたらGitHub Pagesを開く

以後、iPhone側では「全国データ読み込み中」という外部データ待ちは発生しません。

対象件数：市772、町743、村189。
市はe-Statの「市772」と合わせるため、政令指定都市20市を別扱いとして除外しています。
