# Fivem_Z-Framework_Server
Fivem 服务器自主开发的街头PVP框架, 具有文字扮演功能, 即插即用. [Z-Framework].base

脚本功能

-- 记录玩家的击杀/死亡次数.

适用性

-- 理论上可适用于任何框架, 但推荐搭配`z-framework`.

使用教程

1 - 将脚本放在你的资源文件夹中.

2 - 在`server.cfg`中添加`ensure z-kd`.

3 - 启用计数功能.

    针对于`z-framework`：
    
        在`z-base`脚本的`config.lua`中找到`EnableKD`, 并将其设置为`true`.
    
    针对于`standalone`或其他框架, 例如`esx`, `qb`, `qbox` ... (仅提供使用思路, 具体位置自行测试)：
    
        将`TriggerServerEvent('z-kd:playerDied')`, 放置于检测到玩家死亡的代码之后. 
    
4 - 享受😊

-- 效果预览

[Coming soon..]
