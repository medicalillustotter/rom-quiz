ROM測定 ○×クイズ 完成版

■ファイル
index.html：アプリ本体
data/questions.csv：問題データ
images/：問題画像

■問題を追加・編集
questions.csvを編集します。
列：
id,title,image,basic_axis,moving_axis,answer,explanation

answerは ○ または ×。
imageには例：images/shoulder_flexion.png のように記入。

■GitHub Pages
このフォルダの中身をGitHubリポジトリのルートへアップロードし、
Settings → Pages → Deploy from branch → main / root
で公開します。

※この版はGitHub Pages単体で確実に動く「データ分離型の完成版」です。
Googleスプレッドシートを直接編集画面として使う場合は、公開CSV URLをindex.htmlのDATA_URLに設定する方式にできます。
