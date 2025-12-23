# LoRA_BERT
本项目围绕 BERT 在文本情感分类任务中的参数高效微调问题 展开，系统性地研究了 LoRA（Low-Rank Adaptation） 及其变体在实际下游任务中的性能表现与参数效率权衡。实验以 IMDb 电影评论和 GLUE-SST2 数据集为例，对比了 LoRA 微调、不同 rank 的消融实验、全参数微调（Full Fine-tuning）以及梯度感知的 Adaptive LoRA 方法，从实验角度验证了参数高效微调在真实任务中的可行性与优势。
