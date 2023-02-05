# MMCls_HW1

实战营作业1 使用 MMClassification 训练花卉图片分类模型

整理训练数据集，修改配置文件，基于 MMClassification 提供的预训练模型，在 flowers 数据集上完成分类模型的微调训练

（PS：我直接对imagenet.py中的class进行修改，不推荐这种做法）

基本结构

Backbone: MobileNetV2

Neck: GlobalAveragePooling

Head: LinearClsHead
