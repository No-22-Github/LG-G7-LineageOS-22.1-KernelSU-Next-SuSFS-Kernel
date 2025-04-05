# LG G7 LineageOS 22.1 KernelSU-Next SuSFS Kernel Flash Package  
适用于 LG G7 LineageOS 22.1 KernelSU-Next SuSFS 的内核刷机包

## Flash Instructions | 刷入方法
1. Reboot to recovery mode  
   将手机重启到 recovery 模式
2. Select `Apply update` --> `Apply from ADB`  
   选择 `Apply update` --> `Apply from ADB`
3. Connect device to PC via USB  
   将手机连接电脑
4. Flash via command:  
   使用命令刷入：
   ```bash
   adb sideload path/to/kernel_package.zip
   ```
5. When seeing warning about unsigned package, choose Yes  
    刷入时会警告刷机包没有签名，请选择 Yes

6. Install KernelSU Next app and verify SuSFS version on home page, then install SUSFS-FOR-KERNELSU module  
    安装 KernelSU Next，确认首页正确显示 SuSFS 版本，然后安装 SUSFS-FOR-KERNELSU 模块

7. Enjoy ! (^・ω・^ )

## Credits | 致谢

    LG G7 kernel source from LineageOS Team
    来自 LineageOS 团队的 LG G7 内核源码
    https://github.com/LineageOS/android_kernel_lge_sdm845

    KernelSU Next Project
    https://github.com/KernelSU-Next/KernelSU-Next

    SuSFS4KSU Implementation
    https://gitlab.com/simonpunk/susfs4ksu/-/tree/master?ref_type=heads

## Notes | 杂谈
The LG G7 truly has outstanding hardware - 2K LCD display, Hi-Fi chip (except battery life). Though it's starting to show its age in 2025, thanks to LineageOS team we can still run Android 15 smoothly.  
不得不承认 LG G7 有着出色的硬件：2K LCD 屏幕与 HIFI 芯片（除了电池）。虽然在 2025 年性能稍显过时，但感谢 LineageOS 团队让我们能流畅运行安卓 15。

This kernel build is based on the latest available source code (as of Feb 2025). While kernel updates may slow down in the future, it should remain functional for current systems. Remember to re-flash after major system upgrades.  
本内核基于最新可用源码构建（截至2025年2月）。虽然未来内核更新可能放缓，但当前版本应能持续稳定工作，进行系统大版本升级后请记得重新刷入。

Please report any bugs you encounter.  
如果发现 bug 请及时反馈。

Thanks for using!  
感谢你的使用！
