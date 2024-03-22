# voxinimity
LPC voice anonymization project - Skoltech ML 2024

This is the repo for the team project LPC based voice anonymization.

Repository contains 3 approaches:
- McAdams
- S2T+TTS
- VCGAN

## Used Data
```
Data was used to evaluate models is https://www.openslr.org/12
```
## Before run
```
pip install -r requirements.txt 
```

## Project structure:
```
.
├── s2t_baseline.ipynb      # S2T+TTS notebook
├── McAdams_baseline.ipynb  # McAdams LPC notebook
├── vc_gan                  # VCGAN directory
├── requirements.txt        # Requirements file
├── demo                    # Demo audio files
├── Literature              # Papers we used in this project
└── README.md
```

## Running the project
```
One can run the project code with opening it with Google Colab or Conda Environment Jupyter Notebook on their own device.

However, the implementation of CycleGAN is based on regular python files, and so that to run the CycleGAN-based method, one has to run `python3 vc_gan/main.py [params]` to achieve the desired output.
```
