## PRLabeler
PRにつけたラベルを任意のReviewrsがApproveしたときに変更できる、  
GitHubActions用のyml.  
shellで無理やり書いてます.  
軽い動作確認のみなので動かなかったらごめんなさい.

### 設定するもの
- DEFAULT_REVIEWRS_COUNT：レビュアーのデフォルトアサイン人数
- ADD_LABEL：必要人数approveした場合に追加するラベル名
- REMOVE_LABEL：必要人数approveした場合に削除するラベル名
