# Generative Modeling for 2D Data Synthesis

## Overview
This project explores advanced techniques in generative modeling using Denoising Diffusion Probabilistic Models (DDPM) and Denoising Score Matching (DSM) to synthesize 2D data. The models are trained on specially designed datasets including Pinwheel and Gaussian Mixtures to effectively capture complex data distributions.

## Project Files Description
- `dataset_generators.ipynb`: Jupyter notebook for generating training and test datasets.
- `DDPM.ipynb`, `DSM.ipynb`: Jupyter notebooks containing the implementation of the DDPM and DSM models.
- `DDPM_*`, `DSM_*`: Output files from the models including loss metrics and sample visualizations.
- `EE660_Final_Project_yuming.pdf`: Comprehensive project report detailing methodologies, results, and analyses.

## Models
### Denoising Score Matching (DSM)
- An enhanced DSM loss function is utilized, incorporating multiple noise realizations to reduce variance in the loss calculations.
- Training details and loss metrics are visualized in the output files labeled with `DSM_*`.

### Denoising Diffusion Probabilistic Models (DDPM)
- Implements a step-by-step denoising process with a linear noise scheduling from training through sampling.
- Check the `DDPM_*` files for detailed training logs and sample outputs.

## Dataset
- **Training and Test Data**: Each dataset consists of 2000 training samples and 500 test samples.
- Visualizations of the datasets can be found in the `*_samples_*.png` files, illustrating the data distribution the models were trained on.

## Results
- Training and test loss curves are provided for both models, indicating successful learning and generalization capabilities.
- Generated samples closely match the test distributions, showcasing the effectiveness of the models.

## How to Run
Ensure you have Jupyter installed and simply run the provided notebook files to replicate the models and see them in action.

## References
For in-depth technical details and theoretical background, please refer to the project report `EE660_Final_Project_yuming.pdf` and the references therein.