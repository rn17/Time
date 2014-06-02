install:
	yum -y install xinetd	
	install main main_network_gui main_gui /usr/local/bin
	grep -q "`cat main.services`" /etc/services || cat main.services >> /etc/services
	install main.xinetd /etc/xinetd.d/main
        


