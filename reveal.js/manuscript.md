# htmlでプレゼン資料作り！！
## ～パワポよりも自由で簡潔に～

---
## 自己紹介
- 名前：深野大我
- 出身：埼玉県熊谷市
- 年齢：24歳
- 職種：コーダー
- 趣味：サバゲー、ドライブ、動画編集

---
## プレゼン資料作成ライブラリについて
---
### パワポじゃだめなの？

 * htmlで作るのでブラウザで見れる
 * 公開&共有しやすい
 * markdownを用いるので、htmlの実装も簡単
 * cssやjsでデザインや動きの調整も可能

---
## ライブラリの種類
---
### Remark
 https://github.com/gnab/remark

 <a href="http://remarkjs.com/" target="_blank"><img src="img/img_remark_cap.png" alt=""></a>

>>>
### 特徴

#### 長所
 * サーバを立てずにローカルでスライドを表示できる
 * シンプルな資料作りに向いている

#### 短所
 * 1方向にしか作れない
 * スタイルはcssを使い初めから自力で調整する必要がある

---
### Reveal.js
https://github.com/hakimel/reveal.js/

 <a href="http://lab.hakim.se/reveal-js/#/" target="_blank"><img src="img/img_reveal_cap.png" alt=""></a>

>>>
### 特徴

#### 長所
 * chromeでPDF化できる
 * 2方向のスライドを作ることができる
 * 豊富なスタイルがあらかじめ用意されている
 * markdownとhtmlを1つのhtmlソースで併用できる

#### 短所
 * markdownで簡略化できるとはいえ、htmlマークアップ量が他より多くなるので、調整の手間が多い
 * 図や表、アニメーションを使う場合、htmlとmarkdownを両方記述しなければいけない

---
### Cleaver
https://github.com/jdan/cleaver

 <a href="http://jdan.github.io/cleaver/" target="_blank"><img src="img/img_cleaver_cap.png" alt=""></a>

>>>
### 特徴

#### 長所
 * コマンド `npm install cleaver` 1行でインストール可能
 * デザインテンプレートを選べる

#### 短所
 * node.jsをインストールしていないとそもそもインストールできない
 * mdファイルを編集するたびに、コマンドでhtmlに変換する必要がある

---
## このプレゼンで使用したライブラリは

### Reveal.js
- - -
#### -なぜなら-
 * 2方向にスライドを作ることが出来るので、段落ごとにまとめやすい
 * 3次元的な動きを実装出来るので、「プレゼンで魅せること」に一番適していると判断

---
## 余談
---
### Swipe
 <a href="https://www.swipe.to/" target="_blank"><img src="img/img_swipe_cap.png" alt=""></a>
>>>
### 特徴

#### 長所
 * テンプレートやフォントがあらかじめ用意されている
 * レスポンシブデザインに対応
 * パワポのようにドラッグ&ドロップでスライドを簡単にインポートできる
 * 工数が手軽

#### 短所
 * 用意してあるフォントの種類が少ない
 * 独自にcssを指定できない為、ライブラリのように細かい調整ができない

---
##ご清聴、ありがとうございました！