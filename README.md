# web-bootcamp-practice

# CSS セレクタの基本練習
このリポジトリは、CSSの基本的なセレクタを練習するためのサンプルコードです。  
ユニバーサルセレクタ、要素型セレクタ、セレクターリストの使い方を学びます。

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

✅ **IDセレクタ（`#signup`）**  
特定のID（例: `<div id="signup">`）を持つ要素の文字色を白、背景色を darkslateblue に設定します。
```css
#signup {
    color: white;
    background-color: darkslateblue;
}
```

✅ **クラスセレクタ（`.tag`）**  
クラス名 `tag` を持つ要素の背景色を赤、文字色を白、フォントサイズを16pxに設定します。
```css
.tag {
    background-color: red;
    color: white;
    font-size: 16px;
}
```

✅ **子孫セレクタ（`.post a`）**  
クラス名 `post` の中にあるすべての `<a>` 要素の文字色を yellowgreen、下線を消し、太字にします。
```css
.post a {
    color: yellowgreen;
    text-decoration: none;
    font-weight: 700;
}














