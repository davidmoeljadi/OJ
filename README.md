# Old Javanese Experimental Grammar (OJEG)

This is an experimental computational grammar for Old Javanese in [HPSG](http://hpsg.stanford.edu/) using the [DELPH-IN](http://delph-in.net) infrastructure. It is bootstrapped using the [LinGO Grammar Matrix](http://www.delph-in.net/matrix/).

Compile with:

```
ace -g ace/config.tdl -G oj.dat
```

Run it with:

```
echo "hana ta gunung" | ace -g oj.dat
```
