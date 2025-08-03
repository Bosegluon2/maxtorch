# maxtorch

maxtorch 是一个基于 PyTorch 2.6 的高阶模块库，收集了 PyTorch 官方未直接提供但在深度学习中常用的模块，如 ResidualBlock、UNet 等，方便快速搭建复杂神经网络结构。

## 主要特性

- ResidualBlock（残差块）
- UNet（分割网络）
- 兼容 PyTorch 2.6

## 安装

```bash
pip install .
```

## 用法示例

```python
from maxtorch.blocks import ResidualBlock
from maxtorch.models import UNet
``` 