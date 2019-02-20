# XiaoPE-nvme
## 介绍
XiaoPE所使用的nvme驱动，测试通过在Windows 10 PE。   
## 使用方法
推荐使用Dism++挂载PE的boot.wim后，添加驱动。添加时仅需选择主目录（XiaoPE-nvme）即可，Dism++会自动扫描并添加。   
本nvme驱动可能不能适用于部分品牌的nvme驱动器。你可以fork然后pr自己的驱动到此库来进行补充。