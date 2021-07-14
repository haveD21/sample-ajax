# sample-ajax
授業中のリソースの置き場所

ajaxのgetを行うためのテンプレート
## jQuery側のjsonオブジェクトの準備
```javescript
formData={};
```
{} は 空の json オブジェクト
```javascript
formData["param1"] = "テスト";
```
formData のプロパティは formData["プロパティ文字列"] に値をセットして作成される
formData のプロパティは formData.プロパティ文字列 と書く事もできます
```javascript
formData.param1 = "テスト";
```
