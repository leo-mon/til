イベントドリブンにJavascriptを働かせるには
1. タグ内の属性として宣言
```Javascript
<TAGNAME onEVENTNAME=CODE>
```
2. 要素オブジェクトのプロパティとして宣言
```Javascript
OBJ.onEVENT = function() {STATEMENT}
```
3. addEventListenerメソッドで宣言
```Javascript
ELEM.addEventListener(type, listener, capture)
```
