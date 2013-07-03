no-ip for OpenSolaris 5.11 snv_134
=====
1. make
2. pfexec make install
3. pfexec cp svc-noip2 /lib/svc/method/
4. pfexec chmod +x /lib/svc/method/svc-noip2
5. pfexec svccfg import solaris-noip2.xml
6. pfexec chmod 777 /usr/local/etc/no-ip2.conf
7. svcadm enable noip2



