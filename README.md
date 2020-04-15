plz-monoeye-cast氏の<a href="https://github.com/plz-monoeye-cast/wlw">WLWブックマークレット+1</a>に、通信エラー対策の修正を加えたものです。<br>
またついでに、筆者が欲しいと思った機能を追加したバージョンも作りました

通信エラー対策に伴い、データの処理に時間がかかるようになっています。<br>
開放済みキャスト1体あたり最低1秒は必要です。何回もブックマークレットを起動せず、気長にお待ちください。

(1)monoeye.js<br>
通信エラーの原因箇所のみを修正したもの。<br>
javascript:(function(d,s){s=d.createElement('script');s.src='https://cdn.jsdelivr.net/gh/sleptwater/wonder.net-custom@/monoeye.js';d.body.appendChild(s);})(document)

(2)sort.js
勝率、勝数、負数の一覧表示を、使用回数順にソートして表示するよう修正したもの。

(3)profile.js
Twitter等での自己戦績開示用途を想定し、余計な表示の削除＆使用回数30回以下のキャストの非表示としたもの


使用方法は本家様と同じです。そちらをご参照ください。
