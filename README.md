**MTPNet**



🔗 Permanent Resources

​​Paper​​: Frequency-Domain Prompt Guided Hybrid Mamba-Transformer for Enhanced Nighttime Flare Removal

Jiajun Wu, Bo Wang

The Visual Computer (2025)

​​Code Repository​​: https://github.com/xumengsheng/mtpnet-main

🔍Method

**📄 Abstract** 

Nighttime imaging often suffers from lens flare, significantly degrading image quality. Addressing this, we propose MTPNet, a Mamba-Transformer hybrid network guided by frequency-domain prompts, for effective nighttime flare removal. MTPNet integrates the strengths of Mamba and Transformer architectures, introducing an adaptive frequency-domain prompt block to dynamically suppress flare-related frequency components. A feature correlation module fuses encoder and prompt features through dual spatial and channel attention mechanisms. Experiments on real-world and synthetic datasets demonstrate MTPNet's superior performance, improving flare-specific metrics (G-PSNR and S-PSNR) and delivering visually clearer results. This approach offers a robust solution for nighttime image restoration tasks. The source code are available at: https://github.com/xumengsheng/mtpnet-main.

🐍Environments

The project is built with Python 3.10, Pytorch 1.7.0, CUDA 11.7

📁Data
Flare7K++ consists of Flare7K and Flare-R. Flare7K offers 5,000 scattering flare images and 2,000 reflective flare images, consisting of 25 types of scattering flares and 10 types of reflective flares. Flare-R offers 962 real-captured flare patterns. https://pan.baidu.com/share/init?surl=iNomlQuapPdJqtg3_uX_Fg&pwd=nips

The background images are sampled from [Single Image Reflection Removal with Perceptual Losses, Zhang et al., CVPR 2018]. We filter our most of the flare-corrupted images and overexposed images. https://pan.baidu.com/share/init?surl=BYPRCNSsVmn4VvuU4y4C-Q&pwd=zoyv


If you want to use Flare7K++ for training, please use:

python basicsr/train.py -opt options/uformer_flare7kpp_baseline_option.yml


📊Evaluation Code

You can run the evaluate.py

📖 Citation

This work is currently under review. Please check back for the final citation details.

@article{Wu2025MTPNet,

title={Frequency-Domain Prompt Guided Hybrid Mamba-Transformer for Enhanced Nighttime Flare Removal},

author={Jiajun Wu and Bo Wang},

journal={Under Review at The Visual Computer},

year={2025},

note={Manuscript submitted for publication}

}

Contact
If you have any question, please feel free to reach me out at 12023130662@stu.nxu.edu.cn.
