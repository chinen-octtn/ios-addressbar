#  iOS　15　Safariでアドレスバーの表示を確認するデモ（調整中）

## デフォルトではウインドウ下部のメニューバーとアドレスバーが一体型になっている

* スクロールすると縮小して表示（メニューバーは非表示）
* 上に戻るようにスクロールするとアドレスバーとメニューバーが表示される

## 電池残量や電波状況や時計などが表示されるステータスバー

iOS 15では下記コードで色を指定できる。

```
<!-- headタグ内でmetaタグを使って指定 -->
<meta name="theme-color" content="#ff0000">
```

## フロントエンドのローカル開発環境で表示確認する手順

### 動作確認環境
node v12.16.3
npm v6.14.4

### ローカル開発環境の起動

初回のみ
```
npm i
```

```
npm start
```

2回目以降

```
npm start
```
