# ToPu_LockLockTool
#### 3Dビュー上で [オブジェクトの選択可否／編集モードでの頂点ロック] ショートカットでサクッと切り替え！

![ToPu_LockLockTolls](https://github.com/user-attachments/assets/f2cf00fb-0a98-47d0-853e-2c7bb2946127)

## 入手方法
最新版は[Code > Download ZIP](https://github.com/http4211/ToPu_LockLockTool/releases) または Dev ブランチから ZIP ファイルをダウンロードしてください。

## 機能
#### オブジェクトモードでの動作

<p>&nbsp;&nbsp;・アドオンショートカットで　選択/選択外　のオブジェクトをロック（選択不可）できます。このとき自動的に半透明表示になります。(※ビューポートシェーディング)</p>
<p>&nbsp;&nbsp;・アドオンショートカットでロック（選択不可）したすべてのオブジェクトを一括解除（選択可）できます。このとき半透明表示も同時に解除されます。</p> 
<p>&nbsp;&nbsp; ※ロック解除の対象は、アドオンでロックしたオブジェクトのみです。手動で選択不可にしたオブジェクトには影響しません。</p>
<p>&nbsp;&nbsp; ※アウトライナーで手動でロック解除（選択可）した場合、半透明表示はそのまま残ります。ですが、その後アドオンのショートカットを使えば、表示も正しくリセットされます。</p>


![オブジェクト選択](https://github.com/user-attachments/assets/23215f96-ad19-4697-aca5-c4b061597e07)



#### 編集モードでの動作

<p>&nbsp;&nbsp;・アドオンショートカットで　選択/選択外　の頂点をロックできます。</p>
<p>&nbsp;&nbsp;・アドオンショートカットで編集オブジェクトの頂点を一括ロック解除できます。</p>

![編集モード](https://github.com/user-attachments/assets/177bf33d-1b38-4245-8974-1c8825148699)


---

### ⚙️ ショートカットは好きなキーに自由に割り当てOK！
<pre>・オブジェクトモード</font>
  
    ・選択オブジェクトを選択不可に（選択をロック）　　　　　　        デフォルトキー:　    4
  
    ・全選択不可オブジェクトを選択可能に（ロック解除）　　　　        デフォルトキー:  alt+4
 
    ・選択オブジェクト以外を選択不可に(選択以外ロック)               デフォルトキー: ctrl+4


・編集モード
  
    ・選択頂点を選択不可に（選択をロック）　　　　　　               デフォルトキー:　    4
 
    ・選択オブジェクトの選択不可頂点を選択可能に（ロック解除）　　　　デフォルトキー:  alt+4
 
    ・選択頂点以外を選択不可に(選択以外ロック)                      デフォルトキー: ctrl+4</pre>


ビューポートシェーディングを“オブジェクト”に設定すると、選択不可のオブジェクトが半透明で表示され、視認性がアップします。

※オブジェクトモード／メッシュモードで同じキー名が使われていますが、それぞれ異なる動作をします。





![image](https://github.com/user-attachments/assets/1a7d50ac-26a1-4e69-8c85-0a51b2a867ff)
![シェーダー](https://github.com/user-attachments/assets/3f1865eb-885e-4da3-8022-4883821b883a)


## 導入方法
Blender の `Edit > Preferences > Addons > Install` を開き、ダウンロードしたアドオンの ZIP ファイルを選択してインストールボタンを押します。 インストール後、該当するアドオンの左側についているチェックボックスを ON にします。

