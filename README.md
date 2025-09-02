
# ワークショップLP（GitHub Pages）

このリポジトリは、維持費ゼロ・ノーコード無しで公開できるイベントLPの最小テンプレートです。

## 公開手順（最短）
1. GitHubで新しいリポジトリを作成（例: `sunabaco-workshop`）。
2. このフォルダ内のファイルをそのままアップロード（`index.html` と `styles.css` と `assets/hero.svg` と `event.ics`）。
3. Settings → Pages → Source を `Deploy from a branch`、Branch を `main` に設定。数十秒〜数分で公開URLが表示されます。
4. `index.html` 内の日時・説明・フォームID・SNS共有URLを差し替え。

## 差し替える箇所
- 日時: ヘッダーの `2025-09-06 (土) 13:00–16:00` など
- Googleフォーム: `YOUR_FORM_ID` を自分のフォームIDへ
- SNS共有: `{{URL}}` を公開URLへ
- OGP画像: `assets/hero.svg` をお好きな画像へ（ファイル名とパスはそのままでもOK）

## 画像について
- `assets/hero.svg` はダミーです。差し替え画像は 1200x630 以上推奨（OGP用）。
- 画像ファイルは軽量化（70〜200KB程度）を心がけると表示が速くなります。

## カレンダー追加（任意）
- `event.ics` を修正し、イベント日時・概要を調整してください。サイトからダウンロードできます。
