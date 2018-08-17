# php_program_BS_Demo
Git_Branch_Strategy_Demo_using_PHP_Programs

Steps:
ubuntu@ip-10-0-1-84:~/Demos$ git clone https://github.com/muralindia/php_program_BS_Demo.git
Cloning into 'php_program_BS_Demo'...
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.

ubuntu@ip-10-0-1-84:~/Demos/php_program_BS_Demo$ mv ../src .
ubuntu@ip-10-0-1-84:~/Demos/php_program_BS_Demo$ ls
README.md  src

ubuntu@ip-10-0-1-84:~/Demos/php_program_BS_Demo$ ls src/
form.php
ubuntu@ip-10-0-1-84:~/Demos/php_program_BS_Demo$ git add src/
ubuntu@ip-10-0-1-84:~/Demos/php_program_BS_Demo$ git commit -m "Form program"
[master 32e3d4e] Form program
 1 file changed, 113 insertions(+)
 create mode 100644 src/form.php
ubuntu@ip-10-0-1-84:~/Demos/php_program_BS_Demo$ git log
commit 32e3d4e6e9865a6367d9d576c5ca300287152033
Author: Murali Dhandapani <muralindia@gmail.com>
Date:   Fri Aug 17 03:56:57 2018 +0000

    Form program

commit f7a3f5dc8d79f374940bae1ea2978a620bae0cfb
Author: muralindia <muralindia@gmail.com>
Date:   Fri Aug 17 09:19:37 2018 +0530

    Initial commit
ubuntu@ip-10-0-1-84:~/Demos/php_program_BS_Demo$ git push -u origin
Username for 'https://github.com': muralindia
Password for 'https://muralindia@github.com':
Counting objects: 4, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 1.45 KiB | 0 bytes/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/muralindia/php_program_BS_Demo.git
   f7a3f5d..32e3d4e  master -> master
Branch master set up to track remote branch master from origin.

ubuntu@ip-10-0-1-84:~/Demos/php_program_BS_Demo/src$ git commit -m "2 more programs - comments_string_echo.php and php_echo.php"
[master 75b12e7] 2 more programs - comments_string_echo.php and php_echo.php

ubuntu@ip-10-0-1-84:~/Demos/php_program_BS_Demo/src$ git log
commit 75b12e7ba8b3151866d6a476029c1ad55603bbfa
Author: Murali Dhandapani <muralindia@gmail.com>
Date:   Fri Aug 17 04:19:57 2018 +0000

    2 more programs - comments_string_echo.php and php_echo.php

commit 32e3d4e6e9865a6367d9d576c5ca300287152033
Author: Murali Dhandapani <muralindia@gmail.com>
Date:   Fri Aug 17 03:56:57 2018 +0000

    Form program

commit f7a3f5dc8d79f374940bae1ea2978a620bae0cfb
Author: muralindia <muralindia@gmail.com>
Date:   Fri Aug 17 09:19:37 2018 +0530

    Initial commit


======== Updated source to Master ==========

