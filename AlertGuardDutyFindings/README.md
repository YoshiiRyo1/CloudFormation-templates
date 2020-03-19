# AlertGuardDutyFindings

GuardDuty の通知を重要度でフィルターします。  

GuardDuty の重要度レベルと Severity の関係。  

高： 7.0〜8.9 の範囲  
中： 4.0〜6.9 の範囲  
低： 0.1〜3.9 の範囲  

## テンプレート
### yaml
[AlertGuardDutyFindings.yaml](yaml/AlertGuardDutyFindings.yaml)

### パラメーター
|値|説明|
|---|---|
|Number|GuardDuty の重要度値 (Severity Value)|

## ブログ
[GuardDutyの通知が重要度でフィルター可能になりました](https://dev.classmethod.jp/cloud/aws/guardduty-event-filter/)
