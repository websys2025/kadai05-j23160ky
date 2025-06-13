## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
* 日本の郵便番号から住所を検索するAPIです。
* リクエストとレスポンスのフォーマット
* {
  "message": null,
  "results": [
  {
        
      "address1": "東京都",
      "address2": "千代田区",
      "address3": "千代田",
  }
  ],
  "status": 200
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
* https://jsonplaceholder.typicode.com/
* エンドポイントと機能
* 指定したIDのtitleとbodyを取得できます。
* リクエストとレスポンスのフォーマット
* {
  "userId": 1,
  "id": 1,
  "title": "sunt aut facere repellat provident occaecati",
  "body": "quia et suscipit..."
}

### Q3-3. 感想
* 今回の課題で苦労したこと
* JavaScriptでfetch()やawaitを使って非同期処理を行うのが初めてだったので、書き方や書く位置に少し悩みました。また、APIから取得したデータをHTMLにうまく表示させる方法も手間取りました。
* 演習を通して理解できたこと
* フォームの入力を使って外部と通信する処理の流れがわかりました。特に、APIのURLに変数を入れる方法や、JSON形式のデータを扱う基本的な書き方を学べました。
* Web APIの利便性や課題など
* Web APIはとても便利で、天気情報や住所情報など様々なデータを簡単に取得できるのが魅力だと思いました。一方で、エラー処理やデータ形式に注意しないと予期せぬ動作になることもあるので、丁寧に扱う必要があると感じました。
