监测对象内存大小的方法
1。打包之后需要将Premain-Class: com.sizeOfObject.SizeOfObject值设置到包里MANIFEST.MF的后边。
2.在自己的应用中vm-option使用-javaagent:D:\Java\.m2\repository\com\sizeOfObject\size\1.0-SNAPSHOT\size-1.0-SNAPSHOT.jar
