I've published these rpms to help all sysadmin (for CentoOS/Linux 7.x, and RedHat 7.x) to solve this CVE:

https://nvd.nist.gov/vuln/detail/CVE-2019-6111

In my env

"CentOS Linux release 7.9.2009 (Core)"

after installation i've to run this command:

chmod 600 /etc/ssh/*_key

to start sshd.

The dir OpenSSH-RPM contain a yum repo and all packages are signed with my smartcard (the key is opengpg-key.gpg to import in rpm keystore).

