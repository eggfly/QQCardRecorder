﻿QQCardRecorder

QQ游戏“升级”的自动记牌器。

应用场景1：一边玩QQ游戏的升级，一边在python的运行环境里运行 recorder/SHENGJI.py。
该脚本可：
1. 实时自动记录每局出牌，并推演剩下什么牌。（记牌器功能）
2. 每局游戏结束时自动保存该局游戏到文件。

应用场景2：打完游戏后，把文件保存到 Dropbox 上。（需人工上传）

应用场景3：http://qqcardrecorder.azurewebsites.net/choose.html，从dropbox选择刚才保存上去的文件，即可复盘。（开发中）

文件结构：
root
|-	recoreder/: 用于记录牌局
|-	replayer/: 用于复盘牌局
|-	
|-	*.html: 用于复盘牌局的html。放在根目录是为了可以让azure自动部署，否则应该放在replayer/里的。
