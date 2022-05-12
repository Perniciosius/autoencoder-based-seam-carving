# Autoencoder based Seam Carving
Seam Carving with energy map generation using deep convolutional autoencoders.

### Dataset Used
https://www.kaggle.com/datasets/jaygupta2k/energy-map-dataset

## Hardware Specification used for model training
It is recommended to run the model training on either Google Colab or Kaggle with GPU enabled.

- 3 Core CPU
- 13 Gigabytes of RAM
- Nvidia Tesla P100 GPU


## Instructions
Make sure the dataset is available in the `../input/` directory or modify the code in model_training notebook.

## Required python libraries
1. tqdm
2. NumPy
3. OpenCV
4. SciPy
5. Tensorflow

## Model Training and Seam Carving
1. Open the model_training notebook and execute all the cells in sequence.
2. The trained model will be stored in the `model_joined_gen/` directory.
3. Open the seam_carving notebook and modify the scale variable, input file path as required.
4. Execute all cells of the notebook.
5. The energy map generated using the model will be available in the file named `energy_map_inital.png`.
6. The final energy map after carving will be available in the file named `energy_map.png`.
7. Carved image will also be saved in the same directory.