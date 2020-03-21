# CrackSleeve
破解CS4.0
# UseAge
1. 将cobaltstrike.jar和CrackSleeve.java放一起
2. 编译(`javac -encoding UTF-8 -classpath cobaltstrike.jar CrackSleeve.java`)
3. 解密文件(`java -classpath cobaltstrike.jar;./ CrackSleeve decode`)
4. 自定义16位字符串加密文件(`java -classpath cobaltstrike.jar;./ CrackSleeve encode CustomizeString`)
5. 将解密后的sleeve文件夹替换jar包中的文件夹
