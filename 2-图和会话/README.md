**2-图和会话作业：**

1. 在一个notebook文件中构建一张图，实现两个数的加法操作，并在两个不同的会话中执行图。
2. 查找资料学习TensorFlow中执行常量基本运算API的基本用法，如`tf.add`、`tf.subtract`、`tf.multiply`、`tf.divide`、`tf.mod`、`tf.pow`、`tf.square`、`tf.sqrt`等的用法，并在notebook中演示其基本用法。

总结：

建立会话的方式常用有两种：tf.Session()和tf.InteractiveSession()

基本运算API：

| 操作                    | 描述                                                         |
| ----------------------- | ------------------------------------------------------------ |
| tf.add(x, y, name=None) | 求和                                                         |
| tf.sub(x, y, name=None) | 减法                                                         |
| tf.mul(x, y, name=None) | 乘法                                                         |
| tf.div(x, y, name=None) | 除法                                                         |
| tf.mod(x, y, name=None) | 取模                                                         |
| tf.abs(x, name=None)    | 求绝对值                                                     |
| tf.neg(x, name=None)    | 取负 (y = -x).                                               |
| tf.sign(x, name=None)   | 返回符号 y = sign(x) = -1 if x < 0; 0 if x == 0; 1 if x > 0. |
| tf.inv(x, name=None)    | 取反                                                         |
| tf.square(x, name=None) | 计算平方 (y = x * x = x^2).                                  |

  