# 数据集下载链接
https://pan.baidu.com/s/1b9r8hVtwNDS8OmdORHiY7Q?pwd=am9z

### 文件命明方式
[entities|relations|properties].[apidoc|csnet|deepcs|dapim].jsonl
* entities - 实体文件
* relations - 关系文件
* properties - 属性文件
* apidoc - 从API文档中抽取的API知识
* csnet - 从CodeSearchNet提供的开源项目中抽取的API知识
* deepcs - 从DeepCS提供的开源项目中抽取的API知识
* dapim - 通过深度API变异（DAPIM）框架补全的API知识

### entities.XXX.jsonl文件
每一行通过列表存储了一个实体的信息，格式为：[实体类型, 实体名]

### relations.XXX.jsonl文件
每一行通过列表存储了一个关系的信息，格式为：[头实体名, 关系名, 尾实体名]

### properties.XXX.jsonl文件
每一行通过列表存储了一个属性的信息，格式为：[实体名, 属性名, 属性值]
