# 第六周 
## 5/18

- [] [FE101]
- [] 
- []
- [] week6 homework
- [] 
先看 [FE101] 前端基礎：HTML 與 CSS 這堂課熟悉 HTML 與 CSS，並且練習切版。接著可以看 Chrome 網頁除錯功能大解密來熟悉 Chrome devtool 的使用方式。

如果覺得課程太理論，想要看比較偏實戰的，可以看 Lidemy 上第五期的「第六週特別補充課程：position 與 display 實戰篇 by minw 助教」相關單元，會有各種切版實戰。

若是還有時間，可以透過這兩個小遊戲來熟悉 CSS Selector 跟 Flexbox 排版的方法：

CSS Diner
Flexbox Froggy
如果你覺得切版講得很爛，可以參考看看這個：金魚都能懂的網頁設計入門 - 金魚都能懂了你還怕學不會嗎

1. Zeplin => 設計師跟前端工程師的溝通
2. tinypng tinyjpg 網站縮小圖

3. 學一個東西之前都要先問
	1. 這是什麼 
	2. 為甚麼要用這個
	3. 這要用在哪裡？

1. 網頁到底是什麼？
模板網頁：HTML5UP

```css=

```
# hw1 有用到的屬性及知識
1. HTML 現成的版型 html boilerplate

2. 加上 mata RWD
想要讓原本在桌上型電腦能看的網頁加上 RWD 自適應網站功能時需先加上 meta 語法：
`<meta name="viewport" content="width=device-width, initial-scale=1.0" />`

3. 加上 Nomarliz css
把奇怪的地方初始化
不同瀏覽器



1. 要將 div 或是區塊由水平排列變成 垂直排列的話
```css=
display: flex;
flex-direction: row;  水平排列
<!-- flex-direction: column; 這是垂直排列 -->
```

2. 使用 hover 時，不只點到字才有作用，點到 padding 就框框就有作用。

3. 考慮如果螢幕視窗拉很大，是否真的要在最左跟最右邊，或是設定最大寬度。

4. div 內的元素要致中
```
margin: 0 auto;
```
