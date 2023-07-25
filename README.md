# nodejs Hello World

nodejsをインストールしたら、とりあえず`hello world` するのが良いんじゃないですかね。

```
console.log('Hello World');
```

今まで、ブラウザのコンソールで散々打ってきた`console.log`から始めましょう。

nodejsにとってのconsoleは、ブラウザのconsoleではなく、お使いのターミナルのことです。

hello.js なんてファイルを作ったら、こうしましょう。

```
node hello.js
```

これくらい簡単なことから始めて動作を確認することが大事だと思います。

## 配列を操作するファイルを作ってみる

arr.js みたいな名前のファイルを作って、その中で適当に配列を定義して、その配列を操作する関数やメソッドを使って、やはり`console.log` しましょう。

例えば、


```
const myArr = [1, 2, 3, 4, 5];

const arrList = myArr.map((n => n * 2));

console.log(arrList);
```

すると、

`[2, 4, 6, 8, 10]`

とか表示されたりします。

