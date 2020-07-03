







## どんなプラグイン？


装備に「次のグレードの装備のタグ」「必要なお金」「必要なアイテム」を付けると
装備強化メニューで強化できるようになります。


## タグ


### 武器、防具のメモ欄のタグ：

  &lt;NextGrade:x&gt;  
    IDxの武器（防具）にアップグレードできるようになります。

  &lt;UpgradeCost&gt;  
  item id  
  item id: x  
  weapon id  
  weapon id: x  
  armor id  
  armor id: x  
  gold: x  
  &lt;/UpgradeCost&gt;  
    idにアイテムのIDを、xに個数を設定します。
  
  例：  
  &lt;UpgradeCost&gt;  
  item 1  
  item 2: 3  
  gold: 300  
  &lt;/UpgradeCost&gt;  
    ID１のアイテムを1つ、ID2のアイテムを3つ、お金を300G必要とします。


## プラグインコマンド


OpenEquipUpgrade  
装備アップグレード画面を開きます。


## 更新履歴


### Version 0.04
  初回に顔グラが表示されない不具合を修正。

### Version 0.03
  ゴールドの指定で反映されない不具合を修正。

### Version 0.02
  素材に防具と武器を使えるように変更。コストでお金がかからないとき、お金を
  表示しないように変更。

### Version 0.01
  作成。


## 利用規約


 * MITライセンスです。
 * クレジット表記は不要
 * 営利目的で使用可
 * 改変可
	* ただし、ソースコードのヘッダのライセンス表示は残してください。
 * 素材だけの再配布も可
 * アダルトゲーム、残酷なゲームでの使用も可

## LICENSE

MIT


