## Postgres-ai


docker install: 


 ```zsh
 curl -fsSL https://get.docker.com | bash && sudo usermod -aG docker $USER && exit
 ```


`lsblk`




#

* step1 

*before installing zfsutils-linux you must prepare your disk, namely mount a new partition for zfs*


```zsh
sudo apt-get install -y zfsutils-linux
```



```zsh
sudo zpool create -f \
  -O compression=on \
  -O atime=off \
  -O recordsize=128k \
  -O logbias=throughput \
  -m /var/lib/dblab/dblab_pool \
  dblab_pool \
  "sdb"
  ```




  ```zsh
  sudo zfs list
  ```


* step2



```zsh
git clone https://github.com/CtrlPy/postgres-ai.git
```




#### change config file  *server.yml*

* The quick and simple editor for cron schedule expressions by Cronitor https://crontab.guru/every-2-minutes



* step3
#



  ```zsh
docker compose up -d
  ```



  