================
8.0 裸机系统配置
================

单独的用户镜像部署到物理机之后，大部分情况下并不能直接使用，
我们需要对系统做一些配置，例如网络配置，分区修改等。

本章我们介绍使用  ``config drive`` + ``cloud-init`` 来配置系统。

.. NOTE::

    如果是 windows 系列的系统，使用 ``cloudbase-init``
