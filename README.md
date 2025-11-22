SGuard Limiter
https://img.shields.io/github/license/luer4237/SGuardLimiter
https://img.shields.io/badge/Platform-Windows-blue
https://img.shields.io/badge/Language-PowerShell-blue

一个轻量级的PowerShell脚本，用于优化腾讯ACE（SGuard）反作弊进程的CPU资源占用，有效缓解游戏卡顿与系统延迟。

✨ 项目简介
当运行《英雄联盟》、《VALORANT》（无畏契约）等搭载腾讯ACE反作弊系统的游戏时，其后台服务（如 SGuard64.exe、SGuard64_1.exe）可能会持续进行高强度扫描，导致CPU占用率异常升高，进而引发游戏帧数不稳、系统卡顿或电脑发烫。

SGuard Limiter 通过智能调节相关进程的Windows系统调度策略（包括CPU优先级与处理器亲和性），在不干扰其核心反作弊功能的前提下，为您的系统“减负”，带来更流畅的游戏体验。

工作原理：脚本在游戏启动后自动定位ACE相关进程，并对其施加资源限制策略，使其不再过度抢占CPU资源。

📦 下载与使用
方法一：直接下载（推荐）
点击下方链接，下载项目中的PowerShell脚本文件：
📥 直接下载 SGuardLimiter.ps1

方法二：通过Git克隆
bash
git clone https://github.com/luer4237/SGuardLimiter.git
🚀 使用方法（三步搞定）
🎮 启动游戏：首先正常启动您的游戏（如《VALORANT》）。务必先执行此步，以确保ACE进程已被系统加载。

⚡ 运行脚本：直接双击运行下载的 SGuardLimiter.ps1 文件。

系统可能会弹出 “用户账户控制(UAC)” 窗口，请点击 “是” 以授予必要的管理员权限。

脚本将自动在后台执行，完成后窗口会自行关闭。

✨ 享受流畅：切回游戏，即可体验优化后的效果。

💡 重要提示：

请严格遵守 “先游戏，后脚本” 的执行顺序。

每次完全重启游戏后，都需要重新运行一次本脚本。

❓ 常见问题
Q: 运行脚本时安全软件报警，是否正常？
A: 这是正常现象。因为脚本会调用需要高权限的系统命令，部分安全软件会敏感地将其标记。本脚本开源透明，无任何恶意行为，请放心放行。

Q: 使用此脚本会导致游戏账号被封吗？
A: 不会。本脚本不修改任何游戏文件或内存数据，其原理与通过Windows任务管理器手动调整进程优先级完全相同，不存在任何封号风险。

Q: 脚本需要每次开机都运行吗？
A: 不需要。但需要在每次启动游戏后运行一次。

📜 许可证
本项目采用 MIT 许可证。

💬 支持与反馈
如果您在使用中遇到问题或有改进建议，欢迎在 GitHub Issues 中提出。

如果这个项目帮助了您，请考虑给它一个 ⭐Star，这是对开发者最大的鼓励！

Happy Gaming! 🎮