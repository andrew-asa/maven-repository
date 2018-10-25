# maven仓库地址
# 使用说明
+ pom.xml 里面添加

```
<repositories>
        <repository>
            <id>andrew.asa-maven-repository</id>
            <url>https://raw.githubusercontent.com/andrew-asa/maven-repository/master/repository</url>
        </repository>
</repositories>
```

# lib提供列表
+ 重新编译第三方jar third

```
<dependency>
            <groupId>com.asa</groupId>
            <artifactId>com.asa.third</artifactId>
            <version>1.0-SNAPSHOT</version>
</dependency>
```

+ 基础工具包 base

```
<dependency>
            <groupId>com.asa</groupId>
            <artifactId>com.asa.base</artifactId>
            <version>1.0-SNAPSHOT</version>
</dependency>
```

