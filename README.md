plz-monoeye-cast氏の<a href="https://github.com/plz-monoeye-cast/wlw">WLWブックマークレット+1</a>に、通信エラー対策の修正を加えたものです。<br>
またついでに、筆者が欲しいと思った機能を追加したバージョンも作りました。

通信エラー対策に伴い、データの処理に時間がかかるようになっています。<br>
獲得済みキャスト1体あたり最低1秒は必要です。約1分弱かかるとお考えください。

処理中は特に何の表示も出ませんが、何回もブックマークレットを起動することなくお待ちください。<br>
処理が終われば自動でページの表示が変わります。

(1)monoeye.js<br>
通信エラーの原因箇所のみを修正したもの。
```
javascript:(function(d,s){s=d.createElement('script');s.src='https://cdn.jsdelivr.net/gh/sleptwater/wonder.net-custom@1.1/monoeye.js';d.body.appendChild(s);})(document)
```

(2)sort.js<br>
勝率、勝数、負数の一覧表示を、使用回数順にソートして表示するようにしたもの。
```
javascript:(function(d,s){s=d.createElement('script');s.src='https://cdn.jsdelivr.net/gh/sleptwater/wonder.net-custom@1.0/sort.js';d.body.appendChild(s);})(document)
```

(3)profile.js<br>
Twitter等での自己戦績開示用途を想定し、余計な表示の削除＆使用回数30回未満のキャストを非表示としたもの。
```
javascript:(function(d,s){s=d.createElement('script');s.src='https://cdn.jsdelivr.net/gh/sleptwater/wonder.net-custom@1.0/profile.js';d.body.appendChild(s);})(document)
```


使用方法は本家様と同じです。そちらをご参照ください。<br>
特にAndroid端末でChromeをお使いの方は、ブックマークレットの起動方法に一癖ありますのでご留意願います。

作成時にfork機能を知らなかったため何もforkされていませんが、もちろんplz-monoeye-cast氏のコードの複製から作成させ頂きました。<br>
偉大なる先人達に感謝いたします。

良きワンダーライフを。
