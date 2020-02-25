## first_webapp  
## 学習の目標  
サーブレット／JSPについて学習  
### 課題：おみくじサーブレット 
- http://localhost:8080/first_webapp/omikuji.jsp にアクセスすると、以下のような入力フォームが表示される  
![](https://s3-ap-northeast-1.amazonaws.com/techacademy/bootcamp/java-servlet/servlet-jsp/servlet_jsp_omikuji_result_00.png)  
- 入力項目は、氏名の入力欄のみ  
- 「占う！」ボタンをクリックすると OmikujiServlet へPOSTで送信  
- 氏名が未入力の状態で送信した場合は「氏名を入力してください」というエラーを表示  
![](https://s3-ap-northeast-1.amazonaws.com/techacademy/bootcamp/java-servlet/servlet-jsp/servlet_jsp_omikuji_result_02.png)  
- 氏名が入力されている場合は、その氏名をそのまま結果画面に表示   
- 加えて、おみくじの結果を一緒に表示  
![](https://s3-ap-northeast-1.amazonaws.com/techacademy/bootcamp/java-servlet/servlet-jsp/servlet_jsp_omikuji_result_01.png)  
- おみくじの結果はランダムになるようにする
