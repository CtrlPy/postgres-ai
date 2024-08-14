# postgres-ai


docker install `curl -fsSL https://get.docker.com | bash && sudo usermod -aG docker $USER && exit`

`lsblk`


sudo apt-get install -y zfsutils-linux

`sudo zpool create -f \
  -O compression=on \
  -O atime=off \
  -O recordsize=128k \
  -O logbias=throughput \
  -m /var/lib/dblab/dblab_pool \
  dblab_pool \
  "sdb"`


  `sudo zfs list`


  ```zsh
  mkdir -p ~/.dblab/engine/configs

curl -fsSL https://gitlab.com/postgres-ai/database-lab/-/raw/v3.5.0/engine/configs/config.example.logical_generic.yml \
  --output ~/.dblab/engine/configs/server.yml

  ```

  