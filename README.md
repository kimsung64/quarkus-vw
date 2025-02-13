# quarkus-vw

https://ja.quarkus.io/

```
# quarkus cliのinstall
$ sdk install quarkus
# project生成
$ quarkus create app com.example:quarkus-kotlin-gradle --gradle --kotlin
$ cd quarkus-kotlin-gradle 
# hot reload 起動する方法、下記両方ともOK
$ quarkus dev
$ ./gradlew quarkusDev
# native imageで起動する方法(hot reload不可)
$ ./gradlew build -Dquarkus.package.type=fast-jar
$ java -jar build/quarkus-app/quarkus-run.jar
```
