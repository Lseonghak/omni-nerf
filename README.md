# OmniNeRF
Project page

## Installation
'''c
git clone https://github.com/cyhsu14/OmniNeRF.git
cd OmniNeRF
pip install -r requirements.txt
'''

## How to run
A pre-generated example image scene_03122_554516 is in the data directory. Simply run the script to start.
'''c
python run_nerf.py --config configs/st3d.txt
'''
You could also generate data from your own panorama. See the notebook Generate_data.ipynb for more details.

## Citation
The pytorch implementation of NeRF is helpful:

'''c
@misc{lin2020nerfpytorch,
  title={NeRF-pytorch},
  author={Yen-Chen, Lin},
  howpublished={\url{https://github.com/yenchenlin/nerf-pytorch/}},
  year={2020}
}
'''