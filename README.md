# firefox-addons

自作Firefoxアドインの配布・自動更新用リポジトリ

## アドイン一覧

| アドイン | update_url |
|---------|------------|
| img2tab | https://yoshiaki21.github.io/firefox-addons/img2tab/updates.json |
| save-in | https://yoshiaki21.github.io/firefox-addons/save-in/updates.json |

## 更新手順

1. 各リポジトリで `web-ext sign` を実行
2. 生成された xpi をコピー
3. updates.json のバージョンを更新
4. git push → GitHub Pages に自動反映
