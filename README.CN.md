JS UML 时序图
___
源自 https://github.com/bramp/js-sequence-diagrams 基础修改

适配 http://www.uml.org.cn/oobject/200503082.htm 

+ makefile增加http和命令检查
+ 增加对框架元件的支持

```
title 一个时序图
如果{ 块名
  "实例: 类"->服务: "调用\n换行,符号测试\->:,\r\n"
}否则{
  如果{
    Note right of 服务:备注
  }
}
```