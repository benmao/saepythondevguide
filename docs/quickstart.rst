Quick Start 快速指引
==============================

Hello, world!
-----------------

创建新应用
~~~~~~~~~~~

http://sae.sina.com.cn/?m=myapp&a=create


检出svn代码
~~~~~~~~~~~~~

以应用blackfire为例::

    svn co https://svn.sinaapp.com/blackfire

创建index.wsgi
~~~~~~~~~~~~~~~~~

建一个目录1作为默认版本，在此下面新建文件 index.wsgi

::

   jaime@westeros:~/source/apps/blackfire$ mkdir 1
   jaime@westeros:~/source/apps/blackfire$ cd 1
   jaime@westeros:~/source/apps/blackfire/1$ touch index.wsgi
   jaime@westeros:~/source/apps/blackfire/1$ 

index.wsgi

.. literalinclude:: ../examples/blackfire/1/index.wsgi

提交代码
~~~~~~~~~~~~

::

    svn commit


访问应用
~~~~~~~~~~~~~~

http://blackfire.sinaapp.com


Notes:

svn用户名为sae安全邮箱

svn使用参考 http://sae.sina.com.cn/?m=devcenter&content_id=215&catId=212