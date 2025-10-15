# 内存扫描Bypass




# 概述

内存免杀Demo. Just a demo.



# 动态

补一个动态

![360.gif](/resources/E95E40F3B3457A846BA79099CD5BC972.gif)



# Bypass内存扫描

Demo仅演示Bypass常用内存扫描工具，进程注入等风险Bypass这里未作演示。


针对的内存扫描工具：
- [BeaconEye](https://github.com/CCob/BeaconEye)

- [Hunt-Sleeping-Beacons](https://github.com/thefLink/Hunt-Sleeping-Beacons)

- [pe-sieve](https://github.com/hasherezade/pe-sieve)

- [moneta](https://github.com/forrest-orr/moneta)

- [MalMemDetect](https://github.com/waldo-irc/MalMemDetect)

- [Yara](https://github.com/virustotal/yara)

  

## 原理
主要使用的思路和技术包括：CS自带内存规避相关机制，静态特征修改、变异的sleepmask、开源UDRL以及beacon Patch。

现有一些开源UDRL，Beacon休眠时可以过BeaconEye，但执行post-ex任务还是会被检测。
e.g

![UDRL_BeaconEye.gif](/resources/F160C62AFF74389D8070D0637B8B3028.gif)


## Bypass Demo

![MemoryEvasion1.gif](/resources/71B781FC3839DCFE70BD4BF0DFF21E8B.gif)

