# Version 0

使用 uv 虚拟环境。

测试了下载 sherpa-onnx：

```
uv pip install sherpa-onnx

```

然后根据 sherpa-onnx 的官方文档下载模型 sherpa-onnx-streaming-zipformer-bilingual-zh-en-2023-02-20 至model文件夹下并测试

[官方文档链接](https://k2-fsa.github.io/sherpa/onnx/pretrained_models/online-transducer/zipformer-transducer-models.html#sherpa-onnx-streaming-zipformer-bilingual-zh-en-2023-02-20)


注意我这里的下载 sherpa-onnx 的方式是 pip install，官方文档应该是拉了 github 仓库再用 cmake 构造出来可执行文件。所以我们命令行里面直接输入 sherpa-onnx 即可。

test-wav 文件夹下的内容都测试过了， 大致没什么问题。

---

# Version 1

调整了一下文件夹目录结构，增加了 FunASR 的简单安装和测试。

[官方仓库地址](https://github.com/modelscope/FunASR)

基于 README.md 简单测试了一下命令行测试非流式的 ASR。
