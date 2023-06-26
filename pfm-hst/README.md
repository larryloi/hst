# Data Archive Services

## Check out das in parent directory
```
cd hst
git clone git@github.com:larryloi/das.git 
```

## How To Release Image
```
cd hst/pfm-hst
make build
```

## How To Test on Local VM
```
docker-compose up -d src-db
docker-compose up -d app
```
