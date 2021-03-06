<h1># Project No.2 </h1>
<h2>1. Project Name: TODAY SNS</h2>


<h2>2. 開発目的とプロジェクト概要</h2>

 1) 開発目的 : <br>
 SNS APPをベンチマーキングし、日常を共有する事ができるSNSサイトを作りました。<br>
 また、会員なら趣味や関心事が同じである他の人々と一緒に集まりを作ることができるよう小集まり掲示板も構成しています。<br>
 2) 開発人員 : 3人<br>
 3) 開発期間 : 2020.02.12 ~ 2020.03.15 (1ヶ月) <br>


<h2>3. 開発環境</h2>
 1) OS : Windows 10 Home <br>
 2) WAS : Tomcat 8.5 <br>
 3) Java :　jdk1.8.0_231 <br>
 4) DB : Oracle Database 11g Express Edition <br>
 5) Tool : Eclipse, SqlDeveloper, Visual Studio Code <br>
 6) 使用言語 : Java ,  JSP , Servlet & MVC , JSTL , HTML5, CSS , Bootstrap, JavaScript, jQuery, Ajax <br>
 
 
 <h2>4. UseCase</h2>
<img src = "https://user-images.githubusercontent.com/50767972/85623531-82e21300-b6a3-11ea-946a-0e09b3f7a65b.PNG" width = "90%"></img>    


 <h2>5. データベースの構造</h2>
<img src = "https://user-images.githubusercontent.com/50767972/85628024-6a292b80-b6aa-11ea-9070-6043554e519f.PNG" width = "90%"></img>
<img src = "https://user-images.githubusercontent.com/50767972/85628480-2be03c00-b6ab-11ea-9e65-60d34e69088e.PNG" width = "90%"></img>


<h2>6. スクリーンショット</h2>
<h4>1) ログイン画面</h4>
- IDとパスワードを書かずにログインボタンを押すと、警告ウィンドウが表示されます。
IDまたはパスワードを違えば、警告ポップアップウィンドウが表示されます。
左側のバナー部分にログインボタンを押すと、モーダルポップアップウィンドウが表示され、ログインを実行することができます。
会員登録ボタンを押すと、会員登録画面に切り替わります。<br>
<img src = "https://user-images.githubusercontent.com/50767972/85628948-f556f100-b6ab-11ea-9809-efb67265b0f3.PNG" width = "90%"></img>
<br>

<h4>2) 会員登録画面</h4>
- 会員登録のための画面でサイト利用時に必要なニックネーム、ID、パスワード、プロフィール写真などを登録できます。
ニックネームとIDの場合、重複チェックボタンを押して希望のニックネーム(またはID)を作成すると重複を確認します。
プロフィール写真を登録する場合、拡張子がイメージファイル(JPG、PNG、JPEG)でなければ登録できないようにポップアップウィンドウが表示されます。
パスワードとパスワードの確認の値が異なる場合は、ポップアップ ウィンドウが表示されます。
郵便番号のチェックをクリックすると、次の郵便番号APIを活用して住所を入力できるウィンドウが下に表示されます。<br>
<img src = "https://user-images.githubusercontent.com/50767972/85629023-13245600-b6ac-11ea-824d-c9c0fe017c6e.PNG" width = "90%"></img>
<br>

<h4>3) メイン</h4>
<h5>[1] メイン画面</h5>
- ログインした会員のみメイン画面に接続できます。会員たちが作成した全体文が画面の中央に出力されます。左側にはログインした会員の情報を確認することができます。
上段と左側のメニューには、Home、My掲示板、小集まり、映画のメニューがあります。該当ボタンを押すと、該当画面に切り替わります。中央にある掲示文の入力欄を利用し、自分の掲示板に移動することなく、すぐに文を作成することができます。<br>
<img src = "https://user-images.githubusercontent.com/50767972/85628963-fe47c280-b6ab-11ea-9ccc-744c0bbd017f.PNG" width = "90%"></img>
<br>
<h5>[2] 私の掲示板画面</h5>
- ログインした会員が作成したすべての文章が出力されます。
1行に掲示文は4つずつ表示され、該当写真の上にマウスを置くと写真が強調されます。ログインした会員が作成したすべての文章が出力されます。
1行に掲示文は4つずつ表示され、該当写真の上にマウスを置くと写真が強調されます。
もしイメージがない場合は、基本イメージが出力されます。
各写真をクリックすると、掲示文の詳細画面モーダルポップアップウィンドウが表示されます。<br>
<img src = "https://user-images.githubusercontent.com/50767972/85629068-26372600-b6ac-11ea-9eb2-2fa6df7349fc.PNG" width = "90%"></img>
<br>
<h5>[3] 私が書いた文章の詳細画面</h5>
- ログインした会員が作成した掲示文の作成日、文の内容を確認することができます。
該当文のコメントを作成・削除することができます。 
下段の修正、削除、閉じるボタンを押すと、各機能が実行されます。
修正ボタンを押すと、文を修正できる画面に移動します。<br>
<img src = "https://user-images.githubusercontent.com/50767972/85629121-39e28c80-b6ac-11ea-8020-f9248f0eff4f.PNG" width = "90%"></img>
<br>
<h5>[4] 文をアップロードする画面</h5>
- アップロードボタンを押すと添付ファイルをアップロードする画面が出ます。
添付ファイルをアップロードすると、文を作成することができます。
文章は、最大1,000Byteまで作成できます。
もし、超過した場合は、超過した部分は保存されません。
書き換えボタンを押すと、テキストボックスが初期化されます。
書き込みボタンを押すと、掲示文のアップロード成功のポップアップウィンドウが表示され、My 掲示板画面に移動します。<br>
<img src = "https://user-images.githubusercontent.com/50767972/85629165-4bc42f80-b6ac-11ea-80a3-ac980e3c8c77.PNG" width = "90%"></img>
<br>

<h4>4) 小集まりメイン</h4>
<h5>[1] 小集まりメイン画面</h5>
-会員が登録した全体の小集まりのリストを見ることができます。
Goボタンを押すと、文章番号、募集分野、集まり名、場所、募集状態について検索することができます。募集状況が確認できる。募集人数が全員集まった場合、募集状態は募集完了と表示されます。募集人数が全員集まった場合、募集状態は募集完了と表示されます。
ページング処理でそのページに5つずつ見ることができます。
各募集名をクリックすると、該当投稿の詳細画面に移動します。
下の登録ボタンを押すと、新しいクラブの募集文を作成することができます<br>
<img src = "https://user-images.githubusercontent.com/50767972/85629200-61395980-b6ac-11ea-9a88-6c4d0ceb50b5.PNG" width = "90%"></img>
<br>
<h5>[2] 小集まりの登錄画面</h5>
- 関心分野、募集名、集会関連写真、集会日付/時間、募集人員、
リーダー、連絡先、場所、文のパスワードを入力できる画面です。
検索ボタンを押すと、次の郵便番号APIを活用して住所を検索できます。
登録するボタンを押すと、登録が正常に処理された場合は、登録完了案内ウィンドウが表示された後、グループ内のメイン画面に切り替わります。
リストでボタンを押すと、グループ内のメイン画面に切り替わります。<br>
<img src = "https://user-images.githubusercontent.com/50767972/85629225-6d251b80-b6ac-11ea-8f25-2a12d1ba9afa.PNG" width = "90%"></img>
<br>
<h5>[3] 小集まりの詳細画面</h5>
- 集会分野、集会名、集会内容、集会日程、
リーダー、連絡先、募集状況、集会場所を確認することができます。
下段の申込ボタンを押すと、募集状況で募集人数より現在募集された人数が少ない場合は、募集完了案内ポップアップウィンドウが表示され、グループ内のメイン画面に移動します。
もし募集人数と現在募集された人数が同じであれば、申し込み不可の案内ポップアップウィンドウが表示された後、現在のページが表示されます。
リストでボタンを押すと、小集まりのメイン画面に移動します。<br>
<img src = "https://user-images.githubusercontent.com/50767972/85629276-84fc9f80-b6ac-11ea-8478-e8907272cbb1.PNG" width = "90%"></img>
<br>
<h5>[3-1] 小集まりの詳細画面(文の作成者である場合)</h5>
- 文章の作成者が詳細画面にアクセスする場合、下段に修正、募集完了ボタンが表示されます。
変更ボタンを押すと、下段にパスワード入力ボックスが表示されます。 パスワードが一致しない場合、修正画面に戻ります。
もし募集人員が全員集まった場合、または募集を中断したい場合は、募集完了を押すと募集状態が'募集完了'に変更されます。<br>
<img src = "https://user-images.githubusercontent.com/50767972/85629309-96de4280-b6ac-11ea-9905-a2dd1615e27e.PNG" width = "90%"></img>
<br>
<h5>[4] 小集まりの修正画面</h5>
- 文の作成者のみ修正が可能です。
既存の情報が該当マスに入力されています。
もし、会の日日が今日の日付より以前なら、修正できないというポップアップウィンドウが表示されます。修正ボタンを押すと、小集まりのメイン画面に移動します。<br>
<img src = "https://user-images.githubusercontent.com/50767972/85629344-a5c4f500-b6ac-11ea-94ef-5d980bd8e25c.PNG" width = "90%"></img>
