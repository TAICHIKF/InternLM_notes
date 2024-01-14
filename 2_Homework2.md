# (2) 轻松玩转书生·浦语大模型趣味Demo

# 笔记+作业2

参考：[https://github.com/InternLM/tutorial/blob/main/helloworld/hello_world.md](https://github.com/InternLM/tutorial/blob/main/helloworld/hello_world.md)

# 目录

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled.png)

## 1 大模型的概念

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%201.png)

## InternLM 轻量级训练框架

开源的两个预训练模型：InternLM-7B和InternLM-20B

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%202.png)

### InternLM-7B

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%203.png)

### Lagent：智能体框架

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%204.png)

## **2 InternLM-Chat-7B 智能对话 Demo**

按照[https://github.com/InternLM/tutorial/blob/main/helloworld/hello_world.md](https://github.com/InternLM/tutorial/blob/main/helloworld/hello_world.md)教程下载模型，代码后，执行demo：

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%205.png)

[https://github.com/InternLM/tutorial/issues/334](https://github.com/InternLM/tutorial/issues/334)

疑问：为什么有八个文件：

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%206.png)

运行`streamlit run web_demo.py --server.address 127.0.0.1 --server.port 6006`打开浏览器界面：

作业：**基础作业**• 使用 InternLM-Chat-7B 模型生成 300 字的小故事（需截图）。

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%207.png)

## **3 Lagent 智能体工具调用 Demo**

Lagent 是一个轻量级、开源的基于大语言模型的智能体（agent）框架，支持用户快速地将一个大语言模型转变为多种类型的智能体，并提供了一些典型工具为大语言模型赋能。通过 Lagent 框架可以更好的发挥 InternLM 的全部性能。

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%208.png)

作业：**进阶作业**• 完成 Lagent 工具调用 Demo 创作部署（需截图）

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%209.png)

## **4. 浦语·灵笔图文理解创作 Demo**

按照教程安装环境、下载模型和代码后（复制环境很慢，同步下载模型和代码），运行：

```haskell
cd /root/code/InternLM-XComposer
python examples/web_demo.py  \
    --folder /root/model/Shanghai_AI_Laboratory/internlm-xcomposer-7b \
    --num_gpus 1 \
    --port 6006
```

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%2010.png)

作业：**进阶作业**• 完成浦语·灵笔的图文理解及创作部署（需截图）

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%2011.png)

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%2012.png)

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%2013.png)

保存文章后，把下载的图像上传测试另一功能：

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%2014.png)

## **5. 通用环境配置**

[https://help.mirrors.cernet.edu.cn/](https://help.mirrors.cernet.edu.cn/)

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%2015.png)

### 模型下载

**使用huggingface_hub下载一直timeout：**

运行“export HF_ENDPOINT=[https://hf-mirror.com”](https://hf-mirror.xn--com-9o0a/) 添加镜像源就可以解决。

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%2016.png)

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%2017.png)

作业：**基础作业-**使用 `huggingface_hub` python 包，下载 `InternLM-20B` 的 config.json 文件到本地（需截图下载过程）

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%2018.png)

![Untitled]((2)%20%E8%BD%BB%E6%9D%BE%E7%8E%A9%E8%BD%AC%E4%B9%A6%E7%94%9F%C2%B7%E6%B5%A6%E8%AF%AD%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B6%A3%E5%91%B3Demo%20bccbc3d6830242c8af297f5e89cb27c7/Untitled%2019.png)