# Gradle-javaweb
## 一个Gradle构建的简单JavaWeb项目模板

## Gradle的文件结构和Maven基本一致：

src/main/java：存放java代码；

src/main/resources：存放资源和配置文件；

src/main/webapp：存放WEB的代码和资源；

src/test/java：存放测试用的java代码；

src/test/resources：存放测试用的资源和配置文件；

group和version分别为项目的所在组和版本信息。和Maven类似，而artifactId在gradle则是项目的name，值保存在settings.gradle文件的rootProject.name中。

build.gradle设置如图：

![build.gradle设置](https://ooo.0o0.ooo/2016/12/05/5845340956084.png)

