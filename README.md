# Clover
黑苹果引导

CLOVER-B250

适用于华硕B250M和微星B250I pro，个人配合使用的cpu是7400， HD630 或者使用独显白牌584 ， 该efi同样安装了占美4258U工控机，遗憾核显暂时没驱动

驱动情况：声网显都能直接驱动，核显会睡死， 独显无睡眠问题

注意事项：
使用核显安装：华硕主板可以直接使用该efi安装和启动，微星主板在安装时需临时关闭注入Intel显卡，启动则直接启动即可
使用独显安装：华硕可直接安装和启动（独显和核显可同时驱动）微星安装和启动需要在bios中关闭独显，否者Clover进入直接报错重启； 由于两个类型的主板分别使用了不同平台的网卡，可自行删除多余的

特此申明：该文件仅供用于学习参考，切勿用于商业用途，否者相关法律问题自行负责
