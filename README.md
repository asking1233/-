# -
记录一些比较实用的工具和技巧


wget：网上自动下载工具 例如下载jdk 
wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u181-b13/96a7b8442fe848ef90c96a2fad6ed6d1/jdk-8u181-linux-x64.tar.gz

tar: linux解压缩包 jar -xf xxxx.jar解压。打包：-jar -cvfm0 xxx.jar META-INF/MANIFEST.MF ./。其中META-INF/MANIFEST.MF 用于生成清单信息。 ‘./’表示当前目录下的所有文件。cvf是打包的基本参数，但是在打包springboot项目的时候一定要带上m0不然会无法正常运行。

ln -s  /opt/freeware/old/jdk1.7.0_79/bin/jar jar #创建软路由
