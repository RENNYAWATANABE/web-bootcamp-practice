# web-bootcamp-practice

# CSS セレクタの基本練習
このリポジトリは、CSSの基本的なセレクタを練習するためのサンプルコードです。  
ユニバーサルセレクタ、要素型セレクタ、セレクターリストの使い方を学びます。

## 🔧 使用しているCSSセレクタ
✅ **ユニバーサルセレクタ（`*`）**
すべての要素に背景色 `cyan` を適用します。
```css
* {
    background-color: cyan;
}
```

✅ **要素型セレクタ（button）**
ページ上のすべての <button> 要素のフォントサイズを 30px に設定します。
```css
コピーする
編集する
button {
    font-size: 30px ;
}
```

✅ **セレクターリスト（h1, h2）**
h1 および h2　の文字色を darkslateblue に設定します。
```css
コピーする
編集する
h1, h2 {
    color: darkslateblue;
}
```
    
✅ **IDセレクタ（`#signup`）**
特定のID（例: `<div id="signup">`）を持つ要素の文字色を白、背景色を darkslateblue に設定します。
```css
#signup {
    color: white;
    background-color: darkslateblue;
}
```

✅ **クラスセレクタ（`.tag`） **
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
```

✅ **隣接セレクタ（h2 + button）**
同じ親要素内で (h2) の直後にある <button> 要素のフォントサイズを20pxにします。
```css
h2 + button {
    font-size: 20px;
}
```

✅ **直下セレクタ（footer > a） **
(footer) の直下にある (a) 要素の文字色を aqua にします。
```css
footer > a {
    color: aqua;
}
```
    
✅ **属性セレクタ （`input[type="password"]`、`a[href*="google"]`）**  
特定の属性を持つ要素を選択できます。  
例：`type="password"` の `<input>` 要素の文字色を greenyellow に、  
`href` 属性に "google" を含む `<a>` 要素の文字色を magenta に設定します。
```css
input[type="password"] {
    color: greenyellow;
}
a[href*="google"] {
    color: magenta;
}
```

✅ **疑似クラスセレクタ（`:hover`, `:active`, `:nth-of-type`）**  
要素の特定の状態にスタイルを適用できます。  
例：`.post` クラス内の `<button>` をホバーしたときやクリック中、  
2番目ごと（偶数番目）の `.post` 要素に背景色を適用します。
```css
.post button:hover {
    background-color: red;
    color: aliceblue;
}

.post button:active {
    background-color: aqua;
}

.post:nth-of-type(2n) {
    background-color: aliceblue;
}
```

✅ **疑似要素セレクタ（::first-letter, ::first-line, ::selection）**
要素の一部だけにスタイルを適用できます。
```css
h2::first-letter {
    font-size: 50px;
}
p::first-line {
    color: purple;
}
p::selection {
    background-color: orange;
}
```

✅ **!important**
!important を使うことで、他の指定よりも強いスタイルを適用できます。
```css
button {
    background-color: magenta !important;
}
```





