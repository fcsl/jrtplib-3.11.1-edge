# jrtplib-3.11.1-edge


1、增加RTPSession::SendRTCPRRPacket(const char *data, size_t len, const char* ip, unsigned short port )方法，支持给指定地址发送rtcp包
2、该接口发送rtcp包的源端口为接收rtp端口
