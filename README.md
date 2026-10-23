# もっとよくみる｜学校に行く

「大変よく頑張りました展」の3D体験（学校版・7つの発見ルート）を GitHub Pages で公開するリポジトリです。

## 公開方法（ZIPを解凍しなくてOK）

1. [GitHubのアップロード画面](https://github.com/hinakooooooooo/motto-yoku-miru-school/upload/main)で `motto-yoku-miru-school-github-pages-easy.zip` を**解凍せずに**アップロードして **Commit changes** を押します。
2. [Settings → Pages](https://github.com/hinakooooooooo/motto-yoku-miru-school/settings/pages) に移動し、**Build and deployment → Source を「GitHub Actions」** に設定します。
3. [Actions](https://github.com/hinakooooooooo/motto-yoku-miru-school/actions)で `Publish school exhibition` が正常終了したら、[公開サイト](https://hinakooooooooo.github.io/motto-yoku-miru-school/)を開きます。

ワークフローはZIPの中身を展開し、GitHub Pagesへアップロードします。元のAstra ZIPや従来のGitHub用ZIPでも、`index.html` がZIPの直下または `dist/` にあれば自動判別して展開します。複数のZIPは混ぜず、原則として公開したい版のZIPを1つだけ置いてください。

## 公開サイト

https://hinakooooooooo.github.io/motto-yoku-miru-school/

## 内容

学校へ行くことの中にある、見落とされがちな7つの頑張りを虫眼鏡と3Dの小世界で発見する展示です。
