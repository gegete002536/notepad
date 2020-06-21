## kinpin：命令行解析器

kinpin:流式(fluent-interface )、类型安全的命令行解析工具

[^fluent-interface]: verbose = kingpin.Flag(&quot;verbose&quot;, &quot;Verbose mode.&quot;).Short(&#39;v&#39;).Bool()，这种风格即流式接口风格

## 调试参数设置

```
// 设置pprof分析时阻塞事件的采样速率，1表示记录每个阻塞事件
SetBlockProfileRate(1)
// 设置pprof分析时mutex分析中的锁采样速率
SetMutexProfileFraction()
```

