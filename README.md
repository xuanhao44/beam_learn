# beam_learn

## [learn_beam_transforms_by_doing](learn_beam_transforms_by_doing.ipynb)

- Creating a `Pipeline`
- Creating a `PCollection`
- Performing basic `PTransforms`
  - Map
  - Filter
  - FlatMap
  - Combine
- Applications

## [learn_beam_basics_by_doing](learn_beam_basics_by_doing.ipynb)

- Simple UDF(Simple User-Defined Function) Transforms 简单的用户自定义函数的变换
  - ParDo & DoFn
  - Combine & CombineFn
- Composite Transforms 复合变换
  - 使用 Beam SDK 的内置复合变换
  - 创建您自己的复合转换（仅仅是组合或者嵌套转换，并没有改写）
  - 直接创建您自己的复合转换（继承 PTransform 类，重写 expand 方法）

## [learn_beam_windowing_by_doing](learn_beam_windowing_by_doing.ipynb)

- 理解批处理和流数据处理
- 简单的批处理作业
- 使用窗口，一次处理一定间隔的数据
