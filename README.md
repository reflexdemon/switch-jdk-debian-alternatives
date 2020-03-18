# switch-jdk-debian-alternatives
This is a simple tool to switch any AdoptOpenJDK on any Debian using alternatives like Ubuntu, Linux Mint etc.,

This is the outcome of my previous blog on switching JDKs: https://blog.vpv.io/2019/07/installing-open-jdk-on-ubundu.html

## Usage
This tool can be used without installing on your computer. Using the command line tool like `curl` this can be used.

The usage is like this:

```bash
$ curl -s https://raw.githubusercontent.com/reflexdemon/switch-jdk-debian-alternatives/master/switch-jdk.sh | sudo bash -s 11
```

or

```bash
$ curl -s https://raw.githubusercontent.com/reflexdemon/switch-jdk-debian-alternatives/master/switch-jdk.sh | sudo bash /dev/stdin 11
```

# Installing the correct Adopt Open JDK please use this link

To install the latest AdoptOpenJDK visit https://adoptopenjdk.net/installation.html#linux-pkg

## TODO

1. Expand the installation beyond `HotSpot` and support `OpenJ9`
2. May be later Support other JDKs like Oracle and Open JDKs
3. Support other Linux distributions

## Contribution

I am open to take PR for any of the above mentioned TODOs. I am all ears for anything new that can be used.
