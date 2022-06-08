# param_backup
实验室设备 参数备份



### CUAV P9 配置 参数 备份

> 标签样式1

```
[C-RTK] P单->M多
M_20001 23456789
```

功能： 搭配 C-RTK&差分GPS地面站使用

配置数目：3个 (1p + 2M)  

--- ---
### 具体参数

### 1 地面基站


```
[C-RTK] P单->M多
P_1     23456789
```


```
 p900␍␊
 900MHz Mesh Radio Microhard Systems, Inc.␍␊
 v1.33 build 1.2232 Sep 27 2017 11:50:19␍␊
 MAC: 00:F0:49:00:AA:C0␍␊
 ␍␊
 E1  Q0  DCD &C1  DTR &D0  Handshaking &K0  DSR &S1␍␊
 Unit Address           S105=1                ␍␊
 Destination Address    S140=65535            ␍␊
 Reverse RSSI leds      S88=0            Operating Mode         S101=0␍␊
 Serial Baud Rate       S102=1           Wireless Link Rate     S103=1␍␊
 Network Address        S104=23456789    Hop Pattern            S106=0␍␊
 Hop Zone               S180=0           Output Power(dBm)      S108=30␍␊
 Hop Interval           S109=9           Data Format            S110=1␍␊
 Packet Min Size        S111=1           Packet Max Size        S112=256␍␊
 Packet Retransmissions S113=3           Repeat Interval        S115=3␍␊
 Character Timeout      S116=10          RSSI from Downlink(dBm)S124=N/A␍␊
 Network Type           S133=0           Repeaters Y/N          S141=0␍␊
 Serial Channel Mode    S142=0           Address Tag            S153=0␍␊
 FEC Mode               S158=7           Protocol Type          S217=0␍␊
 Input Framing          S218=0␍␊
 OK␍␊
```


--- ---

### 2 飞机端

```
[C-RTK] P单->M多
M_20001 23456789
```


```
 p900␍␊
 900MHz Mesh Radio Microhard Systems, Inc.␍␊
 v1.33 build 1.2232 Sep 27 2017 11:50:19␍␊
 MAC: 00:F0:49:00:AC:96␍␊

 E1  Q0  DCD &C1  DTR &D0  Handshaking &K0  DSR &S1␍␊
 Unit Address           S105=20001            ␍␊
 Destination Address    S140=1                ␍␊
 Reverse RSSI leds      S88=0            Operating Mode         S101=2␍␊
 Serial Baud Rate       S102=1           Wireless Link Rate     S103=1␍␊
 Network Address        S104=23456789    Hop Pattern            S106=0␍␊
 Hop Zone               S180=0           Output Power(dBm)      S108=30␍␊
 Hop Interval           S109=9           Data Format            S110=1␍␊
 Packet Min Size        S111=1           Packet Max Size        S112=256␍␊
 Packet Retransmissions S113=3           Repeat Interval        S115=3␍␊
 Character Timeout      S116=10          Roaming                S118=1␍␊
 RSSI from Uplink(dBm)  S123=N/A         Network Type           S133=0␍␊
 Serial Channel Mode    S142=0           Sleep mode             S143=0␍␊
 Address Tag            S153=0           FEC Mode               S158=7␍␊
 Protocol Type          S217=0           Input Framing          S218=0␍␊
 Sync timeout           S248=512␍␊
 OK␍␊
```
