# ssh-archetype
将代码拉下来后不要使用IDEA打开，否则会产生.idea *.iml无关文件，打开了也没关系，删除即可
在终端cd到项目，mvn archetype:create-from-project ，构建成功了之后，
进入项目目录下的target/generated-sources/archetype执行mvn install将项目的archetype安装到本地
最后就可以通过IDE的maven方式构建ssh项目
