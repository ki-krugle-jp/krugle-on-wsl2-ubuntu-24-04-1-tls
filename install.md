
# Enable WSL2 and Install Ubuntu 24.04.1 LTS

https://learn.microsoft.com/ja-jp/windows/wsl/basic-commands#install

```
wsl --install -d Ubuntu-24.04
```

```
Example:

PS C:\Users\ki-krugle-jp> wsl --install -d Ubuntu-24.04
インストール中: Ubuntu 24.04 LTS
Ubuntu 24.04 LTS がインストールされました。
Ubuntu 24.04 LTS を起動しています...
Installing, this may take a few minutes...
Please create a default UNIX user account. The username does not need to match your Windows username.
For more information visit: https://aka.ms/wslusers
Enter new UNIX username: sysadmin
New password:
Retype new password:
passwd: password updated successfully
Installation successful!
To run a command as administrator (user "root"), use "sudo <command>".
See "man sudo_root" for details.

Welcome to Ubuntu 24.04.1 LTS (GNU/Linux 5.15.167.4-microsoft-standard-WSL2 x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/pro

 System information as of Fri Mar  7 14:26:54 JST 2025

  System load:  0.07                Processes:             32
  Usage of /:   0.1% of 1006.85GB   Users logged in:       0
  Memory usage: 2%                  IPv4 address for eth0: 172.17.122.87
  Swap usage:   0%


This message is shown once a day. To disable it please create the
/home/sysadmin/.hushlogin file.
sysadmin@spring-1:~$
```


