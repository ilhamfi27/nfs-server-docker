## Installation for nfs server on docker
1. Apply this or you can put this code on .profile file. Change $PWD with absolute path.
```
sudo apparmor_parser -r -W $PWD/config/profile.apparmor.c
```
2. Run the docker compose
3. Change volume folder to 777
```
sudo chmod 777 -R volumes
```

## After changing export configuration
Run apply.config.sh
```
./apply.config.sh
```