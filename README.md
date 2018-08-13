# helloSpringBoot

Spring Boot を使って最小限のコードで Hello World します。

条件: maven インストールまで完了している


# ビルド

```
git clone git@github.com:bluemooninc/helloSpringBoot.git
cd helloSpringBoot
mvn package
```

# 実行

以下ポート8888で実行のサンプルです。

```
java -jar target/gs-spring-boot-0.1.0.jar --server.port=8888
```