OpenMPI
=================================

.. hint:: 更多样例代码尽在/seu_share/home/examples

.. toctree::
   :maxdepth: 2
   :caption: 目录:


1. 使用cp命令拷贝样例openMPI.sh到用户目录下。

.. code-block:: 

   cp /seu_share/home/examples/openMPI.sh ./ 

2. 使用cat命令查看脚本内容。

.. code-block:: 

   cat openMPI.sh
 
.. hint:: 脚本含义请查看常用命令

3. 使用bsub命令提交作业。

.. code-block:: 

   busb < openMPI.sh

提交作业后会返回jobid。

.. image:: ../images/software/openmpi/1.png
   :align: center

.. hint:: normal_test队列仅供测试使用，正式使用请选择其他队列。

4. 使用bjobs查看作业状态。

.. image:: ../images/software/openmpi/2.png
   :align: center
 
5. 作业执行完成后会生成jobid.out文件。

.. image:: ../images/software/openmpi/3.png
   :align: center
