# りあれびAI窓口の検討

社内検討資料。GitHub Pages で配信する。

## 検索エンジン対策

`index.html` の `<meta name="robots" content="noindex, ...">` でインデックスを拒否している。
`robots.txt` では Disallow していない。クロールを止めると noindex が読まれず、
他サイトからリンクされた場合にURLだけ登録されることがあるため。

## 注意

**GitHub Pages はリポジトリを private にしてもページは公開される。**
URLを知っている人は誰でも読める。アクセス制限には GitHub Enterprise Cloud が必要。
原価・課金計画を含むので、URLの共有範囲に注意する。

## 更新

`index.html` を置き換えて push すると、1〜2分で反映される。
