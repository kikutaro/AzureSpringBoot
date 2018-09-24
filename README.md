# SpringBoot on Microsoft Azure.
Microsoft AzureでSpring Bootの簡単なサンプルアプリケーションを動かす雛形。
詳細手順は[Qiitaの記事](https://qiita.com/kikutaro/items/251aebc572794105a524)を参照。

# ローカルでの実行

```
.\mvnw.cmd clean package
```

```
.\mvnw.cmd spring-boot:run
```

# Microsoft Azureへのデプロイ

```
az login
```

```
.\mvnw.cmd clean package
```

```
.\mvnw.cmd azure-webapp:deploy
```
