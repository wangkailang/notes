1. 在 Github 中创建一个仓库，比如 [notes](https://github.com/wangkailang/notes)
2. 安装 [Obsidian Git](https://github.com/denolehov/obsidian-git/wiki/Installation)插件
3. 在 Obsidian 当前目录创建一个文件夹，比如 github_notes
4. 打开 Obsidian 命令面板，输入 clone，选择 `Clone an existing remote repo`
5. 粘贴远程仓库地址，我是用的是 ssh 格式 `git@github.com:wangkailang/notes.git`
6. 此时会发现 github_notes 目录下已经同步远程仓库
7. 修改 github_notes 信息，打开 Obsidian 命令面板，输入 backup，选择 `Obsidian Git: Create backup` 此时修改会备份到 Github 指定仓库