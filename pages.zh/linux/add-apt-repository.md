# add-apt-repository

> apt 仓库管理。
> 更多信息：<https://manned.org/add-apt-repository>.

- 添加一个新的 APT 仓库：

`add-apt-repository {{指定仓库}}`

- 移除一个 APT 仓库：

`add-apt-repository {{[-r|--remove]}} {{指定仓库}}`

- 添加一个仓库并更新缓存：

`add-apt-repository --update {{指定仓库}}`

- 允许从指定仓库下载源码：

`add-apt-repository {{[-s|--enable-source]}} {{指定仓库}}`
