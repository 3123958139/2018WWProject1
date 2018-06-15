

# GItHub创建分支及本地Git更新分支方法

- GitHub创建分支

  - 先克隆master分支到本地

  ~~~
  git clone https://github.com/3123958139/WolframProjects.git
  ~~~

  - 通过git bash创建分支

    - 查看分支情况

    ~~~
    git branch
    ~~~

    - 创建新分支

    ~~~
    git branch branch1
    ~~~

  - 本地分支同步到远程
    - 切换到新分支

    ```
    git checkout branch1
    ```

    - 同步到github线上

    ~~~
    git push -u origin branch1
    ~~~

  - 远程分支同步到本地

    - 得到master远程地址，在本地master文件夹内git bash同步分支

    ~~~
    git clone -b branch1 https://github.com/3123958139/WolframProjects.git
    ~~~

  - 其他的add commit push操作一致，需要注意的是你要checkout到你具体的分支进行

# Wolfram项目参见分支

- branch1

