---
theme : "black"
transition : "default"
---

# MerkDown+reveal.jsでスライド作り 

---

# 自己紹介
<div>
name:櫻井翔太<br>
</div>
<div>
age :20<br>
</div>
<div>
like:観光,食事<br>
</div>
<div>
LT経験:高専カンファレンス<br>
プレゼン経験:全国高専プログラミングコンテスト
</div>

---

## スライド作成と言えば
* MS PowerPoint{.fragment .highlight-current-red}
* Keynote{.fragment .highlight-current-blue}
* Google Slides{.fragment .highlight-current-green}

---

無料でダウンロードできるものもあるが大体有料

--

バージョン管理も大変<br>
(最終修正版ver7.4とか見たくない)

---

## 無料で！簡単に！かっこいい！
## スライドが作りたい！

--

## バージョン管理も
## スマートに行いたい！

--

## プログラミングチックな
## スライド作成…?

---

## 文書作成は
## MarkDownで行いたい！
## (唐突なわがまま)

--

# MarkDownって？

--

## 文書を記述するための
## 軽量マークアップ言語

* 手軽に文章構造を明示できる{.fragment .fade-in-then-semi-out}
* 簡単で、覚えやすい{.fragment .fade-in-then-semi-out}
* 読み書きに特別なアプリを必要としない{.fragment .fade-in-then-semi-out}
* 対応アプリを使えば快適に読み書きできる{.fragment .fade-in-then-semi-out}

---

## MarkDownでスライド作れたら最高では？

--

# reveal.js

--

## HTMLを使用して発表資料を
## 簡単に作成するための
## フレームワーク{.fragment .highlight-red}

--

# 特徴
* Markdown対応 {.fragment .fade-in-then-semi-out}
* ネストしたスライド {.fragment .fade-in-then-semi-out}
* PDFエクスポート {.fragment .fade-in-then-semi-out}
* スピーカーノート {.fragment .fade-in-then-semi-out}
* JavaScript API {.fragment .fade-in-then-semi-out}

---

### こんな感じでかける
#### (1つ前のスライド)

```
# 特徴
* Markdown対応 {.fragment .fade-in-then-semi-out}
* ネストしたスライド {.fragment .fade-in-then-semi-out}
* PDFエクスポート {.fragment .fade-in-then-semi-out}
* スピーカーノート {.fragment .fade-in-then-semi-out}
* JavaScript API {.fragment .fade-in-then-semi-out}
```

--

表も作れる
|  A  |  B  |  C  |
|:----|:---:|----:|
|  ○  |  ×  |  ×  |
|  ×  |  ○  |  ×  |
|  ×  |  ×  |  ○  |

--

画像も使える
![画像](photo.jpeg)

--

<!-- .slide: data-background="#f5deb3" -->
背景色も変えられる

--

javascriptも埋め込める<br>
<input type="text" class="text" id="inp1"></input>
+
<input type="text" class="text" id="inp2"></input>
=
<input type="text" class="text" id="out"></input>
<button type="button" value="計算" onclick="fun_click()"></button>

<script>
function fun_click()
{
    var inp1 = document.getElementById('inp1');
    var inp2 = document.getElementById('inp2');document.getElementById('out').value = inp1 + inp2;
}
</script>

---

# 意識高そう！

---

# 是非使ってみてください！

---

## 終わり

ありがとうございました。