# some-script-for-mysql
some script for mysql: replication monitor, multi mysqld manager...

Script For mysqlReplicationMonitorForPHP:
	Run This Script By PHP, so you need install php

	after install:
		run "php ./mysqlReplicationMonitorForPHP"


	Usage: ./mysqlReplicationMonitorForPHP [--help] [--host=localhost] [--user=root] [-password=pwd] [--port=3306] [--column]

	 You can edit default MySQL config in file, where that

	            define('DEFAULT_HOST', '127.0.0.1'); //默认主机名

	            define('DEFAULT_USER_NAME', 'root'); //默认用户名

	            define('DEFAULT_PASSWORD', ''); //默认密码

	            define('DEFAULT_PORT', '3306'); //默认端口

	Options:
	        --help : this help
	        --host : host for login in MySQL, defalut "127.0.0.1"
	        --user : user for login in MySQL, default "root"
	    --password : password for login in MySQL, default ""
	        --port : port for login in MySQL, default "3306"
	      --column : output by column style	









