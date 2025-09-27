**MTPNet**



🔗 Permanent Resources

​​Paper​​: Frequency-Domain Prompt Guided Hybrid Mamba-Transformer for Enhanced Nighttime Flare Removal

Jiajun WU, Bo Wang

The Visual Computer (2025)

​​Code Repository​​: https://github.com/xumengsheng/mtpnet-mian

If you want to use Flare7K++ for training, please use:

python basicsr/train.py -opt options/uformer_flare7kpp_baseline_option.yml

Evaluation
You can run the evaluate.py

Flare7k++ structure

├── Flare7K

    ├── Reflective_Flare 
    
    ├── Scattering_Flare
    
         ├── Compound_Flare
         
         ├── Glare_with_shimmer
         
         ├── Core
         
         ├── Light_Source
         
         ├── Streak
         
├── Flare-R

	├── Compound_Flare
  
	├── Light_Source
  
├── test_data

     ├── real
     
          ├── input
          
          ├── gt
          
          ├── mask
          
     ├── synthetic
     
          ├── input
          
          ├── gt
          
	  ├── mask
    


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
