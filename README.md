## Description

A prototype for a distributed INOTIFY based queue system, intended to be used with machine generated config.


### example
edit Config/Constants.pm

./am_forker.pl (install missing deps via 'cpan install Modulename' or 'cpanm Modulename')

./am_inotify.pl (install missing deps via cpan install Modulename' or 'cpanm Modulename')

to see what happens, use something like this
``` bash
for ((i=100;i<101;i++)); do touch /tmp/test/tm/out/$i\_qbo.xz; done
```



