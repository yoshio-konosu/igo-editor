### 📱 iPad Pro 13インチ（デモ）
https://github.com/user-attachments/assets/0ea31589-5fdd-44cd-ae30-b3df07262b3c

### 📱 iPad Pro 13インチ
<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/0e51f84f-81d6-4bcf-9a0f-6818df715b10" width="260" alt="13-inch 1"></td>
    <td><img src="https://github.com/user-attachments/assets/5ad27100-3e76-4810-8989-1a8f385a6d31" width="260" alt="13-inch 2"></td>
    <td><img src="https://github.com/user-attachments/assets/50c2869d-1db2-4cbc-baa5-58617e7b6c6f" width="260" alt="13-inch 3"></td>
  </tr>
</table>

### 📱 iPad Air/Pro 11インチ
<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/8caf4157-a6c5-427b-9cc0-cf89a7dc058d" width="260" alt="11-inch 1"></td>
    <td><img src="https://github.com/user-attachments/assets/7935ce74-d51e-4a32-8b7e-d7b5e950320f" width="260" alt="11-inch 2"></td>
    <td><img src="https://github.com/user-attachments/assets/d931123d-4875-4424-99bf-126f0d094148" width="260" alt="11-inch 3"></td>
  </tr>
</table>

### 📱 iPad mini
<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/e1ffba6b-4b13-46dc-9de9-1be8e3831c04" width="260" alt="mini 1"></td>
    <td><img src="https://github.com/user-attachments/assets/090e4914-22fa-4a6d-a4e3-ad71877fac08" width="260" alt="mini 2"></td>
    <td><img src="https://github.com/user-attachments/assets/0ab52941-294f-4ede-ba4f-d560cbc7bcf4" width="260" alt="mini 3"></td>
  </tr>
</table>

# iGO-editor

# Table of Contents
1. [機能の詳細](#機能の詳細)
2. [プライバシーポリシー](https://yoshio-konosu.github.io/igo-editor/)
3. [コンタクト](mailto:y.konosu.igoeditor@gmail.com)

## 概要
+ 電子版の碁盤と碁石です。（iPad 専用）  
&nbsp; ”iGO editor”		　　：棋譜の編集と保管  
&nbsp; ”iGO editor 保管庫”	：保管した棋譜の再生  
  
## 機能の詳細
### ”iGO editor”　画面の操作説明

`[盤面リセット]`：盤面の石を片付けます。

```text
【石置き】
　Option
	黒　白	：黒石、白石を交互に置きます。	
	黒のみ	：黒石のみ置きます。
	白のみ	：白石のみ置きます。
	移　動	：石を移動させます。	
	削　除	：石を削除します。

【対　戦】
　Option
	[対戦中]　：ルール通りに碁石を置けます。
    　[棋譜を保存]　：手順を棋譜として保管庫に保存します。（作り碁は記録されません。）
    　[訂正(戻る)]　：訂正したい時に使用します。
        [ ◀ ]（1手戻る）：手順を1手だけ後ろに戻します。
        [ ▶ ]（1手進む）：手順を1手だけ先に進めます。
        [確定]　　　　　：表示中の局面まで戻り、対戦を再開します。
        [キャンセル]　　：訂正を中止します。
     [投了]　　　：相手方の中推し勝ちとなります。
     [パス]　　　：石はどこにも打たれずに、相手方の手番となります。

	[作り碁]	：死石をタップし、アゲハマに加算します。確定地をタップすると確定地から外れます。（セキのケースで誤って確定地となっている場合にタップして下さい。）
	[集　計]	：確定地を表示（半透明の石として表示）し、勝敗を判定します。
	
 コミの数値
    5.5　：コミを5目半として集計時計算します。
    6.5　：コミを6目半として集計時計算します。
    7.5　：コミを7目半として集計時計算します。
        上記から選択できます。（選択にない場合は6.5とします）
```

```text
【保管庫】
	[インポート]：アプリ外の棋譜データを取り込みます。

	保存した棋譜やインポートした棋譜が保管リストに表示されます。
	保管リストを選択すると　”iGO editor 保管庫”に移ります。
```

---

### ”iGO editor 保管庫”　画面の操作説明

`[＜戻る]`：”iGO editor”に戻ります。
`[エクスポート]`：アプリ外に棋譜データを保存します。

```text
	作業中	：保管リストの上位に表示されます。
	完　成	：保管リストの下位に表示されます。

	棋譜名	　　　　　　；保管リストに表示する名称。
	詳細・備考　　　　　：内容の説明など、記載は自由。
	コミの数値　　　　　：5.5、6.５、7.５から選択できます。
	クイック棋譜切り替え：選択した棋譜を表示します。
	［この棋譜を削除］：選択されている棋譜を削除します。

	[|◀ ]（最初の手へ戻る）：一瞬で最初（0手目）の状態に戻します。
	[ ▶|]（最終手へ進む）　：一瞬で最新の（最後まで進めた）状態スキップします。
	[ ◀ ]（1手戻る）　　　：手順を1手だけ後ろに戻します。
	[ ▶ ]（1手進む）　　　：手順を1手だけ先に進めます。
	[棋譜コピー]　　　　　：表示中の棋譜（局面）をコピーします。

	手番スライダー：スライダーのツマミを移動させると、該当の手番まで移動できます。
```

  

   


