## Grok-1
这个仓库包含了用于加载和运行Grok-1开放权重模型的JAX示例代码。

确保下载检查点并将ckpt-0目录放在checkpoint中。然后，运行以下命令：

```
pip install -r requirements.txt
python run.py
```

来测试代码。

该脚本加载检查点并在测试输入上从模型中进行采样。

由于模型的巨大规模（314B个参数），需要具有足够GPU内存的计算机才能使用示例代码测试模型。此存储库中的MoE层的实现效率不高。选择这种实现是为了避免需要自定义内核来验证模型的正确性。

## 下载模型
您可以使用种子客户端和此磁铁链接下载Grok-1的模型数据：

magnet:?xt=urn:btih:5f96d43576e3d386c9ba65b883210a393b68210e&tr=https%3A%2F%2Facademictorrents.com%2Fannounce.php&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce

许可证
此版本中的代码和相关的Grok-1权重受Apache 2.0许可证的约束。该许可证仅适用于此存储库中的源文件和Grok-1的模型权重。
