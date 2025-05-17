飞腾特制版，适用于D2000的笔记本和台式机

已在 长城TN140A2 (1.0) 上测试过 可正常使用网卡，鼠标，键盘

详情见：https://gitee.com/GXDE-OS/GXDE/issues/IAXCQ9

默认带6.6内核，可通过 sudo aptss install linux-kernel-phytium-gxde-arm64 降级到5.4内核，但需手动重新编译键鼠驱动，见 https://gitee.com/GXDE-OS/ft8042 按README操作即可

----

但也有报告在部分FT2000的机型上会导致固件损坏（六九零八厂/深圳电气，附带 JM7201 的笔记本）

不建议没有经验的用户在搭载了 FT2000 的机型尝试安装