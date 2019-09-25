# Adversarial Domain Adaptation

The following code has drawn inspiration from the following papers:

- *Ganin, Yaroslav, and Victor Lempitsky. "Unsupervised domain adaptation by backpropagation." arXiv preprint arXiv:1409.7495 (2014)*.

- *Li, Yanghao, Naiyan Wang, Jianping Shi, Jiaying Liu, and Xiaodi Hou. "Revisiting batch normalization for practical domain adaptation." arXiv preprint arXiv:1603.04779 (2016)*.

- *Tzeng, Eric, Judy Hoffman, Kate Saenko, and Trevor Darrell. "Adversarial discriminative domain adaptation." In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pp. 7167-7176. 2017*.

**The code is tested on the _Office-31_ dataset**

Download the dataset from this link *https://drive.google.com/file/d/0B4IapRTv9pJ1WGZVd1VDMmhwdlE/view*. Create a *domain_adaptation_images* directory under *Data/Office/* and place the downloaded images under it.

**Run _driver.py_**

example running code:

- *python driver.py --batch_size 32 --number_of_gpus 3 --lr_combined 0.00001 --num_iterations 5000*



