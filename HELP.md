# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.0.4/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.0.4/maven-plugin/reference/html/#build-image)

### 在Ubuntu 20上面安装OpenJDK17
1.升级Ubuntu软件资源库
```
sudo apt update -y
```

2.安装openjdk
```
sudo apt-get install openjdk-17-jdk -y
```

3.设置环境变量
```
sudo vim /etc/profile
JAVA_HOME=/usr/lib/jvm/java-17-openjdk-amd64
PATH=$PATH:$HOME/bin:$JAVA_HOME/bin
export JAVA_HOME
export PATH
```
4.使环境变量生效
```
source /etc/profile
```
5.查看JDK版本
```
java --version
```