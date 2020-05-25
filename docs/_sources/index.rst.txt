.. worker-monitor documentation master file, created by
   sphinx-quickstart on Mon May 25 08:39:26 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

############################
worker-monitor documentation
############################

.. toctree::
   :maxdepth: 2
   :caption: Contents:

********
Overview
********

worker-monitorはWindows 10 PCの起動・停止時刻を自動取得・管理するソフトウェアです。

**********
Background
**********

1.監視されない環境野での勤務
==================================================

在宅ワークの学生や労働者は、上司に監視されない環境で仕事をする必要があります。そのため、出退勤時刻の情報操作をすることが可能となり、上司は出退勤時刻の実態を把握することが困難になります。

2.打刻ミスに起因する無駄な作業
==================================================

出退勤管理方法として、出勤・退勤した際は必ず打刻をし、その日の出退勤時刻を記録することが多いといえます。打刻に失敗した場合、後に打刻時刻修正の申請を行う必要があります。この申請に作業コストが取られることは、生産性がないため可能であれば避けたい作業であるといえます。

*******
Purpose
*******

PCの起動・停止時刻を取得し、その時間を出退勤時刻として自動記録するソフトウェアを提供します。

.. toctree::
   :maxdepth: 2
   :caption: System Archtecture

   /softwares/system_arch

.. toctree::
   :maxdepth: 2
   :caption: Softwares

   /softwares/client
   /softwares/server
   /softwares/infrastructure
   /softwares/portal

******************
Indices and tables
******************

* :ref:`genindex`
* :ref:`search`
