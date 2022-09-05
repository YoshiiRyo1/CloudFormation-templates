# CostExplorer Budget Alert

予め決めた月間コストに対してしきい値を3段階を定め、それを超えるとアラートを発砲します。  

[AWS Budgets を用いてコストを管理する](https://docs.aws.amazon.com/ja_jp/cost-management/latest/userguide/budgets-managing-costs.html)  

### パラメーター

|値|説明|
|---|---|
|Amount|予算額(USドル)|
|EmailAddress|異常検知時の通知先メールアドレス|
|Forecasted|いくら使ったか（ACTUAL）、いくら使うと予想されるか（FORECASTED）の何れかを指定|
|Actual1|しきい値(%)、Actual2 より低い値を指定|
|Actual2|しきい値(%)、Actual3 より低い値を指定|
|Actual3|しきい値(%)、Actual2 より高い値を指定|
|UseBlended|ブレンデッドレートを使う(true)、使わない(false)を指定 (※)|

(※) ブレンデッドレートとは、RI 前払い費用または RI 割引時間別料金のいずれを含んだ金額  
