# useconf


###Edit and update USE flags for packages in gentoo
====

### How to install

##### Dependencies
> app-portage/gentoolkit     (required for one of the options. not mandatory)  
> net-misc/curl 

```bash
emerge app-portage/gentoolkit
emerge net-misc/curl
```

##### Installation
```
$ git clone https://github.com/pRivat1337/useconf
$ su
# ./install.sh
```
And you're done!

### How to use

```
Usage: useconf [OPTIONS] [INPUT]...
Edit useflags for a specific package. [INPUT] == package name

Options:
-o, --override          Overrides existing file
-h, --help              Display this screen and exit
-u, --use               Display available useflags for the package (requires app-portage/gentoolkit) and exit
```
