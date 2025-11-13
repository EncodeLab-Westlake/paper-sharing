# Paper List

<!-- <details> -->
<!-- <summary><h2>Oct. 31, 2025</h2></summary> -->
# Oct. 31, 2025
## Efficiency in Large Language Models
Presenter: [Wenjie](https://kurt232.github.io/)

### KV Cache Compression
|paper|conference|date|institution|group|
|---|---|---|---|---|
|[H2O: Heavy-Hitter Oracle for Efficient Generative Inference of Large Language Models](https://arxiv.org/abs/2306.14048)|NeurIPS'23|June 23|CMU|Beidi Chen|
|[SnapKV: LLM Knows What You Are Looking for before Generation](https://arxiv.org/abs/2404.14469)|NeurIPS'24|Apr 24|UIUC| Deming Chen|
|[R-KV: Redundancy-aware KV Cache Compression for Reasoning Models](https://arxiv.org/abs/2505.24133)|NeurIPS'25|May 25|UWisconsin|Junjie Hu|
|[PyramidInfer: Pyramid KV Cache Compression for High-throughput LLM Inference](https://arxiv.org/abs/2405.12532)|ACL'24 Findings|May 24|SJTU|Hai Zhao|
|[CAKE: Cascading and Adaptive KV Cache Eviction with Layer Preferences](https://arxiv.org/abs/2503.12491)|ICLR'25|Mar 25|Ant|Jianguo Li|
|[Model Tells You What to Discard: Adaptive KV Cache Compression for LLMs](https://arxiv.org/abs/2310.01801)|ICLR'24|Oct 23|MSR|Jianfeng Gao|
|[Not All Heads Matter: A Head-Level KV Cache Compression Method with Integrated Retrieval and Reasoning](https://arxiv.org/abs/2410.19258)|ICLR'25|Oct 24|MSR|Wen Xiao|
|[DuoAttention: Efficient Long-Context LLM Inference with Retrieval and Streaming Heads](https://arxiv.org/abs/2410.10819)|ICLR'25|Oct 24|MIT|Song Han|
|[RazorAttention: Efficient KV Cache Compression Through Retrieval Heads](https://arxiv.org/abs/2407.15891)|ICLR'25|July 24|Huawei|Gongyi Wang|
|[Cache Me If You Can: How Many KVs Do You Need for Effective Long-Context LMs?](https://arxiv.org/abs/2506.17121)|arXiv|June 25|Princeton|Danqi Chen|
|[Which Heads Matter for Reasoning? RL-Guided KV Cache Compression](https://arxiv.org/abs/2510.08525)|arXiv|Oct 25|Westlake|Huan Wang|

### Sparse Attention
|paper|conference|date|institution|group|
|---|---|---|---|---|
|[Efficient streaming language models with attention sinks](https://arxiv.org/abs/2309.17453)|ICLR’24|Sept 23|MIT|Song Han|
|[MInference 1.0: Accelerating Pre-filling for Long-Context LLMs via Dynamic Sparse Attention](https://arxiv.org/abs/2407.02490)|NeurIPS’24|July 24|MSR|Lili Qiu|
|[Quest: Query-Aware Sparsity for Efficient Long-Context LLM Inference](https://arxiv.org/abs/2406.10774)|ICML’24|June 24|MIT|Song Han|
|[Native Sparse Attention: Hardware-Aligned and Natively Trainable Sparse Attention](https://arxiv.org/abs/2502.11089)|ACL'25 (best paper award)|Feb 25|DeepSeek-AI|DeepSeek-AI|

### Efficiency for Training
|paper|conference|date|institution|group|
|---|---|---|---|---|
|[Your Efficient RL Framework Secretly Brings You Off-Policy RL Training](https://fengyao.notion.site/off-policy-rl#279721e3f6c48032af82d31498e49c5d)|blog|Aug 25|MS|Jianfeng Gao|
|[On-Policy Distillation](https://thinkingmachines.ai/blog/on-policy-distillation/)|blog|Oct 25|Thinking Machines Lab|Thinking Machines Lab|

## LLM Kernel Generation
Presenter: [Haolei](https://scholar.google.com/citations?user=CGh99DUAAAAJ&hl=zh-CN)

### Benchmark
|paper|conference|date|institution|group|
|---|---|---|---|---|
|[KernelBench: Can LLMs Write Efficient GPU Kernels?](https://arxiv.org/abs/2502.10517)|ICML’25|14 Feb 2025|Stanford|Azalia Mirhoseini|
|[TritonBench: Benchmarking large language model capabilities for generating triton operators](https://arxiv.org/abs/2502.14752)|ACL Findings’25|20 Feb 2025|THUNLP|Maosong Sun|

### Prompt Engineering
|paper|conference|date|institution|group|
|---|---|---|---|---|
|[CUDA-LLM: LLMs Can Write Efficient CUDA Kernels](https://arxiv.org/abs/2506.09092)|arXiv|10 Jun 2025|SJTU|An Zou|

### Reinforcement Learning
|paper|conference|date|institution|group|
|---|---|---|---|---|
|[Kevin: Multi-Turn RL for Generating CUDA Kernels](https://arxiv.org/abs/2507.11948)|ES-FoMo-III Workshop @ICML’25|16 Jul 2025|Stanford, Cognition AI|Cognition AI|
|[AutoTriton: Automatic Triton Programming with Reinforcement Learning in LLMs](https://arxiv.org/abs/2507.05687)|arXiv|8 Jul 2025|THUNLP|Maosong Sun|

### Agent
|paper|conference|date|institution|group|
|---|---|---|---|---|
|[Astra: A Multi-Agent System for GPU Kernel Performance Optimization](https://arxiv.org/abs/2509.07506)|DL4C workshop @NeurIPS’25|9 Sep 2025|Stanford|Stanford|

### Dataset
|paper|conference|date|institution|group|
|---|---|---|---|---|
|[ConCuR: Conciseness Makes State-of-the-Art Kernel Generation](https://arxiv.org/abs/2510.07356)|aXiv|8 Oct 2025|Westlake|Huan Wang|

### Other Resources
### Models
|model|parameter|institution|
|---|---|---|
|[KernelLLM](https://huggingface.co/facebook/KernelLLM)|8B|Meta|
|[cudaLLM](https://huggingface.co/facebook/KernelLLM)|8B|ByteDance|
### Related Blogs
[How Many Agents Does it Take to Beat PyTorch?](https://letters.lossfunk.com/p/how-many-agents-does-it-take-to-beat)  

<!-- <details> -->
<!-- <summary><h2>Nov. 06, 2025</h2></summary> -->
# Nov. 06, 2025
## Large Language Models Quantization
Presenter: [Mingluo](https://github.com/sunshine-0903)

### Datatype
|paper|date|
|---|---|
|[Microscaling Data Formats for Deep Learning](https://arxiv.org/abs/2310.10537)|Oct. 23|
|[NVFP4](https://developer.nvidia.com/blog/introducing-nvfp4-for-efficient-and-accurate-low-precision-inference)|Jan. 25|

### Scaling
|paper|conference|date|institution|group|
|---|---|---|---|---|
|[AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration](https://arxiv.org/abs/2306.00978)|MLSys'24|June 2023|MiT|Song Han|
|[SmoothQuant: Accurate and Efficient Post-Training Quantization for Large Language Models.](https://arxiv.org/abs/2211.10438)|ICML'24|Nov. 2022|MiT|Song Han|
|[OmniQuant: Omnidirectionally Calibrated Quantization for Large Language Models](https://arxiv.org/abs/2308.13137)|ICLR'24|Aug. 2023|Shanghai AI Laboratory|Luo Ping|


### Rotation
|paper|conference|date|institution|group|
|---|---|---|---|---|
|[AffineQuant: Affine Transformation Quantization for Large Language Models](https://arxiv.org/abs/2403.125446)|ICLR'24|March 2024|XMU|Rongrong Ji|
|[QuIP#: Even Better LLM Quantization with Hadamard Incoherence and Lattice Codebooks](https://arxiv.org/abs/2403.125446)|ICML'24|March. 2024|Cornell|Albert Tseng|
|[QuaRot: Outlier-Free 4-Bit Inference in Rotated LLMs](https://arxiv.org/abs/2404.00456)|NeurIPS'24|Apr. 2024|ETH|Saleh Ashkboos|
|[DuQuant: Distributing Outliers via Dual Transformation Makes Stronger Quantized LLMs](https://arxiv.org/abs/2406.01721)|NeurIPS'24|June 2024|ZJU|Ying Wei|
|[SpinQuant: LLM quantization with learned rotations](https://arxiv.org/abs/2406.01721)|ICLR'25|June 2024|Facebook|Tijmen Blankevoort|
|[FlatQuant: Flatness Matters for LLM Quantization](https://arxiv.org/abs/2410.09426)|ICML'25|Oct. 2024|Tsinghua|Jun Yao|

<!-- </details> -->
