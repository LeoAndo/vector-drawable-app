# vectorDrawableを利用したサンプル

### 結論
- Android 5.0以上でベクター型ドローアブルをImageView等で利用する場合は、`android:src`で読み込む
- Android 4.0から4.4まではベクター型ドローアブルを`app:srcCompat`で読み込む

### vectorDrawableの扱い方
Android 5.0(API Level 21)から
[ベクター型ドローアブル](https://developer.android.com/guide/topics/graphics/vector-drawable-resources?hl=ja)をサポート。<br>
Android 5.0より古いOSでvectorDrawableを使用したい場合は、[VectorDrawableCompat](https://developer.android.com/reference/androidx/vectordrawable/graphics/drawable/VectorDrawableCompat?hl=ja)を使って下位互換対応させる必要がある<br>
詳しくは、[ここを参照](https://developer.android.com/guide/topics/graphics/vector-drawable-resources?hl=ja#vector-drawables-backward-solution)

### 使用したアイコンのリンク
https://material.io/resources/icons/?icon=adb&style=baseline

### スクショ
| OS 4.4 (Api Level 19) | OS 5 (Api Level 21)
| --- | --- |
| <img src="https://user-images.githubusercontent.com/16476224/105197392-ebcd3300-5b7f-11eb-8a69-83a6d17c7f85.png" width=320> | <img src="https://user-images.githubusercontent.com/16476224/105193929-685e1280-5b7c-11eb-9b47-4641cb465d19.png" width=320> |
