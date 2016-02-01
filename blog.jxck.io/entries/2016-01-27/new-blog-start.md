# [web][blog] Blog を移転しました

## intro

長いこと [はてな](http://jxck.hatenablog.com/) をメインにし、他にも [Qiita](http://qiita.com/jxck_) や [Tumblr](http://jxck.tumblr.com/) を使って色々書いて来たけど、そろそろ自分のドメインに全部集約していこうかなと思います。


## motivation

最近ではメディア系は独自のサイトを持つよりも、 Medium やらなんやらでツール経由で流入してもらわないと辛いという話を良く聞くので、その意味では完全に逆行しているかもしれません。

でも、別に PV を稼ぐためにブログを書いているわけでもないので、むしろ技術的にも自分で色々試せる自由な環境で、特定のサービスに依存せずやってみるのも良いかなと。

むしろ、ドメイン自体は結構前に取っていたので、遅すぎるくらいなのですが、やっと重い腰を上げました。

まだ作り途中なので、一気に移行は難しい気もしますが、徐々に作りながらやっていこうと思います。

## sample code

```js
// amp html
((amp) => {
  let ast = parse(fs.readFileSync(path.format(file)).toString());
  ast.children = sectioning(ast.children, 1);
  let filename = path.format({ dir: file.dir, base: `${name}.amp.html` });
  amp.Canonical = path.format({ dir: file.dir, base: `${name}.html` });
  amp.Style = fs.readFileSync("assets/style.css").toString();
  let article = build(ast, date, amp);
  fs.writeFileSync(filename, article);
})(AMP);
```