<br/>
### 感谢

本插件是在`辛鑫`同学的原创基础上，进行了针对Grafana7.x版本的重构开发，在此感谢`辛鑫`同学的个人付出与贡献

<hr/>

<br/>
### 插件作用

- 这是一个Chrome插件，可以用来对接grafana，并完成特定图表的人工语音报警提醒

- master分支只兼容grafana7.x版，grafana6.x版本的插件参见当前仓库的grafana-6.x分支

<br/>
### 使用教程

- 克隆本仓库到本机目录

```shell
git clone https://github.com/tay3223/grafana-x.git
```

- 打开Chrome浏览器，点击`浏览器设置`---`更多工具`---`扩展程序`打开`扩展程序`界面

- 打开右上角`开发者模式`的开关

- 然后点击左侧的`加载已解压的扩展程序`，此时在弹出的本地路径中，找到`grafana-x`这个目录选中并确认，此时就会把本仓库的这个目录加载到Chrome的插件中

- 打开本地部署好的Grafana，选择想要监控的大屏开始监控即可

<br/>
### 需要注意的点

由于本插件在底层调用了`Google Text-to-Speech`语音合成服务，因此请保证您安装该插件的`浏览器`可以顺利的访问到Google服务
     
> - 怎样才算的上可以顺利连接到Google的服务呢？     
> - 至少能用上Google的搜索引擎吧，你们懂的~（＾▽＾）
