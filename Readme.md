TOOLS SET UP CYBERPANEL

## STEP 1 ( python )
```sh
yum install gcc openssl-devel bzip2-devel && cd /usr/src && wget https://www.python.org/ftp/python/2.7.18/Python-2.7.18.tgz && tar xzf Python-2.7.18.tgz && cd Python-2.7.18 && ./configure --enable-optimizations && make altinstall
```
## STEP 2 SELINUX DISABLE
```sh
git clone https://github.com/KurrXd/cyberpanel && cd cyberpanel && mv config /etc/selinux/
```
# jika muncul ini :
mv: overwrite ‘/etc/selinux/config’?
ketik aja yes contoh mv: overwrite ‘/etc/selinux/config’?yes

## STEP 3 REBOOT VPS
```sh
reboot
```

## STEP 4 INSTALL CYBERPANEL
```sh
sh <(curl https://cyberpanel.net/install.sh || wget -O - https://cyberpanel.net/install.sh)
```
![image](https://user-images.githubusercontent.com/91126186/233059807-8e8cd9be-a3e5-4485-8797-440323f5ebb8.png)
# pilih 1

![image](https://user-images.githubusercontent.com/91126186/233059974-4e51820c-8c76-44b0-87bf-228734c5c27a.png)
# pilih 1 lagi

![image](https://user-images.githubusercontent.com/91126186/233060275-3a2eb4a5-9f97-4993-b016-001ae401b510.png)
# IKUTI DIATAS DI VERSI (ENTER) SAJA
![image](https://user-images.githubusercontent.com/91126186/233060791-99ea5d8d-7be2-4e2f-8c2f-55e145053979.png)
# ikuti lagi

## DAN TUNGGU SAMPAI KELAR
