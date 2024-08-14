# postgres-ai


docker install: 


 `curl -fsSL https://get.docker.com | bash && sudo usermod -aG docker $USER && exit`


`lsblk`

#

* step1 

`sudo apt-get install -y zfsutils-linux`



`sudo zpool create -f \
  -O compression=on \
  -O atime=off \
  -O recordsize=128k \
  -O logbias=throughput \
  -m /var/lib/dblab/dblab_pool \
  dblab_pool \
  "sdb"`




  `sudo zfs list`


* step2



`git clone https://github.com/CtrlPy/postgres-ai.git`


* step3
#



  ```zsh
docker compose up -d
  ```



  