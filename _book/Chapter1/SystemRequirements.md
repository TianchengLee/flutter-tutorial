# 系统配置需求

## Windows平台

> To install and run Flutter, your development environment must meet these minimum requirements:
>
> - **Operating Systems**: Windows 7 SP1 or later (64-bit)
>
> - **Disk Space**: 400 MB (does not include disk space for IDE/tools).
>
> - Tools
>
>   : Flutter depends on these tools being available in your environment.
>
>   - [Windows PowerShell 5.0](https://docs.microsoft.com/en-us/powershell/scripting/setup/installing-windows-powershell) or newer (this is pre-installed with Windows 10)
>
>   - [Git for Windows](https://git-scm.com/download/win) 2.x, with the **Use Git from the Windows Command Prompt** option.
>
>     If Git for Windows is already installed, make sure you can run `git` commands from the command prompt or PowerShell.

官方建议:

* 操作系统： Windows7 SP1及以上 (64位)
* 硬盘空间：400MB (最低要求, 不包括IDE和其他的工具) 如果需要安装好完整的环境, 最好预留10G以上空间,多多益善嘛
* 其他工具：在你的环境中Flutter还需要依赖一些其他的工具
  * Windows PowerShell 5.0及以上(在Windows10系统中已预装)
  * Git for Windows 2.x

## macOS平台

> To install and run Flutter, your development environment must meet these minimum requirements:
>
> - **Operating Systems**: macOS (64-bit)
>
> - **Disk Space**: 700 MB (does not include disk space for IDE/tools).
>
> - Tools
>
>   : Flutter depends on these command-line tools being available in your environment.
>
>   - `bash`
>   - `curl`
>   - `git` 2.x
>   - `mkdir`
>   - `rm`
>   - `unzip`
>   - `which`

官方建议：

* 操作系统：macOS 64位
* 硬盘空间：700MB (同Windows, 多多益善)
* 其他工具：在macOS下进行开发还需要具备如下指令，确保能使用以下命令即可(打开一个terminal挨个输入一遍, 没有出现`command not found`字样的错误即可)
  * `bash`
  * `curl`
  * `git` 2.x
  * `mkdir`
  * `rm`
  * `unzip`
  * `which`

由于Windows的受众面更广泛，后续一切操作都是基于Windows平台进行，macOS用户大同小异

如果需要打包iOS平台的App，则需要使用macOS进行开发