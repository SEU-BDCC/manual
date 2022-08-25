Pytorch
=================================

.. hint:: 更多样例代码尽在/seu_share/home/examples

.. toctree::
   :maxdepth: 2
   :caption: 目录:


1. 使用cp命令拷贝样例pytorch_mnist.sh到用户目录下。

.. code-block:: 

   cp /seu_share/home/examples/pytorch_mnist.sh ./ 

2. 使用cat命令查看脚本内容。

.. code-block:: 

   cat pytorch_mnist.sh
 
.. hint:: 脚本含义请查看常用命令

3. 使用bsub命令提交作业。

.. code-block:: 

   busb < pytorch_mnist.sh

提交作业后会返回jobid。

.. image:: ../images/software/pytorch/1.png
   :align: center

.. hint:: 正式使用请使用conda命令激活自己的环境，GPU作业不需要指定CPU核，不要在代码中指定GPU设备号，不要在脚本或代码中为CUDA_VISIBLE_DEVICES指定具体的值。


4. 使用bjobs查看作业状态。

.. image:: ../images/software/pytorch/2.png
   :align: center
 
5. 作业执行完成后会生成jobid.out文件。

.. image:: ../images/software/pytorch/3.png
   :align: center
