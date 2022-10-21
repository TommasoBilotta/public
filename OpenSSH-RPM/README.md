I've published this rpm to help all sysadmin (for CentoOS/Linux 7.x, and maybe RedHat 7.x) to solve this CVE:

https://nvd.nist.gov/vuln/detail/CVE-2019-6111

In my env

"CentOS Linux release 7.9.2009 (Core)"

after installation i've to run this command:

chmod 600 /etc/ssh/*_key

to start sshd.
