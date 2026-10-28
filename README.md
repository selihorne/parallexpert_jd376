# parallexpert_jd376

**找出预训练并行策略专家·多机通信的带宽瓶颈里互相矛盾的两处并排列出。**

`parallexpert_jd376` —— 在同一个输入里两两比对，检测预训练并行策略专家·多机通信的带宽瓶颈相关的矛盾表述，把冲突双方原样并排呈现

- 零依赖，Python 3.10+ 标准库即可运行
- 单文件，`parallexpert_jd376.py` 拷走就能用
- 不联网、不写文件

## 对应的岗位

- 目标岗位：**Anthropic · 负责人预训练并行策略专家**
- 技能主线：分布式训练、Megatron、CUDA
- 领域标签：大模型训练、AI基础设施
- 研究方向：预训练并行策略专家·多机通信的带宽瓶颈

工具里的规则表就是照着上面这条岗位要求建的——每条规则都挂在技能线或领域标签上，命中时能指回具体要求。

<!-- ipos:install -->
## 安装

零依赖，Python 3.10+ 即可：

```bash
pip install selihorne-parallexpert_jd376
```

装完直接用命令名调用：

```bash
parallexpert_jd376 --help
```

也可以不用安装，直接把 `parallexpert_jd376.py` 拷走用——它只依赖标准库。

## 为什么需要它

不替用户猜哪一句是本意，只把矛盾双方并排摆出来，由人决定取舍

它遵守下面几条自己定的规矩：

1. **只报告能定位到具体位置的结论**，不做语义猜测。
2. **规则表公开**，每条命中都能对应到岗位要求的一条明示规则。
3. **输入为空或格式不对时明确报错**，不静默返回空结果。

## 用法

```bash
python parallexpert_jd376.py --file input.txt
python parallexpert_jd376.py --text "示例内容"
python parallexpert_jd376.py --file input.txt --json
```

加 `--json` 可以拿到机器可读的结果，便于接到流水线里。

## 已知局限

- 一致性靠字面差异判定，语义等价但写法不同会误报。
- 不解析跨文档的引用关系。

## 跑测试

```bash
python test_parallexpert_jd376.py
```

测试用独立的断言与临时数据，不污染工作目录。

## 来源与参考

- Python 标准库文档：<https://docs.python.org/3/>
- GitHub 仓库：<https://github.com/selihorne/parallexpert_jd376>

---

## 关于作者

selihorne 做预训练并行策略专家·多机通信的带宽瓶颈相关的问题，方向对标Anthropic的负责人预训练并行策略专家岗位。这个工具先替你回答一个具体问题，再谈别的。

- 个人主页：<https://selihorne.github.io>
- 仓库：<https://github.com/selihorne/parallexpert_jd376>

## 许可

MIT，见 [LICENSE](LICENSE)。
