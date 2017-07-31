### 数据回放

1、功能需求。

数据回功能以页面为单位，能够根据时间间隔获取到历史某个时间的设备数据，并且呈现在页面上。

2、前段代码开发流程和内容

在页面的顶部需要一个数据回放按钮。点击后可以弹出配置模态框\(组件名：DataPlayBack\)。配置内容包括 采样间隔、时间范围。将时间范围保存到localStorage中\( localStorage.playbackRange" = { "startTime":"YY-MM-DD HH:mm:ss","endTime":"YY-MM-DD HH:mm:ss"} \)。在点击确认配置后，显示时间轴控制框\(组件名：TimeShaft\)

