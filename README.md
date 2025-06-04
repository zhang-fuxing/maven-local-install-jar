# maven-local-install-jar
maven安装jar到本地仓库
```sh
mvn install:install-file -Dfile="/path/xxx.jar" -DgroupId="cn.com.xxx" -DartifactId="demo" -Dversion="1.0.0" -Dpackaging=jar
```
