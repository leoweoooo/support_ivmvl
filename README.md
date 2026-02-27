<p align="center">
<img src="https://github.com/NICALab/SUPPORT/blob/main/logo-1.png" width="120" alt="SUPPORT Logo">
</p>

<h3 align="center">SUPPORT, a self-supervised denoising method for voltage imaging data.</h3>

<p align="center">
<img src="thumbnail.png" width="80%"/>
</p>

<p align="center">
<a href="https://www.nature.com/articles/s41592-023-02005-8" target="_blank"><b>Paper</b></a> | 
<a href="https://doi.org/10.5281/zenodo.8176722" target="_blank"><b>Data</b></a>
</p>

## Citation
Eom, M. et al. [Statistically unbiased prediction enables accurate denoising of voltage imaging data.](https://www.nature.com/articles/s41592-023-02005-8) *Nature Methods* (2023).
```
@article{eom2023statistically,
  title={Statistically unbiased prediction enables accurate denoising of voltage imaging data},
  author={Eom, Minho and Han, Seungjae and Park, Pojeong and Kim, Gyuri and Cho, Eun-Seo and Sim, Jueun and Lee, Kang-Han and Kim, Seonghoon and Tian, He and B{\"o}hm, Urs L and others},
  journal={Nature Methods},
  pages={1--12},
  year={2023},
  publisher={Nature Publishing Group US New York}
}
```

## 🍴 About this fork of SUPPORT
SUPPORT (Statistically Unbiased Prediction Utilizing Spatiotemporal Information in Imaging Data) is a **self-supervised denoising method** for **voltage imaging data**, as published in "[**_Nature Methods_**](https://www.nature.com/articles/s41592-023-02005-8)". This fork modifies on the original code for better integration with our lab's workflow. 


## 📦 Installing Dependencies
All the dependencies are pre-installed for the _intern_ user. 
If you'd like to install SUPPORT for your own user environment, please try the following.
#### 1. Install Miniconda (IF **conda** is not available)
```
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash ~/Miniconda-latest-Linux-x86_64.sh
source ~/.bashrc
```
#### 2. Clone this repository
```
git clone https://github.com/leoweoooo/support_ivmvl.git
cd support_ivmvl
```
#### 3. Create the conda environment
```
conda env create -f env.yml
```
#### 4. Activate the conda environment
```
conda activate support
```
