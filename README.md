# おみくじのゲーム

## ■機能

画面の画像をクリックすると、おみくじの抽選が始まります。もう一回画像をクリックすると、ランダムで引かれたおみくじの画像が表示されます。

## ■主に利用したJavaScript知識

- ページから指定した名前の要素オブジェクトの取得方法： 

    ```javascript
        document.getElementById(idName);
    ```

- 与える範囲のランダム整数の取得方法：
    
    ```javascript
        Math.floor(Math.random() * scope);
    ```

- タイマーの使い方：

    ```javascript
        myTimer = setInterval(function () {
            // 処理
    }, 100); // 空ける時間（ms）
    ```

- 配列の使い方
- 関数の作成及び使い方
- JSでHTMLの画像を入れ替える方法


## ■使用したおみくじの画像
- [おみくじの検索結果 | かわいいフリー素材集 いらすとや](https://www.irasutoya.com/search?q=%E3%81%8A%E3%81%BF%E3%81%8F%E3%81%98)

## ■これから試したいこと

- おみくじを引いた履歴を保存する
-画面に履歴リストを表示する機能を実装する


# 公開サイトのURL
[おみくじdemo](https://kakocode.github.io/omikuji-html/)
