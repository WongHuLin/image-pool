# 图片来源

在线图池：[image-pool / attention-evolution](https://github.com/WongHuLin/image-pool/tree/main/attention-evolution)。在线版 Markdown 中的 22 张图片均使用该公开仓库的 raw 链接；原始作者与出处保留如下。

正文共 22 张图片：13 张论文图、4 张教材／作者文章图、5 张本文自绘示意。原有四张论文图保持不变。本轮将 11 张自绘图替换为 12 张有出处的原图，其中 CSA/HCA 分别引用两张论文图。

网络原图保留内部标签；SVG 转 PNG 仅用于兼容显示。中文解释写在正文图注中，版权与使用许可遵循原始出处。Jay Alammar 的图片按原站 CC BY-NC-SA 4.0 许可署名引用。

| 文档图号 | 文件 | 作者／原图 | 原始出处 | 处理 |
|---|---|---|---|---|
| 图 01 | web_d2l_information_paths.png | Zhang、Lipton、Li、Smola，《动手学深度学习》，Figure 11.6.1 | [来源](https://d2l.ai/chapter_attention-mechanisms-and-transformers/self-attention-and-positional-encoding.html#fig-cnn-rnn-self-attention) | 原始 SVG 转为 PNG，未改图内内容 |
| 图 02 | web_jay_attention_output.png | Jay Alammar，The Illustrated Transformer，Self-Attention in Detail | [来源](https://jalammar.github.io/illustrated-transformer/#self-attention-in-detail) | 使用作者原始 PNG；图片按原站 CC BY-NC-SA 4.0 许可署名引用 |
| 图 03 | paper_transformer_architecture.png | Vaswani 等，Attention Is All You Need，Figure 1 | [来源](https://arxiv.org/html/1706.03762v7#S3.F1) | 使用论文 HTML 提供的原始 PNG |
| 图 04a | paper_transformer_multihead.png | Vaswani 等，Attention Is All You Need，Figure 2 右图 | [来源](https://arxiv.org/html/1706.03762v7#S3.F2) | 使用论文 HTML 单独提供的右侧原图 PNG |
| 图 04b | web_raschka_autoregressive.png | Sebastian Raschka，Understanding and Coding the KV Cache in LLMs from Scratch，Figure 1 | [来源](https://magazine.sebastianraschka.com/p/coding-the-kv-cache-in-llms) | 作者原始 PNG，未改图内内容；[原图](https://substack-post-media.s3.amazonaws.com/public/images/47afb112-1e46-42bf-80b3-b7b11d0a55eb_1804x1820.png) |
| 图 06 | web_hf_kv_cache.png | Raushan Turganbay／Hugging Face，Unlocking Longer Generation with Key-Value Cache Quantization，KV cache 示意图 | [来源](https://huggingface.co/blog/kv-cache-quantization) | 使用官方文章中的原始 PNG |
| 图 07 | paper_bigbird_figure1.png | Zaheer 等，Big Bird: Transformers for Longer Sequences，Figure 1（PDF 第 3 页） | [来源](https://arxiv.org/html/2007.14062v2#S1.F1) | 从原论文 PDF 以 300 dpi 提取图像区域，保留四个子图及标签 |
| 图 08 | paper_dsa_figure2.png | DeepSeek-AI，DeepSeek-V3.2，Figure 2 | [来源](https://arxiv.org/html/2512.02556v1#S2.F2) | 已有原图，保持不变；从 PDF 第 4 页提取 |
| 图 09 | paper_gqa_figure2.png | Ainslie 等，GQA，Figure 2 | [来源](https://arxiv.org/html/2305.13245v3#S2.F2) | 使用论文 HTML 提供的原始 PNG |
| 图 10 | paper_mla_figure3.png | DeepSeek-AI，DeepSeek-V2，Figure 3 | [来源](https://arxiv.org/html/2405.04434v5#S2.F3) | 已有原图，保持不变；论文原始 PNG |
| 图 11a | paper_v4_csa.png | DeepSeek-AI，DeepSeek-V4，Figure 3 | [来源](https://arxiv.org/html/2606.19348v1#S2.F3) | 论文原始 SVG 转为 PNG，未改图内内容 |
| 图 11b | paper_v4_hca.png | DeepSeek-AI，DeepSeek-V4，Figure 4 | [来源](https://arxiv.org/html/2606.19348v1#S2.F4) | 论文原始 SVG 转为 PNG，未改图内内容 |
| 图 14a | paper_nsa_figure2.png | Yuan 等，NSA，Figure 2 | [来源](https://arxiv.org/html/2502.11089v1#S2.F2) | 已有原图，保持不变；论文原始 PNG |
| 图 14b | paper_kimi_figure3.png | Kimi Team，Kimi Linear，Figure 3 | [来源](https://arxiv.org/html/2510.26692v1#S3.F3) | 已有原图，保持不变；从 PDF 第 6 页提取 |
| 图 15 | paper_csa2_modes.png | DeepSeek-AI，DeepSeek-V4.1-Flash，Figure 4 | [来源](https://arxiv.org/html/2609.19969v1#S2.F4) | 论文原始 SVG 转为 PNG，未改图内内容 |
| 图 16 | paper_rope_figure1.png | Su 等，RoFormer，Figure 1 | [来源](https://arxiv.org/html/2104.09864v5#S3.F1) | 论文原始 SVG 转为 PNG，未改图内内容 |
| 图 17 | paper_differential_attention.png | Ye 等，Differential Transformer，Figure 2 的结构图部分 | [来源](https://arxiv.org/html/2410.05258v1#S2.F2) | 使用论文单独提供的结构图 SVG 并转为 PNG，未改图内内容 |

## 保留的本文自绘图

| 图号 | 用途 | 保留原因 |
|---|---|---|
| 图 05a | 理论增长示意 | 按正文复杂度关系绘制，便于对照长度扩大与关系数量的增长；不是实测曲线。 |
| 图 05b | 显存对象对照 | 按本文的临时中间量与历史缓存口径整理，不对应某一篇论文的实验图。 |
| 图 12 | 历史记录与固定状态对照 | 用于配合本文矩阵方向和递推公式，说明记录数量与固定状态的区别。 |
| 图 13 | 记忆更新机制概览 | 按本文的六种更新方式整理，是跨方法的教学归纳。 |
| 图 18 | 多路线时间线 | 依据文末文献整理，覆盖多条并行路线，不表示未经证实的直接继承关系。 |

正文的 33 组独立公式使用可编辑 LaTeX 数学格式，公式不是图片。
