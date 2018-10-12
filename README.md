# テクノロジー（藤原） 10/12課題

- テキストエディタ（Visual Studio Codeなど）でREADME.mdを開きます
- 下の欄（` ``` `で挟まれている部分）に、ChromeデベロッパーツールのConsoleで実行したログを丸ごとコピー＆ペーストしてください

```

```

## 例（下記の書き方をまねてください）

```
-------------------------------------
var numA = 2;
undefined
var numB = 3;
undefined
var numC = numB + numA;
undefined
console.log(numC);
VM339:1 5
undefined
var numD = numA * numB;
undefined
console.log(numD);
VM403:1 6
undefined
-------------------------------------


-------------------------------------
var numA = 1;
undefined
var numB = 2;
undefined
var boolC = numA == numB;
undefined
console.log(boolC);
VM516:1 false
undefined
var boolD = numA < numB;
undefined
console.log(boolD);
VM596:1 true
undefined
-------------------------------------


-------------------------------------
var numA = 1;
undefined
var numB = "1";
undefined
console.log(numA == numB);
VM719:1 true
undefined
console.log(numA === numB);
VM793:1 false
undefined
-------------------------------------


-------------------------------------
var strA = "あなたは";
undefined
var strB = "名人である";
undefined
var strC = strA + strB;
undefined
console.log(StrC);
VM925:1 Uncaught ReferenceError: StrC is not defined
    at <anonymous>:1:13
(anonymous) @ VM925:1
console.log(strC);
VM943:1 あなたは名人である
undefined
-------------------------------------


-------------------------------------
if(numA===1){
    console.log("namAは１です");
}
VM1112:2 namAは１です
undefined
if(numA===2){
    console.log("numAは２です");
}
undefined
-------------------------------------


-------------------------------------

-------------------------------------

```
