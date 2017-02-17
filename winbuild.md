# build and install

lein install

## or

SET "LEIN_SNAPSHOTS_IN_RELEASE=1.3.1-loc"

lein jar

## install to locale repo

mvn install:install-file -Dfile=target\re-com-1.3.1-loc.jar -DgroupId=seryh -DartifactId=re-com -Dversion=1.3.1-loc -Dpackaging=jar
