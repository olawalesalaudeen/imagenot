# Welcome to ImageNot

ImageNot is the code for [ImageNot: A contrast with ImageNet preserves model rankings](https://arxiv.org/pdf/2404.02112.pdf).

We have included the wnids for ImageNot classes (imagenot_classes.txt). We will not be hosting the ImageNot dataset but will release the code we used to generate the code - based on [LaionNet](https://github.com/alishiraliGit/eval-on-laion)'s construction [1].

Since ImageNot is simply a construction to test the external validity of ImageNet, not a dataset we expect to use outside of this purpose, wnids and LAION-5b [2] are sufficient to reproduce and build on our results.

[1] Shirali, A., & Hardt, M. (2023). What makes imagenet look unlike laion. arXiv preprint arXiv:2306.15769.<br>
[2] Schuhmann, C., Beaumont, R., Vencu, R., Gordon, C., Wightman, R., Cherti, M., ... & Jitsev, J. (2022). Laion-5b: An open large-scale dataset for training next generation image-text models. Advances in Neural Information Processing Systems, 35, 25278-25294.