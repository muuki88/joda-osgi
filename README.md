## Joda P2 Features and Updatesite

This setup will generate a p2 update site for each joda bundle.
Currently integrated are:

* joda-time
* joda-convert

## Troubleshooting

If your maven installation doesn't resolve the joda jars correctly
install them manually via

```bash

mvn install:install-file -DgroupId=org.joda -DartifactId=joda-time -Dversion=2.1 -Dpackaging=jar -Dfile=/path/to/joda-time-2.1.jar
```

and

```bash

mvn install:install-file -DgroupId=org.joda -DartifactId=joda-convert -Dversion=1.2 -Dpackaging=jar -Dfile=/path/to/joda-convert-1.2.jar
```

