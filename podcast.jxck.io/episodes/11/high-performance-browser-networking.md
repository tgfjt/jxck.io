# #11 High Performance Browser Networking

<audio preload=none controls src=http://files.mozaic.fm/mozaic-ep11.m4a></audio>


## Theme

第 11 回目のテーマは High Performance Browser Networking です。

今回は HPBN の著者であり、 Google の Developer Advocate である [@igrigorik](https://twitter.com/igrigorik/) さんとをお迎えして実施しました。この書籍のちょっと遅れた出版記念イベントとして [HPBN-meetup](http://t.umblr.com/redirect?z=http%3A%2F%2Fgoogledevjp.blogspot.jp%2F2014%2F10%2Fblog-post.html&t=MmY0ODgzODQ5NDIyYTI3ODE1YzU2MTI3YjE0OTNkMWZkNzMxMTI0YSxNNk5KM3NVNA%3D%3D) で実施したインタビュー形式の公開収録の模様を配信します。今回は Google さんに通訳をつけて頂きましたので、その分ラグや lost in translation がありますが、ご了承ください。

[High Performance Browser Networking](http://t.umblr.com/redirect?z=http%3A%2F%2Fchimera.labs.oreilly.com%2Fbooks%2F1230000000545&t=MTAyNjg5OGQzODVlMWRkZDYwNTEzOGE3MGJjYzUzMDllNmMwMzg1MCxNNk5KM3NVNA%3D%3D)は、複雑化し知らなくてはならい知識が飛躍的に増えた Web の世界でのネットワークに関わる知識について、幅広く詳細に解説した Web エンジニア必携の一冊です。

インタビューでは Ilya はいったいどういうエンジニアで、何故この本を執筆したのか。この本以降でのアップデートや、 Ilya 自身の見る「これからの Web」について、何がおこっているのか？、これからどうなっていくのか？をお聞きしました。

別途 [Qiita で募集した質問](http://t.umblr.com/redirect?z=http%3A%2F%2Fqiita.com%2FJxck_%2Fitems%2Fa0cea350cc982915d092&t=OWIzYTViMTkwZTA3MDc5OWZlZTVmOGY0OTNhZDBiNzVhMGU5MjRhNixNNk5KM3NVNA%3D%3D) も一部採用させていただきました。応募頂いた皆様ありがとうございました。

エピソードの感想などは、 [#mozaicfm](https://twitter.com/search?q=mozaicfm&src=hash) までお願いします。


## Guest

- [@igrigorik](https://twitter.com/igrigorik)


## Show Note

- [Ilya Grigorik](http://t.umblr.com/redirect?z=https%3A%2F%2Fwww.igvita.com%2F&t=MjZmN2NkNDBkMTgzYzQ3YTQ3NWY3N2IzNmNkYTgyZTk2Yzc5YTY5NSxNNk5KM3NVNA%3D%3D)
- [High Performance Browser Networking](http://t.umblr.com/redirect?z=http%3A%2F%2Fchimera.labs.oreilly.com%2Fbooks%2F1230000000545&t=MTAyNjg5OGQzODVlMWRkZDYwNTEzOGE3MGJjYzUzMDllNmMwMzg1MCxNNk5KM3NVNA%3D%3D)
- [High Performance Browser Networking Meetup (togetter)](http://t.umblr.com/redirect?z=http%3A%2F%2Ftogetter.com%2Fli%2F741422&t=MzRlMGM2MmIzNjg0OTBhOTc5NWQyMjM0OGU0MjZlNDc1MzM3OGU3MCxNNk5KM3NVNA%3D%3D)
- [Make the Web Faster](http://t.umblr.com/redirect?z=https%3A%2F%2Fdevelopers.google.com%2Fspeed%2F&t=NzBmZjA3YzFjN2FiN2Y3Yjk2NzBhNjBmMTNkNjc4MGEwZWU3ZTJkZCxNNk5KM3NVNA%3D%3D)
- ([この辺の連載](http://t.umblr.com/redirect?z=http%3A%2F%2Fhtml5experts.jp%2Fjxck%2F1415%2F&t=Y2RmNWVhZDljNjk0YWNjMTY4MTJhMWU5Y2YxODU0M2NjNDRiNTMwMyxNNk5KM3NVNA%3D%3D) をしていたので彼の業績はずっと追っていた)
- [以前彼がいた PostRank](http://t.umblr.com/redirect?z=http%3A%2F%2Fen.wikipedia.org%2Fwiki%2FPostRank&t=ZmFhMWM4MTlkM2FmNzk5MzRkYjgwY2Y0NGU4MTRhYjFjN2E1ZDU4YSxNNk5KM3NVNA%3D%3D)
- [Ruby Kaigi 2009 でやはり High Performance Networking について登壇している](http://t.umblr.com/redirect?z=http%3A%2F%2Frubykaigi.org%2F2009%2Fja%2Ftalks%2F18M04&t=YjQwOWU4MzNkZTg3YTVlNTE3OTliOGUzZjY3OTE3ZjNiOWVjODI3ZSxNNk5KM3NVNA%3D%3D)
- [WebP も Make the Web Faster の一つ](http://t.umblr.com/redirect?z=https%3A%2F%2Fdevelopers.google.com%2Fspeed%2Fwebp%2F&t=YzFmOTEzNGUyZTAwZTk3YTZhNmU2Mjk5NTM1NzI0Zjg5MDg5ZDI5MixNNk5KM3NVNA%3D%3D)
- [最近 Ilya は HTTPS の啓蒙もしている](http://t.umblr.com/redirect?z=https%3A%2F%2Fwww.google.com%2Fevents%2Fio%2Fschedule%2Fsession%2F84d2d68d-a2bc-e311-b297-00155d5066d7&t=NzEyN2E3ZDIyYjg5YjEyMTM0ZjQ3YzZkNjQ2OTZlOGEwYTgyODhlMSxNNk5KM3NVNA%3D%3D)
- [もとは SPDY の薄い本だった!?](http://t.umblr.com/redirect?z=http%3A%2F%2Fwww.chromium.org%2Fspdy&t=YjZkOWI5NzRlOWE2YTBiNWQ5ZjVjOTJhZmQ2MjcwMjcxN2NkYWQ4NCxNNk5KM3NVNA%3D%3D)
- [SPDY について書くと、どんどん分厚くなるの、分かります](http://t.umblr.com/redirect?z=http%3A%2F%2Fjxck.hatenablog.com%2Fentry%2F20130620%2F1371728186&t=YTVhMTU0ZTYwZDFhNjQ2MTY3NzM3YjZjZTI1ZWUyMjgwY2Q4NjhjYixNNk5KM3NVNA%3D%3D)
- [WebRTC](http://t.umblr.com/redirect?z=http%3A%2F%2Fwebrtc.org&t=MjI1NWUyMmNlMWFlZTYwYjcwYjNhMjYwNzBjNDJjMDk1ZjYwZTFjYixNNk5KM3NVNA%3D%3D)
- [ORTC](http://t.umblr.com/redirect?z=http%3A%2F%2Fortc.org&t=MGFjZmM3Y2QyNWMyOWI2Yjc1NDFlMDg4YjliMGYwYzlmN2I1MTVlNSxNNk5KM3NVNA%3D%3D)
- [WebRTC を支えるマイナーなプロトコル SRTP/DTLS/SCTP を分かった気になる](http://t.umblr.com/redirect?z=http%3A%2F%2Fwww.slideshare.net%2Fiwashi86%2F20140801-web-rtcmeetup3r3&t=N2RlYzE5NWRmNWFmYWQyMjllNTc2NDcyMmNjNTZiY2ZhYTU2OWRkMyxNNk5KM3NVNA%3D%3D)
- [HPBN の 2 章はまるっと無線の話](http://t.umblr.com/redirect?z=http%3A%2F%2Fchimera.labs.oreilly.com%2Fbooks%2F1230000000545%2Fpt02.html&t=NzYzNGMyMmQ5MjJmYzRlZGNkYjMyMTBjNWE3MmE4MGQ1YmYzNmMwZixNNk5KM3NVNA%3D%3D)
- [Stream API](http://t.umblr.com/redirect?z=https%3A%2F%2Fstreams.spec.whatwg.org%2F&t=NzM4NzQ0NTRiZjZkNTZlZGQxMDg0MjVlZjRlM2EzZGM3Yjk2ZWJiZCxNNk5KM3NVNA%3D%3D)
- [Fetch API](http://t.umblr.com/redirect?z=https%3A%2F%2Ffetch.spec.whatwg.org%2F&t=ZWViNmMwZjgyMTNiOWUxOWNkYzdjOGEwNjA1NTgzYzZjZWNhMWEwNyxNNk5KM3NVNA%3D%3D)
- [Service Worker](http://t.umblr.com/redirect?z=http%3A%2F%2Fwww.w3.org%2FTR%2Fservice-workers%2F&t=NTM5ZWRjZmU0OGExM2MwZGI5NjgxN2I2MDM2OTM3N2YzZDEwMmJkNixNNk5KM3NVNA%3D%3D)
- [Server Sent Events](http://t.umblr.com/redirect?z=http%3A%2F%2Fwww.w3.org%2FTR%2Feventsource%2F&t=ODhhNTJmODZiOGE1NjIxMmQ2OWJmOTM1NGZhMzZhNTExZGMwODk5OSxNNk5KM3NVNA%3D%3D)
- [QUIC](http://t.umblr.com/redirect?z=http%3A%2F%2Fwww.chromium.org%2Fquic&t=MTAzYzU0YmQ4NDA4M2M0NzE4Mzk1MzljZTYxZjAwODk1MWFkY2Q4YSxNNk5KM3NVNA%3D%3D)
- [HTTP/1.1 での最適化をまとめた High Performance Web Site](http://t.umblr.com/redirect?z=http%3A%2F%2Fshop.oreilly.com%2Fproduct%2F9780596529307.do&t=ZGQ5OGI4NmQ1ZWQ4NjhiODRiZjI4MzRlZjQ2OGUxMGI1Yjk3YjAzNCxNNk5KM3NVNA%3D%3D)
- [「IPv6 で TLS の普及が進むの」補足](https://twitter.com/igrigorik/status/529812386912288769)
- [Google の光ファイバープロジェクト](http://t.umblr.com/redirect?z=https%3A%2F%2Ffiber.google.com%2Fabout2%2F&t=MmQyNTkwZmNjZWVmZTUwMWFmYjNlNGJmZTI5YmI5NmE3MDg3YjExYyxNNk5KM3NVNA%3D%3D)
- [気球で無線 LAN エリアを増やすプロジェクト](http://t.umblr.com/redirect?z=http%3A%2F%2Fwww.google.com%2Floon%2F&t=ODZkZTI5N2MwYTMxMDU5ZDI1YjhiZjFmOTIyMjgwZWY2YTdhNTZkYSxNNk5KM3NVNA%3D%3D)
- [Frame Timing API](http://t.umblr.com/redirect?z=https%3A%2F%2Fw3c.github.io%2Fframe-timing%2F&t=MTcwOTYwOGJjYzY5Njk5NmIwZmJhZTI5MzVhZGMyMTcxYjRjNDIyYixNNk5KM3NVNA%3D%3D)
- [Delta Encoding(差分エンコーディング)](http://t.umblr.com/redirect?z=https%3A%2F%2Fgithub.com%2FGoogleChrome%2Fdelta-encoding&t=NTZkNWEzYjE2YTI0NTQ4NDc0YTU4YTJiZmM1ZjcyZmNjNWY0OGMwMixNNk5KM3NVNA%3D%3D)
- [この前日の HTTP2 Conference にも出てもらいました](http://t.umblr.com/redirect?z=http%3A%2F%2Fhttp2study.connpass.com%2Fevent%2F9209%2F&t=ZWJjMjEzODViY2YxYmQ0OTA1ODIwYWZjY2UwYWI4NjNkN2VkYjI2MCxNNk5KM3NVNA%3D%3D)