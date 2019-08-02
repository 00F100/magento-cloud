# Magento Cloud for Docker

Bash executable to prepare Magento Cloud localhost with Docker

### Install

```
$ curl https://raw.githubusercontent.com/00F100/magento-cloud/master/install | sudo bash
```

### Uninstall

```
$ curl https://raw.githubusercontent.com/00F100/magento-cloud/master/uninstall | sudo bash
```


### Usage

```
Usage:
    magento-create-project [--name NAME] [--path PATH] [--magento-version VERSION] [--host HOST] [--admin-user USER] [--admin-password PASSWORD] [--public-key KEY] [--private-key KEY]

  Options:
    -h,  --help              Print this
    -n,  --name              Name of admin user
    -P,  --path              Directory to clone Magento Cloud
    -V,  --magento-version   Magento Cloud version
    -H,  --host              Domain to access Magento Cloud
    -u,  --admin-user        Username to access admin area
    -p,  --admin-password    Password to access admin area
    -b,  --public-key        Public key to access Magento Cloud
    -i,  --private-key       Private key to access Magento Cloud
    -v,  --version           Print version
    -vv, --version-small     Print only number of version
```