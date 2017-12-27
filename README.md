# Linux-tips

### user operations
- **whoami**

- **useradd  username**, **passwd username**
- **userdel  username**
- gourp info, /etc/group, command "**id -g**" or "**id -G**", show user belongs to which group, "**id -gn**" can show the name of the group, "**id username**", userid,gourpid, "**groups**" current group.
- **w** shows who logging in the server now.

### install

- source code install, ** configure, make, make install**
- RPM install **rpm -ivh package_name** , query **rpm -q package name**, delete **rpm -e name**
- yum install **yum install name** , update **yum update name**, list installed package **yum list name**, search **yum search name**, uninstall **yum remove name**

### find

- type **find / -type d**, find by directory
- time **find / -mtime +5, -mtime -1**, timeline -5,-4,-3,-2,-1,now, -5.-4.-3.-2 is the find result.

### chmod chown
- **chown username:groupname filename**


### network

- ifconfig, "yum install net-tools"
- netstat
- iptables


### shutdown
- **shutdown -h now**, power off.
- **shutdown -r**, reboot.


### top

- **shift + m**, sort pid by memory
- **shift + p**, sort pid by cpu
- **1**, show cores of cpu

About cpu info, us means user, sy means system, wa means wating for io, hi means hardware interrupt, si means software interrupe.
If us too high, maybe it caused by many computation, hi too high maybe caused by too many network connection etc.


### stat

- **pidstat**
- **iostat**
- **vmstat**





