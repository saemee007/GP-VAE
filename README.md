# GP-VAE

This repository provides datasets and code for preprocessing, training and testing models for reproducing the paper (by Choi Saemee & Karl Meisner Jensen in SKKU):

> [Diverse Text Generation via Variational Encoder-Decoder Models with Gaussian Process Priors](http://arxiv.org/abs/2204.01227) <br>
> Wanyu Du, Jianqiao Zhao, Liwei Wang and Yangfeng Ji <br>
> [ACL 2022 6th Workshop on Structured Prediction for NLP](http://structuredprediction.github.io/SPNLP22) <br>


![image](gpvae.png)



## Basic demo

For basic demo, please following instruction  


1. Clone the git repository
```
git clone https://github.com/saemee007/GP-VAE.git
```
2. Move `GP-VAE/models/pg/notebook/Group2-basic-02.ipynb` into your google drive.  
3. Run `Group-basic-01.ipynb` file

## Datasets
1. **Twitter URL** includes `trn/val/tst.tsv`, which has the following format in each line:
```
source_sentence \t reference_sentence 
```

## Citation
If you find this work useful for your research, please cite the original paper:

#### Diverse Text Generation via Variational Encoder-Decoder Models with Gaussian Process Priors
```
@article{du2022diverse,
  title={Diverse Text Generation via Variational Encoder-Decoder Models with Gaussian Process Priors},
  author={Du, Wanyu and Zhao, Jianqiao and Wang, Liwei and Ji, Yangfeng},
  journal={arXiv preprint arXiv:2204.01227},
  year={2022},
  url={https://arxiv.org/abs/2204.01227}
}
```
