# NettyHelloworld


1、netty服务端hello world案例

SimpleChannelHandler 处理消息接收和写
{
	messageReceived接收消息

	channelConnected新连接，通常用来检测IP是否是黑名单

	channelDisconnected链接关闭，可以再用户断线的时候清楚用户的缓存数据等
}

2、netty客户端hello world案例

channelDisconnected与channelClosed的区别？

channelDisconnected只有在连接建立后断开才会调用
channelClosed无论连接是否成功都会调用关闭资源
