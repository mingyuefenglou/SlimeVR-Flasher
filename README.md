# SlimeVR-Flasher

SlimeVR SlimeNRF 系列追踪器的烧录 / OTA 上位工具（规划中）。

## 目标

- 对 NiNi SlimeNRF 生态追踪器的 USB 直连烧写（UF2 / CDC）
- ESB OTA：经接收器对追踪器无线升级（协议参考上游 esb_ota.py 与 ota-web，MIT）
- 固件产物按板型识别与版本管理

## 状态

工具本体开发中，当前请使用：

- 刷写：UF2 U 盘模式（进 bootloader 后拖 `.uf2`）
- OTA：[ota-web](https://smol-ota.jtcat.com)（WebHID）或上游 `esb_ota.py`

## 相关

- [mingyuefenglou/SlimeVR-Tracker-nRF](https://github.com/mingyuefenglou/SlimeVR-Tracker-nRF)
- [mingyuefenglou/SlimeVR-Receiver-nRF](https://github.com/mingyuefenglou/SlimeVR-Receiver-nRF)
- [mingyuefenglou/Adafruit_nRF52_Bootloader](https://github.com/mingyuefenglou/Adafruit_nRF52_Bootloader)
