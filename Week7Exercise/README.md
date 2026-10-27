## Demo
Bài 1: Tấn công ko qua WAF
![alt text](image.png)
Tên đăng nhập ' OR 1=1-- (SQL Injection)
![alt text](image-1.png)
Vào đc thành công
Bài 2: Tấn công qua WAF
![alt text](image-2.png)
Gõ đúng payload trên, nhưng WAF không cho vào.
Bài 3: Đăng nhập đúng
![alt text](image-3.png)
Gõ đúng tk/mk, vào thành công
Bài 4: Test log
![alt text](image-4.png)
Khi truy cập log, nó hiện ra "SQL Injection Attack Detected via libinjection".