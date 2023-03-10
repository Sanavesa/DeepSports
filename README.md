# Action Quality Assessment using Transformers

We present the official PyTorch implementation of our research paper titled "Action Quality Assessment using Transformers". This repository contains the PyTorch code that can be utilized for both training and testing of our proposed transformer-based model. Our model offers an innovative method for evaluating action quality and has achieved performance levels comparable to the current state-of-the-art approaches.

## Paper
Action quality assessment (AQA) is an active research problem in video-based applications that is a challenging task due to the score variance per frame. Existing methods address this problem via convolutional-based approaches but suffer from its limitation of effectively capturing long-range dependencies. With the recent advancements in Transformers, we show that they are a suitable alternative to the conventional convolutional-based architectures. Specifically, can transformer-based models solve the task of AQA by effectively capturing long-range dependencies, parallelizing computation, and providing a wider receptive field for diving videos? To demonstrate the effectiveness of our proposed architectures, we conducted comprehensive experiments and achieved a competitive Spearman correlation score of 0.9317. Additionally, we explore the hyperparameters effect on the model's performance and pave a new path for exploiting Transformers in AQA.

For the full paper, click [here](https://arxiv.org/abs/2207.12318).

## License
The licensing terms for our work are governed by the [MIT license](LICENSE). [TimeSformer](https://github.com/facebookresearch/TimeSformer), on the other hand, is subject to the CC-NC 4.0 International license. Nonetheless, specific sections of the project fall under distinct licensing terms, such as [SlowFast](https://github.com/facebookresearch/SlowFast) and [pytorch-image-models](https://github.com/rwightman/pytorch-image-models), which are licensed under the Apache 2.0 license.

## Acknowledgements
This project is built on top of [TimeSformer](https://github.com/facebookresearch/TimeSformer), [PySlowFast](https://github.com/facebookresearch/SlowFast), and [pytorch-image-models](https://github.com/rwightman/pytorch-image-models). Our gratitude goes to the authors for sharing their code. In case you utilize our model, we kindly request you to also acknowledge these works by citing them.

```BibTex
@inproceedings{gberta_2021_ICML,
    author  = {Gedas Bertasius and Heng Wang and Lorenzo Torresani},
    title = {Is Space-Time Attention All You Need for Video Understanding?},
    booktitle   = {Proceedings of the International Conference on Machine Learning (ICML)}, 
    month = {July},
    year = {2021}
}
```

```BibTeX
@misc{fan2020pyslowfast,
  author =       {Haoqi Fan and Yanghao Li and Bo Xiong and Wan-Yen Lo and
                  Christoph Feichtenhofer},
  title =        {PySlowFast},
  howpublished = {\url{https://github.com/facebookresearch/slowfast}},
  year =         {2020}
}
```

```BibTeX
@misc{rw2019timm,
  author = {Ross Wightman},
  title = {PyTorch Image Models},
  year = {2019},
  publisher = {GitHub},
  journal = {GitHub repository},
  doi = {10.5281/zenodo.4414861},
  howpublished = {\url{https://github.com/rwightman/pytorch-image-models}}
}
```
