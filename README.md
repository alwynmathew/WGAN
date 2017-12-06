# Wasserstein GAN
Pytorch implementation of WGAN 

dataset = 'mnist' <br />
epoch = 25 <br />
batch_size = 64 <br />
sample_num = 16 <br />
save_dir = './models' <br />
result_dir = './results' <br />
log_dir = './logs' <br />
lrG = 0.0002 <br />
lrD = 0.0002 <br />
beta1 = 0.5 <br />
beta2 = 0.999 <br />
<br />
c = 0.01  clipping value <br />
n_critic = 5  the number of iterations of the critic per generator iteration
