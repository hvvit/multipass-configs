# multipass-configs
## My configs for multipass machines.
cloudconfig.yaml     -> For setting up authorised keys for ubuntu user(helpful in ansible)
                     -> Installs docker
                     -> Installs docker-compose
passwordconfig.yaml  -> Just sets up authorised keys
## How to use with multi[pass
```
multipass launch -n pseudo-name --cloud-init cloudconfig.yaml -c 1 -m 2g -d 10g # creates a machine with 1 core 2gb  memory with 10 gigs of harddisk
``` 
