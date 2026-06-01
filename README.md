# ECA-CMF Net

本仓库与已被 Electronics 接收的论文 “ECA-CMF Net: An ECA-Enhanced Conditional Modulation Fusion Network for Multimodal Sentiment Analysis” 相关。

## 论文信息

题目：ECA-CMF Net: An ECA-Enhanced Conditional Modulation Fusion Network for Multimodal Sentiment Analysis
作者：Shengyuan Yao, Shuxia Ren
期刊：Electronics
稿件编号：electronics-4324900

## 概述

ECA-CMF Net 是一个多模态情感分析框架，用于 CMU-MOSI 和 CMU-MOSEI 等基准数据集上的情感分类任务。该模型结合了 Efficient Channel Attention（ECA）和 Conditional Modulation Fusion（CMF），用于增强模态特定表征学习和自适应多模态融合。

## 代码可用性

源代码和实验配置文件目前正在整理中，之后将在本仓库中公开。

原始实验脚本中包含本地路径和与实验环境相关的设置。因此，我们目前正在对代码进行清理和文档整理，以在公开发布前提高代码的可读性和可复现性。

如需更多实现细节，可向通讯作者合理请求获得。

## 数据集

本文实验使用公开可获得的 CMU-MOSI 和 CMU-MOSEI 数据集。由于数据集许可和分发限制，原始数据集不会包含在本仓库中。

请从其官方来源获取数据集，并遵循相应的数据集使用政策。

## 可复现性

由于随机初始化、硬件差异、CUDA 版本以及数据预处理设置不同，实验结果可能存在轻微波动。主要实现文件、配置文件和使用说明将后续更新至本仓库。

## 引用

如果您认为本文工作有帮助，请引用我们的论文：

@article{yao2026ecacmf,
  title={ECA-CMF Net: An ECA-Enhanced Conditional Modulation Fusion Network for Multimodal Sentiment Analysis},
  author={Yao, Shengyuan and Ren, Shuxia},
  journal={Electronics},
  year={2026}
}

论文正式发表后，本仓库将更新完整引用信息。
