元件練習
===

利用`EditText`,`Button`將註冊畫面呈現
並且點擊Button將其文字由login改為logout

啟用Button點擊事件

    android:onClick="loginin"

設置Button點擊事件

    public void loginin(View view){
        Button btn = findViewById(R.id.login);
        btn.setText("logout");
    }

成果展示

![image](https://user-images.githubusercontent.com/72558210/136035340-6feb13ba-6c92-4012-b300-826e6aeb89ca.png)
-->
![image](https://user-images.githubusercontent.com/72558210/136039474-a20c428a-4b15-42d6-991c-c927fd89f3e4.png)



