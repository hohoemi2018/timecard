# ほほえみタイムカード（timecard）について

合同会社発達支援ほほえみカレッジが事業所に配っているタイムカードアプリです。
公開先は https://hohoemi2018.github.io/timecard/ です。

この `index.html` は直接編集しません。元ファイルは別リポジトリ `hohoemi2018/kinmuhyo` の `_src/hohoemi-src.html` にあり、
勤務表アプリ・合わせたアプリ（`hohoemi2018/kinmuhyo-timecard`）と同じ元ファイルから `_src/build.py` で作り分けています。
直すときは kinmuhyo の `.claude/CLAUDE.md` の手順に従い、kinmuhyo・timecard・kinmuhyo-timecard を同じフォルダに並べて作業してください。

入力データは各事業所のブラウザの localStorage（キー `hohoemi-timecard-v1`）にあります。キーは変えず、以前のデータが読めるようにしてください。
