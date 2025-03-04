# Latest release 适用于macOS Sonoma 14.5 - Sequoia 15.4beta ( 仍推荐使用Ventura系列 )
### 可用功能： ( 玄学 )
- [x] 触控板 
- [x] 键盘 
- [x] 数字小键盘 
- [x] 内建显示器1920x1080 ( 开机有概率无法点亮➡️重启即可 )
- [x] fn快捷键（屏幕亮度调节可用） 
- [x] CPU 睿频 
- [x] CPU 温控 
- [x] 睡眠
- [x] WiFi ( itlwm + Heliport )
- [x] 以太网
- [x] Bluetooth ( 仅Sonoma下可用; Sequoia暂时无法驱动 )
- [x] Samsung 970 EVO Plus ( Trim损坏, 兼容性欠佳; 推荐使用WD )
- [x] USB-A & USB-C
- [ ] HDMI 
- [ ] NVIDIA RTX2060
- [ ] 隔空投送 (未测试)

## [Expired] 建议停留在Ventura13.7.x，后续macOS在逐步取消对Intel CPU的支持，驱动越发困难(玄学)，且此机型关闭DPTF后会严重影响Windows下的续航及散热。(END)
有实际需求可以购买白果
<br>

## Hackintosh-Lenovo-LEGION-y7000p-2020H
### <a href="https://github.com/xiaoMGitHub/LEGION_Y7000Series_Insyde_Advanced_Settings_Tools/releases" target="_blank"><span style="font-size: 12px">🚀y7000p一键修改BIOS</span></a>
## <a href="https://github.com/jerry-bit/Hackintosh-Lenovo-LEGION-y7000p-2020H/releases" target="_blank"><span style="font-size: 12px">🚀The Latest Version for Ventura13.6.1 - OpenCore v.0.9.7</span></a>
### （近期的releases均已添加三码）

<br>


### 近期将会更新OC0.9.7
### 更新至OpenCore0.9.4之后未出现触摸板失效问题
### 更新至macOS13.5.2后Wi-Fi启动速度(开机后或从睡眠中唤醒后)约为1min(明显变慢)，原因未知

### 硬件适配 Hardware adaptation

- [x] 触控板 🖱️Trackpad
- [x] 键盘 ⌨️Keyboard
- [x] 数字小键盘 ⌨️Numeric keypad
- [x] 原生显示器1920x1080 💻Original display 1920x1080
- [x] fn快捷键（屏幕亮度调节可用） 🖥️fn shortcut (screen brightness adjustment available)
- [x] Dolby sound 🎧
- [x] CPU 睿频 CPU turbo frequency
- [x] CPU 温控 CPU temperature control
- [x] 休眠 睡眠 💤Sleep
- [x] WiFi&有线网络 🛜WiFi& wired network (开机后不要切换网络连接)
- [x] Bluetooth ✂️
- [x] 屏蔽独显NVIDIA RTX2060 🚫Shielded graphic card NVIDIA RTX2060
- [x] 硬盘（建议使用Tuxera挂载NTFS硬盘）（未屏蔽pm981） 💾drive (Tuxera is recommended to mount NTFS drive) (unmasked pm981)
- [x] USB-A（USB-C未知） 📲USB-A (USB-C unknown)
- [ ] HDMI 
- [ ] NVIDIA RTX2060（你在想🍑） Are you kidding🤨
- [ ] 多设备互联（未测试） 🥳Multi-device interconnect (not tested)


拯救者y7000p-2020H专用黑苹果EFI，可用更新系统，隔空投送暂不可用（暂时没有测试），可用调节屏幕亮度(将OC更新至0.9.3版本后可以调节屏幕亮度)，触摸板偶发性失效，一般重启解决问题，其他一切正常(<del>启动Wi-Fi可能需要1～2分钟</del>)。<br>
Lenovo legion 7000p-2020H dedicated Hackintosh EFI, can update the system, airdrop is temporarily unavailable (No tests yet), occasional failure of the touchpad, usually solved by restarting, can adjust the screen brightness(after updating OC to version 0.9.3, you can adjust the screen brightness.), everything else is normal.<br>
CPU: i7-10875H<br>需要自己添加机型信息:)
<!-- ![截屏2023-02-26 19 08 05](https://user-images.githubusercontent.com/52237728/221407012-7a83ad2e-19ce-44f6-8770-fb1d10e54454.png)
![截屏2023-02-26 19 07 58](https://user-images.githubusercontent.com/52237728/221407016-76f04da7-94a3-4ec6-9d88-8c2fdd0e708b.png) -->
<br>

## DO NOT INSTALL THESE UPDATES
BIOS

<br>

### 请在系统设置中更新至macOS13.5
<br>

### <a href="https://github.com/jerry-bit/Hackintosh-Lenovo-LEGION-y7000p-2020H/releases/tag/v0.9.3-stable" target="_blank"><span style="font-size: 12px">🚀2023.07.15 [STABLE] UPDATE</span></a>
v0.9.3-stable
<br>

### <a href="https://github.com/jerry-bit/Hackintosh-Lenovo-LEGION-y7000p-2020H/releases/tag/opencore0.9.3" target="_blank"><span style="font-size: 12px">🚀2023.06.24 UPDATE</span></a>
可以成功通过“设置-通用-软件更新”更新至13.4.1版本，更新后在原有配置下，Wi-Fi启动速度明显快于之前（开机即用，但是开机后在睡眠中唤醒时需等待30s），将OC更新至0.9.3版本后可以调节屏幕亮度，暂未发现其他问题。<br>
You can successfully update to version 13.3.1 through "Settings General Software Update". After the update, under the original configuration, the Wi Fi startup speed is significantly faster than before (within 5 seconds, But when waking up during sleep after turning on, it takes 30 seconds to wait). After updating OC to version 0.9.3, you can adjust the screen brightness. no other issues have been found yet.<br>
<br>

### <a href="https://github.com/jerry-bit/Hackintosh-Lenovo-LEGION-y7000p-2020H/releases/tag/opencore0.9.1" target="_blank"><span style="font-size: 12px">🚀2023.04.10 UPDATE</span></a>
可以成功通过“设置-通用-软件更新”更新至13.3.1版本，更新后在原有配置下，Wi-Fi启动速度明显快于之前（30s内），暂未发现其他问题。<br>
You can successfully update to version 13.3.1 through "Settings General Software Update". After the update, under the original configuration, the Wi Fi startup speed is significantly faster than before (within 30 seconds), and no other issues have been found yet.<br>







<br>

