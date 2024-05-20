### git简单使用

1. 建立本地仓库

2. 与远程建立连接 测试

   ```
   ssh -T git@github.com
   ```

3. 初始化仓库

   ```
   git init
   ```

4. clone远程至本地

   ```
   git clone git@github.com:用户名/仓库名.git
   ```

5. add 将修改的文件加入到暂存区（staging area）

   ```
   git add .		//可以将.换成指定的文件夹或者文件
   ```

6. commit 将暂存区的内容添加到本地仓库中

   ```
   git commit -m "注释"
   ```

7. push 将本地仓库中的内容推到远端仓库

   ```
   git push origin master
   ```

   