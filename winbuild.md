# build and install for Windows system 

lein install

## or

SET "LEIN_SNAPSHOTS_IN_RELEASE=1.3.1"

lein jar

## install to locale repo

mvn install:install-file -Dfile=target\re-com-1.3.1-standalone.jar -DgroupId=seryh -DartifactId=re-com -Dversion=1.3.1 -Dpackaging=jar


