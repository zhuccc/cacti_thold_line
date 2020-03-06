# cacti_thold_line
cacti 使用 line notify 告警(含圖片輸出)

2020/03/06修正偵測不到機器和回復時輸出為空白的問題

1.編輯 thold_functions.php，找到“ function thold_mail”這個Function，在最後的“ return'';”上方加入程式碼：

2.把 your_line_token 改成自己使用的 token
