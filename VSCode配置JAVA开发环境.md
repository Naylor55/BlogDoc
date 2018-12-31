# VSCode配置JAVA开发环境
## 1：给机器安装JDK、MAVEN
* 下载JDK  <br>
下载路径：https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html

    ![Aaron Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/downloadJDK.png)

* 配置JAVA的环境变量 <br>
我的JDK在硬盘的位置：
     ![Asron Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/jdkpath.png)
    新建环境变量JAVA_HOME：D:\Applications\JAVAjdk

    新建环境变量CLASSPATH：.;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar

    在path环境变量后面添加如下内容：
    ![Aaron Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/javapath.jpg)
* 下载MAVEN
    下载路径：
    http://maven.apache.org/download.cgi

* 配置MAVEN的环境变量 <br>
    我的MAVEN在硬盘中的位置：
    ![Aasron Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/mavenWindowsPath.png)

    新建环境变量MAVEN_HOME：D:\Applications\Maven\apachemaven3.6.0

    新建环境变量M2_HOME：D:\Applications\Maven\apachemaven3.6.0

    在path环境变量后面添加如下内容：
    ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/mavenPath.jpg)
    

## 2：给VSCODE安装相关JAVA开发的扩展
* 先别管这些扩展是干什么的，安装了再说：
    ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/vsCodeJavaExtensions.jpg)
    


## 3：对VSCODE做一定的配置
* 打开：文件-首选项-设置，添加如下用户设置：

    ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/vscodeJavaMavenConfig.png)
## 4：初始化一个SpringBoot的应用
* 下面的步骤几乎就是下一步下一步，直接贴上我的截图：
    按下快捷键：CTRL+SHIFT+P，输入SpringInitializr。
     ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/createSpringBoot01.png)

     ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/createSpringBoot02.png)

     ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/createSpringBoot03.png)

     ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/createSpringBoot04.png)

     ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/createSpringBoot07.png)

     ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/createSpringBoot08.png)

     ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/createSpringBoot09.png)

     ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/createSpringBoot10.png)

     ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/createSpringBoot11.png)

     ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/createSpringBoot12.png)

     ![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/createSpringBoot13.png)
     

## 5：使用MAVEN来管理刚才新建的SpringBoot应用

* 在VSCODE的终端中可以直接输入maven命令来对项目执行clean、install等相关操作。

![Aarson Swartz](https://github.com/Naylor55/MarkDownImages/raw/master/VSCode%E9%85%8D%E7%BD%AEJAVA%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83/mvnbuild.png)