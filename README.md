# Conda 虚拟环境使用指南
本文档介绍了如何使用 Conda 虚拟环境来隔离和管理不同的 Python 环境和依赖项。
- 安装 Conda
首先需要安装 Conda 包管理器。您可以访问 Conda 官方网站 下载并安装 Miniconda 或 Anaconda。

- **创建虚拟环境**
使用以下命令创建一个新的虚拟环境：
    ```lua
    conda create --name myenv python=3.8
    ```
    这将创建一个名为 myenv 的虚拟环境，并在其中安装 Python 3.8。
- **激活虚拟环境**
使用如下命令激活虚拟环境：
    ```lua
    conda activate myenv
    ```
    在激活虚拟环境后，您可以安装和运行 Python 应用程序。
- **安装 Python 包**
在虚拟环境中安装 Python 包时，只有在该虚拟环境中安装的包才可以被使用。您可以使用一下命令来安安装包：
    ```lua
    conda install package_name
    ```
    其中 package_name 是要安装的包的名称。
- **列出虚拟环境中分包**
要查看虚拟环境中安装的所有包，可以使用以下命令：
    ```lua
    conda list
    ```
- **查看虚拟环境**
如果你想查看当前所有的虚拟环境列表，可以在终端中输入以下命令：
    ```lua
    conda info --envs
    ```
- **查看当前虚拟环境**
如果你想查看当前所有的虚拟环境列表，可以在终端中输入以下命令：
    ```lua
    conda info --env
    ```
- **结论**
希望本文档可以帮助您了解如何使用 Conda 虚拟环境来隔离和管理 Python 环境和依赖项。如果您有任何疑问或意见，请随时提出。

