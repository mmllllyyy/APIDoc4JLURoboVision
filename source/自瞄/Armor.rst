Armor API
==================

.. toctree::
   :maxdepth: 2
   :caption: Contents:


LightBar
---------


ArmorDetector
---------------


ArmorBox
----------


ArmorNumClassifier
-------------------

``void loadSvmModel(const char *model_path, Size armorImgSize = Size(40, 40))``
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

| brif: 
| 载入用于识别装甲板数字的模型

| param: 

* ``model_path``-模型地址
* ``armorImgSize``-模型图片尺寸,默认值为40*40

| return: ``None``