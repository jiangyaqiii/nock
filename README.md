# nock



# 查看钱包余额

nockchain-wallet --nockchain-socket .socket/nockchain_npc.sock update-balance

quinn_proto::connection：表示正在通过 QUIC 协议 进行连接（用于 libp2p 传输）；

got Data packet ... from IP：说明你在接收数据包，连接多个节点；

received RequestResponse + Request received：表示节点成功接收并处理了请求；

block by-height: Ok(27)：本地节点查询第 27 个区块，返回成功；

error: Timeout：个别节点响应超时，这是 P2P 网络中的正常波动，不是错误；

ACK ArrayRangeSet([217..223])：发送数据确认响应，链路活跃；

Waiting for recv on next effect：NockApp 驱动在等待下一轮数据或指令；
