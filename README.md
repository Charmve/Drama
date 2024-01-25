# Drama
Improve LLM inference throughout


## 机器学习编译

MLC-机器学习编译 https://space.bilibili.com/1663273796/channel/collectiondetail?sid=499979

## 大模型推理-2-推理引擎和服务性能优化

针对推理性能和服务吞吐量的优化，我们从三个角度开展：推理引擎层、服务层优化以及量化技术。
- 推理引擎层主要是针对计算性能进行优化，例如KernelFusion、KV-Cache、FlashAttention、TP+PP、PagedAttention等技术；
- 服务层优化主要关注吞吐量的提升，包括Dynamic-Batching、Continous-Batching等技术。此外，还有针对特定场景的优化技术，例如流式、交互式及持续生成，以及长序列推理等。
- 模型量化方面主要涉及Weight-Only、int8、int4以及KV-Cache量化等。

### Continuous Batching
- Continuous Batching https://zhuanlan.zhihu.com/p/676109470?utm_psn=1727339188318552065
- 

### PagedAttention

- 深入浅出理解PagedAttention CUDA实现 https://zhuanlan.zhihu.com/p/673284781

### FlashAttention
- 大模型训练加速之FlashAttention系列：爆款工作背后的产品观 https://zhuanlan.zhihu.com/p/664061672
- 大模型推理加速之Flash Decoding：更小子任务提升并行度 https://zhuanlan.zhihu.com/p/664061672
- FlashDecoding++ https://www.zhihu.com/question/615218061/answer/3280478544?utm_psn=1727364310857318401


大语言模型推理加速技术：模型压缩篇 https://zhuanlan.zhihu.com/p/667455383?utm_psn=1727364780136800258
