# web-bootcamp-practice

# CSS セレクタの基本練習

このリポジトリは、CSSの基本的なセレクタを練習するためのサンプルコードです。  
ユニバーサルセレクタ、要素型セレクタ、セレクターリストの使い方を学びます。

---

## 🔧 使用しているCSSセレクタ

✅ ユニバーサルセレクタ（`*`）
すべての要素に背景色 `cyan` を適用します。

```css
* {
    background-color: cyan;
}


✅ 要素型セレクタ（button）
ページ上のすべての <button> 要素のフォントサイズを 30px に設定します。

css
コピーする
編集する
button {
    font-size: 30px ;
}
✅ セレクターリスト（h1, h2）
<h1> および <h2> の文字色を darkslateblue に設定します。

css
コピーする
編集する
h1, h2 {
    color: darkslateblue;
}

