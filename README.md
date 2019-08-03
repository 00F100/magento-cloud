# Magento Cloud for Docker

Bash executable to prepare Magento Cloud localhost with Docker

This script was originally produced by [@LucasCalazans](https://github.com/LucasCalazans)

My sincere thanks

----

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
    -B,  --base-dir          Base dir content directory mcp
    -v,  --version           Print version
    -vv, --version-small     Print only number of version
```

----

### Install (default dir: /usr/local/bin/)

```
$ curl https://raw.githubusercontent.com/00F100/magento-cloud/master/install | sudo bash
```

##### Customize install dir

> IMPORTANT: All options finish with "/"

```
Usage:
    install [--base-dir PATH] [--save-dir PATH]

  Options:
    -s,  --save-dir     Path to save bash "magento-create-project"
    -B,  --base-dir     Path to save all sources
```

Example:
```
$ curl https://raw.githubusercontent.com/00F100/magento-cloud/master/install | sudo bash -s -- -s=/your/path/ -B=/your/path/
```

### Uninstall (default dir: /usr/local/bin/)

```
$ curl https://raw.githubusercontent.com/00F100/magento-cloud/master/uninstall | sudo bash
```

##### Customized unistall

```
$ curl https://raw.githubusercontent.com/00F100/magento-cloud/master/uninstall | sudo bash -s -- -s=/your/path/ -B=/your/path/
```