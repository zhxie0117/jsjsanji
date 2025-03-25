校园网连接
1.ip route
校园网内路由器：
0.0.0.0 0.0.0.0 下一跳路由器地址
校园网外的路由器：
校园网ip地址 校园网子网掩码（255.255.255.0） 下一跳路由器地址


2.crc
crc 32   给定16填16

3.bandwidth带宽

1gps=1000mbps=1000000kps

4.ip address：
202.112.8.195/30
ip：202.112.8.195
掩码30个1后面补0
这个路由器的ip地址 这个路由器的子网掩码

5 pos framing
pos framing sdh/sonet
给出什么写什么

6.pos flag
sonet填 s1s0 0
shd填 s1s0 2

7.lease
五小时三十分钟
0 5 30

8 network area
network 校园网ip地址 校园网反子网掩码
area 0 range校园网ip地址 校园网子网掩码

9.router ospf 
进程号一般是63

10.excluded-address
ip dhcp 49 excluded-address 221.89.23.200 221.89.23.254

