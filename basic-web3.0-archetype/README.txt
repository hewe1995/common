一个maven webapp3.0 archetype ,里面有一个jar包,可以直接解压到本地仓库中使用

1.在本地仓库的根目录下编辑archetype-catalog.xml,添加:
<archetype>
      <groupId>org.hewe</groupId>
      <artifactId>basic-web3.0-archetype</artifactId>
      <version>1.0.0</version>
      <description>basic-web3.0-archetype</description>
</archetype>
2.eclipse里添加新的仓库,选择上面的文件.
