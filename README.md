# OnlineLogViewer
用于在线查看日志，切换日志输出级别，输出目标等

log-open是基于spring boot的库项目，切换到项目根目录运行 gradlew jar。将生成的jar引入到spring boot项目即可使用。此jar依赖rabbitMQ，需要在MQConfig类里面配置相关信息，参考类的说明

OnlineLogViewer是C#项目，为日志查看的客户端，需要修改LogMessageQueue.cs中的MQ配置信息