# Neural-Style-Transfer
PyTorch implementation from scratch of the original neural style transfer paper (https://arxiv.org/abs/1508.06576). The model was trained with a pretrained VGG19 CNN architecture using the Adam optimizer. A faster convergence was obtained using a second order L-BFGS optimizer. The faster convergence for L-BFGS can attritbuted to it's accounting of secon order information. Hessian approximations are built using a user-specified lookback memeory and gradient steps are taken.

More information on Adam and L-BFGS Optimizer for PyTorch can be found here: https://pytorch.org/docs/stable/optim.html
The original papers on Adam optimizer and L-BFGS algorithm are https://arxiv.org/abs/1412.6980 and https://link.springer.com/article/10.1007/BF01589116 respectively

Some of the images from the implementation are as below:

![download (1)](https://user-images.githubusercontent.com/71509604/106324382-09b52a80-6247-11eb-9530-e2602769ca10.png)

![download (2)](https://user-images.githubusercontent.com/71509604/106324410-16d21980-6247-11eb-9b4c-e273bd683a2a.png)


