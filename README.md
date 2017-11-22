# MybatisGenerator
Running MBG from Java with a Java Based Configuration
以往我们在开发时都需要通过数据库中的表然后自己在po包下建立相对应的pojo类，并要创建相应的mapper.xml写出对表的所有操作，而使用mybatis逆向工程就不用我们自己再编写pojo类与相应的mapper.java和mapper.xml文件，它可以自动对单表生成sql，包括:mapper.xml、mapper.java、表名.java(po类)。是不是很方便？接下来我将为你们介绍如何使用mybatis的逆向工程，只需三步便可以简单做到
