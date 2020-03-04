### 原则: 所有参数和测试案例分离

参数化方式
--
* 直接指定数据
* 引用csv文件
* 引用自定义函数





本文件夹下各文件说明
--
* `login.json`是测试案例.
* `call_code.json` 直接在代码内定义了两个关联变量(`username`,`password`)的值,并调用测试案例`login.json`
* `call_csv.json` 引用csv文件定义关联变量,(`username`,`password`)的值,并调用测试案例`login.json`



