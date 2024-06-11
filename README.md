





## このアプリケーションについて
このアプリケーションはChatGPTのAPIの扱いを勉強する際に作成したプログラムで、ポートフォリオとして公開しています。

起動にはネットワーク環境とOpenAIから発行されるAPIキーが必要です。
<br>
開発環境はVisualStudio2017で、コードは以下で公開しています。
<br>
https://github.com/Lucas816sy/ChatGPT_MailingAppPortfolio_Code
<br>
メール送信機能の部分については、SMTPサーバとパスワードの設定が必要であるため、そのままでは送信機能は使えません。上記URLからコードを編集してください。


 ## 操作説明
 起動すると下のような画面が出てくるので、送信先や作成したいメールの目的を記入してください。
 ![image](https://github.com/Lucas816sy/ChatGPT_MailingAppPortfolio_exe/assets/172348632/1d1dad0e-ee56-4a86-9a15-4371127e0203)
 <br>
 APIキーを入力し、AIモデルを選択したのちに"上記の条件でメール文を作成する"ボタンを押すと入力した内容をもとに自動でメール本文が生成されます。


![image](https://github.com/Lucas816sy/ChatGPT_MailingAppPortfolio_exe/assets/172348632/62330417-5dc4-4305-9330-a6c2b024f582)
<br>
もし内容を修正したい場合、直接テキストボックスの内容を編集するか、"ChatGPTに対して修正内容がある場合はここに入力"という部分に修正内容を入力し、"メール文の内容を修正する"というボタンを押すと修正内容がChatGPTに送信され、再度メール本文が生成されます。
送信ボタンのEnabledはFlaseに設定しています。メール送信機能を試される際はVisual Studioでプロパティから編集してください。
