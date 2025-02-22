# PatternGen
> 支持 ida 9.0 （python3 建议 python3.11）, 低版本没有验证过,需要您自己验证<br>
> 将生成的特征码中的空格去掉，另将??更改为*<br>
> ida 特征码提取 火哥用的版本 （python 2.7 版本） 在此链接 https://github.com/hackflame/ida_python_extractCode<br>
> ida sig pattern generate pulgin<br>
> copy on plugins directory<br>
> shortcut key **alt+z**<br>
> 必须要 IDA Python
> 修复个bug 去他妈的四舍五入
### 更新兼容Python3 和最新的ida 7.5
![image-20220405155554551](https://gitee.com/Canliu/picgo/raw/master/picgo/image-20220405155554551.png)

```
===========================================================================
MiDeletePteRun+5E Address:0x140346ede Offset:0x346ede

===========================================================================
MiDeletePteRun+1F8 Address:0x140347078 Offset:0x347078
 48 89 ?? ?? ?? 4D 8B E2 4C 89 ?? ?? 49 8B FA E8 ?? ?? ?? ?? 48 8B D8 48 ?? ?? ?? ?? ?? ?? ?? ?? ?? 48 ?? ?? ?? 48 23 D8 48 ?? ?? ?? ?? ?? ?? 0F ?? ?? ?? ?? ??
```

![2](https://gitee.com/Canliu/picgo/raw/master/picgo/2.gif)
