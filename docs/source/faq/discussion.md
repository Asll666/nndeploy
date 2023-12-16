# 开发者互相讨论

## mac
+ 不开启任何推理框架编译通过
+ 完善coreml
  + 代码
  + 编译
  + 调通yolov5
+ 调通mnn
  + 编译
  + 调通yolov5

## nndeploy 的 github ActionS
+ nndeploy采用github官网的Actions做编译的ci测试，出现了如下几个问题
  + mac下编译不通过，这个可能是mac下编译有问题
  + 无法每次push都进行一次编译测试

## mdc(这块写的很完善，不仅增加了推理框架mdc，还增加了设备mdc)（我不是很懂这块呀，大佬这是我这边的一些疑惑呀，方便约个时间讨论下吗）
+ 设备Mdc
  + 叫mdc是否合理呢？是不是要叫它本身的编程模型Ascend或者acl呢？（类似编程模型cuda、opencl）（这个host端的api跟cuda十分类似，这个是不是就是一种cuda兼容呀）
  + 是否可以在其他芯片上使用吗？（例如昇腾系列的芯片上）
+ 推理框架Mdc
  + 叫mdc是否合理呢？是不是要叫它本身的编程模型Ascend或者acl呢？ 与 CANN 是什么关系呀
  + 是否可以在其他芯片上使用吗？（例如昇腾系列的芯片上）
+ 华为有那些芯片可以进行推理呀
+ 这个与mindspore-lite是什么关系呀
+ 其他：
  + 变量名是 全部小写呀？
  + OrtValueInfo这个是不是改一下比较好呀