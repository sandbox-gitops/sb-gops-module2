# sb-gops-module2

sb-gops-module2 will have sb-gops-module2 as its subtree


~~~
$ git clone https://github.com/sandbox-gitops/sb-gops-module2.git
~~~
~~~
$ cd sb-gops-module2
~~~

add a subtree
~~~
$ git subtree **add** --prefix path/to/other https://github.com/sandbox-gitops/sb-gops-module1.git main **--squash**
~~~

pull any change from the subtree
~~~
$ git subtree **pull** --prefix path/to/other https://github.com/sandbox-gitops/sb-gops-module1.git main **--squash**
~~~

push any change back to the subtree
~~~
$ git subtree **push** --prefix subtreeDirectory https://github.com/newfivefour/vimrc.git master
~~~
