
# SoftMatch

Official repo for "SoftMatch: Addressing the Quantity-Quality Trade-off in Semi-Supervised Learning", accepted by ICLR 2023. [[Arxiv]](https://arxiv.org/abs/2301.10921)[[Open Review]](https://openreview.net/forum?id=ymt1zQXBDiF&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICLR.cc%2F2023%2FConference%2FAuthors%23your-submissions))


# Code and Results

We publish our code in both [USB](https://github.com/microsoft/Semi-supervised-learning) and [TorchSSL](https://github.com/TorchSSL/TorchSSL). All Results and training logs are also included. This repo only serves as a re-direction and provides more explanation for the results reported in paper.

Note that, the experiments and results of Table 1 was conducted using TorchSSL since back then USB has not supported classic setting yet. Other results are from USB. 

USB indeed well support classic setting now and SoftMatch has similar performance in USB classic setting.


# Cite Us
```
@article{chen2023softmatch},
  title={SoftMatch: Addressing the Quantity-Quality Trade-off in Semi-supervised Learning},
  author={Chen, Hao and Tao, Ran and Fan, Yue and Wang, Yidong and Wang, Jindong and Schiele, Bernt and Xie, Xing and Raj, Bhiksha and Savvides, Marios},
  booktitle={International Conference on Learning Representations (ICLR)},
  year={2023}
}

@article{wang2023freematch},
  title={FreeMatch: Self-adaptive Thresholding for Semi-supervised Learning},
  author={Wang, Yidong and Chen, Hao and Heng, Qiang and Hou, Wenxin and Fan, Yue and and Wu, Zhen and Wang, Jindong and Savvides, Marios and Shinozaki, Takahiro and Raj, Bhiksha and Schiele, Bernt and Xie, Xing},
  booktitle={International Conference on Learning Representations (ICLR)},
  year={2023}
}

```
